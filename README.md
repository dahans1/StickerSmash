# Welcome to StickerSmash 👋

StickerSmash is a universal image editing app built with [React Native](https://reactnative.dev/) and [Expo](https://expo.dev/). This project is developed as part of an Expo tutorial that guides you step-by-step through building an app that runs seamlessly on Android, iOS, and the web—all from a single codebase.

## Overview

StickerSmash demonstrates the following key concepts:

- **Project Initialization**: Created using `create-expo-app` with a TypeScript-enabled blank template.
- **Navigation**: Implements a two-screen bottom tabs layout using Expo Router.
- **UI & Styling**: Uses core React Native components and flexbox for layout.
- **Image Editing**: Integrates an image picker and a sticker modal to allow users to add emojis/stickers to their photos.
- **Gestures & Interaction**: Adds touch gesture handling for interactive sticker manipulation.
- **Cross-Platform Support**: Designed to work consistently on Android, iOS, and web.
- **Customization**: Configures a custom status bar, splash screen, and app icon.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- [Node.js (LTS)](https://nodejs.org/)
- [Expo CLI](https://docs.expo.dev/workflow/expo-cli/)
- [Expo Go](https://expo.dev/client) (for testing on physical devices) or access to an emulator/simulator
- Basic knowledge of [React](https://reactjs.org/) and [TypeScript](https://www.typescriptlang.org/)

### Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/StickerSmash.git
   cd StickerSmash
   ```

2. **Install Dependencies**

   ```bash
   npm install
   ```

3. **Running the App
Start the Expo development server by running:
   ```bash
   npx expo start
   ```
* On Mobile: Scan the QR code displayed in your terminal using the Expo Go app.
* On Web: Press `w` in the terminal to open the app in your default web browser.

### Project Structure
project-root/
├── app/
│   └── (tabs)/
│       └── index.tsx
├── assets/
│   └── images/
│       └── background-image.png
├── components/
│   ├── Button.tsx
│   ├── CircleButton.tsx
│   ├── EmojiList.tsx
│   ├── EmojiPicker.tsx
│   ├── EmojiSticker.tsx
│   ├── IconButton.tsx
│   └── ImageViewer.tsx
└── package.json


### Tutorial Reference
StickerSmash was built following the [Expo tutorial: Using React Native and Expo.](https://docs.expo.dev/tutorial/introduction/)
The objective of this tutorial is to get started with Expo and become familiar with the Expo SDK. It covers the following topics:
* Create an app using the default template with TypeScript enabled
* Implement a two-screen bottom tabs layout with Expo Router
* Break down the app layout and implement it with flexbox
* Use each platform's system UI to select an image from the media library
* Create a sticker modal using the <Modal> and <FlatList> components from React Native
* Add touch gestures to interact with a sticker
* Use third-party libraries to capture a screenshot and save it to the disk
* Handle platform differences between Android, iOS, and web
* Finally, go through the process of configuring a status bar, a splash screen, and an icon to complete the app

https://github.com/user-attachments/assets/5d2a0693-f171-4e6c-a247-a7ba3a160603

