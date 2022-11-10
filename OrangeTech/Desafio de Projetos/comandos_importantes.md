# Comandos importantes do Git

- git init = inicializa um repositorio seja ele vazio ou nao
- git config --global user.name "xxxxxxxx" (coloca seu nome conforme perfil do github) = atribui o atributo nome as informações passadas.
- git config --global user.email "xxx@xx.com" (coloca seu email conforme utilizado na conta do github) = atribui ao atributo email as informações passadas.
- git remote add origin url_do repositorio = adiciona o repositorio remoto ao equipamendo local
- git remote remove origin (ou o nome referencia dado para a branch) = remove o repositorio remoto do equipamento local
- git remote -v = mostra o status dos repositorios remotos utilizados
- git status = verifica na branch se tem algum arquivo/pasta alterados e informa sobre realizar suas alterações.
- git add * = adiciona todos os arquivos "staged" para "working"
- git branch = mostra todas as branch criadas
- git branch -d nome_da_branch = deleta a branch indicada no parametro
- git commit -m "comentario" = coloque de forma clara um comentario no estagio final do arquivo/pasta gerado pelo comando
- git push origin master = envia as alterações feitas para o repositorio remoto
- git pull origin master = busca/atualiza informações do servidor remoto para o equipamento local