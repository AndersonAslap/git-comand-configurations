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
$ git config --global core.editor <nome_editor> 
```

Assim como : 

```bash
$ git config --global core.editor code
```