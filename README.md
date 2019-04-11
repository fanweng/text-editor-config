
## VIM

Copy ```./vim/.vimrc``` into the **$HOME** directory and restart the vim application.

## Visual Studio Code

### User Settings

Copy ```./vs-code/User/settings.json``` into the ```User``` directory depending on the OS platform.

- **Windows**: ```%APPDATA%\Code\User\settings.json```
- **Linux**: ```$HOME/.config/Code/User/settings.json```
- **MacOS**: ```$HOME/Library/Application Support/Code/User/settings.json```

### Extensions

Useful extension identifiers are listed in the ```./vs-code/list-extensions.txt```. Search those extensions in the Extension Marketplace with prefix **@id:**, for example, **@id:ms-python.python**. Note that there is no space after colon symbol ':'.

MacOS must install 'code' command before running it in the shell. Launch VS Code and open the Command Palette (Shift+Cmd+P). Type **Shell Command: Install 'code' command in PATH command** and hit Enter button. Restart the terminal and now we can run the command below to show installed extensions.

```$ code --list-extensions``` 