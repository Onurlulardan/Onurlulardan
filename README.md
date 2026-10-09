# Onur Altuntaş
### Full Stack Engineer · Go · React · TypeScript · PostgreSQL

![Profile Views](https://komarev.com/ghpvc/?username=Onurlulardan&style=flat-square&color=blue)
[![GitHub](https://img.shields.io/badge/GitHub-Onurlulardan-181717?style=flat-square&logo=github)](https://github.com/Onurlulardan)
[![ForgeCRUD](https://img.shields.io/badge/ForgeCRUD-forgecrud.io-0A66C2?style=flat-square&logo=googlechrome&logoColor=white)](https://forgecrud.io)

👋 I'm a Full Stack Engineer based in **Sakarya, Turkey**. I build production-grade operational software, including ERP systems, workflow automation and internal business tools. My main stack is **Go, React, TypeScript and PostgreSQL**. I care about clean architecture, role-based security and containerized deployments that go from `docker compose up` to production without surprises.

**My Specializations:** ERP & Operations Platforms | SaaS Architecture | Go Microservices | React Component Design | Docker-based Deployment

---

## 🚀 What I'm Building

### [ForgeCRUD](https://forgecrud.io)

ForgeCRUD is my main project. It is an **on-premise, no-code ERP and operations platform** for manufacturing and logistics companies. It covers:

- Dynamic forms and workflow automation
- Inventory, production and purchasing
- Accounting, CRM and HR
- AI-assisted operations

Several of my open-source repositories come from the architectural patterns I developed while building ForgeCRUD.

---

## 💻 Technical Expertise

I mostly work across the full stack. I write typed frontends in React and Next.js, and I build service-oriented backends in Go. Docker ties both sides together.

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)

**Backend & Frameworks**

![Gin](https://img.shields.io/badge/Gin-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![.NET](https://img.shields.io/badge/.NET_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)

**Data & Messaging**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO-C72E49?style=for-the-badge&logo=minio&logoColor=white)

**DevOps & Tooling**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

| Area | Tools I use |
|------|-------------|
| **ORM & Data Access** | Drizzle, GORM, Entity Framework |
| **Auth & Security** | Auth.js, JWT, RBAC, rate limiting |
| **Real-time** | WebSockets, real-time notification services |
| **Delivery** | Docker Compose, supervisord, GHCR image publishing |

---

## 🎯 Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🔥 <a href="https://github.com/Onurlulardan/ForgeStart">ForgeStart</a></h3>
      <p><strong>Next.js • TypeScript • Auth.js • Drizzle • PostgreSQL • Docker</strong></p>
      <p>I built ForgeStart as an open-source, production-ready SaaS starter. It is based on the architectural patterns I use in ForgeCRUD. It ships with authentication, RBAC, an admin UI, i18n, file uploads and a real-time server layer.</p>
      <p><b>My Contribution:</b> I designed the modular, per-table database schema. I also implemented runtime environment injection for Next.js, automatic PostgreSQL initialization, and supervisord-based migration orchestration. On top of that, I added an email provider service and a real-time infrastructure.</p>
      <p><b>What I learned:</b> I learned how to make a single Docker image configurable at runtime and safe to expose. One example is binding Compose ports to a configurable host address.</p>
      <p>📝 40 commits • ⭐ 21 stars</p>
    </td>
    <td width="50%" valign="top">
      <h3>🧩 <a href="https://github.com/Onurlulardan/react-lookup-select">react-lookup-select</a></h3>
      <p><strong>React • TypeScript • tsup • CSS</strong></p>
      <p>I created this headless, accessible React lookup and select component, and I published it on <a href="https://www.npmjs.com/package/react-lookup-select">npm</a>. It opens a modal with a data grid for single or multiple selection. This is the kind of control that ERP forms need constantly.</p>
      <p><b>My Contribution:</b> I built it end to end. That includes the type-safe API, the custom rendering capabilities and the selection-change semantics, which trigger only when the modal closes. I also set up the tsup build, the ESLint config and versioned releases up to v1.1.0.</p>
      <p><b>What I learned:</b> I learned how to design a headless component API that stays flexible without sacrificing type safety or accessibility.</p>
      <p>📝 40 commits • ⭐ 5 stars</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>⚙️ <a href="https://github.com/Onurlulardan/go-microservice-sample">go-microservice-sample</a></h3>
      <p><strong>Go • Gin • GORM • PostgreSQL • MinIO • Docker Compose</strong></p>
      <p>I built this as the microservices backend blueprint for ForgeCRUD. It includes the following services:</p>
      <ul>
        <li>API Gateway</li>
        <li>Auth</li>
        <li>Permission</li>
        <li>Core</li>
        <li>Notification</li>
        <li>Document</li>
      </ul>
      <p>The services run on Docker Compose.</p>
      <p><b>My Contribution:</b> I implemented JWT authentication, RBAC, rate limiting, real-time WebSocket notifications and MinIO-backed document storage. I also set up a unified response encoding layer and a GitHub Actions pipeline that builds and pushes images to GHCR.</p>
      <p><b>What I learned:</b> I learned how to draw service boundaries for a permission-heavy business application and how to keep cross-service responses consistent.</p>
      <p>📝 8 commits • ⭐ 4 stars</p>
    </td>
    <td width="50%" valign="top">
      <h3>🧹 <a href="https://github.com/Onurlulardan/cleanFlow">CleanFlow</a></h3>
      <p><strong>C# • .NET Core • Docker • GitHub Actions</strong></p>
      <p>I developed this backend for cleaning-operations automation. It assigns tasks to cleaning staff, generates daily work orders and handles photo-based reporting for supervisors and auditors.</p>
      <p><b>My Contribution:</b> I built the domain model and the DTOs, including auditor work orders. I also containerized the service and created a Docker publish workflow for automated image delivery.</p>
      <p><b>What I learned:</b> This was my first full operational-workflow backend. It shaped how I later approached work orders and task flows in ForgeCRUD.</p>
      <p>📝 34 commits</p>
    </td>
  </tr>
</table>

<details>
<summary><b>📂 Earlier projects</b></summary>

<br>

- **[pdftoworldconverter](https://github.com/Onurlulardan/pdftoworldconverter)**: A Node.js and Express web app that converts PDF files to Word (.docx). It has a drag-and-drop upload interface.
- **[Not](https://github.com/Onurlulardan/Not)**: A full-stack note-taking app with a MongoDB-backed API and token-based authentication. ⭐ 4
- **[rokData](https://github.com/Onurlulardan/rokData)**: A responsive Next.js and TypeScript data application.
- **[ParallaxBackGround](https://github.com/Onurlulardan/ParallaxBackGround)**: A vanilla JavaScript parallax effect experiment. There is a [live demo](https://exquisite-cocada-60ca21.netlify.app/).

</details>

---

## 📊 GitHub Statistics

![GitHub Stats](https://gitfolio.dcoder.io/api/stats/Onurlulardan?theme=professional&show_icons=true)

![Top Languages](https://gitfolio.dcoder.io/api/top-langs/Onurlulardan?theme=professional&layout=compact&langs_count=8)

### At a Glance

| Metric | Value |
|--------|------:|
| Projects | **13** |
| Total Commits | **190** |
| Stars Received | **57** |
| Estimated Lines of Code | **~31.6K** |
| Active Since | **2021** |

### Language Distribution

| Language | Share |
|----------|------:|
| TypeScript | 45.8% |
| JavaScript | 23.5% |
| Go | 21.6% |
| C# | 4.6% |
| CSS | 2.2% |

---

## 🌱 My Journey

- **2022–2023:** I started with vanilla JavaScript UI experiments and full-stack Node.js and MongoDB apps. Then I moved into Next.js and TypeScript.
- **2024:** I built CleanFlow, my first operational automation backend, in .NET Core. It was containerized and delivered through CI.
- **2025:** I designed the ForgeCRUD backend as Go microservices. I also published `react-lookup-select` to npm and started ForgeStart.
- **2026:** I'm focused on ForgeCRUD and on hardening ForgeStart for real-world deployments, including runtime configuration, automated migrations and real-time infrastructure.

I also give back to the Turkish developer community. My open-source work is listed in [awesome-tr](https://github.com/miratcan/awesome-tr), a curated guide to open-source projects by Turkish developers.

---

## 🤝 Let's Connect

I'm open to talking about ERP and operations software, SaaS architecture, Go backends, and collaboration on open-source tooling. If you're building something in this space, or if you'd like to use or contribute to ForgeStart or react-lookup-select, feel free to reach out.

- 🌐 **ForgeCRUD:** [forgecrud.io](https://forgecrud.io)
- 💻 **GitHub:** [@Onurlulardan](https://github.com/Onurlulardan)
- 📦 **npm:** [react-lookup-select](https://www.npmjs.com/package/react-lookup-select)

⭐ If one of my projects saves you time, a star is always appreciated!
