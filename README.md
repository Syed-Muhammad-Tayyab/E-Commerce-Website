<!-- ═══════════════════════════ HEADER ═══════════════════════════ -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0b1a3a,50:123a8a,100:2874f0&height=130&section=header&text=Developed%20by%20Syed%20Muhammad%20Tayyab&fontSize=30&fontColor=ffffff&fontAlignY=38&animation=fadeIn" width="100%" alt="Developed by Syed Muhammad Tayyab"/>

<img src="docs/assets/banner.svg" width="100%" alt="EazyDeals E-Commerce Website banner"/>

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Poppins&weight=700&size=24&duration=3200&pause=900&color=2874F0&center=true&vCenter=true&multiline=false&width=760&height=50&lines=%F0%9F%9B%92+EazyDeals+%E2%80%94+Online+Shopping+Platform;%E2%98%95+Java+17+%7C+JSP+%7C+Servlet+%7C+JDBC;%F0%9F%9B%A0%EF%B8%8F+Full+Admin+Panel+%2B+Order+Management;%E2%9C%89%EF%B8%8F+Email+Alerts+%2B+OTP+Password+Reset" alt="Typing SVG"/></a>

<!-- badges row 1 : stack -->
<p>
<img src="https://img.shields.io/badge/Java-17-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
<img src="https://img.shields.io/badge/JSP%20%2F%20Servlet-Jakarta%20EE%2010-2874F0?style=for-the-badge&logo=eclipseide&logoColor=white"/>
<img src="https://img.shields.io/badge/Tomcat-10.1-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=black"/>
<img src="https://img.shields.io/badge/MySQL-8.0-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/Bootstrap-5.3-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white"/>
<img src="https://img.shields.io/badge/jQuery-3.7-0769AD?style=for-the-badge&logo=jquery&logoColor=white"/>
</p>

<!-- badges row 2 : repo -->
<p>
<img src="https://img.shields.io/github/stars/Syed-Muhammad-Tayyab/E-Commerce-Website?style=flat-square&color=ffe500&logo=github"/>
<img src="https://img.shields.io/github/forks/Syed-Muhammad-Tayyab/E-Commerce-Website?style=flat-square&color=2874f0&logo=github"/>
<img src="https://img.shields.io/github/last-commit/Syed-Muhammad-Tayyab/E-Commerce-Website?style=flat-square&color=22c55e"/>
<img src="https://img.shields.io/github/repo-size/Syed-Muhammad-Tayyab/E-Commerce-Website?style=flat-square&color=38bdf8"/>
<img src="https://img.shields.io/github/actions/workflow/status/Syed-Muhammad-Tayyab/E-Commerce-Website/build.yml?style=flat-square&label=build"/>
<img src="https://img.shields.io/badge/PRs-welcome-ff69b4?style=flat-square"/>
<img src="https://komarev.com/ghpvc/?username=Syed-Muhammad-Tayyab-ecommerce&label=Views&color=2874f0&style=flat-square"/>
</p>

<!-- nav -->
<p>
<a href="#-overview"><b>📖 Overview</b></a> •
<a href="#-features"><b>✨ Features</b></a> •
<a href="#%EF%B8%8F-gallery"><b>🖼️ Gallery</b></a> •
<a href="#-architecture"><b>🏗️ Architecture</b></a> •
<a href="#-getting-started"><b>🚀 Getting Started</b></a> •
<a href="#-database"><b>🗄️ Database</b></a> •
<a href="#%EF%B8%8F-roadmap"><b>🗺️ Roadmap</b></a> •
<a href="#-developer"><b>👨‍💻 Developer</b></a>
</p>

</div>

<img src="docs/assets/divider.svg" width="100%"/>

<details>
<summary><b>📑 Table of Contents</b> (click to expand)</summary>

<br/>

1. [📖 Overview](#-overview)
2. [✨ Features](#-features)
3. [🖼️ Gallery](#%EF%B8%8F-gallery)
4. [🧰 Tech Stack](#-tech-stack)
5. [🏗️ Architecture](#-architecture)
6. [🔄 How It Works](#-how-it-works)
7. [📂 Project Structure](#-project-structure)
8. [🗄️ Database](#-database)
9. [🎨 Colour Palette](#-colour-palette)
10. [🚀 Getting Started](#-getting-started)
11. [☁️ Deployment](#%EF%B8%8F-deployment)
12. [🔐 Security Notes](#-security-notes)
13. [🗺️ Roadmap](#%EF%B8%8F-roadmap)
14. [❓ FAQ](#-faq)
15. [🤝 Contributing](#-contributing)
16. [📜 License & Credits](#-license--credits)
17. [👨‍💻 Developer](#-developer)

</details>

<!-- ═══════════════════════════ OVERVIEW ═══════════════════════════ -->
## 📖 Overview

**EazyDeals** is a full-stack **online shopping platform** built with classic Java web technologies — **JSP, Servlets and JDBC** on **Apache Tomcat 10**, backed by **MySQL 8**. Shoppers can browse, search and filter products, keep a wishlist, manage a cart and check out; administrators get a dedicated panel to run the store's catalogue, orders, users and admin team.

A built-in **mailing system** (Jakarta Mail over Gmail SMTP) emails users on registration, order confirmation, shipment and password reset (OTP).

> [!NOTE]
> The payment page is a **demo** — it is not wired to a real payment gateway, so any card details place a test order.

<div align="center">

| 🧩 Java classes | 📄 JSP pages | 🌐 Servlets | 🗃️ DB tables | ✉️ Email flows |
|:---:|:---:|:---:|:---:|:---:|
| **33** | **25** | **12** | **8** | **4** |

</div>

<img src="docs/assets/modules.svg" width="100%" alt="Module map"/>

<!-- ═══════════════════════════ FEATURES ═══════════════════════════ -->
## ✨ Features

<table>
<tr>
<th width="33%">🛍️ Shopper</th>
<th width="33%">🛠️ Admin</th>
<th width="33%">✉️ Platform</th>
</tr>
<tr valign="top">
<td>

- 📝 Register & log in
- 🔎 Search products by keyword
- 🗂️ Filter by category
- 📦 Product detail with stock check
- ❤️ Wishlist toggle on every card
- 🛒 Cart: add, change qty, remove
- ⚡ Buy now (skip the cart)
- 🏠 Edit delivery address at checkout
- 💳 Choose COD / online (demo)
- 📜 Order history with live status
- 👤 Edit personal info

</td>
<td>

- 🔐 Separate admin login
- ➕ Add / ✏️ update / 🗑️ delete **categories** (with image)
- ➕ Add / ✏️ update / 🗑️ delete **products** (price, discount, stock, image)
- 📋 View every order & update its status
- 👥 View users & remove fraudulent accounts
- 🧑‍🤝‍🧑 Add / remove other admins
- 📊 Dashboard counters

</td>
<td>

- ✉️ Welcome email on sign-up
- 🧾 Order-confirmation email
- 🚚 "Order shipped" email
- 🔢 5-digit OTP for password reset
- 🆔 Timestamped order IDs (`ORD-yyyyMMddhhmmss`)
- 🚫 Custom 404 + exception pages
- 🍬 SweetAlert pop-ups
- 📱 Responsive Bootstrap 5 UI

</td>
</tr>
</table>

<!-- ═══════════════════════════ GALLERY ═══════════════════════════ -->
## 🖼️ Gallery

<details open>
<summary><b>🛍️ Storefront</b></summary>
<br/>

| 🏠 Home | 📝 Register | 🔐 Login |
|:---:|:---:|:---:|
| <img src="https://github.com/bhagatanirudh/JSP-Servlet_Projects/assets/87819222/9f5fe55b-d3da-4cfa-9b4e-ac79f80dea45" width="280"/> | <img src="https://github.com/bhagatanirudh/JSP-Servlet_Projects/assets/87819222/74a9cee7-b090-4289-b20a-5952cc2f37b5" width="280"/> | <img src="https://github.com/bhagatanirudh/JSP-Servlet_Projects/assets/87819222/13025a16-c196-4f83-95da-855644108dea" width="280"/> |
| **📦 All Products** | **🗂️ Category Filter** | **🛒 Cart** |
| <img src="https://github.com/bhagatanirudh/JSP-Servlet_Projects/assets/87819222/d91fd265-c5b9-4c70-826a-603f8d525553" width="280"/> | <img src="https://github.com/bhagatanirudh/JSP-Servlet_Projects/assets/87819222/507acfb9-12c4-4200-890b-e79171f6e0d2" width="280"/> | <img src="https://github.com/bhagatanirudh/JSP-Servlet_Projects/assets/87819222/8dfb823c-a307-4837-9c4a-092391cf40a3" width="280"/> |
| **💳 Checkout** | **✅ Order Placed** | **👤 Profile** |
| <img src="https://github.com/bhagatanirudh/JSP-Servlet_Projects/assets/87819222/555a21c1-d850-4d3d-87e2-a98c04077eea" width="280"/> | <img src="https://github.com/bhagatanirudh/JSP-Servlet_Projects/assets/87819222/ec4dc90f-2ed5-4c50-bd95-28c12d80591b" width="280"/> | <img src="https://github.com/bhagatanirudh/JSP-Servlet_Projects/assets/87819222/c25d1813-3efd-4aba-a607-f1b19865e29d" width="280"/> |
| **❤️ Wishlist** | **🔑 Change Password** | **🔢 OTP → New Password** |
| <img src="https://github.com/bhagatanirudh/JSP-Servlet_Projects/assets/87819222/9d9d0911-7a34-486c-8e79-07d6aed0a39d" width="280"/> | <img src="https://github.com/bhagatanirudh/JSP-Servlet_Projects/assets/87819222/6646f05b-9b66-4645-9ea4-4253a2dffc11" width="280"/> | <img src="https://github.com/bhagatanirudh/JSP-Servlet_Projects/assets/87819222/e8514564-1e32-470c-bac7-6bd5154ce21c" width="135"/> <img src="https://github.com/bhagatanirudh/JSP-Servlet_Projects/assets/87819222/41224c8d-06bb-4680-8c21-75b879678cd4" width="135"/> |

</details>

<details>
<summary><b>🛠️ Admin Panel</b></summary>
<br/>

| 📊 Dashboard | ➕ Add Category | ➕ Add Product |
|:---:|:---:|:---:|
| <img src="https://github.com/bhagatanirudh/JSP-Servlet_Projects/assets/87819222/5aec17c2-b906-420e-bffa-a7ba1fb7a491" width="280"/> | <img src="https://github.com/bhagatanirudh/JSP-Servlet_Projects/assets/87819222/54a621dc-2bd5-4c41-89ab-e467c05f510c" width="280"/> | <img src="https://github.com/bhagatanirudh/JSP-Servlet_Projects/assets/87819222/cdef67ca-e5d0-4582-a309-400c86134af6" width="280"/> |
| **🗂️ Categories** | **📦 Products** | **📋 Orders** |
| <img src="https://github.com/bhagatanirudh/JSP-Servlet_Projects/assets/87819222/c6d0baa4-3559-4ac7-87ee-cdbd66fed4b0" width="280"/> | <img src="https://github.com/bhagatanirudh/JSP-Servlet_Projects/assets/87819222/2934c4b4-cb3b-4233-a710-8d820a2b211e" width="280"/> | <img src="https://github.com/bhagatanirudh/JSP-Servlet_Projects/assets/87819222/b9d6ee0f-d0b7-4e9d-b5d6-f76dd67bab25" width="280"/> |
| **👥 Users** | **🧑‍💼 Add Admin** | |
| <img src="https://github.com/bhagatanirudh/JSP-Servlet_Projects/assets/87819222/9003ee4f-88db-4cc1-a339-95041c0155d8" width="280"/> | <img src="https://github.com/bhagatanirudh/JSP-Servlet_Projects/assets/87819222/014b7630-4641-4a1d-967d-752b5cbc4bb6" width="280"/> | |

</details>

<details>
<summary><b>✉️ Email Templates</b></summary>
<br/>

| 🎉 Registration | 🧾 Order Confirmed | 🚚 Order Shipped | 🔢 Reset OTP |
|:---:|:---:|:---:|:---:|
| <img src="https://github.com/bhagatanirudh/JSP-Servlet_Projects/assets/87819222/b415d82f-fed8-4f59-a9a0-ce9760c1baec" width="200"/> | <img src="https://github.com/bhagatanirudh/JSP-Servlet_Projects/assets/87819222/e6ab034c-6633-4a6b-9e09-177f4c328134" width="200"/> | <img src="https://github.com/bhagatanirudh/JSP-Servlet_Projects/assets/87819222/8733b6ea-431a-4dbf-86f8-edd749a6a2ec" width="200"/> | <img src="https://github.com/bhagatanirudh/JSP-Servlet_Projects/assets/87819222/7a6511ff-7fb2-46a0-9296-e3614289028f" width="200"/> |

</details>

<details>
<summary><b>🎨 In-app illustrations</b> (from <code>src/main/webapp/Images</code>)</summary>
<br/>

<p align="center">
<img src="src/main/webapp/Images/products.png" width="80"/>
<img src="src/main/webapp/Images/categories.png" width="80"/>
<img src="src/main/webapp/Images/order.png" width="80"/>
<img src="src/main/webapp/Images/wishlist.png" width="80"/>
<img src="src/main/webapp/Images/users.png" width="80"/>
<img src="src/main/webapp/Images/admin.png" width="80"/>
<img src="src/main/webapp/Images/add-admin.png" width="80"/>
<img src="src/main/webapp/Images/profile.png" width="80"/>
<img src="src/main/webapp/Images/location.png" width="80"/>
<img src="src/main/webapp/Images/empty-cart.png" width="80"/>
</p>
<p align="center">
<img src="src/main/webapp/Images/scroll_img1.png" width="32%"/>
<img src="src/main/webapp/Images/scroll_img2.png" width="32%"/>
<img src="src/main/webapp/Images/scroll_img3.png" width="32%"/>
</p>

</details>

<!-- ═══════════════════════════ TECH STACK ═══════════════════════════ -->
## 🧰 Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=java,html,css,js,jquery,bootstrap,mysql,tomcat,eclipse,git&theme=dark" alt="stack icons"/>

</div>

| Layer | Technology | Purpose |
|---|---|---|
| 🎨 **Frontend** | HTML5 · CSS3 · JavaScript · jQuery 3.7 · Bootstrap 5.3 · Font Awesome 6 · SweetAlert2 | Responsive UI, modals, alerts |
| 📄 **View** | JSP (Jakarta Pages) + reusable `Components/` includes | Server-rendered pages |
| ⚙️ **Controller** | Jakarta Servlets (`@MultipartConfig` for uploads) | Request handling & routing |
| 🧠 **Model / DAO** | Plain Java entities + DAO classes over **JDBC** | Data access layer |
| 🗄️ **Database** | MySQL 8.0 (InnoDB, utf8mb4) | Persistence |
| ✉️ **Mail** | Jakarta Mail 2.0.1 · Angus Activation 2.0.1 | SMTP notifications |
| 🐱 **Server** | Apache Tomcat 10.1 | Servlet container (Jakarta EE 10) |
| 🧰 **Tooling** | Eclipse IDE for Enterprise Java · MySQL Workbench | Development |

<details>
<summary><b>📦 JAR dependencies</b></summary>

| JAR | Version | Location |
|---|---|---|
| `jakarta.mail` | 2.0.1 | `WEB-INF/lib` ✅ bundled |
| `jakarta.activation-api` | 2.1.2 | `WEB-INF/lib` ✅ bundled |
| `angus-activation` | 2.0.1 | `WEB-INF/lib` ✅ bundled |
| `mysql-connector-j` | 8.0.31+ | ⬇️ **add yourself** → `WEB-INF/lib` or `$CATALINA_HOME/lib` |
| `jakarta.servlet-api` | 6.0 | provided by Tomcat 10.1 |

</details>

<!-- ═══════════════════════════ ARCHITECTURE ═══════════════════════════ -->
## 🏗️ Architecture

The app follows a classic **MVC** split — JSPs render views, Servlets act as controllers, DAOs talk to MySQL through a shared JDBC connection.

```mermaid
flowchart LR
    subgraph Client["🌐 Browser"]
        UI["JSP pages<br/>Bootstrap · jQuery · SweetAlert"]
    end
    subgraph Tomcat["🐱 Apache Tomcat 10.1"]
        direction TB
        S["⚙️ Servlets<br/>Login · Register · Cart · Wishlist<br/>Order · AddOperation · Admin"]
        D["🧠 DAO layer<br/>UserDao · ProductDao · CartDao<br/>OrderDao · CategoryDao · …"]
        E["📦 Entities<br/>User · Product · Order · Cart …"]
        H["🔧 Helpers<br/>ConnectionProvider · Mail<br/>MailMessenger · OrderIdGenerator"]
        S --> D --> E
        S --> H
        D --> H
    end
    DB[("🐬 MySQL 8<br/>eazydeals")]
    SMTP["✉️ Gmail SMTP<br/>:587 TLS"]
    UI -- "HTTP form / GET" --> S
    S -- "forward / redirect" --> UI
    H -- JDBC --> DB
    H -- "Jakarta Mail" --> SMTP
```

<details>
<summary><b>🧭 Servlet routing table</b></summary>

| Route | Servlet | Responsibility |
|---|---|---|
| `/RegisterServlet` | `RegisterServlet` | Create account → welcome email |
| `/LoginServlet` | `LoginServlet` | User **and** admin login (`login` param) |
| `/LogoutServlet` | `LogoutServlet` | End user / admin session |
| `/UpdateUserServlet` | `UpdateUserServlet` | Profile, address, delete user |
| `/ChangePasswordServlet` | `ChangePasswordServlet` | Forgot-password OTP + reset |
| `/AddToCartServlet` | `AddToCartServlet` | Add product to cart |
| `/CartOperationServlet` | `CartOperationServlet` | +/- quantity, remove item |
| `/WishlistServlet` | `WishlistServlet` | Add / remove wishlist item |
| `/OrderOperationServlet` | `OrderOperationServlet` | Place order (cart or buy-now) |
| `/UpdateOrderServlet` | `UpdateOrderServlet` | Admin: change order status → shipped email |
| `/AddOperationServlet` | `AddOperationServlet` | Admin CRUD for categories & products |
| `/AdminServlet` | `AdminServlet` | Admin: add / delete admins |

</details>

<!-- ═══════════════════════════ HOW IT WORKS ═══════════════════════════ -->
## 🔄 How It Works

<details>
<summary><b>🛒 Checkout & order flow</b></summary>

```mermaid
sequenceDiagram
    autonumber
    actor U as 🧑 Shopper
    participant C as cart.jsp / checkout.jsp
    participant O as OrderOperationServlet
    participant DB as 🐬 MySQL
    participant M as ✉️ Mail
    U->>C: Review cart, edit address
    U->>C: Choose COD / online (demo)
    C->>O: POST order
    O->>O: OrderIdGenerator → ORD-yyyyMMddhhmmss
    O->>DB: INSERT order + ordered_product rows
    O->>DB: Reduce product stock, clear cart
    O->>M: Send order-confirmation email
    O-->>U: ✅ "Order placed" pop-up
```

</details>

<details>
<summary><b>🔢 Forgot-password (OTP) flow</b></summary>

```mermaid
flowchart LR
    A["forgot_password.jsp<br/>enter email"] --> B{"Email exists?"}
    B -- No --> A
    B -- Yes --> C["Generate 5-digit OTP<br/>store in session"]
    C --> D["✉️ Mail OTP"]
    D --> E["otp_code.jsp<br/>enter OTP"]
    E --> F{"OTP matches?"}
    F -- No --> E
    F -- Yes --> G["change_password.jsp"] --> H["✅ Password updated"]
```

</details>

<details>
<summary><b>🛠️ Admin order lifecycle</b></summary>

```mermaid
stateDiagram-v2
    [*] --> OrderPlaced: customer checks out
    OrderPlaced --> OrderConfirmed: admin updates
    OrderConfirmed --> Shipped: admin updates ✉️ shipped email
    Shipped --> OutForDelivery
    OutForDelivery --> Delivered
    Delivered --> [*]
```

</details>

<!-- ═══════════════════════════ STRUCTURE ═══════════════════════════ -->
## 📂 Project Structure

```text
📦 E-Commerce-Website
├── 📁 .github/
│   ├── 📁 ISSUE_TEMPLATE/          🐞 bug / ✨ feature templates
│   ├── 📁 workflows/build.yml      🤖 CI: compile Java + package WAR
│   └── 📄 PULL_REQUEST_TEMPLATE.md
├── 📁 database/
│   └── 🗄️ eazydeals.sql            schema + sample data (8 tables)
├── 📁 docs/
│   ├── 📁 assets/                  🎨 banner, divider, module map (SVG)
│   ├── 📄 SETUP.md                 step-by-step local setup
│   └── 📄 DATABASE.md              table reference + ER diagram
├── 📁 src/main/
│   ├── 📁 java/com/eazydeals/
│   │   ├── 📁 dao/                 🧠 8 DAO classes (JDBC)
│   │   ├── 📁 entities/            📦 9 model classes
│   │   ├── 📁 helper/              🔧 DB connection, mail, order IDs
│   │   └── 📁 servlets/            ⚙️ 12 controllers
│   └── 📁 webapp/
│       ├── 📁 Components/          🧩 navbar, alerts, CSS/JS includes
│       ├── 📁 CSS/style.css        🎨 custom styles
│       ├── 📁 JS/script.js         ⚡ client-side validation
│       ├── 📁 Images/              🖼️ UI illustrations
│       ├── 📁 Product_imgs/        📸 uploaded product & category images
│       ├── 📁 WEB-INF/             web.xml + lib/*.jar
│       └── 📄 *.jsp                25 pages (store + admin)
├── ⚙️ .project · .classpath · .settings/   Eclipse project files
├── 📄 CONTRIBUTING.md · CODE_OF_CONDUCT.md · SECURITY.md · CHANGELOG.md
└── 📘 README.md
```

<!-- ═══════════════════════════ DATABASE ═══════════════════════════ -->
## 🗄️ Database

Database name: **`eazydeals`** · dump: [`database/eazydeals.sql`](database/eazydeals.sql) · full reference: [`docs/DATABASE.md`](docs/DATABASE.md)

```mermaid
erDiagram
    USER ||--o{ CART : has
    USER ||--o{ WISHLIST : saves
    USER ||--o{ ORDER : places
    CATEGORY ||--o{ PRODUCT : groups
    PRODUCT ||--o{ CART : "added to"
    PRODUCT ||--o{ WISHLIST : "liked in"
    ORDER ||--|{ ORDERED_PRODUCT : contains

    USER { int userid PK
           varchar name
           varchar email UK
           varchar phone UK
           varchar address
           varchar city
           varchar state }
    CATEGORY { int cid PK
               varchar name
               varchar image }
    PRODUCT { int pid PK
              varchar name
              varchar price
              int quantity
              int discount
              int cid FK }
    CART { int id PK
           int uid FK
           int pid FK
           int quantity }
    WISHLIST { int idwishlist PK
               int iduser FK
               int idproduct FK }
    ORDER { int id PK
            varchar orderid
            varchar status
            varchar paymentType
            int userId FK
            timestamp date }
    ORDERED_PRODUCT { int oid PK
                      varchar name
                      int quantity
                      varchar price
                      int orderid FK }
    ADMIN { int id PK
            varchar name
            varchar email
            varchar phone }
```

<!-- ═══════════════════════════ PALETTE ═══════════════════════════ -->
## 🎨 Colour Palette

| Swatch | Hex | Used for |
|:---:|:---:|---|
| ![](https://img.shields.io/badge/-%20%20%20%20%20%20-2874f0?style=flat-square) | `#2874F0` | Primary brand blue — navbar, buttons |
| ![](https://img.shields.io/badge/-%20%20%20%20%20%20-389aeb?style=flat-square) | `#389AEB` | Hover / secondary accents |
| ![](https://img.shields.io/badge/-%20%20%20%20%20%20-027a3e?style=flat-square) | `#027A3E` | Discount & "in stock" green |
| ![](https://img.shields.io/badge/-%20%20%20%20%20%20-ff0303?style=flat-square) | `#FF0303` | Wishlist heart / errors |
| ![](https://img.shields.io/badge/-%20%20%20%20%20%20-e6eefa?style=flat-square) | `#E6EEFA` | Soft section backgrounds |
| ![](https://img.shields.io/badge/-%20%20%20%20%20%20-909191?style=flat-square) | `#909191` | Muted text, strike-through price |
| ![](https://img.shields.io/badge/-%20%20%20%20%20%20-ffe500?style=flat-square) | `#FFE500` | README / banner highlight |

<!-- ═══════════════════════════ GETTING STARTED ═══════════════════════════ -->
## 🚀 Getting Started

### ✅ Prerequisites

| Tool | Version |
|---|---|
| ☕ JDK | 17+ |
| 🐱 Apache Tomcat | 10.1.x (Jakarta EE 10) |
| 🐬 MySQL Server | 8.0+ |
| 🧰 Eclipse IDE for Enterprise Java *(or IntelliJ Ultimate)* | latest |
| 🔌 `mysql-connector-j` | 8.0.31+ |

### ⚡ Quick start

```bash
# 1️⃣ Clone
git clone https://github.com/Syed-Muhammad-Tayyab/E-Commerce-Website.git
cd E-Commerce-Website

# 2️⃣ Create & seed the database
mysql -u root -p -e "CREATE DATABASE IF NOT EXISTS eazydeals;"
mysql -u root -p eazydeals < database/eazydeals.sql
```

**3️⃣ Configure the DB connection** → `src/main/java/com/eazydeals/helper/ConnectionProvider.java`

```java
connection = DriverManager.getConnection(
        "jdbc:mysql://localhost:3306/eazydeals", "root", "root"); // ← your user / password
```

**4️⃣ Configure email (optional but recommended)** → `src/main/java/com/eazydeals/helper/Mail.java`

```java
String emailId  = "your-store@gmail.com";   // sender Gmail
String password = "xxxx xxxx xxxx xxxx";    // Google App Password (not your login password)
```

**5️⃣ Add the MySQL driver** — drop `mysql-connector-j-8.x.jar` into `src/main/webapp/WEB-INF/lib/`.

**6️⃣ Run it**

<details>
<summary><b>🌘 Eclipse (recommended)</b></summary>

1. `File → Import → Existing Projects into Workspace` → select the repo folder.
2. `Window → Preferences → Server → Runtime Environments` → add **Apache Tomcat v10.1**.
3. Right-click project → `Run As → Run on Server`.
4. Open **http://localhost:8080/E-Commerce-Website/**

</details>

<details>
<summary><b>💻 Command line (no IDE)</b></summary>

```bash
export CATALINA_HOME=/path/to/apache-tomcat-10.1.x
mkdir -p build/classes
javac --release 17 -d build/classes \
  -cp "$CATALINA_HOME/lib/servlet-api.jar:src/main/webapp/WEB-INF/lib/*" \
  $(find src/main/java -name '*.java')
mkdir -p dist && cp -r src/main/webapp dist/eazydeals
mkdir -p dist/eazydeals/WEB-INF/classes && cp -r build/classes/* dist/eazydeals/WEB-INF/classes/
(cd dist/eazydeals && jar -cf ../eazydeals.war .)
cp dist/eazydeals.war "$CATALINA_HOME/webapps/"
"$CATALINA_HOME/bin/startup.sh"
# → http://localhost:8080/eazydeals/
```

</details>

### 🔑 Demo logins (from the sample dump)

| Role | Email | Password |
|---|---|---|
| 🛠️ Admin | `test@gmail.com` | `abc123` |
| 🛍️ User | `test786@gmail.com` | `abc123` |

> [!WARNING]
> These are sample credentials shipped in the SQL dump — change or delete them before going live.

📘 Full walkthrough with troubleshooting: **[docs/SETUP.md](docs/SETUP.md)**

<!-- ═══════════════════════════ DEPLOYMENT ═══════════════════════════ -->
## ☁️ Deployment

| Option | How |
|---|---|
| 🐱 **Any Tomcat 10.1 host** | Build the WAR (above) → upload to `webapps/` |
| 🤖 **GitHub Actions artifact** | Every push runs [`build.yml`](.github/workflows/build.yml) → download `eazydeals-war` from the run |
| ☁️ **Railway / Render / VPS** | Run Tomcat 10.1 + a managed MySQL 8; point `ConnectionProvider` at the cloud DB |

> [!IMPORTANT]
> Static hosts like **Vercel, Netlify or GitHub Pages cannot run this project** — JSP/Servlets need a Java servlet container.

<!-- ═══════════════════════════ SECURITY ═══════════════════════════ -->
## 🔐 Security Notes

This is a learning-grade project. Before any real deployment, review **[SECURITY.md](SECURITY.md)** — key items:

- 🔑 Passwords are stored in **plain text** → hash with BCrypt/Argon2.
- 🧾 DB & SMTP credentials are **hard-coded** → move to environment variables / `context.xml`.
- 🛡️ No CSRF tokens on forms; add them for state-changing requests.
- 💳 Payment is a **mock** — integrate a real gateway (Stripe, JazzCash, Easypaisa…) server-side.

<!-- ═══════════════════════════ ROADMAP ═══════════════════════════ -->
## 🗺️ Roadmap

- [x] User registration, login, profile
- [x] Category & product catalogue with search
- [x] Cart, wishlist, buy-now, checkout
- [x] Admin panel (categories, products, orders, users, admins)
- [x] Email notifications + OTP reset
- [x] Repo redesign: docs, CI, templates, cleaned `web.xml`
- [ ] 🔐 Password hashing (BCrypt)
- [ ] ⚙️ Externalised config (env vars)
- [ ] 📦 Maven `pom.xml` build
- [ ] 💳 Real payment gateway
- [ ] ⭐ Product reviews & ratings
- [ ] 🐳 Docker Compose (Tomcat + MySQL)
- [ ] 🌙 Dark mode

<!-- ═══════════════════════════ FAQ ═══════════════════════════ -->
## ❓ FAQ

<details>
<summary><b>Product images don't show after importing the SQL dump?</b></summary>

The dump references images like `phone1.jpeg`, but the image files themselves are not in the repo. Images live in `src/main/webapp/Product_imgs/` — upload products again from the admin panel, or copy your own files with matching names into that folder.

</details>

<details>
<summary><b><code>ClassNotFoundException: com.mysql.cj.jdbc.Driver</code></b></summary>

The MySQL connector JAR is missing. Put `mysql-connector-j-8.x.jar` in `src/main/webapp/WEB-INF/lib/` (or Tomcat's `lib/`) and redeploy.

</details>

<details>
<summary><b>Emails aren't being sent.</b></summary>

Fill in `emailId` and `password` in `Mail.java`. For Gmail, enable 2-Step Verification and create an **App Password** — your normal Gmail password won't work.

</details>

<details>
<summary><b>Can I run it on Tomcat 9?</b></summary>

No. The code uses the `jakarta.*` namespace (Jakarta EE 9+), so it needs **Tomcat 10 or newer**. Tomcat 9 expects `javax.*`.

</details>

<details>
<summary><b>Where is the admin login?</b></summary>

Open `adminlogin.jsp` (linked from the navbar) and use an account from the `admin` table.

</details>

<!-- ═══════════════════════════ CONTRIBUTING ═══════════════════════════ -->
## 🤝 Contributing

Contributions are welcome! Please read **[CONTRIBUTING.md](CONTRIBUTING.md)** and our **[Code of Conduct](CODE_OF_CONDUCT.md)**.

```bash
git checkout -b feature/amazing-feature
git commit -m "feat: add amazing feature"
git push origin feature/amazing-feature   # → open a Pull Request
```

<!-- ═══════════════════════════ LICENSE ═══════════════════════════ -->
## 📜 License & Credits

- 🧑‍💻 **Original application:** EazyDeals by [Anirudh Kumar Bhagat (@bhagatanirudh)](https://github.com/bhagatanirudh) — screenshots in the gallery are from the original project.
- 🎨 **Repository redesign, documentation, CI & tooling:** [Syed Muhammad Tayyab](https://github.com/Syed-Muhammad-Tayyab).
- 📄 The upstream project does not declare a license. Respect the original author's rights; add a `LICENSE` file only if you own the code or have permission.
- 🙏 Thanks to Bootstrap, Font Awesome, SweetAlert2, jQuery, capsule-render, readme-typing-svg, shields.io and skillicons.dev.

<!-- ═══════════════════════════ DEVELOPER ═══════════════════════════ -->
## 👨‍💻 Developer

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Poppins&weight=700&size=22&duration=3000&pause=800&color=FFE500&center=true&vCenter=true&width=600&lines=Syed+Muhammad+Tayyab;BSCS+%E2%80%A2+Information+Security;Full-Stack+Web+Developer" alt="Syed Muhammad Tayyab"/>

<a href="https://github.com/Syed-Muhammad-Tayyab"><img src="https://img.shields.io/badge/GitHub-Syed--Muhammad--Tayyab-181717?style=for-the-badge&logo=github"/></a>
<img src="https://img.shields.io/badge/Based%20in-Islamabad%2C%20PK-01411C?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Focus-Full--Stack%20%2B%20Security-2874F0?style=for-the-badge"/>

<br/><br/>

**⭐ If this project helped you, drop a star — it keeps the repo alive!**

</div>

<!-- ═══════════════════════════ FOOTER ═══════════════════════════ -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2874f0,50:123a8a,100:0b1a3a&height=120&section=footer&text=Developed%20by%20Syed%20Muhammad%20Tayyab&fontSize=22&fontColor=ffffff&fontAlignY=72&animation=fadeIn" width="100%" alt="footer"/>
