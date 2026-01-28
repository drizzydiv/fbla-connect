# FBLA Connect - Mobile Application Development 2026

![FBLA Connect Banner](./assets/images/logo-icon.png)

**FBLA Connect** is the premier mobile solution designed to centralize chapter operations, boost member engagement through gamification, and provide critical resources—online or offline. Built for the 2026 FBLA Mobile Application Development competition, this app addresses the need for a modern, accessible, and unified member experience.

## 🎯 Purpose
The primary goal of FBLA Connect is to **bridge the gap between chapter leadership and student members**. By digitizing the membership experience, we eliminate communication silos, gamify participation to increase retention, and ensure every member has access to opportunities regardless of their connectivity or ability.

## ✨ Significant Features

### 1. **Gamified Engagement System**
- **Daily Streaks**: A visual streak calendar that rewards consistent daily activity.
- **Achievements & Badges**: Unlockable digital badges for attendance, leadership, and service.
- **Live Leaderboards**: Competitive ranking system to motivate member participation.

### 2. **Comprehensive Event Management**
- **Calendar & List Views**: Flexible viewing options for workshops, conferences, and meetings.
- **One-Tap RSVP**: Seamless registration flow for events.
- **Offline Sync**: Event details are cached locally, ensuring access even without Wi-Fi.

### 3. **Accessibility First**
- **Custom Accessibility Engine**: Built-in tools for:
  - **Font Scaling** (A, A+, A++) independently of system settings.
  - **Color Blindness Modes** (Protanopia, Deuteranopia, Tritanopia filters).
  - **Reduced Motion** & High Contrast support.
- **WCAG Compliance**: All interactive elements are optimized for screen readers and touch targets.

### 4. **Member Resources**
- **Digital Membership Card**: A polished, FBLA-branded ID card with real-time stats.
- **Secure Chat Rooms**: Role-based communication channels (Chapter, Officers, Competitors).
- **News & Announcements**: Centralized feed for local and national updates.

### 5. **Officer & Admin Portal**
- **Data Seeding**: One-click database population for demonstration purposes.
- **Management Tools**: Simplified tools for posting news and managing events.

---

## 🛠 Technology Stack

- **Framework**: [React Native](https://reactnative.dev/) with [Expo](https://expo.dev/) (SDK 50+)
- **Language**: TypeScript
- **Backend**: Firebase Realtime Database
- **Authentication**: Firebase Auth
- **Animations**:
  - **Lottie**: For high-fidelity vector animations (e.g., Streak Fire, Confetti).
  - **React Native Reanimated**: For smooth, 60fps UI micro-interactions.
- **Navigation**: Expo Router (File-based routing)

---

## 🚀 Installation & Setup

### Prerequisites
- Node.js (v18+)
- Expo Go app installed on your physical device (iOS/Android)

### Steps
1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-chapter/fbla-mobile-app.git
   cd fbla-mobile-app
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Start the Development Server**
   ```bash
   npx expo start
   ```

4. **Run on Device**
   - Scan the QR code with your iPhone Camera or Android Expo Go app.

### Demo & Seeding
For judges and testers:
1. Log in with any email (or create a new account).
2. Navigate to **Menu > Admin**.
3. Tap **"Seed Data"** to instantly populate the app with sample events, announcements, and badges.

---

## 📱 Folder Structure

```text
/app               # Expo Router screens and layouts
  /(auth)          # Login/Register screens
  /(tabs)          # Main tab navigation (Home, Events, Ranks, Messages, Menu)
/components        # Reusable UI components (MembershipCard, StreakCalendar, etc.)
/contexts          # Global state (Theme, Accessibility, Auth)
/constants         # Design tokens (Colors, Typography)
/services          # Firebase integration logic
/utils             # Helper scripts (Data Seeding)
/assets            # Images and Lottie animations
```

---

*Developed for the FBLA National Leadership Conference 2026.*
