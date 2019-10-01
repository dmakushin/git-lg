# git-lg

Pretty print for git log comamnd. Just paste the line below to your command line and use `git lg` instead.
 
`git config --global alias.lg "log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit"`

Works with all standard parameters of regular `git log` like `git lg --all` to show all the branches.
