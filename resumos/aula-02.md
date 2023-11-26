Dando sequência a aula anterior na qual aprendemos como criar e clonar repositórios, hoje tratamos da gravação de alteração nos repósitórios. Assim como nas outras aulas estamos utilizando o terminal do Git Bash. Por isso, os comandos listados não estão precedidos de $ já que o terminal já o fornece.
Utilizamos alguns comandos:

```
git status
```
Para checar se alguma alteração foi realizada e ainda não foi preparada para a gravação.

Criamos um arquivo, neste caso um README.md, arquivo que tem como objetivo apresentar o projeto e explicar sua aplicação. Isto nos levou a conhecer a linguagem markup e algumas seções que compõem um readme.
Aprendemos que para tornar um arquivo rastreável (ser enxergado pelo git), ou seja adiciona-lo para a área de preparação, utlizamos o comando:

```
git add nome-do-arquivo.extensão
```


A próxima etapa abordada foi finalmente a gravação, por meio do comando:

```
git commit -m "Descreva o que foi feito na atualização"
