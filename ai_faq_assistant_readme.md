# AI FAQ Assistant for DataTalksClub

**Answer student questions from DataTalksClub courses instantly**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)  
[![Python Version](https://img.shields.io/badge/python-3.10+-blue)](https://www.python.org/)

This project was created as part of the [7-Day AI Agents Crash Course](https://github.com/SeidaAhmed/7-Day-AI-Agents-Crash-Course). It transforms static FAQ documents into an interactive AI-powered assistant, making it easier for students to find relevant course information quickly.

---

## Overview

Finding information in traditional FAQ documents can be slow and frustrating. This AI assistant:

- Provides instant answers to course-related questions
- Guides users to relevant sections and links in the documentation
- Makes learning more interactive and efficient

**Screenshots / GIFs / Demo:**

![Screenshot](./images/screenshot.png)  
*Add GIF or video demo here if possible*

---

## Installation

### Requirements

- Python 3.10+  
- Streamlit  
- OpenAI API key  
- Other dependencies listed in `requirements.txt`

### Steps to run locally

1. Clone the repository:  
```bash
git clone https://github.com/SeidaAhmed/7-Day-AI-Agents-Crash-Course.git
cd 7-Day-AI-Agents-Crash-Course
```

2. Create a virtual environment:  
```bash
python -m venv venv
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate     # Windows
```

3. Install dependencies:  
```bash
pip install -r requirements.txt
```

4. Set your OpenAI API key as an environment variable:  
```bash
export OPENAI_API_KEY="your_api_key_here"  # macOS/Linux
setx OPENAI_API_KEY "your_api_key_here"     # Windows
```

---

## Usage

Run the app locally:  
```bash
streamlit run app/app.py
```

Once the app launches:  
- Type your question in the chat interface  
- The assistant will respond with answers and relevant links  
- Your conversation is saved in the session for easy reference

**Example questions:**  
- "What topics are covered in the Data Engineering course?"  
- "How do I set up my project environment?"

---

## Features

- AI-powered FAQ search  
- Real-time streaming responses  
- Chat history in the session  
- Modular Python code for easy extension  
- Easy deployment with Streamlit Cloud

**Upcoming features / roadmap:**  
- Add support for multiple DataTalksClub repositories  
- User authentication for personalized sessions  
- Export conversation history

---

## Contributing

- Fork the repository  
- Create a branch for your feature:  
```bash
git checkout -b feature-name
```
- Submit a pull request with a clear description  

Follow PEP8 coding style and best practices for Python.

---

## Tests

Run tests with:  
```bash
pytest tests/
```

Make sure all dependencies are installed in your virtual environment.

---

## Deployment

Deploy to Streamlit Cloud:  
1. Push your code to a GitHub repository  
2. Go to [Streamlit Cloud](https://share.streamlit.io/) → “New App”  
3. Select repository and branch, set entrypoint (e.g., `app/app.py`)  
4. Add OpenAI API key as a secret (`OPENAI_API_KEY`)  
5. Click Deploy

---

## FAQ / Troubleshooting

**Q:** The app fails to start with an OpenAI error.  
**A:** Make sure your `OPENAI_API_KEY` is set in your environment or Streamlit secrets.  

**Q:** Chat responses are slow.  
**A:** Streaming is async; ensure a stable internet connection and API usage limits are not exceeded.

---

## Credits / Acknowledgments

- DataTalksClub for the course content  
- OpenAI for GPT API  
- Streamlit for the UI framework  
- [AI Agents Crash Course](https://github.com/SeidaAhmed/7-Day-AI-Agents-Crash-Course) for guidance

---

## License

MIT License – see the [LICENSE](LICENSE) file.