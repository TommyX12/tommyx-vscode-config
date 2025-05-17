## Setup

### Visual Studio Code

- Install [Visual Studio Code](https://code.visualstudio.com/)
- Install the following extensions:
    - TODO
- Quit Visual Studio Code
- Run the following command to setup configuration files:
    - macOS:
        ```bash
        (cd <path-to-repo> && \
        rm -rf ~/Library/Application\ Support/Code/User/snippets && \
        rm -f ~/Library/Application\ Support/Code/User/keybindings.json && \
        rm -f ~/Library/Application\ Support/Code/User/settings.json && \
        rm -f ~/Library/Application\ Support/Code/User/tasks.json && \
        ln -s "$(pwd)/vscode/snippets" ~/Library/Application\ Support/Code/User/snippets && \
        ln -s "$(pwd)/vscode/keybindings.json" ~/Library/Application\ Support/Code/User/keybindings.json && \
        ln -s "$(pwd)/vscode/settings.json" ~/Library/Application\ Support/Code/User/settings.json && \
        ln -s "$(pwd)/vscode/tasks.json" ~/Library/Application\ Support/Code/User/tasks.json)
        ``````

