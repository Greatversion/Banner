<div align="center">

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSwYZG76IrEOaAhOLte9OLB0SmMsig_eWLc2bhYjCnq9g&s=10" alt="Aditya Verma — Flutter Developer" width="100%"/>

# 👋 Hey, I'm Aditya 

### 📱 Flutter Developer · 🧩 Product Builder · 🚀 Founder @ FixitBhaii Solutions

<p>
  <img src="https://img.shields.io/badge/Flutter-Expertise-02569B?style=for-the-badge&logo=flutter&logoColor=white" />
  <img src="https://img.shields.io/badge/Dart-Development-0175C2?style=for-the-badge&logo=dart&logoColor=white" />
  <img src="https://img.shields.io/badge/Supabase-Backend-3ECF8E?style=for-the-badge&logo=supabase&logoColor=111111" />
  <img src="https://img.shields.io/badge/Firebase-Cloud-FFCA28?style=for-the-badge&logo=firebase&logoColor=111111" />
</p>

<p>
  <a href="https://fixitbhaii-solutions.vercel.app/">
    <img src="https://img.shields.io/badge/FixitBhaii%20Solutions-Businesses%20%E2%86%92%20Mobile-0993D9?style=flat-square" />
  </a>
  <img src="https://img.shields.io/badge/Experience-3%2B%20Years-111827?style=flat-square" />
  <img src="https://img.shields.io/badge/Focus-Mobile%20Engineering-111827?style=flat-square" />
</p>

</div>

---

## 🧑‍💻 About Me

I'm a **Flutter developer and product builder** focused on turning ideas and business workflows into production-ready mobile applications.

I work across the full product journey:

```text
💡 Idea
  ↓
🎨 UI / UX
  ↓
📱 Flutter Application
  ↓
🧠 Architecture & State
  ↓
☁️ Backend & Database
  ↓
🔐 Auth / Payments / Notifications
  ↓
🚀 Deployment
  ↓
📈 Production
```

My main focus is building systems that are **clean, maintainable, secure and practical** — not just applications that look good in a demo.

---

## ⚡ What I Do

| 🛠️ Area | What I work on |
|---|---|
| 📱 **Flutter** | Android & iOS applications, responsive UI, animations |
| 🧠 **Architecture** | Riverpod, MVVM, Clean Architecture, repositories |
| ☁️ **Backend** | Supabase, PostgreSQL, Firebase, APIs |
| 💾 **Data** | Caching, offline-first flows, synchronization |
| 💳 **Payments** | Payment flows, server-side verification, settlements |
| 🔔 **Integrations** | FCM, WebView, APIs, deep links |
| 🚀 **Deployment** | Play Store, app releases, production setup |
| 🧩 **Reusable Code** | Flutter packages, modules and shared components |

---

# 🚀 What I'm Building

## FixitBhaii Solutions

### `Businesses → Mobile`

I'm building **FixitBhaii Solutions** as a focused mobile development studio.

The idea is simple:

> 🌐 **Businesses already have digital products. I help take them mobile.**

### 🔧 Core Services

```text
🌐 Website → 📱 Mobile App

🎨 Custom Flutter Development

☁️ Firebase / Supabase Backend

🔐 Authentication & Secure APIs

🔔 Push Notifications

💳 Payments & Business Workflows

🚀 Play Store Launch

🧩 Reusable Flutter Modules
```

🌐 **Website:** https://solutions.fixitbhaii.com/

---

# 🧱 How I Build

One of the areas I've spent significant time on is creating a Flutter structure where the UI isn't responsible for everything.

```mermaid
flowchart TD
    UI["🎨 Flutter Screen"]
    VM["🧠 ViewModel"]
    STATE["⚡ Riverpod State"]
    DOMAIN["🔧 Business Logic"]
    REPO["📦 Repository"]
    LOCAL["💾 Local Cache"]
    REMOTE["🌐 Remote Data Source"]
    API["☁️ Backend API"]
    DB[("🗄️ PostgreSQL / Supabase")]

    UI --> VM
    VM --> STATE
    STATE --> DOMAIN
    DOMAIN --> REPO

    REPO --> LOCAL
    REPO --> REMOTE

    REMOTE --> API
    API --> DB

    LOCAL -. "instant cached data" .-> REPO
    REPO -. "fresh state" .-> STATE
```

### 🎯 Principles

- 🎨 **UI stays focused on presentation**
- 🧠 **Business logic stays outside screens**
- ⚡ **State has a predictable owner**
- 📦 **Repositories abstract data sources**
- 💾 **Cache when it improves UX**
- 🌐 **Backend remains the source of truth**
- 🔐 **Sensitive operations are enforced server-side**
- 🧩 **Reusable solutions become packages/modules**

---

# 🏗️ A Bigger System I'm Building

## FixitBhaii Service Marketplace

A multi-sided platform connecting customers, vendors and technicians.

```mermaid
flowchart LR
    USER["👤 User App"]
    VENDOR["🏪 Vendor App"]
    TECH["🔧 Technician App"]
    ADMIN["🛡️ Admin App"]

    API["⚡ Backend"]
    CATALOG["📚 Master Service Catalog"]
    BOOKING["📅 Booking Engine"]
    WALLET["💰 Wallet & Settlement"]
    DB[("🗄️ PostgreSQL")]

    USER --> API
    VENDOR --> API
    TECH --> API
    ADMIN --> API

    API --> CATALOG
    API --> BOOKING
    API --> WALLET

    CATALOG --> DB
    BOOKING --> DB
    WALLET --> DB
```

### 📚 Master Service Catalog

```text
🏢 Division
   └── 📂 Category
        └── 📁 SubCategory
             └── 🔧 Service
```

The catalog acts as the central source of truth across:

`Vendor Onboarding` · `Technician Assignment` · `Discovery` · `Booking` · `Pricing` · `Add-ons` · `FAQs` · `Media`

---

# 🛠️ Tech Stack

### 📱 Mobile

<img src="https://skillicons.dev/icons?i=flutter,dart,android,apple" alt="Mobile stack" />

### ☁️ Backend

<img src="https://skillicons.dev/icons?i=firebase,supabase,postgres" alt="Backend stack" />

### 🧠 Architecture

`Riverpod` · `MVVM` · `Clean Architecture` · `Freezed` · `Repository Pattern`

### 🔌 Integrations

`REST APIs` · `WebView` · `FCM` · `Payments` · `Deep Links` · `Storage`

### 🚀 Delivery

`Git` · `GitHub` · `Play Console` · `CI/CD` · `Fastlane`

---

# 📦 Open Source

## 🔗 `fixit_webview`

A Flutter package created around one of the recurring problems I encountered while building mobile products:

### 🌐 Web → 📱 Mobile

The goal is to make WebView-based application wrappers more reusable instead of rebuilding the same foundation for every project.

**Focus:**

`Flutter` · `WebView` · `Navigation` · `Reusable Architecture`

🔗 **pub.dev:** [https://pub.dev/packages/fixit_webview]

---

# 💼 Selected Work

## 🔵 FixitBhaii

**Local Services Marketplace**

A multi-app ecosystem designed around:

👤 Customers  
🏪 Vendors  
🔧 Technicians  
🛡️ Administrators

### Core workflows

`Service Discovery` → `Booking` → `Vendor Assignment` → `Technician Assignment` → `Service Completion` → `Payment` → `Settlement`

---

## 🌐 Website → Mobile Systems

I've worked on the architecture required to transform web-based experiences into mobile products while adding native capabilities such as:

- 🔔 Push notifications
- 💾 Offline handling
- 🔗 Deep linking
- 📱 Native navigation
- 🚀 App-store deployment
- ⚡ Startup/performance optimization

---

# 🧠 Engineering Mindset

```text
┌─────────────────────────────────────────────┐
│              BUILDING > CODING              │
├─────────────────────────────────────────────┤
│                                             │
│  🔍 Understand the problem                  │
│       ↓                                     │
│  🧩 Design the system                       │
│       ↓                                     │
│  🏗️ Build the smallest solid version       │
│       ↓                                     │
│  🧪 Test the edge cases                     │
│       ↓                                     │
│  🔐 Secure the critical operations          │
│       ↓                                     │
│  🚀 Ship it                                 │
│       ↓                                     │
│  📈 Learn from production                   │
│       ↓                                     │
│  🔁 Improve it                               │
│                                             │
└─────────────────────────────────────────────┘
```

I don't want to just write more code.

I want to build **better systems**.

---

# 🌱 Currently Exploring

```text
📱 Advanced Flutter Architecture
🏗️ Scalable Marketplace Systems
☁️ Supabase + PostgreSQL
💾 Offline-First Applications
💳 Payment & Settlement Architecture
🧩 Reusable Flutter Packages
⚡ Application Performance
🚀 Product Engineering
```

# 🤝 Let's Connect

I'm always interested in:

💡 Interesting product ideas  
📱 Mobile development  
🏗️ Architecture discussions  
🧩 Open-source collaboration  
🚀 Building useful products

<div align="center">

<a href="https://github.com/Greatversion">
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>
<a href="https://www.linkedin.com/in/aditya-verma-87a346240/">
<img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="https://solutions.fixitbhaii.com/">
<img src="https://img.shields.io/badge/FixitBhaii%20Solutions-0993D9?style=for-the-badge&logo=google-chrome&logoColor=white" />
</a>

</div>

---

<div align="center">

### 💙 Code. Build. Improve. Repeat.

`Always learning.` · `Always building.` · `Always shipping.`

<img src="./assets/divider.svg" alt="divider" width="80%"/>

</div>
