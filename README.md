# Community plugins for [esbuild](https://esbuild.github.io/)

⚠️ *These plugins are from the community and are not officially supported.* ⚠️

This is just a centralized list of 3rd-party plugins to make discovery easier. No guarantees are made as to plugin quality, compatibility, or lack of malicious code. As with all 3rd-party dependencies, you should review them yourself before including them in your project.

## Plugin list

* [esbuild-graphql-loader](https://github.com/luckycatfactory/esbuild-graphql-loader): A plugin allowing for GraphQL file imports.
* [esbuild-plugin-cache](https://github.com/dalcib/esbuild-plugin-cache): A plugin to cache http/https modules. It works with [import-maps](https://github.com/WICG/import-maps)
* [esbuild-plugin-flow](https://github.com/dalcib/esbuild-plugin-flow): A plugin to strip types for Flow files using flow-remove-types package.
* [esbuild-plugin-glsl](https://github.com/vanruesc/esbuild-plugin-glsl): A plugin that adds support for GLSL file imports with optional shader minification.
* [esbuild-plugin-ignore](https://github.com/Knowre-Dev/esbuild-plugin-ignore): A plugin to ignore some certain dependencies from bundling.
* [esbuild-plugin-pnp](https://github.com/shiftx/esbuild-plugin-pnp): A plugin to support yarn 2 (berry) with PnP (Plug’n’Play).
* [esbuild-plugin-velcro](https://github.com/ggoodman/esbuild-plugin-velcro): A plugin to load npm (bare module) dependencies from the cloud and requiring no previous npm install.
* [esbuild-stylus-loader](https://github.com/ym-project/esbuild-stylus-loader): A plugin to transform stylus files to css files.
* [esbuild-svelte](https://github.com/EMH333/esbuild-svelte): A plugin to load and compile Svelte components.
* [esbuild-svelte-paths](https://github.com/alexxnb/esbuild-svelte-paths): A plugin that resolves shortcuted pathes for Svelte components.

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

* [example-esbuild-plugin](https://github.com/esbuild/example-esbuild-plugin): A plugin to load `*.example` files.

Before creating a PR, please make sure that:

* The package is already published to npm
* You are the author of the plugin
* You are willing to respond to issues about the plugin if people file issues against it
