# testando-git-sozinha

### PASSO A PASSO PARA CRIAÇÃO DE NOVO REPOSITÓRIO E ENVIAR ALTERAÇÕES PARA O GITHUB

1. git init
    1. criando o repositório
2. por padrão a branch será a master
3. criar arquivo qualquer na branch master
4. adicionar esses arquivos para a área staging
    1. `git add .`
5. commitar esses arquivos
    1. `git commit -m [mensagemCommit]`
6. adicionar o link do repositório remoto
    1. `git remote add origin [linkRepositorioRemoto]`
7. enviar as alterações que estão no repositório local para o repositório remoto
    1. `git push -u origin master`

### PASSO A PASSO COM REPOSITÓRIO JÁ CRIADO

1. criar nova branch a partir da branch principal e já selecionar a branch criada
    1. `git checkout -b [novaBranch]`
2. adicionar esses arquivos para a área staging
    1. `git add .`
3. commitar esses arquivos
    1. `git commit -m [mensagemCommit]`
4. enviar nova branch para o repositório remoto
    1. `git push origin [nomeBranch]`
5. fazer a junção dos códigos da branch criada para a branch principal. Então deve acessar a branch principal e realizar o merge com o nome da branch que irá enviar as novas alterações
    1. `git merge [branchComNovaAlteracao]`
6. Enviar essas alterações para o repositório remoto
    1. `git push origin master`
