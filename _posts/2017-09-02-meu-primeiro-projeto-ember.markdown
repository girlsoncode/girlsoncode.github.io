---
layout: post
title: "Meu Primeiro Projeto Ember"
date: 2017-09-02T19:35:13-03:00
comments: true
footer: true
author: mel
image:
  feature: abstract-7.jpg
  credit: dargadgetz
  creditlink: http://www.dargadgetz.com/ios-7-abstract-wallpaper-pack-for-iphone-5-and-ipod-touch-retina/
share: true
tags: [ember, tutorial]
---

Esse é o primeiro post sobre Ember.js e vamos começar com a mão na massa e criando uma aplicação do zero com este framework.

Para criar a nossa primeira aplicação Ember é necessário instalar o pacote do ember a partir do npm. Digite o seguinte comando no seu terminal:

```shell
$ npm install -g ember-cli@latest
```
Em um próximo post eu vou explicar mais sobre esse pacote `ember-cli`.

Com o ember instalado podemos criar o nossa aplicação utilizando o comando `new` do ember:

```shell
$ ember new ember-first-project
```

Este comando cria uma nova pasta chamada `ember-first-project` e configura uma nova aplicação Ember dentro da pasta da aplicação. Esta aplicação Ember contém um compilador para os templates criados e um servidor de desenvolvimento.

Agora vamos entrar na pasta criada:

```shell
$ cd ember-first-project
```

E vamos executar o servidor de desenvolvimento executando em seu terminal o seguinte comando:

```shell
$ ember server
```

Este comando inicializa um servidor local no endereço `http://localhost:4200/`. Abra o seu browser e digite `http://localhost:4200/` e verá uma página de boas vindas.

Para parar o servidor você pode digitar Ctrl + C em seu terminal.

Você pode ver este projeto [aqui](https://github.com/melderaldo/ember-projects/tree/master/ember-first-project).
