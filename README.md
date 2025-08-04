
# Friday - Your Personal AI Assistant

Inspired by Iron Man's AI assistant, **Friday** is a voice-enabled, real-time personal assistant built using [LiveKit Agents](https://docs.livekit.io/ai/agents/), equipped with tools like web search, weather info, and email support.

---

## 🧠 Features

- 🎙️ Real-time voice interaction using Google’s speech plugin
- 🌦️ Weather information using `wttr.in`
- 🌐 Web search using DuckDuckGo
- 📧 Email sending via Gmail (App Password based)
- 🧞 Custom agent personality (sarcastic, classy, and always brief)

---

## 📁 Project Structure

| File | Description |
|------|-------------|
| `agent.py` | Main logic that defines the Assistant and runs the LiveKit Agent session |
| `tools.py` | Tools integrated with the agent (weather, search, email) |
| `prompts.py` | Instruction prompts defining agent behavior and session startup |
| `requirements.txt` | All required Python dependencies |

---

## 🚀 Quick Start

### 1. Clone the repository
```bash
git clone https://github.com/your-username/friday-ai-assistant.git
cd friday-ai-assistant

2. Set up environment variables

Create a .env file in the root directory with:

GMAIL_USER=your-email@gmail.com
GMAIL_APP_PASSWORD=your-app-password

> ⚠️ Use a Gmail App Password instead of your actual Gmail password.




---

3. Install Dependencies

Make sure you are using Python 3.10 or compatible.

pip install -r requirements.txt


---

4. Run the Assistant

python agent.py


---

🧩 Requirements

Python 3.10+

LiveKit Account for cloud usage (optional)

Gmail App Password



---

🗣️ Voice Persona

Friday mimics a classy, sarcastic AI butler. It only answers in one sentence and always acknowledges commands with personality, such as:

> "Will do, sir. Just sent the weather report to your inbox."




---

🤖 Powered By

LiveKit Agents

LangChain Tools

DuckDuckGo Search API

wttr.in



---

📜 License

MIT License. Feel free to use, modify, and contribute!


---

🙋‍♂️ Author

Built by [Your Name] — inspired by the genius of Stark Industries 😉

---

Would you like me to add this `README.md` file to your project folder so you can commit and push it along with the others?

