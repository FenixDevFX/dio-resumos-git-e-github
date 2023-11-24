
# Dio | Resumos Git e GitHub

Repositórios para armazenar resumos sobre Git e GitHub da [Digital Innovation One](https://www.dio.me).

## 📚 Documentação
- [Documentação Git](https://git-scm.com/doc)
- [Documentação GitHub](https://docs.github.com)

## 💻 Resumo das Aulas
| Aulas | Resumos |
|-------| --------|
| Gravando Alterações no Repositório Local | [Resumo]() |
| Aula 2 | [Resumo]() |

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
```


## 🔍 Referências
- [Digital Innovation One](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/3f9f2336-6fd5-44cb-ba39-d1a4f6448023?back=/track/coding-future-banco-pan-desenvolvimento-frontend-com-angular&tab=undefined&moduleId=undefined).
