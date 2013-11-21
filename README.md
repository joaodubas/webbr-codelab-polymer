# Codelab de Polymer

Código gerado no [codelab de polymer][codelab] durante a [conferência webbr
2013][webbr].

## Preparando o ambiente

Para rodar o projeto é necessário instalar os seguintes softwares:

* [git][git]: [instruções para instalação][git-install]
* [node][node]: [instruções para instalação][node-install]

Com ambos os programas instalados é necessário fazer o `clone` do projeto:

```bash
$ git clone https://github.com/joaodubas/webbr-codelab-polymer.git
```

Após clonar o projeto, é possível fazer a instalação das dependências:

```bash
$ cd webbr-codelab-polymer
$ npm install
```

## Iniciando a aplicação

Para iniciar o servidor da aplicação use o comando:

```bash
$ cd webbr-codelab-polymer
$ npm start
```

E o seguinte output deve aparecer:

```bash
> webbr-codelab-polymer@0.0.1 start <path>/webbr-codelab-polymer
> node_modules/.bin/nodemon node_modules/.bin/static ./app

21 Nov 09:18:37 - [nodemon] v0.7.10
21 Nov 09:18:37 - [nodemon] to restart at any time, enter `rs`
21 Nov 09:18:37 - [nodemon] watching: <path>/webbr-codelab-polymer
21 Nov 09:18:37 - [nodemon] starting `node node_modules/.bin/static ./app`
serving "./app" at http://127.0.0.1:8080
```

Com o servidor rodando é possível acessar o projeto no seu navegador.

[codelab]: http://goo.gl/ySpHQ0
[webbr]: http://conferenciaweb.w3c.br/#/page/1
[git]: http://git-scm.com/
[git-install]: http://git-scm.com/book/en/Getting-Started-Installing-Git
[node]: http://nodejs.org
[node-install]: https://github.com/joyent/node/wiki/Installation
