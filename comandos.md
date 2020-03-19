# Comandos

##### Aula 01 
>Ver a versão 

    git --version

>Comandos Básicos de ajuda

    git 

>Iniciar rastreamento

    git init

>Verificar Estado atual

    git status

##### Aula 02

>Adicionar Arquivo (Staging area)

    git add file.extensao

>Usuario

    git config --global user.name "Fulano"

    git config --global user.email "fulano@email"

>Saber usuario e email

    git config user.name
    git config user.email

>commit

    git commit -m "mensagem de commit"


##### Aula 03

>Visualisar todos os commits 

    git log

>Sair da visualisação do git log

    q

>Ver as Modificações, Mais que ainda não foram Adicionadas

    git diff

##### Aula 04

>Ver as Modificações, Mais que ainda não foram Adicionadas

    git diff

>Adicionar Vários Arquivos

    git add .

>Depois de add se quiser ver o que já ta add (está na staging)

    git diff --staged


___OBS___ 

git diff Compara a Working com a Staging
git diff --staged Compara a Staging com a .gitDiretory


##### Aula 05 

>Ver as alterações de um arquivo específico

    git diff <file>

>Depois de add se quiser ver o que já ta add(está na stage)

    git diff --staged 


>Depois de add se quiser ver o que já ta add por arquivo(está na stage)

    git diff --staged <file>

>Visualizar Todos os Commits

    git log

>Visualizar Todos os Commits e saber quais arquivos foram modificados
Vai aparecer Tudo
    git log --name-status 

>Ver Alterações ocorridas do 1º commit até o último 

    git diff <numero do commit1>


>Ver Alterações ocorridas entre o 2ª commit até o 4º

             2ª commit 4ª commit
    git diff < 1442e06 e6031a9>
