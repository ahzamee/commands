#### Run VSCode from folder Mac
- If you want to run VS Code from the terminal, append the following to your ~/.bash_profile file (~/.zshrc in case you use zsh).

 `code () { VSCODE_CWD="$PWD" open -n -b "com.microsoft.VSCode" --args $* ;}`
