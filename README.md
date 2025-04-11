# Atividade Avaliativa - Git Colaborativo com Portugol

## Integrantes do grupo
- Rafael Eiji Hokama utiyama
- Luis Augusto
- Marcos Yudi

## Objetivo
Desenvolver colaborativamente um algoritmo em Portugol de uma calculadora (soma, subtração e multiplicação)

## Etapas realizadas por cada membro

### Rafael Utiyama
- O repositorio foi criado a partir do Github, e compartilhado com os integrantes do grupo
- O git bash foi configurado utilizando os comandos "$ git config --global user.name "RafaelUtiyama"" para configurar o nome, "$ git config --global user.email "rafaelutiyama@edu.unifil.br"" para configurar o email e "ssh-keygen -t rsa -b 4096 -C "rafaelutiyama@edu.unifil.br"" para gerar a senha SSH, apos isso inicializei o agente SSH, adiciono a chave SSH ao agente e colo a chave SSH no Github
- Criei o arquivo "codigo.por" em branco, para cada membro modificar o codigo.
- Apos a criação do codigo, fiz o clone do repositorio "Trabalho-final-git" para meu computador utilizando o git bash, com o repositorio na minha maquina, eu modifiquei o código adicionando a soma. Apos a modificação dei um commit com a descrição "soma" para indicar a mudança feita no codigo e por fim dei o push para mandar o repositorio modificado de volta para o github.


### Luis Augusto
- Configurei o meu user name e email no repositório e após criei a minha chave SSH. Então, iniciei o meu agente e adicionei a minha chave ao o agente depois registrei a minha chave no GitHub web usando o comando clip. Após ter feito isso estava pronto para clonar o repositório, clonei-o em um pasta na área de trabalho e entrei no diretório do repo usando o comando cd repositório, editei os arquivos e no git bash fiz o comando git add e o git commit com a descrição do que eu alterei no meu código e por fim um git push para lançar as minhas alterações na nuvem.

### Marcos Yudi


## Comandos utilizados
Todos os comandos foram executados via terminal utilizando chave SSH:
### Comandos de Rafael

compuni@Lab6m11 MINGW64 ~
$ git config --global --unset user.email

compuni@Lab6m11 MINGW64 ~
$ rm -f ~/.ssh/id_rsa*

compuni@Lab6m11 MINGW64 ~
$ git config --global user.name

compuni@Lab6m11 MINGW64 ~
$ git config --global user.email

compuni@Lab6m11 MINGW64 ~
$ git config --global user.name "RafaelUtiyama"

compuni@Lab6m11 MINGW64 ~
$ git config --global --unset user.name

compuni@Lab6m11 MINGW64 ~
$ git config --global user.name "RafaelUtiyama"

compuni@Lab6m11 MINGW64 ~
$ git config --global user.name
RafaelUtiyama

compuni@Lab6m11 MINGW64 ~
$ git config --global user.email "rafaelutiyama@edu.unifil.br"

compuni@Lab6m11 MINGW64 ~
$ ssh-keygen -t rsa -b 4096 -C "rafaelutiyama@edu.unifil.br"
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/compuni/.ssh/id_rsa):
Enter passphrase for "/c/Users/compuni/.ssh/id_rsa" (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/compuni/.ssh/id_rsa
Your public key has been saved in /c/Users/compuni/.ssh/id_rsa.pub
The key fingerprint is:
SHA256:CJAYlS5qJWD2quFTdETWUiq+lKQ6zysCtNKGUCzJda4 rafaelutiyama@edu.unifil.br
The key's randomart image is:
+---[RSA 4096]----+
|o*++.+o.         |
|=+=.+o..         |
|++.ooo.          |
|oo=++o .         |
|+=*E. . S        |
|B++..            |
|Oo..             |
|+*               |
|..=.             |
+----[SHA256]-----+

compuni@Lab6m11 MINGW64 ~
$ eval "$(ssh-agent -s)"
Agent pid 1633

compuni@Lab6m11 MINGW64 ~
$ clip < ~/.ssh/id_rsa.pub

compuni@Lab6m11 MINGW64 ~
$ ssh -T git@github.com
Hi rafaelutiyama! You've successfully authenticated, but GitHub does not provide shell access.


compuni@Lab6m11 MINGW64 ~/Desktop/Nova pasta
$ ssh -T git@github.com
Hi rafaelutiyama! You've successfully authenticated, but GitHub does not provide shell access.

compuni@Lab6m11 MINGW64 ~/Desktop/Nova pasta
$ git clone git@github.com:rafaelutiyama/Trabalho-final-git.git
Cloning into 'Trabalho-final-git'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (6/6), done.

compuni@Lab6m11 MINGW64 ~/Desktop/Nova pasta
$ cd "C:\Users\compuni\Desktop\Nova pasta\Trabalho-final-git"

compuni@Lab6m11 MINGW64 ~/Desktop/Nova pasta/Trabalho-final-git (main)
$ git add .

compuni@Lab6m11 MINGW64 ~/Desktop/Nova pasta/Trabalho-final-git (main)
$ git commit -m "Soma"
[main 12c4fe4] Soma
 1 file changed, 15 insertions(+)

compuni@Lab6m11 MINGW64 ~/Desktop/Nova pasta/Trabalho-final-git (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 407 bytes | 407.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To github.com:rafaelutiyama/Trabalho-final-git.git
   eac65c0..12c4fe4  main -> main


### Comandos de Luis

compuni@Lab6m10 MINGW64 ~
$ git config --global user.name
rafael

compuni@Lab6m10 MINGW64 ~
$ git config --global user.email
rafaelhu763@gmail.com

compuni@Lab6m10 MINGW64 ~
$ git config --global --unset user.name

compuni@Lab6m10 MINGW64 ~
$ git config --global --unset user.email

compuni@Lab6m10 MINGW64 ~
$ ls -al ~/.ssh
total 17
drwxr-xr-x 1 compuni 1049089   0 Mar 28 20:50 ./
drwxr-xr-x 1 compuni 1049089   0 Apr 11 19:04 ../
-rw-r--r-- 1 compuni 1049089 828 Mar 28 19:41 known_hosts
-rw-r--r-- 1 compuni 1049089  92 Mar 28 19:41 known_hosts.old

compuni@Lab6m10 MINGW64 ~
$ rm -f ~/.ssh/id_rsa*

compuni@Lab6m10 MINGW64 ~
$ ls -al ~/.ssh
total 17
drwxr-xr-x 1 compuni 1049089   0 Mar 28 20:50 ./
drwxr-xr-x 1 compuni 1049089   0 Apr 11 19:04 ../
-rw-r--r-- 1 compuni 1049089 828 Mar 28 19:41 known_hosts
-rw-r--r-- 1 compuni 1049089  92 Mar 28 19:41 known_hosts.old

compuni@Lab6m10 MINGW64 ~
$ rm -f ~/.ssh/id_rsa*

compuni@Lab6m10 MINGW64 ~
$ ls -al ~/.ssh
total 17
drwxr-xr-x 1 compuni 1049089   0 Mar 28 20:50 ./
drwxr-xr-x 1 compuni 1049089   0 Apr 11 19:04 ../
-rw-r--r-- 1 compuni 1049089 828 Mar 28 19:41 known_hosts
-rw-r--r-- 1 compuni 1049089  92 Mar 28 19:41 known_hosts.old

compuni@Lab6m10 MINGW64 ~
$ git config --global user.name

compuni@Lab6m10 MINGW64 ~
$ git config --global user.name LuisAugusto00

compuni@Lab6m10 MINGW64 ~
$ git config --global user.email luisaugustobarbosab@gmail.com

compuni@Lab6m10 MINGW64 ~
$ ssh-keygen -t rsa -b 4096 -C luisaugustobarbosab@gmail.com
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/compuni/.ssh/id_rsa):
Enter passphrase for "/c/Users/compuni/.ssh/id_rsa" (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/compuni/.ssh/id_rsa
Your public key has been saved in /c/Users/compuni/.ssh/id_rsa.pub
The key fingerprint is:
SHA256:P5p5Lb6K0wR3vnESXQu4mD+gfPKVPYmxJwZZeEBYxqA luisaugustobarbosab@gmail.com
The key's randomart image is:
+---[RSA 4096]----+
|      .*=o .     |
|     ...o + . .  |
|    E    * o o . |
|      . B = . .  |
|     . +S* B .   |
|      + o.& *    |
|       * ooX .   |
|      ..o++..    |
|      ..=+oo     |
+----[SHA256]-----+

compuni@Lab6m10 MINGW64 ~
$ eval "$(ssh-agent -s)"
Agent pid 598

compuni@Lab6m10 MINGW64 ~
$ ssh-add ~/.ssh/id_rsa
Identity added: /c/Users/compuni/.ssh/id_rsa (luisaugustobarbosab@gmail.com)

compuni@Lab6m10 MINGW64 ~
$ clip < ~/.ssh/id_rsa.pub

compuni@Lab6m10 MINGW64 ~
$ ssh -T git@github.com
Hi LuisAugusto00! You've successfully authenticated, but GitHub does not provide shell access.

compuni@Lab6m10 MINGW64 ~
$


compuni@Lab6m10 MINGW64 ~/Desktop/Nova pasta (2)
$ git clone git@github.com:rafaelutiyama/Trabalho-final-git.git
Cloning into 'Trabalho-final-git'...
remote: Enumerating objects: 9, done.
remote: Counting objects: 100% (9/9), done.
remote: Compressing objects: 100% (6/6), done.
remote: Total 9 (delta 0), reused 3 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (9/9), done.

compuni@Lab6m10 MINGW64 ~/Desktop/Nova pasta (2)
$ cd "C:\Users\compuni\Desktop\Nova pasta (2)\Trabalho-final-git"

compuni@Lab6m10 MINGW64 ~/Desktop/Nova pasta (2)/Trabalho-final-git (main)
$ git add .

compuni@Lab6m10 MINGW64 ~/Desktop/Nova pasta (2)/Trabalho-final-git (main)
$ git commit -m "Adição da subtração no código"
[main 7a4b7dd] Adição da subtração no código
 1 file changed, 4 insertions(+), 3 deletions(-)

compuni@Lab6m10 MINGW64 ~/Desktop/Nova pasta (2)/Trabalho-final-git (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 407 bytes | 407.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To github.com:rafaelutiyama/Trabalho-final-git.git
   12c4fe4..7a4b7dd  main -> main


### Comandos de Marcos


## Observações
Cada etapa foi realizada por apenas um integrante por vez, respeitando a ordem de commits e a integridade do código. 
