# Simple HTML boilerplate
This is a very simple, bare-bones boilerplate I use to start building webpages quickly.

## index.html
I adapted this from HTML5 boilerplate and updated the pathsto reflect the way I've organized my files.

## Resources
The folders for resources like JavaScript and LESS stylesheets are in semantic folders preceded with an underscore so they stay at the top of my directory, i.e. **/_js** and **/_less**.

## LESS
I happen to use LESS as my compiler of choice. The primary CSS stylesheet **main.css** is compiled from **main.less**, which uses @import to pull in and organize sub-modular LESS files. In **/_less_**, there's a style reset that I dig, along with a file of custom mixins that I frequently use. I'm pretty picky about my mixins, which is why I don't include a comprehensive mixin library. I'll add more as I write them.

## JavaScript
**main.js** is the primary script I use. It's compressed to **main.min.js**, which is included in **index.html**.

## CodeKet
I use CodeKit when I work locally. I may or may not update the boilerplate to use Grunt.js in the future. For now, **codekit-config.json** sets up the project settings in CodeKit and compiles and minifies files to the correct destination.

## Fin
I put this on GitHub to make my life easier and I'll continually update it. Let me know if you find this useful. Hit me up on Twitter [@theJayBeeWhy](http://twitter.com/theJayBeeWhy)