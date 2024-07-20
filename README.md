
# TestesGit

## Formatações do markdown

# Texto h1 ## Texto h2 ### Texto h3

`Bordinha radius fundo`

Três tracinhos cria uma linha "---"

> Comentário

```shell
Códigos
```

[Isso é um link](https://github.com/MathLuz/TestesGit/blob/main/README.md)

---

[Funcionalidades do Markdown](https://wordpress.com/support/markdown-quick-reference/)

[Para estudar branchs](https://git-school.github.io/visualizing-git/)

---

## Comandos do terminal - Git

git init
> Inicia um repositório Git vazio no diretório atual.

git add . / git add -A
> Adiciona todas as alterações no diretório atual para o próximo commit.

git commit -m "Mensagem"
> Cria um commit com as mudanças adicionadas e uma mensagem.

git push origin
> Envia os commits locais para o repositório remoto especificado.

git pull
> Atualiza a branch local com as mudanças do repositório remoto.

git switch [Nome da branch]
> Muda para a branch especificada.

git switch -c [Nome da nova branch]
> Cria e muda para a nova branch

git restore [.] // para voltar a última [--source = id do commit]
> restauda o projeto

git remote add origin [link do repositório]
> Adiciona um link ao repositório remoto com o nome original.

git clone [link do repositório]
> Faz uma cópia de um repositório remoto para o diretório local.

git status
> Mostra o status atual do repositório, incluindo a branch, arquivos modificados, adicionados e excluídos.

git log
> Exibe o histórico de commits do repositório.

[Documentação do git log](https://git-scm.com/docs/git-log/pt_BR)

git rebase main
> Adiona os commit da main na sua branch (antes da atual).

git merge [nome-da-branch]
> Mescla a branch especificada com a branch atual.

git diff [Commit antigo] [Commit novo]
> Mostra as diferenças entre os arquivos no repositório e no diretório de trabalho ou entre commit especificados.

git show [Commit]
> Mostra as diferenças entre o seu diretório local e o commit especificado

git revert [id do commit]
> Cria um novo commit que desfaz as mudanças do commit especificado.

git reset --hard [id do commit anterior ao que eu quero apagar]
> Volta o histórico para o commit especificado e descarta todas as mudanças após esse commit.

git reset --hard HEAD
> Desfaz todas as mudanças não comitadas e restaura o estado do último commit.

git commit --amend -m "Mensagem a substituir"
> Modifica a mensagem do último commit.

git stash
> Deixa as modificações desde o último commit armazenadas.

[Documentação git stash](https://git-scm.com/docs/git-stash/pt_BR)

git tag [Nome da tag] [id co commit] [-m "Descrição da tag"]
> Cria uma marcação (comum usado em versões)

[Documentação git tag](https://git-scm.com/docs/git-tag/pt_BR)


