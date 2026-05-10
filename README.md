# 📧 Smart Email Assistant

An AI-powered Smart Email Assistant built using Streamlit, LangChain, and Gmail API to help users efficiently manage their inbox. The application can summarize emails, clean unwanted messages, categorize emails, create Gmail filters automatically, and provide an AI-powered chat interface for email management.

---

# 🚀 Features

- Summarize unread emails instantly
- Clean promotional or spam emails older than 30 days
- Automatically categorize emails into:
  - Promotions
  - Work
  - Personal
- Create Gmail filters automatically
- AI-powered email assistant using LangChain
- Supports OpenAI and Google Gemini models
- Unsubscribe from unwanted newsletters
- Simple and user-friendly Streamlit interface

---

# 🛠️ Tech Stack

- Python
- Streamlit
- LangChain
- Gmail API
- OpenAI API
- Google Gemini API
- OAuth 2.0 Authentication

---

# 📂 Project Structure

```bash
Smart-Email-Assistant/
│
├── tools/
├── __pycache__/
├── .env.example
├── .gitignore
├── LICENSE
├── README.md
├── agent.py
├── app.py
├── requirements.txt
└── utils.py
```

---

# ⚙️ Installation & Setup

## 1. Clone the Repository

```bash
git clone https://github.com/your-username/Smart-Email-Assistant.git
cd Smart-Email-Assistant
```

## 2. Create Virtual Environment

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### macOS/Linux

```bash
python3 -m venv venv
source venv/bin/activate
```

## 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

# 🔑 Gmail API Setup

## Step 1: Create Google Cloud Project

- Open Google Cloud Console
- Create a new project
- Enable Gmail API

## Step 2: Configure OAuth Consent Screen

- Add required scopes
- Configure test users if needed

## Step 3: Create OAuth Credentials

- Create OAuth Client ID
- Download the credentials JSON file
- Rename the file to:

```bash
credentials.json
```

- Place it inside the project root folder

---

# 🌍 Environment Variables

Create a `.env` file in the project root directory.

## Example `.env`

```env
GOOGLE_API_KEY=your_google_gemini_api_key
OPENAI_API_KEY=your_openai_api_key
```

---

# ▶️ Running the Application

Run the Streamlit application using:

```bash
streamlit run app.py
```

The application will automatically open in the browser.

---

# 💡 Usage

Use the AI chat interface to interact with your inbox.

## Example Commands

```text
Summarize my unread emails
Delete old marketing emails
Categorize my inbox
Create Gmail filters
```

Users can also use sidebar quick actions for faster operations.

---

# 🔒 Authentication Flow

When the application runs for the first time:

1. Gmail authentication window opens
2. Login with Gmail account
3. Grant required permissions
4. `token.json` file will be generated automatically

---

# 📸 Main Functionalities

## 📬 Email Summarization

Quickly summarize unread emails using AI models.

## 🧹 Inbox Cleaning

Delete old promotional and unwanted emails automatically.

## 🏷️ Smart Categorization

Automatically classify emails into categories.

## 🤖 AI Chat Assistant

Interact with emails using natural language prompts.

## 📩 Newsletter Unsubscription

Detect and unsubscribe from unnecessary newsletters.

---

# 📋 Requirements

- Python 3.8+
- Gmail Account
- Google Cloud Project
- Gmail API Enabled
- OpenAI API Key or Gemini API Key

---

# 🔮 Future Enhancements

- One-click unsubscribe automation
- AI-generated email reply suggestions
- Calendar integration
- Task creation from emails
- Multi-email provider support
- Advanced machine learning categorization
- Voice-enabled email assistant

---

# 🤝 Contributing

Contributions are welcome.

## Steps to Contribute

1. Fork the repository

2. Create a new feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push to GitHub

```bash
git push origin feature-name
```

5. Create a Pull Request

---

# 📜 License

This project is licensed under the MIT License.

---

# ⭐ Support

If you found this project useful:

- Star the repository
- Share the project
- Contribute to improve it

---

# 📧 Contact

For suggestions, issues, or improvements, create an issue in the repository.

---

Made with ❤️ using Python and AI
