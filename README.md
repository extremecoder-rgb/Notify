# Notify - Medicine Reminder App

Notify is a cross-platform mobile application built with React Native and Expo. It helps users manage their medication schedules, receive timely reminders, track medication history, and monitor refills. The app is designed for ease of use, security, and reliability, making it an ideal companion for anyone who needs to take medications regularly.

---

## 🚀 Features

- **Biometric or PIN Authentication**: Secure access using Face ID, Touch ID, or PIN.
- **Medication Management**: Add, edit, and delete medications with details like dosage, frequency, duration, and notes.
- **Smart Reminders**: Receive push notifications for each scheduled dose.
- **Calendar View**: Visualize your medication schedule and history on a monthly calendar.
- **Dose Tracking**: Mark doses as taken and view your daily progress.
- **Refill Tracker**: Monitor medication supply and get alerts when it's time to refill.
- **History Log**: Review your medication intake history and clear all data if needed.
- **Modern UI**: Clean, accessible, and responsive design with support for light and dark modes.

---

## 🧰 Tech Stack

- **React Native**: Core framework for building native mobile apps using JavaScript and React.
- **Expo**: Toolchain and platform for universal React Native apps (development, build, and deployment).
- **TypeScript**: Strongly-typed language for safer and more robust code.
- **Expo Router**: File-based routing for navigation.
- **AsyncStorage**: Local storage for persisting medication and dose data.
- **Expo Notifications**: Push notification scheduling and handling.
- **Expo Local Authentication**: Biometric authentication (Face ID, Touch ID, etc.).
- **@react-native-community/datetimepicker**: Native date and time pickers.
- **Ionicons**: Icon library for consistent UI.
- **Jest & jest-expo**: Testing framework for unit and integration tests.
- **React Native Reanimated**: Smooth and performant animations.
- **Expo Linear Gradient & Blur**: Visual effects for modern UI.

---

## 📱 Screens & Navigation

- **Splash Screen**: Animated intro with app branding.
- **Authentication**: Biometric or PIN login for security.
- **Home**: Daily progress, quick actions, and today's medications.
- **Add Medication**: Form to add new medications with reminders and refill options.
- **Calendar**: Monthly view of medication schedule and dose history.
- **History**: Log of all taken doses and option to clear data.
- **Refills**: Track and record medication refills.

---

## 🛠️ Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v16 or newer recommended)
- [Yarn](https://classic.yarnpkg.com/) or [npm](https://www.npmjs.com/)
- [Expo CLI](https://docs.expo.dev/get-started/installation/): `npm install -g expo-cli`

### Installation

1. **Clone the repository:**
   ```sh
   git clone <repo-url>
   cd Notify/
   ```
2. **Install dependencies:**
   ```sh
   yarn install
   # or
   npm install
   ```
3. **Start the development server:**
   ```sh
   yarn start
   # or
   npm start
   # or
   expo start
   ```
4. **Run on your device or emulator:**
   - For Android: `yarn android` or `expo start --android`
   - For iOS: `yarn ios` or `expo start --ios`
   - For Web: `yarn web` or `expo start --web`

---

## 🗂️ Folder Structure

```
  app/                # App screens and navigation
  assets/             # Images, fonts, and static assets
  components/         # Reusable UI components
  constants/          # App-wide constants (e.g., colors)
  hooks/              # Custom React hooks
  utils/              # Utility functions (storage, notifications)
  scripts/            # Project scripts (e.g., reset-project.js)
  package.json        # Project metadata and dependencies
  app.json            # Expo app configuration
  tsconfig.json       # TypeScript configuration
  yarn.lock           # Dependency lockfile
```

---

## 🧪 Testing

- Run all tests with:
  ```sh
  yarn test
  # or
  npm test
  ```
- The project uses [Jest](https://jestjs.io/) and [jest-expo](https://docs.expo.dev/guides/testing-with-jest/).

---

## ⚙️ Scripts

- `yarn start` / `npm start` / `expo start`: Start the Expo development server
- `yarn android` / `yarn ios` / `yarn web`: Run the app on Android, iOS, or Web
- `yarn test`: Run tests
- `yarn lint`: Lint the codebase
- `yarn reset-project`: Reset the project to a blank state (see `scripts/reset-project.js`)

---

## 📝 Notes

- The app's internal name in some config files is `bycicle-rental-app`, but the actual product is **MedRemind** (Medicine Reminder App).
- All medication and dose data is stored locally on the device using AsyncStorage.
- Push notifications require permissions and may not work on all emulators.
- For biometric authentication, your device must support Face ID or Touch ID.

---

## 🙏 Credits

- Built with [React Native](https://reactnative.dev/) and [Expo](https://expo.dev/)
- Icons by [Ionicons](https://ionicons.com/)
- Calendar and date/time pickers by [@react-native-community/datetimepicker](https://github.com/react-native-datetimepicker/datetimepicker)
- Special thanks to the open-source community!

---

## 📄 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details. 