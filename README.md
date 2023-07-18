# Git 

# Curso de Git e Github COMPLETO 2021 [Iniciantes] + Desafios + Muita Prática
# https://www.youtube.com/watch?v=kB5e-gTAl_s&t=31s

Sequência para trabalhar com mais de uma branch

    Cria uma branch secundária, trabalha nela, atualizar a branch principal e commitar as alterações no servidor remoto.

1. Git pull da branch principal.
    $ git pull origin [branch-principal]

2. Gerar uma nova branch a partir da principal.
    $ git branch [nome-da-branch] ou $ git checkout -b [nome-da-branch] (cria a branch e faz o checkout).

3. Trabalhar e adicionar funcionalidades na nova branch que criou.

4. Finalizar o trabalho na branch temporária.

5. Git checkout na branch principal.
    $ git checkout [branch-principal]

6. Git pull da branch principal.
    $ git pull origin [branch-principal].

7. Fazer o merge (únir) os códigos da branch temporária com a principal, depois de testado.
    $ git checkout [branch-principal] $ git merge [branch-temporaria].

8. Envia para o repositório remoto.
    $ git push origin [branch-principal]


Reverter um commit   

1. Lista os commits realizados (para pegar o id do commit em questão).
    $ git reflog

2. Retorna para o commit desejado passando o id como parâmetro.
    $ git reset --hard [id]

  
-----------------


# Javascript
# Curso de JavaScript Assíncrono - Callbacks, Promises & Async/Await
https://www.youtube.com/watch?v=WUmAAxH9n-A
