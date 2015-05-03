# sails-hook-dust-exec
Dust.js (Linkedin) helpers that works with [Sails JS](http://sailsjs.org) to be able execute functions in view

### Installation
1. Make sure your Sails app. use [Dust.js](https://github.com/linkedin/dustjs) as template engine
2. Install this hook by `npm install sails-hook-dust-exec`

### Helpers Included
1. `exec`

### Usage
*requires at least sails >= 0.11*

1. Put function in `func` argument, example: `{@exec func="function" /}`
2. Put arguments in `args` parameter if needed, example: `{@i18n func="function" args="['param1','param2']" /}`

### References and Credits
1. [Stackoverflow](http://stackoverflow.com/questions/24368464/call-function-from-dust-template) and that contributed users

### License
MIT
