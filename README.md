## Setup

### Visual Studio Code

- Install [Visual Studio Code](https://code.visualstudio.com/)
- Install https://github.com/TommyX12/tommyx-vimrc
- Install the following extensions:
    - [vscodevim.vim](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim)
    - [patbenatar.advanced-new-file](https://marketplace.visualstudio.com/items?itemName=patbenatar.advanced-new-file)
    - [jeff-hykin.better-cpp-syntax](https://marketplace.visualstudio.com/items?itemName=jeff-hykin.better-cpp-syntax)
    - [streetsidesoftware.code-spell-checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
    - [naumovs.color-highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)
    - [MatthewNespor.vscode-color-identifiers-mode](https://marketplace.visualstudio.com/items?itemName=MatthewNespor.vscode-color-identifiers-mode)
    - [rid9.datetime](https://marketplace.visualstudio.com/items?itemName=rid9.datetime)
    - [sleistner.vscode-fileutils](https://marketplace.visualstudio.com/items?itemName=sleistner.vscode-fileutils)
    - [GitHub.copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot)
    - [GitHub.copilot-chat](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot-chat)
    - [eamodio.gitlens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
    - [oderwat.indent-rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow)
    - [yzhang.markdown-all-in-one](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
    - [fabiospampinato.vscode-open-in-github](https://marketplace.visualstudio.com/items?itemName=fabiospampinato.vscode-open-in-github)
    - [PKief.material-product-icons](https://marketplace.visualstudio.com/items?itemName=PKief.material-product-icons)
    - [PKief.material-icon-theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
    - [tomoki1207.selectline-statusbar](https://marketplace.visualstudio.com/items?itemName=tomoki1207.selectline-statusbar)
    - [alefragnani.separators](https://marketplace.visualstudio.com/items?itemName=alefragnani.separators)
    - [kylepaulsen.stack-tabs](https://marketplace.visualstudio.com/items?itemName=kylepaulsen.stack-tabs)
    - [wenhoujx.swiper](https://marketplace.visualstudio.com/items?itemName=wenhoujx.swiper)
    - [bbenoist.togglehs](https://marketplace.visualstudio.com/items?itemName=bbenoist.togglehs)
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
        ```

### Cursor

- Install [Cursor](https://cursor.com/)
- Setup things like privacy settings.
- Install https://github.com/TommyX12/tommyx-vimrc
- Install the following extensions:
    - The same set of extensions as Visual Studio Code (or just let Cursor import from VSCode), except for:
        - GitHub copilot related extensions
- Quit Cursor
- Run the following command to setup configuration files:
    - macOS:
        ```bash
        (cd <path-to-repo> && \
        rm -rf ~/Library/Application\ Support/Cursor/User/snippets && \
        rm -f ~/Library/Application\ Support/Cursor/User/keybindings.json && \
        rm -f ~/Library/Application\ Support/Cursor/User/settings.json && \
        rm -f ~/Library/Application\ Support/Cursor/User/tasks.json && \
        ln -s "$(pwd)/vscode/snippets" ~/Library/Application\ Support/Cursor/User/snippets && \
        ln -s "$(pwd)/vscode/keybindings.json" ~/Library/Application\ Support/Cursor/User/keybindings.json && \
        ln -s "$(pwd)/vscode/settings.json" ~/Library/Application\ Support/Cursor/User/settings.json && \
        ln -s "$(pwd)/vscode/tasks.json" ~/Library/Application\ Support/Cursor/User/tasks.json)
        ```
