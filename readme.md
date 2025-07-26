# Dicas, Referências & Informações pertinentes para as áreas de: Análise e Engenharia de Dados.

## 1. Git & Github, passos para criar repositório (Opção 1).

- Criar nova pasta no computador.
- Abrir pasta no VS Code (Botão direito do mouse e abrir com VS Code, ou pela linha de comando: cmd, git bash, powershell).
- No VS Code, ir em "View >> Terminal" para abrir linha de comando.
- Escrever comando: git init (Foi inicializado um repositório git para controle de versão).
- git config --global user.name "my_name" (Exemplo). 
- git config --global user.email "my_name@email.com" (Exemplo).
- Criar arquivo: README.md

- Abrir perfil do github: github.com
- Ir em: "Repositories >> New" (Criar novo repositório).
- Escolher nome do repositório: exemplo_01
- Clicar no botão: "Create repository"
- git add .
- git commit -m "first commit"
- git branch -M main
- git remote add origin https://github.com/seu_perfil/exemplo_01.git
- git push -u origin main  