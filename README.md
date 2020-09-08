# Git-Comandos
Este repo é totalmente focado em reunir a maior quantidadade possível de comandos git e seus respectivos engenhos

##### Criar uma Branch nova
    git checkout -b <Nome da nova branch> 
O comando acima também mudará o apontador(HEAD) da branch em que você está trabalhando para a nova branch

 ou

#####
    git branch <Nome da nova branch>
Esse comando não mudará o apontador, apenas criará uma nova branch a partir da branch em que o apontador está.


##### Trocar o apontador(HEAD) da branch em que você está trabalhando
    git checkout <Nome da branch>

Caso a branch não exista acontecerá um erro

##### Deletar localmente uma Branch
    git branch -d <Nome da branch local>

##### Deletar remotamente uma Branch
    git push origin --delete <Nome da branch remota>
