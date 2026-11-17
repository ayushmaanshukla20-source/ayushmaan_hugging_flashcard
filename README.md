<<<<<<< HEAD
# Gemini API Integration using Python

A beginner-friendly Python project demonstrating how to integrate Google's Gemini AI models using the OpenAI Python SDK and Google's OpenAI-compatible API endpoint.

This project explores how to send prompts to an AI model, manage API credentials securely, and retrieve AI-generated responses using Python.

## 🚀 Features

- Integration with Google Gemini API.
- Uses the OpenAI Python SDK for API communication.
- Secure API key management using environment variables.
- Supports system and user messages.
- Generates AI responses through chat completions.
- Simple and beginner-friendly Python implementation.

## 🛠️ Technologies Used

- **Python** – Core programming language.
- **Google Gemini API** – AI model integration.
- **OpenAI Python SDK** – API client.
- **Python-dotenv** – Environment variable management.

## 📁 Project Structure

```text
Gemini-API-Integration/
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
cd Gemini-API-Integration
```

### 3. Create a Virtual Environment (Optional)

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

Create a `.env` file in the root directory:

```env
GEMINI_API_KEY=your_gemini_api_key
```

Get your API key from [Google AI Studio](https://aistudio.google.com/apikey).

### 6. Run the Project

```bash
python app.py
```

## 💻 How It Works

1. Loads the API key from the `.env` file using `python-dotenv`.
2. Initializes the OpenAI client with Google's OpenAI-compatible API endpoint.
3. Selects the Gemini model.
4. Sends system and user messages using the chat completions interface.
5. Receives the AI-generated response.
6. Prints the response in the terminal.

## 📌 Example Prompt

**System Message:**
```text
You are a concise programming assistant.
```

**User Message:**
```text
Explain what an API is in exactly two sentences.
```

The model generates a response based on the provided instructions.

## 🔐 Security

- Never upload your actual API key to GitHub.
- Store credentials in the `.env` file.
- Add `.env` to `.gitignore`.

Example `.gitignore`:

```gitignore
.env
.venv/
__pycache__/
*.pyc
```

If an API key has already been pushed publicly, revoke it and generate a new one.

## 🎯 Learning Objectives

Through this project, I explored:

- Understanding APIs and API endpoints.
- Integrating AI models into Python applications.
- Using the OpenAI-compatible API format.
- Managing environment variables.
- Working with system and user prompts.
- Understanding AI model responses.

## 🔮 Future Improvements

- Implement conversation history.
- Add streaming AI responses.
- Build a simple graphical user interface.
- Experiment with different Gemini models.
- Implement prompt engineering techniques.
- Explore RAG (Retrieval-Augmented Generation).

## 👨‍💻 Author

**Ayushmaan Shukla**

B.Tech Computer Science Engineering  
Artificial Intelligence & Machine Learning

GitHub: [@ayushmaanshukla20-source](https://github.com/ayushmaanshukla20-source)

---

⭐ If you find this project useful, consider giving it a star!
=======
# ayushmaan_ai_training
>>>>>>> origin/main
