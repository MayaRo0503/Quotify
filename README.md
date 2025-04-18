# Quotify

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=FFD62E)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![API Ninjas](https://img.shields.io/badge/API_Ninjas-000000?style=for-the-badge)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

> A sleek, responsive quote generator that delivers fresh inspiration at the click of a button.

---

## 🚀 Live Demo
[https://quotifym.netlify.app/](https://quotifym.netlify.app/)

---

## 📖 Project Overview
Quotify is a modern React + Vite application that fetches and displays inspirational quotes from the external **API Ninjas** service. It was born out of a desire to practice:

- **Core React concepts** (components, state & props, lifecycle hooks)  
- **Asynchronous data fetching** and error handling  
- **Responsive, polished UI/UX**  
- **CI/CD pipelines** and environment‑safe API key management  

Hosted on Netlify’s free tier, Quotify demonstrates end‑to‑end web development skills—from coding to deployment.

---

## 🎯 What You’ll Learn
- **React Fundamentals**: Creating and composing components, managing local state with `useState`, and handling side effects with `useEffect`.  
- **API Integration**: Fetching data from RESTful endpoints, displaying loading/error states.  
- **Responsive Design**: Crafting layouts that adapt across mobile and desktop viewports.  
- **Environment Variables**: Safely injecting `VITE_API_KEY` at build time.  
- **Deployment & CI/CD**: Automating builds and deployments with Netlify.  
- **Local Storage Management** (optional): Persisting user favorites for offline access.

---

## ⚙️ Features
- **Inspire On Demand**: Click “New Quote” to load a random quote.  
- **Error & Loading States**: Friendly UI feedback for network issues.  
- **Clean, Minimal Design**: Focus on readability and user flow.  
- **Future Enhancements**:  
  - Favorites list (persisted in localStorage)  
  - Dark/Light theme toggle  

---

## 🏗 Architecture

1. **`src/components/QuotesApp.jsx`**  
   Main UI component handling state, fetch logic, and rendering.  
2. **`src/main.jsx`**  
   App entry point — mounts the root component.  
3. **`.env`**  
   Holds `VITE_API_KEY` (excluded from Git via `.gitignore`).  
4. **`vite.config.js`**  
   Vite build/dev configuration.  
5. **`netlify.toml`**  
   Netlify build and publish settings.

---

## 🛠 Tech Stack
- **Framework**: React  
- **Bundler**: Vite  
- **Styling**: CSS Modules  
- **API**: API Ninjas  
- **Hosting**: Netlify (CI/CD, environment variables)  
- **Version Control**: Git & GitHub  

---

## 📋 Prerequisites
- Node.js ≥ v14  
- npm ≥ v6 (or Yarn)  
- Basic knowledge of HTML, CSS, JavaScript  
- Familiarity with React is a plus but not mandatory  

---

## ⚡ Installation & Setup

1. **Clone the repo**  
   ```bash
   git clone https://github.com/MayaRo0503/Quotify.git
   cd Quotify
   ```

2. **Install dependencies**  
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Configure environment**  
   Create a `.env` file in the project root:
   ```bash
   VITE_API_KEY=YOUR_API_KEY_HERE
   ```
   Replace `YOUR_API_KEY_HERE` with your **API Ninjas** key.

4. **Run in development**  
   ```bash
   npm run dev
   # or
   yarn dev
   ```
   Open [http://localhost:5173](http://localhost:5173) to view in your browser.

---

## 🚢 Deployment
- **Netlify** automatically builds on every push to `main`.  
- See `netlify.toml`:
  ```toml
  [build]
    command = "npm run build"
    publish = "dist"
  ```
- **Live at**: [https://quotify-your-domain.netlify.app](https://quotify-your-domain.netlify.app)

---

## 🤝 Contributing
Contributions, issues, and feature requests are welcome!  
1. Fork the repo  
2. Create a feature branch (`git checkout -b feature/my-feature`)  
3. Commit your changes (`git commit -m "Add my feature"`)  
4. Push to branch (`git push origin feature/my-feature`)  
5. Open a Pull Request

---

## 📄 License
This project is licensed under the [MIT License](./LICENSE).

---

## 🏅 Author
**Maya Shahaf Rozenberg**  
- GitHub: [MayaRo0503](https://github.com/MayaRo0503)  
- LinkedIn: [Maya Shahaf Rozenberg](https://www.linkedin.com/in/maya-rozenberg-software-engineer/)  
```

**Note:** Don’t forget to commit your `architecture.png` (or rename it appropriately) and to add `.env` to your `.gitignore` so your API key stays secret.
