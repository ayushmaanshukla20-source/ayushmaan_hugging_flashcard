# AI Flashcard Generator using Gemini 3.6 Flash

An AI-powered Flashcard Generator built using Python and Google's Gemini API. This project uses Gemini 3.6 Flash to generate topic-based flashcards, helping students learn and revise technical concepts more effectively.

The application demonstrates how to integrate a Large Language Model (LLM) into a Python application using API authentication and prompt engineering.

## 🚀 Features

- Generate AI-powered flashcards based on user-provided topics.
- Uses Google Gemini 3.6 Flash as the AI model.
- Accepts custom topics through user input.
- Generates structured learning content.
- Integrates Google's Gemini API with Python.
- Secure API key management using environment variables.

## 🛠️ Technologies Used

- **Python** – Core programming language.
- **Google Gemini API** – AI-powered flashcard generation.
- **Gemini 3.6 Flash** – Language model.
- **OpenAI Python SDK** – API client using Google's OpenAI-compatible endpoint.
- **Python-dotenv** – Environment variable management.

## 🤖 AI Model

**Gemini 3.6 Flash**

The application uses Google's Gemini model through the OpenAI-compatible API interface.

API Endpoint:

```text
https://generativelanguage.googleapis.com/v1beta/openai/
```

## 📁 Project Structure

```text
huggingface_flashcards/
│
├── app.py
├── .env
├── .gitignore
└── README.md
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Navigate to the Project Directory

```bash
cd huggingface_flashcards
```

### 3. Create a Virtual Environment

```bash
python -m venv .venv
```

Activate it:

**Windows:**

```bash
.venv\Scripts\activate
```

**Mac/Linux:**

```bash
source .venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install openai python-dotenv
```

### 5. Configure API Key

Create a `.env` file:

```env
GEMINI_API_KEY=your_gemini_api_key
```

Get your API key from:

https://aistudio.google.com/apikey

### 6. Run the Application

```bash
python app.py
```

## 🔍 How It Works

1. Loads the Gemini API key from the `.env` file.
2. Initializes the OpenAI Python client with Google's compatible API endpoint.
3. Connects to Gemini 3.6 Flash.
4. Accepts a topic from the user.
5. Sends the topic and instructions to the AI model.
6. Receives the generated flashcards.
7. Displays the output for learning and revision.

## 🎯 Learning Objectives

Through this project, I explored:

- Understanding Large Language Models (LLMs).
- Integrating Gemini API with Python.
- Using OpenAI-compatible API interfaces.
- Managing API credentials securely.
- Understanding system and user prompts.
- Learning prompt engineering.
- Generating structured AI responses.

## 🔮 Future Improvements

- Develop a web-based flashcard interface.
- Add interactive question-and-answer functionality.
- Implement flashcard categories and difficulty levels.
- Save generated flashcards for future revision.
- Add user progress tracking.
- Explore Retrieval-Augmented Generation (RAG).

## 👨‍💻 Author

**Ayushmaan Shukla**

B.Tech Computer Science Engineering  
Artificial Intelligence & Machine Learning

GitHub: [@ayushmaanshukla20-source](https://github.com/ayushmaanshukla20-source)

---

⭐ If you find this project interesting, consider giving the repository a star!