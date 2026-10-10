# AI Personal Assistant 🤖

An AI-powered personal assistant built with Python and Flask that lets you ask anything, get AI-generated answers, and summarize emails quickly and efficiently through a simple, user-friendly web interface.

## ✨ Features

- **Ask Anything:** Get AI-generated answers to your questions.
- **Email Summarization:** Summarize emails into concise, easy-to-understand content.
- **AI Integration:** Uses an AI language model API to generate responses.
- **Simple Web Interface:** Clean and user-friendly interface.
- **Flask Backend:** Handles requests and connects the frontend with AI services.

## 🛠️ Tech Stack

- **Programming Language:** Python
- **Backend:** Flask
- **Frontend:** HTML, CSS, JavaScript
- **AI:** Large Language Model API
- **Version Control:** Git and GitHub

## 📁 Project Structure

```text
AI-Personal-Assistant/
├── main.py
├── templates/
│   └── index.html
├── static/
│   └── style.css
├── .gitignore
├── LICENSE
└── README.md
```

## 🚀 Getting Started

### Prerequisites

- Python 3.10 or later
- Git
- An API key for the AI service used by the application

### 1. Clone the Repository

```bash
git clone https://github.com/Danish-khan77/AI-Personal-Assistant.git
cd AI-Personal-Assistant
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 3. Install Dependencies

If a `requirements.txt` file exists:

```bash
pip install -r requirements.txt
```

Otherwise, install the dependencies required by your project.

### 4. Configure Environment Variables

Create a `.env` file in the project root and add the API key required by your application.

```env
API_KEY=your_api_key_here
```

Use the exact environment variable name expected by your code. Never commit your `.env` file or expose your API key publicly.

### 5. Run the Application

```bash
python main.py
```

Open the local URL displayed in your terminal, usually `http://127.0.0.1:5000`.

## 🔐 Security

- Keep API keys and other secrets in environment variables.
- Do not upload `.env` files to GitHub.
- Do not share credentials publicly.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Danish Khan**

- GitHub: [@Danish-khan77](https://github.com/Danish-khan77)
- LinkedIn: [danish-khan-cse](https://linkedin.com/in/danish-khan-cse)