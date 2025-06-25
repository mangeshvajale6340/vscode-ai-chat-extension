# VS Code AI Chat Extension

A Visual Studio Code extension that provides an in-editor AI chat interface built with React. The extension allows developers to chat with an AI assistant, attach file references via @filename, and receive code suggestions within the editor.

## 🚀 Features
- 💬 AI-powered code chat interface
- 📎 Support for file & image attachment using @filename syntax
- ⚛️ React-based chat UI embedded in a VS Code Webview
- 📂 File context-aware suggestions
- 🔁 Message history display

## 🛠️ Installation & Setup

### 1. Clone the Repository
git clone https://github.com/mangeshvajale6340/vscode-ai-chat-extension.git
cd vscode-ai-chat-extension

### 2. Install Dependencies
npm install

### 3. Build the React Webview
cd webview-ui
npm install
npm run build
cd ..

### 4. Compile the Extension
npm run compile

### 5. Run in VS Code
code .
Press F5 to launch the extension in a new Extension Development Host

## 📦 Project Structure
vscode-ai-chat-extension/
├── media/
├── src/
│   └── extension.ts
├── webview-ui/
│   ├── components/
│   ├── App.tsx
│   └── index.tsx
├── package.json
├── tsconfig.json
├── webpack.config.js
└── README.md

## 📸 Screenshots (optional)
![AI Chat Preview](media/extension-preview.png)

## 🧑‍💻 Author
**Mangesh Vajale**  
📧 mangeshvajale1631@gmail.com  
📱 +91 87675 61631

## 📄 License
MIT
