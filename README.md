# Git Config

```bash
git config --global color.ui true
alias grep='grep --color'
alias ll="ls -lhA  --color"

# 顯示 Log 圖形紀錄
show-graph = log --graph --abbrev-commit --pretty=oneline
lg1 = log --graph --oneline --decorate --date=relative --all	
lg2 = log --graph --abbrev-commit --decorate --date=relative --format=format:'%C(bold blue)%h%C(reset) - %C(bold green)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(bold yellow)%d%C(reset)' --all
lg3 = log --graph --abbrev-commit --decorate --format=format:'%C(bold blue)%h%C(reset) - %C(bold cyan)%aD%C(reset) %C(bold green)(%ar)%C(reset)%C(bold yellow)%d%C(reset)%n''          %C(white)%s%C(reset) %C(dim white)- %an%C(reset)' --all    
lg4 = log --graph --abbrev-commit --decorate --date=relative --all
lg5 = log --graph --abbrev-commit --decorate --format=format:'%C(bold blue)%h%C(reset) %C(bold yellow)%d %C(white)%s%C(reset)%n ' --all        
lg = !"git lg1"
```

# Git Add Remote
```bash
git remote add origin /Remote/Project/Path/
git remote update
git remote -v
```
