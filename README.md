# Thinking Claude

Let Claude think comprehensively before responding!

> **A super quick reminder:**
> Thinking claude **is not aimed for benchmarks or huge leaps in math or something**, since those are pre-determined by the base model (new Claude-3.5 Sonnet).
> I only want to explore how further we could reach with Claude's "deep mindset". That said, when using it in your daily tasks, you will find Claude's inner monolog (thinking process) very very fun and interesting.

## Demo:


https://github.com/user-attachments/assets/88ff0c75-c51b-42b9-a042-00d47053795a


## Overview

This project consists of two main components:
1. **Thinking Protocol**: A comprehensive set of instructions that guides Claude to think deeply and systematically before responding
2. **Browser Extension**: A tool that makes Claude's thinking process more readable and manageable in the browser interface

## Project Structure
thinking-claude/
├── extension/
│   ├── .vscode/
│   ├── chrome/
│   ├── firefox/
│   └── changelog.md
├── model_instructions/
│   ├── changelog.md
│   ├── v3.5-20241113.md
│   ├── v4-20241118.md
│   ├── v4-visualization-20241121.md
│   ├── v4-lite-20241118.md
│   └── v4-lite-visualization-20241121.md
├── LICENSE
└── README.md
The project is organized into two main directories:
- `extension/`: Contains browser extension implementations
- `model_instructions/`: Contains thinking protocols for different versions

Each directory maintains its own changelog for version tracking.
## Thinking Protocol

The thinking protocol instructs Claude to follow a natural, thorough thought process before providing responses.

## Browser Extension

The browser extension enhances the Claude interface by making the thinking process more manageable:

### Features
- 🔄 Collapsible thinking process sections
- 📋 Easy copy functionality
- 🎯 Clean and intuitive interface
- ⚡ Automatic processing of new messages

### Installation

#### Chrome

**Quick Install:**
Install directly from the [Chrome Web Store](https://chromewebstore.google.com/detail/thinking-claude/ncjafpbbndpggfhfgjngkcimeaciahpo)

**Manual Installation:**
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/thinking-claude.git
2. Open Chrome and navigate to `chrome://extensions/`
3. Enable "Developer mode"
4. Click "Load unpacked" and select the `extension/chrome` folder

#### Firefox
1. Clone this repository 
2. Open Firefox and navigate to `about:debugging#/runtime/this-firefox`
3. Click "Load Temporary Add-on"
4. Navigate to the repository and select the `extension/firefox/manifest.json` file

## Usage

### Applying the Thinking Protocol

1. Copy the latest version in `model_instructions` folder
2. Start a new Project in Claude.ai
3. Paste the instructions to the Custom Instructions section
3. Claude will now follow the thinking protocol for all subsequent interactions

### Using the Extension

Once installed, the extension automatically:
- Detects Claude's thinking process blocks
- Adds collapse/expand functionality
- Provides a copy button for each block

## Why Use Thinking Claude?

- **Better Reasoning**: Get more thorough and well-thought-out responses
- **Transparency**: See how Claude arrives at its conclusions
- **Improved Organization**: Manage long conversations more effectively
- **Quality Control**: Benefit from built-in verification steps

## Adding Feature: Visualization

1. Enhanced Visibility
   * Integrated Mermaid diagrams for thought flow tracking
   * Hierarchical visualization structure
   * Progressive updates as thinking evolves
2. Usage
   * Use v4-visualization-20241121.md for full version
   * Use v4-lite-visualization-20241121.md for lightweight version
   * Paste into Claude's Custom Instructions
3. Benefits 
   * Clear thought process tracking
   * Easy-to-follow reasoning flow

## Contributing

Contributions are welcome! Feel free to:
- Submit bug reports
- Propose new features
- Create pull requests

## License

MIT License - feel free to use and modify as needed.

## Acknowledgments

Special thanks to Claude! We build this whole extension together!
