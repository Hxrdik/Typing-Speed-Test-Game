# ⌨️ Typing Speed Test Game

A fast, responsive typing speed test game built with **React**, **TypeScript**, **Tailwind CSS**, and **Vite**. It calculates **Words Per Minute (WPM)**, detects **real-time typing mistakes**, and provides feedback to help users improve typing accuracy and speed.

---

## 🚀 Features

- ⚡ Real-time WPM and accuracy tracking
- ❌ Mistake highlighting and correction suggestions
- ⏱️ Timer-based and endless typing modes
- 🔤 Random word generation using a Trie data structure
- 🖥️ Responsive and clean UI for desktop and mobile
- 🌐 Live demo deployed with Netlify

---

## 🛠️ Tech Stack

- **React** – for building the UI components  
- **TypeScript** – for type safety and scalability  
- **Tailwind CSS** – for modern, responsive design  
- **Vite** – for fast bundling and development  
- **Trie Algorithm** – for fast word lookup and random generation

---

## 📦 Installation

```bash
git clone https://github.com/your-username/typing-speed-test.git
cd typing-speed-test
npm install
npm run dev





├── public/                 # Static files
├── src/
│   ├── components/         # React components (Timer, InputBox, etc.)
│   ├── data/               # Word list & Trie logic
│   ├── utils/              # Helper functions
│   ├── App.tsx             # Root component
│   └── main.tsx            # Entry point
├── tailwind.config.js
├── vite.config.ts
└── package.json
