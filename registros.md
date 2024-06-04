# Comandos Importantes Git

rm -rf (folder); **Exclui à força um diretório.**
mkdir (folder); **Cria um novo diretório.**
touch (folder/file); **Cria um arquivo no diretório passado.**
echo "#(file) > (content); **Cria um arquivo de texto com o nome passado em (file) e seu conteúdo passo em (content).**
git restore (file); **Restaura um arquivo alterado para sua versão anterior**
git log; **Mostra o histórico de commits**
git reflog; **Histórico detalhado das ações realizadas.**
git commit --amend; **Abre o editor de commit**
git commit --amend -m (mensagem); **Altera a mensagem do último commit**
git reset (option); **Restaura um determinado commit. Se não passada uma opção, --mixed é chamada por padrão.**
                    Opções:
                    • --soft (commit ID); **Exclui os commits posteriores ao commit ID passado e transfere os arquivos posteriores a este na área de preparação para serem comitados posteriormente**
                    • --mixed (commit ID); **Exclui os commits posteriores ao commit ID passado. Os arquivos novos/alterados posteriores ao commit são considerados como untracked.**
                    • --hard (commit ID); **Exclui os commits posteriores ao commit ID passado, juntamente com os arquivos novos/alterados.**
git reset (file) ou git restore --staged (file); **Remove um arquivo da área de preparação.**
git remote add origin (link do github); **Conecta o repositório remoto do GitHub (origin) com o repositório local.**
git branch -M (branch name); **Cria uma Branch.**
git push -u origin (branch); **Envia as alterações locais para o repositório remoto. -u = -setupstream.**
git checkout -b (branch name); **Cria uma branch nova e automaticamente muda para aquela branch.**
git branch; **Lista as branchs existentes.**
git branch -v; **Lista as branchs e em qual commit cada uma se encontra.**
git branch -d (branch name); **Dele a branch selecionada.**
git merge (branch name); **Mescla a branch passada em (branch name) com a branch atual.**
git fetch; **Baixa o conteúdo da branch remota sem mesclar com a local.**
