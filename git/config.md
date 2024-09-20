# Git Config

## Listar configurações

Todas

```sh
   git config list
```

Somente as configurações globais (recomendado)

```sh
   git config --global --list
```

## Configurar usuário

```sh
   git config --global user.name "Nome do Autor"
   git config --global user.email "email do Autor"
```

## Configurar a _branch_ padrão para _main_

```sh
   git config init.defaultBranch main
```

## Abrir a ajuda do comando

```sh
   git config --help
```

# Autenticação

## Criar a chave SSH

Usando o Git-Bash faça:

```sh
   # Cria a chave criptografada
   ssh-keygen -t ed25519 -C "<email@email.com>"
   # Inicia o SSH
   eval `ssh-agent -s`
   # Adiciona a chave ao SSH
   ssh-add ~/.ssh/id_ed25519
```

Adicione a chave pública no Github, Gitlab ou outro serviço Git.

[github.com/settings/ssh/new](github.com/settings/ssh/new)

PS: alternativa para iniciar o SSH: `eval "$(ssh-agenty -s)"`

