# Awesome Deno [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="deno-logo.png" align="right" width="100">](https://deno.land)

Deno is a simple, modern and secure runtime for JavaScript and TypeScript that uses V8 and is built in Rust.

This list is a collection of the best Deno modules and resources.

## Contents

- [Docs](#docs)
  - [Official Docs](#official-docs)
  - [External Docs](#external-docs)
  - [Online Playgrounds](#online-playgrounds)
- [Modules](#modules)
  - [Automation](#automation)
  - [CLI utils](#cli-utils)
  - [Database](#database)
  - [Frontend development](#frontend-development)
  - [Frontend framework](#frontend-framework)
  - [Logging](#logging)
  - [Mail](#mail)
  - [Markdown](#markdown)
  - [String utils](#string-utils)
  - [Template engine](#template-engine)
  - [Testing](#testing)
  - [Utils](#utils)
  - [Web framework](#web-framework)
  - [WebSocket](#websocket)
  - [Web utils](#web-utils)
  - [Webview](#webview)
  - [XML](#xml)
- [Registries](#registries)
- [Showcases](#showcases)
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
  - [Uzbek](#uzbek)

## Docs

### Official Docs

- [Official Site](https://deno.land)
- [Deno API Reference](https://doc.deno.land/builtin/stable)
  - [Deno Unstable API Reference](https://doc.deno.land/builtin/unstable)
- [Deno Manual](https://deno.land/manual)

### External Docs

- [V8 Docs for Deno](https://denolib.github.io/v8-docs/)
- [DenoBeginner.com](https://DenoBeginner.com) - A completely free crash course on deno for beginners.

### Online Playgrounds

- [deno.town](https://deno.town)
- [Deno Playground](https://deno-playground.now.sh)
  - [maman/deno-playground](https://github.com/maman/deno-playground)
- [DenoBR Playground](https://playground.denobr.com/)
- [myCompiler.io](https://www.mycompiler.io/new/deno)
- [Repl.it](https://repl.it/languages/deno)

## Modules

__NOTICE__: Deno has a few official modules that could be found at [deno_std](https://deno.land/std/).
Consider submitting to the [deno.land/x](https://deno.land/x/) registry.

### Automation
- [autopilot](https://github.com/divy-work/autopilot-deno) - Autopilot - Cross-platform web automation with Deno.

### CLI utils
- [cac](https://github.com/cacjs/cac) - Simple yet powerful framework for building command-line apps.
- [charmd](https://github.com/littletof/charmd) - A simple, extendable markdown renderer for your terminal.
- [chart](https://github.com/maximousblk/chart) - Console ASCII line charts with no dependencies.
- [cli-spinner](https://github.com/ameerthehacker/cli-spinners) - Show spinners in the terminal while running long tasks.
- [cliffy](https://github.com/c4spar/deno-cliffy) - The complete solution for building interactive command-line tools.
- [kia](https://github.com/HarryPeach/kia) - Simple terminal spinners for Deno 🦕
- [terminal_images](https://github.com/mjrlowe/terminal_images) -  A Deno module and CLI tool for displaying images in the terminal.

### Database
- [deno_mysql](https://github.com/denodrivers/mysql) - MySQL database driver.
- [deno_mongo](https://github.com/denodrivers/deno_mongo) - MongoDB database driver.
- [redis](https://github.com/denodrivers/redis) - An experimental implementation of redis client for deno.
- [denodb](https://github.com/eveningkid/denodb) - MySQL, SQLite, MariaDB, PostgreSQL and MongoDB ORM for Deno.
- [dndb](https://github.com/denyncrawford/dndb) - Persistent and embedable NoSQL database engine written for Deno 🦕. 
- [dsddb](https://github.com/MaximilianHeidenreich/DsDDB) - A dead simple persistant key-value database utilizing the JSON format.
- [dso](https://github.com/manyuanrong/dso) - A simple ORM library based on mysql.
- [postgres](https://github.com/denodrivers/postgres) - Driver for PostgreSQL database.
- [sql-builder](https://github.com/manyuanrong/sql-builder) - An sql query builder.
- [maxminddb](https://github.com/josh-hemphill/maxminddb-deno) - A library that enables the usage of MaxmindDB geoIP database files

### Frontend development
- [postcss](https://github.com/postcss/postcss-deno) - A tool for transforming styles with JS plugins.

### Frontend framework
- [aleph.js](https://github.com/postui/aleph.js) - A React framework in Deno, inspired by [Next.js](https://nextjs.org).

### Logging
- [gardens](https://github.com/partheseas/gardens) - A useful logging utility for JavaScript everywhere.

### Mail
- [deno-smtp](https://github.com/manyuanrong/deno-smtp) - A smtp mail sender for deno.

### Markdown
- [marked](https://github.com/denolib/marked/) - Markdown-to-HTML converter.

### String utils
- [camelcase](https://github.com/denolib/camelcase) - Convert a dash/dot/underscore/space separated string to camelCase: foo-bar → fooBar.
- [deno_case_style](https://github.com/zekth/deno_case_style) - String validator and formater for different case style. eg: camelCase etc.
- [deno-prettystring](https://github.com/OnikurYH/deno-prettystring) - Format, trim and remove extra white spaces between characters from string.
- [deno-slugify](https://github.com/jcardama/deno_slugify) - A string slugifier for deno.
- [normalize_diacritics](https://github.com/motss/deno_mod/tree/master/normalize_diacritics) - Remove accents/diacritics in string.

### Template engine
- [dejs](https://github.com/syumai/dejs) - Ejs template engine for deno.
- [deno_tiny_templates](https://github.com/zekth/deno_tiny_templates) - Template renderer for deno.
- [eta](https://github.com/eta-dev/eta) - Fast, lightweight, and configurable embedded template engine.

### Testing
- [deno-pretty-assert](https://github.com/bokuweb/deno-pretty-assert) - A colorful assertEqual for deno.
- [deno-puppeteer](https://github.com/lucacasonato/deno-puppeteer) - A library which provides a high-level API to control Chromium or Chrome over the DevTools Protocol.
- [expect](https://github.com/allain/expect) - Helpers for writing jest like expect tests in deno.
- [merlin](https://github.com/crewdevio/merlin) - Testing and Benchmarking framework for deno 🧙‍♂️
- [pretty_benching](https://github.com/littletof/prettyBenching) - A small library to make your Deno benchmarking progress and results look pretty.
- [rhum](https://github.com/drashland/rhum) - A lightweight testing framework for Deno.
- [superdeno](https://github.com/asos-craigmorten/superdeno) - Super-agent driven library for testing Deno HTTP servers.
- [superoak](https://github.com/asos-craigmorten/superoak) - HTTP assertions for Oak made easy via SuperDeno.
- [tincan](https://github.com/gcaptn/tincan) - A Jest-like testing library for Deno.
- [unexpected](https://github.com/unexpectedjs/unexpected) - Extensible BDD assertion toolkit.

### Utils
- [buckets](https://github.com/jacoborus/deno-buckets) - Bundle assets and scripts in a single executable file.
- [bytes_formater](https://github.com/manyuanrong/bytes_formater) - Format bytes (Uint8Array, ArrayBufferView, etc) output, useful when debugging IO functions.
- [coffee](https://github.com/irandeno/coffee) - Deno Configuration - a type-safe, easy to use Deno config manager.
- [computed_types](https://github.com/neuledge/computed-types) - Joi like validators for Typescript and Deno.
- [dcc](https://github.com/BoltDoggy/deno#dcc) - Deno Cache Clean, reloading deps when next running.
- [denon](https://github.com/denosaurs/denon/blob/master/mod.ts) - A file watcher with a for-await generator.
- [deno-context](https://github.com/code-hex/deno-context) - Propagate deadlines, a cancellation and other request-scoped values to multiple promise. The behaviour is like Go's context.
- [deno_cron](https://github.com/rbrahul/deno_cron) - A cron Job scheduler that allows you to write human readable cron syntax with tons of flexibility
- [deno-deamon](https://github.com/manyuanrong/deno-deamon) - Make the Deno program run in the background.
- deno-dotenv
  - [pietvanzoen/deno-dotenv](https://github.com/pietvanzoen/deno-dotenv) - Dotenv handling for deno.
  - [cardosomarcos/deno-dotenv](https://github.com/cardosomarcos/deno-dotenv) - Loads environment variables from .env for Deno projects.
- [deno-fnparse](https://github.com/hashrock/deno-fnparse) - An extremely simple parser combinator for JavaScript.
- [deno-globrex](https://github.com/hayd/deno-globrex) - Port of globrex to deno, glob to regular expression.
- [deno_notify](https://github.com/PandawanFr/deno_notify) - Send desktop notifications on all platforms.
- [deno-opn](https://github.com/hashrock/deno-opn) - Opens stuff like websites, files, executables. Cross-platform.
- [deno-plugin-prepare](https://github.com/manyuanrong/deno-plugin-prepare) - A library for managing Deno native plugin dependencies.
- [deno_random_interval](https://github.com/zekth/deno_random_interval) - Helper to generate random interval.
- [deno_tokenizer](https://github.com/eliassjogreen/deno_tokenizer) - A simple tokenizer for deno.
- [deno-using](https://github.com/hayd/deno-using) - An python-style with statements for deno.
- [dinoenv](https://deno.land/x/dinoenv) - tiny library to manage environment variables with deno.
- [ensure](https://github.com/eankeen/ensure) - Ensure you are running a minimum version of Deno, Typescript, or V8.
- [evt](https://github.com/garronej/evt) - Type safe replacement for EventEmitter.
- [fossil](https://github.com/matteocrippa/fossil) - A value-type validation suite.
- [garn-yaml](https://github.com/jupegarnica/garn-yaml) - Read or write yaml interpolating env variables.
- [garn-validator](https://github.com/jupegarnica/garn-validator) - Create validations with ease.
- [invert-kv](https://github.com/denorg/invert-kv) - Invert key-value pairs in Deno.
- [lazy](https://github.com/luvies/lazy) - A linq-like lazy-evaluation iteration module.
- [maze_generator](https://github.com/mjrlowe/maze_generator) - Javascript module for generating, solving, analyzing and displaying mazes.
- [ms](https://github.com/denolib/ms) - Easily convert various time formats to milliseconds.
- [online](https://github.com/denorg/online) - Check if you're currently online in Deno.
- [qrcode](https://github.com/denorg/qrcode) - QR code image generator for Deno.
- [recursive-readdir](https://github.com/denorg/recursive-readdir) - Recursively read directories in Deno.
- [rubico](https://github.com/richytong/rubico) - 🏞 [a]synchronous function composition; it just works.
- [type-fest](https://github.com/denoserverless/type-fest) - A collection of essential TypeScript types (port of sindresorhus/type-fest).
- [wasm-gzip](https://github.com/manyuanrong/wasm_gzip) - Encrypt and decrypt gzip for Deno.
- [watch](https://github.com/jinjor/deno-watch) - A file watcher.
- [wu-diff-js](https://github.com/bokuweb/wu-diff-js) - A diff library to compute differences between two slices using wu(the O(NP)) algorithm.

### Web framework
- [abc](https://github.com/zhmushan/abc) - A better Deno framework to create web application.
- [alosaur](https://github.com/alosaur/alosaur) - Alosaur - Deno web framework with many decorators.
- [attain](https://github.com/aaronwlee/Attain) - A middleware web framework for Deno which is using http standard library inspired by express and Oak. Fast and stable with proper memory usage.
- [aqua](https://github.com/l2ig/aqua) - A minimal and fast web framework for Deno.
- [deno-express](https://github.com/NMathar/deno-express) - Node Express ported to Deno.
- [denotrain](https://github.com/Caesar2011/denotrain) - All-in-One web framework like express or fastify for Node.js with middleware support.
- [dinatra](https://github.com/syumai/dinatra) - Sinatra like light weight web app framework for deno.
- [doa](https://github.com/johannlai/doa) - A middleware framework for Deno's http serve🦕. Transplanted from Koa with ❤️
- [drash](https://github.com/drashland/deno-drash) - A REST microframework for Deno's HTTP server with zero dependencies.
- [dragon](https://github.com/xanny-projects/dragon) - ⚡A powerful HTTP router and URL matcher for building Deno web servers with dragon 🐲.
- [microraptor](https://github.com/matteocrippa/microraptor) - Lightweight framework for easy network routing with validation.
- [oak](https://github.com/oakserver/oak) - A middleware framework for Deno's net server.
  - [oak-http-proxy](https://github.com/asos-craigmorten/oak-http-proxy) - Proxy middleware for Deno Oak HTTP servers.
- [opine](https://github.com/asos-craigmorten/opine) - Fast, minimalist web framework ported from ExpressJS.
  - [opine-http-proxy](https://github.com/asos-craigmorten/opine-http-proxy) - Proxy middleware for Deno Opine HTTP servers.
- [pogo](https://github.com/sholladay/pogo) - Server framework for Deno.
- [servest](https://github.com/keroxp/servest) - A progressive HTTP server/router.

### WebSocket
- [deno-websocket](https://github.com/ryo-ma/deno-websocket) - 🦕A simple WebSocket library like ws of node.js library.
- [dropper](https://github.com/denyncrawford/dropper-deno) - Custom event-based WebSockets framework for building real-time apps on Deno 🦕
- [websocket_server](https://github.com/JohanWinther/websocket_server) - A WebSocket server library.
- [sockets](https://github.com/drashland/sockets) - A WebSocket library for Deno.

### Web utils
- [compression](https://github.com/deno-libs/compression) - Deno HTTP compression middleware.
- [djwt](https://github.com/timonson/djwt) - Make JSON Web Tokens (JWT) on Deno based on JWT and JWS specifications.
- [forwarded](https://github.com/deno-libs/forwarded) - Deno port of `forwarded` library.
- [gentleRpc](https://github.com/timonson/gentleRpc) - A JSON-RPC 2.0 TypeScript library for Deno and the browser.
- [gql](https://github.com/deno-libs/gql) - Universal GraphQL HTTP middleware.
- [graphql-tag](https://github.com/deno-libs/graphql-tag) - GraphQL schema AST from template literal. 
- [nats](https://github.com/nats-io/nats.deno) - A Deno client for the [NATS messaging system](https://nats.io/).
- [obsidian](https://github.com/oslabs-beta/obsidian) - A native GraphQL caching client and server module.
- [qs](https://github.com/denolib/qs) - A query string parser with nesting support.
- [router](https://github.com/zhmushan/router) - A high-performance basic router works anywhere.
- [status](https://github.com/denosaurs/status) - HTTP codes and status utility for Deno.
- [ts-prometheus](https://github.com/marcopacini/ts-prometheus) - A prometheus client.
- [up](https://github.com/denorg/up) - Check if a website is up in Deno.
- [youtube-deno](https://github.com/akshgpt7/youtube-deno) - A Deno client library for the YouTube Data API for any interaction with YouTube.

### Webview
- [webview](https://github.com/eliassjogreen/deno_webview) - Deno bindings for webview, a tiny library for creating web-based desktop GUIs.

### XML
- [deno-xml-parser](https://github.com/nekobato/deno-xml-parser) - Deno XML parser ported from segmentio/xml-parser.
- [sax-ts](https://github.com/Maxim-Mazurok/sax-ts) - SAX-style XML parser ported from [sax-js](https://github.com/isaacs/sax-js).

## Registries

- [crux.land](https://crux.land/) - A free registry service meant for hosting small ( < 10kB) single deno scripts.
- [Deno PKG](https://denopkg.com/) - An easier way to use code from GitHub in your Deno project.
- [deno.land/x/](https://deno.land/x/) - The official 3rd party module registry.
- [nest.land](https://nest.land) - An immutable, blockchain powered Deno package registry. 🥚

## Showcases

- [AuthCompanion](https://github.com/pmprosociety/authcompanion) - A token-based user management server.
- [Deno Rest](https://github.com/vicky-gonsalves/deno_rest) - A Boilerplate for deno RESTful apis.
- [Deno Seed](https://github.com/tamasszoke/deno-seed) - Complete boilerplate for development. :seedling:
- [GitHub Profile Trophy](https://github.com/ryo-ma/github-profile-trophy) - 🏆 Add dynamically generated GitHub Trophy on your readme
- [UsingDeno](https://usingdeno.com) - Curated list of Web Applications & Projects using Deno 🦕.

## Tools

- [commands](https://github.com/buttercubz/commands) - Create commands shortcuts for node js and deno
- [clone](https://github.com/ekaragodin/clone) - A simple utility for the convenient clone.
- [decense](https://github.com/vinliao/decense) - Generate a license with one `deno run` command.
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
- [dmm](https://github.com/drashland/dmm) - Lightweight Deno Module Manager
- [dpm](https://github.com/BoltDoggy/deno#dpm) - Deno Package Manager, install global command for deno. like denoget.
- dvm
  - [justjavac/dvm](https://github.com/justjavac/dvm) - Deno Version Manager: manage multiple active Deno versions.
  - [axetroy/dvm](https://github.com/axetroy/dvm) - Version manger for Deno without runtime dependencies.
  - [dvm.cmd](https://github.com/MarkTiedemann/dvm.cmd) - Deno Version Manager for Windows. Written as a single batch file.
- [elm-live-reload](https://github.com/jinjor/deno-playground/tree/master/elm-live-reload) - An elm live reloader written in Deno.
- [kopo-cli](https://github.com/littletof/kopo-cli) - A Deno registry browser in the terminal.
- [lume](https://github.com/lumeland/lume) - A static site generator similar to Jekyll or Eleventy with support for multiple file formats.
- [make-deno-edition](https://github.com/bevry/make-deno-edition) - Automatically makes package.json projects (such as npm packages and node.js modules) compatible with Deno.
- [nessie](https://github.com/halvardssm/deno-nessie) - Create, migrate and rollback migrations for PostgreSQL, MySQL and SQLite.
- [packer-provisioner-deno](https://github.com/dontlaugh/packer-provisioner-deno) - A Packer plugin that makes it easy to build virtual machine images with Deno scripts.
- [pagic](https://github.com/xcatliu/pagic) - The easiest way to generate static html page from markdown, built with Deno.
- [pika Deno plugin](https://github.com/pikapkg/builders/tree/master/packages/plugin-build-deno/)
- [starter](https://github.com/denorg/starter) - Deno module starter template with GitHub Actions CI
- [task-runner](https://github.com/jinjor/deno-task-runner) - Write tasks just like npm scripts.
- [trex](https://github.com/crewdevio/Trex) - Package management like npm for deno.
- [typescript-deno-plugin](https://github.com/justjavac/typescript-deno-plugin) - Deno language service plugin, providing intellisense in TypeScript files within editors.
- [udd](https://github.com/hayd/deno-udd) - Update Deno dependencies: updates import statements to their latest published version.
- [velociraptor](https://github.com/umbopepato/velociraptor) - An npm-style script runner for Deno.
- [vscode-deno](https://github.com/denoland/vscode_deno) - VS Code extension that provides Deno support using the `TypeScript Deno language service plugin`.
- [Update Deno](https://github.com/marketplace/actions/update-deno) - Github Action that puts a file with the latest Deno Version in your repository.
- [denofn-selfhosted](https://github.com/denofn/denofn-selfhosted) - Self-hosted Deno functions, made with Deno and Docker.

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
- [Create your first News CLI app using Deno](https://medium.com/javascript-in-plain-english/creating-your-first-news-cli-app-using-deno-e1470398c627)
- [Continuous Integration with Deno](https://semaphoreci.com/blog/continuous-integration-with-deno)
- [How to create and validate JSON Web Tokens in Deno](https://www.loginradius.com/engineering/blog/jwt-authentication-with-deno/)
- [Build A Simple Covid19 CLI Tool using Deno](https://www.loginradius.com/engineering/blog/build-a-cli-tool-using-deno/)
- [Creating a Web Application using Deno](https://www.loginradius.com/engineering/blog/a-webapp-in-deno/)
- [Read and Write in a local file with Deno](https://www.loginradius.com/engineering/blog/read-and-write-in-a-local-file-with-deno/)
- [The Hidden Superpower of Deno: xeval](https://stefanbuck.com/blog/hidden-superpower-deno-xeval)
- [Test coverage in Deno with Codecov and GitHub Actions](https://v1rtl.site/blog/coverage-in-deno)
- Deno REST API with Oak Tutorial Series [0](https://www.robinwieruch.de/deno-tutorial), [1](https://www.robinwieruch.de/deno-oak), [2](https://www.robinwieruch.de/deno-oak-rest-api)
- [Runtime permissions in Deno](https://findthedifficult.com/runtime-permissions-in-deno/)
- [Using Webstorage in Deno](https://findthedifficult.com/deno-1-10-released-support-for-webstorage/)
## Presentations

- [10 Things I Regret About Node.js - Ryan Dahl - JSConf EU 2018](https://www.youtube.com/watch?v=M3BM9TB-8yA)
  - [Slides](https://tinyclouds.org/jsconf2018.pdf)
- [JSDC 2018#A01 - Deno, A New Server-Side Runtime By Ryan Dahl](https://www.youtube.com/watch?v=FlTG0UXRAkE)
  - [Slides](https://tinyclouds.org/deno_jsdc.pptx)
- [Ryan Dahl. Deno, a new way to JavaScript. JS Fest 2019 Spring](https://www.youtube.com/watch?v=z6JRlx5NC9E)
  - [Slides](https://www.slideshare.net/JSFestUA/js-fest-2019-ryan-dahl-deno-a-new-way-to-javascript)
- [Rafał Pocztarski — From Node.js to Deno - JavaScript/TypeScript runtime built with V8 and Rust [EN]](https://www.youtube.com/watch?v=Aib1OZLy0_c)
- [Ryan Dahl: A secure runtime for JavaScript and TypeScript | js.la April 2019](https://www.youtube.com/watch?v=RAmqgbv247s)
  - [Slides](https://docs.google.com/presentation/d/1CSQVTeH5tFzE4AZVXIpx9Xwew5YS-gxJZ03eRFtNeIc/edit)
- [Ryan Dahl: Deno, a new way to JavaScript - HolyJS 2019 Piter](https://www.youtube.com/watch?v=HjdJzNoT_qg)
  - [Slides](https://docs.google.com/presentation/d/1BjvZx5S8noVfFINptH4jfKfqh9jB9nXlFC0I3oIDtg4/edit)
- [Rafał Pocztarski - What is Deno? A new runtime for modern JavaScript and TypeScript backends for 2020s - Deno Warsaw](https://www.youtube.com/watch?v=aI5A9zvYSjk)
- [Michał Sabiniarz - How to contribute to Deno? - Deno Warsaw](https://www.youtube.com/watch?v=LAtjnKLbPpw)
  - [Slides](https://docs.google.com/presentation/d/1rETgslJS1ks4EihzLpUI3sS_zI46YxAOuQ5B1Z_k1mY/edit?usp=sharing)
- [Bartek Iwańczuk - Deno internals, how modern runtime is built - Deno Warsaw](https://www.youtube.com/watch?v=qt7fbmypAFk)
  - [Slides](https://docs.google.com/presentation/d/1LYNGpyjx9PemL-P__7hVC8mSqkX-jL8VQLMhCRehy00/edit?usp=sharing)
- [Ryan Dahl & Kitson Kelly: Deno is a New Way to JavaScript - TSConf 2019](https://www.youtube.com/watch?v=1gIiZfSbEAE)
- [Bert Belder - Deno - dotJS 2019](https://www.youtube.com/watch?v=puXyo1jGQys)

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
- [Primer vistazo con deno](https://dev.to/buttercubz/first-look-with-deno-spanish-30dh)

### Uzbek

- [Telegram](https://t.me/denolanduz)
