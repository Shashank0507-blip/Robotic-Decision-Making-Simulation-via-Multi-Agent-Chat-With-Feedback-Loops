* **Initialization:**
  * All agents are initialized with Groq API configurations.
* **Task Kickoff:**
  * The PerceptionAgent sends an environmental observation to the PlannerAgent.
  * The PlannerAgent generates a plan and sends it to the ExecutorAgent.
* **Execution and Feedback:**
  * The ExecutorAgent processes the plan and sends execution results to the DecisionAgent.
  * The DecisionAgent provides feedback to the PlannerAgent, prompting possible plan improvements.
* **Re-Planning and Summarization:**
  * The Planner refines the plan if needed.
  * Finally, the Summariser agent produces a mission debrief covering the entire flow.
* **Memory Tracking:**
  * Throughout the task, all agent-to-agent communications are logged in the history dictionary.
