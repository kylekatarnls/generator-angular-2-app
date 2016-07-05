# Generator Angular2 App

[![NPM version][npm-image]][npm-url] [![Dependency Status][daviddm-image]][daviddm-url]  [![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/ruffiem/generator-angular-2-app/blob/master/LICENSE)   [![Twitter](https://img.shields.io/twitter/url/https/github.com/ruffiem/generator-gulp-angular2.svg?style=social)](https://twitter.com/intent/tweet?text=Angular2-App:&url=http://ow.ly/qncD301Vw7G)

### What is it ?
Generator Angular2 App is designed to be an application generator for Yeoman providing a full stack working environment for Angular2 (rc 4+) developments.


![alt text][gulp] &nbsp; ![alt text][sass] &nbsp; ![alt text][typescript] &nbsp; ![alt text][live-reload] &nbsp; ![alt text][bower] &nbsp; ![alt text][karma] &nbsp; ![alt text][jasmine] &nbsp; ![alt text][protractor] &nbsp; ![alt text][bootstrap] &nbsp; ![alt text][jquery]

It implements **Gulp**, **Sass**, **TypeScript**, **Live Reload**, **Bower**, **Karma**, **Jasmine**, **Protractor**, **Bootstrap**, **jQuery**, _Jade_, _Dart_, _Angular2 Material_, _TingoDB_, _Ng-React_.

> Tools in italic - if any - are not yet implemented.

### Install

First, install [Yeoman](http://yeoman.io) and angular-2-application-scaffolder using [npm](https://www.npmjs.com/) (we assume you have pre-installed [node.js](https://nodejs.org/)).

```bash
$ npm install -g yo
$ npm install -g generator-angular-2-app
```

Then generate your new project:

```bash
$ yo angular-2-app
```

### Dependencies

Make sure you ran the following command before starting your project:

```bash
$ npm install && bower install && typings install
```

### Launch the development environment

Go to your project and run:

```bash
$ gulp serve
```

This command will run a live reload server and will watch for changes to instantly update your dev distribution.

### Build application for production

Go to your project and run:

```bash
$ gulp build
```

This command will run all the compilation tasks and create a dist/ folder to your root directory with optimized code for production

### Unit testing with Karma

```bash
$ npm test
```

### End-to-end testing with Protractor

```bash
$ npm run e2e
```

### Code coverage with Istanbul

```bash
$ npm run coverage
```

### License

MIT © Michel Ruffieux ([ruffiem](mailto:ruffiem@gmail.com)) and contributors.

[yo]: https://pbs.twimg.com/profile_images/3786155988/46ea2dd8b1bdd31a8ba61044cb5b6ebe_normal.png "Yeoman"
[gulp]: https://pbs.twimg.com/profile_images/417078109075034112/iruTC031_normal.png "Gulp"
[sass]: https://pbs.twimg.com/profile_images/583681608269471744/jCR2zNJV_normal.png "Sass"
[typescript]: https://pbs.twimg.com/profile_images/743155381661143040/bynNY5dJ_normal.jpg "TypeScript"
[live-reload]: https://pbs.twimg.com/profile_images/1650346891/128_normal.png "Live Reload"
[bower]: https://pbs.twimg.com/profile_images/3536632979/66db62603f426a8fc6664081811be6d4_normal.png "Bower"
[karma]: https://pbs.twimg.com/profile_images/420262386352652288/TidYGd6a_normal.png "Karma"
[jasmine]: https://pbs.twimg.com/profile_images/378800000228414878/7c0b595409af531b9cdeb07f8c513e8b_normal.png "Jasmine"
[protractor]: https://pbs.twimg.com/profile_images/444227625389531136/qYHM6E5V_normal.png "Protractor"
[bootstrap]: https://pbs.twimg.com/profile_images/378800000195279414/f8404a9d719c7ffce1478ba1a50036f9_normal.png "Bootstrap"
[jquery]: http://jomboom.com/images/jquery.png "jQuery"

[npm-image]: https://badge.fury.io/js/generator-angular-2-app.svg
[npm-url]: https://npmjs.org/package/generator-angular-2-app.svg
[daviddm-image]: https://david-dm.org/ruffiem/generator-angular-2-app.svg.svg?theme=shields.io
[daviddm-url]: https://david-dm.org/ruffiem/generator-angular-2-app.svg
