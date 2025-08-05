# Single LLM-based Agent Helping Learn and Review English Language

- We all know that making sentences is essential for learning and reviewing English content, so this agent facilitates these cases successfully using a ReAct agent created by Lanchain and Langraph.
- To create a ReAct agent, we need a tool to retrieve sentences for each word from <a href="https://sentencedict.com">sentencedict.com</a> by fully mimicking browser behavior, then a graph to put all nodes and edges together in our desired way.
- If the tool returns `No sentences found` for a word, the agent must generate 10 new sentences for that word only
