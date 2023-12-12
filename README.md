# git-flow

## 1. Iniciando o git flow
Neste repo temos um passo a passo de como utilizar o git flow de forma simples

De inicio, iremos utilizar o comando git flow init
assim que ele acontecer, sugiro manter os nomes que ja vem como sugestão para cada passo do gitflow

assim que o comando terminar, ja estaremos na branch de development


## 2. Usando a Feature
as features são updates que não estavam inicialmente envolvidos no escopo selecionado, ou seja, são novas mudanças que foram solicitadas no meio do caminho. assim, para adicionar uma nova utilizamos o git flow

git flow feature start css

para finalizar essa feature iremos fazer o seguinte comando
git flow feature finish
assim o merge é feito e a branch se finaliza

## 3. Subindo para release

por padrão, utilizamos a release com numerais, afim de identificar mais facilmente os major points da aplicação

git flow release start 1.0

esta branch é feita para que os testes possam ser aplicados, assim podemos enviar para teste a aplicação fazendo com que possamos garantir uma entrega com qualidade

assim que corrigir todos os bugs podemos finalizar
git flow release finish 1.0