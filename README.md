<!-- filepath: /c:/Agentic_AI/README.md -->

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue?logo=python" alt="Python Version">
  <img src="https://img.shields.io/badge/OpenAI-API-green?logo=openai" alt="OpenAI API">
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter" alt="Jupyter Notebooks">
</p>

<h1 align="center">🤖 Agentic AI Practical Knowledge Repository</h1>

<p align="center">
  <em>The go-to resource for hands-on, modern agentic AI development.<br/>
  Learn, build, and extend state-of-the-art AI agents with real-world tools and examples.</em>
</p>

---

## 📚 Table of Contents
- [Project Overview](#project-overview)
- [Repository Structure](#repository-structure)
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

---

## 🧠 Project Overview
Agentic_AI is a comprehensive, hands-on repository for learning and building modern agentic AI systems. Through a series of well-documented Jupyter notebooks, you will:
- Construct reasoning and acting agents from scratch (ReAct pattern)
- Explore advanced agent architectures with LangGraph
- Integrate real-world search and web scraping tools
- Gain practical skills for research, prototyping, and production

**Who is this for?**
- Students, researchers, and developers interested in agentic AI, LLMs, and practical automation.

---

## 🗂 Repository Structure
```text
Agentic_AI/
│
├── Agentic_search_tools.ipynb         # Practical agentic search and web scraping tools
├── Langgraph_components.ipynb         # Deep dive into LangGraph agent components
└── Agentic_AI_Practical/
    └── langgraph/
        ├── Agent_Creation.ipynb       # Step-by-step ReAct agent from scratch
        └── README.md                  # Langgraph module documentation
```

---

## ✨ Features
- **Step-by-step agent construction:** Build ReAct and LangGraph agents from the ground up.
- **Real-world integrations:** Use OpenAI, Tavily, DuckDuckGo, and web scraping in your agents.
- **Modular, extensible code:** Designed for learning, research, and rapid prototyping.
- **Fully annotated notebooks:** Every step explained, with code, comments, and outputs.
- **Modern best practices:** Environment management, error handling, and extensibility.

---

## 🚀 Getting Started
### Prerequisites
- Python 3.8 or higher
- Jupyter Notebook or VS Code with Jupyter extension
- API keys for OpenAI and Tavily (for full functionality)

### Installation
1. **Clone this repository:**
   ```sh
   git clone <your-repo-url>
   cd Agentic_AI
   ```
2. **Install dependencies:**
   ```sh
   pip install openai python-dotenv httpx tavily duckduckgo-search beautifulsoup4 pygments
   ```
3. **Set your API keys:**
   Create a `.env` file in the project root:
   ```env
   OPENAI_API_KEY=your-openai-key
   TAVILY_API_KEY=your-tavily-key
   ```

---

## 🛠 Usage
- Open any notebook in Jupyter or VS Code and run the cells step by step.
- **Recommended learning path:**
  1. `Agentic_AI_Practical/langgraph/Agent_Creation.ipynb` – Build a ReAct agent from scratch
  2. `Langgraph_components.ipynb` – Explore LangGraph agent components and advanced flows
  3. `Agentic_search_tools.ipynb` – Learn agentic search and web scraping techniques
- Each notebook is self-contained and fully annotated for independent study.

---

## 🤝 Contributing
Contributions are welcome! Please open issues or submit pull requests for improvements, new features, or additional notebooks. For major changes, please open an issue first to discuss your ideas.

---

## 📝 License
This project is licensed under the MIT License.

---

<p align="center">
  <em>Empowering the next generation of agentic AI developers and researchers.</em>
</p> 