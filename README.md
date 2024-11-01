# Disney+ Clone Project

---

# ![Screenshot 2024-11-01 151737](https://github.com/user-attachments/assets/531be3fb-c496-4bc9-81c3-9908215ad408)

Welcome to the **Disney+ Clone**! This project is a full-stack streaming application that simulates core features of the Disney+ platform, leveraging **React**, **Redux**, **Firebase**, and **CSS Modules**.

---

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Project Architecture](#project-architecture)

---

## Overview
This Disney+ clone project was created to explore the functionality of modern streaming platforms. Built using the latest tools and frameworks, it includes core features such as user authentication, video streaming, and content management. This project demonstrates the powerful combination of **React for building user interfaces**, **Redux for state management**, and **Firebase for backend services**.

---

## Features
- **User Authentication**: Secure sign-in and sign-up using Firebase Authentication.
- **Content Streaming**: Browse and stream a variety of movies and shows.
- **User Profiles**: Create and manage multiple user profiles.
- **Responsive UI**: CSS Modules for a seamless experience across devices.
- **Search Functionality**: Easily search for content within the app.

---

## Tech Stack
- **Frontend**: React, Redux, CSS Modules
- **Backend**: Firebase (Authentication, Firestore)
- **Styling**: CSS Modules
- **Development Tools**: ESLint, Node.js

---

## Setup and Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Parthav99/disney_clone.git
   cd disney_clone

2. Install dependencies: Make sure you have Node.js and npm installed. Then run:
    ```bash
    npm install
    ```

3. Set up Firebase:

    Go to the Firebase Console, create a new project, and add your web app.
    Copy the Firebase configuration and replace it in firebase.js.

4. Set up environment variables:

    In the project root, create a .env.local file and add your Firebase credentials.

5. Start the development server:

    ```bash
    npm run dev
    ```

    View in Browser:
        Open http://localhost:3000 to see your Uber clone in action.

## Usage

Once the app is running, you can:

  - Sign Up / Sign In: Create an account or log in with Firebase Authentication.
  - Browse Content: View available movies and shows on the homepage.
  - Stream Videos: Select and watch your favorite content.
  - Manage Profiles: Switch between different user profiles.

## Project Architecture

This project is designed with modularity and scalability in mind. Here's a high-level view of key components:

  - Authentication: Managed by Firebase Authentication, handling secure logins and signups.
  - Content Management: Firestore is used for managing content metadata and user profiles.
  - UI Components: Styled with CSS Modules, each component is designed to be reusable and responsive.
  - State Management: Redux is employed for managing application state and ensuring a smooth user experience.

We hope you enjoy exploring this Disney+ Clone project and that it inspires you to build even more exciting applications. 🎬✨
