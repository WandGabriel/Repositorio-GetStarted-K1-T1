# _Comandos GitHub_

Conteúdo criado para auxiliar na memorização de comandos Git.

# _Configurações iniciais_

git config user.name "nome do Usuário"
git config user.email "e-mail do Usuário"

Configurações iniciais de extrema importância na qual será apresentado nos commits.

# Comandos
 git init -> Utilizado para iniciar o projeto git em um repositório local
 git status -> Apresenta o estado atual do projeto local, se está em Working Directory, Staging Area apresentando a ramificação do conteúdo.
 git add -> Envia o projeto local para o Staging Area
 git commit -m "Mensagem descritiva" -> Envia Envia o arquivo da Staging Area para a Commited, assim faltando poucas etapas para o envio ao repositório remoto.
 git push -> Envia o projeto do commited para o repositório remoto.
 git pull -> Verifica se existe atualização no repositório remoto e altera o projeto local, essa etapa faz a alteração direta do projeto, independente se deseja validar o que foi alterado anteriormente.
 git fetch -> Verifica se existe atualização no repositóiro remoto e baixa para o projeto local, contudo nessa etapa não é feito a alteração no projeto, sendo assim é possível valdiar quais são as alteração e caso esteja de acordo com as validações feitas é necessário realizar um Merge.
 git clone -> Realiza uma cópia do repositório remoto a máquina local.
 
Não foram inseridos todos os comando, o arquivo pode sofrer alterações futuras com suas funcionalidades.
