# dio-desafio-github-primeiro-repositorio
Desafio de Projeto sobre Git/GitHub da Dio

Repositório criado para o desafio de projeto.

## links úteis 
[Sintaxe básica Markdown](https://www.markdownguide.org/)

### comandos github
para subir seus projetos

git init

git add .

git commit -m "first commit"


git remote add origin https://github.com/dawidferreira/exemplo.git

git push -u origin master

Atualizando o repositório
Para atualizar seu repositório, novamente vá para o diretório onde está seu projeto e execute os comandos abaixo:

git init

git status

git add .

git commit -m "novos arquivos inseridos"

git branch -m master main

git push -u origin main

Feito!!!

pull é sempre a abordagem certa, mas uma exceção pode ser quando você está tentando converter um sistema de arquivos sem Git em um repositório Github. Lá você teria que forçar o primeiro commit.

git init

git add README.md

git add .

git commit -m "first commit"

git remote add origin https://github.com/userName/repoName.git

git push --force origin master
