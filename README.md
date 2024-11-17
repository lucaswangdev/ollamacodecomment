# OllamaCodeComment README

[中文说明/Chinese Documentation](README_CN.md)

This is the README for your VS Code extension "OllamaCodeComment". It helps developers easily generate code comments using AI models with a simple workflow.

## Features

OllamaCodeComment streamlines the process of generating comments for your code. Follow these steps to use it effectively:

1. Run the command to pull the AI model:
   ```bash
   ollama pull phi3.5
   ```
2. Start the AI model server:
   ```bash
   ollama serve
   ```
3. Copy the code snippet to your clipboard.
4. Place the cursor at the location in your code where you want to insert the generated comment.
5. Open the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P`) and execute the `ollamacodecomment.ollamacodecomment` command.

The extension will analyze the code in your clipboard and insert meaningful comments at the specified location.

### Screenshots

\!\[Generating code comments\]\(images/feature-screenshot.png\)

> Tip: Use concise animations to showcase the command execution process and how comments are generated.

## Requirements

To use OllamaCodeComment, ensure the following dependencies are installed:

- [Ollama CLI](https://ollama.ai/) (Install and configure using the official documentation.)
- An active AI model such as `phi3.5` pulled using the `ollama pull` command.

## Extension Settings

This extension contributes the following settings:

- `ollamaCodeComment.enable`: Enable or disable the extension.
- `ollamaCodeComment.model`: Specify the AI model to use for generating comments (default: `phi3.5`).

## Known Issues

- Comments may occasionally be misaligned if the code structure is unconventional. Ensure your code follows standard formatting for optimal results.
- AI model latency may vary based on system performance.

## Release Notes

### 1.0.0

- Initial release of OllamaCodeComment.
- Features:
  - AI-powered code comment generation.
  - Seamless integration with VS Code's Command Palette.

---

## Following Extension Guidelines

Ensure you've reviewed and followed the [Extension Guidelines](https://code.visualstudio.com/api/references/extension-guidelines) for best practices.

## For More Information

- [Visual Studio Code's Markdown Support](http://code.visualstudio.com/docs/languages/markdown)
- [Markdown Syntax Reference](https://help.github.com/articles/markdown-basics/)

**Enjoy using OllamaCodeComment to enhance your code!**
