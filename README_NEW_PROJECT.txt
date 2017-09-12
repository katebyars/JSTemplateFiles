Create Index.html
Create .gitignore
Create README.md
Create gulpfile.js
Create js/template.js (add in exports.xxx = ObjectName;) at bottom of .js
Create js/template-interface.js (add in var ObjectName = require('./../js/template.js').ObjectNameModule;

potentials to index.html:
<link rel="stylesheet" href="build/css/vendor.css">
<link rel="stylesheet" href="css/styles.css" type="text/css">
<script src="build/js/vendor.min.js"></script>
<script type="text/javascript" src="build/js/app.js"></script>
<script src="bower_components/jquery/dist/jquery.min.js"></script>
<script src="bower_components/bootstrap/dist/js/bootstrap.min.js"></script>
<script src="bower_components/moment/min/moment.min.js"></script>
<link rel="stylesheet" href="bower_components/bootstrap/dist/css/bootstrap.min.css">
<script src="http://code.jquery.com/jquery-3.2.1.min.js" integrity="sha256-hwg4gsxgFZhOsEEamdOYGBf13FyQuiTwlAQgxVSNgt4=" crossorigin="anonymous"></script>
<script type="text/javascript" src="js/template-interface.js"></script>

$ npm init
$ npm install gulp --save-dev
$ npm install browserify --save-dev
$ npm install gulp -g
$ npm install vinyl-source-stream --save-dev
$ gulp jsBrowserify (generates build folder)
$ npm install gulp-concat --save-dev
$ npm install gulp-uglify --save-dev
$ npm install gulp-util --save-dev
$ npm install del --save-dev
$ npm install jshint --save-dev
$ npm install gulp-jshint --save-dev
$ npm install bower -g
$ bower init
$ bower install jquery --save
$ bower install
$ bower install bootstrap --save
$ bower install moment --save
$ npm install bower-files --save-dev
$ npm install browser-sync --save-dev
$ npm install jasmine --save-dev
$ npm test
$ npm install watchify --save-dev
$ npm install karma --save-dev
$ npm install karma-jasmine jasmine-core --save-dev
$ npm install karma-chrome-launcher --save-dev
$ npm install karma-cli --save-dev
$ npm install karma-browserify --save-dev
$ npm install karma-jquery --save-dev
$ npm install karma-jasmine-html-reporter --save-dev
$ npm install babelify babel-preset-es2015 --save-dev
$ gulp build
$ ./node_modules/.bin/jasmine init
$ gulp jsBrowserify
$ gulp jshint
$ karma init
