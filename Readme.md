Projeto para aprender o git/github
Isso é uma alteração

git init
git add   (git add . para adicionar tudo)
git commit -m "mensagem para commitar"
git remote add origin link (fazer a conexão do git com github)
git push -u origin main    ( para mandar o arquivo par ao github)

git pull, ele irá puxar todas as alterações feitas no repositório do Github para o seu repositório local

Merge:
Ir para a nossa branch principal 'git checkout main' e lá faremos o merge com a branch 'nome da branch' que criamos, com 'git merge nome da branch'

Pronto, agora tudo o que tinha de alteração na branch 'nome da branch' juntou com a 'main'

Branches:
git checkout -b "nome da branch"
git checkout "nome da branch" (para entrar na branch)
git push origin nome da branch (envia a branch para o github)
