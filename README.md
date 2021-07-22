# mesheryctl-aliases
Programmatically generated, handy mesheryctl aliases.

### Examples

Some of the generated aliases are:
```shell
alias m="mesheryctl"
alias ms="mesheryctl system"

alias mslo="mesheryctl system logs"
...
```

### Installation

You can directly download the .mesheryctl_aliases file and save it in your `$HOME` directory, then edit your `.bashrc/.zshrc` file with:
```shell
[ -f ~/.mesheryctl_aliases ] && source ~/.mesheryctl_aliases
```