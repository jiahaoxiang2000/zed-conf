# Zed Editor Configuration

Personal configuration for the [Zed](https://zed.dev) text editor, optimized for development workflows with vim mode, AI integration, and LaTeX support.

## Features

- **Vim Mode**: Full vim keybindings and modal editing
- **AI Integration**: GitHub Copilot for code completion and chat (GPT-4.1)
- **LaTeX Support**: TeXLab LSP with latexmk build system and Okular PDF forward search
- **Custom Themes**: GitHub Dark theme configuration
- **Task Runner**: Configured tasks for common development workflows

## Configuration Files

- `settings.json` - Main editor settings and preferences
- `keymap.json` - Custom key bindings (currently using defaults)
- `tasks.json` - Task definitions for running commands
- `themes/` - Custom theme directory
- `.claude/` - Claude AI configuration (submodule)

## Installation

1. Clone this repository to your Zed config directory:
   ```bash
   git clone --recurse-submodules https://github.com/jiahaoxiang2000/zed-conf.git ~/.config/zed
   ```

2. Initialize submodules if not already done:
   ```bash
   cd ~/.config/zed
   git submodule update --init --recursive
   ```

3. Restart Zed to apply the configuration

## License

This configuration is part of a personal dotfiles collection and is provided as-is for reference and inspiration.
