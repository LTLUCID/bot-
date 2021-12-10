{
  "name": "LUCID",
  "version": "0.0.0-development",
  "author": "Lucid ",
  "keywords": [
    "github",
    "hubot",
    "campfire",
    "bot"
  ],
  "description": "A simple helpful robot for your Company",
  "license": "MIT",
  "repository": {
    "type": "git",
    "url": "https://github.com/hubotio/hubot.git"
  },
  "dependencies": {
    "async": ">=0.1.0 <1.0.0",
    "chalk": "^1.0.0",
    "cline": "^0.8.2",
    "coffeescript": "1.6.3",
    "connect-multiparty": "^2.1.1",
    "express": "^4.16.3",
    "log": "1.4.0",
    "optparse": "1.0.4",
    "scoped-http-client": "0.11.0"
  },
  "devDependencies": {
    "chai": "~2.1.0",
    "coveralls": "^3.0.2",
    "is-circular": "^1.0.2",
    "mocha": "^5.2.0",
    "mockery": "^1.4.0",
    "nyc": "^13.0.0",
    "semantic-release": "^15.9.3",
    "sinon": "~1.17.0",
    "sinon-chai": "^2.8.0",
    "standard": "^10.0.2"
  },
  "engines": {
    "node": "> 4.0.0",
    "npm": "> 2.0.0"
  },
  "main": "./index",
  "bin": {
    "hubot": "./bin/hubot"
  },
  "scripts": {
    "start": "bin/hubot",
    "pretest": "standard",
    "test": "nyc --reporter=html --reporter=text mocha",
    "coverage": "nyc report --reporter=text-lcov | coveralls",
    "test:smoke": "node src/**/*.js",
 #not my code 
 
