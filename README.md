Comando do Git

git init: cria um repositório novo git em um diretório pré-existente e cria um subdiretório .git contendo todos os arquivos necessários para o repositório;

git status: mostra o atual estado do repositório, bem como seu arquivos modificados, arquivos novos e arquivos prontos para serem commitados;

git add <filename ou . >: adiciona arquivos ao indíce (staging area) informado e os prepara para o próximo commit;

git rm --cached <file> / git restore --staged <filename ou . >: remove arquivos do indíce (staging area) informado;

git branch: lista todas as branchs que existentes;

git branch -r: lista todas as branchs remotas;

git branch -a: lista todas as branchs remotas e locais;

git checkout <branchname>: muda para a branch escolhida;

git checkout -b <branchname>: cria uma nova branch e muda para a mesma;

git commit -m "<description>": commita as mudanças no índice com uma mensagem descritiva;

git merge <branch>: mescla a branch atual com a selecionada;

git push: envia os commits do repositório local ao repositório remoto;

git branch -D <branchname>: exclui a branch informada;

git fetch: baixa objetos e referências do repositório remoto e atualiza o repositório local com informações do repositório local sem mesclar;

git pull: baixa objetos e referências do repositório remoto e mescla com a atual branch;
