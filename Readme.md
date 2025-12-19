Olá! Estou fazendo este mini projeto para aprender funcionalidades do Git e aprimorar meus conhecimentos na ferramenta

Isso é uma alteração

Este tutorial é feito através dos vídeos da Rafaella Ballerini, no yotube, conforme os links a seguir:
Parte 1: https://youtu.be/DqTITcMq68k?si=PhOb0Vfeh9kdzVt5
Parte 2: https://youtu.be/UBAX-13g8OM?si=85NLPM4XN66RiIND

E essas são as minhas anotações e aprendizados:
Git: sistema de versionamento de arquivo

GitHub: plataforma para hospedar esses arquivos
-repositorios: pastas para colocar projeto
-branch: ramificaçao para usar no projeto (varias linhas cronologicas para cada alteraçao feita no codigo)
-commit: postar a alteraçao/nova versao do projeto  (pode ser nas branchs)
-merge: junçao da branch principal com a ramificaçao
-push: joga o commit da sua maquina para o repositorio la no github
-remote: o repositorio da sua maquina tambem esteja no github
-pull: puxar o que está no github para sua maquina

Primeira coisa a se fazer é criar a pasta do projeto, abri-la e dar um "git init"

"git add (nome do arquivo)" ( "ou git add ." para adicionar todos os arquivos)serve para mandar um arquivo para a "staging area", preparando-os para serem incluídos no próximo commit

"git status" para mostrar as últimas mudanças para usar o "commit"

Agora sim usar "git commit -m "(titulo do commit)" "

Usar o comando "git branch -M "main" " para renomear a branch. Normalmente usado o nome "main" para a principal branch

"git remote add origin https://github.com/YagoDomiciano/Projeto-Git.git" serve para criar a conexão com nosso repositório no Git Hub que estou dando o nome de "origin"

"git push -u origin main" serve para enviar o ultimo commit da branch que estou (no caso a "main") para o repositório do git nomeado de "origin". O "remote" só é necessário utilizar uma vez, então o proximo push pode ser apenas "git push origin main"

O comando "git checkout -b "novo-botao" " serve para criar uma nova branch, tendo o "checkout" para ja sair da branch atual em que estou

Quando se está em uma nova branch, é necessário dar o push com o nome dela, nesse caso "git push origin novo-botao"

"git checkout main" utilizado para mudar para a branch que quiser (nesse caso para a main)

Para unir a branch com a main, é necessario estar na branch principal e dar um "git merge nome-da-branch" para uni-las. Após isso, basta dar dar o push

O "git clone (link do repositorio)", como o proprio nome diz, serve para poder clonar o repositório de alguem, para sua modificação