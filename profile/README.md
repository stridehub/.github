# 👋 Welcome to Stridehub

**Stridehub** is a software development organisation building high-performance tools, freelance web platforms, and enterprise applications. This document gives an overview of every project in the organisation, its current status, and key links.

---

## 📋 Table of Contents

- [About Stridehub](#about-stridehub)
- [Projects Overview](#projects-overview)
  - [Pivot Table Generator](#1--pivot-table-generator)
  - [Codelush](#2--codelush)
  - [hk-ERP (Nextgen ERP)](#3--hk-erp-nextgen-erp)
  - [Smartcars](#4--smartcars)
- [Contributing](#contributing)
- [Contact](#contact)

---

## 🏢 About Stridehub

Stridehub is home to a growing portfolio of open-source and proprietary projects across web, systems programming, and enterprise software. Our work spans from blazing-fast data processing engines built in Rust to full-stack freelance platforms and pick-up/drop-off services.

| Metric | Value |
|---|---|
| Public Repositories | 4 |
| Active Projects | 3 |
| Primary Languages | TypeScript · JavaScript · Rust |

---

## 🗂️ Projects Overview

### 1. 🔢 Pivot Table Generator

| Field | Details |
|---|---|
| **Repository** | [stridehub/pivot-table-generator](https://github.com/stridehub/pivot-table-generator) |
| **Status** | 🟢 Active |
| **Language** | TypeScript (Frontend) · Rust (Backend) |
| **Last Updated** | March 2026 |

**Description:** A high-performance pivot table generator that processes **300,000+ rows in under a second** using a Rust backend with Rayon parallel computing, paired with a modern Next.js 14 frontend.

**Key Features:**
- 🦀 Rust + Actix-web backend with Rayon-powered parallel processing
- ⚡ Processes 1 million rows in ~400 ms
- 📊 6 aggregation types (Sum, Count, Average, Min, Max, Distinct Count)
- 🔍 8 filter operators with multi-field sorting
- 📈 Bar, Line, and Pie chart visualizations (Recharts)
- 🌙 Full dark mode with glass morphism UI
- 📤 CSV export support
- 🖥️ Responsive design for desktop, tablet, and mobile

**Tech Stack:** Rust · Actix-web · Rayon · Next.js 14 · React 18 · TypeScript · Tailwind CSS · Zustand · Recharts · @tanstack/react-table

**Quick Start:**
```bash
git clone https://github.com/stridehub/pivot-table-generator.git
cd pivot-table-generator
cd frontend && npm install && cd ..
npm run dev
# Backend → http://127.0.0.1:8080  |  Frontend → http://localhost:3000
```

---

### 2. 🌐 Codelush

| Field | Details |
|---|---|
| **Repository** | [stridehub/codelush](https://github.com/stridehub/codelush) |
| **Status** | 🟡 In Progress (7 open issues) |
| **Language** | JavaScript · PHP · MySQL |
| **Live Site** | [codelush.pages.dev](https://codelush.pages.dev) |
| **Last Updated** | February 2026 |

**Description:** Codelush is a **freelance project** — an interactive web-based platform hosted on Cloudflare Pages with a database layer on InfinityFree.

**Key Features:**
- 🚀 Deployed on Cloudflare Pages (fast global CDN)
- 💾 PHP + MySQL backend
- 📱 Fully responsive design
- 🔍 Interactive and beginner-friendly UI

**Tech Stack:** HTML · CSS · JavaScript · PHP · MySQL · Cloudflare Pages

**Open Issues (7):**
| # | Title | Label |
|---|---|---|
| [#13](https://github.com/stridehub/codelush/issues/13) | Adding Pull Request template | `enhancement` |
| [#10](https://github.com/stridehub/codelush/issues/10) | Add transitions, shadows, animations & hover effects | `SWOC25` |
| [#9](https://github.com/stridehub/codelush/issues/9) | Improve README for better clarity and contribution | `SWOC25` |
| [#7](https://github.com/stridehub/codelush/issues/7) | Adding issue templates | `SWOC25` |
| [#5](https://github.com/stridehub/codelush/issues/5) | Update Twitter icon to X | `SWOC25` |
| [#3](https://github.com/stridehub/codelush/issues/3) | Integrating chatbot to enhance user experience | `SWOC25` |
| [#1](https://github.com/stridehub/codelush/issues/1) | Adding a Favicon | `SWOC25` |

> ⚠️ **Note:** The database is hosted on InfinityFree over **HTTP**. Some browsers may block mixed content. Consider migrating to a platform that supports HTTPS (e.g., Supabase, Firebase, Render).

**Local Setup:**
```bash
git clone https://github.com/stridehub/codelush.git
cd codelush
# Requires XAMPP / MAMP — move to htdocs, start Apache + MySQL
# Open http://localhost/codelush in your browser
```

---

### 3. 🏢 hk-ERP (Nextgen ERP)

| Field | Details |
|---|---|
| **Repository** | [stridehub/hk-ERP](https://github.com/stridehub/hk-ERP) |
| **Status** | 🔴 Low Activity (last commit Sep 2025) |
| **Language** | TypeScript |
| **Figma Design** | [View on Figma](https://www.figma.com/design/U0HTiXNoIywMt601zYjKqc/Nextgen-ERP) |
| **Last Updated** | September 2025 |

**Description:** A code bundle for **Nextgen ERP**, built from a comprehensive Figma design. Aimed at delivering a modern enterprise resource planning solution.

**Tech Stack:** TypeScript · Next.js (assumed) · Node.js

**Local Setup:**
```bash
git clone https://github.com/stridehub/hk-ERP.git
cd hk-ERP
npm install
npm run dev
```

---

### 4. 🚗 Smartcars

| Field | Details |
|---|---|
| **Repository** | [stridehub/Smartcars](https://github.com/stridehub/Smartcars) |
| **Status** | 🟠 Planning / Early Stage |
| **Tagline** | *pick-drop-made-simple* |
| **Last Updated** | January 2026 |

**Description:** Smartcars is a pick-up and drop-off service platform, designed to make transportation simple and seamless. The project is in its early stages.

**Planned Features:**
- 🚗 Easy ride booking (pick-up / drop-off)
- 📍 Real-time location tracking
- 👤 Driver and passenger profiles
- 💳 Payment integration

**Tech Stack:** *(To be confirmed — project is in planning phase)*

---

## 🤝 Contributing

We welcome contributions to all of our projects! Here's how to get started:

1. **Fork** the repository you want to contribute to.
2. **Create a branch** for your feature or fix:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Make your changes** and commit them with a meaningful message:
   ```bash
   git commit -m "feat: describe your change"
   ```
4. **Push** to your forked repository:
   ```bash
   git push origin feature/your-feature-name
   ```
5. **Open a Pull Request** against the `main` branch and describe your changes.

Please ensure your PR:
- Follows the existing code style of the project
- Includes a clear description of the changes and the motivation
- References any related issues (e.g., `Closes #9`)

---

## 📬 Contact

| | |
|---|---|
| **Organisation Lead** | [@dapphari007](https://github.com/dapphari007) |
| **GitHub Organisation** | [github.com/stridehub](https://github.com/stridehub) |
| **Issues / Discussions** | Use the respective repository's Issues tab |

---

> 💡 *If you find any of our projects useful, please consider giving them a ⭐ on GitHub!*
