# Saúde mais

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.


# NOME PROJETOS

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/a9f549fe009d410f807065fce0f17bf4)](https://www.codacy.com/app/tiagohs/PopMovies?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=tiagohs/PopMovies&amp;utm_campaign=Badge_Grade)
[![Build Status](https://travis-ci.org/tiagohs/PopMovies.svg?branch=master)](https://travis-ci.org/tiagohs/PopMovies)

### <a href="https://github.com/tiagohs/PopMovies-iOS">Clique aqui</a> para conhecer a versão iOS desse App!

<p>Uma rede social de filmes relativamente simples, onde você pode:</p>

<ul>
<li>Login com Facebook, Twitter ou Google, obtendo estátisticas de quantas horas você já gastou assistindo filmes, além de saber os seus gêneros favoritos;</li>
<li>Marcar seus filmes favoritos, quais filmes você já assistiu, os que quer assistir e os que não quer ver nunca;</li>
<li>Obter Rankings no IMDB, Rotten Tomatoes e Metascore;</li>
<li>Obter reviews do IMDB, Rotten Tomatoes e da Comunidade TMDB;</li>
<li>Obter informações sobre os atores, diretores e produtores, incluindo suas filmografias;</li>
<li>Assistir trailers originais, legendados ou dublados;</li>
<li>Visualizar e baixar Walpapers de vários filmes em diversas Qualidades;</li>
</ul>

<b>Donwload do APK</b>: Vá para a página de releases e baixe a última versão: <a href="https://github.com/tiagohs/PopMovies/releases">DOWNLOAD</a>

<p align="center">
  <img src="https://raw.githubusercontent.com/tiagohs/PopMovies/master/arts/gif.gif" width="360" height="640">
</p>

### Configuração:

Antes de usar, você deverá preenxer no arquivo gradle.properties os seguintes campos:
<ul>
<li>MOVIEDB_API="" -> API Key do <a href="https://www.themoviedb.org/">theMovieDB.org</a></li>
<li>TWITTER_SECRET="" -> Secret Token para realizar o Login com o <a href="https://apps.twitter.com/">Twitter com o Fabric</a></li>
<li>TWITTER_KEY="" -> Key para realizar o Login com o <a href="https://apps.twitter.com/">Twitter com o Fabric</a></li>
<li>GOOGLE_KEY="" -> API Key para abrir os <a href="https://developers.google.com/youtube/android/player/?hl=pt-br">vídeos com o Youtube </a></li>
</ul>

Além diso, no Arquivo string.xml, adicione no campo "facebook_app_id" o id do Facebook, para o login utilizando a rede social funcionar corretamente.


### Base de Dados:
<ul>
<li><a href="https://www.themoviedb.org/"><b>TheMovieDB</b></a> - The Movie Database (TMDb) is a popular, user editable database for movies and TV shows.</li>
<li><a href="https://github.com/jvanbaarsen/omdb"><b>OMDB API</b></a> - The OMDb API is a free web service to obtain movie information, all content and images on the site are contributed and maintained by our users.</li>
</ul>

### Padrões de Projetos Adotados:

<ul>
<li><a href="http://antonioleiva.com/mvp-android">MVP</a> - Model View Presenter.</li>
</ul>

### Libaries utilizadas nesse Projeto:

<ul>
<li><a href="https://github.com/ReactiveX/RxAndroid">RxAndroid 2</a> - RxJava bindings for Android </li>
<li><a href="https://github.com/ReactiveX/RxJava">RxJava 2</a> - Reactive Extensions for the JVM – a library for composing asynchronous and event-based programs using observable sequences for the Java VM. </li>
<li><a href="https://github.com/square/retrofit">Retrofit 2</a> - Type-safe HTTP client for Android and Java by Square, Inc.</li>
<li><a href="https://github.com/square/dagger">Dagger 2</a> - A fast dependency injector for Android and Java.</li>
<li><a href="https://github.com/JakeWharton/butterknife">Butterknife</a> - Bind Android views and callbacks to fields and methods.</li>
<li><a href="https://github.com/square/picasso">Picasso</a> - A powerful image downloading and caching library for Android .</li>
<li><a href="https://github.com/google/gson">Gson</a> - A powerful image downloading and caching library for Android. </li>
<li><a href="https://github.com/FasterXML/jackson-core">Jackson</a> - Core part of Jackson that defines Streaming API as well as basic shared abstractions <a href="http://wiki.fasterxml.com/JacksonHome">http://wiki.fasterxml.com/JacksonHome</a>. </li>
<li><a href="https://github.com/afollestad/material-dialogs">Material-dialogs
</a> - A beautiful, fluid, and customizable dialogs API. </li>
<li><a href="https://github.com/jd-alexander/LikeButton">LikeButton</a> - Twitter's heart animation for Android. </li>
<li><a href="https://github.com/square/okhttp">okhttp</a> - An HTTP+HTTP/2 client for Android and Java applications. </li>
<li><a href="https://github.com/balysv/material-ripple">Material Riple</a> - Android L Ripple effect wrapper for Views. </li>
<li><a href="https://github.com/lopspower/CircularImageView">CircularImageView</a> - Create circular ImageView in Android in the simplest way possible. </li>
<li><a href="https://github.com/amulyakhare/TextDrawable">TextDrawable</a> - This light-weight library provides images with letter/text like the Gmail app. It extends the Drawable class thus can be used with existing/custom/network ImageView classes. Also included is a fluent interface for creating drawables and a customizable ColorGenerator. </li>
<li><a href="https://github.com/chrisbanes/PhotoView">PhotoView</a> - Implementation of ImageView for Android that supports zooming, by various touch gestures. </li>
<li><a href="https://github.com/pnikosis/materialish-progress">Material-ish Progress</a> - A material style progress wheel compatible with 2.3. </li>
<li><a href="https://github.com/syedowaisali/crystal-range-seekbar">Crystal Range Seekbar</a> - An extended version of seekbar and range seekbar with basic and advanced customization. </li>
</ul>

## Screens

<p align="center">
<img src="https://raw.githubusercontent.com/tiagohs/PopMovies/master/arts/login-screen.png" width="280" height="540"> <img src="https://raw.githubusercontent.com/tiagohs/PopMovies/master/arts/image_lancamentos.png" width="280" height="540">
<img src="https://raw.githubusercontent.com/tiagohs/PopMovies/master/arts/image_movies_list.png" width="280" height="540">
</p>

<p align="center">
<img src="https://raw.githubusercontent.com/tiagohs/PopMovies/master/arts/image_estatisticas.png" width="280" height="540"> <img src="https://raw.githubusercontent.com/tiagohs/PopMovies/master/arts/image_filme.png" width="280" height="540">
<img src="https://raw.githubusercontent.com/tiagohs/PopMovies/master/arts/midia-screen.png" width="280" height="540">
</p>

<p align="center">
<img src="https://raw.githubusercontent.com/tiagohs/PopMovies/master/arts/image_persons_list.png" width="280" height="540"> <img src="https://raw.githubusercontent.com/tiagohs/PopMovies/master/arts/image_search.png" width="280" height="540">
<img src="https://raw.githubusercontent.com/tiagohs/PopMovies/master/arts/image_person.png" width="280" height="540">
</p>

<p align="center">
<img src="https://raw.githubusercontent.com/tiagohs/PopMovies/master/arts/image_wallpaper.png" width="280" height="540"> <img src="https://raw.githubusercontent.com/tiagohs/PopMovies/master/arts/genres-screen.png" width="280" height="540">
<img src="https://raw.githubusercontent.com/tiagohs/PopMovies/master/arts/image_perfil.png" width="280" height="540">
</p>

<p align="center">
<img src="https://raw.githubusercontent.com/tiagohs/PopMovies/master/arts/tablet-2.png" width="800" height="538">
</p>

### Desenvolvido por:

Tiago Henrique da Silva - tiago.hsilva@al.infnet.edu.br / tiago.silva.93@hotmail.com

<p><a href="https://www.facebook.com/tiago.henrique.16">
  <img alt="Follow me on Facebook" src="https://image.freepik.com/free-icon/facebook-symbol_318-37686.png" data-canonical-src="https://image.freepik.com/free-icon/facebook-symbol_318-37686.png" style="max-width:100%;" height="60" width="60">
</a>
<a href="https://br.linkedin.com/in/tiago-henrique-395868b7">
  <img alt="Add me to Linkedin" src="http://image.flaticon.com/icons/svg/34/34405.svg" data-canonical-src="http://image.flaticon.com/icons/svg/34/34405.svg" style="max-width:100%;" height="60" width="60">
</a>
<a href="http://tiagohs.net/">
  <img alt="Site Portfolio" src="https://raw.githubusercontent.com/tiagohs/PopMovies/master/arts/portfolio.png" data-canonical-src="https://raw.githubusercontent.com/tiagohs/PopMovies/master/arts/portfolio.png" style="max-width:100%;" height="60" width="60">
</a></p>

## License

    Copyright 2015 Tiago Henrique da Silva

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.








meninos da ADS

<h1 align="center">
    <img alt="FuelSupply" title="FuelSupply-logo" src="./assets/logo.png" width="180px" />
</h1>

<h1 align="center">FuelSupply</h1>

<p align="center">FuelSupply o projeto para mudar a maneira de compra e vender combustiveis</p>

<h4 align="center"> 
	🚧  Em construção...  🚧
</h4>

Tabela de conteúdos
=================
<!--ts-->
   * [Tabela de Conteudo](#tabela-de-conteudo)
   * [Sobre](#Sobre)
   * [Features](#Features)
   * [Como usar](#como-usar)
      * [Pre Requisitos](#pre-requisitos)
      * [Como Instalar](#como-instalar)
   * [Tecnologias](#tecnologias)
<!--te-->

## 💻 [Sobre](#Sobre)

O projeto FuelSupply é um projeto para a materia de projeto integrador de turma do 5º termo de ADS 2021 da Unimar - Universidade de Marília, professor Victor Borba.

Este projeto visa conectar consumidores que querem ecomizar consumidores que desejam ecomizar no abastecimento de veiculos, e postos de combustiveis que visam vender mais.

Os postos de combustiveis poderam:

- Se cadastrar na aba web do projeto 
- Cadastrar e editar os combustiveis disponiveis para venda
- Acompanhar as vendas de credito de combustiveis
- Editar as informações do seu cadastro
- Efetuar o checkout do uso do credito junto ao consumidor no momento do abastecimento

Os consumidores poderam: 

- Se cadastrar através do aplicativo
- Editar seus dados cadastrais 
- Efetuar a compra do credito de combustivel
- Acompanhar o historico de compras e utilizações dos creditos
- Efetuar o checkout do credito no momento do abastecimento

## [Features](#Features)

- [x] Cadastro de Posto
- [x] Cadastro de combustiveis
- [x] Edição de combustiveis
- [x] Listagem de vendas
- [ ] Editar informações do Posto
- [ ] checkout Posto da compra de credito

- [x] Cadastro de usuario
- [ ] Editar informações do usuario
- [x] Efetuar compra do credito
- [x] Listagem das compras de credito
- [ ] Listagem das utilizações de credito
- [ ] checkout do usuario no abastecimento


## [Como usar](#como-usar)

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/), [React Native](https://reactnative.dev/), 
[Android Studio + Virtual Device Android >= 9.0](https://developer.android.com/studio), [Docker](https://docs.docker.com/docker-for-windows/install/), [MySQLworkbench](https://www.mysql.com/products/workbench/)
Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)

### 🎲 Rodando o Back End (API)

```bash

#Instanciando mariadb no docker
docker run -p 3306:3306  --name some-mariadb -e MARIADB_ROOT_PASSWORD=my-secret-pw -d mariadb

# Abra o MySQLworkbench e crie a conexão 
Link para ajudar a criar a conexão https://www.youtube.com/watch?v=qa7SWCozY_A

# crie o banco com sql deste Link 
https://drive.google.com/file/d/18a3vpPKT0lKT28bvfA1etXHUGVnWkHf_/view?usp=sharing

# Clone este repositório
$ git clone <https://gitlab.com/unimar-ads/fuel-supply/fuel-supply-app.git>

# Acesse a pasta do projeto no terminal/cmd
$ cd fuel-supply-app

# Vá para a pasta api
$ cd api

# Instale as dependências
$ npm install
$ npm install --save express
$ npm install --save cors
$ npm install --save jsonwebtoken
$ npm install --save morgan
$ npm install --save body-parser
$ npm install --save express
$ npm install --save bcrypt
$ npm install --save mysql

#conectar mysql com a API
link do video para conectar o mysql com a api : https://www.youtube.com/watch?v=642J5YzLXDk

# Execute a aplicação
$ npm start

# o Server vai inicar em  <http://localhost:3000>

# A API também ja esta online no serviço heroku url base: https://fuel-supply-api.herokuapp.com/ 


```

### 💻 Rodando Cliente web

```bash

# Clone este repositório
$ git clone <https://gitlab.com/unimar-ads/fuel-supply/fuel-supply-app.git>

# Acesse a pasta do projeto no terminal/cmd
$ cd fuel-supply-app

# Vá para a pasta web
$ cd web

# Instale as dependências
$ npm install
$ npm install --save vue
$ npm install --save axios
$ npm install --save bootstrap
$ npm install --save vuex

# Execute a aplicação 
$ npm run serve

# A aplicação inciará na porta:8080 - acesse <http://localhost:8080>


```

### 📱 Rodando APP

```bash

# Clone este repositório
$ git clone <https://gitlab.com/unimar-ads/fuel-supply/fuel-supply-app.git>

# Acesse a pasta do projeto no terminal/cmd
$ cd fuel-supply-app

# Vá para a pasta app
$ cd app

# Instale as dependências
$ npm install
$ npm install --save @fortawesome/fontawesome-svg-core
$ npm install --save @fortawesome/free-solid-svg-icons
$ npm install --save @fortawesome/react-fontawesome
$ npm install --save @react-native-async-storage/async-storage
$ npm install --save @react-native-community/masked-view
$ npm install --save @react-native-masked-view/masked-view
$ npm install --save @react-navigation/bottom-tabs
$ npm install --save @react-navigation/native
$ npm install --save @react-navigation/stack
$ npm install --save apisauce
$ npm install --save link
$ npm install --save node-fetch
$ npm install --save react
$ npm install --save react-icons
$ npm install --save react-native
$ npm install --save react-native-elements
$ npm install --save react-native-gesture-handler
$ npm install --save react-native-masked-text
$ npm install --save react-native-reanimated
$ npm install --save react-native-safe-area-context
$ npm install --save react-native-screens
$ npm install --save react-native-vector-icons

# Execute a aplicação 
$ npx react-native run-android

# A aplicação inciará no emulador instalado no Android studio

```

### 🛠 [Tecnologias](#tecnologias)

As seguintes ferramentas foram usadas na construção do projeto:

- [Node.js](https://nodejs.org/en/)
- [React Native](https://reactnative.dev/)
- [Vue.js](https://vuejs.org/)

## Autores

Feito por Emerson Willian,Ana Paula, Willian Santos 👋🏽


## 📝 Licença

Este projeto esta sobe a licença [MIT](https://gitlab.com/unimar-ads/fuel-supply/fuel-supply-app/-/blob/master/LICENSE).


