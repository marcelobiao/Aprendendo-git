# Aprendendo git
Esse arquivo irá ter todos os comandos do curso Git

## Comando iniciais
```shell
$ git config --global user.name "Marcelo Bião"
$ git config --global user.email "marcelobiao2@gmail.com"
$ git init
$ git status
```

## Comandos de Log
```shell
$ git log
$ git log --full-diff -p README.md
```

## Trabalhando com branchs
```shell
$ git checkout -b <name> # Cria e faz checkout na nova branch
$ git checkout <name> # Altera entre as branchs
$ git branch <name> # Cria uma nova branch
$ git checkout <name> # Alterna entre as branchs
```

## Checkout
```shell
$ git checkout -- <file> #Desfaz as mudanças
```

# Trabalhando com tags
```shell
$ git tag                               # Lista todas as tags
$ git tag -a v0.0.1 -m "Texto qualquer" # Adiciona uma nova tag
$ git show v0.0.1                       # Mostra conteudo da tag
$ git tag -d v0.0.1                     # Apaga uma tag
```
