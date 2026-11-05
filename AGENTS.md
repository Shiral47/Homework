# Repository Guidelines

## Project Scope

This project contains Python code intended to run in Google Colab notebooks. Keep contributions focused on Colab-ready Python, notebook workflows, and supporting explanations. Do not add unrelated applications or non-Python implementations.

## Project Structure

- `dana_bakery_orders.ipynb` contains the bakery order workflow.
- `creative_ideas.ipynb` contains an OpenAI-powered creative idea example.
- `README.md` explains the project and how to open its notebooks in Colab.

Organize future notebooks by task and use descriptive filenames such as `analyze_sales.ipynb`. Keep example data small or link to its source rather than committing large datasets.

## Development and Execution

There is no local build system or test command configured. Open notebooks in Google Colab and run cells from top to bottom in a fresh runtime. Note any required packages, settings, input files, and secrets in notebook Markdown. Avoid machine-specific paths.

## Python Style

Use readable, idiomatic Python with four-space indentation, descriptive `snake_case` names, and focused functions. Keep notebooks linear and add short Markdown explanations where they clarify inputs, outputs, or decisions. Avoid unnecessary package installation steps.

## Testing and Review

There is no configured test framework or coverage requirement. Validate notebook changes in Colab and describe the validation in the pull request. Pull requests should explain the change and expected result; include screenshots when notebook output or visualization is central to the change.

## Security and Data

Never include credentials, tokens, or personal data in notebooks or committed files. Read secrets from Colab's Secrets feature or request them securely at runtime. State data requirements and provenance, and avoid committing large or sensitive datasets.
