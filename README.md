# ALX Listing App

An Airbnb-style listing application built with Next.js, TypeScript, TailwindCSS, and ESLint.
This project serves as the foundation for creating a responsive property listing page with reusable UI components and a clean, maintainable codebase.

## 🚀 Project Goal

The goal of this project is to scaffold an Airbnb-like property listing page using Next.js Pages Router, ensuring:

Type safety with TypeScript

Clean and consistent code with ESLint

Responsive, modern design with TailwindCSS

A scalable structure for components, constants, and interfaces

## 📂 Project Structure
alx-listing-app/
│
├─ pages/
│   └─ index.tsx          # Home page (entry point)
│
├─ components/
│   └─ common/
│       ├─ Card.tsx       # Reusable Card component for property info
│       └─ Button.tsx     # Reusable Button component for actions
│
├─ interfaces/
│   └─ index.ts           # TypeScript interfaces (CardProps, ButtonProps, etc.)
│
├─ constants/
│   └─ index.ts           # Reusable constants (API URLs, config, UI text)
│
├─ public/
│   └─ assets/            # Images, SVGs, and static assets
│
├─ styles/
│   └─ globals.css        # Tailwind base, components, and utilities
│
├─ tailwind.config.js     # Tailwind configuration
└─ README.md              # Project documentation

## 🧩 Components Overview

Card.tsx: Displays property details such as title, price, and image.

Button.tsx: A reusable button for actions like Book Now or View Details.

## ⚡️ Tech Stack

Next.js (Pages Router) – Framework for building React applications

TypeScript – Static type checking for safer, more maintainable code

TailwindCSS – Utility-first CSS for rapid, responsive styling

ESLint – Enforces coding standards and consistency

## 🛠️ Getting Started

Follow these steps to run the project locally:

## 1️⃣ Clone the repository
git clone https://github.com/<your-username>/alx-listing-app.git
cd alx-listing-app

## 2️⃣ Install dependencies
npm install

## 3️⃣ Run the development server
npm run dev


Open your browser and navigate to 👉 http://localhost:3000
 to see the app in action.

## ✅ Next Steps

Implement the Card and Button components with props defined in interfaces/index.ts.

Add placeholder images to the public/assets folder for property listings.

Extend constants for API endpoints and reusable UI strings.
