Introdução ao Git e ao GitHub

Comandos CLI

windows		linux
cd			cd
dir			ls
mkdir			mkdir
del / rmdir		rm -rf


SHA1 security hash algorithm - chave 40 digitos
Objetos - blobs tree commits
Sistema distribuído
Segurança

# - command terminal

Chave SSh e Token

#ssh-keygen -t ed25519 -C tlandskron@gmail.com

ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIH+tbaUMva+LL3gwg2bpHf1BmGlOcwj5O4vPKVHYOF6X tlandskron@gmail.com

iniciar o agente ssh
#eval $(ssh-agent -s)

adicionar a chave ssh privada
#ssh-add id_ed25519

token Inspiron 3583 w11
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

#git status

Inicialização do Git
#git init

Git config
#git config --global user.email "[endereco-de-email]"
#git config --global user.name "[nome]"

Adicionar arquivos e pastas no staged
#git add * ou #git add .  ou #git add "file name"

Adcionar os arquivos do staged para unmodified
#git commit -m "mensagem"


Markdown
# Título nível 1
## Título nível 2

**Negrito**
_itálico_

- epsaço aparece bolinha
1. cria a numeração das linhas

remover configurações do config do git
#git config --global --unset user.name
#git config --global --unset user.email

#git config --list

#git remote add origin https://github.com/tlandskron/livro-receitas.git
#git remote -v



conflitos no GitHub
#git pull origin master





