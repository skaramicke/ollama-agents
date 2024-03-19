# Ollama Agents

## Introduction

This is a React app that uses an OpenAI/Ollama compatible API to run a multi agent simulation to solve some problem.

## Todo

1. Create an ollama agent runner that has a queue of inferences to run. Idea: The user could add multiple inference runners to the app and they could run in parallel, or define that a specific runner can handle some number of inferences in parallell.
2. Define some central "todo" list data structure for the agent network to process over time.
3. Create an agent factory agent that can create agents and write their system prompts with different strategies.
4. Find a system prompt for tool usage that works well with llama2 or most models.
5. Define a bunch fo tools:

- Google search
- Wikipedia search
- Youtube search (transcripts only?)

6. Get a method for thoughts working so the agents can reason about if they need tools or not.

## Contribution

Please feel free to contribute to this project. It is open source and open to new ideas. You can add to the todo list too if have any ideas.
