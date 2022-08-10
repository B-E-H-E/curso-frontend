# Curso-FrontEnd
#### EBAC

# GIT
## Conceitos de versionamento
  - Histórico
  - Controle de versão
  - Quem alterou
  - O que alterou
  - Quando foi alterado
  - Todos os arquivos
  - Evolução contínua
  
Arquivo A | Versão 1 | Versão 2
Arquivo B | Versão 1 | Versão 2

## Instalação do GIT
https://git-scm.com

## Criar conta no GitHub

## Clonar o projeto

##  Commits
Informação de alteração
  - após testado todo seu código
  - git add *
  - git commit -m "mensagem"
  - git push (enviar alterações para o repositório)
  - git pull (trazer alterações do repositório para a máquina)

## Git Flow
Fluxo do Git

### Branches
Ramificações / Versões paralelas
  - Main/Master (Vai para produção, o projeto é publicado)
  - Develop
  - DOD (Definition of Done: critérios de aceite)
  - Versionamento 0.1.10 -> 1.0.0

git checkout -b dev (cria uma branch)
git checkout dev (muda de branch)



### Merge
Mescla de branches
Pode precisar resolver conflitos manualmente

  git merge main

### Pull Requests
  Mescla de branches no repositório
  Permite code review
  Repositório resolve conflitos automaticamente

### Configurar o GitFlow
git flow init
git flow feature start nome-da-feature
