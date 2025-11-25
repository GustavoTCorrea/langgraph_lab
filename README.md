# langgraph-lab
A personal lab for experimenting with LangChain, LangGraph, and LangSmith.

This repository includes the folders lca-langchainV1-essentials and lca-langgraph-essentials, which come from the official LangChain Academy courses. You can obtain the originals directly from the Academy, but in this repo I've modified the code to use Google API Keys instead of OpenAI keys.
The goal is to provide a free and accessible setup for learning and testing the ecosystem.

Using Google AI Studio, you can generate API keys here: https://aistudio.google.com/api-keys

##### Based on my testing:
- gemini-2.5-flash-lite is the most practical model for unrestricted free usage (high request limits), but its performance is noticeably weaker and requires more robust prompting to achieve good results.
- gemini-2.5-flash provides significantly better outputs, but the free request limits are much more restrictive.

##### Recommended Learning Path
If you're starting with the LangChain ecosystem, I highly recommend completing the Academy courses in the following order:
- LangSmith Essentials: introduces monitoring and observability, which are extremely valuable when debugging LangChain and LangGraph workflows later.
- LangChain Essentials: covers the core building blocks and is a simpler agent modeling system than LangGraph.
- LangGraph Essentials: builds on LangChain concepts and introduces graph-based agent design.

This order ensures that each course builds on the previous one in a natural way.

##### Course Links
- LangSmith Essentials: https://academy.langchain.com/courses/quickstart-langsmith-essentials
- LangChain Essentials: https://academy.langchain.com/courses/langchain-essentials-python
- LangGraph Essentials: https://academy.langchain.com/courses/langgraph-essentials-python
