# Git e GitHub

# Configuração inicial

```markdown
$ git config --global user.name "Fulano de Tal"
$ git config --global user.email fulanodetal@exemplo.br
```

# Nomenclaturas

**Commit** - Salvar

**Push** - “Upar” o codigo, “empurrar”, fazer o upload no github

**Pull** -  “Puxar”, “baixar” o codigo do github para a maquina

**Branch** - Ramificação do projeto

**Merge** - junta as branches, ele unifica, mistura

# Comandos

### Versão

`git  --version`

### Inicializar repositório

`git init`

### Adicionando o arquivo .gitignore do c#

`dotnet new gitignore`

### Adicionar arquivo para standing

`git add nomedoarquivo.abc` 

### Adicionar todos arquivos modificados para standing

`git add .`

### Ver mudanças a serem commitadas

`git status`

### Criar um commit

`git commit -m “Frase do commit”`

### Boas praticas (Mudar o nome da branch principal de “master” para “main”)

`git branch -M “main”`

### Histórico de commits

`git log` 

## Criar o repositório remoto no GitHub

### Criar repositório remoto (origin é um apelido para o repositório)

`git remote add origin https://github.com/t3staa/ProjetoGit.git` 

### Fazer o primeiro upload do commit do repositório local para o remoto

`git push -u origin main`

### Fazer upload do commit do repositório local para o remoto

`git push origin main` 

### Criar nova Branch (ramificação).

`git checkout -b “novo-botao”` 

### Fazer upload dos arquivos e modificações na nova Branch

`git push origin novo-botao`

### Mudar de Branch

`git checkout main` 

### Fazer o Merge (unificar Branches)

`git merge novo-botao`

### Clonar repositório

`git clone https://github.com/rafaballerini/GitTutorial.git`

### Pull (puxar o projeto atualizado para a sua maquina)

`git pull`