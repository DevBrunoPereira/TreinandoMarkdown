# Estudo de comandos Git

> Criando o primeiro repositorio GIT
- Crie uma pasta onde sera criado o projeto.
- Comando usando no linux `mkdir` "nome_do_arquivo"
- Comando para entrar no arquivo: `cd` "nome_do_arquivo"
> Comando Inicial - `git init` 
- O comando `git init` da inicio ao repositorio.
> Configurando o repositorio:
- `git config --global user.name "Bruno Pereira  dos Santos"`
- `git config --global user.email "dev.bruno.pereira@gmail.com`
> Verificando qual o status  do repositorio
- Para verificar como se encontra o seu repositorio você deve digitar o comando `git status`
> Adicionando arquivo ao controle de versão
- Para adicionar seu arquivo ou alteração de codigo no repositorio é só digitar o seguinte comando: `git add "nomeDoArquivo"`
- No caso de mais de um arquivo podemos usar o comando `git add .`
> Primeiro Commit
- Para criar commits devemos usar o seguinte comando: `git commit -m "comentario do que foi feito no codigo"`
> Como enviar alterações usando `git push`
- O comando `git push` usado para enviar o conteúdo do repositório local para um repositório remoto.    
- O Comando que mais uso é `git push origin master`
- `git push` (_remot_ ) (_branch_)
> comando `git fetch`
- É o oposto do `git push` onde inporta commits para o branches local.
> Verificando o historico de commits
- Você pode verificar o historico de commits usando o comnado `git reflog`.