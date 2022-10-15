- git init
- git --version
- git status
- git add . ( ou o arquivo )
- git commit -a -m "ensagem"(-a: add todo tipo de arquivo, -m: add uma mensagem)

# add repository remote

- git remote add origin https://github.com/CaioHayashi/tutorial-git.git
- git branch -M main
- git push -u origin main

## Change branch

- git checkout -b(cria branch)

## Create branch remote repo

- git push --set-upstream origin test

## Unindo os branchs

- git branch (mostra as branchs que tem)
- git checkout main/test (altera para a branch escrita)
- git merge test (uni a branch na main)

## Changes from remote to local

- git pull

## Clone project

- git clone https://github.com/CaioHayashi/tutorial-git.git test(nome)
