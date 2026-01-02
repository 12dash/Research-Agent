# Reserach Agent
The repository contains code for a *research agent* that can break a big question into smaller questions. It can then iterate over the smaller questions by using different sources and corresponding tools to answer the sub-question.

The overall workflow looks something like below : 
1. **Interpret intent of the user question**: Recognise what the user wants
2. **Create a research plan**: Break the question into sub-questions 
3. **Select the tools via MCP**: Based on the sub-question it will try to find the best resource to use. 
4. **Iterate Autonmously**: Based on the answer the system generate, it will try to find missing pieces and find additional sources to answer.
5. **Finaly Answer**: Generate a human readable answer. 

Unlike a RAG, the agent selects the resource using a tool to answer the sub-questions.

## Tools 


## Motivation
The goal is to learn more about an agentic workflow and understand how do MCP servers work. 