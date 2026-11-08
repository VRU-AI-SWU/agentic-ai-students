# Agentic AI (Thai course) — Lab notebooks for learners

🇹🇭 [อ่านเป็นภาษาไทย](README.md)

Notebooks for the YouTube series *Agentic AI ภาษาไทย* (narrated in Thai, with English subtitles), based on the textbook *The Hitchhiker's Guide to Agentic AI* (Haggai Roitman, CC BY-SA 4.0). Every lab has an English notebook; the links below open them.

📖 **Read the lessons online:** https://vru-ai-swu.github.io/agentic-ai-students/en/

Each lab has two files:

- **✏️ Starter** (`.en.student.ipynb`) — most of the code is ready; watch the video and fill in only the `✏️ TODO`s. Each TODO gives the time in the video where that code is explained.
- **✅ Solution** (`.en.ipynb`) — the same code as in the video, ready to run; compare when you get stuck.

## Getting started

1. Click **Open in Colab** for the lab you want (or download the `.ipynb` and open it in Jupyter)
2. Get an API key at [openrouter.ai](https://openrouter.ai) → Keys → Create Key
3. **Colab:** 🔑 Secrets icon → add `OPENROUTER_API_KEY` → turn on *Notebook access*  
   **Your own machine:** create a `.env` file next to the notebook containing `OPENROUTER_API_KEY=sk-or-...`
4. Run every cell from top to bottom

⚠️ Never put the key in the code itself, and never commit your `.env` file.

## EP04 Workflow Patterns (§19.1)

| Lab | ✏️ Starter | ✅ Solution |
|---|---|---|
| Lab 1 — Prompt Chaining | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VRU-AI-SWU/agentic-ai-students/blob/main/ep04-workflow-patterns/19-1-lab1-chaining.en.student.ipynb) · [file](ep04-workflow-patterns/19-1-lab1-chaining.en.student.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VRU-AI-SWU/agentic-ai-students/blob/main/ep04-workflow-patterns/19-1-lab1-chaining.en.ipynb) · [file](ep04-workflow-patterns/19-1-lab1-chaining.en.ipynb) |
| Lab 2 — Routing | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VRU-AI-SWU/agentic-ai-students/blob/main/ep04-workflow-patterns/19-1-lab2-routing.en.student.ipynb) · [file](ep04-workflow-patterns/19-1-lab2-routing.en.student.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VRU-AI-SWU/agentic-ai-students/blob/main/ep04-workflow-patterns/19-1-lab2-routing.en.ipynb) · [file](ep04-workflow-patterns/19-1-lab2-routing.en.ipynb) |
| Lab 3 — Parallelization | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VRU-AI-SWU/agentic-ai-students/blob/main/ep04-workflow-patterns/19-1-lab3-parallel.en.student.ipynb) · [file](ep04-workflow-patterns/19-1-lab3-parallel.en.student.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VRU-AI-SWU/agentic-ai-students/blob/main/ep04-workflow-patterns/19-1-lab3-parallel.en.ipynb) · [file](ep04-workflow-patterns/19-1-lab3-parallel.en.ipynb) |
| Lab 4 — Orchestrator-Workers | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VRU-AI-SWU/agentic-ai-students/blob/main/ep04-workflow-patterns/19-1-lab4-orchestrator.en.student.ipynb) · [file](ep04-workflow-patterns/19-1-lab4-orchestrator.en.student.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VRU-AI-SWU/agentic-ai-students/blob/main/ep04-workflow-patterns/19-1-lab4-orchestrator.en.ipynb) · [file](ep04-workflow-patterns/19-1-lab4-orchestrator.en.ipynb) |
| Lab 5 — Evaluator-Optimizer | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VRU-AI-SWU/agentic-ai-students/blob/main/ep04-workflow-patterns/19-1-lab5-evaluator.en.student.ipynb) · [file](ep04-workflow-patterns/19-1-lab5-evaluator.en.student.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VRU-AI-SWU/agentic-ai-students/blob/main/ep04-workflow-patterns/19-1-lab5-evaluator.en.ipynb) · [file](ep04-workflow-patterns/19-1-lab5-evaluator.en.ipynb) |

## EP05 Autonomous Agent Patterns (§19.2)

| Lab | ✏️ Starter | ✅ Solution |
|---|---|---|
| Lab 1 — ReAct Loop | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VRU-AI-SWU/agentic-ai-students/blob/main/ep05-autonomous-agents/ep05-lab1-react.en.student.ipynb) · [file](ep05-autonomous-agents/ep05-lab1-react.en.student.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VRU-AI-SWU/agentic-ai-students/blob/main/ep05-autonomous-agents/ep05-lab1-react.en.ipynb) · [file](ep05-autonomous-agents/ep05-lab1-react.en.ipynb) |
| Lab 2 — Planning Agent | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VRU-AI-SWU/agentic-ai-students/blob/main/ep05-autonomous-agents/ep05-lab2-planning.en.student.ipynb) · [file](ep05-autonomous-agents/ep05-lab2-planning.en.student.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VRU-AI-SWU/agentic-ai-students/blob/main/ep05-autonomous-agents/ep05-lab2-planning.en.ipynb) · [file](ep05-autonomous-agents/ep05-lab2-planning.en.ipynb) |
| Lab 3 — Reflexion | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VRU-AI-SWU/agentic-ai-students/blob/main/ep05-autonomous-agents/ep05-lab3-reflexion.en.student.ipynb) · [file](ep05-autonomous-agents/ep05-lab3-reflexion.en.student.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VRU-AI-SWU/agentic-ai-students/blob/main/ep05-autonomous-agents/ep05-lab3-reflexion.en.ipynb) · [file](ep05-autonomous-agents/ep05-lab3-reflexion.en.ipynb) |
| Lab 4 — Tool-Use Patterns | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VRU-AI-SWU/agentic-ai-students/blob/main/ep05-autonomous-agents/ep05-lab4-tool-use.en.student.ipynb) · [file](ep05-autonomous-agents/ep05-lab4-tool-use.en.student.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VRU-AI-SWU/agentic-ai-students/blob/main/ep05-autonomous-agents/ep05-lab4-tool-use.en.ipynb) · [file](ep05-autonomous-agents/ep05-lab4-tool-use.en.ipynb) |
| Lab 5 — From scratch to LangGraph | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VRU-AI-SWU/agentic-ai-students/blob/main/ep05-autonomous-agents/ep05-lab5-langgraph.en.student.ipynb) · [file](ep05-autonomous-agents/ep05-lab5-langgraph.en.student.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VRU-AI-SWU/agentic-ai-students/blob/main/ep05-autonomous-agents/ep05-lab5-langgraph.en.ipynb) · [file](ep05-autonomous-agents/ep05-lab5-langgraph.en.ipynb) |

## License

All notebooks are adapted from Haggai Roitman, *The Hitchhiker's Guide to Agentic AI: From Foundations to Systems* ([arXiv:2606.24937](https://arxiv.org/abs/2606.24937)) and released under [CC BY-SA 4.0](LICENSE). The data in the tools is simulated for teaching.
