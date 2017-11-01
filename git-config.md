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
	lg = log --graph --abbrev-commit --date=short --pretty=format:'%C(magenta)%h%C(reset) - %C(bold cyan)%ad%C(reset) %C(yellow)%d%C(reset) %s %C(green)%cr %C(bold blue)<%an>%C(reset)'
	lg-date = log --graph --date=local --abbrev-commit --pretty=format:'%C(magenta)%h%C(reset) - %C(bold cyan)%ad%C(reset) %C(yellow)%d%C(reset) %s %C(bold blue)<%an>%C(reset)'
	lg-full = log --graph --abbrev-commit --pretty=format:'%C(magenta)%h%C(reset) - %C(bold cyan)%ad%C(reset) %C(yellow)%d%C(reset) %s %C(bold blue)<%an>%C(reset)' --all
	ck = checkout
```
