# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
# ⏱️ React Stopwatch App

This is a simple stopwatch application built with React. It allows you to start, stop, and reset the timer.

## 🚀 Features

- Start, stop, and reset stopwatch functionality
- Responsive UI built with React
- Clean and simple design

## 🧠 What I Learned

While building this app, I practiced and learned:

- `useState` – to manage timer state and control the stopwatch status.
- `useEffect` – to handle side effects, like starting/stopping the interval.
- `useRef` – to keep a mutable reference for the interval ID without triggering re-renders.

## 📦 Tech Stack

- React
- JavaScript
- CSS

## 🔗 Live Demo

Check it out here: [Stopwatch App Live](https://AnuThmsn.github.io/stop-watch-app)  
_(replace with your actual deployed URL)_

## 📸 Screenshots

> *(Optional: Add screenshots of your stopwatch UI here)*

## 🛠️ Installation

To run locally:

```bash
git clone https://github.com/AnuThmsn/stop-watch-app.git
cd REPO
npm install
npm run dev    # if using Vite
# or
npm start      # if using Create React App
