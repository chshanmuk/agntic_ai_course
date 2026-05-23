# agntic_ai_course
This repo includes the agentic ai course from krish Naik which covers langchain, langgraph, RAG, vectorless Rag, MCP's, EVAL, Deep agents and LLM Gateways

Where normal gen ai usage includes calling an LLM with normal question and it used to answert it based on its trainied data

But when the requirement is something like a real time temparature, the LLM cannot able to answer it correctly as it doesn't have the real time data, so in this case we have to use an External website which have that to connect to it and its called as tools and we request someinfo from it and get that out of that tool!

and to retrive the same we use architecture called **REACT** (Reasoning and Acting). Architecture!

In Langchain, we can use the Langchain Expression Language (LCEL) to create an Agent.

In an Agent we have several components. we have to pass the inputs to the agent and it will process the inputs based on the instructions and give the output.



## Middleware

- it will help with checking all the preliminary checks for the request and for the response!

For a Input:
- Checking if the input is safe for the model
- Limiting the input to certain length

For a Output:
- Checking if the output is safe for the user
- Limiting the output to certain length

Built-in Middleware


1. Summarization ---> Agent
2. Human in the feedback
3. Model Call limit
