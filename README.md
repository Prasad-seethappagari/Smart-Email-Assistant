# 🚀 Smart Email Assistant

An AI-powered Smart Email Assistant that helps users generate professional and context-aware email replies directly inside Gmail using Generative AI.

This project integrates a Chrome Extension, React frontend, and Spring Boot backend with the Gemini API to automate email writing and improve productivity.

---

# 📌 Features

- ✨ AI-generated email replies
- 🎯 Multiple email tone options (Professional, Friendly, Casual, etc.)
- 🌐 Gmail integration through Chrome Extension
- ⚡ Fast response generation using Gemini API
- 🖥️ Interactive React frontend
- 🔗 REST API integration with Spring Boot
- 📋 Easy-to-use and lightweight interface
- 📩 Context-aware smart email generation

---

# 🛠️ Tech Stack

## Frontend
- React.js
- JavaScript
- HTML5
- CSS3

## Backend
- Spring Boot
- Java
- REST API

## AI Integration
- Gemini API

## Browser Extension
- Chrome Extension APIs
- Manifest V3

---

# 🏗️ Project Architecture

```text
User → Chrome Extension / React UI
            ↓
      Spring Boot Backend
            ↓
        Gemini API
            ↓
   AI Generated Email Reply
```

---

# 📂 Project Structure

```text
Smart-Email-Assistant/
│
├── email-writer-sb/        # Spring Boot Backend
├── email-writer-react/     # React Frontend
├── email-writer-ext/       # Chrome Extension
│
├── README.md
└── pom.xml
```

---

# ⚙️ Installation & Setup

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/Prasad-seethappagari/Smart-Email-Assistant.git

cd Smart-Email-Assistant
```

---

# 🔹 Backend Setup (Spring Boot)

## Navigate to Backend Folder

```bash
cd email-writer-sb
```

## Configure Environment Variables

Create an `application.properties` or configure environment variables:

```properties
gemini.api.url=YOUR_GEMINI_API_URL
gemini.api.key=YOUR_GEMINI_API_KEY
```

## Run Backend

```bash
mvn spring-boot:run
```

Backend will start on:

```text
http://localhost:8080
```

---

# 🔹 Frontend Setup (React)

## Navigate to Frontend Folder

```bash
cd email-writer-react
```

## Install Dependencies

```bash
npm install
```

## Start React Application

```bash
npm run dev
```

Frontend will start on:

```text
http://localhost:5173
```

---

# 🔹 Chrome Extension Setup

## Navigate to Extension Folder

```bash
cd email-writer-ext
```

## Load Extension in Chrome

1. Open Chrome Browser
2. Go to:

```text
chrome://extensions/
```

3. Enable **Developer Mode**
4. Click **Load Unpacked**
5. Select the `email-writer-ext` folder

The extension will now be added to Chrome.

---

# 🤖 How It Works

1. User opens Gmail
2. Chrome Extension injects AI Reply button
3. User clicks AI Reply
4. Email content is sent to Spring Boot backend
5. Backend calls Gemini API
6. AI-generated response is returned
7. User can copy and send the generated email

---

# 📡 API Endpoint

## Generate Email Reply

### POST Request

```http
POST /api/email/generate
```

### Request Body

```json
{
  "emailContent": "Can you attend the meeting tomorrow?",
  "tone": "Professional"
}
```

### Response

```json
{
  "reply": "Thank you for your email. I would be happy to attend the meeting tomorrow."
}
```

---

# 📸 Screenshots

## Gmail Integration

Add your screenshots here:

```md
![Home](screenshots/home.png)
```

```md
![AI Reply](screenshots/reply.png)
```

---

# 🚀 Future Enhancements

- 📧 Email summarization
- 🌍 Multi-language support
- 🧠 Personalized AI responses
- 🔒 User authentication
- ☁️ Cloud deployment
- 📱 Mobile support
- 📝 Smart templates

---

# 🔐 Environment Variables

```properties
GEMINI_API_KEY=your_api_key
```

---

# 🧪 Testing

## Backend

```bash
mvn test
```

## Frontend

```bash
npm test
```

---

# 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create your feature branch

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

5. Create Pull Request

---

# 📄 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

Developed by Prasad Seethappagari

- GitHub: https://github.com/Prasad-seethappagari

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.
