# Repository Guidelines

## Project Scope

This project is for generating Python code intended to run in Google Colab notebooks. Keep contributions focused on Colab-ready Python, including notebook cells, data analysis, machine learning, and supporting explanations needed to use the code. Do not add unrelated applications, services, or non-Python implementations.

## Project Structure

The repository currently contains only this guide. Add `.ipynb` notebooks for complete, interactive Colab workflows and `.py` files when reusable Python code is useful. Organize files by task or topic, use descriptive filenames such as `analyze_sales.ipynb`, and keep example data small or link to its source rather than committing large datasets.

## Development and Execution

There is no local build system or test command configured. Validate notebook code by running its cells in Google Colab, from top to bottom, with a fresh runtime. Make setup cells explicit: install only required packages, import dependencies, and explain any required Colab settings, Drive mounts, or uploaded files. Avoid machine-specific paths; use Colab-compatible paths and APIs.

## Python Style

Use readable, idiomatic Python with four-space indentation, descriptive `snake_case` names, and focused functions. Keep notebooks linear and easy to follow, with short Markdown explanations where they clarify inputs, outputs, or decisions. Pin package versions only when compatibility requires it; otherwise avoid unnecessary installation steps.

## Testing and Review

There is no configured test framework or coverage requirement. For code changes, run the relevant notebook cells in a fresh Colab runtime and check that outputs match the stated purpose. Pull requests should describe the task and expected result, note the Colab validation performed, and include screenshots only when notebook output or visualization is central to the change.

## Security and Data

Never include credentials, API keys, or personal data in notebooks or committed files. Read secrets from Colab's Secrets feature or request them securely at runtime. State data requirements and provenance, and avoid committing large or sensitive datasets.
