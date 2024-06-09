# git-configs
Um repositório para armazenar e compartilhar configurações personalizadas do Git.

Abra o arquivo de configuração do git.
```bash
git config --global --edit
```

Substitua os arquivos de configuração atuais pelos fornecidos abaixo:
```txt
[user]
	name = paulohdelia
	email = paulohdelia@gmail.com
[core]
	editor = vim
[alias]
	e = !git config --global --edit
	r = !git rebase -i --root
	s = !git status -s
	c = !git add --all && git commit -m
	cc = !git add --all && git commit
	l = !git log --pretty=format:'%C(cyan)%h %C(magenta)%d %C(white)%s %C(green)- %cr'
	logg = !git log --pretty=format:'%C(cyan)%h %C(magenta)%d %C(white)%s - %C(cyan)%cn, %C(green)%ce / %C(yellow)%cr'
```
