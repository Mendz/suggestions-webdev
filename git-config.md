# Git Config

### Core

```
[core]
	editor = 'c:/program files (x86)/Notepad++/notepad++.exe' -multiInst -notabbar -nosession -noPlugin
```

### Alias

```
[alias]
	st = status
	sts = status -s
	ck = checkout
	lg = log --graph --abbrev-commit --date=short --decorate --pretty=format:'%C(magenta)%h%C(reset) - %C(bold cyan)%ad%C(reset) %C(yellow)%d%C(reset) %s %C(green)%cr %C(bold blue)<%an>%C(reset)'
	lgdate = log --graph --date=local --abbrev-commit --decorate --pretty=format:'%C(magenta)%h%C(reset) - %C(bold cyan)%ad%C(reset) %C(yellow)%d%C(reset) %s %C(bold blue)<%an>%C(reset)'
	lgfull = log --graph --numstat --abbrev-commit --decorate --pretty=format:'%C(magenta)%h%C(reset) - %C(bold cyan)%ad%C(reset) %C(yellow)%d%C(reset) %s %C(bold blue)<%an>%C(reset)' --all
	last = "!git lg --numstat -1"
	lastdif = diff --cached HEAD^
	filelog = log -u
	gconfig-e = config --global -e
	gconfig-l = config --global --list
	config-e = config -e
	config-l = config --list
	la = "!git config -l | grep alias | cut -c 7-"
	diff = diff --word-diff
	dc = diff --cached
```
