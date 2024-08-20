# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version 3.2.0
* Rails version 7.1.3.4

* System dependencies

Caso ocorrer alguns erros (como os abaixo listados) ao criar o projeto frontend, através do comando: npm create vite@lastest

npm WARN deprecated object-keys@0.2.0: Please update to the latest object-keys
npm ERR! code ETARGET
npm ERR! notarget No matching version found for ionic-native@^3.5.0
npm ERR! notarget In most cases you or one of your dependencies are requesting
npm ERR! notarget a package version that doesn't exist.
npm ERR! notarget 
npm ERR! notarget It was specified as a dependency of 'ionic-hello-world'
npm ERR! notarget 

Passos para resolver o erro acima:
> npm view ionic-native versions
> npm install https://github.com/ionic-team/ionic-native/tarball/v3.5.0

Ver o link da documentação:
https://stackoverflow.com/questions/44331005/npm-error-no-matching-version-found-for


* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
