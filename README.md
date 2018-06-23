Stable URL (v2.0.17, 21 March 2016) - http://www.softwareishard.com/har/viewer/

Up-to-date master - http://gitgrimbo.github.io/harviewer/master/ (and [https](https://gitgrimbo.github.io/harviewer/master/))

# HAR Viewer

* Author: Jan Odvarko, odvarko@gmail.com
* http://www.softwareishard.com/
* Issue list: https://github.com/janodvarko/harviewer/issues
* Project home: https://github.com/janodvarko/harviewer

## License

HAR Viewer is free and open source software distributed under the [BSD License](https://github.com/janodvarko/harviewer/blob/master/webapp/license.txt).

## Components

* RequireJS: http://requirejs.org/
* jQuery: http://jquery.com/
* jQuery JSON plugin: Jim Dalton (jim.dalton@furrybrains.com), based on http://www.JSON.org/json2.js
* Domplate + Domplate based templates: http://getfirebug.com
* Downloadify: http://github.com/dcneiner/Downloadify/
* SWFObject 2.0: http://code.google.com/p/swfobject/
* Code Syntax Highlighter: http://alexgorbatchev.com/SyntaxHighlighter/
* JSON Query: https://github.com/JasonSmith/jsonquery, http://www.sitepen.com/blog/2008/07/16/jsonquery-data-querying-beyond-jsonpath/

## Build Tools

* JSDoc: http://usejsdoc.org/
* Node.js: https://nodejs.org/
* ESLint: http://eslint.org/

## Testing

* Selenium: http://seleniumhq.org/
* Intern: https://theintern.io/ (preferred, see [tests](tests/))
* PHPUnit: http://www.phpunit.de/ (deprecated, see [tests](selenium/tests))

## Development

The HAR Viewer build process uses `Node.js` and `npm` as its build tools.

Firstly, run `npm install` from the command line to install the `Node.js`/`npm` dependencies.

### Linting

HAR Viewer uses [ESLint](http://eslint.org/) for linting.  It will be installed when you run `npm install` from the project root.

To show lint errors only:

    npm run eslint

To show lint errors and warnings:

    npm run eslint-full

### Build

Go to the project directory and execute the following command:

`npm run build`

(*Indicative build time - about 12 seconds.  Node.js v10.2.1*)

### JSDoc

Go to the project directory and execute the following command:

`npm run jsdoc`

### Version and Google Analytics

Use the `build.json` file to set the version and Google Analytics profile.
