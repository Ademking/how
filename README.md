<p align="center">
  <img src="./screenshot.png" alt="How-CLI" />
</p>
 <h1 align="center">How-CLI</h1>
    <p align="center">A Terminal-Based Assistant for Generating Shell Commands</p>

**How-CLI** is a terminal-based assistant that generates precise shell commands for any task you ask. Powered by Google Gemini’s generative AI, it provides context-aware, executable shell commands tailored to your current environment.

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

### ⚠️ Disclaimer:

```
Yeah, I know... It’s a Gemini wrapper.
I know it's not the next Warp AI terminal or some fancy LLM-based shell integration with auto-completion and context persistence...
I know it's “yet another CLI tool” 
and yes, I'm painfully aware that wrapping an API and printing stuff in the terminal isn't groundbreaking computer science...
But here's the thing: I made How-CLI because it was fun and quick to build...
It's not meant to change the world. It’s meant to make typing "how to do X in bash" a little more amusing..
Think of it as a weekend hack.
```

## Installation

```bash
pip install how-cli-assist
```

## Demo

https://github.com/user-attachments/assets/25638fe5-766e-4318-928a-c3a4b7eccab0

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
