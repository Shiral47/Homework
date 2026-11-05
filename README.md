# Dana's Bakery Order Desk

A beginner-friendly Google Colab project for Dana's Bakery in Nachlaot. The bakery order pipeline uses LangGraph to run deterministic Python rules for inventory, customer-approved substitutions, delivery, discounts, and a step-by-step order diary. It does not use an LLM or require API keys.

## Repository structure

- dana_bakery_orders.ipynb — LangGraph order-processing workflow and graph visualization.
- creative_ideas.ipynb — separate OpenAI-powered creative idea example.
- README.md — project overview and Colab instructions.
- AGENTS.md — contributor guidance.

## Open and run in Google Colab

1. Open the repository in Colab with File → Open notebook → GitHub, or open [Dana's Bakery Order Desk](https://colab.research.google.com/github/Shiral47/Homework/blob/main/dana_bakery_orders.ipynb).
2. Run notebook cells from top to bottom. The notebook installs LangGraph if needed, builds the graph, and displays its Mermaid PNG layout.
3. The example graph.invoke call asks the customer to approve an in-stock substitution. To accept it, pass replacement_answers=['yes']; pass ['no'] to decline and review the next eligible offer. The graph records each processing stage in steps.
4. Inventory persists for accepted orders during the active Colab runtime and resets when the runtime restarts. No API key is needed for the bakery pipeline.

The separate Creative Ideas notebook uses the OpenAI API and requires a key at runtime. Keep its key out of notebook cells, outputs, commits, and GitHub.
