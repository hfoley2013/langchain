# 🦜️🔗 LangChain

⚡ Building applications with LLMs through composability ⚡

## Quick Install

* Fork or clone this repository to your local machine
* Run `pip install -r requirements.txt`
* You will also need to create an account on [Pinecone](https://docs.pinecone.io/docs/overview) in order to upload the content to a vector database for embedding
* Additionally, this model uses [OpenAIs](https://openai.com/) LLMs, so you will also need to get an API key from your account there

## 🤔 What is this?

Large language models (LLMs) are emerging as a transformative technology, enabling developers to build applications that they previously could not. However, using these LLMs in isolation is often insufficient for creating a truly powerful app - the real power comes when you can combine them with other sources of computation or knowledge.

This is a simple project to put together a functioning Generative AI Chatbot that is conversant about specific data feed to it. In this case, the data set I provide 22 books about AI/ML development in PDF form to be upload to the [Pinecone](https://docs.pinecone.io/docs/overview) vector database.

**❓ Question Answering over specific documents**

- [LangChain Question Answering Documentation](https://langchain.readthedocs.io/en/latest/use_cases/question_answering.html)

**💬 Chatbots**

- [LangChain Chatbot Documentation](https://langchain.readthedocs.io/en/latest/use_cases/chatbots.html)

**🤖 Agents**

- [LangChain Agent Documentation](https://langchain.readthedocs.io/en/latest/modules/agents.html)

## 📖 Documentation

Please see [here](https://langchain.readthedocs.io/en/latest/?) for full LangChain documentation on:

- Getting started (installation, setting up the environment, simple examples)
- How-To examples (demos, integrations, helper functions)
- Reference (full API docs)
- Resources (high-level explanation of core concepts)

## 🚀 What can this help with?

There are six main areas that LangChain is designed to help with.
These are, in increasing order of complexity:

**📃 LLMs and Prompts:**

This includes prompt management, prompt optimization, a generic interface for all LLMs, and common utilities for working with LLMs.

**🔗 Chains:**

Chains go beyond a single LLM call and involve sequences of calls (whether to an LLM or a different utility). LangChain provides a standard interface for chains, lots of integrations with other tools, and end-to-end chains for common applications.

**📚 Data Augmented Generation:**

Data Augmented Generation involves specific types of chains that first interact with an external data source to fetch data for use in the generation step. Examples include summarization of long pieces of text and question/answering over specific data sources.

**🤖 Agents:**

Agents involve an LLM making decisions about which Actions to take, taking that Action, seeing an Observation, and repeating that until done. LangChain provides a standard interface for agents, a selection of agents to choose from, and examples of end-to-end agents.

**🧠 Memory:**

Memory refers to persisting state between calls of a chain/agent. LangChain provides a standard interface for memory, a collection of memory implementations, and examples of chains/agents that use memory.
