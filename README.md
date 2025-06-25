# 💡 DevPrompt – Developer Prompt Workspace

**DevPrompt** is a web-based application that helps developers craft, organize, and test AI prompts with ease. Whether you're working with ChatGPT, Claude, or local LLMs, DevPrompt is your central hub for building effective prompts with live previews, reusable templates, and visual formatting.

---

## 🚀 Features

- ✍️ **Prompt Editor** – Write and tweak prompts in a clean editor
- 📂 **Prompt Library** – Save, categorize, and reuse custom prompts
- 🔁 **Live Output Preview** *(optional via OpenAI API)*
- 🧪 **Prompt Testing Playground** – Modify temperature, tokens, role context
- 🧠 **Prompt Templates** – Developer-focused examples for coding, bug fixes, etc.
- 🌙 **Dark/Light Mode** – User-friendly theme switcher

---

## 📸 Screenshots

> _Add screenshots here to show the editor, prompt output, and prompt management tabs._

---

## 🧱 Tech Stack

- **Frontend**: React.js, Tailwind CSS
- **State Management**: Zustand or Redux Toolkit
- **Optional API**: OpenAI (for testing outputs)
- **Editor**: CodeMirror / Monaco Editor
- **Build Tool**: Vite

---

## 📁 Project Structure
devprompt/
├── public/
├── src/
│ ├── components/ # Reusable UI elements
│ ├── pages/ # Editor, Library, Settings
│ ├── api/ # Prompt API (if used)
│ ├── context/ # State management
│ └── main.jsx
├── tailwind.config.js
├── package.json
└── README.md

