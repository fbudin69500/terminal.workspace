# terminal.workspace

## Installation

To install this project, it is recommended to clone this repository
in $HOME/.terminal.workspace
```
git clone https://github.com/fbudin69500/terminal.workspace.git .terminal.workspace
```
Then add the following line into your terminal configuration file.
```
source ~/.terminal.workspace/workspace.config
```
If you are using zsh:
```
echo "source ~/.terminal.workspace/workspace.config" >> ~/.zshrc
```
## TODO

* Document using local vs environment variables (environment variables clutter the
environment but allow the user to interrogate the current configuration.
* Allow a quiet vs verbose mode which would print information when changing directory.
with just a name, not the whole path. Beware: Handle collisions.
* Can we create an extension that saves the command history per folder?
* Allow inheritance of workspace configuration.
* Improve manual configuration by creating configuration file and update configuration file that contains a name
and a corresponding folder. This would allow calling the activate and deactivate function
