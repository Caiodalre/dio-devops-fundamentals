# Comandos Git Essenciais

Este arquivo reúne os principais comandos Git utilizados durante os estudos da Formação DevOps Fundamentals.

## Configurar usuário Git

```bash
git config --global user.name "Seu Nome"
git config --global user.email "seu-email@email.com"

# Comandos Git Essenciais

Este arquivo reúne os principais comandos Git utilizados durante os estudos da Formação DevOps Fundamentals.

## Configurar usuário Git

```bash
git config --global user.name "Caio Dal Ré"
git config --global user.email "caio_dalre@hotmail.com"

Iniciar um repositório local
git init
Cria um novo repositório Git no diretório atual.

Verificar o status dos arquivos
git status
Mostra arquivos modificados, adicionados ou pendentes de commit

Adicionar arquivos ao controle de versão
git add .
Adiciona todos os arquivos modificados para a área de preparação.

Criar um commit
git commit -m "mensagem do commit"
Registra uma alteração no histórico do projeto.

Clonar um repositório remoto
git clone <url-do-repositorio>
Copia um repositório remoto para o ambiente local.

Criar uma nova branch
git checkout -b nome-da-branch
Cria e muda para uma nova branch.

Listar branches
git branch
Lista as branches existentes no repositório.

Enviar alterações para o GitHub
git push origin main
Envia os commits locais para o repositório remoto.

Atualizar o repositório local
git pull origin main
Baixa as alterações mais recentes do repositório remoto.

Visualizar histórico de commits
git log

Exibe o histórico de commits do projeto.

Clique em:

```text
Commit changes

docs: adiciona comandos Git essenciais
