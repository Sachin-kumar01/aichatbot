# AI Chatbot

An intelligent web-based chatbot that uses Google's Gemini AI to generate accurate and natural responses in real time. The project is built with Flask and provides a clean, responsive interface where users can interact with an AI assistant directly from their browser.

The primary goal of this project is to demonstrate how Large Language Models (LLMs) can be integrated into a modern web application using Python and Flask.

---

## Features

* Real-time AI conversation
* Google Gemini API integration
* Clean and responsive user interface
* Fast Flask backend
* Secure API key management using environment variables
* Lightweight and easy to deploy
* Mobile-friendly design

---

## Tech Stack

**Frontend**

* HTML5
* CSS3
* JavaScript
* Bootstrap

**Backend**

* Python
* Flask

**AI Model**

* Google Gemini API

**Deployment**

* Render

**Version Control**

* Git & GitHub

---

## Project Structure

```text
aichatbot/
│
├── static/
│   ├── css/
│   ├── js/
│   └── images/
│
├── templates/
│   └── index.html
│
├── app.py
├── requirements.txt
├── runtime.txt
├── .env
├── .gitignore
└── README.md
```

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Sachin-kumar01/aichatbot.git
cd aichatbot
```

### 2. Create a Virtual Environment

Windows

```bash
python -m venv venv
venv\Scripts\activate
```

Linux / macOS

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure Environment Variables

Create a `.env` file in the project root.

```env
GEMINI_API_KEY=YOUR_GEMINI_API_KEY
```

### 5. Run the Application

```bash
python app.py
```

Open your browser and visit:

```
http://127.0.0.1:5000
```

---

## How It Works

1. The user types a message in the chat interface.
2. Flask receives the request from the frontend.
3. The backend sends the prompt to the Gemini API.
4. Gemini processes the request and generates a response.
5. The generated response is returned and displayed instantly in the chat window.

---

## Deployment

This project can be deployed easily on Render.

**Build Command**

```bash
pip install -r requirements.txt
```

**Start Command**

```bash
gunicorn app:app
```

Don't forget to add the following environment variable in your deployment settings:

```text
GEMINI_API_KEY=YOUR_GEMINI_API_KEY
```

---

## Future Improvements

Some features planned for future versions include:

* Conversation history
* User authentication
* Multiple AI model support
* Voice input and speech response
* File and image upload
* Markdown response rendering
* Dark mode
* Export chat as PDF or TXT
* Multi-language support

---

## Screenshots

You can add screenshots here after deployment.

```
screenshots/
├── home.png
├── chat.png
├── response.png
└── mobile.png
```

---

## Contributing

Contributions are always welcome.

If you would like to improve the project:

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Commit and push your code.
5. Open a Pull Request.

---

## License

This project is available under the MIT License.

---

## Author

**Sachin Kumar**

* GitHub: https://github.com/Sachin-kumar01
* Project: https://github.com/Sachin-kumar01/aichatbot

If you found this project helpful, consider giving it a ⭐. It helps others discover the project and motivates future improvements.
