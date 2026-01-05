# Reserach Agent
The repository contains code for a *research agent* that can answer an ambigous question by the user by figuring out smaller pieces. For each of the smaller pieces, it can answer using different tools that are connected to different sources.

The overall workflow for the agent would look something like below : 
1. **Interpret intent of the user question**: Recognise what the user wants
2. **Create a research plan**: Break the question into sub-questions 
3. **Select the tools via MCP**: Based on the sub-question it will try to find the best resource to use. 
4. **Iterate Autonmously**: Based on the answer the system generate, it will try to find missing pieces and find additional sources to answer.
5. **Finaly Answer**: Generate a human readable answer. 

Unlike a RAG, the agent selects the resource using a tool to answer the sub-questions.

## Tools 


## Motivation
The goal is to learn more about agentic workflow and understand how MCP servers works. 

## Package Management
The repository is built using `uv`. Some common commands for the package manager:

1. When changing the `pyproject.toml` directly - remove the `uv.lock` file and then run the following 
```
uv lock
uv sync
```

2. To run any command in the virtual env of the `fastmcp`
```
uv run <>
```
