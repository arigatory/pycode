# pycode

LangChain is a Python project that harnesses the power of OpenAI's language models to streamline code and test generation. With LangChain, you can effortlessly define tasks and programming languages, receiving concise code snippets and corresponding tests.

## Features

- **Task-Driven:** Specify tasks and target languages to generate code and tests seamlessly.
- **OpenAI Integration:** Leverage OpenAI's language models for high-quality code generation.
- **Versatile Framework:** A flexible and extensible framework for creating chains of language model interactions.

## Usage

1. Install dependencies: `pip install -r requirements.txt`
2. Set up your environment variables: `cp .env.example .env` and configure as needed.
3. Run the script: `python main.py --task "Print a nice Christmas Tree" --language "python"`

## Example Output

```python
>>>>>> GENERATED CODE:
# Your generated code here

>>>>>> GENERATED TEST:
# Corresponding test code here
