<div align="center">

<!-- Hero Banner & Header Logo -->
<a href="https://github.com/TAIJULAMAN/Multy-Tenant-School-Management-scholarstika">
  <img src="./public/logo.png" alt="Scholarstika Logo" width="260" />
</a>

<br />
<br />

<a id="overview"></a>
# Scholarstika — Multi-Tenant School Management Platform

**A unified, cloud-native educational ERP and multi-tenant SaaS platform empowering institutions, branches, educators, parents, and students with isolated data governance, automated academics, and seamless financial operations.**

<br />

<a id="tech-stack"></a>
<!-- Tech Stack Badges (for-the-badge style) -->
[![Next.js 16](https://img.shields.io/badge/Next.js%2016-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)](https://nextjs.org/)
[![React 19](https://img.shields.io/badge/React%2019-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://react.dev/)
[![TypeScript 5](https://img.shields.io/badge/TypeScript%205-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Tailwind CSS 4](https://img.shields.io/badge/Tailwind%20CSS%204-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![Redux Toolkit](https://img.shields.io/badge/Redux%20Toolkit-764ABC?style=for-the-badge&logo=redux&logoColor=white)](https://redux-toolkit.js.org/)
[![Radix UI](https://img.shields.io/badge/Radix%20UI-161618?style=for-the-badge&logo=radixui&logoColor=white)](https://www.radix-ui.com/)
[![Zod](https://img.shields.io/badge/Zod%20Validation-3E67B1?style=for-the-badge&logo=zod&logoColor=white)](https://zod.dev/)
[![Vercel Analytics](https://img.shields.io/badge/Vercel%20Analytics-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://vercel.com/analytics)
[![License](https://img.shields.io/badge/License-Proprietary-red?style=for-the-badge)](#license)

<br />

<a id="cta-links"></a>
<!-- Live Demo & CTA Links -->
<p align="center">
  <a href="https://scholarstika.org"><b>🌐 Explore Live Demo</b></a> &nbsp;•&nbsp;
  <a href="#architecture"><b>🏗️ Architecture</b></a> &nbsp;•&nbsp;
  <a href="#core-features"><b>✨ Core Features</b></a> &nbsp;•&nbsp;
  <a href="https://github.com/TAIJULAMAN/Multy-Tenant-School-Management-scholarstika/issues"><b>🐛 Report Bug</b></a> &nbsp;•&nbsp;
  <a href="https://github.com/TAIJULAMAN/Multy-Tenant-School-Management-scholarstika/issues"><b>✨ Request Feature</b></a> &nbsp;•&nbsp;
  <a href="mailto:admin@scholarstika.org"><b>📬 Contact Sales</b></a>
</p>

<br />

<!-- Hero Banner Graphic -->
<img src="./public/hero.png" alt="Scholarstika Platform Overview" width="100%" />

</div>

---

## 📑 Table of Contents

- [🌟 Title & Value Proposition](#overview)
- [🛠️ Tech Stack Badges](#tech-stack)
- [🔗 Live Demo & CTA Links](#cta-links)
- [🖼️ Interface Preview](#interface-preview)
- [✨ Core Features & Role Portals](#core-features)
  - [🏢 Multi-Tenancy & Multi-Branch Architecture](#multi-tenancy)
  - [🏫 Global Institution Admin Portal](#global-admin)
  - [🏛️ Branch Admin Operations](#branch-admin)
  - [👨‍🏫 Teacher Classroom & Evaluation Suite](#teacher-suite)
  - [🎓 Student Academic & Resource Hub](#student-hub)
  - [👪 Parent Real-Time Child Tracking](#parent-tracking)
  - [🏥 School Nurse & Health Incident Center](#nurse-center)
  - [💰 Bursar & Financial Administration](#finance-admin)
  - [🌐 Public Landing & Institutional Discovery](#public-discovery)
- [🏗️ Engineering Highlights & Architecture](#architecture)
  - [Role-Based Access Control (RBAC) Matrix](#rbac-matrix)
- [📂 Project Directory Structure](#project-structure)
- [👨‍💻 Developer Info & Socials](#developer-info)
- [📄 License & Proprietary Notice](#license)

---

<a id="interface-preview"></a>
## 🖼️ Interface Preview

Experience role-tailored dashboards and a modern, responsive design built with Tailwind CSS 4 and Radix UI primitives.

| **Institution & Administrative Control** | **Branch & Academic Analytics** |
| :---: | :---: |
| <img src="./public/admin-dashboard-illustration.png" alt="Admin Dashboard Overview" width="480" /> | <img src="./public/school-dashboard-charts-illustration.jpg" alt="School Dashboard Analytics" width="480" /> |
| *Centralized multi-tenant institution overview* | *Real-time academic performance & metrics* |

| **Multi-Tenant Scalability** | **Student & Mobile First Experience** |
| :---: | :---: |
| <img src="./public/features/Multi-Tenant.png" alt="Multi-Tenant System" width="480" /> | <img src="./public/mobile-app-students-illustration.jpg" alt="Mobile App & Student Portal" width="480" /> |
| *Independent tenant branding & data isolation* | *Optimized for tablets, smartphones, and web* |

---

<a id="core-features"></a>
## ✨ Core Features & Role Portals

Scholarstika is architected around granular, persona-driven workflows to serve every stakeholder in the educational lifecycle.

<a id="multi-tenancy"></a>
### 🏢 **Multi-Tenancy & Multi-Branch Architecture**
- **Complete Data Isolation**: Logical data segregation safeguarding institutional privacy across diverse organizations.
- **Custom Branding per Tenant**: White-label capability supporting unique school logos, colors, and domains.
- **Centralized Billing & Subscriptions**: Tiered subscription management with branch-level quota oversight.
- **Hierarchical Governance**: Global administrators manage institutions while branch admins retain local operational autonomy.

<a id="global-admin"></a>
### 🏫 **Global Institution Admin Portal**
- **Academics & Curricula**: Full catalog management of subjects, class sections, timetables, and academic terms.
- **Faculty & Staff Allocation**: Central staff directory, role assignments, department structuring, and workload balance.
- **Transitions & Promotions**: Automated academic transitions, student promotions, and multi-branch transfer workflows.
- **Enterprise Reporting**: Institution-wide academic trends, exam distributions, and consolidated revenue reports.

<a id="branch-admin"></a>
### 🏛️ **Branch Admin Operations**
- **Identity & Credentials**: Built-in visual designer to generate and print custom Student & Staff ID Cards with QR verification.
- **Certificate Templates**: Issue diplomas, honor rolls, and transfer certificates using dynamic template engines.
- **Branch Operations**: Localized exam scheduling, attendance policies, and branch staff payroll processing.

<a id="teacher-suite"></a>
### 👨‍🏫 **Teacher Classroom & Evaluation Suite**
- **Classroom Roster**: View allocated classrooms, student profiles, and historical performance trajectories.
- **Attendance Registry**: Daily and period-based attendance marking with automated absence flags.
- **Gradebook & Assessments**: Digital grading rubrics, assignment submission reviews, and weighted grading scales.
- **Resource Repository**: Upload course syllabus, assignments, and lecture notes directly to classes.

<a id="student-hub"></a>
### 🎓 **Student Academic & Resource Hub**
- **Self-Service Dashboard**: Real-time view of upcoming homework deadlines, exam dates, and attendance records.
- **Assignment Submissions**: Integrated assignment tracker supporting digital file uploads and status tracking.
- **Report Cards**: Instant access to term evaluations, GPA calculation, and teacher feedback.
- **Timetable & Schedule**: Interactive daily schedule with room and instructor details.

<a id="parent-tracking"></a>
### 👪 **Parent Real-Time Child Tracking**
- **Multi-Child Dashboard**: Seamlessly switch between multiple enrolled siblings within a unified account.
- **Academic & Attendance Alerts**: Real-time SMS and email notifications regarding absences and grade updates.
- **Direct School Messaging**: Secure communication channels connecting parents with teachers and principals.
- **Medical & Clinic Visibility**: Immediate updates when children visit the school health clinic.

<a id="nurse-center"></a>
### 🏥 **School Nurse & Health Incident Center**
- **Electronic Health Records (EHR)**: Secure storage of allergies, chronic conditions, and emergency contacts.
- **Immunization Tracking**: Compliance tracking for state/country required vaccinations.
- **Incident & Clinic Logs**: Timely reporting of medical visits, first aid incidents, and parent notification dispatches.

<a id="finance-admin"></a>
### 💰 **Bursar & Financial Administration**
- **Fee Structures**: Configurable tuition templates, optional fees (transportation, laboratory, lunch), and discounts.
- **Scholarship & Aid Programs**: Grant allocation and automated tuition fee waiver adjustments.
- **Audit Trails**: Ledger recording all incoming receipts, outgoing expenses, and payroll settlements.
- **Financial Analytics**: Revenue forecasting and delinquency tracking with printable PDF receipts (`html2pdf.js`).

<a id="public-discovery"></a>
### 🌐 **Public Landing & Institutional Discovery**
- **Marketing Suite**: Comprehensive landing pages (Home, About Us, Features, Pricing Calculator, FAQ, Contact Us).
- **Public Directory (`/institutions`)**: Searchable index of accredited institutions powered by Scholarstika.
- **Resource Center**: Built-in educational blog and product announcements hub.

---

<a id="architecture"></a>
## 🏗️ Engineering Highlights & Architecture

Scholarstika leverages modern software engineering patterns to ensure high availability, strong type safety, and zero-latency user interactions.

```
+-----------------------------------------------------------------------------------+
|                                Client Layer (Browser)                             |
|  Next.js 16 App Router | React 19 | Tailwind CSS 4 | Radix UI | Redux Persist     |
+-----------------------------------------------------------------------------------+
                                         │
                                         ▼ (Type-safe RTK Query Hooks)
+-----------------------------------------------------------------------------------+
|                                State & API Gateway Layer                          |
|  Redux Toolkit Slice Store | baseApi.ts | JWT Authorization Interceptors          |
+-----------------------------------------------------------------------------------+
                                         │
                                         ▼ (REST API / Subdomain Multi-Tenant Router)
+-----------------------------------------------------------------------------------+
|                              Microservices / Backend API                          |
|  Tenant Scoping Middleware | Role-Based Access Control (RBAC) | Validation (Zod)  |
+-----------------------------------------------------------------------------------+
                                         │
                                         ▼
+-----------------------------------------------------------------------------------+
|                                Database & Cloud Storage                           |
|  Multi-Tenant Database Isolation | Assets & Documents Storage | Cloud Infrastructure |
+-----------------------------------------------------------------------------------+
```

<a id="rbac-matrix"></a>
### Role-Based Access Control (RBAC) Matrix

| Feature / Domain | Global Admin | Branch Admin | Teacher | Student | Parent | Nurse | Bursar |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| **Institution Settings** | Full Access | View Only | ❌ | ❌ | ❌ | ❌ | ❌ |
| **Branch Operations** | Full Access | Full Access | ❌ | ❌ | ❌ | ❌ | ❌ |
| **Classroom & Grading** | Manage | Manage | Full Access | View Only | View Only | ❌ | ❌ |
| **Assignments & Notes** | View | View | Full Access | Submit/View | View | ❌ | ❌ |
| **Fee Collection & Payroll** | Full Access | Branch Level | ❌ | ❌ | Pay Fees | ❌ | Full Access |
| **Medical & Health Logs** | View Reports | View Reports | ❌ | ❌ | View Only | Full Access | ❌ |
| **ID Card & Certificates** | Generate | Generate | ❌ | View | View | ❌ | ❌ |

---

<a id="project-structure"></a>
## 📂 Project Directory Structure

```plaintext
Multy-Tenant-School-Management-scholarstika/
├── app/                        # Next.js 16 App Router pages and layouts
│   ├── (auth)/                 # Authentication routes (login, register, forgot-password)
│   ├── about/                  # Company story, vision, and team page
│   ├── blog/                   # Educational articles and product updates
│   ├── contact/                # Contact and support inquiries
│   ├── features/               # Platform feature breakdown
│   ├── institutions/           # Public directory of enrolled institutions
│   ├── pricing/                # Plan comparison and dynamic enterprise calculator
│   └── page.tsx                # High-converting SaaS landing page
├── components/                 # Atomic design React component hierarchy
│   ├── common/                 # Global shared components (Navigation, Footer, Modals)
│   ├── home/                   # Landing page presentation blocks (Hero, Stats, CTA)
│   └── ui/                     # Accessible, unstyled-primitive shadcn & Radix UI widgets
├── config/                     # Application configurations & dynamic environment handlers
│   └── envConfig.ts            # Base URL resolution & API version routing
├── hooks/                      # Custom business logic & viewport hooks
├── lib/                        # Formatting utilities, tailwind-merge, clsx helpers
├── public/                     # Static production assets
│   ├── features/               # Feature illustration previews
│   ├── hero/                   # High-res landing page banners
│   ├── images/                 # Header & badge graphics
│   └── logo.png                # Official Scholarstika brand identity
├── redux/                      # Enterprise state layer powered by Redux Toolkit
│   ├── features/               # Domain-specific RTK Query API slice definitions
│   │   ├── auth/               # Authentication & token renewal endpoints
│   │   ├── branchManagement/   # Multi-branch orchestration API
│   │   ├── assignments/        # Student homework & submission endpoints
│   │   └── baseApi.ts          # Centralized RTK Query entry point
│   ├── Slice/                  # Synchronous slices (authSlice, preferences)
│   └── store.ts                # Redux store configured with redux-persist
├── styles/                     # Tailwind CSS 4 global style definitions
├── .env.example                # Canonical environment variable blueprint
├── components.json             # shadcn/ui configuration metadata
└── package.json                # Project dependencies, scripts, and build pipeline
```

---

<a id="developer-info"></a>
## 👨‍💻 Developer Info & Socials

Scholarstika is built and actively maintained by a team of full-stack engineers and education-technology specialists.

### Core Engineering & Maintainers

- **Md Shah Aman Patwary** — *Lead Full-Stack Software Engineer*
  - 🌐 GitHub: [@TAIJULAMAN](https://github.com/TAIJULAMAN)
  - 💼 LinkedIn: [Md Shah Aman Patwary](https://linkedin.com/in/taijulaman)
  - 📧 Email: [taijulaman8@gmail.com](mailto:taijulaman8@gmail.com)

- **DbHridoy** — *Full-Stack Engineer & Core Contributor*
  - 🌐 GitHub: [@DbHridoy](https://github.com/DbHridoy)
  - 📧 Email: [mdnuralam378@gmail.com](mailto:mdnuralam378@gmail.com)

---

<a id="license"></a>
## 📄 License & Proprietary Notice

Copyright © 2026 Scholarstika. All rights reserved.

This software, including its design, backend architecture, and intellectual property, is private and proprietary. Unauthorized copying, distribution, modification, public display, or commercial exploitation without prior written consent from Scholarstika is strictly prohibited.

<div align="center">
  <b>Built with ❤️ for educational excellence across the globe</b>
</div>
