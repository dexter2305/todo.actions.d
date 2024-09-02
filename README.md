These are plugins or addons for todotxt-cli.  These are just grouped into a repository as is from the original repository. 

## Usage
- `todo.sh due [n-days]` lists tasks due in 'n-days'.
- `todo.sh do <todo-id>` overrides default `do` to handle recurrence.
- `todo.sh edit [todo-id]` opens the todo.txt file in default editor.

## Installation
```bash
mkdir ~/bin
# dnf, apt & brew install todo.sh in PATH. Only the plugins are to be installed and configured in todo.cfg.
git clone https://github.com/dexter2305/todo.actions.d ~/bin/todotxt-cli/todo.actions.d
```
