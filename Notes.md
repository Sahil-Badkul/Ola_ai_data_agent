**Agentic AI** represents a shift from individual AI models to a network or **system of multiple AI agents** that communicate and collaborate to solve complex domains.

Instead of just a single program, an agentic solution functions by autonomously dividing work among specialized sub-agents, which allows for better governance and the ability to handle diverse tasks, such as SQL analysis and ETL operations.

Key characteristics of agentic AI include:
* **Stateful Execution:** The agents maintain context and state throughout the workflow, allowing them to perform steps in a specific, reliable sequence.
* **ReAct Architecture (Reasoning + Acting):** Agents use a reasoning loop to decide which tools to call, receive feedback, and continue acting until the task is complete.
* **Specialized Sub-agents:** By breaking down large problems, a parent agent (or team lead) can assign tasks to expert sub-agents, such as a SQL analyst or an ETL analyst, ensuring more effective execution.


pip install uv
uv init
uv sync
uv add langchain
uv add langgraph
uv add langchain-openai
uv add langchain-anthropic
uv add pydantic-ai
uv add pydantic
uv add dotenv
uv add psycopg2-binary



Langchain & Langgraph are frameworks.