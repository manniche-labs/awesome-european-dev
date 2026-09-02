<img src="https://raw.githubusercontent.com/manniche-labs/awesome-european-dev/main/.github/banner.svg" alt="" width="100%">

<div align="center">

  # 🇪🇺 Awesome European Dev

  **A curated list of tools, libraries, and resources for developers building in the European ecosystem.**

  *Danish 🇩🇰 • German 🇩🇪 • Austrian 🇦🇹 • Nordic 🇸🇪🇳🇴🇫🇮 — VAT/Moms, Apache hosting, GDPR, MobilePay & more.*

  <br />

  [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
  [![Project Views](https://komarev.com/ghpvc/?username=manniche-labs-awesome-european-dev&color=2563eb&style=flat-square&label=PROJECT+VIEWS)](https://github.com/manniche-labs/awesome-european-dev)
  [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://github.com/manniche-labs/awesome-european-dev/pulls)
  [![Studio](https://img.shields.io/badge/Studio-manniche_labs-0f0f0f?style=flat-square&logo=github&logoColor=white)](https://github.com/manniche-labs)

  <br />

  <sub>Curated by <b><a href="https://github.com/mikkelmanniche-dk">Mikkel Manniche</a></b> at <b><a href="https://github.com/manniche-labs">manniche labs</a></b></sub>

</div>

---

## Contents

- [🧾 VAT / Moms / Steuer](#-vat--moms--steuer)
- [🏦 Payments & Banking](#-payments--banking)
- [🌐 Hosting & Infrastructure](#-hosting--infrastructure)
- [🔒 Security & GDPR](#-security--gdpr)
- [🛒 E-Commerce](#-e-commerce)
- [📨 Email & Communication](#-email--communication)
- [🤖 AI & Vision APIs](#-ai--vision-apis)
- [🛠️ Developer Tools](#-developer-tools)
- [📚 Learning & Documentation](#-learning--documentation)
- [🏗️ Open-Source Projects from manniche labs](#-open-source-projects-from-manniche-labs)

---

## 🧾 VAT / Moms / Steuer

European VAT handling is notoriously complex. These tools and resources help.

### Libraries

- **[vatstack](https://vatstack.com)** — VAT validation and rate API for 100+ countries. Supports EU VAT, UK VAT, and live verification.
- **[vat-rates](https://github.com/Rates-API/vat-rates)** — Simple JSON file listing current VAT rates for all EU countries.
- **[taxes.js](https://github.com/felipeduarte/taxes.js)** — Small JS library for calculating EU VAT with historical rate support.

### Reference

- **[European Commission — VAT Rates](https://taxation-customs.ec.europa.eu/taxation/vat/telecommunications-broadcasting-and-electronic-services/vat-rates_en)** — Official EU VAT rate table.
- **🇩🇪 German MwSt.:** Standard 19%, Reduced 7% (food, books, newspapers). Groups printed on receipts as `A` (19%) and `B` (7%).
- **🇩🇰 Danish Moms:** Flat 25% on all goods. No reduced rate for food.
- **🇦🇹 Austrian USt.:** Standard 20%, Reduced 10% (food, accommodation, books).
- **[VIES VAT Number Validator](https://ec.europa.eu/taxation_customs/vies/)** — Official EU tool to validate cross-border B2B VAT numbers.

### Tools

- **[receipt-scanner-core](https://github.com/manniche-labs/receipt-scanner-core)** — TypeScript schemas and Vision AI prompts for parsing DE 🇩🇪 and DK 🇩🇰 receipts with MwSt./Moms tax breakdown extraction.

---

## 🏦 Payments & Banking

### Denmark 🇩🇰

- **[MobilePay for Developers](https://developer.mobilepay.dk)** — REST API docs for MobilePay, Denmark's dominant mobile payment platform (5+ million users).
- **[Quickpay](https://quickpay.net)** — Danish payment gateway with easy REST API. Supports Dankort, Visa, MasterCard, MobilePay.
- **[NETS Easy](https://developers.nets.eu/nets-easy)** — Nordic payment platform (Dankort, MobilePay, Swish). Well-documented REST API.
- **[Stripe DK](https://stripe.com/en-dk)** — Stripe in Denmark. Supports DKK and MobilePay as of 2024.

### Germany 🇩🇪

- **[Stripe DE](https://stripe.com/de)** — Full German localization with SEPA, Sofort, GiroPay, and Klarna support.
- **[Mollie](https://www.mollie.com/de)** — Popular European PSP with excellent DACH coverage. iDEAL, SEPA, Klarna.
- **[PayPal Germany Docs](https://developer.paypal.com)** — Strong market penetration in DE. REST + SDK docs.
- **[Unzer (formerly Heidelpay)](https://www.unzer.com)** — German payment gateway with SEPA Direct Debit and installment support.

### Multi-Country

- **[Stripe](https://stripe.com)** — Best-in-class DX. Supports 40+ countries, multi-currency, and automatic tax calculation.
- **[Adyen](https://www.adyen.com)** — Enterprise-grade pan-European payment processing.

---

## 🌐 Hosting & Infrastructure

### Danish Hosting 🇩🇰

- **[Simply.com](https://simply.com)** — Popular Danish shared hosting. Apache 2.4, PHP, MySQL, FTPS, cPanel. Used by many SMBs.
- **[one.com](https://one.com)** — Pan-European hosting. Good for WordPress + WooCommerce.
- **[DK Hostmaster](https://www.dk-hostmaster.dk/en)** — Official .dk domain registry.

### German Hosting 🇩🇪

- **[IONOS (1&1)](https://www.ionos.de)** — Germany's largest hosting provider. VPS, Dedicated, WordPress.
- **[Hetzner](https://www.hetzner.com)** — Excellent price/performance VPS and dedicated servers. Extremely popular in the DE dev community.
- **[Strato](https://www.strato.de)** — German hosting with strong WordPress and e-commerce focus.
- **[netcup](https://www.netcup.de)** — Budget VPS with German data centers. Huge community.
- **[e-studio.dk](https://www.e-studio.dk)** — Danish e-commerce hosting specialists.

### DNS & CDN

- **[Cloudflare](https://cloudflare.com)** — Industry standard CDN, DDoS protection, DNS. Works seamlessly with all European hosting.

---

## 🔒 Security & GDPR

### GDPR Compliance

- **[iubenda](https://www.iubenda.com)** — Auto-generated GDPR privacy policies and cookie banners for Danish and German sites.
- **[Cookiebot](https://www.cookiebot.com)** — GDPR/ePrivacy compliant cookie consent management. Very popular in DK/DE.
- **[Matomo](https://matomo.org)** — Open-source analytics. GDPR-compliant alternative to Google Analytics with EU data residency.

### Apache Security

- **[apache-spa-security-hardening](https://github.com/manniche-labs/apache-spa-security-hardening)** — Production-grade `.htaccess` with OWASP A+ CSP, HSTS, and SPA routing for React/Next.js/Vite.
- **[Mozilla Observatory](https://observatory.mozilla.org)** — Free security scan for any domain. Tests CSP, HSTS, X-Frame-Options, and more.
- **[SecurityHeaders.com](https://securityheaders.com)** — Instant HTTP security header grading.

---

## 🛒 E-Commerce

### Platforms

- **[WooCommerce](https://woocommerce.com)** — WordPress-based. Dominant in DK/DE SMB market. Strong GDPR plugins available.
- **[Shopify](https://shopify.com)** — SaaS e-commerce. Growing fast in DE/DK markets. MobilePay + SEPA support.
- **[Magento / Adobe Commerce](https://business.adobe.com/products/magento/magento-commerce.html)** — Enterprise-grade. Popular with larger DE retailers.

### Tools

- **[Slimpack for WooCommerce](https://slimpack.io)** — Lightweight WooCommerce performance toolkit.
- **[WP Rocket](https://wp-rocket.me)** — Cache & performance plugin used widely with Danish/German WooCommerce stores.

---

## 📨 Email & Communication

- **[Mailchimp](https://mailchimp.com)** — Email marketing. Well-integrated with WooCommerce and Shopify.
- **[HubSpot](https://www.hubspot.com)** — CRM + email marketing + lead capture. Widely used by European agencies.
- **[Resend](https://resend.com)** — Developer-focused transactional email API. Modern alternative to SendGrid.
- **[Brevo (formerly Sendinblue)](https://brevo.com)** — European email platform. GDPR-compliant, EU data centers.

---

## 🤖 AI & Vision APIs

- **[Google Gemini Vision](https://ai.google.dev)** — Best-in-class document and receipt understanding. Powers `receipt-scanner-core`.
- **[OpenAI GPT-4o Vision](https://platform.openai.com)** — Strong general-purpose vision with JSON output mode. Great for receipt extraction.
- **[Anthropic Claude](https://www.anthropic.com)** — Excellent at structured extraction from complex document images.
- **[receipt-scanner-core](https://github.com/manniche-labs/receipt-scanner-core)** — TypeScript lib wrapping production-tested prompts for DE/DK receipt parsing.

---

## 🛠️ Developer Tools

- **[Antigravity IDE](https://antigravity.dev)** — AI-powered coding assistant with multi-step agentic capabilities.
- **[CodeRabbit](https://coderabbit.ai)** — AI-powered code review. Integrates directly with GitHub PRs.
- **[Vercel](https://vercel.com)** — Best deployment platform for Next.js. Instant previews, Edge Functions.
- **[Bruno](https://www.usebruno.com)** — Open-source Postman alternative. API testing with offline-first design.
- **[Hoppscotch](https://hoppscotch.io)** — Web-based API client. Fast and free.

---

## 📚 Learning & Documentation

- **[MDN Web Docs](https://developer.mozilla.org)** — The definitive web platform reference.
- **[web.dev](https://web.dev)** — Google's Core Web Vitals, performance, and modern web best practices.
- **[OWASP Top 10](https://owasp.org/www-project-top-ten/)** — The standard security vulnerability reference for web applications.
- **[nextjs.org/docs](https://nextjs.org/docs)** — Official Next.js documentation.

---

## 🏗️ Open-Source Projects from manniche labs

Projects built for and by European developers:

| Project | Description |
| :--- | :--- |
| **[receipt-scanner-core](https://github.com/manniche-labs/receipt-scanner-core)** | 🧾 European receipt parsing — TypeScript schemas, Vision AI prompts, DE/DK normalization |
| **[next-enterprise-starter](https://github.com/manniche-labs/next-enterprise-starter)** | ⚡ Next.js 16 + React 19 + Tailwind CSS 4 production starter |
| **[apache-spa-security-hardening](https://github.com/manniche-labs/apache-spa-security-hardening)** | 🛡️ OWASP A+ Apache `.htaccess` security template for SPAs |

---

## Contributing

Contributions welcome! To add a resource:
1. Fork this repository
2. Add your resource under the relevant section (alphabetically within sections)
3. Follow the link format: `**[Name](url)** — Brief description.`
4. Open a pull request

Please ensure all submitted resources are:
- Actively maintained
- Relevant to the European developer ecosystem
- Free of affiliate links

---

<div align="center">
  <sub>Maintained by <b><a href="https://github.com/manniche-labs">manniche labs</a></b> • <a href="https://mikkelmanniche.dk">mikkelmanniche.dk</a></sub>
</div>
