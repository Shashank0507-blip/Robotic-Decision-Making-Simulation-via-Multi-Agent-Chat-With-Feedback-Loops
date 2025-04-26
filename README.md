## **Project Overview:**
This project demonstrates a multi-agent collaboration system powered by Large Language Models (LLMs) through the Groq API.
It simulates how autonomous agents — including a Perception Agent, Planning Agent, Execution Agent, Decision-Making Agent, and Summarization Agent — can communicate, make decisions, refine actions based on feedback, and summarize the entire task flow.
The system showcases real-world inspired AI communication pipelines where agents operate with memory, feedback loops, and decision-making, enabling more intelligent, dynamic behavior.

## **Key Features:**
* **Multi-Agent System:**
  Five independent AI agents collaborate through structured message passing.
* **Memory Simulation:**
  A lightweight history mechanism stores and tracks interactions between agents for analysis and debugging.
* **Dynamic Feedback Loop:**
  Agents adapt their plans based on feedback provided by other agents, simulating realistic AI behavior.
* **Summarization:**
  After each task, a summarizer agent generates a debrief summarizing the mission's flow and outcomes.
* **Groq API Integration:**
  Fast and efficient LLM responses using Groq's ultra-low-latency Llama-3.3-70B models.
* Robust Error Handling:
  Try-except blocks ensure the system remains operational even if an API call fails or times out.
