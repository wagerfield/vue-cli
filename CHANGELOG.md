<a name="3.0.0-beta.11"></a>
# [3.0.0-beta.11](https://github.com/vuejs/vue-cli/compare/v3.0.0-beta.10...v3.0.0-beta.11) (2018-05-21)


### Bug Fixes

* css sourceMap in production ([#1270](https://github.com/vuejs/vue-cli/issues/1270)) ([2d09a4c](https://github.com/vuejs/vue-cli/commit/2d09a4c))
* **css:** css-loader importLoaders should account for vue-loader's injected ([853662c](https://github.com/vuejs/vue-cli/commit/853662c)), closes [#1267](https://github.com/vuejs/vue-cli/issues/1267)
* fix babel.config.js compat in vue-jest ([48d7e00](https://github.com/vuejs/vue-cli/commit/48d7e00))
* fix transpileDependencies by always using babel.config.js ([1279b3e](https://github.com/vuejs/vue-cli/commit/1279b3e))
* **eslint:** ensure all config values are contained in config file ([83f5f4f](https://github.com/vuejs/vue-cli/commit/83f5f4f)), closes [#1006](https://github.com/vuejs/vue-cli/issues/1006) [#1313](https://github.com/vuejs/vue-cli/issues/1313)
* fix ts/tsx rule separation ([41a56f1](https://github.com/vuejs/vue-cli/commit/41a56f1)), closes [#1315](https://github.com/vuejs/vue-cli/issues/1315)
* handle failed git commit ([a1ccde8](https://github.com/vuejs/vue-cli/commit/a1ccde8)), closes [#1306](https://github.com/vuejs/vue-cli/issues/1306)
* rename test-utils `shallow` to `shallowMount` ([#1269](https://github.com/vuejs/vue-cli/issues/1269)) ([5c54df7](https://github.com/vuejs/vue-cli/commit/5c54df7))
* stringifyJS should be used in all call sites ([07ac887](https://github.com/vuejs/vue-cli/commit/07ac887))
* typo in vue-loader compilerOptions ([#1263](https://github.com/vuejs/vue-cli/issues/1263)) ([b2b277a](https://github.com/vuejs/vue-cli/commit/b2b277a))


### Features

* **build:** add 'watch' option ([#1332](https://github.com/vuejs/vue-cli/issues/1332)) ([6ea17c9](https://github.com/vuejs/vue-cli/commit/6ea17c9))
* **cli-service:** add assetsDir option to specify assets root directory ([#1322](https://github.com/vuejs/vue-cli/issues/1322)) ([9638d90](https://github.com/vuejs/vue-cli/commit/9638d90)), closes [#1311](https://github.com/vuejs/vue-cli/issues/1311)
* **eslint:** add --max-warnings and --max-errors for cli-plugin-eslint ([#1289](https://github.com/vuejs/vue-cli/issues/1289)) ([ab877a2](https://github.com/vuejs/vue-cli/commit/ab877a2)), closes [#1268](https://github.com/vuejs/vue-cli/issues/1268)
* **eslint:** enable caching ([ff0f97b](https://github.com/vuejs/vue-cli/commit/ff0f97b))
* **eslint:** pass cli arguments to linter ([#1258](https://github.com/vuejs/vue-cli/issues/1258)) ([9ac2642](https://github.com/vuejs/vue-cli/commit/9ac2642)), closes [#1255](https://github.com/vuejs/vue-cli/issues/1255)
* **inspect:** add --rule and --plugin options for inspect command ([82349ba](https://github.com/vuejs/vue-cli/commit/82349ba))
* **inspect:** add --rules and --plugins options for inspect command ([fd1c0d5](https://github.com/vuejs/vue-cli/commit/fd1c0d5))
* support `<style lang="postcss">` ([#1259](https://github.com/vuejs/vue-cli/issues/1259)) ([1037b9c](https://github.com/vuejs/vue-cli/commit/1037b9c))
* **inspect:** improve `vue inspect` output with webpack-chain hints ([f6bfb63](https://github.com/vuejs/vue-cli/commit/f6bfb63)), closes [#881](https://github.com/vuejs/vue-cli/issues/881)
* allow disabling serve progress via devServer.progress ([da38747](https://github.com/vuejs/vue-cli/commit/da38747)), closes [#1284](https://github.com/vuejs/vue-cli/issues/1284)
* allow router/vuex to be late added via `vue add` ([2a195f0](https://github.com/vuejs/vue-cli/commit/2a195f0)), closes [#1202](https://github.com/vuejs/vue-cli/issues/1202) [#1204](https://github.com/vuejs/vue-cli/issues/1204)
* ask for whether to use taobao registry when getting versions ([#1273](https://github.com/vuejs/vue-cli/issues/1273)) ([8fbbd35](https://github.com/vuejs/vue-cli/commit/8fbbd35))
* GeneratorAPI: addImports & addRootOptions ([8b32f4a](https://github.com/vuejs/vue-cli/commit/8b32f4a))
* make it possible to opt-out of Babel ([d75ea99](https://github.com/vuejs/vue-cli/commit/d75ea99)), closes [#1199](https://github.com/vuejs/vue-cli/issues/1199)
* support webp ([763cf7a](https://github.com/vuejs/vue-cli/commit/763cf7a)), closes [#1321](https://github.com/vuejs/vue-cli/issues/1321)
* temporarily fix source map by patching babel ([453597a](https://github.com/vuejs/vue-cli/commit/453597a))



<a name="3.0.0-beta.10"></a>
# [3.0.0-beta.10](https://github.com/vuejs/vue-cli/compare/v3.0.0-beta.9...v3.0.0-beta.10) (2018-05-11)


### Bug Fixes

* **build:** fix --dest flag regression ([fd9d255](https://github.com/vuejs/vue-cli/commit/fd9d255)), closes [#1193](https://github.com/vuejs/vue-cli/issues/1193)
* **serve:** fix non-GET requests match error w/ multi-proxy config ([c4c4bff](https://github.com/vuejs/vue-cli/commit/c4c4bff)), closes [#1210](https://github.com/vuejs/vue-cli/issues/1210)
* **tslint:** don't change working directory ([#1225](https://github.com/vuejs/vue-cli/issues/1225)) ([8dbe262](https://github.com/vuejs/vue-cli/commit/8dbe262))
* **typescript:** add node_modules/** to tslint default excludes ([#1200](https://github.com/vuejs/vue-cli/issues/1200)) ([a6e47ce](https://github.com/vuejs/vue-cli/commit/a6e47ce)), closes [#1194](https://github.com/vuejs/vue-cli/issues/1194)
* **typescript:** separate tsx shim ([51c8090](https://github.com/vuejs/vue-cli/commit/51c8090)), closes [#1198](https://github.com/vuejs/vue-cli/issues/1198)
* css imports from js ([1b5bdde](https://github.com/vuejs/vue-cli/commit/1b5bdde))
* ensure dynamic publicPath is set early in lib/wc mode ([c3d246f](https://github.com/vuejs/vue-cli/commit/c3d246f)), closes [#1253](https://github.com/vuejs/vue-cli/issues/1253)
* improve error message when entry is missing w/ --target lib ([8b4a112](https://github.com/vuejs/vue-cli/commit/8b4a112)), closes [#1051](https://github.com/vuejs/vue-cli/issues/1051)
* pwa plugin compat with webpack 4 ([6d1716e](https://github.com/vuejs/vue-cli/commit/6d1716e))
* respect chunk name in all build targets ([66bab8c](https://github.com/vuejs/vue-cli/commit/66bab8c)), closes [#1251](https://github.com/vuejs/vue-cli/issues/1251)


### Code Refactoring

* adjust mode loading order ([d595ada](https://github.com/vuejs/vue-cli/commit/d595ada)), closes [#959](https://github.com/vuejs/vue-cli/issues/959)
* rename test commands ([69ebd80](https://github.com/vuejs/vue-cli/commit/69ebd80)), closes [#876](https://github.com/vuejs/vue-cli/issues/876) [#878](https://github.com/vuejs/vue-cli/issues/878)
* require Node 8 ([6b865db](https://github.com/vuejs/vue-cli/commit/6b865db))


### Features

* default preset save to no ([ab90d50](https://github.com/vuejs/vue-cli/commit/ab90d50)), closes [#1212](https://github.com/vuejs/vue-cli/issues/1212)
* expose env variables as root level in index.html template ([4c5784d](https://github.com/vuejs/vue-cli/commit/4c5784d))
* new option "preserveWhitespace" ([ea83441](https://github.com/vuejs/vue-cli/commit/ea83441))
* relex transpile includes + new transpileDependencies option ([da4d0b2](https://github.com/vuejs/vue-cli/commit/da4d0b2))
* **babel:** better Babel polyfill defaults ([4e7d57f](https://github.com/vuejs/vue-cli/commit/4e7d57f))
* **cli:** allow local .json files for presets ([#1201](https://github.com/vuejs/vue-cli/issues/1201)) ([9766db1](https://github.com/vuejs/vue-cli/commit/9766db1)), closes [#1068](https://github.com/vuejs/vue-cli/issues/1068)
* **serve:** support entry in `vue-cli-service serve` ([05f9f3a](https://github.com/vuejs/vue-cli/commit/05f9f3a)), closes [#974](https://github.com/vuejs/vue-cli/issues/974)
* **typescript:** support lang="tsx" in vue files ([718ba3c](https://github.com/vuejs/vue-cli/commit/718ba3c)), closes [#1219](https://github.com/vuejs/vue-cli/issues/1219)
* remove DLL option ([6d4e51d](https://github.com/vuejs/vue-cli/commit/6d4e51d))
* support { prompts: true } for preset plugins ([3dd38da](https://github.com/vuejs/vue-cli/commit/3dd38da)), closes [#952](https://github.com/vuejs/vue-cli/issues/952)
* upgrade to vue-loader 15 ([f5c0f58](https://github.com/vuejs/vue-cli/commit/f5c0f58))
* upgrade to webpack 4 ([2dcdedd](https://github.com/vuejs/vue-cli/commit/2dcdedd))


### Reverts

* feat: new option "preserveWhitespace"" ([a8af883](https://github.com/vuejs/vue-cli/commit/a8af883))


### BREAKING CHANGES

* `css.modules` option has been removed. To import css files (or
any other supported pre-processor files) as CSS Modules, append the request
with a `?module` resourceQuery.
* Upgrade wepback 4, all webpack option
modifications must be webpcak 4 compatible. Drop support
for webpack plugins that do not work with v4 or above.
* dll option has been removed.
* the "vueLoader" option has been removed. To modify vue-loader
options, use chainWebpack then `config.module.rule(vue).use(vue-loader).tap()`.
vue-loader has been upgraded to v15 and expects different options from v14.
* To include a dependency for Babel transpilation, tapping
babel-loader and adding .include() will no longer work. Use the new
transpileDependencies option instead.
* `cli-plugin-unit-jest` and `cli-plugin-unit-mocha` now register
"test:unit" command and script instead of "test"; `cli-plugin-e2e-cypress` now
register "test:e2e" with optional `--headless` flag instead of "e2e" and
"e2e:open"; `cli-plugin-e2e-nightwatch` now register "test:e2e" instead of "e2e".
* PluginAPI.setMode() has been removed. Instead, for a plugin to
sepcify the default mode for a registered command, the plugins should expose
`module.exports.defaultModes` in the form of `{ [commandName]: mode }`.
* @vue/cli-service and all plugins now require Node version 8+.



<a name="3.0.0-beta.9"></a>
# [3.0.0-beta.9](https://github.com/vuejs/vue-cli/compare/v3.0.0-beta.8...v3.0.0-beta.9) (2018-04-28)


### Bug Fixes

* **dependencies:** add deepmerge dependencies ([#1188](https://github.com/vuejs/vue-cli/issues/1188)) ([67fa39d](https://github.com/vuejs/vue-cli/commit/67fa39d)), closes [#1187](https://github.com/vuejs/vue-cli/issues/1187)



<a name="3.0.0-beta.8"></a>
# [3.0.0-beta.8](https://github.com/vuejs/vue-cli/compare/v3.0.0-beta.7...v3.0.0-beta.8) (2018-04-27)


### Bug Fixes

* --target lib/wc should overwrite user entry/output ([92e136a](https://github.com/vuejs/vue-cli/commit/92e136a)), closes [#1072](https://github.com/vuejs/vue-cli/issues/1072)
* add name to chunk file output ([#1173](https://github.com/vuejs/vue-cli/issues/1173)) ([1fc9593](https://github.com/vuejs/vue-cli/commit/1fc9593))
* allow user to define testMatch in package.json ([#1069](https://github.com/vuejs/vue-cli/issues/1069)) ([cac18f2](https://github.com/vuejs/vue-cli/commit/cac18f2)), closes [#1067](https://github.com/vuejs/vue-cli/issues/1067)
* avoid emoji length problem in update log (close [#835](https://github.com/vuejs/vue-cli/issues/835)) ([fb7ccb6](https://github.com/vuejs/vue-cli/commit/fb7ccb6))
* css.extract options handling ([8e72943](https://github.com/vuejs/vue-cli/commit/8e72943)), closes [#1061](https://github.com/vuejs/vue-cli/issues/1061)
* deep merge objects when extending package.json via plugins ([#1070](https://github.com/vuejs/vue-cli/issues/1070)) ([6af7bbe](https://github.com/vuejs/vue-cli/commit/6af7bbe)), closes [#1053](https://github.com/vuejs/vue-cli/issues/1053)
* include test -> tests for eslint-loader ([3d29458](https://github.com/vuejs/vue-cli/commit/3d29458))
* pass all parameters to onProxyReq in proxy configuration ([#1083](https://github.com/vuejs/vue-cli/issues/1083)) ([65ee2fa](https://github.com/vuejs/vue-cli/commit/65ee2fa))
* **build:** copy plugin should be loaded in all cases ([87892a5](https://github.com/vuejs/vue-cli/commit/87892a5)), closes [#1073](https://github.com/vuejs/vue-cli/issues/1073)
* **build-wc:** honor custom component name for single file wc builds ([#1182](https://github.com/vuejs/vue-cli/issues/1182)) ([2b236e0](https://github.com/vuejs/vue-cli/commit/2b236e0)), closes [#1146](https://github.com/vuejs/vue-cli/issues/1146)
* **cli:** fix invoke glob node_modules ignore pattern ([#1004](https://github.com/vuejs/vue-cli/issues/1004)) ([708cde9](https://github.com/vuejs/vue-cli/commit/708cde9))
* **cli-service:** should not add a leading slash to baseUrl when it is absolute ([#1172](https://github.com/vuejs/vue-cli/issues/1172)) ([abb82ab](https://github.com/vuejs/vue-cli/commit/abb82ab)), closes [#1084](https://github.com/vuejs/vue-cli/issues/1084)
* **eslint:** fix --no-fix flag when linting with typescript plugin ([#1115](https://github.com/vuejs/vue-cli/issues/1115)) ([83171e4](https://github.com/vuejs/vue-cli/commit/83171e4))
* **serve:** don't set header origin if using an agent ([#1179](https://github.com/vuejs/vue-cli/issues/1179)) ([79bc088](https://github.com/vuejs/vue-cli/commit/79bc088))
* **typescript:** fix invalid tsconfig.json ([#1036](https://github.com/vuejs/vue-cli/issues/1036)) ([c49eeb7](https://github.com/vuejs/vue-cli/commit/c49eeb7))
* **typescript,babel:** tests path for babel and typescript plugins ([#1058](https://github.com/vuejs/vue-cli/issues/1058)) ([b285b0b](https://github.com/vuejs/vue-cli/commit/b285b0b))
* validate project name ([#1039](https://github.com/vuejs/vue-cli/issues/1039)) ([78ed155](https://github.com/vuejs/vue-cli/commit/78ed155)), closes [#1024](https://github.com/vuejs/vue-cli/issues/1024)
* vue invoke should delete renamed/removed files ([#1049](https://github.com/vuejs/vue-cli/issues/1049)) ([c648301](https://github.com/vuejs/vue-cli/commit/c648301))
* **unit-jest:** handle static asset imports ([#1180](https://github.com/vuejs/vue-cli/issues/1180)) ([be3bede](https://github.com/vuejs/vue-cli/commit/be3bede))


### Features

* **babel:** expose loose option ([7a125d4](https://github.com/vuejs/vue-cli/commit/7a125d4))
* **cli:** skip git if already in a git repo, add --skipGit option ([23480ae](https://github.com/vuejs/vue-cli/commit/23480ae)), closes [#967](https://github.com/vuejs/vue-cli/issues/967)
* **e2e-nightwatch:** allow using custom config via --config flag ([#1016](https://github.com/vuejs/vue-cli/issues/1016)) ([e4d67d6](https://github.com/vuejs/vue-cli/commit/e4d67d6))
* **inspect:** add a -v/--verbose flag to inspect command to output full functions ([#1175](https://github.com/vuejs/vue-cli/issues/1175)) ([6ca86aa](https://github.com/vuejs/vue-cli/commit/6ca86aa)), closes [#1157](https://github.com/vuejs/vue-cli/issues/1157)
* allow specifying proxy when creating project ([b1512be](https://github.com/vuejs/vue-cli/commit/b1512be)), closes [#1009](https://github.com/vuejs/vue-cli/issues/1009)
* support custom initial commit message ([#1116](https://github.com/vuejs/vue-cli/issues/1116)) ([11ccf64](https://github.com/vuejs/vue-cli/commit/11ccf64))
* warn when user modifies output.path directly ([81d29ab](https://github.com/vuejs/vue-cli/commit/81d29ab))
* **plugin-api:** allow non-semver versioned dependencies ([#1184](https://github.com/vuejs/vue-cli/issues/1184)) ([0f76b8e](https://github.com/vuejs/vue-cli/commit/0f76b8e)), closes [#1177](https://github.com/vuejs/vue-cli/issues/1177)
* **pwa:** Make injected meta tags configurable and change defaults ([#961](https://github.com/vuejs/vue-cli/issues/961)) ([36f954b](https://github.com/vuejs/vue-cli/commit/36f954b))
* **typescript:** improve tsx support ([#1168](https://github.com/vuejs/vue-cli/issues/1168)) ([3aa3743](https://github.com/vuejs/vue-cli/commit/3aa3743))



<a name="3.0.0-beta.7"></a>
# [3.0.0-beta.7](https://github.com/vuejs/vue-cli/compare/v3.0.0-beta.6...v3.0.0-beta.7) (2018-04-25)


### Bug Fixes

* allow user to define onProxyReq ([#955](https://github.com/vuejs/vue-cli/issues/955)) ([179033d](https://github.com/vuejs/vue-cli/commit/179033d))
* **invoke:** issue [#1037](https://github.com/vuejs/vue-cli/issues/1037) invoke binary files ([#1038](https://github.com/vuejs/vue-cli/issues/1038)) ([e65110f](https://github.com/vuejs/vue-cli/commit/e65110f))
* babel legacy decorator ([#1163](https://github.com/vuejs/vue-cli/issues/1163)) ([fb013da](https://github.com/vuejs/vue-cli/commit/fb013da))
* pin babel version (fix [#1162](https://github.com/vuejs/vue-cli/issues/1162)) ([dbc3f10](https://github.com/vuejs/vue-cli/commit/dbc3f10))


### Features

* allow vue add to work with plugins without a generator ([#1032](https://github.com/vuejs/vue-cli/issues/1032)) ([11956ac](https://github.com/vuejs/vue-cli/commit/11956ac))
* use `esnext` targets for downleveling and modules. ([#966](https://github.com/vuejs/vue-cli/issues/966)) ([ba5a375](https://github.com/vuejs/vue-cli/commit/ba5a375))



<a name="3.0.0-beta.6"></a>
# [3.0.0-beta.6](https://github.com/vuejs/vue-cli/compare/v3.0.0-beta.5...v3.0.0-beta.6) (2018-03-06)


### Bug Fixes

* do not exit with 1 on lint warnings (fix [#872](https://github.com/vuejs/vue-cli/issues/872)) ([b162cab](https://github.com/vuejs/vue-cli/commit/b162cab))
* fix [@vue](https://github.com/vue)/cli-service initial version ([08add21](https://github.com/vuejs/vue-cli/commit/08add21))
* fix babel preset jsx dependency ([2eb1ef9](https://github.com/vuejs/vue-cli/commit/2eb1ef9))
* fix cases where error fails to display ([dee7809](https://github.com/vuejs/vue-cli/commit/dee7809))
* fix devServer proxy when using object syntax (fix [#945](https://github.com/vuejs/vue-cli/issues/945)) ([114e085](https://github.com/vuejs/vue-cli/commit/114e085))
* use dynamic publicPath for web component bundles (fix [#949](https://github.com/vuejs/vue-cli/issues/949)) ([f744040](https://github.com/vuejs/vue-cli/commit/f744040))



<a name="3.0.0-beta.5"></a>
# [3.0.0-beta.5](https://github.com/vuejs/vue-cli/compare/v3.0.0-beta.4...v3.0.0-beta.5) (2018-03-05)


### Bug Fixes

* resolve template extend source from the template location (fix [#943](https://github.com/vuejs/vue-cli/issues/943)) ([89f5cc3](https://github.com/vuejs/vue-cli/commit/89f5cc3))
* temporarily disable babel plugins that are not compatible with babel 7 yet ([389ea86](https://github.com/vuejs/vue-cli/commit/389ea86))


### Features

* allow specifying plugin versions in presets ([bdce865](https://github.com/vuejs/vue-cli/commit/bdce865))



<a name="3.0.0-beta.4"></a>
# [3.0.0-beta.4](https://github.com/vuejs/vue-cli/compare/v3.0.0-beta.3...v3.0.0-beta.4) (2018-03-05)


### Bug Fixes

* fix pwa + ts + lint (close [#937](https://github.com/vuejs/vue-cli/issues/937)) ([b878767](https://github.com/vuejs/vue-cli/commit/b878767))
* mock process for 3rd party libs (close [#934](https://github.com/vuejs/vue-cli/issues/934)) ([a2ac6be](https://github.com/vuejs/vue-cli/commit/a2ac6be))
* **pwa:** set cacheid in GenerateSW mode only ([#939](https://github.com/vuejs/vue-cli/issues/939)) ([43971d8](https://github.com/vuejs/vue-cli/commit/43971d8)), closes [#891](https://github.com/vuejs/vue-cli/issues/891)
* **test:** e2e w/ typescript ([#933](https://github.com/vuejs/vue-cli/issues/933)) ([b728624](https://github.com/vuejs/vue-cli/commit/b728624))
* use same Puppeteer like in main package.json ([#942](https://github.com/vuejs/vue-cli/issues/942)) ([11192cf](https://github.com/vuejs/vue-cli/commit/11192cf))


### Features

* add `vue add` command ([#936](https://github.com/vuejs/vue-cli/issues/936)) ([896aec5](https://github.com/vuejs/vue-cli/commit/896aec5))
* allow specifying additional configs in preset ([2b9a750](https://github.com/vuejs/vue-cli/commit/2b9a750))
* Generator now supports template inheritance ([1869aa2](https://github.com/vuejs/vue-cli/commit/1869aa2))
* generatorAPI.exitLog ([#935](https://github.com/vuejs/vue-cli/issues/935)) ([0f2ee80](https://github.com/vuejs/vue-cli/commit/0f2ee80))
* initialize project with corresponding CSS pre-processor (close [#930](https://github.com/vuejs/vue-cli/issues/930)) ([811d056](https://github.com/vuejs/vue-cli/commit/811d056))
* read existing files during plugin invocation (close [#873](https://github.com/vuejs/vue-cli/issues/873)) ([de60d9f](https://github.com/vuejs/vue-cli/commit/de60d9f))
* support using remote preset (close [#884](https://github.com/vuejs/vue-cli/issues/884)) ([2d89c51](https://github.com/vuejs/vue-cli/commit/2d89c51))



<a name="3.0.0-beta.3"></a>
# [3.0.0-beta.3](https://github.com/vuejs/vue-cli/compare/v3.0.0-beta.2...v3.0.0-beta.3) (2018-03-03)


### Bug Fixes

* **dev-server:** dev server behind NAT network ([#868](https://github.com/vuejs/vue-cli/issues/868)) ([bbc931c](https://github.com/vuejs/vue-cli/commit/bbc931c)), closes [#828](https://github.com/vuejs/vue-cli/issues/828)
* **e2e:** end to end test(s) folder ([#923](https://github.com/vuejs/vue-cli/issues/923)) ([852d26c](https://github.com/vuejs/vue-cli/commit/852d26c))
* **tsconfig.json:** typo in includes ([#917](https://github.com/vuejs/vue-cli/issues/917)) ([6adc0b5](https://github.com/vuejs/vue-cli/commit/6adc0b5))
* **tslint.json:** linting of test(s) folder ([#924](https://github.com/vuejs/vue-cli/issues/924)) ([549ff7f](https://github.com/vuejs/vue-cli/commit/549ff7f))
* externalize vue-server-renderer + support dynamic import in mocha tests ([fe9aed8](https://github.com/vuejs/vue-cli/commit/fe9aed8))
* fix baseUrl normalization (close [#900](https://github.com/vuejs/vue-cli/issues/900)) ([89982df](https://github.com/vuejs/vue-cli/commit/89982df))
* fix options for css optimize plugin (close [#918](https://github.com/vuejs/vue-cli/issues/918)) ([7681106](https://github.com/vuejs/vue-cli/commit/7681106))
* include root config files in lint (close [#913](https://github.com/vuejs/vue-cli/issues/913)) ([c40a88d](https://github.com/vuejs/vue-cli/commit/c40a88d))
* respect --dest when copying static assets (close [#909](https://github.com/vuejs/vue-cli/issues/909)) ([57ce32a](https://github.com/vuejs/vue-cli/commit/57ce32a))
* respect dotfiles in public dir (fix [#880](https://github.com/vuejs/vue-cli/issues/880)) ([59ac4f4](https://github.com/vuejs/vue-cli/commit/59ac4f4))


### Features

* **css modules:** Add CSS Module localIdentName option to vue config ([#915](https://github.com/vuejs/vue-cli/issues/915)) ([31cdc86](https://github.com/vuejs/vue-cli/commit/31cdc86))
* support creating project in current directory ([#916](https://github.com/vuejs/vue-cli/issues/916)) ([6ae1569](https://github.com/vuejs/vue-cli/commit/6ae1569)), closes [#896](https://github.com/vuejs/vue-cli/issues/896)
* support dynamic import in jest tests (close [#922](https://github.com/vuejs/vue-cli/issues/922)) ([09ed0b1](https://github.com/vuejs/vue-cli/commit/09ed0b1))



<a name="3.0.0-beta.2"></a>
# [3.0.0-beta.2](https://github.com/vuejs/vue-cli/compare/v3.0.0-beta.1...v3.0.0-beta.2) (2018-02-28)


### Bug Fixes

* **cypress:** upgrade cypress and properly set base url ([#879](https://github.com/vuejs/vue-cli/issues/879)) ([46358eb](https://github.com/vuejs/vue-cli/commit/46358eb))
* do not swallow vue.config.js errors ([14a2dc7](https://github.com/vuejs/vue-cli/commit/14a2dc7)), closes [#874](https://github.com/vuejs/vue-cli/issues/874) [#866](https://github.com/vuejs/vue-cli/issues/866)
* enable html doctype by default for pug ([e15a930](https://github.com/vuejs/vue-cli/commit/e15a930)), closes [#894](https://github.com/vuejs/vue-cli/issues/894)
* fix friendly-error plugin name typo ([#882](https://github.com/vuejs/vue-cli/issues/882)) ([73ad2f8](https://github.com/vuejs/vue-cli/commit/73ad2f8))
* nightwatch helper compat with airbnb linter ([f4d1841](https://github.com/vuejs/vue-cli/commit/f4d1841)), closes [#870](https://github.com/vuejs/vue-cli/issues/870)
* ts generator & airbnb import/extensions rule compatibility ([88726a3](https://github.com/vuejs/vue-cli/commit/88726a3)), closes [#871](https://github.com/vuejs/vue-cli/issues/871)


### Code Refactoring

* change default test directory name to "tests" ([64b4515](https://github.com/vuejs/vue-cli/commit/64b4515)), closes [#877](https://github.com/vuejs/vue-cli/issues/877)


### Features

* add ability to use environment variables in vue.config.js ([#867](https://github.com/vuejs/vue-cli/issues/867)) ([92ddd09](https://github.com/vuejs/vue-cli/commit/92ddd09))
* add default <noscript> content ([#856](https://github.com/vuejs/vue-cli/issues/856)) ([a489803](https://github.com/vuejs/vue-cli/commit/a489803)), closes [#854](https://github.com/vuejs/vue-cli/issues/854)
* **cli-plugin-pwa:** Upgrade workbox-webpack-plugin to 3.0.0-beta.1 ([#897](https://github.com/vuejs/vue-cli/issues/897)) ([6d7985a](https://github.com/vuejs/vue-cli/commit/6d7985a))
* output help information on unknown CLI commands ([#857](https://github.com/vuejs/vue-cli/issues/857)) ([cd23858](https://github.com/vuejs/vue-cli/commit/cd23858)), closes [#849](https://github.com/vuejs/vue-cli/issues/849)
* preserveWhitespace: false ([1864cef](https://github.com/vuejs/vue-cli/commit/1864cef))


### BREAKING CHANGES

* all tests are now located in "tests" instead of "test"
* preserveWhitespace now defaults to false in vue-loader options.



<a name="3.0.0-beta.1"></a>
# [3.0.0-beta.1](https://github.com/vuejs/vue-cli/compare/v3.0.0-alpha.13...v3.0.0-beta.1) (2018-02-16)


### Bug Fixes

* **babel preset:** allow setting `useBuiltIns` to be `false`. ([#843](https://github.com/vuejs/vue-cli/issues/843)) ([a9ac1a9](https://github.com/vuejs/vue-cli/commit/a9ac1a9))
* also include import rule in eslint plugin ([e8f036b](https://github.com/vuejs/vue-cli/commit/e8f036b))
* eslint + airbnb compat with TypeScript ([d391e47](https://github.com/vuejs/vue-cli/commit/d391e47))
* fix core-js import for global service ([3a5d125](https://github.com/vuejs/vue-cli/commit/3a5d125)), closes [#837](https://github.com/vuejs/vue-cli/issues/837)
* fix eslint-loader for TypeScript ([9f5d0b9](https://github.com/vuejs/vue-cli/commit/9f5d0b9))



<a name="3.0.0-alpha.13"></a>
# [3.0.0-alpha.13](https://github.com/vuejs/vue-cli/compare/v3.0.0-alpha.12...v3.0.0-alpha.13) (2018-02-13)


### Bug Fixes

* include missing dep (fix [#831](https://github.com/vuejs/vue-cli/issues/831)) ([6a0bc17](https://github.com/vuejs/vue-cli/commit/6a0bc17))



<a name="3.0.0-alpha.12"></a>
# [3.0.0-alpha.12](https://github.com/vuejs/vue-cli/compare/v3.0.0-alpha.11...v3.0.0-alpha.12) (2018-02-12)


### Bug Fixes

* fix usage with https proxy by switching from axios to request ([#829](https://github.com/vuejs/vue-cli/issues/829)) ([e8aa688](https://github.com/vuejs/vue-cli/commit/e8aa688)), closes [#785](https://github.com/vuejs/vue-cli/issues/785)
* make extension test for font files case-insensitive ([#830](https://github.com/vuejs/vue-cli/issues/830)) ([d7cfa00](https://github.com/vuejs/vue-cli/commit/d7cfa00))
* only enable TSLint when tslint.json exists ([76d7f77](https://github.com/vuejs/vue-cli/commit/76d7f77))


### Features

* allow e2e plugins to sepcify which mode the server should start in ([8f8fe6d](https://github.com/vuejs/vue-cli/commit/8f8fe6d)), closes [#814](https://github.com/vuejs/vue-cli/issues/814)
* expose useBuiltIns options in [@vue](https://github.com/vue)/babel-preset-app ([8e0661e](https://github.com/vuejs/vue-cli/commit/8e0661e)), closes [#812](https://github.com/vuejs/vue-cli/issues/812)
* lintOnSave no longer causes compilation to fail ([9040df8](https://github.com/vuejs/vue-cli/commit/9040df8)), closes [#817](https://github.com/vuejs/vue-cli/issues/817)
* use eslint-plugin-cypress ([9410442](https://github.com/vuejs/vue-cli/commit/9410442)), closes [#815](https://github.com/vuejs/vue-cli/issues/815)
* use more descriptive classNames for CSS modules ([fd13106](https://github.com/vuejs/vue-cli/commit/fd13106)), closes [#813](https://github.com/vuejs/vue-cli/issues/813)



<a name="3.0.0-alpha.11"></a>
# [3.0.0-alpha.11](https://github.com/vuejs/vue-cli/compare/v3.0.0-alpha.10...v3.0.0-alpha.11) (2018-02-09)


### Bug Fixes

* eslint config should be root ([ea74da1](https://github.com/vuejs/vue-cli/commit/ea74da1))
* **eslint:** load node env by default (fix [#806](https://github.com/vuejs/vue-cli/issues/806)) ([c2e3228](https://github.com/vuejs/vue-cli/commit/c2e3228))
* respect user configured output path ([b5564af](https://github.com/vuejs/vue-cli/commit/b5564af)), closes [#809](https://github.com/vuejs/vue-cli/issues/809)



<a name="3.0.0-alpha.10"></a>
# [3.0.0-alpha.10](https://github.com/vuejs/vue-cli/compare/v3.0.0-alpha.9...v3.0.0-alpha.10) (2018-02-08)


### Bug Fixes

* fix pwa info link (close [#801](https://github.com/vuejs/vue-cli/issues/801)) ([a0004ea](https://github.com/vuejs/vue-cli/commit/a0004ea))
* vue-class-component and vue-property-decorators should be dependencies ([c26559d](https://github.com/vuejs/vue-cli/commit/c26559d))


### Features

* include eslint:recommended in prettier config ([e261718](https://github.com/vuejs/vue-cli/commit/e261718))
* support using ESLint to lint TypeScript ([dd04add](https://github.com/vuejs/vue-cli/commit/dd04add))



<a name="3.0.0-alpha.9"></a>
# [3.0.0-alpha.9](https://github.com/vuejs/vue-cli/compare/v3.0.0-alpha.8...v3.0.0-alpha.9) (2018-02-06)


### Bug Fixes

* **unit-mocha:** fix test glob to avoid running e2e tests ([172e8eb](https://github.com/vuejs/vue-cli/commit/172e8eb)), closes [#790](https://github.com/vuejs/vue-cli/issues/790)
* handle vue invoke config merging for existing files ([46166fb](https://github.com/vuejs/vue-cli/commit/46166fb)), closes [#788](https://github.com/vuejs/vue-cli/issues/788)
* object returned from api.configureWebpack should be merged ([920d8fa](https://github.com/vuejs/vue-cli/commit/920d8fa))
* only support taobao check and inline registry when using npm ([67df3eb](https://github.com/vuejs/vue-cli/commit/67df3eb)), closes [#789](https://github.com/vuejs/vue-cli/issues/789)


### Features

* Use the Workbox webpack plugin in pwa template ([#769](https://github.com/vuejs/vue-cli/issues/769)) ([9095483](https://github.com/vuejs/vue-cli/commit/9095483))



<a name="3.0.0-alpha.8"></a>
# [3.0.0-alpha.8](https://github.com/vuejs/vue-cli/compare/v3.0.0-alpha.7...v3.0.0-alpha.8) (2018-02-04)


### Bug Fixes

* fix eslint errors when using airbnb + cypress ([313533d](https://github.com/vuejs/vue-cli/commit/313533d))
* fix jest test match ([2c61d23](https://github.com/vuejs/vue-cli/commit/2c61d23)), closes [#771](https://github.com/vuejs/vue-cli/issues/771)
* fix overwrite prompt ([7871c5c](https://github.com/vuejs/vue-cli/commit/7871c5c))
* include version marker in workspace ([d3d040a](https://github.com/vuejs/vue-cli/commit/d3d040a)), closes [#772](https://github.com/vuejs/vue-cli/issues/772)
* **inspect:** correct usage of `resolve` ([#773](https://github.com/vuejs/vue-cli/issues/773)) ([0f9a44a](https://github.com/vuejs/vue-cli/commit/0f9a44a))
* move plugin data extraction into GeneratorAPI ([4f2f6f0](https://github.com/vuejs/vue-cli/commit/4f2f6f0))
* shim global for node modules ([691cfa2](https://github.com/vuejs/vue-cli/commit/691cfa2)), closes [#774](https://github.com/vuejs/vue-cli/issues/774)


### Features

* build --target wc-async ([50fdd9b](https://github.com/vuejs/vue-cli/commit/50fdd9b))
* polish build output ([dc29e88](https://github.com/vuejs/vue-cli/commit/dc29e88))
* update default component content ([59f5913](https://github.com/vuejs/vue-cli/commit/59f5913))



<a name="3.0.0-alpha.7"></a>
# [3.0.0-alpha.7](https://github.com/vuejs/vue-cli/compare/v3.0.0-alpha.6...v3.0.0-alpha.7) (2018-02-02)


### Bug Fixes

* ensure vue init works when installed with npm ([6ce8565](https://github.com/vuejs/vue-cli/commit/6ce8565))


### Features

* check and show newer version on create ([3df1289](https://github.com/vuejs/vue-cli/commit/3df1289))
* support prompts when invoking plugins ([c1142e2](https://github.com/vuejs/vue-cli/commit/c1142e2))



<a name="3.0.0-alpha.6"></a>
# [3.0.0-alpha.6](https://github.com/vuejs/vue-cli/compare/v3.0.0-alpha.5...v3.0.0-alpha.6) (2018-02-02)


### Bug Fixes

* --target for global build ([4fb4e35](https://github.com/vuejs/vue-cli/commit/4fb4e35))
* allow console during dev ([5ad8fae](https://github.com/vuejs/vue-cli/commit/5ad8fae))
* avoid deepmerge on project config ([7d590d8](https://github.com/vuejs/vue-cli/commit/7d590d8))
* compatible with safari 10 ([#755](https://github.com/vuejs/vue-cli/issues/755)) ([199c754](https://github.com/vuejs/vue-cli/commit/199c754))
* do not extract vue.config.js in tests ([7874b0e](https://github.com/vuejs/vue-cli/commit/7874b0e))
* ensure loaders exist ([fcfb099](https://github.com/vuejs/vue-cli/commit/fcfb099))
* fix --force flag ([6661ac2](https://github.com/vuejs/vue-cli/commit/6661ac2))
* fix project creation when path contains spaces (fix [#742](https://github.com/vuejs/vue-cli/issues/742)) ([5be05f3](https://github.com/vuejs/vue-cli/commit/5be05f3))
* fix version check ([e5ef34d](https://github.com/vuejs/vue-cli/commit/e5ef34d))
* move linkBin into [@vue](https://github.com/vue)/cli since it requires node 8 ([120d5c5](https://github.com/vuejs/vue-cli/commit/120d5c5))
* TS 2.7 compat ([c7e28fd](https://github.com/vuejs/vue-cli/commit/c7e28fd))
* typescript caching problems ([a80cf18](https://github.com/vuejs/vue-cli/commit/a80cf18))
* **typescript:** explicitly include global types ([31c1261](https://github.com/vuejs/vue-cli/commit/31c1261)), closes [#762](https://github.com/vuejs/vue-cli/issues/762)


### Features

* build --target lib/wc ([faadadf](https://github.com/vuejs/vue-cli/commit/faadadf))
* build --target web-component (WIP) ([6db7735](https://github.com/vuejs/vue-cli/commit/6db7735))
* complete --target wc & multi-wc + tests ([9a07eeb](https://github.com/vuejs/vue-cli/commit/9a07eeb))
* improve build lib/web-component ([1c4943b](https://github.com/vuejs/vue-cli/commit/1c4943b))
* improve inspect output ([fd87394](https://github.com/vuejs/vue-cli/commit/fd87394))
* inject styles under shadow root in web component mode ([98afd07](https://github.com/vuejs/vue-cli/commit/98afd07))
* make env variables available in HTML template ([b626ef1](https://github.com/vuejs/vue-cli/commit/b626ef1))
* parallel mode ([b8f2487](https://github.com/vuejs/vue-cli/commit/b8f2487))
* vue build --target multi-wc [pattern] ([0f59c03](https://github.com/vuejs/vue-cli/commit/0f59c03))
* vue inspect that proxies to vue-cli-service ([4c00cfa](https://github.com/vuejs/vue-cli/commit/4c00cfa))


### Reverts

* feat: load config w/ cosmiconfig ([702b539](https://github.com/vuejs/vue-cli/commit/702b539))



<a name="3.0.0-alpha.5"></a>
# [3.0.0-alpha.5](https://github.com/vuejs/vue-cli/compare/v3.0.0-alpha.4...v3.0.0-alpha.5) (2018-01-29)


### Bug Fixes

* cache-loader doesnt seem to work well with ts-loader ([63c8f65](https://github.com/vuejs/vue-cli/commit/63c8f65))
* jest should only run files in given directory ([4a7fd64](https://github.com/vuejs/vue-cli/commit/4a7fd64)), closes [#740](https://github.com/vuejs/vue-cli/issues/740)


### Features

* allow saving multiple presets ([f372f55](https://github.com/vuejs/vue-cli/commit/f372f55))
* load config w/ cosmiconfig ([5288122](https://github.com/vuejs/vue-cli/commit/5288122))
* support config in dedicated files ([01edb46](https://github.com/vuejs/vue-cli/commit/01edb46))



<a name="3.0.0-alpha.4"></a>
# [3.0.0-alpha.4](https://github.com/vuejs/vue-cli/compare/v3.0.0-alpha.3...v3.0.0-alpha.4) (2018-01-26)


### Bug Fixes

* pin joi to 12.x for node version compat ([3bd447a](https://github.com/vuejs/vue-cli/commit/3bd447a))
* skip postcss-loader if no postcss config is present ([1142339](https://github.com/vuejs/vue-cli/commit/1142339))
* temp pinning vue-jest to github branch ([2d6a0d9](https://github.com/vuejs/vue-cli/commit/2d6a0d9))


### Features

* move babel-preset and eslint-plugin as deps of plugins ([c2583e4](https://github.com/vuejs/vue-cli/commit/c2583e4))



<a name="3.0.0-alpha.3"></a>
# [3.0.0-alpha.3](https://github.com/vuejs/vue-cli/compare/v3.0.0-alpha.2...v3.0.0-alpha.3) (2018-01-26)


### Bug Fixes

* clone options before mutating ([7471f94](https://github.com/vuejs/vue-cli/commit/7471f94))
* **typescript:** fix tsconfig.json ([235676f](https://github.com/vuejs/vue-cli/commit/235676f))
* **typescript:** include [@types](https://github.com/types)/node instead of shimming process ([f9c8849](https://github.com/vuejs/vue-cli/commit/f9c8849))
* ensure cache-loader apply to both babel and ts ([5f76980](https://github.com/vuejs/vue-cli/commit/5f76980))
* fix sync script for generators ([134ac58](https://github.com/vuejs/vue-cli/commit/134ac58))
* force babel-core version when using ts + babel ([d7c6af7](https://github.com/vuejs/vue-cli/commit/d7c6af7))
* more global resolve fixes + better error message for missing loaders ([367b78b](https://github.com/vuejs/vue-cli/commit/367b78b))
* more global service resolve fixes ([76dda73](https://github.com/vuejs/vue-cli/commit/76dda73))
* packageManager flag ([0c9ecd5](https://github.com/vuejs/vue-cli/commit/0c9ecd5))
* resolve for global service ([8f0b52f](https://github.com/vuejs/vue-cli/commit/8f0b52f))


### Features

* use cache-loader for ts ([4680544](https://github.com/vuejs/vue-cli/commit/4680544))



<a name="3.0.0-alpha.2"></a>
# [3.0.0-alpha.2](https://github.com/vuejs/vue-cli/compare/v3.0.0-alpha.1...v3.0.0-alpha.2) (2018-01-25)


### Bug Fixes

* avoid dotfiles not being published to npm ([2e3fe07](https://github.com/vuejs/vue-cli/commit/2e3fe07))
* do not update dep if latest tag is older then specified ([b913047](https://github.com/vuejs/vue-cli/commit/b913047))
* use babel-loader@8 ([c769110](https://github.com/vuejs/vue-cli/commit/c769110))



<a name="3.0.0-alpha.1"></a>
# [3.0.0-alpha.1](https://github.com/vuejs/vue-cli/compare/a923afb...v3.0.0-alpha.1) (2018-01-25)


### Bug Fixes

* avoid scrolling when picking features ([d57208d](https://github.com/vuejs/vue-cli/commit/d57208d))
* bump root deps as well ([f52ff70](https://github.com/vuejs/vue-cli/commit/f52ff70))
* ensure paths + make html optional ([2c1ad14](https://github.com/vuejs/vue-cli/commit/2c1ad14))
* typo {mdoule => module} ([#721](https://github.com/vuejs/vue-cli/issues/721)) ([4765cc6](https://github.com/vuejs/vue-cli/commit/4765cc6))


### Features

* add caching for babel ([7605bd6](https://github.com/vuejs/vue-cli/commit/7605bd6))
* auto DLL ([8dff383](https://github.com/vuejs/vue-cli/commit/8dff383))
* better validation error message ([5fef42c](https://github.com/vuejs/vue-cli/commit/5fef42c))
* complete prettier integration ([100c5c6](https://github.com/vuejs/vue-cli/commit/100c5c6))
* core ([a923afb](https://github.com/vuejs/vue-cli/commit/a923afb))
* css preprocessors ([d3bb381](https://github.com/vuejs/vue-cli/commit/d3bb381))
* e2e cypress ([8a3ac7e](https://github.com/vuejs/vue-cli/commit/8a3ac7e))
* e2e nightwatch ([655202f](https://github.com/vuejs/vue-cli/commit/655202f))
* enable caching for uglifyjs plugin ([abaed00](https://github.com/vuejs/vue-cli/commit/abaed00))
* experimental support for compiling TS with Babel ([e4dcc2f](https://github.com/vuejs/vue-cli/commit/e4dcc2f))
* improve generator hasPlugin check + invoke output ([52dad9d](https://github.com/vuejs/vue-cli/commit/52dad9d))
* improve prompt flow ([06af371](https://github.com/vuejs/vue-cli/commit/06af371))
* make jest plugin work with TypeScript ([ea2648e](https://github.com/vuejs/vue-cli/commit/ea2648e))
* make tslint work for vue files ([52b587e](https://github.com/vuejs/vue-cli/commit/52b587e))
* mocha-webpack plugin ([21187b4](https://github.com/vuejs/vue-cli/commit/21187b4))
* optimize minification ([bd1ffd3](https://github.com/vuejs/vue-cli/commit/bd1ffd3))
* preliminary TS plugin imeplementation ([54a902d](https://github.com/vuejs/vue-cli/commit/54a902d))
* pwa ([902f6c0](https://github.com/vuejs/vue-cli/commit/902f6c0))
* router & vuex ([88e9d46](https://github.com/vuejs/vue-cli/commit/88e9d46))
* support Prettier eslint config (pending) ([d84df9a](https://github.com/vuejs/vue-cli/commit/d84df9a))
* tweak invoke command ([65cc27d](https://github.com/vuejs/vue-cli/commit/65cc27d))
* use Babel w/ TS for polyfills ([5b19826](https://github.com/vuejs/vue-cli/commit/5b19826))
* wip invoke command ([132b0db](https://github.com/vuejs/vue-cli/commit/132b0db))
* WIP jest plugin ([bb5d968](https://github.com/vuejs/vue-cli/commit/bb5d968))



