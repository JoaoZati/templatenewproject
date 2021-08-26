# templatenewproject
Template de como criar um projeto do zero de python no git.

#1) Utilização do git:
-Criando repositório;
-Criando chave ssh;
-Criação de forks;
-Commit and Push no Pycharm;
-Realização de Pull Requests;
-Feature Branch (origin, remote);
-Gerenciando Branch e conflitos;

#2) Atualizar .gitgnore para não utilizar .idea

#3) Criar e Setar .gitgnore_global para excluir .idea/ com comando (no terminal):
```buildoutcfg
$ git config --global core.excludesfile ~/.gitignore_global
```

#3) Criar virtualenv na pasta .venv
-No Pycharm em settings > Project > Python Interpreter
-via terminal utilizando o comando (Versão em Python 3):
```buildoutcfg
$ python -m venv .venv
```
(nota: na linha de comando podemos usar qualquer versão python utililando o pyenv)

-via terminal utilizando o comando (Versão em Python 2):
```buildoutcfg
$ python2 -m virtualenv .venv
```




