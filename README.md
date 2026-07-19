# 🎓 Scholarstika - Multi-Tenant School Management System

A modern, scalable, cloud-based school management platform designed to streamline operations, enhance communication, and drive academic excellence across educational institutions.

![Next.js](https://img.shields.io/badge/Next.js-16.0-black?style=flat-square&logo=next.js)
![React](https://img.shields.io/badge/React-19.2-blue?style=flat-square&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue?style=flat-square&logo=typescript)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-4.1-38bdf8?style=flat-square&logo=tailwind-css)

## ✨ Features

### 🏢 **Multi-Tenancy & Branch Management**
- Manage multiple schools under one secure system
- Independent data isolation and custom branding per institution
- Multi-branch capability with centralized billing
- Branch-specific dashboards with local autonomy

### 🌍 **Landing Page & Public Website**
- **Core Pages** - Home, About Us, Features, Pricing, Contact Us, Book a Demo
- **Resources** - Blogs/News section for updates
- **Legal** - Privacy Policy, Terms & Conditions
- **Functionality** - Public-facing institution listing (`/institutions`)

### 🏫 **Global Admin (Institution Dashboard)**
- **Academics Management**
  - **Subjects & Classes** - Manage subjects, class sections
  - **Staff** - Allocation and management of academic staff
  - **Scheduling** - Class timetables and schedules
  - **Transitions** - Student transfer and promotion management
- **Financial & Fee Management**
  - **Fees** - Configure student fees, optional fees
  - **Transactions** - View and manage payment transactions
  - **Earnings** - Overview of institution earnings
  - **Payroll** - Manage staff payroll
- **Reports & Analytics**
  - **Academic** - Exam reports, Student performance reports
  - **Financial** - Financial revenue/expense reports
- **Administration**
  - **Branch Management** - Oversee multiple branches
  - **Announcements** - Broadcast announcements
  - **Staff & Student Management** - Comprehensive directories and profiles

### 🏢 **Branch Admin**
- **Identity & Certificates**
  - **Templates** - Manage certificate templates
  - **ID Cards** - Generate and manage Staff IDs and Student IDs
- **Branch Operations**
  - **Academics** - Branch-specific exam and fee management
  - **People** - Manage branch staff and students
  - **Payroll** - Branch-level payroll administration

### 👨‍🏫 **Teacher**
- **Classroom Management**
  - **Classes** - View and manage assigned classes
  - **Attendance** - Mark and track student attendance
  - **Grades** - Input and update student grades
- **Learning Resources**
  - **Assignments** - Create and track assignments
  - **Resources** - Upload and share study materials
- **Productivity**
  - **Schedule** - Personal class schedule view
  - **Communication** - Internal messaging system

### 🎓 **Student**
- **Academics**
  - **Assignments** - View and submit assignments
  - **Grades** - Check exam results and grading history
  - **Resources** - Access study materials and downloads
  - **Schedule** - View personal class timetable
  - **Attendance** - Monitor own attendance records
- **Support** - Access student support/helpdesk

### 👪 **Parent**
- **Child Monitoring**
  - **Dashboard** - Overview of children's activities
  - **Health** - View health records/notifications
- **Communication**
  - **Messages** - Direct communication with school staff
  - **Notifications** - Receive important alerts
  - **Parent Communication** - Dedicated channel for school updates

### 🏥 **School Nurse**
- **Health Management**
  - **Records** - Maintain student health records
  - **Immunizations** - Track vaccination and immunization status
- **Incident Response**
  - **Incidents** - Log and report injuries or medical incidents
- **Communication**
  - **Alerts** - Notify parents/guardians

### 💰 **Finance Administration (Bursar)**
- **Fee Management**
  - **Collections** - Manage student fee collections
  - **Scholarships** - Manage student scholarships and grants
  - **Optional Fees** - Handle miscellaneous/optional payments
- **Financial Operations**
  - **Transactions** - Detailed transaction logging and auditing
  - **Reports** - Generate financial status reports

### 🎨 **Modern UI/UX**
- Responsive design optimized for mobile, tablet, and desktop
- Beautiful gradient backgrounds and smooth animations
- Accessible components built with Radix UI
- Dark mode support with next-themes

## 🚀 Tech Stack

### **Frontend**
- **Framework:** Next.js 16.0 (App Router)
- **Language:** TypeScript 5
- **UI Library:** React 19.2
- **Styling:** Tailwind CSS 4.1
- **Components:** Radix UI, shadcn/ui
- **Icons:** Lucide React
- **Animations:** Tailwind Animate, tw-animate-css

### **Development Tools**
- **Form Handling:** React Hook Form + Zod validation
- **State Management:** React Hooks
- **Analytics:** Vercel Analytics
- **Charts:** Recharts
- **Date Handling:** date-fns


## 🏗️ Project Structure

```
scholarstika--saas-development/
├── app/                      # Next.js App Router pages
│   ├── about/               # About page
│   ├── auth/                # Authentication pages (login, signup, etc.)
│   ├── blog/                # Blog section
│   ├── contact/             # Contact page
│   ├── features/            # Features showcase
│   ├── pricing/             # Pricing plans
│   ├── institutions/        # Institution details
│   └── page.tsx             # Home page
├── components/              # React components
│   ├── common/              # Shared components (Header, Footer)
│   ├── home/                # Home page sections
│   └── ui/                  # shadcn/ui components
├── hooks/                   # Custom React hooks
├── lib/                     # Utility functions
├── public/                  # Static assets
│   ├── hero/                # Hero section images
│   ├── features/            # Feature images
│   └── ...
└── styles/                  # Global styles
```

## 🎨 Key Pages

- **Home** (`/`) - Landing page with hero, features, institutions showcase
- **Features** (`/features`) - Comprehensive feature list
- **Pricing** (`/pricing`) - Pricing plans with enterprise calculator
- **About** (`/about`) - Company information and mission
- **Blog** (`/blog`) - Educational content and updates
- **Contact** (`/contact`) - Contact form and information
- **Authentication** (`/auth/*`) - Login, signup, password recovery

## 🎯 Key Features Implementation

### Responsive Design
All components are fully responsive with mobile-first approach:
- Mobile: Optimized layouts and touch-friendly interfaces
- Tablet: Balanced grid layouts
- Desktop: Full-featured experience with advanced interactions

### Multi-Tenant Architecture
- Isolated data per institution
- Custom branding and configuration
- Centralized management dashboard
- Branch-specific access controls

### Enterprise Features
- Dynamic pricing calculator
- Custom integrations support
- Dedicated account management
- 24/7 priority support
- SLA guarantees

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📄 License

This project is private and proprietary.

## 👥 Team

Developed by the Scholarstika team for modern educational institutions.

**Built with ❤️ for Schools & Education**
