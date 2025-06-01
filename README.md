# Taskly

Taskly is a simple productivity app built with [Expo 53](https://docs.expo.dev/) and [React Native 0.79](https://reactnative.dev/). It features a shopping list, a recurring countdown timer with notification support, and a placeholder for ideas.

## Features

- **Shopping List:**  
  Add, complete, and delete shopping list items. Items are persisted locally.

- **Countdown Timer:**  
  Track recurring tasks with a countdown timer. Get notified when the timer is up, and view your completion history.

- **Push Notifications:**  
  Receive local notifications when your countdown is due (requires permissions).

- **Persistent Storage:**  
  All data is stored locally using AsyncStorage.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/)
- [Yarn](https://yarnpkg.com/) or [npm](https://www.npmjs.com/)
- [Expo CLI](https://docs.expo.dev/get-started/installation/)

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/yourusername/taskly.git
   cd taskly

   ```

2. Install dependencies:

   ```sh
   npm install
   # or
   yarn install

   ```

3. Start the development server:

   ```sh
   npx expo start

   ```

4. Open the app in Expo Go on your device, or use an emulator.

## Project Structure

- **app/** - Main application screens and navigation
- **components/** - Resuable UI components
- **utils/** - Utility functions (storage, notifications)
- **assests/** - App icons and images
- **theme.ts** - App color theme

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

Made with ❤️ using Expo and React Native.
