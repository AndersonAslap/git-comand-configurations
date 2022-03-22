# Níveis de configurações

> Existem 3 tipos de níveis de configuração no git

> Configuração do git para a máquina toda qualquer projeto <br> e qualquer usuário na máquina.

```bash
$ git config --system
```

> Configuração do usuário para qualquer projeto.

```bash
$ git config --global
```

> Configuração do projeto atual.

```bash
$ git config --local
```

# git basic comands utils

> ...

```bash
$ git pull
```

> ...
```bash
$ git add .
```

> ...
```bash
$ git commit -m "message"
```

> ...
```bash
$ git push
```

> ...
```bash
$ git log
```

> ...
```bash
$ git checkout -B <name>
```

> Comando que lista todas as configurações da máquina
```bash
$ git branch
```

> Comando que lista todas as configurações da máquina
```bash
$ git merge
```

# Alteração pessoal para meus projetos

> Com o comando abaixo consegue-se editar as configurações.
```bash
$ git config --global --edit 
```

> Com o comando abaixo consegue-se editar as configurações em um editor de texto. 
```bash
$ git config --global core.editor <nome_editor> 
$ git config --global --edit 
```

Assim como : 

```bash
$ git config --global core.editor code
$ git config --global --edit 
```

# Criando atalhos 

> No aquivo .gitconfig adicionei 3 atalhos para o seguintes comandos.
- git log
- git status
- git add e git commit 

```gitconfig
[alias]
	s = !git status -s 
	c = !git add --all && git commit -m
	l = !git log --pretty=format:'%C(blue)%h%C(red)%d %C(white)%s - %C(cyan)%cn, %C(green)%cr'
    p = !git push
```

- $ git log => $ git l
- $ git status => $ git s
- $ git add -all e git commit -m => $ git c "message"
- $ git push => $ git p
