# rn-assignment3-11117467

# React Native Assignment 3

This project is a React Native application that displays categories and tasks. The UI closely follows a provided design from Figma, ensuring that all required core components are used, and custom components are created for modularity.

## Features

- Displays categories with embedded text in images.
- Provides a list of ongoing tasks.
- Implements a search functionality for tasks.
- Uses core React Native components:
  - `View`
  - `Text`
  - `ScrollView`
  - `TextInput`
  - `Button`
  - `FlatList`
  - `Image`
  - `StyleSheet`

## Technologies Used

- React Native
- Expo CLI

## Installation

1. Navigate to the project directory:

   ```bash
   cd rn-assignment3-ID
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm start
   ```

## File Structure

```
rn-assignment3-ID/
├── assets/
│   ├── exercise.png
│   ├── study.png
│   ├── code.png
│   ├── cook.png
│   ├── read.png
│   ├── shop.png
│   ├── clean.png
│   ├── sleep.png
├── components/
│   ├── CategoryItem.js
│   ├── TaskItem.js
├── screens/
│   ├── HomeScreen.js
├── App.js
├── package.json
└── README.md
```

## Usage

### HomeScreen Component

The `HomeScreen` component displays the categories and tasks. It uses the `CategoryItem` and `TaskItem` components to render each category and task respectively.

### CategoryItem Component

The `CategoryItem` component displays an image with embedded text, styled to match the provided UI design.

### TaskItem Component

The `TaskItem` component renders individual tasks in the list.

## Screenshots

![Screenshot](./assets/UI.jpg)

## Commit History

- **Initial commit**: Project setup and initial structure.
- **Add assets**: Added images for categories.
- **Implement HomeScreen**: Added HomeScreen with categories and tasks.
- **Create CategoryItem component**: Implemented CategoryItem with styles.
- **Create TaskItem component**: Implemented TaskItem for task list.
- **Style updates**: Adjusted styles to match the provided design.
- **Final touches**: Final adjustments and README update.



