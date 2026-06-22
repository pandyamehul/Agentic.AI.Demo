# Agentic AI Engineering Overview

Documenting exploration and journey in the Agentic AI Engineering masterclass on Udemy. This course covers the fundamentals of building intelligent agents, including concepts like memory, tool use, and decision-making. The notes will include code snippets, explanations, and insights gained from the course.

## Simple Agent implementation

The course starts with a simple agent implementation that can perform basic tasks. The agent is designed to analyze companies, industries, and competitors, and then write a report summarizing the findings.

The agent can use tools to gather information and has memory to remember previous interactions and information it has gathered. For memory management, the agent uses a SQLite database to store and retrieve information across sessions.

The agent is enhanced with the ability to use tools, such as a web search tool to gather real-time information (via the tavily_search tool) and a OpenAI code interpreter tool to perform calculations and simulations (via the code_interpreter tool). This allows the agent to provide more comprehensive and accurate responses to user queries.
