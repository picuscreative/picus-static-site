[<img width="110" src="https://avatars3.githubusercontent.com/u/38539999?s=200&v=4g" />](https://picuscreative.com)

# picus-static-site

PICUS Static Site is a starter theme based on HTML5 Boilerplate, gulp, Bower, and Bootstrap Sass, that will help you make static sites.

## Requirements

| Prerequisite    | How to check | How to install                   |
| --------------- | ------------ | -------------------------------- |
| Node.js >= 4.5  | `node -v`    | [nodejs.org](http://nodejs.org/) |
| gulp >= 3.8.10  | `gulp -v`    | `npm install -g gulp`            |
| Bower >= 1.3.12 | `bower -v`   | `npm install -g bower`           |

For more installation notes, refer to the [Install gulp and Bower](#install-gulp-and-bower) section in this document.

## Features

- [gulp](http://gulpjs.com/) build script that compiles both Sass, checks for JavaScript errors, optimizes images, and concatenates and minifies files
- [BrowserSync](http://www.browsersync.io/) for keeping multiple browsers and devices synchronized while testing, along with injecting updated CSS and JS into your browser while you're developing
- [Bower](http://bower.io/) for front-end package management
- [asset-builder](https://github.com/austinpray/asset-builder) for the JSON file based asset pipeline
- [Bootstrap](http://getbootstrap.com/)

## Development

Sage uses [gulp](http://gulpjs.com/) as its build system and [Bower](http://bower.io/) to manage front-end packages.

### Install gulp and Bower

Building the theme requires [node.js](http://nodejs.org/download/). We recommend you update to the latest version of npm: `npm install -g npm@latest`.

From the command line:

1.  Install [gulp](http://gulpjs.com) and [Bower](http://bower.io/) globally with `npm install -g gulp bower`
2.  Navigate to the theme directory, then run `npm install`
3.  Run `bower install`

You now have all the necessary dependencies to run the build process.

### Available gulp commands

- `gulp` — Compile and optimize the files in your assets directory
- `gulp watch` — Compile assets when file changes are made
- `gulp --production` — Compile assets for production (no source maps).

## LICENSE

[MIT License](https://opensource.org/licenses/MIT) - [PICUS](https://picuscreative.com)
