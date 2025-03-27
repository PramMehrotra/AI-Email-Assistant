# AI Auto Email Responder

## 📌 Introduction
This project is an **AI-powered automatic email responder** that reads incoming emails, generates appropriate responses using **LangChain** and **Ollama**, and sends replies automatically. It is designed to work with **IMAP** and **SMTP** email services like Gmail.

## 🚀 Features
- Reads unread emails from an inbox.
- Uses **Ollama (LLM)** to generate context-aware replies.
- Sends automatic responses via SMTP.
- Runs periodically to check for new emails.

## 🛠️ Requirements
### 🔹 Install Dependencies
Ensure you have Python installed, then run:
```sh
pip install -r requirements.txt
```

### 🔹 Environment Variables (`.env` file)
Create a `.env` file in the project root with the following:
```
EMAIL_ADDRESS=your-email@gmail.com
EMAIL_PASSWORD=your-email-password
IMAP_SERVER=imap.gmail.com
SMTP_SERVER=smtp.gmail.com
SMTP_PORT=587
OLLAMA_MODEL=mistral
```
> **Note**: If using Gmail, enable IMAP and generate an App Password.

## 🏃‍♂️ Running the Script
To start the auto email responder, run:
```sh
python app.py
```
The script will check for unread emails every 60 seconds and respond automatically.

## 📌 Technologies Used
- **LangChain** for AI-generated email responses.
- **Ollama** as the LLM model.
- **IMAP & SMTP** for email handling.
- **Python-dotenv** for managing environment variables.

## 🤝 Contributing
Feel free to submit pull requests or report issues. Let's improve it together! 🚀
