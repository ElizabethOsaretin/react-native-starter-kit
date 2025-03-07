<div align="center">
  <img src="documentation/rnsk-logo.jpg" alt="React Native Starter Kit" width="400" />
  <p></p>
  <h1>React Native App</h1>
  <p></p>
  <sup>
    <a href="https://github.com/mcnamee/react-native-starter-kit/actions">
      <img src="https://img.shields.io/endpoint.svg?url=https%3A%2F%2Factions-badge.atrox.dev%2Fmcnamee%2Freact-native-starter-kit%2Fbadge%3Fref%3Dmaster&style=flat" alt="builds" />
    </a>
    <a href="/LICENSE">
      <img src="https://img.shields.io/github/license/mcnamee/react-native-starter-kit?style=flat-square" alt="license" />
    </a>
  </sup>
  <br />
  <p align="center">
    <a href="#-intro"><b>What is this?</b></a>
    &nbsp;&nbsp;&mdash;&nbsp;&nbsp;
    <a href="#-getting-started"><b>Usage</b></a>
    &nbsp;&nbsp;&mdash;&nbsp;&nbsp;
    <a href="#-docs"><b>Docs</b></a>
    &nbsp;&nbsp;&mdash;&nbsp;&nbsp;
    <a href="#-further-help"><b>Need help?</b></a>
  </p>
  <br />
</div>

---

### Looking for something else??

- [React Native Starter Kit (Expo) / Boilerplate](https://github.com/mcnamee/react-native-expo-starter-kit)
- [React Starter Kit (web) / Boilerplate](https://github.com/mcnamee/react-starter-kit)
- [Previous Version (React Starter Kit (Web + Native) w/ Firebase)](https://github.com/mcnamee/react-native-starter-kit/tree/archive/v3)

---

## 👋 Intro

This project was bootstrapped with the [React Boilerplate Builder](https://github.com/mcnamee/react-native-boilerplate-builder) by [Matt McNamee](https://mcnam.ee).

The project is _super_ helpful to kick-start your next project, as it provides a lot of the common tools you may reach for, all ready to go. Specifically:

- __Flux architecture__
    - [Redux](https://redux.js.org/docs/introduction/)
    - Redux Wrapper: [Rematch](https://github.com/rematch/rematch)
- __Routing and navigation__
    - [React Native Router Flux](https://github.com/aksonov/react-native-router-flux) for native mobile navigation
- __Data Caching / Offline__
    - [Redux Persist](https://github.com/rt2zz/redux-persist)
- __UI Toolkit/s__
    - [Native Base](https://nativebase.io/) for native mobile
- __Code Linting__ with
    - [Airbnb's JS Linting](https://github.com/airbnb/javascript) guidelines
- __Deployment strategy__
    - [Both manual and automated strategies](documentation/deploy.md)
- __Splash Screen + Assets__
    - [React Native Splash Screen](https://github.com/crazycodeboy/react-native-splash-screen)

---

## 🚀 Getting Started

 - Install [React Native Debugger](https://github.com/jhen0409/react-native-debugger/releases) and open before running the app
 - Install `eslint`, `prettier` and `editor config` plugins into your IDE
 - Ensure your machine has the [React Native dependencies installed](https://facebook.github.io/react-native/docs/getting-started)

```bash
# Install dependencies
yarn install && ( cd ios && pod install )
```

#### iOS

```bash
# Start in the iOS Simulator
npx react-native run-ios --simulator="iPhone 11"
```

#### Android

```bash
# Start in the Android Simulator
#  - Note: open Android Studio > Tools > AVD > Run a device
#  - Example device specs: https://medium.com/pvtl/react-native-android-development-on-mac-ef7481f65e47#d5da
npx react-native run-android
```

---

## 📖 Docs

- [Contributing to this project](documentation/contributing.md)
- [FAQs & Opinions](documentation/faqs.md)
- [Tests & testing](documentation/testing.md)
- [Understanding the file structure](documentation/file-structure.md)
- [Deploy the app](documentation/deploy.md)

---

## 👊 Further Help?

This repo is a great place to start. But...if you'd prefer to sit back and have your new project built for you or just need some consultation, [get in touch with me directly](https://mcnam.ee) and I can organise a quote.
