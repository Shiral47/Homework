# Creative Ideas

A beginner-friendly Google Colab notebook that asks OpenAI for one unusual, creative, and practical use for an everyday object.

## Repository structure

- `creative_ideas.ipynb` — the interactive notebook.
- `README.md` — project overview and instructions.

## Open and run in Google Colab

1. Clone the repository with `git clone https://github.com/Shiral47/Homework.git`, or open the notebook directly from GitHub using Colab's **File → Open notebook → GitHub** option.
2. In Colab, select the `Shiral47/Homework` repository and open `creative_ideas.ipynb`. You can also use [this Colab link](https://colab.research.google.com/github/Shiral47/Homework/blob/main/creative_ideas.ipynb) after the repository is published.
3. Run the notebook cells from top to bottom. The notebook installs the OpenAI SDK if it is missing, securely prompts for your API key, and asks for an everyday object.

## API key security

An OpenAI API key is required at runtime. Enter it only at the hidden `getpass` prompt in Colab. Never hardcode the key in a cell, save it in notebook output, or commit it to Git or GitHub. If a key is accidentally exposed, revoke it and create a new one.
