# Code-Craft-AI

## Project Description

Code-Craft-AI is an intelligent coding assistant designed to help developers with various coding tasks. It provides a chat interface for code generation, reviews, debugging, and explanations, along with file management capabilities for a simulated workspace.

## Features

- **AI-Powered Chat**: Interact with a coding assistant for code generation, reviews, and explanations.
- **File Operations**: Create, read, and manage files within a simulated workspace.
- **Example Files**: Generate example code files to get started quickly.
- **Settings Customization**: Adjust agent persona, creativity level, and API key for personalized assistance.
- **Gradio Interface**: User-friendly web interface for seamless interaction.

## Tech Stack

- **Python**: Core programming language.
- **Gradio**: Web interface framework.
- **Cohere API** (optional): For advanced AI capabilities.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/Code-Craft-AI.git
   cd Code-Craft-AI
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up the workspace**:
   ```bash
   python App.py
   ```

## Usage

1. **Run the application**:
   ```bash
   python App.py
   ```

2. **Access the interface**:
   Open your browser and navigate to `http://localhost:7860`.

3. **Interact with the AI**:
   - Use the chat interface to ask coding questions or request code generation.
   - Manage files in the workspace using the file operations tab.

**Example Commands**:
- "Write a Python function to check prime numbers"
- "Explain recursion with an example"
- "Review this code: `def add(a, b): return a + b`"

## Project Structure

```
Code-Craft-AI/
├── App.py              # Main application file
├── Prompts/            # Directory for system prompts (not used in this example)
└── workspace/          # Simulated workspace for file operations
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
