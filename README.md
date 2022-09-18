# Aulas de Git


## Comandos 
`git init` inicia o git   
`git status`- verifica se foi modificado arquivo entre remoto e local   
`git add .` ou `git add +A` adiciona o arquivo a branch   
`git commit -m` faz o comentario   
`git branch` mostra as branch existente   
`git checkout` + nome da branch, muda de beanch 
`git checkout HEAD` Mais nome do arquivo, apaga as modificaçoes do arquivo e restaura para ultima adição     
`git log` Mostra os commits anterior    
`git diff`Mostra a modificação linha a linha do arquivo   
`git diff --name-only` Mostra apenas os arquivos que foram modificado   

   ---   
### Tipos de restore
`git restore` acompanhado do tipo de restore e id do comit
**`git restore --soft`** - restara os arquivos fazendo e da merge com remoto
**`git restore --hard`**  - restaura e substitui o remoto
**`git restore --mixed`**  - restauta porem nao adiciona ao repositorio local