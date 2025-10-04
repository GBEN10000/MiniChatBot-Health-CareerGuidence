Health / Career Chatbot

A responsive, Chatbot for Health and Career guidance, built with Flask (Python) and Google Gemini API. Users can chat via text input, switch between Health and Career modes, and get AI-generated responses in a dark-themed, mobile-friendly interface.

Features

🩺 Health Mode: Get suggestions and guidance for common health-related questions.

💼 Career Mode: Receive advice for career planning, especially for AI/tech students.

💬 ChatGPT-style Interface: Chat bubbles for user and bot.

🌓 Dark Theme: Easy on the eyes, looks like ChatGPT.

📱 Responsive Design: Works on mobile and desktop.

⚡ Typing Animation: Shows “Bot is typing…” for better UX.

Demo Screenshot

(Add a screenshot of your chatbot UI here for reference)

Prerequisites

Python 3.6+

Flask (pip install Flask)

Google Gemini API access

Internet connection for API requests

Project Structure
Health-Career/
│
├─ app.py              # Flask backend
├─ templates/
│   └─ index.html      # Chatbot frontend (HTML, inline CSS & JS)
└─ README.md           # Project instructions


All CSS and JS are inline in index.html. No external static folder required.

Setup Instructions

Clone the repository

git clone https://github.com/GBEN10000/MiniChatBot-Health-CareerGuidence.git
cd MiniChatBot-Health-CareerGuidence


Install dependencies

pip install Flask google-genai


Set your Gemini API key

On Windows PowerShell:

$Env:GEMINI_API_KEY = "your_gemini_api_key_here"


On macOS/Linux:

export GEMINI_API_KEY="your_gemini_api_key_here"


Run the Flask server

python app.py


Open your browser

Navigate to: http://127.0.0.1:5000

Start chatting!

Switch between Health 🩺 and Career 💼 using the buttons.

Type your message in the input box and hit Enter or Send.

AI responses appear in chat bubbles.

Usage Example

Health Mode:

User: I have a headache.
Bot: It might be due to stress or dehydration. Drink water, rest for a while. If it persists, please consult a doctor.


Career Mode:

User: What career is good for AI students?
Bot: If you're interested in AI, you can explore roles like Machine Learning Engineer, Data Scientist, or AI Researcher.

Notes

Ensure your Gemini API key is valid and has sufficient access.

The chatbot is text-only. Audio/speech input is currently not supported.

For production deployment, use a proper WSGI server instead of Flask’s dev server.

Future Improvements

Add voice input/output.

Save chat history per user.

Support multiple languages.

Enhance UI with animations like ChatGPT.

License

MIT License – feel free to use, modify, and distribute.
