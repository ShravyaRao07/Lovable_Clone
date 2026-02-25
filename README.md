# 🧠 Multi-Agent AI Project Builder

A multi-agent AI system that converts a single user prompt into a fully implemented project using structured planning, task decomposition, and autonomous code generation.

Built using **LangGraph + Groq LLM + Pydantic**.

---

## 🚀 How It Works

The system simulates an engineering team:

1. **Planner Agent**
   - Converts user prompt into a structured project plan.

2. **Architect Agent**
   - Breaks the plan into detailed implementation steps.

3. **Coder Agent**
   - Executes each step using file system tools.
   - Reads and writes files.
   - Loops until all tasks are complete.

Workflow:
![Flow](resources/flow.png)