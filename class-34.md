# React Native Ecosystem

### What is native development? 

- The working principles of React Native are virtually identical to React except that React Native does not manipulate the DOM via the Virtual DOM. It runs in a background process (which interprets the JavaScript written by the developers) directly on the end-device and communicates with the native platform via a serialisation, asynchronous and batched Bridge.

- React components wrap existing native code and interact with native APIs via React’s declarative UI paradigm and JavaScript. This enables native app development for whole new teams of developers, and can let existing native teams work much faster.

- React Native does not use HTML or CSS. Instead, messages from the JavaScript thread are used to manipulate native views. React Native also allows developers to write native code in languages such as Java for Android and Objective-C or Swift for iOS which make it even more flexible.

### Why is it important to develop a native app vs a responsive react app?

It’s still just state and components
But no HTML or CSS
You can still “style” things using the framework guidelines

### Expo

- Expo Is the dev environment
- Snack is an online sandbox
- expo-cli is the local equivalent to create-react-app (you can eject)
- Running locally, you can use your own device or the official simulator
Only Apple users can test iPhones
- Anyone can test android, but you need to start up an ADB from The Android Studio IDE

