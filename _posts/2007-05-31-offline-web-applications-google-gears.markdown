---
theme:
  name: twitter
author: alexandre
comments: true
date: 2007-05-31 13:31:48
layout: post
slug: offline-web-applications-google-gears
title: Offline web applications - Google Gears
wordpress_id: 138
tags:
- Ferramentas
- Web
- Google
---

A **Google** acabou de lançar uma nova API chamada  [Google Gears](http://code.google.com/apis/gears/). Esta é uma API  composta por três módulos:



	
  * **LocalServer:** permite que uma aplicação web crie um cache controlado pela aplicação. Desta forma, as solicitiações de URLs realizadas presentes no cache do LocalServer são interceptadas e atendidas localmente, através do disco do usuário (armazena arquivos HTML, JavaScript, imagens, etc);

	
  * **Database**: provê um "banco de dados" relacional armazenado localmente, utilizando o [SQLite](http://www.sqlite.org). O acesso ao banco se dá via JavaScript;

	
  * **WorkerPoll:** permite executar código JavaScript em background, sem bloquear a execução do script da página principal.


Para utilizar a API, o cliente deve baixar um plugin (disponível somente para **Firefox** e **IE**). A idéia da API parece bastante interessante, e acredito irá gerar uma nova categoria de aplicações **web**. Simultaneamente ao lançamento desta API, o pessoal do [GoogleReader](http://www.google.com/reader) lançou a funcionalidade de navegação offline. Ao utilizar esta funcionalidade, o **GoogleReader** faz o download dos últimos 2000 items do seu feed, e vc passa a acessá-los localmente. Assim, você pode conectar seu notebook à internet, baixar os últimos post da sua lista, e ir para o clube, tomar uma cervejinha, e ainda ler as novidades. Ou então, em empresas cmo limitações de banda, você pode chegar de manhã, baixar tudo, e ir lendo durante o dia as novidades **offline**, sem consumir banda. É claro que para algo como o **GoogleReader**, esta economia é pequena ... mas imagine as possibilidades para novas aplicações que surgem ...


Powered by [ScribeFire](http://scribefire.com/).
