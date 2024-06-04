git init    
    - Iniciar novo projeto com git

git add .
    - Adicionar os arquivos que estão prontos para ser comitados (commit)

git commit -m ""
    - Comita os arquivos no histórico

git log
    - Mostra os últimos commits, log de alterações

git status
    - Como está o estado da nossa ramificação

git diff
    - O que foi alterado
    - O que tem de alteração na ramificação

git merge
    - Merge de ramificações, mescla ramificações

git branch
    - Mostra a branch atual

git checkout (nome da branch)
    - Muda para essa branch

git checkout -b (nome da branch)
    - Criar uma nova branch a partir da branch atual em que estamos

git checkout -d (nome da branch)
    - Deleta a branch

git remote add (nome) (url)
    - Adiciona um novo repositório remoro

git push (nome) (nome da branch)
    - Manda nossas alterações locais para o repositório remoto, para cada branch

git pull (nome) (nome da branch)
    - Pega as alterações do repositório remoto e joga para nossa máquina

git fetch 
    - Atualiza o novo histórico local de acordo com o histórico salvo no repositório remoto
    - Sincronização do local com remoto 