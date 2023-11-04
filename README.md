
# React Vite Theme Switcher App

This is a simple React application created using Vite that allows users to switch between light and dark themes. It provides a user interface with a theme switch button and a card component that demonstrates the theme switching functionality.

## Demo 
[Click Here](https://dark-theme-toggle-blue.vercel.app/) 

## Features

- Switch between light and dark themes.
- Minimalistic design for easy understanding.

## Technologies Used

- React: A JavaScript library for building user interfaces.
- Vite: A build tool for modern web development.
- Context API: Used for managing and providing theme-related data to components.

## Installation

1. Make sure you have Node.js and npm (Node Package Manager) installed on your system.

2. Clone this repository:

   ```bash
   git clone https://github.com/tejus05/Dark-Theme-Toggle/.git
   ```

3. Navigate to the project directory:

   ```bash
   cd Dark-Theme-Toggle
   ```

4. Install the dependencies:

   ```bash
   npm install
   ```

## Usage

1. Start the development server:

   ```bash
   npm run dev
   ```

   This command will start the development server and open the application in your default web browser.

2. You can now use the theme switch button to toggle between light and dark themes.

## How It Works

- The theme state (light or dark) is managed using the `useState` hook in the `App` component.
- The `ThemeProvider` component is used to provide the theme-related data to child components using the Context API.
- The `ThemeBtn` component provides a button to switch between light and dark themes.
- The `Card` component demonstrates the theme switching functionality by changing its appearance based on the selected theme.

