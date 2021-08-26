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


#4) Instalando a biblioteca request para testar na virtual venv
```buildoutcfg
$ pip install requests
```
-Verificar se funcionou:
```buildoutcfg
$ pip freeze
```

#5) Criação do templatenewproject e do github_api para usar o request como exemplo:

#6) Criação do requirements.txt com comando:
```buildoutcfg
$ pip freeze > requirements.txt
```
para outros programadores usarem, será apenas necessário rodar o codigo no terminal:
```buildoutcfg
$ pip install -r requirements.txt
```

#7) Flake8 (biblioteca de desenvolvimento para saber se o projeto está conforme a PEP 8)
```buildoutcfg
$ pip install flake8
```

#8) Fazer pip freeze pararequirements-dev.txt (-r requirements.txt)

#9) Criar arquivo .flake8:
```buildoutcfg
$ flake8
```
para rodar o flake8