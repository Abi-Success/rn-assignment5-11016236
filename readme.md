# NAME : AFFUL ABIGAIL

# STUDENT ID: 11016236


## This project demonstrates a simple React Native application with a light and dark theme switcher. It utilizes React Navigation for navigation between screens and a custom context provider (ThemeContext) to manage the application's theme.


## Installation
Clone the repository:

# Bash
git clone https://github.com/Abi-Success/rn-assignment5-11016236.git
Use code with caution.
content_copy
Install dependencies:

# Bash
cd react-native-theming-app
npm install
Use code with caution.
content_copy
Usage
Start the app:

# Bash
npx react-native start
Use code with caution.
content_copy
Run on a device or simulator:

# Bash
npx react-native run-android 
Use code with caution.
content_copy

# Bash
npx react-native run-ios 
Use code with caution.
content_copy


## Navigate between the "Home" and "Settings" screens using the bottom navigation bar.

In the "Settings" screen, use the toggle switch to change the theme.

# Project Structure
react-native-theming-app/
├── App.js               
├── Components/           
│   └── StackNavigator.js
├── Context/             
│   └── ThemeContext.js 
├── screens/
│   ├── Home.js 
│   └── Settings.js      
├── ... (other project files)
## Key Components

# App.js: The main entry point of the application. It wraps everything in the ThemeProvider and sets up the NavigationContainer.

# ThemeContext.js: Provides the theme state (light or dark) and the function to toggle it. This context is consumed by other components.

# MainApp.js: Consumes the ThemeContext, sets the theme for NavigationContainer, and renders the main stack navigator.

# StackNavigator.js: Defines the navigation structure with "Home" and "Settings" screens.

# Home.js: The home screen of the application.

# Settings.js: Contains settings options and the theme toggle.


## Explanation

# Clear Structure: The README provides a clear outline of the project's purpose, features, and how to get started.

# Instructions: Installation and usage steps are straightforward, guiding users through the setup process.

# Project Organization: The project structure section helps developers understand the code layout.

# Component Descriptions: Briefly explains the role of each key component in the app.

# Improvement (Optional): If you've implemented any of the enhancements discussed previously, you can include a section called "Improvements" or "Additional Notes" in the README to highlight them.
