<div align="center">
  <h1>Hi there, I'm Psyche Supreme! 👋</h1>
  <p><b>Full Stack Engineer | Distributed Systems & Multi-Tenant SaaS | Quant Trading</b></p>
  <p><i>Based in Kenya 🇰🇪</i></p>
</div>

---

### 👨‍💻 About Me

I am a Computer Science student and Software Engineer specializing in architecting secure, scalable, and data-driven systems. My work spans high-reliability enterprise platforms, multi-tenant SaaS ecosystems, institutional-grade quantitative trading engines, and localized FinTech/AgTech applications.

#### 🎯 Core Focus Areas:
- 🌐 **Enterprise & Multi-Tenant Architecture:** Engineering decoupled 3-tier enterprise applications and SaaS platforms with schema-isolated multi-tenancy (`stancl/tenancy`, ASP.NET Core, Laravel, Django).
- 📈 **Quantitative Finance & Algorithmic Trading:** Developing automated market execution engines for MetaTrader 5 (MT5) with Smart Money Concepts (SMC), Markov regime gating, Kelly sizing, multi-asset correlation guards, and dynamic risk ladders.
- 📱 **Mobile & Offline-First Engineering:** Crafting reactive mobile applications with Flutter, Isar, and Hive NoSQL, featuring background GPS isolation, BLoC state management, and Last-Write-Wins (LWW) conflict resolution.
- 🔗 **FinTech & Supply Chain Integrations:** Integrating mission-critical localized payment gateways (Safaricom M-Pesa / Daraja API STK Push) and statutory tax invoicing (KRA eTIMS QR code vectors).
- 🗄️ **Advanced Database Engineering:** Designing strict normalized schemas (3NF, Exclusive Arc supertypes), spatial geographic modeling (PostgreSQL / PostGIS), WAL persistence, and ACID-compliant transaction controls.

---

### 🚀 Featured Projects

#### 🛡️ [Sentinel](https://github.com/psychesupreme/sentinel-v1)
**Autonomous Multi-Asset Algorithmic Trading Platform**
* **Overview:** An institutional-grade, fully automated trading platform built for Spot Gold (XAUUSD), Spot Silver (XAGUSD), and Major/Cross Forex pairs deployed live on MetaTrader 5.
* **Key Highlights:** Multi-timeframe Smart Money Concepts (SMC) engine (Order Blocks, Fair Value Gaps, BOS/CHoCH, Equilibrium discount/premium filtering). Institutional risk engine with dynamic contract-tick lot sizing, Pearson correlation guard (>0.75), 2.0% daily drawdown cap, zero-cost MT5 economic news guard, 5-phase dynamic exit sequence, live FastAPI web terminal, and remote Telegram daemon control.
* **Tech Stack:** `Python 3.12` `MetaTrader 5 API` `FastAPI` `SQLite (WAL)` `Telegram API` `pytest`

---

#### 🛰️ [OmniRoute v2](https://github.com/psychesupreme/omniverse)
**Multi-Tenant Field Force Automation & Real-Time Telematics SaaS**
* **Overview:** An enterprise multi-tenant field workforce management system connecting distributed field agents with central dispatchers via offline-first syncing and real-time mapping.
* **Key Highlights:** PostgreSQL schema isolation via `stancl/tenancy`, dynamic PostGIS geography types, background Flutter GPS service isolate (60s logging with mock-GPS countermeasures), Last-Write-Wins Isar DB sync queue, and real-time Leaflet.js live tracking powered by Laravel Reverb WebSockets.
* **Tech Stack:** `Laravel 11` `Flutter` `PostgreSQL` `PostGIS` `Vue.js 3` `Inertia.js` `Laravel Reverb` `Isar` `Tailwind CSS`

---

#### 📈 [TradeCore Quant (Kom v1.0)](https://github.com/psychesupreme/TradeCore_Quant)
**Quantitative Execution & Algorithmic Gold Scalping System**
* **Overview:** A fully automated quantitative trading engine purpose-built for high-frequency XAUUSD market execution, deployed on MetaTrader 5.
* **Key Highlights:** Dual-layer architecture combining continuous 24h M1 momentum scalping with session-gated structural ICT strategies (London/NY Judas, Silver Bullet, FVG). Implements Kelly criterion position sizing, Markov regime detection, XGBoost ML scoring pipelines, and a 5-phase dynamic exit engine.
* **Tech Stack:** `Python 3.11+` `MetaTrader 5 API` `FastAPI` `XGBoost` `SQLite (WAL)` `Telegram Bot API` `APScheduler`

---

#### 🌸 [Noir & Bloom Atelier](https://github.com/psychesupreme/noir)
**Luxury Floral ERP & Bespoke Curation Platform**
* **Overview:** An enterprise ERP, floriculture inventory logistics, and curation platform tailored for Kenya's luxury floriculture market.
* **Key Highlights:** Consolidated into 4 squashed domain baseline migrations, automated statutory KRA eTIMS QR code vector generation and PDF tax invoicing (DOMPDF), tagged storefront caching with event-driven invalidation (`StorefrontCacheService`), and Resend transactional email driver.
* **Tech Stack:** `Laravel 11/12` `Livewire 3` `PostgreSQL` `Tailwind CSS` `KRA eTIMS` `Resend` `DOMPDF`

---

#### 🧩 [CultureCode](https://github.com/psychesupreme/Word-Culture-Puzzle-Game)
**Multi-Sensory Linguistic & Cultural Learning Puzzle Game**
* **Overview:** A gamified cross-platform mobile puzzle application merging cognitive language acquisition with interactive cultural lore and multi-sensory gameplay.
* **Key Highlights:** Engineered with Flutter & Dart using Clean Architecture and the BLoC pattern (`flutter_bloc`). Features a cognitive dashboard with multi-axis radar charts tracking user retention, phonetic & letter tile banks, visual clue renderers, audio speed matching arcade games (`just_audio`), text-to-speech (`flutter_tts`), and Hive NoSQL local storage.
* **Tech Stack:** `Flutter` `Dart` `flutter_bloc` `Hive NoSQL` `GoRouter` `Just Audio` `Flutter TTS`

---

#### 🗳️ [Secure Multi-Election Voting System](https://github.com/psychesupreme/VotingSystemProject)
**3-Tier Enterprise Multi-Demographic Voting Platform**
* **Overview:** A high-integrity electronic voting platform designed for multi-tier elections across university and national demographics (staff, students, residents).
* **Key Highlights:** Exclusive Arc (Supertype/Subtype) normalized 3NF database schema, ACID-compliant TCL transactions to mathematically eliminate double-voting, immutable audit logging, and a decoupled SPA with real-time leaderboards.
* **Tech Stack:** `Angular` `C# ASP.NET Core` `Microsoft SQL Server` `TypeScript` `Tailwind CSS`

---

#### 🛒 [Ecobid](https://github.com/psychesupreme/Ecobid)
**Localized E-Commerce & Real-Time Auction Platform**
* **Overview:** A full-stack localized marketplace supporting real-time auction bidding, direct purchases, and integrated driver logistics.
* **Key Highlights:** Real-time auction bidding system, multi-item shopping cart with bulk-checkout, automated Safaricom M-Pesa (Daraja API STK Push) integration, and a dedicated delivery driver logistics portal.
* **Tech Stack:** `Python` `Django` `M-Pesa Daraja API` `Bootstrap` `SQLite`

---

#### 📦 [BARA Mobile Platform](https://github.com/psychesupreme/Bara)
**Multi-Tenant Field Operations & Workforce Mobile Suite**
* **Overview:** Multi-tenant operations suite bridging central administrative scheduling with distributed field teams.
* **Key Highlights:** Isolated tenant environments (`stancl/tenancy`), cross-platform Flutter field client with local Isar database caching, geolocation tracking, and real-time WebSocket communications.
* **Tech Stack:** `Laravel 11` `Flutter` `stancl/tenancy` `Isar NoSQL` `Docker` `WebSockets`

---

#### 🌾 [KAPEM](https://github.com/psychesupreme/kapem-distributed-system)
**Kenya Agricultural Produce Exchange Market**
* **Overview:** A distributed, cloud-native database management system (DDBMS) modernizing agricultural supply chain logistics.
* **Key Highlights:** Decentralized data nodes for farmers and commercial buyers, multi-node database synchronization, and containerized deployment to optimize fair market access and reduce middleman overhead.
* **Tech Stack:** `Node.js` `PostgreSQL` `Docker` `Distributed Systems`

---

### 🛠️ Tech Stack & Tools

#### Languages
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP" />
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white" alt="C#" />
  <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" alt="Dart" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
</p>

#### Frameworks & Environments
<p>
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter" />
  <img src="https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white" alt="Laravel" />
  <img src="https://img.shields.io/badge/.NET_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET Core" />
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" alt="Django" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white" alt="Angular" />
  <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white" alt="Vue.js" />
  <img src="https://img.shields.io/badge/Livewire-4E56A6?style=for-the-badge&logo=livewire&logoColor=white" alt="Livewire" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
</p>

#### Databases & Storage
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/PostGIS-006400?style=for-the-badge&logo=postgis&logoColor=white" alt="PostGIS" />
  <img src="https://img.shields.io/badge/Microsoft_SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" alt="MS SQL Server" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite" />
  <img src="https://img.shields.io/badge/Hive_NoSQL-F39C12?style=for-the-badge&logoColor=white" alt="Hive NoSQL" />
</p>

#### DevOps, Trading & Integrations
<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/MetaTrader_5-2C3E50?style=for-the-badge&logoColor=white" alt="MetaTrader 5" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/M--Pesa_Daraja-00A651?style=for-the-badge&logoColor=white" alt="M-Pesa Daraja" />
  <img src="https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" alt="pytest" />
</p>

---

### 📊 GitHub Activity

<div align="center">
  <img src="https://github-readme-stats-anuraghazra.vercel.app/api?username=psychesupreme&show_icons=true&theme=midnight-purple&hide_border=true&count_private=true" alt="psychesupreme's GitHub stats" width="48%" />
  <img src="https://github-readme-stats-anuraghazra.vercel.app/api/top-langs/?username=psychesupreme&layout=compact&theme=midnight-purple&hide_border=true" alt="Top Languages" width="48%" />
  <br />
  <br />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=psychesupreme&theme=midnight-purple&hide_border=true" alt="GitHub Streak" width="96%" />
</div>

<br />

---

<div align="center">
  <a href="mailto:s3dwn@outlook.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://linkedin.com/in/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</div>
