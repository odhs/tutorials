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
