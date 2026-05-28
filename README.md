# 🚀 AI-Powered Code Reviewer

<div align="center">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="NodeJS" />
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="ExpressJS" />
  <img src="https://img.shields.io/badge/Google_Gemini-8E75B2?style=for-the-badge&logo=google&logoColor=white" alt="Gemini" />
</div>

<br/>

## 📌 Overview
The **AI-Powered Code Reviewer** is an intelligent, full-stack web application designed to help developers write better, cleaner, and more efficient code. By leveraging the power of the **Google Gemini 2.0 Flash AI model**, the application analyzes submitted code snippets, detects potential bugs, suggests optimal fixes, and provides industry-standard best practices in real-time. 

## ✨ Key Features
- **🤖 Intelligent Code Analysis:** Seamlessly integrated with Google's Gemini AI to parse and review code logic.
- **🐛 Instant Bug Detection:** Identifies syntax errors, unhandled exceptions, and logical flaws.
- **💡 Refactoring Suggestions:** Recommends alternative approaches to improve code readability and performance.
- **🎨 Interactive Code Editor:** Features a built-in code editor (`react-simple-code-editor`) with live syntax highlighting using `PrismJS`.
- **📝 Rich Markdown Rendering:** AI feedback is formatted cleanly using `react-markdown` and `rehype-highlight` for an intuitive reading experience.
- **⚡ Modern & Fast:** Built using Vite and React for a lightning-fast, responsive user interface.

## 🛠️ Tech Stack

### Frontend
* **Framework:** React.js (via Vite)
* **API Communication:** Axios
* **Code Editor:** `react-simple-code-editor`
* **Syntax Highlighting & Formatting:** PrismJS, React Markdown, Rehype Highlight

### Backend
* **Runtime:** Node.js
* **Framework:** Express.js
* **AI Integration:** `@google/generative-ai` (Gemini API)
* **Middleware:** CORS, Dotenv

## 🚀 Installation & Setup

Follow these steps to get the project running on your local machine.

### Prerequisites
* Node.js installed on your machine
* A Google Gemini API Key (Get it from [Google AI Studio](https://aistudio.google.com/))

### 1. Clone the Repository
```bash
git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
cd your-repo-name

## 2. ⚙️ Backend Setup

Navigate to the backend directory and install the required dependencies:

```bash
cd backend
npm install
```

Create a `.env` file in the root of the backend directory and add your Gemini API key:

```env
GEMINI_API_KEY=your_api_key_here
```

Start the backend development server:

```bash
npm run dev
```

> The backend server will spin up on `http://localhost:3000`

---

## 3. 🎨 Frontend Setup

Open a new terminal window, navigate to the frontend directory, and install the dependencies:

```bash
cd frontend
npm install
```

Start the Vite development server:

```bash
npm run dev
```

> The frontend application will be live at `http://localhost:5173`

---

# 💻 Usage

### Launch the App
Open your browser and navigate to:

`http://localhost:5173`

### Input Code
Paste or type your code snippet into the interactive editor panel on the left.

### Analyze
Click the **Review** button.

### Review Feedback
The backend will securely route your code to the Gemini AI, which will return a detailed, markdown-formatted review on the right panel — highlighting bugs, improvements, and refactored code.

---

# 🧠 System Architecture & Prompt Engineering

The core intelligence of this application relies on a highly structured system prompt passed to the Gemini 2.0 Flash model via the Express controller.

The system instructs the AI to act as an expert senior developer, ensuring the output focuses on:

- **Issue Identification**  
  Spotting unhandled exceptions, logical flaws, and poor coding practices.

- **Actionable Solutions**  
  Providing exact, copy-pasteable code fixes.

- **Educational Value**  
  Explaining why the recommended approach is better for performance and long-term maintainability.

---

# 🤝 Contributing

Contributions, issues, and feature requests are highly welcome!

If you'd like to improve this project:

1. Fork the repository  
2. Create your feature branch  
3. Commit your changes  
4. Push to the branch  
5. Submit a pull request  

You can also check the issues page for ideas and bug reports.

---

# 📄 License

This project is open-source and licensed under the **MIT License**.