# Básico de Git e Github

Este repositório tem anotações sobre as diferenças entre Git e Github e comandos básicos de Git

## Diferenças

- Git é um sistema de controle de versão;
- Github é uma plataforma online de compartilhamento de código, que pode ser utilizada, entre outras coisas, como um repositório remoto do Git.

### Comandos básicos do Git

```bash
git init # Cria um repositório local do Git e cria uma branch master
git config --global user.name "Herley Oliveira" # configura o nome do usuário no git globalmente (em todos os repositórios do git, se quiser configurar apenas no repositório atual, então substituir o trecho "--global" por "--local" )
git config --global user.email "herleyoliveira19@gmail.com" # configura o email do usuário no git globalmente (em todos os repositórios do git, se quiser configurar apenas no repositório atual, então substituir o trecho "--global" por "--local" )
git clone <endereço do repositório remoto> # Faz uma cópia do repositório remoto do Git para sua máquina local
git branch # Lista as branchs (pilhas ou ramificações) que exisem no seu repositório local
git checkout -b <nome-da-branch> # Cria uma nova brach, cópia da branch atual
git status # Mostra se há alterações
git add <nome do arquivo ou -A para todos arquivos modificados> # Adiciona arquivos alterados em stage
git commit -m "descrição da alteração feita" # Cria uma nova versão dos arquivos em stage
git push origin <nome-da-branch> # Envia cópia da branch atual para repositório remoto
git pull origin <nome-da-branch> # Puxa uma cópia da branch que está no repositório remoto para o repo local 
git merge <nome da branch> # tras as alterações da outra branch para branch atual 

```

### Comandos básicos de Comunicação do github

```bash
feat: # Quando eu construo um novo recurso no meu projeto
fix: # utilizo para correção de bug para o usuário
docs: # Quando há algumas mudanças na documentação
style: # é usado para formatação, vírgula faltando etc...
refactor: # utilizo quando refatorar código de produção
test: # utilizo quando adicionar testes ausentes, refatorar testes
chore: # quando há atualizações nas tarefas, sem modicação de código

```