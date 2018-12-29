# Awesome Parcel [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Slack](https://slack.parceljs.org/badge.svg)](https://slack.parceljs.org) [![Twitter Follow](https://img.shields.io/twitter/follow/parceljs.svg?style=social)](https://twitter.com/parceljs)

> A curated list of Parcel [plugins](https://www.npmjs.com/search?q=parcel-plugin-), articles, etc.


## Ecosystem
- [Website](https://parceljs.org)
- [Documentation](https://parceljs.org/getting_started.html)
- [Repository](https://github.com/parcel-bundler/parcel)
- [Twitter](https://twitter.com/parceljs)
- [Slack](https://slack.parceljs.org/)


## Contents

- [Examples](#examples)
- [Plugins](#plugins)
    - [Templates](#templates)
    - [Frameworks](#frameworks)
    - [JavaScript dialects, other languages](#javascript-dialects-other-languages)
    - [Other](#other)
- [Integration with other languages, frameworks](#integration-with-other-languages-frameworks)
- [Articles](#articles)
    - [English](#english)
    - [Portuguese](#portuguese)
    - [Russian](#russian)
    - [French](#french)
    - [Chinese](#chinese)


## Examples

- [React](https://github.com/jaredpalmer/react-parcel-example) - Minimum viable React app.
- [React with SSR](https://github.com/gregtillbrook/react-head-start) - React starter app including Server Side Rendering and code splitting.
- [React with TypeScript](https://github.com/adhrinae/ts-react-parcel) - Example code and test cases with React, TypeScript, Jest.
- [Angular](https://github.com/DeMoorJasper/Angular-Parcel-Boilerplate) - Angular boilerplate.
- [Vue.js](https://github.com/parcel-bundler/examples/tree/master/vue) - Basic `Hello, World!` example.
- [Vue.js with Vuex and Vue Router](https://github.com/proYang/vue-parcel-demo) - Quickstart example including Code Splitting, Hot Reloading, Vuex, Vue Router and Less.
- [Metal.js](https://github.com/matuzalemsteles/metal-parcel-example) - Simple example with Metal.js.
- [ReasonReact](https://github.com/Raincal/parcel-reason-react-app) - Simple Reason React app.
- [PixiJS with Typescript](https://github.com/lucas-jones/pixi-ts-parcel-example) - Simple PixiJS starter app.


## Plugins

### Templates

- [Pug](https://github.com/Ty3uK/parcel-plugin-pug) - Pug template support.
- [Markdown](https://github.com/gongpeione/parcel-plugin-markdown) - Plugin for markdown support.
- [Markdown String](https://github.com/jaywcjlove/parcel-plugin-markdown-string) - Plugin for markdown string support.
- [Markdown with Frontmatter](https://github.com/umstek/parcel-plugin-md-fm) - Plugin for markdown with frontmatter support.
- [Mustache](https://github.com/suuzee/parcel-plugin-mustache) - Plugin for Mustache template support.
- [Nunjucks](https://github.com/devmattrick/parcel-plugin-nunjucks) - Plugin to compile Nunjucks templates.
- [Handlebars](https://github.com/TheBlackBolt/parcel-plugin-handlebars) - Plugin to compile handlebars templates.
- [Handlebars precompile](https://github.com/belicekm/parcel-plugin-handlebars-precompile) - Plugin to precompile handlebars templates into template functions.
- [Protobuf](https://github.com/Jabher/parcel-plugin-pbf) - Plugin to compile [Protocol Buffer](https://developers.google.com/protocol-buffers/) binary protocol schemas with [pbf](https://github.com/mapbox/pbf).

### Frameworks

- [Svelte](https://github.com/DeMoorJasper/parcel-plugin-svelte) - Svelte support.
- [Angular](https://github.com/fathyb/parcel-plugin-angular) - Angular support.

### JavaScript dialects, other languages

- [TypeScript](https://github.com/fathyb/parcel-plugin-typescript) - Enhanced TypeScript integration.
- [BuckleScript](https://github.com/jihchi/parcel-plugin-bucklescript) - Plugin that enables BuckleScript support
- [Elm](https://github.com/ssuman/parcel-plugin-elm) - Plugin that enables Elm support.
- [LightScript](https://github.com/chee/parcel-plugin-lightscript) - Example plugin for loading LightScript.
- [Emscripten](https://github.com/taktod/parcel-plugin-emc) - Plugin for Emscripten support.
- [Fable](https://github.com/slogsdon/parcel-plugin-fable) - Enable F# support via Fable + Babel.

### Other

- [ESLint](https://github.com/BoltDoggy/parcel-plugin-eslint) - Plugin for ESlint support.
- [Bundle Manifest](https://github.com/mugi-uno/parcel-plugin-bundle-manifest) - Plugin for generating a bundle manifest.
- [AppCache](https://github.com/pierredavidbelanger/parcel-plugin-appcache) - Plugin for generating an appcache manifest.
- [Inline SVG](https://github.com/albinotonnina/parcel-plugin-inlinesvg) - Plugin that enables inline svg support.
- [Wrapper](https://github.com/albinotonnina/parcel-plugin-wrapper) - Plugin that wraps output files with custom text or code.
- [Url-Loader](https://github.com/fansenze/parcel-plugin-url-loader) - Plugin that enables convert image to base64 in `.js`.
- [Google Closure](https://github.com/fathyb/parcel-plugin-closure) - Plugin that uses Google Closure compiler to minify and tree-shake JavaScript.
- [Image minification](https://github.com/DeMoorJasper/parcel-plugin-imagemin) - Plugin that uses imagemin to minify images on build
- [Bundle Visualiser](https://github.com/gregtillbrook/parcel-plugin-bundle-visualiser) - Plugin to visualise bundle contents (the parcel version of webpacks [webpack-bundle-analyzer](https://www.npmjs.com/package/webpack-bundle-analyzer))
- [css to style object](https://www.npmjs.com/package/parcel-plugin-css-object) import css as object
- [SW Precache](https://github.com/cyyyu/parcel-plugin-sw-precache) Plugin to generate a service worker file that will precache resources so they work offline. (PWA)
- [react-native-web](https://github.com/dalcib/parcel-plugin-react-native-web) - Plugin that enables [react-native-web](https://github.com/necolas/react-native-web) support.
- [web-extension](https://github.com/kevincharm/parcel-plugin-web-extension) - Plugin that enables to use a WebExtension `manifest.json` as an entry point.
- [Static Files Copy](https://github.com/elwin013/parcel-plugin-static-files-copy) - Plugin that copies static files into bundle directory.
- [Inliner](https://github.com/shff/parcel-plugin-inliner) - Inlines all your CSS, JS and images in a single HTML file. Great for small websites.
- [PurifyCSS](https://github.com/shff/parcel-plugin-purifycss) - Removes unused selectors from your CSS files using [PurifyCSS](https://github.com/purifycss/purifycss).
- [PurgeCSS](https://github.com/cprecioso/parcel-plugin-purgecss) - Removes unused selectors from your CSS files using [PurgeCSS](https://github.com/FullHuman/purgecss).
- [Modernizr](https://github.com/hirasso/parcel-plugin-modernizr) - Generates a custom modernizr build
- [Watch Reload](https://github.com/hirasso/parcel-plugin-watch-reload) - Watches files outside of parcel bundles and sends a reload request to parcel if they change
- [HTML Interpolation](https://github.com/krotovic/parcel-plugin-interpolate-html) - Interpolation plugin that gives you option to use your .env variable inside HTML
- [Static ZIP](https://github.com/agentcooper/parcel-plugin-static-zip) - Provide archived local directory in the static build. Useful for BrowserFS.
- [Shebang](https://github.com/sintloer/parcel-plugin-shebang) - Add a shebang to the output files (useful for CLI applications).
- [data-src](https://github.com/arnellebalane/parcel-plugin-data-src) - Bundles resources defined in `data-srcset` and `data-src` HTML attributes.
- [compress](https://github.com/ralscha/parcel-plugin-compress) - Precompresses (gzip, brotli) build output with [@gfx/zopfli](https://github.com/gfx/universal-zopfli-js) and [brotli](https://www.npmjs.com/package/brotli)

## Integration with other languages, frameworks

- [parcel-rails](https://github.com/michaldarda/parcel-rails) - Ruby On Rails gem, for easier integration into Rails applications

## Articles

### English

- [Announcing Parcel: A blazing fast, zero configuration web application bundler](https://hackernoon.com/announcing-parcel-a-blazing-fast-zero-configuration-web-application-bundler-feac43aac0f1?source=search_post---------0)
- [Parcel Bundler with React and Hot Module Replacement](https://medium.com/@d.kang/parcel-bundler-with-react-and-hot-module-replacement-7f92efd25584)
- [Code Splitting with Parcel Web App Bundler](https://hackernoon.com/code-splitting-with-parcel-web-app-bundler-fe06cc3a20da)
- [Parcel: A Zero-Configuration Webpack Alternative](https://www.youtube.com/watch?v=4XB6jcyiADY) - Get started with Parcel in 20 minutes(video)

### Portuguese

- [Parcel Bundler: Criando um projeto React](https://medium.com/tableless/parcel-bundler-criando-um-projeto-react-1a620a151e34)

### Russian

- [Parcel — очень быстрый бандлер, не требующий настройки](https://habrahabr.ru/post/344486/) - Parcel quick review.
- [Parcel — пишем плагин](https://habrahabr.ru/post/344858/) - How to write a Parcel plugin.

### French

- [Parcel - Présentation](https://www.grafikart.fr/tutoriels/javascript/parcel-bundler-985) - Parcel review (video)
- [Parcel - Changer le bundler de Phoenix](https://medium.com/@_MaximeBlanc/phoenix-changer-de-bundler-e53f00110740) - Integration in a framework

### Chinese

- [下一代零配置打包工具 Parcel 初体验](https://zhuanlan.zhihu.com/p/34033344) - Quick view of the next generation bundler Parcel
- [Parcel 教程？不需要。](https://blog.zfanw.com/parcel-bundler-tutorial/) - You don't need a tutorial for Parcel since it's so easy
## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.


## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Maksim Karelov](https://github.com/Ty3uK) has waived all copyright and
related or neighboring rights to this work.
