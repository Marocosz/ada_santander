git config --global user.name "seu_nick"
git config --global user.email seu_email

git clone (link do repositório)  ## Pegar um repositório do github para nosso pc

git init ## Para iniciar o repositório

@@ Estados do git

    - untracked: 
    - unmodified: Já mapeado pelo git, e já commitados, passou pelo estado STAGED
    - modified: O arquivo está com mudanças que não foram commitadas
    - Staged: Área preparatória para o commit,

git status ## Para ver como estão os arquivos de nosso repositório

git add (arquivo que queremos adicionar/atualizar) ## Jogar pra a fase de STAGED

git diff ## Serve para vermos a diferença entre os commits
git diff --stage 

git commit -m "título do commit"  ## Serve para fazermos a snapshot do arquivo

git log  ## Serve para vermos o histórico de commit do repositório

git restore (nome do arquivo) ## Serve para removermos a última alteração
git restore --staged (nome do arquivo)  ## Serve para removermos o último "git add" 

git push (repositorio remoto) (branch) ## Serve para enviarmos as alterações ao repositório remoto

git pull ## Serve para pegarmos as alterações enviadas ao repositório remoto para nosso local, fazendo um murge
