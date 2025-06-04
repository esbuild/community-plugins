# Community plugins for [esbuild](https://esbuild.github.io/)

⚠️ *These plugins are from the community and are not officially supported.* ⚠️

This is just a centralized list of 3rd-party plugins to make discovery easier. No guarantees are made as to plugin quality, compatibility, or lack of malicious code. As with all 3rd-party dependencies, you should review them yourself before including them in your project.

## Plugin list

### New file extensions (hosted on npm)

* [@asn.aeb/esbuild-css-modules-plugin](https://github.com/asnaeb/esbuild-css-modules-plugin): A CSS Modules plugin with support for both Client and SSR transformations.
* [@digitalmaas/esbuild-plugin-ejs](https://github.com/digitalmaas/esbuild-plugin-ejs): Adds support for [Embedded JavaScript Templates](https://ejs.co/) (.ejs) imports.
* [@es-pack/esbuild-sass-plugin](https://github.com/Csszabi98/es-pack/tree/main/plugins/esbuild-sass-plugin): A Sass plugin using Dart Sass with type definitions.
* [@exact-realty/esbuild-plugin-responsive-images](https://github.com/Exact-Realty/esbuild-plugin-responsive-images): A plugin for responsive images using Sharp for automatic resizing and conversion.
* [@offen/esbuild-plugin-jsonschema](https://github.com/offen/esbuild-plugin-jsonschema): Compile and pack JSON schema definitions on import.
* [@ymulenll/esbuild-plugin-pug](https://github.com/ymulenll/esbuild-plugin-pug): A plugin to transform pug templates files into pug compiled functions
* [esbuild-coffeescript](https://github.com/johnie/esbuild-coffeescript): A plugin to compile CoffeeScript files (`*.coffee` & `*.litcoffee` files).
* [esbuild-css-modules-plugin](https://github.com/indooorsman/esbuild-css-modules-plugin#readme): A plugin to bundle `xxx.modules.css` or `xxx.module.css` into `.js(x)/.ts(x)`. Can build with both `bundle: true` & `bundle: false`. Based on the extremely fast [Lightning CSS](https://lightningcss.dev/).
* [esbuild-graphql-loader](https://github.com/luckycatfactory/esbuild-graphql-loader): A plugin allowing for GraphQL file imports.
* [esbuild-mdx](https://github.com/zaydek/esbuild-mdx): A plugin to render `.md` and `.mdx`-delimited files as React components.
* [esbuild-peggy](https://github.com/rodw/esbuild-peggy): A plugin enabling direct [peggy / peg.js](https://peggyjs.org/) imports into JavaScript / TypeScript files. Available as [`esbuild-peggy` on npm](https://www.npmjs.com/package/esbuild-peggy).
* [esbuild-plugin-ajv](https://github.com/mister-what/esbuild-plugin-ajv): A plugin to load and compile standalone validation code from JSON Schema / JSON Type Definition.
* [esbuild-plugin-class-modules](https://github.com/inqnuam/esbuild-plugin-class-modules): A plugin to compile your stylesheets with Saas, PostCSS and CSS Modules.
* [esbuild-plugin-css-modules](https://github.com/koluch/esbuild-plugin-css-modules): Another one plugin to support CSS-modules (partially)
* [esbuild-plugin-define](https://github.com/webdeveric/esbuild-plugin-define): Flatten an object and pass it to esbuild's `define`.
* [esbuild-plugin-elm](https://github.com/phenax/esbuild-plugin-elm): A plugin to compile an elm project with esbuild.
* [esbuild-plugin-env](https://github.com/yamitsushi/esbuild-plugin-env): Update `process.env` variables. Uses dotenv and pass it to esbuild.
* [esbuild-plugin-environment](https://github.com/webdeveric/esbuild-plugin-environment): Define `process.env` variables. It accepts an array of keys or an object with keys mapped to their default values.
* [esbuild-plugin-external-package](https://github.com/yamitsushi/esbuild-plugin-external-package): sets all dependencies to external, alternative when `packages:"external"` is not applicable.
* [esbuild-plugin-global-api](https://github.com/DarrenDanielDay/esbuild-plugin-global-api): An esbuild plugin for simplifying global API calls.
* [esbuild-plugin-glsl](https://github.com/vanruesc/esbuild-plugin-glsl): A plugin that adds support for GLSL file imports with optional shader minification.
* [esbuild-plugin-glslify-inline](https://github.com/marcofugaro/esbuild-plugin-glslify-inline): A plugin to process inline GLSL strings with [glslify](https://github.com/glslify/glslify).
* [esbuild-plugin-glslify](https://github.com/darionco/esbuild-plugin-glslify): A plugin to import GLSL strings with [glslify](https://github.com/glslify/glslify) (a node.js-style module system for GLSL).
* [esbuild-plugin-glslx](https://github.com/evanw/esbuild-plugin-glslx): A plugin that supports [`*.glslx` files](http://evanw.github.io/glslx/) including type checking of GLSL code.
* [esbuild-plugin-handlebars](https://github.com/inqnuam/esbuild-plugin-handlebars) an esbuild plugin to handle ... handlebars!
* [esbuild-plugin-hjson](https://github.com/ChildishGiant/esbuild-plugin-hjson) A simple plugin to allow [`*.hjson`](https://hjson.github.io/) files to be imported.
* [esbuild-plugin-html-modules](https://github.com/whitefusionhq/esbuild-plugin-html-modules) A plugin to load HTML Modules based on [the proposed spec](https://github.com/WICG/webcomponents/blob/gh-pages/proposals/html-modules-explainer.md).
* [esbuild-plugin-inline-image](https://github.com/natrim/esbuild-plugin-inline-image) A plugin that switches loader for images between file and dataurl depending on size
* [esbuild-plugin-inline-worker](https://github.com/mitschabaude/esbuild-plugin-inline-worker): A plugin to create inline [Web Workers](https://developer.mozilla.org/en-US/docs/Web/API/Web_Workers_API) by importing `.worker.js` files.
* [esbuild-plugin-less](https://github.com/iam-medvedev/esbuild-plugin-less): A plugin to transform LESS files to CSS files.
* [esbuild-plugin-lightningcss-modules](https://github.com/mhsdesign/esbuild-plugin-lightningcss-modules): Yet another (minimal) css modules plugin using parcels rust based lightningcss implementation. (Full support for `composes: mixin from "./mixin.module.css"`)
* [esbuild-plugin-lit-css](https://github.com/bennypowers/lit-css/tree/main/packages/esbuild-plugin-lit-css): Import CSS files as tagged-template literals
* [esbuild-plugin-lit](https://github.com/zandaqo/esbuild-plugin-lit): Import and minify static assets (CSS, SVG, HTML, XLIFF) as tagged-template literals using built-in capabilities.
* [esbuild-plugin-markdown-import](https://github.com/LinbuduLab/nx-plugins/tree/main/packages/esbuild-plugin-markdown-import): Import, bundle, customize markdown files(support markdown2html by `marked`.).
* [esbuild-plugin-markdown](https://github.com/martonlederer/esbuild-plugin-markdown): Import & bundle markdown files
* [esbuild-plugin-postcss](https://github.com/deanc/esbuild-plugin-postcss): A plugin to use PostCSS.
* [esbuild-plugin-postcss2](https://github.com/martonlederer/esbuild-plugin-postcss2): A plugin to use preprocessors and CSS modules with PostCSS.
* [esbuild-plugin-prismjs](https://github.com/activeguild/esbuild-plugin-prismjs): A plugin bundles PrismJs language and plugins.
* [esbuild-plugin-properties](https://github.com/pd4d10/esbuild-plugin-properties): A plugin to load `*.properties` files.
* [esbuild-plugin-pug](https://github.com/adamjberg/esbuild-plugin-pug): A plugin to to render pug templates
* [esbuild-plugin-purescript](https://github.com/Mateiadrielrafael/esbuild-plugin-purescript): Adds support for importing [PureScript](https://www.purescript.org/) code.
* [esbuild-plugin-sass](https://github.com/koluch/esbuild-plugin-sass/): A plugin to transform Sass files to CSS files
* [esbuild-plugin-spglsl](https://github.com/rottencandy/esbuild-plugin-spglsl): A plugin that adds support for GLSL file imports using [spglsl](https://github.com/SalvatorePreviti/spglsl).
* [esbuild-plugin-svg](https://github.com/nativew/esbuild-plugin-svg): A plugin to import SVG files.
* [esbuild-plugin-svgj](https://github.com/Jarred-Sumner/svgj): Import `*.svg` files as React components using svgj (~40x faster than svgr)
* [esbuild-plugin-svgr](https://github.com/kazijawad/esbuild-plugin-svgr): A plugin to import `*.svg` files as React components.
* [esbuild-plugin-toml](https://github.com/SilentVoid13/esbuild-plugin-toml): A plugin to load `*.toml` files.
* [esbuild-plugin-type-schema](https://github.com/mooooooi/esbuild-plugin-type-schema): A plugin to generate type schema using decorators in your custom way, Like `type-graphql`.
* [esbuild-plugin-vue-next](https://github.com/Bigfish8/esbuild-plugin-vue-next): A plugin to transform Vue 3.x SFC (`*.vue` files).
* [esbuild-plugin-wat](https://github.com/mitschabaude/esbuild-plugin-wat): A plugin to import `.wasm` (WebAssembly) and `.wat` (WebAssembly text format).
* [esbuild-plugin-yaml](https://github.com/martonlederer/esbuild-plugin-yaml): A plugin to load YAML files as ES6 modules.
* [esbuild-postcss](https://github.com/karolis-sh/esbuild-postcss): A plugin to transform PostCSS files to CSS.
* [esbuild-sass-plugin-async](https://github.com/wfleming/esbuild-sass-plugin/): Fork of esbuild-sass-plugin using sass-embedded & async rendering: the advantage is potentially much faster compilation if you have many sass entrypoints, the tradeoff is sass-embedded is not compatible with musl libc distributions.
* [esbuild-sass-plugin](https://github.com/glromeo/esbuild-sass-plugin/): Yet another Sass to CSS but with support for [lit-element's styles](https://lit-element.polymer-project.org/guide/styles)
* [esbuild-squoosh](https://github.com/bognarlaszlo/esbuild-squoosh): A plugin for compressing/optimising images using libSquoosh
* [esbuild-style-plugin](https://github.com/g45t345rt/esbuild-style-plugin) A PostCSS plugin that support multiple preprocessors like SASS, STYLUS & LESS. Works with css modules and server side rendering / SSR.
* [esbuild-stylus-loader](https://github.com/ym-project/esbuild-stylus-loader): A plugin to transform stylus files to CSS files.
* [esbuild-svelte](https://github.com/EMH333/esbuild-svelte): A plugin to load and compile Svelte components.
* [esbuild-svg](https://github.com/Inqnuam/esbuild-svg): A plugin to transform your svg files to jsx components.
* [esbuild-usemin](https://github.com/oliverkuchies/esbuild-usemin): A plugin to transpile multiple lines of external resources into one line within a view.
* [esbuild-vue](https://github.com/apeschar/esbuild-vue): A plugin to load and compile Vue 2 single-file components (`*.vue` files).
* [esgleam](https://github.com/bwireman/esgleam): A plugin to compile gleam projects with esbuild.
* [essass](https://github.com/fayismahmood/sassEs/): A plugin to transform Sass files to CSS files.

### Other plugins (hosted on npm)

* [@akrc/esbuild-plugin-clean](https://github.com/akarachen/esbuild-plugin-clean): A plugin to clean the output dir.
* [@anatine/esbuild-decorators](https://github.com/anatine/esbuildnx/tree/main/packages/esbuild-decorators): This is a plugin for esbuild to handle the tsconfig setting `"emitDecoratorMetadata": true` using tsc to transpile `.ts` or `.tsx` files with decorators.
* [@craftamap/esbuild-plugin-html](https://github.com/craftamap/esbuild-plugin-html) A Plugin to create `*.html`-files from specified entry points.
* [@datadog/build-plugin](https://github.com/DataDog/build-plugin) A plugin to monitor your build performances.
* [@es-exec/esbuild-plugin-serve](https://github.com/tim117/es-exec/tree/main/plugins/es-serve): A plugin for running your build output in a child process after the project build completes.
* [@es-exec/esbuild-plugin-start](https://github.com/tim117/es-exec/tree/main/plugins/es-start): A plugin for running a script after your build completes, similar to [nodemon](https://github.com/remy/nodemon).
* [@exact-realty/esbuild-plugin-closure-compiler](https://github.com/Exact-Realty/esbuild-plugin-closure-compiler): A plugin for post-processsing esbuild output with Google Closure compiler. Useful for additional advanced transformations (esp. while using the `ADVANCED` compilation mode). Note: this will slow down your compilation. Source-maps are an upcoming feature.
* [@exact-realty/esbuild-plugin-inline-js](https://github.com/Exact-Realty/esbuild-plugin-inline-js): A plugin for inline scripts with SRI support; runs a separate esbuild process and returns a string for ease of embedding.
* [@fal-works/esbuild-plugin-global-externals](https://github.com/fal-works/esbuild-plugin-global-externals): A plugin to replace module imports with global variables.
* [@gjsify/esbuild-plugin-deno-loader](https://github.com/gjsify/esbuild-plugin-deno-loader): A plugin that adds support for Deno module resolution (to use in Node.js).
* [@liber-ufpe/esbuild-plugin-compress](https://github.com/Liber-UFPE/esbuild-plugin-compress): esbuild plugin to compress output using gzip, brotli, and deflate.
* [@liber-ufpe/esbuild-plugin-sharp](https://github.com/Liber-UFPE/esbuild-plugin-sharp): esbuild plugin that creates webp and avif versions (or any other format supported by [sharp](https://github.com/lovell/sharp)) for your images.
* [@linjiajian999/esbuild-plugin-import](https://github.com/linjiajian999/esbuild-plugin-import): A plugin for modular import from ant, lodash, etc., similar to [babel-plugin-import](https://github.com/ant-design/babel-plugin-import).
* [@sprout2000/esbuild-copy-plugin](https://github.com/sprout2000/esbuild-copy-plugin): A plugin which is a typed and fully tested version of [@nickjj](https://github.com/nickjj)'s [esbuild-copy-static-files](https://github.com/nickjj/esbuild-copy-static-files).
* [@stylify/unplugin](https://github.com/stylify/packages): A plugin for [Stylify CSS](https://stylifycss.com) with which you can use CSS-like selectors to style your website.
* [@yarnpkg/esbuild-plugin-pnp](https://github.com/yarnpkg/berry/tree/master/packages/esbuild-plugin-pnp#yarnpkgesbuild-plugin-pnp): A plugin adding support for [Yarn Plug'n'Play](https://yarnpkg.com/features/pnp) installs.
* [altv-esbuild](https://github.com/xxshady/altv-esbuild): Smoother development as well as production of JS/TS server/client scripts on the [alt:V](https://altv.mp) platform.
* [decky](https://github.com/jarred-sumner/decky): A plugin that makes TypeScript experimental decorators run at compile-time, enabling macros and potentially reducing bundle size
* [esbuild-cf-functions-plugin](https://github.com/BeeeQueue/esbuild-cf-functions-plugin): A plugin for building code [compatible](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/functions-javascript-runtime-features.html) with [CloudFront Functions](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/functions-javascript-runtime-features.html)
* [esbuild-compress](https://github.com/polyipseity/esbuild-compress): Compress embedded data, which will be decompressed at runtime, to reduce bundle size.
* [esbuild-copy-files-plugin](https://github.com/whatdoyouseedoc/esbuild-copy-files-plugin/): Simple plugin that helps to copy files and folders across the application
* [esbuild-copy-plugin](https://github.com/DasRed/esbuild-plugin-copy): A plugin to copy some files from one destination to another
* [esbuild-copy-static-files](https://github.com/nickjj/esbuild-copy-static-files): An esbuild plugin to efficiently copy static files from a source directory to a destination directory
* [esbuild-cross-browser-css](https://github.com/plxity/esbuild-cross-browser-css): A plugin to make CSS compatible for all the different browsers.
* [esbuild-dev-server](https://github.com/Falldot/esbuild-dev-server): A plugin allows you to start a local server with hot reloading.
* [esbuild-gas-plugin](https://github.com/mahaker/esbuild-gas-plugin): A plugin that generate codes for Google Apps Script.
* [esbuild-ignore-with-comments-plugin](https://github.com/goldstack/goldstack/tree/master/workspaces/utils/packages/esbuild-ignore-with-comments-plugin#readme): A plugin that allows ignoring specific source files during build by adding the comment `/* esbuild-ignore */`.
* [esbuild-inline-sass](https://github.com/ProdigyPXP/esbuild-inline-sass): A plugin that loads SASS/SCSS straight into your JavaScript bundle (A combination of [this inline style loader](https://github.com/hyrious/esbuild-plugin-style) and [this scss loader](https://github.com/glromeo/esbuild-sass-plugin)).
* [esbuild-metadata-report](https://github.com/cenfun/esbuild-metadata-report): A plugin that generate HTML report for esbuild metadata.
* [esbuild-plugin-alias-path](https://github.com/LinbuduLab/nx-plugins/tree/main/packages/esbuild-plugin-alias-path): A plugin to transform TypeScript `compilerOptions.path` at compile-time.
* [esbuild-plugin-alias](https://github.com/igoradamenko/esbuild-plugin-alias): A plugin to resolve dynamic path aliases.
* [esbuild-plugin-assets-manifest](https://github.com/indooorsman/esbuild-plugin-assets-manifest): A plugin to Generate manifest file like assets-webpack-plugin does.
* [esbuild-plugin-babel-flow](https://github.com/henrhie/esbuild-plugin-babel-flow): A plugin that allows you to strip off Flow annotations from JavaScript code using Babel.
* [esbuild-plugin-babel](https://github.com/nativew/esbuild-plugin-babel): A plugin to compile files with Babel.
* [esbuild-plugin-bookmarklet](https://github.com/reesericci/esbuild-plugin-bookmarklet): A plugin to generate bookmarklets.
* [esbuild-plugin-brode](https://github.com/geut/brode/tree/main/packages/esbuild-plugin-brode): A plugin to add node polyfills core modules for the web.
* [esbuild-plugin-browserify-adapter](https://github.com/m90/esbuild-plugin-browserify-adapter): An adapter to use existing Browserify transforms as esbuild plugins.
* [esbuild-plugin-browserslist](https://github.com/nihalgonsalves/esbuild-plugin-browserslist): Configure esbuild targets based on a browserslist query.
* [esbuild-plugin-cache](https://github.com/dalcib/esbuild-plugin-cache): A plugin to cache http/https modules. It works with [import-maps](https://github.com/WICG/import-maps).
* [esbuild-plugin-clean](https://github.com/LinbuduLab/nx-plugins/tree/main/packages/esbuild-plugin-clean): esbuild plugin for cleaning up output before build.
* [esbuild-plugin-clear](https://github.com/DasRed/esbuild-plugin-clear): A plugin to clear a directory.
* [esbuild-plugin-compress](https://github.com/LinbuduLab/nx-plugins/tree/main/packages/esbuild-plugin-compress): esbuild plugin for output compression (gzip/brotli).
* [esbuild-plugin-copy-file](https://github.com/ozanozbek/esbuild-plugin-copy-file): A plugin for asynchronously copying files in parallel before or after bundling.
* [esbuild-plugin-copy-watch](https://github.com/tinchoz49/esbuild-plugin-copy-watch): A plugin to watch and copy static files.
* [esbuild-plugin-copy](https://github.com/LinbuduLab/nx-plugins/tree/main/packages/esbuild-plugin-copy): esbuild plugin for assets copy.
* [esbuild-plugin-d-ts-path-alias](https://github.com/ArtemKlyuev/esbuild-plugin-d-ts-path-alias): esbuild plugin for compiling typescript declarations along with path aliases transformation.
* [esbuild-plugin-d.ts](https://github.com/Floffah/esbuild-plugin-d.ts): esbuild convenience plugin for compiling TypeScript definitions along with JavaScript
* [esbuild-plugin-decorator](https://github.com/LinbuduLab/nx-plugins/tree/main/packages/esbuild-plugin-decorator): esbuild plugin for TypeScript decorators compilation, support `tsc`/`swc`.
* [esbuild-plugin-deepkit](https://github.com/gjsify/gjsify/tree/main/packages/infra/esbuild-plugin-deepkit#readme): A plugin for the transformer of [@deepkit/type](https://deepkit.io/library/type) for TypeScript Runtime types.
* [esbuild-plugin-dev-server](https://github.com/kmalakoff/esbuild-plugin-dev-server): Dev server for esbuild with live reload and error overlay.
* [esbuild-plugin-drop](https://github.com/pirxpilot/esbuild-plugin-drop): A plugin to remove `assert`, `debug`, etc.
* [esbuild-plugin-eslint](https://github.com/robinloeffel/esbuild-plugin-eslint): Lint your esbuild bundles with eslint. 🧐
* [esbuild-plugin-eslinter](https://github.com/TurtIeSocks/esbuild-plugin-eslinter): A plugin for linting your builds, includes caching and node_module exclusion.
* [esbuild-plugin-eval](https://github.com/vpctorr/esbuild-plugin-eval): Optimize runtime execution and bundle size by pre-evaluating some modules before they are imported.
* [esbuild-plugin-execute](https://github.com/qiweiii/esbuild-plugin-execute): A plugin to create esbuild plugins with executables.
* [esbuild-plugin-file-path-extensions](https://github.com/favware/esbuild-plugin-file-path-extensions): A plugin to automatically insert file extensions in your built JavaScript files based on the specified target.
* [esbuild-plugin-filelastmodified](https://github.com/g45t345rt/esbuild-plugin-filelastmodified): A plugin to replace `__fileLastModified__` with the actual time the file has been modified.
* [esbuild-plugin-flow](https://github.com/dalcib/esbuild-plugin-flow): A plugin to strip types for Flow files using flow-remove-types package.
* [esbuild-plugin-glob-import](https://github.com/whaaaley/esbuild-plugin-glob-import): Use globs to import multiple files.
* [esbuild-plugin-glob](https://github.com/waspeer/esbuild-plugin-glob): Use glob patterns as `entryPoints`
* [esbuild-plugin-globals](https://github.com/a-b-r-o-w-n/esbuild-plugin-globals): A plugin to replace module contents with user provided globals.
* [esbuild-plugin-ifdef](https://github.com/Jarred-Sumner/esbuild-plugin-ifdef) A plugin that adds conditional code compilation for JavaScript/TypeScript using `//#ifdef CONDITION` comments.
* [esbuild-plugin-ignore](https://github.com/Knowre-Dev/esbuild-plugin-ignore): A plugin to ignore some certain dependencies from bundling.
* [esbuild-plugin-imagemin](https://github.com/omyasn/esbuild-plugin-imagemin): A plugin to minimize images using imagemin.
* [esbuild-plugin-import-glob](https://github.com/thomaschaaf/esbuild-plugin-import-glob): A plugin to import multiple files using the glob syntax. Similar to `require.context` from webpack.
* [esbuild-plugin-inline-import](https://github.com/claviska/esbuild-plugin-inline-import): A plugin that inlines and optionally transforms imports with a configurable prefix.
* [esbuild-plugin-lit-minify-html](https://github.com/chapery/esbuild-plugin-lit-minify-html): minify tagged-template literals of the lit `html` method, it remove white space characters.
* [esbuild-plugin-lodash](https://github.com/josteph/esbuild-plugin-lodash): A plugin that helps tree-shake non-es lodash imports, similar to how [babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) works.
* [esbuild-plugin-manifest](https://github.com/jfortunato/esbuild-plugin-manifest): A plugin to generate a hashed asset manifest file.
* [esbuild-plugin-mxn-copy](https://github.com/ZimNovich/esbuild-plugin-mxn-copy): A esbuild plugin for copying assets into the output directory of your bundle.
* [esbuild-plugin-node-externals](https://github.com/LinbuduLab/nx-plugins/tree/main/packages/esbuild-plugin-node-externals): esbuild plugin for node externals handing.
* [esbuild-plugin-output-reset](https://github.com/yamitsushi/esbuild-plugin-output-reset): Minimal plugin to clean output before starting a new build.
* [esbuild-plugin-path-alias](https://github.com/indooorsman/esbuild-plugin-path-alias): A esbuild plugin to support path alias like `resolve.alias` in webpack config.
* [esbuild-plugin-pino](https://github.com/davipon/esbuild-plugin-pino): An esbuild plugin to generate extra pino files for bundling
* [esbuild-plugin-pipe](https://github.com/nativew/esbuild-plugin-pipe): A plugin to pipe the output of esbuild plugins.
* [esbuild-plugin-pnp](https://github.com/shiftx/esbuild-plugin-pnp): A plugin to support yarn 2 (berry) with PnP (Plug’n’Play).
* [esbuild-plugin-polyfill-node](https://github.com/cyco130/esbuild-plugin-polyfill-node): Plugin to polyfill Node.js built-ins geared towards edge environments.
* [esbuild-plugin-postcss-literal](https://github.com/nativew/esbuild-plugin-postcss-literal): A plugin to transform tagged template literals with PostCSS.
* [esbuild-plugin-progress](https://github.com/kmalakoff/esbuild-plugin-progress): A plugin to add a progress spinner to esbuild.
* [esbuild-plugin-purgecss](https://github.com/GitHubJiKe/esbuild-plugin-purgecss): A plugin to remove useless css class with purgecss.
* [esbuild-plugin-raw-css](https://github.com/Debonex/esbuild-plugin-raw-css): A plugin to import css files as minified raw text.
* [esbuild-plugin-realpath](https://github.com/kmalakoff/esbuild-plugin-realpath): A plugin to resolve the fs.realpath for modules in monorepos targeting the browser and node.
* [esbuild-plugin-replace-regex](https://github.com/fakundo/esbuild-plugin-replace-regex): Simple plugin for replacing file content.
* [esbuild-plugin-resolve](https://github.com/markwylde/esbuild-plugin-resolve): Change where a module dependency is resolved/imported from.
* [esbuild-plugin-run](https://github.com/LinbuduLab/nx-plugins/tree/main/packages/esbuild-plugin-run): esbuild plugin to execute output file after build.
* [esbuild-plugin-simple-css-modules](https://gitlab.com/hesxenon/esbuild-plugin-simple-css-modules/-/tree/main): A plugin to transform `.module.css` files by prefixing classnames with a unique identifier
* [esbuild-plugin-sixsixsix-killer](https://github.com/inqnuam/esbuild-plugin-sixsixsix-killer): Remove bloc of code when 'if' statement meets 666 condition
* [esbuild-plugin-solid-js](https://gitlab.com/hesxenon/esbuild-plugin-solid-js/-/tree/main): A plugin to apply solids jsx transforms with esbuild (without breaking/dropping sourcemaps)
* [esbuild-plugin-stimulus](https://github.com/zombiezen/esbuild-plugin-stimulus): A plugin to automatically [load Stimulus controllers](https://stimulus.hotwire.dev/handbook/installing) from a folder.
* [esbuild-plugin-styled-components](https://github.com/appzic/esbuild-plugin-styled-components): A plugin to support styled-components
* [esbuild-plugin-summary](https://github.com/devm33/esbuild-plugin-summary): A plugin to output the CLI build summary, time and filesize, when using the API.
* [esbuild-plugin-swc-minify](https://github.com/D1g1talEntr0py/esbuild-plugin-swc-minify): plugin to minify js(x) files using SWC.
* [esbuild-plugin-swc](https://github.com/sanyuan0704/esbuild-plugin-swc): A plugin to support swc transform in Esbuild.
* [esbuild-plugin-text-replace](https://github.com/aheissenberger/esbuild-plugin-text-replace): Replace content before bundling with support for Filefilter, Namespace, Regex and Functions.
* [esbuild-plugin-time](https://github.com/DasRed/esbuild-plugin-time): A simple plugin for time measuring of the build process.
* [esbuild-plugin-transform-ext](https://github.com/gjsify/gjsify/tree/main/packages/infra/esbuild-plugin-transform-ext#readme): A plugin to transform import file extensions, e.g. `.ts` to `.js`.
* [esbuild-plugin-transform](https://github.com/sxzz/esbuild-plugin-transform): A plugin to pipe transformation plugins for esbuild.
* [esbuild-plugin-tsc](https://github.com/thomaschaaf/esbuild-plugin-tsc): A plugin to transform TypeScript files using the official [TypeScript compiler](https://github.com/microsoft/TypeScript). Allows usage of `emitDecoratorMetadata`.
* [esbuild-plugin-tsconfig-paths](https://github.com/wjfei/esbuild-plugin-tsconfig-paths): Transform `Typescript` `compilerOptions.paths` alias to relative path when compile.
* [esbuild-plugin-umd-wrapper](https://github.com/inqnuam/esbuild-plugin-umd-wrapper): UMD wrapper for esbuild.
* [esbuild-plugin-unused-modules](https://github.com/tridge-hq/esbuild-plugin-unused-modules): A plugin to extract unused module files under a specific directory.
* [esbuild-plugin-velcro](https://github.com/ggoodman/esbuild-plugin-velcro): A plugin to load npm (bare module) dependencies from the cloud and requiring no previous NPM install.
* [esbuild-plugin-version-injector](https://github.com/favware/esbuild-plugin-version-injector): A plugin to inject your application's version number or today's date into your files.
* [esbuild-plugin-wildcard-imports](https://github.com/andreventuravale/esbuild-plugin-wildcard-imports): Wildcard imports for CJS Require, ESM Import/Export, and dynamic imports.
* [esbuild-plugin-write-file](https://github.com/ozanozbek/esbuild-plugin-write-file): A plugin for asynchronously creating/writing files in parallel before or after bundling.
* [esbuild-plugins-node-modules-polyfill](https://github.com/imranbarbhuiya/esbuild-plugins-node-modules-polyfill): A plugin to polyfill nodejs builtin modules for the browser.
* [esbuild-svelte-paths](https://github.com/alexxnb/esbuild-svelte-paths): A plugin that resolves shortcuted pathes for Svelte components.
* [opentelemetry-esbuild-plugin-node](https://github.com/DrewCorlin/opentelemetry-esbuild-plugin-node): A plugin that instruments NodeJS packages with OpenTelemetry instrumentation.
* [react-native-esbuild](https://github.com/oblador/react-native-esbuild): Bundler and dev server for react-native using esbuild.

### Plugins for Deno

* [esbuild-plugin-bookmarklet](https://deno.land/x/esbuild_plugin_bookmarklet): A plugin to generate bookmarklets.
* [esbuild-plugin-env](https://deno.land/x/esbuild_plugin_env): A plugin that exports the current environment as a module.
* [esbuild-plugin-eval](https://deno.land/x/esbuild_plugin_eval): A plugin that evaluates a module before importing it.
* [esbuild-plugin-http-fetch](https://deno.land/x/esbuild_plugin_http_fetch): A plugin that resolves http(s) modules, for use with browsers and Deno.
* [esbuild-plugin-sass-deno](https://deno.land/x/esbuild_plugin_sass_deno@v0.1.0): A Plugin which adds support for SASS/SCSS using `denosass`.
* [esbuild-plugin-postcss](https://jsr.io/@udibo/esbuild-plugin-postcss): A plugin that makes it easy to use PostCSS with Deno. Supports CSS Modules, Sass, Less, and Stylus.

## How to use a plugin

To use an esbuild plugin, you generally import it into your build script and then pass it to the esbuild API like this:

```js
const esbuild = require('esbuild')
const somePlugin = require('some-plugin')

esbuild.build({
  plugins: [
    somePlugin(),
  ],
  ...
}).catch(() => process.exit(1))
```

More documentation about plugins and the plugin API is available [here](https://esbuild.github.io/plugins/#using-plugins).

## Adding your plugin here

If you would like to add your plugin to this list, create a PR that updates this README file. The update should add a single bullet under the **Plugin list** section that starts with a link to the plugin and is followed by a brief one-sentence description. The text of the link should be the npm package name and it should be inserted in alphabetical order. It should look something like this:

* [esbuild-plugin-example](https://github.com/your-username-here/your-plugin-name-here): A plugin to load `*.example` files.

Before creating a PR, please make sure that:

* The package is already published to npm
* You are the author of the plugin
* You are willing to respond to issues about the plugin if people file issues against it

_Note: Even though the text "esbuild-plugin-example" above is a link, it's just example placeholder text. The project at the link destination intentionally doesn't exist. The text is only linked to demonstrate how you should format your entry._
