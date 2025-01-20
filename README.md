# Little Lemon Newsletter Subscription App

A mobile application developed using React Native and Expo, allowing users to subscribe to a newsletter by entering their email. It showcases the integration of various UI components like Buttons, Inputs, and Typography, while utilizing navigation and validation mechanisms.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Folder Structure](#folder-structure)
- [Installation](#installation)
- [Usage](#usage)

## Project Overview

This project demonstrates a simple yet functional mobile application designed for a newsletter subscription service. Users can enter their email address, validate its format, and subscribe to the newsletter. The app uses React Navigation to manage different screens and React Native components for a seamless user interface.

![](little_lemon.gif)

## Features
- **Navigation**: Users can navigate between the Welcome screen and Subscribe screen.
- **Email Validation**: The app validates email format using a regular expression and provides real-time feedback to the user.
- **Responsive Design**: The app's layout adjusts dynamically based on screen size and orientation.
- **Debounced Input**: Input validation uses a debouncing technique to limit the frequency of validation checks.

## Tech Stack
- **React Native**: Framework for building the app.
- **Expo**: Development environment for building and testing the app.
- **React Navigation**: For screen navigation.
- **React Hooks**: Managing state and side-effects.
- **JavaScript (ES6+)**: For application logic.
- **Babel**: For JavaScript transpiling.

## Folder Structure

The directory structure is organized as follows:

Directory structure:

- **App.js**: Main entry point of the app, which sets up the navigation.
- **components/**: Contains reusable components like `Button`, `Input`, and `Typography`.
- **constants/**: Stores constant values like color themes.
- **hooks/**: Custom hooks such as `useFontSize` for responsive typography.
- **navigators/**: Defines screen navigation using `React Navigation`.
- **screens/**: Contains the `WelcomeScreen` and `SubscribeScreen`.
- **utils/**: Contains helper functions like `debounce` and `validateEmail`.

## Installation

To get started with this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/little-lemon-newsletter-app.git
    ```

2. Navigate into the project directory:
    ```bash
    cd little-lemon-newsletter-app
    ```

3. Install the dependencies:
    ```bash
    npm install
    ```

4. Start the project:
    ```bash
    npm start
    ```

## Usage

Once the project is running, follow these steps:

1. **Welcome Screen**: Upon launching the app, users are greeted with the Welcome screen which includes information about the "Little Lemon" bistro and a button to navigate to the subscription page.
   
2. **Subscribe Screen**: Users can enter their email address to subscribe to the newsletter. The input field provides real-time validation and feedback if the email format is incorrect. After a valid email is entered, the user can press the "Subscribe" button to complete the subscription process.

3. **Mobile Friendly**: The application adjusts its layout to accommodate various screen sizes and orientations.


**Feel free to fork, clone, and modify this repository to suit your needs.**

