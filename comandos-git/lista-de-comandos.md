# Lista de Comandos

## Comandos Essenciais

- Quando **git init** é usado, de fato estamos iniciando um repositório (pasta) no Git.
- Para criar uma pasta: **mkdir (nome da pasta)**
- Para navegar entre as pastas: **cd (nome da pasta)**, e para retroceder: **cd ..**
- O comando **git status**, ajuda a saber justamente o status dos arquivos, se estão untracked, unmodified, etc.
- Para mover um arquivo para outro repositório: **mv (nomedoarquivo.formato) ./nomerepositorio/**
- O comando **git add** \* ou **git add .** ou **git add -A**, serve para adicionar todos os arquivos do repositório local e os colocam na área de stage, para a realização do commit.
- Para fazer um commit: **git commit -m "digitar mensagem"**

## Para empurrar o repositório para o GitHub:

1. Para adicionar a origem do repositório

```git
git remote add origin https://github.com/username/nome-repositorio.git
```

2. Para listar os repositórios remotos existentes cadastrados

```git
git remote -v
```

3. Para mudar a Branch para Main

```git
git branch -M main
```

4. Para "empurrar" o repositório local para o repositório remoto

```git
git push origin main
```

## Resolver conflitos de Merge

1. Para puxar as alterações feitas por outra pessoa, no repositório remoto:

```git
git pull origin main
```

2. Para adicionar a área de stage:

```git
git add *
```

3. Para realizar o commit, com as alterações feitas e resolvendo os conflitos de merge:

```git
git commit -m "comentário"
```

3. Para empurrar para o repositório do GitHub, com a versão mais atual do código:

```git
git push origin main
```

## Clonar repositórios do GitHub

Comando HTTPS:

```git
git clone (link https)
```
