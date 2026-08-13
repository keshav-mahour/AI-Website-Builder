# 🤖 AI Website Builder

An AI-powered website builder that generates responsive React websites from natural-language prompts. The generated code can be viewed, edited, and previewed directly in the browser.

## 🚀 Features

- 🤖 **AI Website Generation** — Generate complete website structures from natural-language prompts.
- ⚡ **Live Preview** — Instantly preview generated websites in the browser.
- 🧩 **React Code Generation** — Generate modular React components and project files.
- 📝 **In-Browser Code Editor** — View and edit generated source code.
- 🔄 **Real-Time Preview** — See changes reflected directly in the preview.
- 🔐 **User Authentication** — Secure registration and login system using JWT-based sessions.
- 💾 **Project Persistence** — Save and manage generated projects using MongoDB.
- 📦 **Project Export** — Export generated project files for further development.
- 🎨 **Responsive UI** — Generate responsive websites suitable for different screen sizes.
- 🛠️ **Code Validation** — Generated code is processed and validated before preview.

## 🧠 How It Works

```text
User Prompt
     ↓
OpenRouter AI
     ↓
AI-generated Project Structure
     ↓
React Components & Files
     ↓
Code Validation / Normalization
     ↓
Sandpack
     ↓
Live Website Preview
```

The user provides a natural-language prompt describing the website they want to create. The application sends the request to an AI model through OpenRouter, processes the generated project files, validates the code, and renders the result using Sandpack.

## 🛠️ Tech Stack

### Frontend

- React.js
- Vite
- Tailwind CSS
- Sandpack
- JavaScript

### Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication

### AI

- OpenRouter API

## ⚙️ Installation & Setup

### Clone the Repository

```bash
git clone https://github.com/keshav-mahour/AI-Website-Builder.git
cd AI-Website-Builder
```

### Start the Backend

```bash
cd server
npm install
npm run dev
```

The backend requires environment variables for MongoDB, JWT authentication, and OpenRouter.

### Start the Frontend

Open a new terminal:

```bash
cd client
npm install
npm run dev
```

The frontend will run locally using Vite.

## 🔑 Environment Variables

The backend requires the following environment variables:

```env
JWT_SECRET=your_jwt_secret
MONGODB_URI=your_mongodb_uri
OPENROUTER_API_KEY=your_openrouter_api_key
OPENROUTER_MODEL=openrouter/free
ORIGINS=http://localhost:5173
```

> Never commit `.env` files or API keys to GitHub.

## 📁 Project Structure

```text
AI-Website-Builder/
│
├── client/
│   ├── src/
│   │   ├── components/
│   │   ├── api/
│   │   ├── utils/
│   │   └── ...
│   ├── package.json
│   └── vite.config.js
│
├── server/
│   ├── models/
│   ├── routes/
│   ├── services/
│   ├── server.js
│   └── package.json
│
└── README.md
```

## 🎯 Example Prompt

```text
Create a modern website for a coffee shop with a responsive
layout, navigation bar, hero section, menu, testimonials,
and contact section.
```

The AI generates the corresponding React project structure and the website can then be viewed and edited through the live development interface.

## 🔮 Future Improvements

- One-click deployment of generated websites
- AI-powered automatic bug fixing
- Support for multiple AI models
- Project version history
- More advanced website templates
- Improved code generation and validation

## 👨‍💻 Author

**Keshav Mahour**

B.Tech — Electronics and Computer Engineering

---

⭐ If you find this project interesting, consider giving it a star!
