# Voltar um Commit

Para voltar para o _commit_ anterior, então precisa pegar atual - 1:

```sh
git reset --hard HEAD~1
```

Se quer voltar para algum outro _commit_ específico deve usar o _hash_ dele. Ou em alguns casos pode fazer

```sh
git reset --hard HEAD^
```

Tente com `--soft` antes e veja se resolve o que precisa. Ele é menos radical e mais seguro.

Se o _commit_ já tinha sido enviado terá que forçar no remoto:

```sh
git push origin HEAD --force
```

Isto fará perder todas as alterações locais. Então se não pode perdê-las, sugiro fazer um _stash_ com todas elas antes.

Se der errado pode reverter assim:

```sh
git reset HEAD@{1}
```

Se está com medo de fazer algo errado, faça um _backup_ antes e pode voltar ao original se não sair como esperava (em geral isso não deveria ser necessário porque o objetivo dessa ferramenta é justamente este).

Se quiser fazer no remoto:

```sh
git push origin +HEAD^:master #ou outro nome aqui
```

Se o medo se estende ao servidor remoto, faça o mesmo com ele. Se envolver o servidor remoto, vários cuidados precisam ser tomados, o principal é que seu _branch_ atual deve ser o mais novo do remoto. Se isto não for garantido, estará criando uma realidade alternativa para os demais usuários.

[Leitura recomendável](https://git-scm.com/blog/2011/07/11/reset.html).

[Coloquei no **GitHub** para referência futura](https://github.com/maniero/SOpt/blob/master/Conceptual.md).

FROM: [https://pt.stackoverflow.com/questions/128578/como-excluir-commit-de-um-branch-no-git](StackOverflow)
