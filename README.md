# 🎉 Party Planner Agent

An AI-powered party planning assistant that helps users prepare and organize events using **SmolAgents, Gemini 2.5 Flash, DuckDuckGo Search, and Gradio**.

The agent can research party-related information, generate personalized recommendations, and help users make practical decisions for their event.

## 🚀 Live Demo

👉 **[Try Party Planner Agent on Hugging Face](https://huggingface.co/spaces/bikrantchaurasiya/party-planner-agent)**

## ✨ Features

* 🎵 **Music Search** — Search for music and party playlist ideas.
* 🍽️ **Menu Suggestions** — Get personalized food and menu recommendations.
* 👔 **Dress Code Suggestions** — Generate dress-code ideas based on the party type and theme.
* 🍽️ **Catering Search** — Find suitable catering services using web search.
* ⏱️ **Preparation Time Calculator** — Estimate the time required to prepare for the party.
* 🤖 **AI Agent** — Uses an AI agent to understand requests and use the appropriate tools.

## 🛠️ Tech Stack

* **Python 3.13**
* **SmolAgents** — AI agent framework
* **Gemini 2.5 Flash** — Large language model
* **DuckDuckGo Search** — Web search
* **Gradio** — User interface
* **Hugging Face Spaces** — Deployment

## 🏗️ How It Works

The Party Planner Agent uses an AI model together with specialized tools to help users plan their events.

```text
User
  │
  ▼
Gradio Interface
  │
  ▼
Party Planner AI Agent
  │
  ├── Gemini 2.5 Flash
  │
  ├── DuckDuckGo Search
  │
  └── Party Planning Tools
       ├── Music Search
       ├── Menu Suggestions
       ├── Dress Code
       ├── Catering Search
       └── Preparation Time
  │
  ▼
Personalized Party Plan
```

## 📁 Project Structure

```text
party-planner-agent/
│
├── app.py
├── requirements.txt
├── README.md
└── ...
```

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/BikrantChaurasiya/party-planner-agent.git
cd party-planner-agent
```

Install the dependencies:

```bash
pip install -r requirements.txt
```

## 🔑 Gemini API Key

This project requires a **Gemini API key**.

For local development, set your API key as an environment variable rather than hard-coding it into the source code.

For example:

```bash
GEMINI_API_KEY="your-api-key"
```

> ⚠️ **Never commit API keys, passwords, or other secrets to GitHub.**

When deployed on Hugging Face Spaces, configure the API key using the Space's **Secrets and Variables** settings.

## ▶️ Run Locally

Start the Gradio application:

```bash
python app.py
```

Then open the local Gradio URL shown in your terminal.

## 🌐 Deployment

The application is deployed on **Hugging Face Spaces** and can be accessed here:

**[Party Planner Agent — Live Demo](https://huggingface.co/spaces/bikrantchaurasiya/party-planner-agent)**

## 🎯 Project Purpose

This project demonstrates how **AI agents can combine large language models with external tools and web search** to solve practical, real-world planning tasks.

Instead of simply generating text, the agent can determine when it needs additional information and use available tools to provide more useful party-planning recommendations.

## 📌 Future Improvements

* 🎨 More party themes and planning templates
* 💰 Detailed budget breakdowns
* 👥 Guest management
* 📅 Automated event schedules
* 🎵 Improved playlist generation
* 📍 Location-aware venue recommendations
* 💬 More specialized party-planning tools

## 👨‍💻 Author

**Bikrant Chaurasiya**

## 📄 License

Add your preferred open-source license here.
