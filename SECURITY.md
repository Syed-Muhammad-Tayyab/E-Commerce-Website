<div align="center">

# 🔐 Security Policy

**Developed by Syed Muhammad Tayyab**

</div>

EazyDeals is an **educational project**. It works well as a demo, but the following must be fixed before handling real customers or money.

## ⚠️ Known weaknesses

| # | Issue | Where | Recommended fix |
|---|---|---|---|
| 1 | Passwords stored in **plain text** | `user`, `admin` tables · `UserDao`, `AdminDao` | Hash with BCrypt / Argon2; compare hashes on login |
| 2 | DB credentials hard-coded (`root` / `root`) | `helper/ConnectionProvider.java` | Read from env vars or a Tomcat JNDI `DataSource` in `context.xml` |
| 3 | SMTP credentials in source | `helper/Mail.java` | Env vars + Google App Password; never commit them |
| 4 | Single shared static JDBC `Connection` | `ConnectionProvider` | Use a connection pool (HikariCP / Tomcat JDBC pool) |
| 5 | No CSRF protection on forms | all POST forms | Add per-session CSRF tokens |
| 6 | Admin pages rely on session checks in JSP | `admin.jsp`, `display_*.jsp` | Central auth `Filter` for `/admin*` routes |
| 7 | File uploads not type/size checked | `AddOperationServlet` | Whitelist image MIME types, cap size, randomise filenames |
| 8 | OTP has no expiry / attempt limit | `ChangePasswordServlet` | Expire after ~5 min, lock after N tries |
| 9 | Mock payment page | `checkout.jsp` | Use a real gateway with server-side verification |
| 10 | Sample accounts in SQL dump | `database/eazydeals.sql` | Remove or change before deployment |

## 📬 Reporting a vulnerability
Please **don't open a public issue** for security problems. Contact the maintainer privately through [GitHub](https://github.com/Syed-Muhammad-Tayyab) with steps to reproduce; you'll get a response as soon as possible.
