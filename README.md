[![Join the chat at https://gitter.im/patrickrb/edGalaxyMap](https://badges.gitter.im/patrickrb/edGalaxyMap.svg)](https://gitter.im/patrickrb/edGalaxyMap?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
# Elite Dangerous Galaxy Map
##Preview: [http://elitedangerousuniverse.com][3]
Built with [Angular][1] and [Three.js][2]

## Getting Started

### Prerequisites

- [Git](https://git-scm.com/)
- [Node.js and NPM](nodejs.org) >= v0.12.0
- [Bower](bower.io) (`npm install --global bower`)
- [Ruby](https://www.ruby-lang.org) and then `gem install sass`
- [Grunt](http://gruntjs.com/) (`npm install --global grunt-cli`)
- [MongoDB](https://www.mongodb.org/) - Keep a running daemon with `mongod`

### Developing

1. Run `npm install` to install server dependencies.

2. Run `bower install` to install front-end dependencies.

3. Run `mongod` in a separate shell to keep an instance of the MongoDB Daemon running

4. Run `grunt serve` to start the development server. It should automatically open the client in your browser when ready.

## Build & development

Run `grunt build` for building and `grunt serve` for preview.

## Testing

Running `npm test` will run the unit tests with karma.


##Contributors

[patrickrb][4]

[csvurt][5]


[1]: https://angularjs.org/
[2]: http://threejs.org/
[3]: http://elitedangerousuniverse.com
[4]: https://github.com/patrickrb
[5]: https://github.com/csvurt
