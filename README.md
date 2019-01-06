# COMANDOS GIT

Comandos básicos e essenciais para uso em projetos open source

# CONFIGURANDO USUÁRIO

git config --add user.name "Segundo Usuario"

git config --add user.email email@segundaconta.com

REMOVENDO CONFIGURAÇÃO GLOBAL USUÁRIO

git config --global --unset user.name

git config --global --unset user.email

ou 

git config --global --unset-all

ou 

echo -e "host=github.com\nprotocol=https\n" | git credential-osxkeychain erase

git config --unset-all --global user.name

git config --unset-all --global user.email



# CRIANDO UM R3POSITÓRIO

echo "# site-modelo" >> README.md

git init

git add README.md

git commit -m "first commit"

git remote add origin https://github.com/DevAdriana/site-modelo.git

git push -u origin master


OU ENVIA REPOSITORIO EXISTENTE


git remote add origin https://github.com/DevAdriana/site-modelo.git

git push -u origin master



# CONTRIBUINDO EM PROJETOS OPENSOURCE

Fazer fork do repositorio

git clone urldorepositorio // clona o repositorio

git checkout -b nomedabranch   // cria branch 

git status  // mostra o status com as modificações de arquivos

git add nomedoarquivo // adiciona o arquivo

git commit -m "Aqui vai uma pequena mensagem"  // commit do da nova modificação 

git remote -v // mostra os arquivos remotos

git push origin // envia o arquivo caso de erro usar o comando abaixo para o enviar o novo branch

git push --set-upstream origin patch-0 // push do arquivo para repositorio

git log // log com informações das modificações enviadas para a master

# ====================para exclusões de PRs fechadas===================

git checkout master // muda para a branch master

git branch -D nomedabranch // deleta a modificação enviada para a master

# =====================================================================

git fetch

git rebase  upstream/master // busca todos os commits da master e atualiza

git push origin master // enviar as novas modificações para a master






