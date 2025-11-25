# Rachel---JobPrep-AI-Interview-Prep-Partner-Agentic-AI-
💼 JobPrep AI – Powered by Rachel 🎤

An AI-driven mock interview assistant designed to help candidates practice for real technical and non-technical job interviews.
Built as part of the Eightfold.ai – AI Agent Building Assignment.

Rachel — your interviewer — offers:
✔ Adaptive conversation
✔ Technical + Behavioral interview flow
✔ Hidden test-case based code evaluation
✔ Scenario-based reasoning
✔ Voice input & voice output support
✔ Personalized feedback

🚀 Features
🧑‍💼 Role-Aware Interviewing

Select role and experience:

Software Engineer

Data Scientist

Sales Associate

Retail Associate

Technical roles include coding and DSA questions.
Non-technical roles focus on behavioral + scenario-based questions.

🎙 Conversation Personas Supported

Rachel adapts her interviewing style for different types of users:

Persona	Behavior
Confused User	Explains questions clearly + gives guidance
Efficient User	Quick, concise interview flow
Chatty User	Polite redirecting to keep interview on track
Edge-Case User	Graceful fallback and capability messaging
💻 Coding Round (Python Execution)

Code editor: streamlit-ace

Auto-evaluation using hidden tests

Smart hinting system:

Attempt 1 → small hint

Attempt 2 → stronger hint

Attempt 3+ → full example solution allowed

Coding topics:

Sum of Array (base question)

DSA (Two Sum / Contains Duplicate)

🗣 Voice Interaction

Speech Input (via Groq Whisper)

Speech Output (via gTTS)

Toggleable voice mode

Auto-play only for natural spoken messages (not code)

📝 End-Interview Feedback

Structured evaluation:

Overall performance

Communication skills

Technical ability

Problem-solving approach

Actionable improvement suggestions

🧠 System Architecture
Component	Tech
Frontend	Streamlit
LLM	Groq – llama-3.1-8b-instant
Code Execution	Python sandbox via exec
Speech-to-Text	Groq Whisper (whisper-large-v3)
Text-to-Speech	gTTS
Code Editor	streamlit-ace
State Management	Streamlit Session State
📌 Flow Overview

1️⃣ Greeting — Rachel introduces herself
2️⃣ Behavioral warm up
3️⃣ Technical coding (if role requires)
4️⃣ Hints + re-attempts → DSA progression
5️⃣ Scenario-based behavioral
6️⃣ Final structured feedback

🛠 Installation & Setup

Clone repo:

git clone https://github.com/<your-username>/jobprep-ai-rachel.git
cd jobprep-ai-rachel


Create virtual environment:

python -m venv venv
source venv/bin/activate  # Mac/Linux
venv\Scripts\activate     # Windows


Install dependencies:

pip install -r requirements.txt


Create .env:

GROQ_API_KEY=your_api_key_here


Run application:

streamlit run app.py


👤 Author

Teja Shree R 
B.Tech – Artificial Intelligence & Data Science

Built for: Eightfold.ai – AI Agent Building Assignment
Project Codename: JobPrep AI – Rachel
