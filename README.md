Comando do Git

git --version: verifica a versão atual do git;

git config --global user.name & git config global user.email : usados pra configurar o user e email do github do usuário ao git;

ls -al ~/.ssh: usado para verificar se já existe alguma chave ssh configurada no repositório;

ssh-keygen -t ed25519 -C "your_email@example.com": utilizado para adicionar uma nova chave ssh ao repositório;

eval "$(ssh-agen-s)": inicializa um agente-ssh;

ssh-add ~/.ssh/id_ed25519: adiciona a chave ssh ao agente;

clip <~/.ssh/id_ed25519.pub: copia a chave ssh;

github --> settings -->  ssh and gpg keys --> new ssh key --> colar * título que identifique a chave *: adiciona a chave ssh ao github;

ssh -T git@github.com yes: testa a conexão 
