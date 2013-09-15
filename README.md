# node-quneo

This is a work in progress module for providing some tools to work with a QuNeo controller in node.js land (probably via node-osc, unless you're a masochist).

If you have any ammendments or can improve this, feel free to fork the project, do your magic and then send me a pull request ;-)

## Installing

````bash
npm install quneo
````

## Usage

Include the quneo module and you can then do stuff with its hopefully self-explanative methods.

````javascript
var quneo = require('quneo');

quneo.getPadLedsPath(1, 'green'); // returns /quneo/leds/pads/0/SW/green/

````

## Author

[Soledad Penadés](http://soledadpenades.com)

## Where did this thing come from?

This is extracted from the slide-app-thingie that I made for my JSConf.EU 2013 talk. Get it [here](https://github.com/sole/4x4JS)
