# AI Agent Project

An AI-powered conversational agent built using Python and Google's Agent Development Kit (ADK). This project demonstrates the implementation of an intelligent AI agent capable of processing user prompts and generating AI-driven responses using the Gemini API.

---

## Features

- AI-powered conversational agent
- Built using Python and Google ADK
- Gemini API integration
- Modular and beginner-friendly project structure
- Environment variable support using `.env`
- Easy local setup and execution
- Git and GitHub integration ready

---

## Tech Stack

- Python
- Google ADK
- Gemini API
- dotenv
- Virtual Environment (`venv`)
- Git & GitHub

---

## Project Structure

```plaintext
adk-workspace/
│
├── my_first_agent/
│   ├── agent.py
│   ├── __init__.py
│
├── .gitignore
├── requirements.txt
├── README.md
└── .env
```

> Note: The `.env` file is excluded from GitHub for security purposes.

---

## Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
```

---

### 2. Navigate to the project directory

```bash
cd YOUR_REPOSITORY
```

---

### 3. Create a virtual environment

```bash
python -m venv .venv
```

---

### 4. Activate the virtual environment

#### Windows

```bash
.venv\Scripts\activate
```

#### Linux / Mac

```bash
source .venv/bin/activate
```

---

### 5. Install Google ADK

```bash
pip install google-adk
```

---

### 6. Install project dependencies

```bash
pip install -r requirements.txt
```

---

### 7. Configure environment variables

Create a `.env` file in the root directory and add:

```env
GOOGLE_API_KEY=your_api_key_here
GOOGLE_GENAI_USE_VERTEXAI=0
```

---

## Running the Project

Start the AI agent using:

```bash
adk web
```

After running the command, open the local server URL displayed in the terminal in your browser.

---

## Learning Outcomes

Through this project, I gained hands-on experience in:

- Working with AI APIs
- Building AI agents using Google ADK
- Managing Python virtual environments
- Using Git and GitHub for version control
- Structuring real-world Python projects
- Handling environment variables securely

---

## Future Improvements

- Add memory support
- Integrate voice interaction
- Build a web-based frontend
- Deploy the project online
- Add multi-agent capabilities

---

## Author

**Prastab Kumar Biswas**

- B.Tech in Information Technology
- Techno Main Salt Lake

---

## License

This project is created for learning and educational purposes.