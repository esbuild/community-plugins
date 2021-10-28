# Community plugins for [esbuild](https://esbuild.github.io/)

⚠️ *These plugins are from the community and are not officially supported.* ⚠️

This is just a centralized list of 3rd-party plugins to make discovery easier. No guarantees are made as to plugin quality, compatibility, or lack of malicious code. As with all 3rd-party dependencies, you should review them yourself before including them in your project.

## Plugin list

### New file extensions (hosted on npm)

* [@es-pack/esbuild-sass-plugin](https://github.com/Csszabi98/es-pack/tree/main/plugins/esbuild-sass-plugin): A Sass plugin using Dart Sass with type definitions.
* [@offen/esbuild-plugin-jsonschema](https://github.com/offen/esbuild-plugin-jsonschema): Compile and pack JSON schema definitions on import.
* [esbuild-coffeescript](https://github.com/johnie/esbuild-coffeescript): A plugin to compile CoffeeScript files (`*.coffee` & `*.litcoffee` files).
* [esbuild-css-modules-plugin](https://github.com/indooorsman/esbuild-css-modules-plugin#readme): A plugin to bundle `xxx.modules.css` or `xxx.module.css` into `.js(x)/.ts(x)`. Can build with both `bundle: true` & `bundle: false`.
* [esbuild-graphql-loader](https://github.com/luckycatfactory/esbuild-graphql-loader): A plugin allowing for GraphQL file imports.
* [esbuild-mdx](https://github.com/zaydek/esbuild-mdx): A plugin to render `.md` and `.mdx`-delimited files as React components.
* [esbuild-plugin-css-modules](https://github.com/koluch/esbuild-plugin-css-modules): Another one plugin to support CSS-modules (partially)
* [esbuild-plugin-elm](https://github.com/phenax/esbuild-plugin-elm): A plugin to compile an elm project with esbuild.
* [esbuild-plugin-glsl](https://github.com/vanruesc/esbuild-plugin-glsl): A plugin that adds support for GLSL file imports with optional shader minification.
* [esbuild-plugin-glslify-inline](https://github.com/marcofugaro/esbuild-plugin-glslify-inline): A plugin to process inline GLSL strings with [glslify](https://github.com/glslify/glslify).
* [esbuild-plugin-glslify](https://github.com/darionco/esbuild-plugin-glslify): A plugin to import GLSL strings with [glslify](https://github.com/glslify/glslify) (a node.js-style module system for GLSL).
* [esbuild-plugin-glslx](https://github.com/evanw/esbuild-plugin-glslx): A plugin that supports [`*.glslx` files](http://evanw.github.io/glslx/) including type checking of GLSL code.
* [esbuild-plugin-hjson](https://github.com/ChildishGiant/esbuild-plugin-hjson) A simple plugin to allow [`*.hjson`](https://hjson.github.io/) files to be imported.
* [esbuild-plugin-inline-worker](https://github.com/mitschabaude/esbuild-plugin-inline-worker): A plugin to create inline [Web Workers](https://developer.mozilla.org/en-US/docs/Web/API/Web_Workers_API) by importing `.worker.js` files.
* [esbuild-plugin-less](https://github.com/iam-medvedev/esbuild-plugin-less): A plugin to transform LESS files to CSS files.
* [esbuild-plugin-lit-css](https://github.com/bennypowers/lit-css/tree/main/packages/esbuild-plugin-lit-css): Import CSS files as tagged-template literals
* [esbuild-plugin-markdown](https://github.com/martonlederer/esbuild-plugin-markdown): Import & bundle markdown files
* [esbuild-plugin-postcss](https://github.com/deanc/esbuild-plugin-postcss): A plugin to use PostCSS.
* [esbuild-plugin-postcss2](https://github.com/martonlederer/esbuild-plugin-postcss2): A plugin to use preprocessors and CSS modules with PostCSS.
* [esbuild-plugin-properties](https://github.com/pd4d10/esbuild-plugin-properties): A plugin to load `*.properties` files.
* [esbuild-plugin-purescript](https://github.com/Mateiadrielrafael/esbuild-plugin-purescript): Adds support for importing [PureScript](https://www.purescript.org/) code.
* [esbuild-plugin-sass](https://github.com/koluch/esbuild-plugin-sass/): A plugin to transform Sass files to CSS files
* [esbuild-plugin-svg](https://github.com/nativew/esbuild-plugin-svg): A plugin to import SVG files.
* [esbuild-plugin-svgj](https://github.com/Jarred-Sumner/svgj): Import `*.svg` files as React components using svgj (~40x faster than svgr)
* [esbuild-plugin-svgr](https://github.com/kazijawad/esbuild-plugin-svgr): A plugin to import `*.svg` files as React components.
* [esbuild-plugin-type-schema](https://github.com/mooooooi/esbuild-plugin-type-schema): A plugin to generate type schema using decorators in your custom way, Like `type-graphql`.
* [esbuild-plugin-wat](https://github.com/mitschabaude/esbuild-plugin-wat): A plugin to import `.wasm` (WebAssembly) and `.wat` (WebAssembly text format).
* [esbuild-plugin-yaml](https://github.com/martonlederer/esbuild-plugin-yaml): A plugin to load YAML files as ES6 modules.
* [esbuild-postcss](https://github.com/karolis-sh/esbuild-postcss): A plugin to transform PostCSS files to CSS.
* [esbuild-sass-plugin](https://github.com/glromeo/esbuild-sass-plugin/): Yet another Sass to CSS but with support for [lit-element's styles](https://lit-element.polymer-project.org/guide/styles)
* [esbuild-style-plugin](https://github.com/g45t345rt/esbuild-style-plugin) A PostCSS plugin that support multiple preprocessors like SASS, STYLUS & LESS. Works with css modules and server side rendering / SSR.
* [esbuild-stylus-loader](https://github.com/ym-project/esbuild-stylus-loader): A plugin to transform stylus files to CSS files.
* [esbuild-svelte](https://github.com/EMH333/esbuild-svelte): A plugin to load and compile Svelte components.
* [esbuild-vue](https://github.com/apeschar/esbuild-vue): A plugin to load and compile Vue 2 single-file components (`*.vue` files).
* [essass](https://github.com/fayismahmood/sassEs/): A plugin to transform Sass files to CSS files.

### Other plugins (hosted on npm)

* [@anatine/esbuild-decorators](https://github.com/anatine/esbuildnx/tree/main/packages/esbuild-decorators): This is a plugin for esbuild to handle the tsconfig setting `"emitDecoratorMetadata": true` using tsc to transpile `.ts` or `.tsx` files with decorators.
* [@craftamap/esbuild-plugin-html](https://github.com/craftamap/esbuild-plugin-html) A Plugin to create `*.html`-files from specified entry points.
* [@fal-works/esbuild-plugin-global-externals](https://github.com/fal-works/esbuild-plugin-global-externals): A plugin to replace module imports with global variables.
* [@linjiajian999/esbuild-plugin-import](https://github.com/linjiajian999/esbuild-plugin-import): A plugin for modular import from ant, lodash, etc., similar to [babel-plugin-import](https://github.com/ant-design/babel-plugin-import).
* [@yarnpkg/esbuild-plugin-pnp](https://github.com/yarnpkg/berry/tree/master/packages/esbuild-plugin-pnp#yarnpkgesbuild-plugin-pnp): A plugin adding support for [Yarn Plug'n'Play](https://yarnpkg.com/features/pnp) installs.
* [decky](https://github.com/jarred-sumner/decky): A plugin that makes TypeScript experimental decorators run at compile-time, enabling macros and potentially reducing bundle size
* [esbuild-dev-server](https://github.com/Falldot/esbuild-dev-server): A plugin allows you to start a local server with hot reloading.
* [esbuild-gas-plugin](https://github.com/mahaker/esbuild-gas-plugin): A plugin that generate codes for Google Apps Script.
* [esbuild-plugin-alias](https://github.com/igoradamenko/esbuild-plugin-alias): A plugin to resolve dynamic path aliases.
* [esbuild-plugin-assets-manifest](https://github.com/indooorsman/esbuild-plugin-assets-manifest): A plugin to Generate manifest file like assets-webpack-plugin does.
* [esbuild-plugin-babel](https://github.com/nativew/esbuild-plugin-babel): A plugin to compile files with Babel.
* [esbuild-plugin-browserify-adapter](https://github.com/m90/esbuild-plugin-browserify-adapter): An adapter to use existing Browserify transforms as esbuild plugins.
* [esbuild-plugin-browserslist](https://github.com/nihalgonsalves/esbuild-plugin-browserslist): Configure esbuild targets based on a browserslist query.
* [esbuild-plugin-cache](https://github.com/dalcib/esbuild-plugin-cache): A plugin to cache http/https modules. It works with [import-maps](https://github.com/WICG/import-maps).
* [esbuild-plugin-d.ts](https://github.com/Floffah/esbuild-plugin-d.ts): ESBuild convenience plugin for compiling typescript definitions along with javascript
* [esbuild-plugin-filelastmodified](https://github.com/g45t345rt/esbuild-plugin-filelastmodified): A plugin to replace `__fileLastModified__` with the actual time the file has been modified.
* [esbuild-plugin-flow](https://github.com/dalcib/esbuild-plugin-flow): A plugin to strip types for Flow files using flow-remove-types package.
* [esbuild-plugin-glob](https://github.com/waspeer/esbuild-plugin-glob): Use glob patterns as `entryPoints`
* [esbuild-plugin-globals](https://github.com/a-b-r-o-w-n/esbuild-plugin-globals): A plugin to replace module contents with user provided globals.
* [esbuild-plugin-ifdef](https://github.com/Jarred-Sumner/esbuild-plugin-ifdef) A plugin that adds conditional code compilation for JavaScript/TypeScript using `//#ifdef CONDITION` comments.
* [esbuild-plugin-ignore](https://github.com/Knowre-Dev/esbuild-plugin-ignore): A plugin to ignore some certain dependencies from bundling.
* [esbuild-plugin-import-glob](https://github.com/thomaschaaf/esbuild-plugin-import-glob): A plugin to import multiple files using the glob syntax. Similar to `require.context` from webpack.
* [esbuild-plugin-inline-import](https://github.com/claviska/esbuild-plugin-inline-import): A plugin that inlines and optionally transforms imports with a configurable prefix.
* [esbuild-plugin-lodash](https://github.com/josteph/esbuild-plugin-lodash): A plugin that helps tree-shake non-es lodash imports, similar to how [babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) works.
* [esbuild-plugin-manifest](https://github.com/jfortunato/esbuild-plugin-manifest): A plugin to generate a hashed asset manifest file.
* [esbuild-plugin-path-alias](https://github.com/indooorsman/esbuild-plugin-path-alias): A esbuild plugin to support path alias like `resolve.alias` in webpack config.
* [esbuild-plugin-pipe](https://github.com/nativew/esbuild-plugin-pipe): A plugin to pipe the output of esbuild plugins.
* [esbuild-plugin-pnp](https://github.com/shiftx/esbuild-plugin-pnp): A plugin to support yarn 2 (berry) with PnP (Plug’n’Play).
* [esbuild-plugin-postcss-literal](https://github.com/nativew/esbuild-plugin-postcss-literal): A plugin to transform tagged template literals with PostCSS.
* [esbuild-plugin-resolve](https://github.com/markwylde/esbuild-plugin-resolve): Change where a module dependency is resolved/imported from.
* [esbuild-plugin-stimulus](https://github.com/zombiezen/esbuild-plugin-stimulus): A plugin to automatically [load Stimulus controllers](https://stimulus.hotwire.dev/handbook/installing) from a folder.
* [esbuild-plugin-text-replace](https://github.com/aheissenberger/esbuild-plugin-text-replace): Replace content before bundling with support for Filefilter, Namespace, Regex and Functions.
* [esbuild-plugin-tsc](https://github.com/thomaschaaf/esbuild-plugin-tsc): A plugin to transform typescript files using the official [typescript compiler](https://github.com/microsoft/TypeScript). Allows usage of `emitDecoratorMetadata`.
* [esbuild-plugin-velcro](https://github.com/ggoodman/esbuild-plugin-velcro): A plugin to load npm (bare module) dependencies from the cloud and requiring no previous NPM install.
* [esbuild-plugin-webpack-bridge](https://github.com/igoradamenko/esbuild-plugin-webpack-bridge): A plugin that allows to use webpack loaders.
* [esbuild-svelte-paths](https://github.com/alexxnb/esbuild-svelte-paths): A plugin that resolves shortcuted pathes for Svelte components.
* [esbuild-plugin-solid-js](https://gitlab.com/hesxenon/esbuild-plugin-solid-js/-/tree/main): A plugin to apply solids jsx transforms with esbuild (without breaking/dropping sourcemaps)

### Plugins not hosted on npm (e.g. for Deno)

* [esbuild-plugin-http-fetch](https://deno.land/x/esbuild_plugin_http_fetch): A plugin that resolves http(s) modules, for use with browsers and Deno.

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
