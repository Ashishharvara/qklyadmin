# Qkly Admin App 🚀

Qkly Admin ek powerful React Native mobile application hai jo admin panel ke liye banaya gaya hai. Is app mein aap users, services, reports, aur payments ko manage kar sakte hain.

![React Native](https://img.shields.io/badge/React%20Native-0.83.1-blue?style=for-the-badge&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5.8.3-blue?style=for-the-badge&logo=typescript)
![Navigation](https://img.shields.io/badge/React%20Navigation-7.9.1-green?style=for-the-badge)

---

## 📱 App Features

### 🔐 Authentication
- Secure login system
- Demo credentials
- Session management
- Logout functionality

### 📊 Dashboard
- **Key Metrics Display**
  - Total Users
  - Active Services
  - Revenue tracking
  - Reports overview
- **User Analytics**
  - Daily Active Users (DAU)
  - Monthly Active Users (MAU)
  - New users today
- **Conversion Funnel**
  - Viewed → Contacted
  - Contacted → Requested
  - Requested → Accepted
  - Accepted → Reviewed
- **Revenue Breakdown**
  - Today's revenue
  - Renewal rate
- **Trust & Safety**
  - Complaints per service
  - Average resolution time
  - Services removed
- **Quick Actions**
  - Users management
  - Services management
  - Reports management
  - Payments access

### 👥 User Management
- User list view
- Search users by name, email, phone
- Filter by status (active, blocked, all)
- Sort by newest, oldest, most services, most reports
- View user details
- Block/unblock users
- Delete users

### 🛠️ Service Management
- Service list with details
- Search by title, description, provider
- Filter by status and category
- Sort by newest, oldest, most views, most contacts
- Hide/remove services
- Mark as suspicious
- View service analytics

### ⚠️ Reports Management
- Reports list with priority indicators
- Filter by type, status, priority
- Search by reporter/reported name
- Sort by priority or date
- Actions:
  - Ignore report
  - Warn user
  - Block user
  - Remove service

### 💳 Payments Management
- Payment transactions list
- Filter by status, method, plan type
- Search by user name, email, transaction ID
- View payment details
- Refund payments

### 🎨 Theme Support
- Dark mode (default)
- Light mode support
- Custom color palette
- Status colors
- Priority colors

---

## 🏗️ Project Structure

```
qklyadmin/
├── src/
│   ├── assets/
│   │   ├── icons/
│   │   └── images/
│   ├── components/
│   │   ├── analytics/
│   │   ├── common/
│   │   │   ├── Avatar.tsx
│   │   │   ├── Badge.tsx
│   │   │   ├── Button.tsx
│   │   │   ├── Card.tsx
│   │   │   ├── EmptyState.tsx
│   │   │   ├── Header.tsx
│   │   │   ├── Input.tsx
│   │   │   ├── Spinner.tsx
│   │   │   └── index.ts
│   │   └── layout/
│   ├── context/
│   │   ├── AnalyticsContext.tsx
│   │   ├── AuthContext.tsx
│   │   ├── PaymentContext.tsx
│   │   ├── ReportContext.tsx
│   │   ├── ServiceContext.tsx
│   │   ├── ThemeContext.tsx
│   │   ├── UserContext.tsx
│   │   └── index.ts
│   ├── navigation/
│   │   ├── AppNavigator.tsx
│   │   ├── BottomTabBar.tsx
│   │   ├── Stacks.tsx
│   │   └── index.ts
│   ├── screens/
│   │   ├── auth/
│   │   │   ├── LoginScreen.tsx
│   │   │   └── index.ts
│   │   ├── dashboard/
│   │   │   ├── DashboardHome.tsx
│   │   │   └── index.ts
│   │   ├── payments/
│   │   │   ├── PaymentDetailScreen.tsx
│   │   │   ├── PaymentsListScreen.tsx
│   │   │   └── index.ts
│   │   ├── reports/
│   │   │   ├── ReportDetailScreen.tsx
│   │   │   ├── ReportsListScreen.tsx
│   │   │   └── index.ts
│   │   ├── services/
│   │   │   ├── ServiceDetailScreen.tsx
│   │   │   ├── ServiceListScreen.tsx
│   │   │   └── index.ts
│   │   ├── settings/
│   │   ├── users/
│   │   │   ├── UserDetailScreen.tsx
│   │   │   ├── UserListScreen.tsx
│   │   │   └── index.ts
│   │   └── index.ts
│   ├── services/
│   │   ├── api.ts
│   │   ├── index.ts
│   │   └── mockData.ts
│   ├── theme/
│   │   ├── colors.ts
│   │   ├── index.ts
│   │   └── typography.ts
│   ├── types/
│   │   ├── analytics.ts
│   │   ├── index.ts
│   │   ├── payment.ts
│   │   ├── react-native-vector-icons.d.ts
│   │   ├── report.ts
│   │   ├── service.ts
│   │   └── user.ts
│   ├── utils/
│   │   ├── constants.ts
│   │   ├── formatters.ts
│   │   ├── helpers.ts
│   │   ├── index.ts
│   │   └── validators.ts
│   └── App.tsx
├── android/
├── ios/
├── .eslintrc.js
├── .gitignore
├── .prettierrc.js
├── App.tsx
├── babel.config.js
├── index.js
├── jest.config.js
├── metro.config.js
├── package.json
└── tsconfig.json
```

---
## 📦 Dependencies

### Core
- **react**: ^19.2.0
- **react-native**: ^0.83.1

### Navigation
- **@react-navigation/native**: ^7.1.27
- **@react-navigation/native-stack**: ^7.9.1
- **@react-navigation/bottom-tabs**: ^7.9.1

### UI Components
- **react-native-paper**: ^5.14.5
- **react-native-safe-area-context**: ^5.6.2
- **react-native-screens**: ^4.18.0
- **react-native-vector-icons**: ^10.3.0

### Charts & Analytics
- **react-native-chart-kit**: ^6.12.0

### Utilities
- **date-fns**: ^4.1.0
- **uuid**: ^13.0.0

---


## 🎨 Theme Colors

### Dark Mode (Default)
| Color | Value |
|-------|-------|
| Primary | `#60A5FA` |
| Secondary | `#A78BFA` |
| Success | `#34D399` |
| Warning | `#FBBF24` |
| Error | `#F87171` |
| Background | `#0F172A` |
| Surface | `#1E293B` |

### Light Mode
| Color | Value |
|-------|-------|
| Primary | `#2563EB` |
| Secondary | `#7C3AED` |
| Success | `#10B981` |
| Warning | `#F59E0B` |
| Error | `#EF4444` |
| Background | `#0F172A` |
| Surface | `#FFFFFF` |

---

## 📱 Screens Overview

| Screen | Route | Description |
|--------|-------|-------------|
| Login | Login | Admin login screen |
| Dashboard | Main → Dashboard | Main dashboard with analytics |
| Users List | Main → Users → UserList | User management list |
| User Detail | Main → Users → UserDetail | User details view |
| Services List | Main → Services → ServiceList | Service management list |
| Service Detail | Main → Services → ServiceDetail | Service details view |
| Reports List | Main → Reports → ReportsList | Reports management list |
| Report Detail | Main → Reports → ReportDetail | Report details view |
| Payments List | Main → Payments → PaymentsList | Payment transactions list |
| Payment Detail | Main → Payments → PaymentDetail | Payment details view |

---

## 🔐 API Authentication

The app uses JWT-based authentication with mock data.

**Demo Credentials:**
- Email: `admin@qkly.com`
- Password: `admin123`

**Mock Token:** `mock-jwt-token`

---



## 📄 License

This project is proprietary software. All rights reserved.

## 🤝 Contributing

This is an academic/student project. For inquiries:
- **Developer**: [Ashish Harvara]
- **Email**: [ashishharvara111@gmail.com]


## 📌 Version History

| Version | Date | Changes |
|---------|------|---------|
| 1.0.0 | Current | Initial release with core features |

---

**Built with ❤️ using React Native**

