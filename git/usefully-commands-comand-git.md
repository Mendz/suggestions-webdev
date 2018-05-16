# Usefully Commands in Git

- `git checkout -b [name_of_your_new_branch]` : Create a new branch.
- `git branch -a` : List all of the local and remote branches. ([for more info](http://gitready.com/intermediate/2009/02/13/list-remote-branches.html))
- `git branch -r` : List only all of the remote branches. ([for more info](http://gitready.com/intermediate/2009/02/13/list-remote-branches.html))
- `git mv old_filename new_filename` : Rename a file, I found it useful when I needed to change the file extension. ([for more info](https://help.github.com/articles/renaming-a-file-using-the-command-line/))
- `git log --grep='css'`: Filter the logs that have the word **css** in their commits. You can also add `--author=""` to filter by the commit author.
- `git commit --amend`: Open the editor to change the last not pushed commit message. ([for more info](https://help.github.com/articles/changing-a-commit-message/))