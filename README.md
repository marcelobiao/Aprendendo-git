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
```
## Checkout
```shell
$ git checkout -- <file> #Desfaz as mudanças
```
