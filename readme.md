# Webpack 4 Boilerplate

> Webpack 4 boilerplate with Babel, Bootstrap 4, jQuery and SCSS on board

## Download

Download in current directory

```sh
$ curl -L -o master.zip https://github.com/hardwit/webpack-boilerplate/archive/master.zip && unzip master.zip && rm master.zip && mv ./webpack-boilerplate-master/* ./ && rm -rf ./webpack-boilerplate-master
```

## Setup

Install dependencies

```sh
$ npm install
```

## Scripts

#### Run the local webpack-dev-server with livereload and autocompile on [http://localhost:8080/](http://localhost:8080/)

```sh
$ npm run dev
```

#### Build the current application for deployment

```sh
$ npm run build

```

#### How to config stylelint
```
конфига читать вот это: https://stylelint.io/user-guide/configuration/
перевод на русском: https://github.com/MerrickGit/material/blob/master/styleLint/02-Rules.md 
https://github.com/MerrickGit/material
https://stylelint.io/user-guide/configuration/
```
### Нужно установить плагин. 	
npm install --save-dev stylelint

### В конфиге vscode
```
	{
	"stylelint.enable": true,
	"css.validate": false,
	"scss.validate": false
	}
```