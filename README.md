# angular-starter-kit
Starting points for building a new Angular single page app.

# Getting Started

- Install dependencies: `bash npm install`
- Run `gulp serve` to launch default browser and watch for changes
- Run `bower install --save <package>` to install frontend dependencies
- Run `gulp serve:unit_test` to run the unit tests
- Run `gulp serve:dist` to build your webapp for production 

# Features included in gulpfile
- seref : allow configuration of your files in comments of your HTML file
- ngAnnotate : convert simple injection to complete syntax to be minification proof
- angular-filesort: Automatically sort AngularJS app files depending on module definitions and usage
- ng-html2js: pre-load your HTML code into the $templateCache. Please **change your model name** to make it work correctly.
- uglify : optimize all your JavaScript
- csso: optimize all your CSS
- sass: compile sass file to css.
- autoprefixer: Prefix CSS with [Autoprefixer](https://github.com/postcss/autoprefixer-core)
- jshint : JavaScript code linter
- minify-html: Minify html with minimize.
- Unit test (karma) : out of the box unit test configuration with karma
- browser sync : full-featured development web server with livereload and devices sync
- And more...

# Directory structure
The root directory is **app/**
