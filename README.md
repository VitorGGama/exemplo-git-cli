# Exemplos de operações básicas para git via CLI

## Comandos de uso geral da CLI

-Criar pasta: mkdir  nomepasta
-Listar conteúdo: dir
-Limpar tela: cls
-Entrar na pasta: cd nomepasta

## Comandos principais do git

`git config use.name`  e `git config use.email` 

verificar usuário/email

`git config --global user.name "Vitor Gama"` e 
`git config --global user.email "vitorggam@hotmail.com"`

Mudar usuário e e-mail de forma global.

**obs:** normalmente estes dados estão relacionados ao 
usuário/conta do site GitHub.

`git init` 

Inicializar um repositório (executado dentro da pasta)

`git branch nome-branch-atual novo-nome-para-branch`

Renomear Branches.

Para alterar a branch de **master** para **main** (novo padrão), usariámaos: `git branch master main` 

`git status`

Verificar status atual do repositório

`git add nomearquivo` 

Adicionar (tornar arquivo rastreável) ao monitoramento do git.

`git commit -m "Texto da mensagem sobre esta alteração"`

Fazer commit das alterções (salvar no histórico)

`git remote add origin endereço-do repositorio-git`

Adicionar/conectar o repositório remoto ao local.

`git push origin main`

Enviar as mudanças para o GitHub (PUSH)

`git pull origin main`

Pegar/obter as mudanças do repositório online GitHub (PULL)

`git clone endereço-do-repositório.git`

Copiando/baixando um repositório para a maquina remota.