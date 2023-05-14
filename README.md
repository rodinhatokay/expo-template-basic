# Expo Template Repository

This repository provides a template for Expo projects, designed to help you get started quickly with your React Native applications. The template includes a basic setup for authentication, localization, a color theme, fonts, and route examples written in TypeScript.

The structure is not fully functional as a standalone application, but it's enough to give you a solid starting point. The template leverages popular libraries such as `react-navigation` and `react-native-paper` to provide a robust and modern user interface.

## Structure

This project is organized into a logical folder structure to keep things neat and understandable. Here's an overview of the folder structure and the purpose of each directory:

- **src/**: This is where all of your TypeScript files live.
    - **components/**: Reusable UI components.
    - **screens/**: Different application screens.
    - **routes/**: Route setup.
    - **contexts/**: contextts setup (auth/localization/theme).
    - **localization/**: Localization langauges.
    - **services/**: Contains services (e.g api).
    - **constants/**: Contains colors and fonts.
    
## Getting Started

Follow these steps to set up and run this project locally.

### Prerequisites

You'll need to have the following installed to run the application:

- Node.js
- npm/yarn
- Expo CLI

### Installation

1. Clone the repository ```bash git clone https://github.com/username/expo-template.git```
2. Navigate to the project directory ```bash cd expo-template```
3. Install the dependencies ```bash npm install``` or if you prefer using Yarn: ```bash yarn install```
4. Start the Expo server ```bash expo start```

#### You should now be able to open the Expo client on your phone and scan the QR code to run the app, or run the app on an emulator.
  > **Important Note:** Remember to replace  "expo-template" with your actual wanted repository name.


## Libraries Used

- [React Navigation](https://reactnavigation.org/)
- [React Native Paper](https://callstack.github.io/react-native-paper/)
- [axios](https://github.com/axios/axios)
- [i18n](https://github.com/fnando/i18n-js)
- [Lottie React Native](lottie-react-native)
- and more...


