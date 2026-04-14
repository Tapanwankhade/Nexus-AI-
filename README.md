# NexusAI 🤖

NexusAI is an intelligent, modern, and highly interactive ChatGPT/Gemini-like conversational web application. Built with **React** and powered by the **Google Gemini API**, NexusAI offers an immersive chat experience with multimodal capabilities including text, speech, and image processing.

## 🌟 Features

- **Brain-inspired Chat Interface**: Communicates with the powerful Gemini API for answering questions, writing code, and brainstorming ideas.
- **Multimodal Inputs**:
  - 🎤 **Speech-to-Text**: Built-in microphone support utilizing browser Speech Recognition.
  - 📎 **Image Uploads**: Feed images to NexusAI for context-aware responses and analysis.
- **Dynamic UI/UX**:
  - 🌓 **Dark/Light Mode**: Seamless theme switching with user preference saved in LocalStorage.
  - ⌨️ **Typing Effect**: Simulates natural human-like response generation word by word.
- **Conversation History**: Access previous prompts and chats from the interactive Sidebar.
- **Feature Shorts**: Clickable prompt cards providing quick starting points for Travel Planning, Education, Creative Ideas, and Coding Assistance.

## 📸 Screenshots

![Screenshot 1](https://github.com/user-attachments/assets/7efb56be-8d7d-4853-b0c7-f914644043a2)
![Screenshot 2](https://github.com/user-attachments/assets/a2acbdb9-dac4-4564-96a5-33caf658e205)
![Screenshot 3](https://github.com/user-attachments/assets/56e913bc-077a-44e6-bded-cd6140d8eb4a)

## 🛠️ Technology Stack

- **Frontend Framework**: React 19 + Vite
- **Styling**: Contextual localized CSS + Responsive Design
- **API Integration**: `@google/generative-ai`
- **State Management**: React Context API

## 🚀 Getting Started

Follow these steps to run NexusAI locally:

### Prerequisites

- [Node.js](https://nodejs.org/) (v16 or higher)
- [npm](https://www.npmjs.com/) or yarn
- A valid Google Gemini API Key

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Tapanwankhade/NexusAI.git
   cd NexusAI
   ```

2. **Install the dependencies:**
   ```bash
   npm install
   ```

3. **Environment Setup:**
   Create a secure `.env` file in the root directory (never commit this) or configure the Gemini API key inside `src/config/gemini.js` with your active token.
   _Note: Make sure to follow Google Generative AI Docs for key configuration._

4. **Start the development server:**
   ```bash
   npm run dev
   ```
   Open [http://localhost:5173](http://localhost:5173) to view it in your browser.

## 📂 Project Structure

```
NexusAI/
├── public/                 # Static assets
└── src/
    ├── assets/             # Images and Icons
    ├── components/
    │   ├── main/           # Main chat interface component
    │   └── sidebar/        # Sidebar for conversation history
    ├── config/             # Gemini API configurations
    ├── context/            # React Context for state management
    ├── App.jsx             # Root layout and theme provider
    └── main.jsx            # Entry point
```

## ✍️ Author

**Tapan Jaydeo Wankhade**
- GitHub: [@Tapanwankhade](https://github.com/Tapanwankhade)
- Project Repository: [NexusAI](https://github.com/Tapanwankhade/NexusAI)
- email: tapanjw@gmail.com

---
*Feel free to star ⭐ this repository if you found it helpful and interesting!*
