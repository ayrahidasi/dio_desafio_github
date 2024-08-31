# Comandos Git Bash

##### **No Git Bash**

###### LISTAR OS DIRETÓRIOS E ARQUIVOS

 **ls	**

 **ls -a** [mostra arquivos ocultos]

###### MUDAR DEDIRETÓRIO

**cd** dio_desafio_github/

**cd ..** [muda para o diretório pai]

###### INICIALIZAR UM NOVO REPOSITÓRIO GIT

**git init** [cria um repositório]

###### ADICIONAR UM REPOSITÓRIO REMOTO A UM REPOSITÓRIO LOCAL

Primeiramente, crie o repositório no GitHub e copie o link do repositorio

**git remote add origin** link_do_repositório_github

###### CLONAR REPOSITÓRIO

**git clone** https://github.com/ayrahidasi/dio_desafio_github.git

**cd** dio_desafio_github/

###### MOSTRA O STATUS DOS ARQUIVOS NO REPOSITÓRIO

**git status**

###### PUSH DAS ALTERAÇÕES

 **git add .** [todos os arquivos e diretórios]

 **git add *:** [adiciona todos os arquivos]

 **git add** nome_do_arquivo.md pasta/ [adiciona um arquivo específico à área de stage na pasta]

 **git commit -m** "Inclusão das anotações do curso de GIT/GITHUB" [comita as mudanças com uma mensagem descritiva]

 **git push origin main**

###### CRIAR ARQUIVO

 **mkdir** livro_receitas

###### LIMPAR UM ARQUIVO OU CRIAR UM ARQUIVO VAZIO

 **echo >** nome_do_arquivo.md

###### ADICIONAR UM REPOSITÓRIO REMOTO A UM REPOSITÓRIO LOCAL

Primeiramente, crie o repositório no GitHub e copie o link do repositorio

**git remote add origin** link_do_repositório_github

###### EXIBIR OS URLs DOS REPOSITÓRIOS REMOTOS

**git remote -v**

###### ATUALIZA O BRANCH MASTER NO REPOSITÓRIO REMOTO

**git checkout master** [certifique-se você esteja no branch master local]

**git push origin master**


##### Chave SSH


##### Token


##### COMANDOS BÁSICOS

1. **Configuração Inicial** :

* `git config --global user.name "Seu Nome"`: Define seu nome de usuário.
* `git config --global user.email "seuemail@exemplo.com"`: Define seu e-mail.
* **git config --list**

1. **Criar e Clonar Repositórios** :

* `git init`: Inicializa um novo repositório Git.
* `git clone <URL do repositório>`: Clona um repositório remoto para sua máquina local.

1. **Gerenciamento de Arquivos** :

* `git add <arquivo>`: Adiciona um arquivo específico à área de stage.
* `git add .`: Adiciona todos os arquivos modificados à área de stage.
* `git commit -m "mensagem do commit"`: Comita as mudanças com uma mensagem descritiva.

1. **Verificar o Status e Histórico** :

* `git status`: Mostra o status dos arquivos no repositório.
* `git log`: Exibe o histórico de commits.

1. **Trabalhando com Branches** :

* `git branch`: Lista todas as branches.
* `git checkout <nome da branch>`: Troca para a branch especificada.
* `git checkout -b <nome da nova branch>`: Cria e troca para uma nova branch.

1. **Atualizar e Compartilhar Alterações** :

* `git pull`: Atualiza seu repositório local com as mudanças do repositório remoto.
* `git push`: Envia suas mudanças para o repositório remoto.

1. **Outros Comandos Úteis** :

* `git merge <nome da branch>`: Mescla a branch especificada com a branch atual.
* [`git reset --hard`: Desfaz todas as modificações não comitadas](https://gist.github.com/leocomelli/2545add34e4fec21ec16)
