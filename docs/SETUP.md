<div align="center">

# 🚀 EazyDeals — Local Setup Guide

**Developed by Syed Muhammad Tayyab**

</div>

## 1. Install the tools

| Tool | Version | Notes |
|---|---|---|
| JDK | 17+ | `java -version` should print 17 or higher |
| Apache Tomcat | **10.1.x** | Tomcat 9 will **not** work (code uses `jakarta.*`) |
| MySQL Server | 8.0+ | plus MySQL Workbench if you like a GUI |
| Eclipse IDE for Enterprise Java | latest | or IntelliJ IDEA Ultimate |
| `mysql-connector-j` | 8.0.31+ | download from dev.mysql.com |

## 2. Database

```bash
mysql -u root -p -e "CREATE DATABASE IF NOT EXISTS eazydeals;"
mysql -u root -p eazydeals < database/eazydeals.sql
```

Or in Workbench: **Server → Data Import → Import from Self-Contained File** → `database/eazydeals.sql` → target schema `eazydeals`.

## 3. Connection settings

Edit `src/main/java/com/eazydeals/helper/ConnectionProvider.java`:

```java
DriverManager.getConnection("jdbc:mysql://localhost:3306/eazydeals", "<user>", "<password>");
```

## 4. Email (Gmail SMTP)

1. Turn on **2-Step Verification** on the sender Google account.
2. Create an **App Password** (Google Account → Security → App passwords).
3. Edit `src/main/java/com/eazydeals/helper/Mail.java` and set `emailId` and `password`.

Leave them blank to run without email — the app still works, sending just fails silently in the console.

## 5. MySQL driver

Copy `mysql-connector-j-8.x.jar` into `src/main/webapp/WEB-INF/lib/`.

## 6. Run in Eclipse

1. **File → Import → General → Existing Projects into Workspace** → choose the repo folder.
2. **Window → Preferences → Server → Runtime Environments → Add → Apache Tomcat v10.1**.
3. Right-click the project → **Properties → Targeted Runtimes** → tick Tomcat 10.1.
4. Right-click → **Run As → Run on Server**.
5. Visit `http://localhost:8080/E-Commerce-Website/`.

## 7. Demo accounts

| Role | Email | Password |
|---|---|---|
| Admin | `test@gmail.com` | `abc123` |
| User | `test786@gmail.com` | `abc123` |

## 🧯 Troubleshooting

| Symptom | Fix |
|---|---|
| `ClassNotFoundException: com.mysql.cj.jdbc.Driver` | Add the MySQL connector JAR (step 5) |
| `Access denied for user 'root'@'localhost'` | Wrong DB user/password in `ConnectionProvider` |
| `Unknown database 'eazydeals'` | Run step 2 |
| `jakarta.servlet` classes not found | You're on Tomcat 9 — use Tomcat 10.1 |
| Product images missing | Image files aren't in the repo; re-upload via admin panel into `Product_imgs/` |
| Emails not arriving | Use a Gmail **App Password**, check spam folder |
| Port 8080 in use | Change the HTTP connector port in Tomcat's `server.xml` |
