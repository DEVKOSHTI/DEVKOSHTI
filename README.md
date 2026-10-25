<h1 align="center">Hi, I'm Dev Koshti 👋</h1>
<h3 align="center">Software Engineer</h3>

<p align="center">
  I build complete products (servers, admin panels and mobile apps) and keep them running.<br>
  Two of them are served live from an Android phone I set up as a production server.
</p>

<p align="center">
  <a href="https://devkoshti.com"><img src="https://img.shields.io/badge/Website-devkoshti.com-12161B?style=for-the-badge&logo=googlechrome&logoColor=FFD21F" /></a>
  <a href="mailto:devkoshti0119@gmail.com"><img src="https://img.shields.io/badge/Email-devkoshti0119%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/devkoshti"><img src="https://img.shields.io/badge/LinkedIn-devkoshti-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://www.instagram.com/ha.dev.ha"><img src="https://img.shields.io/badge/Instagram-ha.dev.ha-E4405F?style=for-the-badge&logo=instagram&logoColor=white" /></a>
</p>

<p align="center"><img src="https://img.shields.io/badge/Open%20to-full--time%20roles%20%26%20freelance-2ea44f?style=flat-square" /></p>

---

## 🚀 Products running today

### 💧 Water Delivery Platform · [water.devkoshti.com](https://water.devkoshti.com)
Software for water bottle delivery businesses. One server runs many businesses, and each sees only its own customers, staff, deliveries, bills and payments.

| Who | What they do |
|---|---|
| **Platform owner** | Creates businesses, switches them off, sees everything, takes database backups |
| **Business owner** | Manages staff, customers, cards, payments, bills and pending dues in the admin panel |
| **Delivery staff** | Tap a customer's NFC card or scan its QR code at the door; add new customers on the spot |
| **Customers** | See bottles, bills and payments; log in with mobile number + PIN or fingerprint |

**Built with:** Spring Boot 3.5 · Java 21 · Spring Security (JWT) · JPA · H2/PostgreSQL · Angular admin panel · two Flutter apps
**Runs on:** a Realme 7 phone with Termux and a Cloudflare Tunnel, auto-updated from GitHub releases with rollback
> Private code · walkthrough on request

### 👗 Jeenal's Design Studio · [fashion.devkoshti.com](https://fashion.devkoshti.com)
An online clothing store for a design studio. Shoppers browse collections, pick sizes, check out, get an order number and track their order, with a WhatsApp hand-off to the owner. The owner manages photos, prices, sizes, shop text and orders from an admin panel on her phone.

**Built with:** Angular 19 · TypeScript · Node.js · Express 5 · SQLite · 20 end-to-end API tests
**Runs on:** the same Realme 7 phone, with the same release pipeline
> Private code · walkthrough on request

---

## 🔁 How a change reaches the phone

1. Push to `main`
2. GitHub Actions runs the tests and builds the server and website
3. The build is published as a release with a SHA-256 checksum
4. Every 5 minutes the phone checks for a newer release and verifies the download
5. It saves the current version and data, installs the new one and restarts
6. If the health check fails, it restores the saved version and skips that release

---

## 🛠️ Stack

| | |
|---|---|
| **Languages** | Java, TypeScript, JavaScript, Dart, SQL |
| **Backend** | Spring Boot, Spring Security, JPA, Node.js, Express, REST APIs |
| **Frontend & apps** | Angular, Flutter |
| **Data** | PostgreSQL, H2, SQLite |
| **Delivery** | GitHub Actions, Docker, Linux shell, Termux, Cloudflare Tunnel |

---

## 📫 Contact

**Email:** devkoshti0119@gmail.com · **LinkedIn:** [devkoshti](https://www.linkedin.com/in/devkoshti) · **Instagram:** [ha.dev.ha](https://www.instagram.com/ha.dev.ha) · **Website:** [devkoshti.com](https://devkoshti.com)
