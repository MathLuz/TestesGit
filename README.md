
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

git checkout [Nome da branch]
> Muda para a branch especificada.

git remote add origin [link do repositório]
> Adiciona um link ao repositório remoto com o nome original.

git clone [link do repositório]
> Faz uma cópia de um repositório remoto para o diretório local.

git status
> Mostra o status atual do repositório, incluindo a branch, arquivos modificados, adicionados e excluídos.

git log
> Exibe o histórico de commits do repositório.

git log --oneline
> Mostra o log de forma resumida.

git log -p
> Mostra o log só que mais detalhado.

git log --help
> Abre a documentação do git log.

git log --format="%H %an"
> Exemplo de formato que mostra o ID do commit e nome de quem comitou.

git branch
> Lista todas as branches no repositório.

git branch [nome-da-branch]
> Cria uma nova branch com o nome especificado.

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
