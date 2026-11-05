# Dana's Bakery Order Desk

Beginner-friendly Google Colab notebooks for Python projects. The bakery order notebook helps Dana's Bakery in Nachlaot process orders using current menu prices, daily inventory, customer-approved replacement suggestions, delivery rules, discounts, and a step-by-step diary for each order.

## Repository structure

- dana_bakery_orders.ipynb — interactive bakery order processing system.
- creative_ideas.ipynb — generates a creative use for an everyday object with the OpenAI API.
- README.md — project overview and Colab instructions.
- AGENTS.md — contributor guidance.

## Open and run in Google Colab

1. Open the repository in Colab with File → Open notebook → GitHub, or open a notebook link directly:
   - [Dana's Bakery Order Desk](https://colab.research.google.com/github/Shiral47/Homework/blob/main/dana_bakery_orders.ipynb)
   - [Creative Ideas](https://colab.research.google.com/github/Shiral47/Homework/blob/main/creative_ideas.ipynb)
2. Run cells from top to bottom. In the bakery notebook, enter a product, quantity, weekday, and city when prompted. If the requested item is out of stock, the notebook asks before replacing it. Leave city blank for shop pickup. Rerun the order-entry cell for each new order; inventory persists during the runtime and resets when it restarts.
3. The Creative Ideas notebook requires an OpenAI API key at runtime. Enter it only at the hidden getpass prompt. Never hardcode a key, save it in notebook output, or commit it to Git or GitHub.
