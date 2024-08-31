# Blog App

## Overview

Welcome to the Blog App! This project is a modern blog application built with React and Vite for the frontend, and Appwrite as the backend service. The app features a rich text editor, dynamic routing, state management, and form handling, making it a robust platform for blogging.

## Features

- **Rich Text Editor**: Integrated TinyMCE editor for creating and managing blog posts.
- **State Management**: Using Redux Toolkit and React-Redux for state management.
- **Routing**: React Router DOM for navigation between different pages.
- **Form Handling**: React Hook Form for handling form submissions and validations.
- **HTML Parsing**: html-react-parser for rendering HTML content safely.

## Installation

To get started with the Blog App, follow these steps:

1. **Create a Vite Project**

   ```bash
   npm create vite@latest
2.Install Dependecies:
  ```bash
  # 1. Create a Vite project
npm create vite@latest

# Navigate into the project directory
cd your-project-name

# 2. Install initial dependencies
npm install

# 3. Install Tailwind CSS (follow the Tailwind CSS guide for Vite)
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p

# 4. Install Appwrite SDK
npm install appwrite

# 5. Install Redux Toolkit
npm install @reduxjs/toolkit

# 6. Install React-Redux
npm install react-redux

# 7. Install React Router DOM
npm install react-router-dom

# 8. Install React Hook Form
npm install react-hook-form

# 9. Install HTML React Parser
npm install html-react-parser

# 10. Install TinyMCE React Integration
npm install @tinymce/tinymce-react

### Additional Setup
Tailwind CSS Configuration

After installing Tailwind CSS, you'll need to configure it by adding the following lines to your tailwind.config.js:

js
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
And add the following directives to your src/index.css or src/App.css:

css
@tailwind base;
@tailwind components;
@tailwind utilities;
