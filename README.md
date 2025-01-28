# React Native

![Image](https://github.com/user-attachments/assets/b9cfb4e2-e1e9-4dd9-96e7-6f6fb495c103)

React Native is an open-source framework developed by Facebook that enables mobile application development using JavaScript. With React Native, the code you write can run on both iOS and Android platforms, allowing you to create native-like and high-performance mobile applications.

## Quick Start

Create new latest version project with Typescript

```
npx create-expo-app ProjectName
```

Or create new latest version project with templates

```
npx create-expo-app ProjectName --template
```

Start the expo server

```bash
npx expo start
```

## Folder Structure

Organize files according to the folder structure

```
src/
├── assets/
│   ├── fonts/
│   └── images/
├── components/
│   ├── buttons/
│   │   ├── PrimaryButton.js
│   │   └── SecondaryButton.js
│   ├── headers/
│   │   ├── PrimaryHeader.js
│   │   └── SecondaryHeader.js
│   ├── inputs/
│   │   ├── PrimaryTextInput.js
│   │   └── SecondaryTextInput.js
│   ├── items/
│   │   ├── HomeItem.js
│   │   └── ProfileItem.js
│   ├── layouts/
│   │   ├── AlertNotification.js
│   │   └── BottomSheetDialog.js
├── constants/
│   ├── HomeData.js
│   └── ProfileData.js
├── contexts/
│   ├── ThemeContext.js
│   └── UserContext.js
├── hooks/
│   ├── useAuth.js
│   └── useFetch.js
├── screens/
│   ├── Home.js
│   ├── Profile.js
│   └── Route.js
├── services/
│   ├── api.js
│   └── i18next.js
├── store/
│   ├── slices/
│   │   ├── HomeSlice.js
│   │   └── Profile.js
│   └── Store.js
├── styles/
│   ├── HomeStyles.js
│   └── ProfileStyles.js
└── themes/
    ├── DarkTheme.js
    └── LightTheme.js
```
