# Command line scripts and aliases for everyday use

These are some of the aliases and short cuts we use on a daily basis for software development.

At the moment it contains short cuts for git, docker and some utilities. The locations included are local to our machines, so you'll need to customize them to fit your system.

There is a ruby runner included, check out the git commands in the `/lib` directory for an example.

### Installation
```
# Clone the repo. Fork it first if you plan to keep customizing it
git clone https://github.com/eldoy/dotfiles.git

# Add this line to your .zshrc or .bashrc, and start a new shell
source ~/your/path/to/clone/aliases.sh
```
### Usage
```
# Git command is 'g'
g 'Readme' # => git add --all && git commit -m "Readme" && git push
g          # => Will ask for message if you forget it

# To use the ruby runner
alias command="$C ruby_method_name arg1 arg2"
```

For other aliases, see the source
* [Aliases](https://github.com/eldoy/dotfiles/blob/master/aliases.sh)
* [Scripts](https://github.com/eldoy/dotfiles/tree/master/lib)
```

Created and by [Eldøy Tech AS](https://eldoy.com)
