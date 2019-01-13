Comandos Essenciais Git

## Configurar usuário
$ git --global user.name "NOME DO USUÁRIO" 
// configura usuário
$ git --global user.email "EMAIL DO USUÁRIO"
// configura email


## Criando repositorio e enviando arquivos.
# crie um repositório no github.com
$ git init         
// inicia repositorio
$ git remote add origin https://github.com/usuário/repositorio-criado.git  
// sincroniza com o repositório remoto
$ git status       
// monitora as mudanças
$ git add nome-do-repositorio
// adiciona arquivo no git
$ git commit -m "mensagem referente o envio"
// envia uma mensagem referente ao arquivo modificado e enviado
$ git push origin -u master
// envia o arquivo para repositorio remoto



## Enviar arquivos atualizados
$ git add nome-do-repositorio
// adiciona arquivo no git
$ git commit -m "mensagem referente o envio"
// envia uma mensagem referente ao arquivo modificado e enviado
$ git push 
// envia o arquivo modificado


# CONTRIBUINDO EM PROJETOS OPENSOURCE

- Fazer fork do repositorio

- git clone urldorepositorio // clona o repositorio

- git checkout -b nomedabranch   // cria branch 

- git status  // mostra o status com as modificações de arquivos

- git add nomedoarquivo // adiciona o arquivo

- git commit -m "Aqui vai uma pequena mensagem"  // commit do da nova modificação 

- git remote -v // mostra os arquivos remotos

- git push origin // envia o arquivo caso de erro usar o comando abaixo para o enviar o novo branch

- git push --set-upstream origin patch-0 // push do arquivo para repositorio

- git log // log com informações das modificações enviadas para a master





