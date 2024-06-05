# Resumo comandos git
- **git config init.defaultBranch**: retorna o nome da nossa branch padrão.
- **git config --global init.defaultBranch nome_alterado**: altera **globalmente** o nome da branch padrão para **nome_alterado**.
- **git config --global credential.helper cache**: salva temporariamente as credenciais **(nome do usuário e token)** na nossa máquina no escopo global.
- **git config --global credential.helper**: retorna o valor armazenado em **credential.helper**.
- **git config --global credential.helper store**: salva permanentemente as credenciais **(nome do usuário e token)** na nossa máquina no escopo global.
  
- **git init**: inicia um repositório.
- Primeira vez que for usar o repositório:
  - **git config --global user.email "nome@email.com"** :  configuração do email para o repositório.
  - **git config --global user.name "nome"**: configuração do usuário para o repositório.

- **git add "nome arquivo": irá adicionar o "nome arquivo"** para a staged area.
- git add * e **git add .** : irá adicionar todos os arquivos dentro do repositório para a staged area.
- **git commit -m "mensagem"**: irá efetivar todas as alterações, criando um "Produto final".
- **git remote add origin "Endereço http do repositório"**: irá linkar o repositório GitHub ao repositório local.
- **git push origin master**: irá enviar  os arquivos/modificações para o repositório remoto.
- **git pull origin master**: irá pegar todos os arquivos/modificações do repositório remoto e enviar para o repositório local.

- **git clone "Endereço http do repositório"**: irá enviar para a máquina local, todo um repositório.  Dessa forma, o repositório já vem configurado para o uso git.

   

