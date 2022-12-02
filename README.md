LangChain is a library for building applications with large language models (LLMs) through composability.

Key concepts:
- LLM: Large language models (e.g. GPT-3)
- Tools: APIs designed for assisting with a particular use case (search, databases, Python REPL, etc). Prompt templates, LLMs, and chains can also be considered tools.
- Chain: combination of multiple tools
- Agents: receive user input and determines which tools to use in which order
- Memory: A class that can be added to an Agent or Chain to (1) pull in memory variables before calling that chain/agent, and (2) create new memories after the chain/agent finishes.

Examples:
- [Simple](langchain_examples.ipynb) (using LLM, Chain, and an Agent that uses Tools)
- [Conversation](langchain_convo.ipynb)
- [Conversation with rolling summary](langchain_convo_summary.ipynb)
