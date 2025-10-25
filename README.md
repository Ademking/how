# How CLI

**How CLI** is a terminal-based assistant that generates precise shell commands for any task you ask. Powered by Google Gemini’s generative AI, it provides context-aware, executable shell commands tailored to your current environment.

---

## Features

- Generate **exact shell commands** based on your current working directory, OS, and available tools.
- Context-aware: considers **files, git repositories, shell type**, and installed tools.
- **Command history** logging for easy reference.
- Clipboard support: copies generated commands automatically.
- Typewriter effect for visually appealing output (optional).
- Configurable Google Gemini API key.
- Handles API errors, content blocks, and timeouts gracefully.

---

## Installation

Using pip:

```bash
pip install how-cli-assist
```

## Quick Start

Open your terminal and try:

```bash
# Examples:
how to create a Python virtual environment
> python -m venv env

how to list all files modified in the last 7 days
> find . -type f -mtime -7

# Show your previous questions and commands
how --history

# Set or update your Google Gemini API key
how --api-key YOUR_GEMINI_API_KEY_HERE
```

## Options

`--silent` : Suppress spinner and typewriter effect.

`--type` : Show output with typewriter effect.

`--history` : Display previous questions and generated commands.

`--help` : Show help message and exit.

`--api-key <API_KEY>` : Set or replace your Google Gemini API key.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
