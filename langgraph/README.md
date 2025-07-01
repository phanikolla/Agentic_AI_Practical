<!-- filepath: c:/Agentic_AI/Agentic_AI_Practical/langgraph/README.md -->

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue?logo=python" alt="Python Version">
  <img src="https://img.shields.io/badge/OpenAI-API-green?logo=openai" alt="OpenAI API">
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter" alt="Jupyter Notebooks">
</p>

<h1 align="center">🧩 LangGraph & Agentic AI Practical Notebooks</h1>

<p align="center">
  <em>Hands-on, modular notebooks for building, analyzing, and extending agentic AI systems.<br/>
  Part of the <a href="../../README.md">Agentic_AI Practical Knowledge Repository</a>.</em>
</p>

---

## 📚 Table of Contents
- [Overview](#overview)
- [Notebook Summaries](#notebook-summaries)
- [Folder Structure](#folder-structure)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

---

## 🧠 Overview
This folder contains a suite of Jupyter notebooks for practical, hands-on learning in agentic AI. Each notebook is self-contained, fully annotated, and designed for both beginners and advanced users interested in:
- Building reasoning and acting agents (ReAct pattern)
- Exploring LangGraph agent architectures
- Integrating real-world search and web scraping tools

---

## 📒 Notebook Summaries
- **Agent_Creation.ipynb**  
  <em>Step-by-step construction of a ReAct agent from scratch, with custom actions and OpenAI integration.</em>
- **Langgraph_components.ipynb**  
  <em>Deep dive into LangGraph agent components, state management, and advanced agent flows.</em>
- **Agentic_search_tools.ipynb**  
  <em>Practical agentic search and web scraping using Tavily, DuckDuckGo, and BeautifulSoup.</em>

---

## 🗂 Folder Structure
```text
langgraph/
├── Agent_Creation.ipynb         # ReAct agent from scratch
├── Langgraph_components.ipynb   # LangGraph agent components
├── Agentic_search_tools.ipynb   # Agentic search & web scraping
└── README.md                    # This documentation
```

---

## 🚀 Getting Started
### Prerequisites
- Python 3.8 or higher
- Jupyter Notebook or VS Code with Jupyter extension
- API keys for OpenAI and Tavily (for full functionality)

### Installation
1. **Clone the main repository:**
   ```sh
   git clone <your-repo-url>
   cd Agentic_AI/Agentic_AI_Practical/langgraph
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
- Each notebook is self-contained and can be studied independently or as part of the full Agentic_AI curriculum.
- For a broader context and learning path, see the [main project README](../../README.md).

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
