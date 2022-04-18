## QUESTÃO 5 - ATIVIDADE GIT E GITHUB

#### Questão 1

<a href="https://github.com/marlissonls/my_first_steps">https://github.com/marlissonls/my_first_steps</a>

#### Questão 2

```bash

#Escolha do diretório
$ cd E:/AlphaEdTech/TRILHAS/Hard Skills/Introdução Web/Aula 7

#Iniciando o rastreamento no diretório local
$ git init

#Iniciando ramificação
$ git branch -M main

#Sincronizando o diretório local com o repositório remoto
$ git remote add origin https://github.com/marlissonls/my_first_steps.git

#Verificação
$ git remote -v
origin  https://github.com/marlissonls/my_first_steps.git (fetch)
origin  https://github.com/marlissonls/my_first_steps.git (push)

```
#### Questão 3

```bash

#Colocando o arquivo na STAGE AREA
$ git add ola_mundo.txt

#Iniciando o rastreamento do arquivo
$ git commit -m "iniciando o rastreamento"

#Enviando para o repositório remoto
$ git push --set-upstream origin main #git push -u origin main

```
#### Questão 4

```bash

serei_ignorado.txt

# $ git touch .gitignore
# $ git nano .gitignore
# *O arquivo .gitignore foi editado com o texto: serei_ignorado.txt*
# $ git add .gitignore
# $ git commit -m "Rastrear .gitignore"
# $ git push

```
#### Questão 5

```bash

#Adicionando o arquivo README.md para a STAGE AREA
$ git add README.md

#Iniciando o rastreamento do arquivo README.md
$ git commit -m "Rastreando o arquivo README.md"

#Enviado o arquivo README.md para o respositório remoto
$ git push
```


