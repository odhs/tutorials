# Contribuição com um projeto no Git

## Instruções

1. Faça um **Fork** do repositório que você quer contribuir.
2. Clone localmente `git clone https://github.com/**SEUUSERNAME**/nome-do-repositorio.git`.
3. Adicione o remote upstream para manter seu repositório local atualizado: `git remote add upstream https://github.com/nome-repositorio-original/nome-do-repositorio.git`. Utilize o comando `git pull upstream main` para baixar e mesclar as alterações no seu repositório local com base na branch main deste repositório original de onde você fez o fork, ou `git fetch upstream main` para baixar sem mesclar. Veja mais em: ["Primeiros Passos com Git e GitHub"](https://github.com/elidianaandrade/dio-curso-git-github/blob/main/materiais-de-apoio/03-primeiros-passos-com-git-e-github.md).
4. Crie uma nova **branch** e nomeie como `feat/nome-da-branch/seu-usuario`. Exemplo:

```sh
   git checkout feat/community/odhs
```

5. Faça suas modificações no código.
6. Adicione suas alterações à "staging area" com o comando `git add .`;
7. Crie um commit e adicione a mensagem indicando a adição do seu perfil `git commit -m "feat: add resumo_do_que_vc_fez"`.
8. Envie as alterações para o seu repositório remoto `git push -u origin feat/nome-da-branch/seu-usuario`.
9. Crie um **Pull Request**.

<details align="left">
  <summary></summary>

- Fonte: [https://digitalinnovationone.github.io/dio-lab-open-source/](https://digitalinnovationone.github.io/dio-lab-open-source/)

</details>
