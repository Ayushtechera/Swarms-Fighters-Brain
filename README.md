# 🤖 Swarm Fighters
<img width="959" height="515" alt="Screenshot 2026-07-14 000751" src="https://github.com/user-attachments/assets/e3f81215-140f-400e-845b-73d8e00cd9bd" />
<img width="838" height="457" alt="Screenshot 2026-07-14 000955" src="https://github.com/user-attachments/assets/5a479f07-ec02-4350-8d1c-edbea462b84a" />
<img width="798" height="458" alt="Screenshot 2026-07-14 001018" src="https://github.com/user-attachments/assets/b03acc8b-068b-41c1-8f2e-88b31bc2e0eb" />

Swarm Fighters is a simple Multi-Agent AI project where four LLMs communicate with each other to complete a shared mission.

Each AI agent has a different responsibility:

- 🛰️ Navigator
- 📐 Formation Planner
- ✅ Verifier
- 🎯 Coordinator

The agents discuss, calculate, verify each other's responses, and work together to reach a final decision.

## Features

- Four AI agents
- Multi-agent communication
- Real-time streaming responses
- Gradio interface
- Different roles for each agent

## Tech Stack

- Python
- Gradio
- Google Gemini
- Mistral AI
- Groq
- DeepSeek
- OpenAI SDK

## Installation

```bash
git clone <your-repository-url>

cd Swarm-Fighters

pip install -r requirements.txt
```

Create a `.env` file and add your API keys:

```env
GEMINI_API_KEY=your_key
MISTRAL_API_KEY=your_key
GROQ_API_KEY=your_key
DEEPSEEK_API_KEY=your_key
```

Run the project:

```bash
python app.py
```

## How It Works

1. Four AI agents are initialized.
2. Each agent receives a unique role.
3. The agents communicate with one another.
4. They collaborate, verify calculations, and reach a common decision.
5. The complete conversation is streamed live in the Gradio interface.

## Project Structure

```text
Swarm-Fighters/
│── app.py
│── requirements.txt
│── README.md
```

## Note

This project is built for learning and experimenting with Multi-Agent AI systems and LLM collaboration.
