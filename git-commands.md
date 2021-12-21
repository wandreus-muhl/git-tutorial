# Comandos GIT

| Comando | Descrição |
| --- | --- |
| `git add` | Adiciona as modificações para a área de *staging* do repositório local |
| `git commit` | Transforma as alterações da área de *staging* em um *commit* |
| `git push` | Envia os *commits* para o repositório central |
| `git merge <branch>` | Mescla as alterações realizadas na `<branch>` com a *branch* do HEAD, criando um *commit* de *merge* |
| `git rebase <branch>` | Mescla as alterações realizadas na `<branch>` com a *branch* do HEAD, entretanto, não gera um novo *commit* |
| `git checkout` | Navega entre estados do repositório |
| `git branch` | Lista todas as *branches* existentes no repositório atual |
| `git checkout -b <branch>` | Cria uma nova *branch* nomeada como `<branch>` e altera o HEAD para a mesma |
| `git branch -d <branch>` | Deleta a `<branch>` informada |
| `git reset` | Descarta as alterações no HEAD adicionadas à área de *staging*. Não descarta as alterações commitadas |
| `git revert <commitId>` | Gera um novo commit revertendo as alterações realizadas no commit `<commitId>` |
| `git stash` | Salva as alterações do HEAD, sem commitá-las |
| `git stash pop` | Recupera a última alteração adicionada à área de *stash*, excluindo-a da área após a recuperação |