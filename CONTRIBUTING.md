<div align="center">

# 🤝 Contributing to EazyDeals

**Developed by Syed Muhammad Tayyab**

</div>

Thanks for wanting to improve EazyDeals! 🎉

## 🧭 Workflow
1. **Fork** the repo and create a branch: `git checkout -b feature/short-name`
2. Set up locally using [`docs/SETUP.md`](docs/SETUP.md).
3. Make your change — keep commits small and focused.
4. Test the pages you touched on **Tomcat 10.1 + MySQL 8**.
5. Open a **Pull Request** using the template.

## ✍️ Commit style
Use [Conventional Commits](https://www.conventionalcommits.org/):

| Prefix | Use for |
|---|---|
| `feat:` | new feature |
| `fix:` | bug fix |
| `docs:` | documentation only |
| `style:` | CSS / formatting |
| `refactor:` | code change without behaviour change |
| `security:` | hardening |

## 🧑‍💻 Code guidelines
- Java: 4-space/tab indentation as in existing files, `com.eazydeals.<layer>` packages.
- Keep SQL in DAO classes; use `PreparedStatement` — never string-concatenate user input.
- JSP: reuse `Components/` includes instead of duplicating navbar or CSS/JS links.
- **Never commit real DB or SMTP passwords.**

## 🗄️ Database changes
If you change the schema, update `database/eazydeals.sql` and `docs/DATABASE.md` in the same PR.
