# GIT E GITHUB
> Testes de funcionalidades do git e github

Treinando os comandos de usabilidade da ferramenta

![](github.png)

## Comandos úteis

```sh
git init

git add "nome" : exemplo git add index.html

git add .      — adiciona todos arquivos

git commit -m "added landing page"

git commit -am "comentario"    — adiciona e já atualiza

git log

git status

git branch    — lista as branchs
```

### Criar uma branch

git branch feature/cart

git checkout feature/cart

### Criar novo arquivo

touch cart.html

### Voltar para linha do tempo principal

git checkout "master"

### Olhar as linhas do tempo

git checkout

### Verificar os itens no folder

ls -al

git merge feature/cart     —-   precisa estar em alguma outra branch, por exemplo na master

git branch -D feature/cart   —  deletar a branch

### Subindo os arquivos na nuvem

git remote add origin [https://github.com/rafanp/testes-git](https://github.com/rafanp/testes-git)

git remote -v

git push -u origin master







# Templates para o README
_Algumas sugestões de itens a serem adicionados no Readme_

## Release History

* 0.2.1
    * CHANGE: Update docs (module code remains unchanged)
* 0.2.0
    * CHANGE: Remove `setDefaultXYZ()`
    * ADD: Add `init()`
* 0.1.1
    * FIX: Crash when calling `baz()` (Thanks @GenerousContributorName!)
* 0.1.0
    * The first proper release
    * CHANGE: Rename `foo()` to `bar()`
* 0.0.1
    * Work in progress

## Meta

Your Name – [@YourTwitter](https://twitter.com/dbader_org) – YourEmail@example.com

Distributed under the XYZ license. See ``LICENSE`` for more information.

[https://github.com/yourname/github-link](https://github.com/dbader/)

## Contributing

1. Fork it (<https://github.com/yourname/yourproject/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

<!-- Markdown link & img dfn's -->
[npm-image]: https://img.shields.io/npm/v/datadog-metrics.svg?style=flat-square
[npm-url]: https://npmjs.org/package/datadog-metrics
[npm-downloads]: https://img.shields.io/npm/dm/datadog-metrics.svg?style=flat-square
[travis-image]: https://img.shields.io/travis/dbader/node-datadog-metrics/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/dbader/node-datadog-metrics
[wiki]: https://github.com/yourname/yourproject/wiki