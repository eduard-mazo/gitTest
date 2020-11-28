# Starting with Git

## To-dos

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item
- [x] Adding github rules

## Setting SSH

Create your SSH file

    ssh-keygen -t rsa -C "user@email.com"

Start your ssh-agent and add your new ssh key

    eval "$(ssh-agent -s)"

    ssh-add /c/users/ASUS/.ssh/github

Add your ssh to github

check your connection to **GitHub**

    ssh -vT git@github.com

