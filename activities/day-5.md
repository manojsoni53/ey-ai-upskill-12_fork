---------------------------------------------------
11:35 - 11:55 Break + 5
1:40 - 2:30 Lunch Break
4:30 - 4:45 Break
---------------------------------------------------

Project Assignments:

Phase 3: [60]

Ref: 32-agentic-capstone-assignments\Assignment_Extending_Agentic_Cyber_Security_Assistant_v2.1.md
There are 3 tools
Add them into the notebook: 30-agentic-capstone\agentic-capstone-part-2.ipynb
Independetly test it
 - tool_name.invoke(message)

Create an agent with 5 tools:

tools = ["ask_cis", "lookup_cve", "lookup_cisa_kev", "lookup_attack", "lookup_epss"]
cyber_agent = create_agent(llm, tools=tools, system_prompt="write_your_prompt")

NOTE: This is not a multi-agent system

Test the agent with the following messages:
Ref: Part 4 -> 32-agentic-capstone-assignments\Assignment_Extending_Agentic_Cyber_Security_Assistant_v2.1.md
Test all the 10 queries

Deliverable:
Text file containing the results of the 10 queries

