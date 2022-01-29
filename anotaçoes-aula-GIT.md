# Comandos do GIT
### Setar usuário -
- git config --global user.name "Nome"

### Setar email -
- git config --global user.email "Email"

### Listar configurações 
- git config --list

### Criar novo repositório 
- git init

### Verificar estado dos arquivos/diretórios 
- git status

### Adicionar um arquivo em específico 
- git add meu_arquivo.txt

### Adicionar um diretório em específico 
- git add meu_diretorio

### Comitar um arquivo
- git commit meu_arquivo.txt

### Comitar vários arquivos
- git commit meu_arquivo.txt meu_outro_arquivo.txt

### Comitar informando mensagem
- git commit meuarquivo.txt -m "minha mensagem de commit"

### Remover arquivos 
- git rm meu_arquivo.txt

### Remover diretorio
- git rm -r diretorio

### Exbir Histórico
- git log

### Exibir resumo do histórico
- git log --stat

### Desfazendo alteração local (staging area)
- git reset HEAD meu_arquivo.txt

### Exibir os repositórios remotos
- git remote
- git remote -v

### Vincular repositório local com um repositório remoto
- git remote add origin

### Desvincular um repositório remoto
- git remote rm curso-git

### Enviar arquivos/diretórios para o repositório remoto (PRIMEIRO PUSH)
 - git push -u origin master
 - git push (Demais PUSH)

 ### Atualizar repositório local de acordo com o repositório remoto
 - git pull

 ### Buscar as alterações, mas não aplica-las no branch atual
 - git fetch

### Clonar um repositório remoto já existente
- git clone
 