# Movie App - EXPO

## Table of Contents

- [Movie App - EXPO](#movie-app---expo)
  - [Table of Contents](#table-of-contents)
  - [1. Create Expo Project](#1-create-expo-project)
  - [2. Configure Eslint](#2-configure-eslint)
  - [3. Install Expo Screen Orientation (Optional)](#3-install-expo-screen-orientation-optional)
  - [4. Install React Navigation](#4-install-react-navigation)
  - [5. Install Stack Navigator](#5-install-stack-navigator)
  - [6. Install Axios](#6-install-axios)
  - [7. Install React Native Snap Carousel](#7-install-react-native-snap-carousel)

## 1. Create Expo Project

- Run:
  - `$ npx create-expo-app -t expo-template-blank-typescript`
  - `$ cd Movie-App`
  - `$ $ npx expo start -c`

## 2. Configure Eslint

- Run:
  - `$ npm install eslint -D`
  - `$ .\node_modules\.bin\eslint --init` or `$ npm init @eslint/config`

## 3. Install Expo Screen Orientation (Optional)

- Run:
  - `$ npx expo install expo-screen-orientation`

## 4. Install React Navigation

<https://reactnavigation.org/docs/getting-started>

- Run:
  - `$ npm install @react-navigation/native`
  - `$ npx expo install react-native-screens react-native-safe-area-context`

## 5. Install Stack Navigator

<https://reactnavigation.org/docs/stack-navigator>

- Run:
  - `$ npm install @react-navigation/stack`
  - `$ npx expo install react-native-gesture-handler`
- Optional
  - `$ npx expo install @react-native-masked-view/masked-view`

## 6. Install Axios

<https://www.npmjs.com/package/axios>

- Run:
  - `$ npm i axios`

## 7. Install React Native Snap Carousel

<https://github.com/meliorence/react-native-snap-carousel>

- Run:

- ~~`$ npm install --save react-native-snap-carousel`~~

- ~~`$ npm i react-native-new-snap-carousel`~~

- Stable

```bash
$ npm install apurba-bware/react-native-snap-carousel#5a7f809e921262e4e2f646e8cfc4da85f7bd663d
```

- If you're using Typescript you should also install type definitions (Optional):

```bash
$ npm install --save-dev @types/react-native-new-snap-carousel
```
