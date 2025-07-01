<!-- filepath: c:\Agentic_AI\Agentic_AI_Practical\langgraph\README.md -->

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue?logo=python" alt="Python Version">
  <img src="https://img.shields.io/badge/OpenAI-API-green?logo=openai" alt="OpenAI API">
</p>

<h1 align="center">🧠 Simple ReAct Agent from Scratch</h1>

<p align="center">
  <em>Build a reasoning and acting agent using Python and OpenAI, step by step in a Jupyter Notebook.</em>
</p>

---

## 📚 Table of Contents
- [Features](#-features)
- [Repository Structure](#-repository-structure)
- [Getting Started](#-getting-started)
- [Usage Example](#-usage-example)
- [Notebook Overview](#-notebook-overview)
- [Contributing](#-contributing)
- [License](#-license)

---

## ✨ Features
- Step-by-step construction of a ReAct agent
- Integration with OpenAI's GPT models
- Custom actions (e.g., calculations, dog breed weight lookup)
- Interactive agent loop for reasoning and acting
- Fully documented and annotated Jupyter Notebook

---

## 🗂 Repository Structure
```text
langgraph/
    Agent_Creation.ipynb  # Main notebook with all code and explanations
    README.md             # Project documentation
```

---

## 🚀 Getting Started
### Prerequisites
- Python 3.8 or higher
- Jupyter Notebook or VS Code with Jupyter extension
- OpenAI Python SDK
- `python-dotenv` for environment variable management

### Installation
1. **Clone this repository:**
   ```powershell
   git clone <your-repo-url>
   cd langgraph
   ```
2. **Install dependencies:**
   ```powershell
   pip install openai python-dotenv httpx
   ```
3. **Set your OpenAI API key:**
   Create a `.env` file in the project root:
   ```env
   OPENAI_API_KEY=your-api-key-here
   ```

---

## 🛠 Usage Example
Open `Agent_Creation.ipynb` in Jupyter or VS Code and run the cells step by step. The notebook demonstrates:
- Creating an agent
- Defining custom actions
- Running the agent in a reasoning-action loop
- Example queries (e.g., calculating values, looking up dog weights)

---

## 📒 Notebook Overview
- **Agent Construction:** Build a simple agent class that interacts with OpenAI's API.
- **Prompt Engineering:** Use a prompt template for the agent's reasoning and acting loop.
- **Custom Actions:** Functions for calculations and dog breed weight lookup.
- **Interactive Loop:** See how the agent processes user queries, performs actions, and returns answers.

---

## 🤝 Contributing
Contributions are welcome! Please open issues or submit pull requests for improvements or new features.

---

## 📝 License
This project is licensed under the MIT License.
