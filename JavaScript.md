JavaScript, Node.js, frontend, and other things related.

2016
----

* [loadjs](https://github.com/muicss/loadjs) - asynchronous JS/CSS loader
* [choices](https://github.com/jshjohnson/Choices) - a vanilla JS customisable select box/text input plugin
* [lru-cache](https://www.npmjs.com/package/lru-cache) - a cache object that deletes the least-recently-used items
* [phantasma](https://www.npmjs.com/package/phantasma) - PhantomJS wrapper
* [nightmare](https://www.npmjs.com/package/nightmare) - browser automation (like PhantomJS), but based on Electron
* [local_modules](https://www.npmjs.com/package/local_modules) - use project files as if they're node_modules
* [baffle.js](https://camwiegert.github.io/baffle/) - obfuscates text
* [dialog-polyfill](https://github.com/GoogleChrome/dialog-polyfill) - modals in 2016
* [tether](https://github.com/HubSpot/tether/) - position elements next to other elements (like tooltips)
* [tape-catch](https://github.com/michaelrhodes/tape-catch) - catch syntax errors in tape tests
* [speakingurl](https://www.npmjs.com/package/speakingurl) - slugify, but aware of locales
* [npm-run-all](https://www.npmjs.com/package/npm-run-all) - run npm tasks in parallel/serial
* [isomorphic-fetch](https://www.npmjs.com/package/isomorphic-fetch) - fetch() for the browser and Node.js
* ~~[got](https://github.com/sindresorhus/got) - better, less-bloated, promise-aware `request`~~ use [isomorphic-fetch](https://www.npmjs.com/package/isomorphic-fetch)
* [cofy](https://github.com/RocksonZeta/cofy) - kinda like 'promisify-all'
* [path-is-inside](https://www.npmjs.com/package/path-is-inside) - check if `/home/me/file.js` is inside `/home/me`
* [sorted-object](https://www.npmjs.com/package/sorted-object) - sort object keys
* [wrappy](https://www.npmjs.com/package/wrappy) - function decorator helper to keep static properties
* [leaked-handles](https://github.com/Raynos/leaked-handles) - check for any leaked timeouts/connections/child processes on tests
* [loud-rejection](https://github.com/sindresorhus/loud-rejection) - die on unhandled promise rejections
* [zenscroll](https://zengabor.github.io/zenscroll/) - scroll things smoothly into view

### React

* [react-select](http://jedwatson.github.io/react-select/) - select box dropdown
* [react-redux-form](http://davidkpiano.github.io/react-redux-form/) - Form helpers for React/Redux

### Browserify

* [exposify](https://github.com/thlorenz/exposify) - alias `window.jQuery` as `require('jquery')`
* [persistify](https://github.com/royriojas/persistify) - browserify-incremental + watchify wrapper
* [concatenify](https://github.com/trodrigues/concatenify) - browserify with Angular.js (among other things)
* [require-globify](https://github.com/capaj/require-globify) - Require globs in Browserify (like `concatenify` but with more control)

### CSS

* [doiuse](https://github.com/anandthakker/doiuse) - check for your minimum browser compatibility
* [precss](https://github.com/jonathantneal/precss) - sass-like syntax for postcss
* [lost](https://github.com/peterramsing/lost) - jeet-like grid in postcss

### ANSI

* [slice-ansi](https://github.com/chalk/slice-ansi) - substring with colors
* [wrap-ansi](https://github.com/chalk/wrap-ansi) - word-wrap with colors
* [chalk](https://www.npmjs.com/package/chalk) - the colorizer to rule them all

### Koa

* [koa-route](https://npmjs.com/package/koa-route) - `app.use(route.get('/post/:id', function * show (id) {}))`
* [koa-rewrite](https://npmjs.com/package/koa-rewrite) - `app.use(rewrite('/post/:id', '/posts/$1'))`
* [koa-static](https://npmjs.com/package/koa-static) - `app.use(koaStatic('public'))`
* [koa-favicon](https://npmjs.com/package/koa-favicon) - `app.use(koaFavicon('public/favicon.ico'))`
* [koa-session](https://npmjs.com/package/koa-session) - `app.use(koaSession(app))` + `this.session`
* [koa-conditional-get](https://github.com/koajs/conditional-get/blob/master/index.js) - return 304 if fresh (for etags and such)
* [koa-response-time](https://npmjs.com/package/koa-response-time) - X-Response-Time HTTP headers
* [koa-rate-limit](https://npmjs.com/package/koa-rate-limit) - rate limiting API's
* [koa-compress](https://npmjs.com/package/koa-compress) - compression
* [koa-logger](https://npmjs.com/package/koa-logger) - logging
* [koa-mount](https://github.com/koajs/mount) - mount Koa apps in Koa apps
* [koa-etag](https://npmjs.com/package/koa-etag) - sets ETag
* [co-body](https://npmjs.com/package/co-body) - body parsing (JSON et al)
* [koa-sslify](https://github.com/turboMaCk/koa-sslify) - force SSL

2015
----

### Misc

* [number-format.js](https://npmjs.com/package/number-format.js) - `format('#,###.##', 1234.56)` → `'1,234.56'`
* [React primer](https://github.com/mikechau/react-primer-draft) (github.com)
* [What have I been missing out on?](http://www.reddit.com/r/webdev/comments/2wuw3v/ive_just_discovered_bootstrapwhat_else_have_i/coueywo) (reddit.com)

### Frontend

* [clipboard.js](http://zenorocha.github.io/clipboard.js/) - copy text to clipboard without flash
* [locally](https://github.com/ozantunca/locally) - localStorage manager with expiration and compression
* [dom4](http://webreflection.github.io/dom4/) - dom level 4 polyfill
* [polyfill.io](https://cdn.polyfill.io/v1/docs/) - polyfill as a service
* [prettyembed](https://github.com/mike-zarandona/prettyembed.js) - embed youtube videos with custom previews and reduced controls
* [zenfonts](https://github.com/zengabor/zenfonts) - font loader with fouc prevention
* [coverr](http://coverr.co/) - videos for your homepage
* [typogr](https://www.npmjs.com/package/typogr) - prettier ampersands and quotes and smartypants
* [vibrant.js](http://jariz.github.io/vibrant.js/) - extract prominent image colors
* [headroom](http://wicky.nillia.ms/headroom.js/) - auto-hiding headers
* [layzr](http://callmecavs.github.io/layzr.js/) - lazy loading images
* [number-grouper](https://www.npmjs.com/package/number-grouper) - simple number formatter
* [malarkey](https://github.com/yuanqing/malarkey) - fancy typer
* [p-promise](https://www.npmjs.com/package/p-promise) - simple promise implementation
* [zeroclipboard](https://www.npmjs.com/package/zeroclipboard) - copy text to clipboard
* [favico.js](http://lab.ejci.net/favico.js/) - favicon badges
* [templayed](https://github.com/archan937/templayed.js/) - old, but very slim mustache loader
* [browser-upgrade-lite](https://github.com/litejs/browser-upgrade-lite) - super lightweight ES5 shim
* [overscroll](http://tholman.com/overscroll/) - easter eggs when scrolling beyond the screen edge
* [vd](https://www.npmjs.com/package/vd) - expressive dom syntax

### JS / Events

* [component-emitter](https://www.npmjs.com/package/component-emitter)
* [riot-observable](https://www.npmjs.com/package/riot-observable)

### JS / Router

* [riot-route](https://www.npmjs.com/package/riot-route)

### JS / View

* [deku](https://www.npmjs.com/package/deku) - mini-react that's more functional
* [magic-virtual-element](https://github.com/dekujs/magic-virtual-element) - support for `class` and `style` props in deku

### Node.js / CLI

* [release-it](https://github.com/webpro/release-it) - npm release helper
* [npm-check](https://github.com/dylang/npm-check) - checks for outdated packages
* [publish-latest](https://github.com/kentcdodds/publish-latest) - publish generated files to a branch
* [next-update](https://www.npmjs.com/package/next-update) - test new package versions
* [greenkeeper](https://www.npmjs.com/package/greenkeeper) - get PR's when new dependencies are ready
* [fixpack](https://github.com/henrikjoreteg/fixpack) - package.json formatter
* [gh-annotate](https://www.npmjs.com/package/gh-annotate) - annotate history
* [cping](https://www.npmjs.com/package/cping) - continuous ping
* [bump-cli](https://www.npmjs.com/package/bump-cli) - bump version numbers

### Node.js / CLI utilities

* [react-blessed](https://www.npmjs.com/package/react-blessed) - jsx + blessed
* [blessed](https://www.npmjs.com/package/blessed) - ncurses-like terminal interface
* [blessed-contrib](https://www.npmjs.com/package/blessed-contrib) - graphs and more for blessed
* [meow](https://www.npmjs.com/package/meow) - command line runner
* [le-table](https://www.npmjs.com/package/le-table) - another table drawing library
* [cli-table](https://www.npmjs.com/package/cli-table) - tables with box drawing chars
* [cliff](https://www.npmjs.com/package/cliff) - cli formatting

### Node.js / testing

* [budo](https://github.com/mattdesl/budo) - kinda like smokestack with watchify
* [tap-dev-tool](https://www.npmjs.com/package/tap-dev-tool) - pretty tap in browsers
* [tap-spec](https://www.npmjs.com/package/tap-spec) - most sensible tap reporter I know
* [smokestack](https://www.npmjs.com/package/smokestack) - `browserify index.js | smokestack --browser chrome`
* [hihat](https://www.npmjs.com/package/hihat) - local development in chrome devtools

### Node.js

* [is-there](https://www.npmjs.com/package/is-there) - fs.exists
* [sift](https://www.npmjs.com/package/sift) - mongodb-style filtering for JavaScript objects
* [redent](https://www.npmjs.com/package/redent) - strip redundant indentation
* [repeating](https://www.npmjs.com/package/repeating) - repeat a string N times
* [indent-string](https://www.npmjs.com/package/indent-string) - indent a string
* [ms](https://github.com/rauchg/ms.js) - convert `1 day` to `86400000`
* [superstatic](https://www.npmjs.com/package/superstatic) - the best static server ever
* [pathmodify](https://www.npmjs.com/package/pathmodify) - allow `require('app/x')` without `../` in browserify
* [aliasify](https://github.com/benbria/aliasify) - rewrite `require('d3')` calls to `require('../shims/d3.js')` or something
* [debowerify](https://github.com/eugeneware/debowerify) - use `require('package')` for bower components
* [inquirer](https://www.npmjs.com/package/inquirer) - cli prompts
* [get-port](https://npmjs.com/package/get-port) - get available port
* [tildify](https://npmjs.com/package/tildify) - replace /home/user with ~ (also see untildify)
* [update-notifier](https://npmjs.com/package/update-notifier) - sparkle for global CLI apps
* [opener](https://npmjs.com/package/opener) - abstraction for open/xdg-open/start
* [nixt](https://github.com/vesln/nixt) - CLI testing
* [v8flags](https://www.npmjs.com/package/v8flags) - all available v8 flags
* [minimatch](https://www.npmjs.com/package/minimatch) - file glob matching used by npm
* [espower-babel](https://www.npmjs.com/package/espower-babel) - babel + power-assert integration
* [power-assert](https://www.npmjs.com/package/power-assert) - detailed test assertions
* [mz](https://github.com/normalize/mz) - modernize node.js API to ECMA standards (promises)
* [osmosis](https://github.com/rc0x03/node-osmosis) - web scraper
* [yargs](https://github.com/bcoe/yargs) - argument parser
* [make-lint](https://github.com/tj/make-lint) - makefile integration for eslint
* [eslint](http://eslint.org/) - another linter
* [nconf](https://www.npmjs.com/package/nconf) - configuration helper (like figaro)
* [cli](https://github.com/chriso/cli) - rapidly build cli apps
* [browser-sync](http://www.browsersync.io/) - livereload server
* [changelog-maker](https://github.com/rvagg/changelog-maker) - changelog tool used by io.js
* [xtend](https://www.npmjs.com/package/xtend) - use this for extend
* [outpipe](https://github.com/substack/outpipe) - write output to a file using shell commands
* [package-json-to-readme](https://github.com/zeke/package-json-to-readme) - parse dependencies
* [dashdash](https://github.com/trentm/node-dashdash) - option parser
* [gulp-concat-filenames](https://www.npmjs.com/package/gulp-concat-filenames/) - makes import globbing possible
* [object-assign](https://www.npmjs.com/package/object-assign) - ES6 Object.assign (like $.extend)
* [brstar](https://www.npmjs.com/package/brstar) - pre-rendering browserify transformations
* [napa](https://www.npmjs.com/package/napa) - use bower packages like npm packages
* [ga](https://www.npmjs.com/package/ga) - server-side google analytics
* [review](https://www.npmjs.com/package/review) - take screenshots of sites for testing
* [systemjs](https://github.com/systemjs/systemjs) - dynamic module loader, built in es6
* [babel](http://babeljs.io/) - best es6 transpiler today
* [browserify-versionify](https://www.npmjs.com/package/browserify-versionify) - add package version in

### Node.js streams

* [stream-combiner](https://www.npmjs.com/package/stream-combiner)

2014
----

### Frontend

* [jquery.timepicker](http://jonthornton.github.io/jquery-timepicker/) - time picker
* [strip.js](http://www.stripjs.com/) - less intrusive lightbox
* [jquery-sortable](http://johnny.github.io/jquery-sortable/) - opinionated drag-and-drop sorting plugin
* [html5-device-mockups](https://github.com/pixelsign/html5-device-mockups) - pure CSS devices
* [devices.css](http://marvelapp.github.io/devices.css/) - pure CSS devices
* [email templates](https://github.com/mailgun/transactional-email-templates) - transactional email templates
* [switcher](https://github.com/rscherf/switcher) - converts links to native iOS links
* [raf](https://github.com/chrisdickinson/raf) - requestanimationframe polyfill
* [Poshytip](https://github.com/vadikom/poshytip) - tooltips
* [Dropzone.js](http://www.dropzonejs.com) - file upload
* [ractive.js](http://www.ractivejs.org/) - data binding
* [fastclick](https://github.com/ftlabs/fastclick) - remote click delays
* [page.js](http://visionmedia.github.io/page.js/) - router
* [js-model](http://benpickles.github.io/js-model/) - model system
* [modella](https://github.com/modella/modella) - models
* [wow.js](http://mynameismatthieu.com/WOW/) - stock animations on scrolling
* [intro.js](http://usablica.github.io/intro.js/) - better introductions for websites
* [hammer.js](http://duckduckgo.com/?q=hammer.js) - touch events
* [ractive-swipe](https://github.com/ekanna/Ractive-events-swipe) - swipe events for ractive
* [ractive-promise](https://github.com/lluchs/Ractive-adaptors-Promise) - promise objects in data
* [slip](https://github.com/pornel/slip) - interactive swiping and reordering of elements
* [spin.js](http://fgnass.github.io/spin.js/) - custom spinners
* [behave.js](https://github.com/jakiestfu/Behave.js) - textareas with identation
* [chance.js](http://chancejs.com/) - pseudo-random generator, support guid
* [gremlins.js](https://github.com/marmelab/gremlins.js) - monkey testing
* [enquire.js](https://github.com/WickyNilliams/enquire.js) - media queries
* [constraint.js](http://cjs.from.so/) - handlebars-like templating
* [bluebird](https://github.com/petkaantonov/bluebird) - promisify
* [scrollupbar](http://eduardomb.github.io/scroll-up-bar/) - fixed top bar
* [trumbowyg](http://alex-d.github.io/Trumbowyg) - wysiwyg editor
* [quill](http://quilljs.com) - wysiwyg editor
* [waves](http://publicis-indonesia.github.io/Waves/) - matter-inspired wave press effect

### Node.js

* [hashmark](https://github.com/keithamus/hashmark) - adds filename hashes
* [debug](https://github.com/visionmedia/debug) - simple debug logger
* [katon](https://github.com/typicode/katon) - generic development server helper, like pow
* [sander](https://www.npmjs.org/package/sander) - promise-based fs utilities
* [mocha-jshint](https://github.com/Muscula/mocha-jshint) - invoke jshint as mocha tests
* [rc](https://www.npmjs.org/package/rc) - cli configuration loader
* [clivas](https://github.com/mafintosh/clivas) - cli drawing
* [peerflix](https://github.com/mafintosh/peerflix) - stream torrent videos to airplay/vlc
* [ase](https://npmjs.org/package/ase) - maintains a distributed network
* [configstore](https://github.com/yeoman/configstore) - store config in ~/.config/x/y
* [marked](https://npmjs.org/package/marked) - markdown
* [cheerio](https://npmjs.org/package/cheerio) - minimalistic jquery api for the server
* [orchestrator](https://github.com/robrich/orchestrator) - define tasks and run them with max concurrency
* [trigger.io](https://trigger.io/) - mobile apps in js
* [nopt](https://www.npmjs.org/package/nopt) - option parser
* [mdconf](https://github.com/visionmedia/mdconf) - markdown configuration
* [brocolli](http://www.solitr.com/blog/2014/02/broccoli-first-release/index.html) - sprockets-like asset manager
* [spelunk](https://www.npmjs.org/package/spelunk) - directory to json
* [yargs](https://www.npmjs.org/package/yargs) - cli arg parser
* [observatory](https://github.com/dylang/observatory) - cli task reporter

### Usual Express.js middleware

* [serve-static](https://github.com/expressjs/serve-static) - default static server
* [st](https://github.com/isaacs/st) - better static serving
* [morgan](https://github.com/expressjs/morgan) - http request logger
* [session](https://github.com/expressjs/session) - simple sessions
* [body-parser](https://github.com/expressjs/body-parser) - parse json bodies
* [errorhandler](https://github.com/expressjs/errorhandler) - development error handler
* [compression](https://github.com/expressjs/compression) - on-the-fly gzip compression

2013
----

### Frontend

* [Password123](https://github.com/timmywil/password123) - password meter
* [Backbone Query](http://duckduckgo.com/?q=backbone query) - https://github.com/davidgtonge/backbone_query
* [Supermodel.js](http://pathable.github.com/supermodel/) - Backbone model relationships
* [Jwerty](https://github.com/keithamus/jwerty) - keyboard events helper
* [WysiHTML5](http://xing.github.com/wysihtml5/) - editor
* [Mousetrap](https://github.com/ccambell/mousetrap) - keyboard hooks http://craig.is/killing/mice
* [Reveal.js](https://github.com/hakimel/reveal.js) - presentation tool
* [Select2](https://github.com/ivaynberg/select2) - select box replacement
* [Piecon](http://lipka.github.com/piecon/) - Progress pie chart favicon
* [Tinycon](https://github.com/tommoor/tinycon) - favicon notification count and more
* [Mailcheck](https://github.com/Kicksend/mailcheck) - email address typo corrector
* [Fastclick](https://github.com/ftlabs/fastclick) - Transparent tap handler
* [X-Editable](http://vitalets.github.com/x-editable/) - in-place editability
* [Chardin](http://heelhook.github.io/chardin.js/) - Simple overlay instructions
* [Moment](http://duckduckgo.com/?q=moment) - Date parsing/formatting momentjs.com
* [Harvey](https://github.com/harvesthq/harvey) - Size responder
* [Waypoints](http://imakewebthings.com/jquery-waypoints/) - Trigger when it scrolls into view (2013-08)

### Frontend (deprecated)

* [Notificon](https://github.com/makeable/Notificon) - favicon notification count
* [Touche](http://duckduckgo.com/?q=touche) - backports ontouch events to desktop
* [Tappable](https://github.com/cheeaun/tappable) - tap events for iOS

### Node.js

* [passport-local](http://passportjs.org) - authentication
* [browserify](http://browserify.org) - bundle JS
* [connect-assets](http://duckduckgo.com/?q=connect-assets) - assets
* [js-yaml](http://duckduckgo.com/?q=js-yaml) - yaml
* [coffee-resque](http://duckduckgo.com/?q=coffee-resque) - nodejs port of resque
* [marked](http://duckduckgo.com/?q=marked) - markdown parser
* [matador](http://obvious.github.com/matador/) - MVC built on Express
* [commander](https://npmjs.org/package/commander) - options parser
* [htmlparser](https://npmjs.org/package/htmlparser) - Forgiving html parser
* [apricot](https://github.com/silentrob/Apricot) - Hpricot clone
* [shelljs](https://github.com/arturadib/shelljs) - Portable GNU tools in Node.js
* [SEOServer](http://duckduckgo.com/?q=seoserver) - https://github.com/ApiEngine/seoserver
* [appjs](http://appjs.org) - native desktop apps in HTML5

### JS/Templating

* Handlebars.js
* Jade
* Mustache
* Eco
* Emblem
* Dust
* [Emblem](http://duckduckgo.com/?q=emblem) - jade that compiles to handlebars

### Node.js filesystem

* [rimraf](https://npmjs.org/package/rimraf) - rm -rf
* [mkdirp](https://npmjs.org/package/mkdirp) - mkdirp

