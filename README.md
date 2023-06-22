# mfds
Tutorial básico de Git e GitHub:

Passo 1: Configurar o Git 
É importante configurar o Git antes de começar com seu nome de usuário e e-mail do GitHub. Você pode fazer isso usando os seguintes comandos no terminal ou no Git Bash:

arduinoCopy code

$ git config --global user.name "seu_usuario_no_github"

$ git config --global user.email "seu_email_do_github"

Passo 2: Iniciar um repositório 
Vá até o diretório onde os arquivos que você deseja estão e execute este comando para iniciar um repositório:

csharpCopy code

$ git init

Passo 3: Adicionar arquivos ao commit 
Existem duas maneiras de adicionar arquivos ao commit:
    • Se você quer adicionar todos os arquivos do diretório atual, use o comando:
    
csharpCopy code

$ git add .

    • Se você quer adicionar apenas arquivos, utileze o comando:
    
csharpCopy code

$ git add nome_do_arquivo

Passo 4: Criar um commit 
Depois de adicionar os arquivos, você pode criar um commit com uma mensagem descritiva. Usando o comando:

rubyCopy code

$ git commit -m "mensagem_do_commit"

Passo 5: Conectar-se ao repositório remoto
Antes de enviar os arquivos para o repositório remoto no GitHub, você precisa conectar o repositório local ao repositório remoto. Usando o comando:

csharpCopy code

$ git remote add origin nome_do_repositorio_remoto

Passo 6: Enviar os arquivos para o repositório remoto
Agora é a hora de você enviar os arquivos para o repositório remoto utilizando o comando:

perlCopy code

$ git push origin branch

Certifique-se de substituir "branch" pelo nome da branch que você deseja enviar.

Feito isso, seus arquivos serão enviados para o repositório remoto no GitHub.
