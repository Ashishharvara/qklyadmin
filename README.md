# Qkly - Service Provider Marketplace App

A React Native mobile application for connecting users with local service providers. The app supports multiple service categories including AC repair, cleaning, electrician, plumbing, carpentry, tailoring, laundry, and mobile repair services.

![React Native](https://img.shields.io/badge/React%20Native-0.80.2-61DAFB?style=flat-square&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue?style=flat-square&logo=typescript)
![Firebase](https://img.shields.io/badge/Firebase-23.5.0-FFCA28?style=flat-square&logo=firebase)
![React Navigation](https://img.shields.io/badge/React%20Navigation-v7-61DAFB?style=flat-square&logo=react)

## 📱 App Features

### 🔐 Authentication
- Email/Password authentication via Firebase Auth
- Google Sign-In integration
- Facebook Sign-In integration
- Secure user session management

### 🛠️ Services
- Multiple service categories:
  - AC Repair
  - Cleaning
  - Electrician
  - Plumbing
  - Carpentry
  - Tailoring
  - Laundry
  - Mobile Repair
- Service listing with images
- Search and filter functionality
- Favorite services (wishlist)

### 📅 Booking System
- Service booking with time slots
- Booking confirmation modals
- Booking history tracking
- Real-time status updates

### 📍 Location Services
- Geolocation integration
- Google Places autocomplete
- Map integration
- Distance calculation

### 🔔 Notifications
- In-app notifications
- Push notification support
- Notification filtering
- Toast messages

### 💳 Payment
- UPI payment integration
- Google Pay integration
- Secure payment processing

## 🏗️ Tech Stack

| Technology | Version | Purpose |
|------------|---------|---------|
| React Native | 0.80.2 | Mobile Framework |
| TypeScript | 5.x | Programming Language |
| React Navigation | v7 | Navigation |
| Firebase App | 23.5.0 | Backend Services |
| Firebase Auth | 23.5.0 | Authentication |
| Firebase Firestore | 23.5.0 | Database |
| React Context API | - | State Management |

## 📁 Project Structure

```
qkly/
├── src/
│   ├── components/       # Reusable UI components
│   │   ├── Ac.tsx
│   │   ├── Carpenter.tsx
│   │   ├── Cleaning.tsx
│   │   ├── Electrician.tsx
│   │   ├── Header.tsx
│   │   ├── Laundry.tsx
│   │   ├── Mobile.tsx
│   │   ├── Painter.tsx
│   │   ├── Plumbing.tsx
│   │   ├── Services.tsx
│   │   ├── Tailor.tsx
│   │   ├── Tiffin.tsx
│   │   └── common/
│   │       ├── AuthGuard.tsx
│   │       ├── BookingConfirmationModal.tsx
│   │       ├── HeaderWithBack.tsx
│   │       ├── ImagePickerSection.tsx
│   │       ├── SearchBar.tsx
│   │       └── TimeSlotSelectionModal.tsx
│   ├── config/          # Configuration files
│   │   ├── apiKeys.ts
│   │   └── firebase.ts
│   ├── context/         # React Context providers
│   │   ├── AuthContext.tsx
│   │   ├── FavoritesContext.tsx
│   │   ├── SearchFocusContext.tsx
│   │   └── ThemeContext.tsx
│   ├── navigation/      # Navigation configuration
│   │   └── RootNavigator.tsx
│   ├── screens/         # App screens
│   │   ├── Auth/
│   │   ├── CHAT/
│   │   ├── CustomerReviews.tsx
│   │   ├── HomeScreen.tsx
│   │   ├── LikedServices.tsx
│   │   ├── LocationScreen.tsx
│   │   ├── NotificationCenter.tsx
│   │   ├── NotificationScreen.tsx
│   │   ├── PROVIDER/
│   │   ├── Screens.ts
│   │   ├── SellScreen.tsx
│   │   ├── SERVICES/
│   │   ├── navigation/
│   │   └── PROFILE/
│   ├── services/        # Business logic services
│   │   ├── bookingService.ts
│   │   ├── GooglePayService.ts
│   │   ├── NotificationService.ts
│   │   └── UPIPaymentService.ts
│   ├── types/           # TypeScript definitions
│   │   ├── navigation.d.ts
│   │   └── navigation.ts
│   └── utils/           # Utility functions
│       ├── authUtils.ts
│       └── responsive.ts
├── resources/
│   ├── colors/          # Color definitions
│   │   └── Color.js
│   ├── data/            # Static data
│   │   └── SellScreen.json
│   ├── fonts/           # Custom fonts (Poppins)
│   └── styles/          # Shared styles
├── android/             # Android native code
├── ios/                 # iOS native code
├── package.json
└── README.md
```

## 🚀 Getting Started

### Prerequisites
- Node.js >= 18
- npm or yarn
- iOS: Xcode, CocoaPods
- Android: Android Studio, JDK 17

### Installation

```bash
# Install dependencies
npm install
# or
yarn install

# For iOS
bundle install
bundle exec pod install

# For Android
# Ensure Android SDK is configured
```

### Running the App

```bash
# Start Metro
npm start
# or
yarn start

# Run on iOS
npm run ios
# or
yarn ios

# Run on Android
npm run android
# or
yarn android
```

## 🛠️ Key Dependencies

### Core
- `react`: 19.1.0
- `react-native`: 0.80.2
- `@react-navigation/native`: 7.1.17
- `@react-navigation/bottom-tabs`: 7.4.5
- `@react-navigation/native-stack`: 7.2.0
- `@react-native-firebase/app`: 23.5.0
- `@react-native-firebase/auth`: 23.5.0
- `@react-native-firebase/firestore`: 23.5.0

### UI Components
- `react-native-vector-icons`: 10.3.0
- `react-native-image-picker`: 8.2.1
- `react-native-image-crop-picker`: 0.51.1
- `react-native-maps`: 1.26.6

## 📱 App Screens

| Screen | Description |
|--------|-------------|
| Home Screen | Main landing with service categories |
| Services Screen | Browse all services with filters |
| Liked Services | View saved/favorite services |
| Profile Screen | User profile and settings |
| Notification Center | View and manage notifications |
| Sell Screen | Post new services |
| Auth Screens | Login and registration |

## 🎯 Key Achievements

- ✅ Developed cross-platform mobile app for iOS and Android
- ✅ Implemented multi-factor authentication (Email, Google, Facebook)
- ✅ Built comprehensive service marketplace with 8+ categories
- ✅ Created end-to-end booking system with time slots
- ✅ Integrated Google Maps and location services
- ✅ Implemented UPI and Google Pay payment processing
- ✅ Designed notification system with real-time updates
- ✅ Used React Context API for state management
- ✅ Configured Firebase for both iOS and Android

## 👨‍💻 Developer Info

**Developer:** [Your Name]

**Project Type:** Personal Project / Portfolio Project

**Duration:** [Start Date] - Present

**Contact:** [Your Email]

---
