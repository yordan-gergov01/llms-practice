# 🤖 LLMs Practice

A collection of hands-on mini-projects exploring the capabilities of Large Language Models (LLMs) using the OpenAI API and Gradio. Each project is self-contained and focuses on a distinct real-world use case.

## 🚀 Projects

### ✈️ Airline Assistant
A conversational AI assistant tailored for airline customer support. Handles typical passenger queries such as flight information, baggage policies, cancellations, and rebooking — demonstrating how LLMs can be adapted to domain-specific assistant roles using system prompts.

### 📄 Business Brochure Generator
Takes a company name or URL as input and generates a polished, professional business brochure. Uses web scraping (via `scraper.py`) to gather context about a company and then prompts the LLM to produce structured marketing content.

### 💻 Code Generator
Converts plain-English descriptions into working code. Demonstrates how to leverage LLMs for developer productivity tasks — users describe what they want and receive a ready-to-use code snippet with explanations.

### 💬 Gradio Chat UI
A clean, interactive chat interface built with [Gradio](https://www.gradio.app/). Serves as a reusable template for wrapping any LLM-powered backend in a user-friendly web UI — useful as a starting point for demos and prototypes.

### 🎓 Technical Tutor
An AI tutor focused on technical subjects. Guides users through concepts step by step, answers follow-up questions, and adapts explanations to the user's level — showcasing multi-turn conversation management and instructional prompt design.

## ⚙️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yordan-gergov01/llms-practice.git
cd llms-practice
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Set your OpenAI API key

```bash
export OPENAI_API_KEY="your-api-key-here"
```

Or create a `.env` file in the root directory:

```
OPENAI_API_KEY=your-api-key-here
```

### 4. Run a project

Each project lives in its own folder. Open the corresponding Jupyter Notebook or Python script:

```bash
# Example — launch the Gradio chat UI
cd gradio_chat_ui
jupyter notebook
```


## 📚 Learning Goals

This repository is built as a practical playground for:

- Understanding how to craft effective **system prompts** for different roles
- Managing **multi-turn conversations** with message history
- Building **Gradio UIs** on top of LLM backends
- Combining **web scraping** with LLM generation for grounded outputs
- Exploring different **use-case patterns** (assistant, tutor, generator)
