# 🤖 Agent ADK Lab Collection

A hands-on playground of **Agent Development Kit (ADK)** examples — from the simplest agent to advanced multi-agent orchestration.  
This repo is structured as a progressive learning path: start with a **basic agent**, then build toward **stateful, parallel, and loop-driven agent systems**.

---

## 📂 Repository Structure

| #  | Example                    | Description |
|----|----------------------------|-------------|
| 1  | **basic_agent**            | Your very first agent: minimal setup and execution. |
| 2  | **tool_agent**             | Extend your agent with external tool integration. |
| 3  | **litellm_agent**          | Power your agent with LiteLLM as the model provider. |
| 4  | **structured_outputs**     | Ensure your agents produce reliable, typed outputs. |
| 5  | **sessions_and_memory**    | Add memory across agent interactions. |
| 6  | **persistent_storage**     | Store and retrieve agent state beyond a single session. |
| 8  | **stateful_multi_agent**   | Coordinate stateful collaboration between multiple agents. |
| 9  | **callbacks**              | Add hooks for monitoring and debugging agent actions. |
| 10 | **sequential_agent**       | Chain tasks in sequence across one or more agents. |
| 11 | **parallel_agent**         | Run multiple agents concurrently for faster workflows. |
| 12 | **loop_agent**             | Build feedback loops for iterative reasoning and execution. |

---

## 🚀 Getting Started

### 1. Clone the Repo
git clone https://github.com/SumanthMeenan/Google_Agents_Development_Kit_Tutorials.git
cd Google_Agents_Development_Kit_Tutorials

### 2. Set Up Environment
python3 -m venv .venv
source .venv/bin/activate   # On Windows: .venv\Scripts\activate
pip install -r requirements.txt

### 3. Run an Example
python 1.basic_agent/main.py

