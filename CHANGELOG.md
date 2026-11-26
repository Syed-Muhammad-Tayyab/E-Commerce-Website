# 📝 Changelog

*Developed by Syed Muhammad Tayyab*

## [2.0.0] — 2026-11-26 · Repository redesign
### ✨ Added
- Fully decorated `README.md` (animated banner, gallery, Mermaid diagrams, setup, FAQ, roadmap)
- `docs/` — `SETUP.md`, `DATABASE.md`, SVG assets (banner, divider, module map)
- GitHub Actions workflow that compiles the sources and uploads a WAR artifact
- Issue templates, PR template, `CONTRIBUTING.md`, `CODE_OF_CONDUCT.md`, `SECURITY.md`
- `.gitignore`, `.editorconfig`
- `src/main/webapp/Product_imgs/` folder so image uploads have a target directory

### 🔧 Changed
- SQL dump moved to `database/eazydeals.sql`
- Removed compiled `build/classes/` output from version control

### 🐞 Fixed
- Removed three `web.xml` mappings (`AddressServlet`, `RemoveAddressServlet`, `AdminLoginServlet`) that pointed to classes not present in the source

## [1.0.0] — Original release
- EazyDeals e-commerce app (JSP · Servlet · JDBC · MySQL) by Anirudh Kumar Bhagat
