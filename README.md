# Awesome Deno [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="deno-logo.svg" align="right" width="100">](https://deno.land)

Deno is a simple, modern and secure runtime for JavaScript and TypeScript that uses V8 and is built in Rust.

This list is a collection of the best Deno modules and resources.

## Contents

- [Docs](#docs)
  - [Official Docs](#official-docs)
  - [External Docs](#external-docs)
  - [Online Playgrounds](#online-playgrounds)
- [Modules](#modules)
- [Tools](#tools)
- [Articles](#articles)
- [Presentations](#presentations)
- [Resources in Other Languages](#resources-in-other-languages)
  - [Chinese](#chinese)
  - [Hebrew](#hebrew)
  - [Indonesian](#indonesian)
  - [Italian](#italian)
  - [Japanese](#japanese)
  - [Korean](#korean)
  - [Russian](#russian)
  - [Spanish](#spanish)

## Docs

### Official Docs

- [Official Site](https://deno.land)
- [Deno API TypeDoc](https://deno.land/typedoc/)
- [Deno Manual](https://deno.land/manual)
- [Deno Registry](https://deno.land/x/)

### External Docs

- [V8 Docs for Deno](https://denolib.github.io/v8-docs/)
- [DenoBeginner.com](https://DenoBeginner.com) - A completely free crash course on deno for beginners.

### Online Playgrounds

- [deno.town](https://deno.town)
- [Deno Playground](https://deno-playground.now.sh)
  - [maman/deno-playground](https://github.com/maman/deno-playground)
- [DenoBR Playground](https://playground.denobr.com/)

## Modules

__NOTICE__: Deno has a few official modules that could be found at [deno_std](https://deno.land/std/).
Consider submitting to [the deno.land/x](https://github.com/denoland/deno_website2/blob/master/database.json) repository.

- [abc](https://github.com/zhmushan/abc) - A better Deno framework to create web application.
- [alosaur](https://github.com/alosaur/alosaur) - Alosaur - Deno web framework with many decorators.
- [attain](https://github.com/aaronwlee/Attain) - A middleware web framework for Deno which is using http standard library inspired by express and Oak. Fast and stable with proper memory usage.
- [aqua](https://github.com/l2ig/aqua) - A minimal and fast web framework for Deno.
- [autopilot](https://github.com/divy-work/autopilot-deno) - Autopilot - Cross-platform web automation with Deno.
- [bytes_formater](https://github.com/manyuanrong/bytes_formater) - Format bytes (Uint8Array, ArrayBufferView, etc) output, useful when debugging IO functions.
- [cac](https://github.com/cacjs/cac) - Simple yet powerful framework for building command-line apps.
- [camelcase](https://github.com/denolib/camelcase) - Convert a dash/dot/underscore/space separated string to camelCase: foo-bar → fooBar.
- [colors](https://deno.land/std/fmt/colors.ts) - A basic console color library intended for Deno.
- [computed_types](https://github.com/neuledge/computed-types) - Joi like validators for Typescript and Deno.
- [cli-spinner](https://github.com/ameerthehacker/cli-spinners) - Show spinners in the terminal while running long tasks.
- [csv](https://github.com/hashrock/deno-fnparse/blob/master/parsers/csv.ts) - A simple CSV parser.
- [dcc](https://github.com/BoltDoggy/deno#dcc) - Deno Cache Clean, reloading deps when next running.
- [dejs](https://github.com/syumai/dejs) - Ejs template engine for deno.
- [denon](https://github.com/denosaurs/denon/blob/master/mod.ts) - A file watcher with a for-await generator.
- [deno_case_style](https://github.com/zekth/deno_case_style) - String validator and formater for different case style. eg: camelCase etc.
- [deno-context](https://github.com/code-hex/deno-context) - Propagate deadlines, a cancellation and other request-scoped values to multiple promise. The behaviour is like Go's context.
- [deno_cron](https://github.com/rbrahul/deno_cron) - A cron Job scheduler that allows you to write human readable cron syntax with tons of flexibility
- [deno-deamon](https://github.com/manyuanrong/deno-deamon) - Make the Deno program run in the background.
- deno-dotenv
  - [pietvanzoen/deno-dotenv](https://github.com/pietvanzoen/deno-dotenv) - Dotenv handling for deno.
  - [cardosomarcos/deno-dotenv](https://github.com/cardosomarcos/deno-dotenv) - Loads environment variables from .env for Deno projects.
- [deno-express](https://github.com/NMathar/deno-express) - Node Express ported to Deno.
- [deno-fnparse](https://github.com/hashrock/deno-fnparse) - An extremely simple parser combinator for JavaScript.
- [deno-globrex](https://github.com/hayd/deno-globrex) - Port of globrex to deno, glob to regular expression.
- [deno-mysql](https://github.com/manyuanrong/deno_mysql) - MySQL database driver.
- [deno_mongo](https://github.com/manyuanrong/deno_mongo) - MongoDB database driver.
- [deno_notify](https://github.com/PandawanFr/deno_notify) - Send desktop notifications on all platforms.
- [deno-opn](https://github.com/hashrock/deno-opn) - Opens stuff like websites, files, executables. Cross-platform.
- [deno-plugin-prepare](https://github.com/manyuanrong/deno-plugin-prepare) - A library for managing Deno native plugin dependencies.
- [deno-pretty-assert](https://github.com/bokuweb/deno-pretty-assert) - A colorful assertEqual for deno.
- [deno-prettystring](https://github.com/OnikurYH/deno-prettystring) - Format, trim and remove extra white spaces between characters from string.
- [deno_random_interval](https://github.com/zekth/deno_random_interval) - Helper to generate random interval.
- [deno-redis](https://github.com/keroxp/deno-redis) - An experimental implementation of redis client for deno.
- [deno-slugify](https://github.com/jcardama/deno_slugify) - A string slugifier for deno.
- [deno-smtp](https://github.com/manyuanrong/deno-smtp) - A smtp mail sender for deno.
- [deno_tiny_templates](https://github.com/zekth/deno_tiny_templates) - Template renderer for deno.
- [deno_tokenizer](https://github.com/eliassjogreen/deno_tokenizer) - A simple tokenizer for deno.
- [deno-using](https://github.com/hayd/deno-using) - An python-style with statements for deno.
- [deno-uuid](https://github.com/lucascaro/deno-uuid) - UUID module for deno.
- [deno-ws](https://github.com/keroxp/deno-ws) - An experimental implementation of websocket server for deno.ts.
- [deno-websocket](https://github.com/ryo-ma/deno-websocket) - 🦕A simple WebSocket library like ws of node.js library.
- [deno-xml-parser](https://github.com/nekobato/deno-xml-parser) - Deno XML parser ported from segmentio/xml-parser.
- [denotrain](https://github.com/Caesar2011/denotrain) - All-in-One web framework like express or fastify for Node.js with middleware support.
- [dinatra](https://github.com/syumai/dinatra) - Sinatra like light weight web app framework for deno.
- [djwt](https://github.com/timonson/djwt) - Make JSON Web Tokens (JWT) on Deno based on JWT and JWS specifications.
- [dso](https://github.com/manyuanrong/dso) - A simple ORM library based on mysql.
- [ensure](https://github.com/eankeen/ensure) - Ensure you are running a minimum version of Deno, Typescript, or V8.
- [evt](https://github.com/garronej/evt) - Type safe replacement for EventEmitter.
- [expect](https://github.com/allain/expect) - Helpers for writing jest like expect tests in deno.
- [flags](https://github.com/denoland/deno_std/tree/master/flags) - Command line arguments parser for Deno based on minimist.
- [gardens](https://github.com/partheseas/gardens) - A useful logging utility for JavaScript everywhere.
- [gentleRpc](https://github.com/timonson/gentleRpc) - A JSON-RPC 2.0 TypeScript library for Deno and the browser.
- [http](https://github.com/denoland/deno_std/tree/master/http) - HTTP module including a file server.
- [http-libs](https://github.com/denoserverless/http-libs) - HTTP modules and typings.
- [invert-kv](https://github.com/denorg/invert-kv) - Invert key-value pairs in Deno.
- [jwt](https://github.com/denoserverless/jwt) - Port of auth0/jsonwebtoken.
- [lazy](https://github.com/luvies/lazy) - A linq-like lazy-evaluation iteration module.
- [log](https://github.com/denoland/deno_std/tree/master/log) - Logging module for Deno.
- [marked](https://github.com/denolib/marked/) - Markdown-to-HTML converter.
- [ms](https://github.com/denolib/ms) - Easily convert various time formats to milliseconds.
- [normalize_diacritics](https://github.com/motss/deno_mod/tree/master/normalize_diacritics) - Remove accents/diacritics in string.
- [oak](https://github.com/oakserver/oak) - A middleware framework for Deno's net server.
- [online](https://github.com/denorg/online) - Check if you're currently online in Deno.
- [opine](https://github.com/asos-craigmorten/opine) - Fast, minimalist web framework ported from ExpressJS.
- [path](https://github.com/denoland/deno_std/tree/master/fs/path) - Deno Path Manipulation Libraries.
- [pogo](https://github.com/sholladay/pogo) - Server framework for Deno.
- [postgres](https://github.com/buildondata/deno-postgres) - Driver for PostgreSQL database.
- [qrcode](https://github.com/denorg/qrcode) - QR code image generator for Deno.
- [qs](https://github.com/denolib/qs) - A query string parser with nesting support.
- [recursive-readdir](https://github.com/denorg/recursive-readdir) - Recursively read directories in Deno.
- [router](https://github.com/zhmushan/router) - A high-performance basic router works anywhere.
- [rubico](https://github.com/richytong/rubico) - 🏞 [a]synchronous function composition; it just works.
- [sax-ts](https://github.com/Maxim-Mazurok/sax-ts) - SAX-style XML parser ported from [sax-js](https://github.com/isaacs/sax-js).
- [servest](https://github.com/keroxp/servest) - A progressive HTTP server/router.
- [sql-builder](https://github.com/manyuanrong/sql-builder) - An sql query builder.
- [status](https://github.com/denosaurs/status) - HTTP codes and status utility for Deno.
- [textproto](https://github.com/denoland/deno_std/tree/master/textproto)
- [time.ts](https://github.com/burhanahmeed/time.ts) - Time.ts - A straightforward Deno timezone manipulation
- [type-fest](https://github.com/denoserverless/type-fest) - A collection of essential TypeScript types (port of sindresorhus/type-fest).
- [unexpected](https://github.com/unexpectedjs/unexpected) - Extensible BDD assertion toolkit.
- [up](https://github.com/denorg/up) - Check if a website is up in Deno.
- [wasm-gzip](https://github.com/manyuanrong/wasm_gzip) - Encrypt and decrypt gzip for Deno.
- [watch](https://github.com/jinjor/deno-watch) - A file watcher.
- [websocket_server](https://github.com/JohanWinther/websocket_server) - A WebSocket server library. 🔌
- [webview](https://github.com/eliassjogreen/deno_webview) - Deno bindings for webview, a tiny library for creating web-based desktop GUIs.
- [wu-diff-js](https://github.com/bokuweb/wu-diff-js) - A diff library to compute differences between two slices using wu(the O(NP)) algorithm.
- [youtube-deno](https://github.com/akshgpt7/youtube-deno) - A Deno client library for the YouTube Data API for any interaction with YouTube.

## Tools

- [clone](https://github.com/ekaragodin/clone) - A simple utility for the convenient clone.
- [dedep](https://github.com/egoist/dedep) - Manage dependency versions.
- [denoget](https://github.com/syumai/denoget) - Denoget installs executable Deno script.
- [denoify](https://github.com/garronej/denoify) - For NPM module authors that would like to support Deno but do not want to write and maintain a port.
- [denoinit](https://github.com/syumai/deno-libs/tree/master/denoinit) - Denoinit generates useful files for Deno project.
- [denoliver](https://github.com/joakimunge/denoliver) - A simple, dependency free file server with live reload.
- [denomander](https://github.com/siokas/denomander) - Deno command-line interfaces inspired from commander.js.
- [denon](https://github.com/denosaurs/denon) - A daemon script runner, like nodemon. Built in and for Deno.
- [denopkg](https://github.com/denopkg/denopkg.com) - An easier way to use code from GitHub in your Deno project.
- [denoversion](https://github.com/lucascaro/denoversion) - SemVer and git version management for Deno.
- [denox](https://github.com/BentoumiTech/denox) - Like packages.json scripts, but for Deno with permissions support.
- [deno.mk](https://github.com/MarkTiedemann/deno.mk) - Cross-platform Makefile for installing and running Deno.
- maxmcd's [deno-docker](https://github.com/maxmcd/deno-docker) A docker image.
- hayd's [deno-docker](https://github.com/hayd/deno-docker) Several docker images.
- [deno-vscode](https://github.com/ameerthehacker/deno-vscode) - Leverage the typedef and intellisense built into vscode using this extension.
- [dev_server](https://github.com/zhmushan/dev_server) - Let TypeScript files be used directly in the script tag.
- [dpm](https://github.com/BoltDoggy/deno#dpm) - Deno Package Manager, install global command for deno. like denoget.
- dvm
  - [justjavac/dvm](https://github.com/justjavac/dvm) - Deno Version Manager: manage multiple active Deno versions.
  - [axetroy/dvm](https://github.com/axetroy/dvm) - Version manger for Deno without runtime dependencies.
- [elm-live-reload](https://github.com/jinjor/deno-playground/tree/master/elm-live-reload) - An elm live reloader written in Deno.
- [nessie](https://github.com/halvardssm/deno-nessie) - Create, migrate and rollback migrations for PostgreSQL, MySQL and SQLite.
- [packer-provisioner-deno](https://github.com/dontlaugh/packer-provisioner-deno) - A Packer plugin that makes it easy to build virtual machine images with Deno scripts.
- [pagic](https://github.com/xcatliu/pagic) - The easiest way to generate static html page from markdown, built with Deno.
- [pika Deno plugin](https://github.com/pikapkg/builders/tree/master/packages/plugin-build-deno/)
- [starter](https://github.com/denorg/starter) - Deno module starter template with GitHub Actions CI
- [task-runner](https://github.com/jinjor/deno-task-runner) - Write tasks just like npm scripts.
- [typescript-deno-plugin](https://github.com/justjavac/typescript-deno-plugin) - Deno language service plugin, providing intellisense in TypeScript files within editors.
- [udd](https://github.com/hayd/deno-udd) - Update Deno dependencies: updates import statements to their latest published version.
- [velociraptor](https://github.com/umbopepato/velociraptor) - An npm-style script runner for Deno.
- [vscode-deno](https://github.com/denoland/vscode_deno) - VS Code extension that provides Deno support using the `TypeScript Deno language service plugin`.

## Articles

- [Develop with Deno and Visual Studio Code](https://medium.com/@kitsonk/develop-with-deno-and-visual-studio-code-225ce7c5b1ba)
- [First thoughts on Deno, the JavaScript/TypeScript run-time](https://43081j.com/2019/01/first-look-at-deno)
- [Getting started with Deno](https://dev.to/wuz/getting-started-with-deno-e1m)
- [What's Deno, and how is it different from Node.js?](https://dev.to/bnevilleoneill/what-s-deno-and-how-is-it-different-from-node-js-366g)
- [Write a small API using Deno](https://dev.to/kryz/write-a-small-api-using-deno-1cl0)
- [Deno on AWS Lambda with Architect or SAM](https://blog.begin.com/deno-runtime-support-for-architect-805fcbaa82c3)
- [Deno on Cloud Run](https://medium.com/google-cloud/deno-on-cloud-run-89ae64d1664d)
- [Learn Deno: Chat app](https://aralroca.com/blog/learn-deno-chat-app)
- [From Node to Deno](https://dev.to/aralroca/from-node-to-deno-5gpn)
- [Create a simple Note-taking app with Deno](https://dev.to/jeferson_sb/create-a-simple-note-taking-app-with-deno-3k7g)
- [Develop and Dockerize a Blogging API With Deno, Oak, and MySQL](https://dev.to/fhsinchy/develop-and-dockerize-a-blogging-api-with-deno-oak-and-mysql-170e)
- [Building API's using Deno, Oak and MYSQL](https://codeforgeek.com/building-api-server-using-deno-and-mysql/)
- [Create interactive mail utility CLI Tool using Deno
](https://www.soubai.me/posts/create-interactive-mail-utility-cli-with-deno)

## Presentations

- [10 Things I Regret About Node.js - Ryan Dahl - JSConf EU 2018](https://www.youtube.com/watch?v=M3BM9TB-8yA)
  - [Slides](https://tinyclouds.org/jsconf2018.pdf)
- [JSDC 2018#A01 - Deno, A New Server-Side Runtime By Ryan Dahl](https://www.youtube.com/watch?v=FlTG0UXRAkE)
  - [Slides](https://tinyclouds.org/deno_jsdc.pptx)
- [Ryan Dahl. Deno, a new way to JavaScript. JS Fest 2019 Spring](https://www.youtube.com/watch?v=z6JRlx5NC9E)
  - [Slides](https://www.slideshare.net/JSFestUA/js-fest-2019-ryan-dahl-deno-a-new-way-to-javascript)
- [Rafał Pocztarski — From Node.js to Deno - JavaScript/TypeScript runtime built with V8 and Rust [EN]](https://www.youtube.com/watch?v=Aib1OZLy0_c)
  - [Slides](https://gitpitch.com/rsp/ntd/ntd?utm_campaign=Deno%20Newsletter#/)
- [Ryan Dahl: A secure runtime for JavaScript and TypeScript | js.la April 2019](https://www.youtube.com/watch?v=RAmqgbv247s)
  - [Slides](https://docs.google.com/presentation/d/1CSQVTeH5tFzE4AZVXIpx9Xwew5YS-gxJZ03eRFtNeIc/edit)
- [Ryan Dahl: Deno, a new way to JavaScript - HolyJS 2019 Piter](https://www.youtube.com/watch?v=HjdJzNoT_qg)
  - [Slides](https://docs.google.com/presentation/d/1BjvZx5S8noVfFINptH4jfKfqh9jB9nXlFC0I3oIDtg4/edit)
- [Rafał Pocztarski - What is Deno? A new runtime for modern JavaScript and TypeScript backends for 2020s - Deno Warsaw](https://www.youtube.com/watch?v=aI5A9zvYSjk)
  - [Slides](https://gitpitch.com/rsp/wid/wid)
- [Michał Sabiniarz - How to contribute to Deno? - Deno Warsaw](https://www.youtube.com/watch?v=LAtjnKLbPpw)
  - [Slides](https://docs.google.com/presentation/d/1rETgslJS1ks4EihzLpUI3sS_zI46YxAOuQ5B1Z_k1mY/edit?usp=sharing)
- [Bartek Iwańczuk - Deno internals, how modern runtime is built - Deno Warsaw](https://www.youtube.com/watch?v=qt7fbmypAFk)
  - [Slides](https://docs.google.com/presentation/d/1LYNGpyjx9PemL-P__7hVC8mSqkX-jL8VQLMhCRehy00/edit?usp=sharing)
- [Ryan Dahl & Kitson Kelly: Deno is a New Way to JavaScript - TSConf 2019](https://www.youtube.com/watch?v=1gIiZfSbEAE)

## Resources in Other Languages

### Chinese

- [Deno 并不是下一代 Node.js](https://juejin.im/post/5b14a390e51d4506c1300bbc)
- [玩 Deno 遇到问题的解决方案](https://juejin.im/post/5b1245b3f265da6e4c6cf249)
- [让我们一起来学习别人学不动的 Deno](https://segmentfault.com/a/1190000015151287)
- [Design Mistakes in Node zh-CN](https://zhuanlan.zhihu.com/p/37637923)
- [Node之父ry：Node中的设计错误](https://mp.weixin.qq.com/s/7XAiYw18c8YZc-fXk0-wrw)
- [《Deno进阶开发笔记》](https://github.com/chenshenhai/deno_note/)
- [Deno中文社区](https://denocn.org)
- [Deno 手册](https://github.com/Nugine/deno-manual-cn/)
- [Deno 中文开发者社区](https://deno.js.cn)

### Hebrew

- [Deno intro in Hebrew (slides in English)](https://www.youtube.com/watch?v=9tJ_LkI6_qw)

### Indonesian

- [Berkenalan dengan Deno](https://medium.com/@redhajuanda/berkenalan-dengan-dengan-deno-c48cdf3aa31e)
- [Perkenalan Deno dan Instalasi](https://youtu.be/V_kpUTJSd9c)
- [Deno Land Indonesia website](https://denoland.id/)
- [Deno Land Indonesia Telegram group](https://t.me/deno_id)

### Italian

- [Deno - L'anagramma di Node](https://www.slideshare.net/FrancescoSciuti/deno-lanagramma-di-node)

### Japanese

- [Node.js における設計ミス By Ryan Dahl](https://yosuke-furukawa.hatenablog.com/entry/2018/06/07/080335)
- [mizchi/deno_code_reading.md](https://gist.github.com/mizchi/31e5628751330b624a0e8ada9e739b1e)
- [Design Mistakes in Node & Deno #kng5 / deno](https://speakerdeck.com/masashi/deno)
- [Dive into Deno：プロセス起動からTypeScriptが実行されるまで](https://blog.leko.jp/post/code-reading-of-deno-boot-process/)

### Korean

- [denoland.kr/](https://denoland.kr/)

### Russian

- [Telegram channel](https://t.me/denoland_ru)
- [Telegram chat](https://t.me/denoland)

### Spanish

- [Hola Deno! . 🦕](https://medium.com/javascript-espa%C3%B1ol/hola-deno-f31f9f6f2c84)
- [Así puedes crear tu primera API REST con Deno](https://medium.com/@mpampols/as%C3%AD-puedes-crear-tu-primera-api-rest-con-deno-a9094ee5c0b2)
- [Primeros pasos con Deno 🦕 El sucesor de NodeJS desarrollado con Rust y TypeScript](https://medium.com/@manurua/primeros-pasos-con-deno-el-nuevo-nodejs-desarrollado-con-rust-y-typescript-b9ac14f7d0c7)

### Uzbek

- [Telegram Channel](https://t.me/denoland_uz)
- [Telegram Group](https://t.me/chisel_deno)
- [Deno Translated Website](https://deno.uz)
