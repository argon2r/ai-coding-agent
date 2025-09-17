# ai-coding-agent

An experimental AI-powered coding assistant built with Python.  
The agent leverages the Gemini API and a set of tools to read, write, run, and fix code automatically.

---

## 🚀 Features

- 🔄 **Feedback Loop** — The agent iteratively uses tools until it reaches a final answer.
- 🛠️ **Tool Support** — Includes:
  - `get_files_info` → list files in a directory
  - `get_file_content` → read code files
  - `write_file` → modify or create files
  - `run_python_file` → execute Python scripts
- 🤖 **Self-Correcting** — Can debug and fix Python code (e.g., operator precedence bugs).
- 💬 **CLI Interface** — Interact naturally with the agent from the terminal.

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/ai-coding-agent.git
cd ai-coding-agent
