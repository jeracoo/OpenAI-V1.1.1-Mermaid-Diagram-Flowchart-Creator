# OpenAI-V1.1.1-Mermaid-Diagram-Flowchart-Creator

# Interactive Flowchart Generator

This Python script provides an interactive way to generate flowchart diagrams using the OpenAI API and render them with Mermaid syntax in a Markdown cell, which is particularly useful within IPython environments such as Jupyter notebooks.

## Features

- Interactive prompts to get user input for creating a flowchart diagram.
- A tick-box styled list for selecting the type of flowchart.
- Generation of Mermaid code based on user descriptions.
- Rendering of the flowchart diagram within the IPython display.

## Prerequisites

To run this script, you'll need:

- Python 3.x installed on your machine.
- An OpenAI API key with access to GPT-3 models.
- An environment that supports IPython display functions (e.g., Jupyter Notebook or JupyterLab).

## Installation

To get started with this script, follow these steps:

1. Clone this repository or download the script directly.
2. Install the required dependencies by running `pip install openai IPython` in your command line.
3. Ensure you have set up your OpenAI API key in your environment variables. For security reasons, it's not recommended to hardcode your API keys in your scripts.

## Usage

Run the script in an IPython-enabled environment like Jupyter Notebook:

1. Execute the entire script or run it cell by cell following the inline comments.
2. Follow the interactive prompts in the output cells to input the required information for your flowchart.
3. Choose the type of flowchart you want to generate by typing the corresponding number when prompted.
4. View the generated flowchart diagram rendered by Mermaid within the Markdown cell.

## Security Note

This README includes an exposed API key, which is a significant security risk. You should never expose your private API keys in publicly accessible code. The included key in the script is for example purposes only and should be replaced with an environment variable or a secure storage solution.

## Contributing

Contributions to improve this script are welcome. Please feel free to fork the repository, make changes, and submit a pull request with your improvements.

## License

This project is open-sourced and is available under the MIT License.

Enjoy creating flowcharts with ease!
