# Multi Agent Samples

Here are some of the multi-agent samples I've created using Crew AI as the agentic framework and Anthropic (Haiku) as the LLM.

* **[qa-ba-agents.ipynb](qa-ba-agents.ipynb)**
  * Given a functional business requirement, create agile user stories and system tests
  * Creates a crew with 3 agents 
  * _Business Analyst Agent_ - Takes in a functional requirement and creates a set of agile user stories
  * _System Tester Agent_ - Takes in a set of agile user stories and creates system test cases
  * _System Test Reviewer Agent_ - Reviews the output from System Tester and improves its quality