# Comandos Git Hub

## 10- O que significa o git pull?
#### É usado para buscar e baixar conteúdo de repositórios remotos e atualizar o repositório local

## 11- Acesse o histórico da sua branch atual (main):
#### git log - Este comando exibirá uma lista de commits com seus hashes, mensagens de commit, autor e data.

## 12- Crie uma tag do seu projeto:
## git tag -a v1.0 -m "Versão 1.0" - Neste exemplo, v1.0 é o nome da tag, e "Versão 1.0" é a mensagem associada a ela.

## 13- Inclua um título no index.html (ou outra modificação), crie uma branch com o nome feature/inclusão-do-título. 
## Faça a modificação no arquivo index.html.
## Crie uma nova branch:
## git checkout -b feature/inclusao-do-titulo
## Isso criará e moverá você para a nova branch.

## 14- Como acessar uma branch? 
## git checkout nome-da-branch
## Por exemplo, para acessar a branch feature/inclusao-do-titulo:
## git checkout feature/inclusao-do-titulo

## 15- Como trocar de branch?
## git checkout main

## 15- Como deletar uma branch?
## git branch -d nome-da-branch

## 16- Entre na main branch e faça um merge da branch desejada para integrar ao main.
## 1 - git checkout main 
## 2 - git merge inclusao-do-titulo

## 17- Para resolver o conflito do código, por que é preferível utilizar o rebase em vez do merge?

## 18- Como inserir apenas um commit de uma branch para a main?

## 19- Resete seu código até algum momento utilizando como parâmetro o hash da commit:

## 20- Crie um arquivo tipo txt e guarde em sua stash:

## 21- Como fazer um Pull-Request?

## 22- Como adicionar Reviewers em seu repositório:

# Outras informações: 
## git add . -> adicionar na stage 
## git commit -m "Alteracoes" -> Salva no repositorio local 
## git push -> sobre para o github 
## git status -> verifica o status 
## git pull -> atualiza repositorio local 
## git pull (siginificado) -> significa basicamente dois comando git fetch e git merge. 
## git log -> acessa o historico dos commits 
#### Para fazer um pull request no GitHub: faça um fork do repositório e clone-o. Crie uma nova branch para suas alterações. Edite o código, adicione as mudanças e faça o commit. Envie a branch para o repositório no GitHub e crie o pull request para que suas alterações possam ser revisadas e mescladas.