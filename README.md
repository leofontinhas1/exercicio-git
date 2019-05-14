Boas práticas de versionamento

- Commits pequenos e devidamente descritos

- Backup das versões separadas por tag devem ser mantidas em um repositório remoto 

- Assegurar que os commits não causem quebra na build do projeto

- Revisar as alterações antes de efetuar o commit

- Fazer integrações frequentemente


Principais funcionalidades 

- Iniciar repositorio em branco -> git init
(dentro da pasta do projeto)

- ver o status de situação dos arquivos no índice -
   git status

-  incluir arquivos ao repositorio git -
    git add <file>

- incluir todos os arquivos, diretorios e subdiretorios dentro do indice -
   git add .

- comitar -
    git commit -m "sua mensagem aki"

- ver todos os commits que ja foram realizados nesse projeto -
    git log

- Desfazer alterações no arquivo -
    git checkout -- <file>

- Tirar um arquivo do índice -
    git reset HEAD <file>

- voltar com o commit -
   git reset HEAD ~1 --hard (para voltar 1 versão e retirar o commit)

- Mostra todos os commites que ja foram realizados,
 inclusive os que foram 'arrancados com o --hard' -
   git reflog

- voltar com o commit para o índice -
    git reset HEAD~1 --soft

- Remover permanentemente todos os untracked files -
   git clean -f

- Listar todos os branch -
 git branch

- novo branch -
  git checkout -b <nome_do_branch> 

- alternar entre os branch -
   git checkout <nome do branch>

- Mandar de um branch para o master
   git rebase <nome do branch> (dentro do master)  

- Remover um branch
   git branch -d <nome do branch>

- Adicionar automaticamente os modificados e dá o commit
   git commit -a -m "Sua mensagem aki"

- pegar todos os commits de um branch e agrupar em apenas um no master.
   git merge <branch> --squash (no master)


- Deleta o branch mesmo se ele estiver diferente do master
    git branch -D

- 'Remendar' o ultimo commit realizado com outras alterações
    git commit -m "sua mensagem aki" --amend

- Gerar uma tag
 git tag add <nome da tag>

-  Adicionar repositorio remoto
    git remote add origin <caminho>

- Empurrar os dados para o repositorio central
    git push

- Pegar todas as atualizaçoes do repositorio
    git pull origin

- Clonar o repositorio central
(dentro da pasta de destino vc digita)
    git clone c:/caminho/

