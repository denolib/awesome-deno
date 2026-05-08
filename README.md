# Awesome Deno [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="deno-logo.png" align="right" width="100">](https://deno.land)

Deno is a simple, modern and secure runtime for JavaScript and TypeScript that uses V8 and is built in Rust.

This list is a collection of the best Deno modules and resources.

## Contents

- [Docs](#docs)
  - [Official Docs](#official-docs)
  - [External Docs](#external-docs)
- [Modules](#modules)
  - [Automation](#automation)
  - [CLI utils](#cli-utils)
  - [Cloud APIs](#cloud-apis)
  - [Database](#database)
  - [Editor framework](#editor-framework)
  - [Frontend framework](#frontend-framework)
  - [Game engine](#game-engine)
  - [Logging](#logging)
  - [Machine Learning](#machine-learning)
  - [Mail](#mail)
  - [Markdown](#markdown)
  - [Math](#math)
  - [Static site generator](#static-site-generator)
  - [String utils](#string-utils)
  - [Social Platform APIs](#social-platform-apis)
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
- [Integrations](#integrations)
- [Articles](#articles)
- [Blogs/Newsletters](#blogsnewsletters)
- [Presentations](#presentations)
- [Resources](#resources)
  - [Books](#books)
- [Resources in Other Languages](#resources-in-other-languages)
  - [Chinese](#chinese)
  - [Hebrew](#hebrew)
  - [Indonesian](#indonesian)
  - [Italian](#italian)
  - [Japanese](#japanese)
  - [Korean](#korean)
  - [Russian](#russian)
  - [Spanish](#spanish)
  - [Darija (Arabe marocain)](#darija)
  - [Kurdish (Central)](#kurdish-central)

## Docs

### Official Docs

- [Deno API Reference](https://docs.deno.com/api)
- [Deno Manual](https://docs.deno.com)
- [Deno Standard Library](https://jsr.io/@std)
- [Official Site](https://deno.com)

### External Docs

- [V8 Docs for Deno](https://denolib.github.io/v8-docs/)

## Modules

### Automation
- [swissknife](https://github.com/fakoua/SwissKnife) - SwissKnife - Deno Swiss Knife tools for Windows.

### CLI utils
- [cac](https://github.com/cacjs/cac) - Simple yet powerful framework for building command-line apps.
- [charmd](https://github.com/littletof/charmd) - A simple, extendable markdown renderer for your terminal.
- [cli-spinner](https://github.com/ameerthehacker/deno-cli-spinners) - Show spinners in the terminal while running long tasks.
- [cliffy](https://github.com/c4spar/cliffy) - The complete solution for building interactive command-line tools.
- [clite](https://github.com/jersou/clite-parser) - Automatic CLI generation from a class.
- [commit-sage-cli](https://github.com/AhmedOsman101/commit-sage-cli) - Generates Conventional Commit messages with AI based on Git repository changes.
- [tui](https://github.com/Im-Beast/deno_tui) - Module which allows easy creation of Terminal User Interfaces.
- [yargs](https://github.com/yargs/yargs) - The modern, pirate-themed successor to optimist.

### Cloud APIs
- [aws-api](https://aws-api.deno.dev/) - From-scratch Typescript AWS API client built for Deno.
- [googleapis](https://googleapis.deno.dev/) - Auto-generated Google API clients for Deno.

### Database
- [@iuioiua/redis](https://jsr.io/@iuioiua/redis) - Fast, lightweight Redis client built upon the Web Streams API.
- [aloedb](https://github.com/Kirlovon/aloedb) - Light, Embeddable, NoSQL database for Deno without dependencies.
- [deno_mongo](https://github.com/denodrivers/mongo) - MongoDB database driver.
- [deno_mysql](https://github.com/denodrivers/mysql) - MySQL database driver.
- [denodb](https://github.com/eveningkid/denodb) - MySQL, SQLite, MariaDB, PostgreSQL and MongoDB ORM for Deno.
- [dongoose](https://github.com/roonie007/dongoose) - A simple and easy to use ORM for Deno KV.
- [maxminddb](https://github.com/josh-hemphill/maxminddb-wasm) - A library that enables the usage of MaxmindDB geoIP database files
- [nessie](https://github.com/halvardssm/deno-nessie) - Create, migrate and rollback migrations for PostgreSQL, MySQL and SQLite.
- [postgres](https://github.com/denodrivers/postgres) - Driver for PostgreSQL database.
- [redis](https://github.com/denodrivers/redis) - An experimental implementation of redis client for deno.
- [yongo](https://github.com/yooneskh/yongo) - Subset of Mongoose api in deno (like populate) but will not fully copy mongoose

### Editor framework

- [Denops](https://github.com/vim-denops/denops.vim) - 🐜 An ecosystem to write Vim/Neovim plugins with Deno.

### Frontend framework
- [fresh](https://github.com/denoland/fresh) - The next-gen web framework.
- [packup](https://github.com/kt3k/packup) - Zero-config web application packager for Deno.
- [ultra](https://github.com/exhibitionist-digital/ultra) - 💎 Modern Streaming React Framework in Deno.

### Game engine
- [caviar](https://github.com/load1n9/caviar) - ⚡ Blazing fast, modern, Game Engine powered by WebGPU for Deno and the browser
- [sdl2](https://github.com/littledivy/deno_sdl2) - SDL2 module for Deno

### Image
- [ImageScript](https://github.com/matmen/ImageScript) - Image processing in JavaScript, utilizing WebAssembly for performance.
- [monke](https://github.com/retraigo/monke) - Color quantization and dithering library with extra image filters (blur, invert, etc).

### Logging
- [LogTape](https://github.com/dahlia/logtape) - Simple logging library with zero dependencies for Deno/Node.js/Bun/browsers.

### Machine learning
- [appraisal](https://github.com/retraigo/appraisal) - Feature extraction and conversion.
- [classy-lala](https://github.com/retraigo/la-classy) - Single-layer perceptrons for supervised learning tasks.
- [netsaur](https://github.com/denosaurs/netsaur) - Powerful machine learning, accelerated by WebGPU

### Mail
- [deno-smtp](https://github.com/manyuanrong/deno-smtp) - A smtp mail sender for deno.

### Markdown
- [LiteMarkup](https://github.com/tuures/LiteMarkup) - AST-first parser. Under 3 KB gzipped, zero dependencies.

### Math
- [neo](https://github.com/denosaurs/neo/) - Matrix and other math, accelerated by WebGPU

### Static site generator
- [lume](https://github.com/lumeland/lume) - A static site generator similar to Jekyll or Eleventy with support for multiple file formats.
- [pagic](https://github.com/xcatliu/pagic) - The easiest way to generate static html page from markdown, built with Deno.

### String utils
- [written](https://github.com/vixalien/written) - A provides a set of utilities for manipulating text, with a focus on providing typographic tools rather than pure string manipulation.

### Social Platform APIs
- [discordeno](https://github.com/discordeno/discordeno) - Discord API library for Deno
- [grammY](https://github.com/grammyjs/grammY) - Telegram Bot API framework for Deno.
- [MTKruto](https://github.com/MTKruto/MTKruto) - Deno-first, cross-runtime client library for Telegram's MTProto API.


### Template engine
- [dejs](https://github.com/syumai/dejs) - Ejs template engine for deno.
- [eta](https://github.com/bgub/eta) - Fast, lightweight, and configurable embedded template engine.
- [handlebars](https://github.com/alosaur/handlebars) - Handlebars template engine for deno

### Testing
- [deno-puppeteer](https://github.com/lucacasonato/deno-puppeteer) - A library which provides a high-level API to control Chromium or Chrome over the DevTools Protocol.
- [qunitx](https://github.com/izelnakri/qunitx) - Zero dependency, fully customizable, mature, universal test API that can run interchangably in node.js, Deno & browser, using default runtime test runners.
- [rhum](https://github.com/drashland/rhum) - A lightweight testing framework for Deno.
- [superdeno](https://github.com/cmorten/superdeno) - Super-agent driven library for testing Deno HTTP servers.
- [superoak](https://github.com/cmorten/superoak) - HTTP assertions for Oak made easy via SuperDeno.
- [tepi](https://deno.land/x/tepi) - A .http Test Runner
- [unexpected](https://github.com/unexpectedjs/unexpected) - Extensible BDD assertion toolkit.

### Utils
- [buckets](https://github.com/jacoborus/deno-buckets) - Bundle assets and scripts in a single executable file.
- [colors](https://github.com/retraigo/colors) - Color conversions and operations in TypeScript.
- [computed_types](https://github.com/neuledge/computed-types) - Joi like validators for Typescript and Deno.
- [croner](https://github.com/Hexagon/croner) - Cron library with advanced scheduling features, well-documented API, and zero dependencies.
- [deno-config](https://github.com/yooneskh/deno-unified-config) - Utility to streamline deno app configuration management through cli, .env and json files
- [deno_kv_fs](https://github.com/hviana/deno_kv_fs) Deno KV file system, compatible with Deno deploy. Makes use of Web Streams API.
- [denon](https://github.com/denosaurs/denon/blob/master/mod.ts) - A file watcher with a for-await generator.
- [dinoenv](https://deno.land/x/dinoenv) - tiny library to manage environment variables with deno.
- [durationjs](https://github.com/retraigo/duration.js) - Get formatted time duration from a timestamp or a human-readable string.
- [esm-itter](https://github.com/tillsanders/esm-itter) – A strongly typed fork of the popular EventEmitter3 with a focus on EcmaScript module syntax, TypeScript and modern tooling.
- [evt](https://github.com/garronej/evt) - Type safe replacement for EventEmitter.
- [fastest-validator](https://github.com/icebob/fastest-validator) - Schema validator for all javascript platforms
- [fortuna](https://github.com/retraigo/fortuna) - Weighted gacha system.
- [garn-validator](https://github.com/jupegarnica/garn-validator) - Create validations with ease.
- [locale-kit](https://deno.land/x/localekit) ([GitHub](https://github.com/locale-kit/locale-kit)) - A internationalisation/localisation/translation (i18n/l10n/t9n) library with a wrapper for Fresh and support for plurals and dynamic replacement.
- [optionals](https://github.com/OliverBrotchie/optionals) - Rust-like error handling and options with exhaustive pattern matching.
- [PLS](https://github.com/xorgram/pls) - Use 2 lines to persist localStorage in any database, including, but not limited to, MongoDB, PostgreSQL and Redis.
- [qrcode](https://github.com/denorg/qrcode) - QR code image generator for Deno.
- [rubico](https://github.com/a-synchronous/rubico) - 🏞 [a]synchronous function composition; it just works.
- [solc](https://github.com/deno-web3/solc) - 💎 Solidity bindings for Deno.
- [switcher4deno](https://github.com/switcherapi/switcher-client-deno) - Feature Flag Deno SDK client for Switcher-API.
- [wu-diff-js](https://github.com/bokuweb/wu-diff-js) - A diff library to compute differences between two slices using wu(the O(NP)) algorithm.

### Validation

- [zod](https://github.com/colinhacks/zod) - TypeScript-first schema validation with static type inference.

### Web framework
- [alosaur](https://github.com/alosaur/alosaur) - Alosaur - Deno web framework with many ES Decorators.
- [aqua](https://github.com/predetermined/aqua) - A minimal and fast web framework for Deno.
- [danet](https://github.com/Savory/Danet) - A Savory web framework for Deno heavily inspired by [Nest.js](https://nestjs.com).
- [drash](https://github.com/drashland/drash) - A REST microframework for Deno's HTTP server with zero dependencies.
- [faster](https://github.com/hviana/faster) - A fast and optimized middleware server with a set of useful middlwares.
- [faster_react](https://github.com/hviana/faster_react) - Full Stack web framework with React + Faster. Fully compatible with Deno Deploy.
- [hono](https://github.com/honojs/hono) - Ultrafast web framework for Cloudflare Workers, Deno, and Bun. Fast, but not only fast.
- [oak](https://github.com/oakserver/oak) - A middleware framework for Deno's net server.
  - [oak-http-proxy](https://github.com/cmorten/oak-http-proxy) - Proxy middleware for Deno Oak HTTP servers.
  - [oak-routing-ctrl](https://github.com/Thesephi/oak-routing-ctrl) - TypeScript Decorators for easy scaffolding API services with the oak framework.
- [opine](https://github.com/cmorten/opine) - Fast, minimalist web framework ported from ExpressJS.
  - [opine-http-proxy](https://github.com/cmorten/opine-http-proxy) - Proxy middleware for Deno Opine HTTP servers.

### WebSocket
- [dropper](https://github.com/denyncrawford/dropper-deno) - Custom event-based WebSockets framework for building real-time apps on Deno 🦕
- [wocket](https://github.com/drashland/wocket) - A WebSocket library for Deno.

### Web utils
- [djwt](https://github.com/Zaubrik/djwt) - Make JSON Web Tokens (JWT) on Deno based on JWT and JWS specifications.
- [forwarded](https://github.com/deno-libs/forwarded) - Deno port of `forwarded` library.
- [fresh_chart](https://github.com/denoland/fresh_charts) - A server-side-rendered charting library for Fresh.
- [gentleRpc](https://github.com/timonson/gentle_rpc) - A JSON-RPC 2.0 TypeScript library for Deno and the browser.
- [gql](https://github.com/deno-libs/gql) - Universal GraphQL HTTP middleware.
- [graphql-tag](https://github.com/deno-libs/graphql_tag) - GraphQL schema AST from template literal.
- [nats](https://github.com/nats-io/nats.deno) - A Deno client for the [NATS messaging system](https://nats.io/).
- [obsidian](https://github.com/open-source-labs/obsidian) - A native GraphQL caching client and server module.
- [react-icons](https://react-icons.deno.dev/) - React Icons converted to preact for deno fresh.
- [router](https://github.com/zhmushan/router) - A high-performance basic router works anywhere.
- [rpc](https://github.com/deno-libs/rpc) - JSONRPC server implementation for Deno.
- [ts-prometheus](https://github.com/marcopacini/ts_prometheus) - A prometheus client.

### Webview
- [webview](https://github.com/webview/webview_deno) - Deno bindings for webview, a tiny library for creating web-based desktop GUIs.

### XML
- [sax-ts](https://github.com/Maxim-Mazurok/sax-ts) - SAX-style XML parser ported from [sax-js](https://github.com/isaacs/sax-js).

## Registries

- [crux.land](https://crux.land/) - A free registry service meant for hosting small ( < 10kB) single deno scripts.
- [Deno PKG](https://denopkg.com/) - An easier way to use code from GitHub in your Deno project.
- [deno.land/x/](https://deno.land/x/) - The official 3rd party module registry.
- [nest.land](https://nest.land) - An immutable, blockchain powered Deno package registry. 🥚

## Showcases

- [Deno Rest](https://github.com/Prolifode/deno_rest) - A Boilerplate for deno RESTful apis.
- [Edrys](https://github.com/edrys-org/edrys) - Remote Teaching Software
- [GitHub Profile Trophy](https://github.com/ryo-ma/github-profile-trophy) - 🏆 Add dynamically generated GitHub Trophy on your readme
- [ShopSavvy Deno Deploy](https://github.com/shopsavvy/deno-deploy-shopsavvy) - Deno Deploy router with Hono for product search, real-time pricing, and price history.
- [The Official Showcase](https://deno.land/showcase) - The official showcase of Deno.
- [UsingDeno](https://usingdeno.com) - Curated list of Web Applications & Projects using Deno 🦕.

## Tools

- [clone](https://github.com/ekaragodin/clone) - A simple utility for the convenient clone.
- [denoflow](https://github.com/denoflow/denoflow) - Configuration as code, use YAML to write automated workflows that run on Deno, with any Deno modules, Typescript/Javascript codes
- [denoify](https://github.com/garronej/denoify) - For NPM module authors that would like to support Deno but do not want to write and maintain a port.
- [denoliver](https://github.com/joakimunge/denoliver) - A simple, dependency free file server with live reload.
- [denomander](https://github.com/siokas/denomander) - Deno command-line interfaces inspired from commander.js.
- [denon](https://github.com/denosaurs/denon) - A daemon script runner, like nodemon. Built in and for Deno.
- [denopendabot](https://github.com/apps/denopendabot) - Dependabot for Deno projects.
- [denopkg](https://github.com/egoist-labs/denopkg.com) - An easier way to use code from GitHub in your Deno project.
- [Deno Dig](https://github.com/theGEBIRGE/DenoDig) - A tool for extracting application code and npm packages from stand-alone Deno executables.
- [deno_docker](https://github.com/denoland/deno_docker) - Latest dockerfiles and images for Deno - alpine, centos, debian, ubuntu.
- [dmm](https://github.com/drashland/dmm) - Lightweight Deno Module Manager
- [dnt](https://github.com/denoland/dnt) - Deno to npm package build tool.
- [dpm](https://github.com/dpmland/dpm) - Deno Package Manager, a NPM | Yarn Experience for Deno
- dvm
  - [asdf-community/asdf-deno](https://github.com/asdf-community/asdf-deno) - Deno plugin for [asdf](https://asdf-vm.com/)
  - [justjavac/dvm](https://github.com/justjavac/dvm) - Deno Version Manager: manage multiple active Deno versions.
  - [axetroy/dvm](https://github.com/axetroy/dvm) - Version manger for Deno without runtime dependencies.
  - [ghosind/dvm](https://github.com/ghosind/dvm) - A lightweight Deno Version Manager for Linux/MacOS.
- [entype](https://github.com/bcheidemann/entype) - A CLI tool used to generate type definitions for serialised data, currently supporting JSON to Rust and TypeScript.
- [kopo-cli](https://github.com/littletof/kopo-cli) - A Deno registry browser in the terminal.
- [make-deno-edition](https://github.com/bevry/make-deno-edition) - Automatically makes package.json projects (such as npm packages and node.js modules) compatible with Deno.
- [pup](https://github.com/Hexagon/pup) - Advanced process manager for Deno. With autorestart, fs watch, cron start, process telemetry, ipc, clustering, load balancer and more.
- [studio-pack-generator](https://github.com/jersou/studio-pack-generator) - Convert a folder or a RSS URL to Studio pack for Lunii device
- [trex](https://github.com/crewdevio/Trex) - Package management like npm for deno.
- [udd](https://github.com/hayd/deno-udd) - Update Deno dependencies: updates import statements to their latest published version.
- [vscode-deno](https://github.com/denoland/vscode_deno) - VS Code extension that provides Deno support using the `TypeScript Deno language service plugin`.

## Integrations

- [Netlify Edge Functions](https://docs.netlify.com/edge-functions/overview/) - Edge Functions connect the Netlify platform and workflow.
- [Slack Custom Functions](https://api.slack.com/future/functions/custom) - Build custom Run On Slack functions using Deno.
- [Smallweb](https://www.smallweb.run/) - A personal cloud contained in a single directory. You can customize the server behavior using Deno.
- [Supabase Edge Functions](https://supabase.com/docs/guides/functions) - Edge Functions are server-side TypeScript functions, distributed globally at the edge.
- [Astro](https://docs.astro.build/en/guides/deploy/deno/) - Deploy a server-side rendered Astro site to Deno Deploy.

## Blogs/Newsletters
- [Craig's Deno Diary](https://deno-blog.com) - A blog focussing on Deno tech & lib howtos.
- [Deno Blog](https://deno.com/blog) - The official blog of the Deno Company.
- [Deno News](https://deno.news) - A newsletter of Deno articles, news and cool projects.

## Articles

- [Develop with Deno and Visual Studio Code](https://medium.com/@kitsonk/develop-with-deno-and-visual-studio-code-225ce7c5b1ba)
- [First thoughts on Deno, the JavaScript/TypeScript run-time](https://43081j.com/2019/01/first-look-at-deno)
- [Getting started with Deno](https://dev.to/wuz/getting-started-with-deno-e1m)
- [What's Deno, and how is it different from Node.js?](https://dev.to/bnevilleoneill/what-s-deno-and-how-is-it-different-from-node-js-366g)
- [Write a small API using Deno](https://dev.to/kryz/write-a-small-api-using-deno-1cl0)
- [Deno on Cloud Run](https://medium.com/google-cloud/deno-on-cloud-run-89ae64d1664d)
- [Learn Deno: Chat app](https://aralroca.com/blog/learn-deno-chat-app)
- [From Node to Deno](https://dev.to/aralroca/from-node-to-deno-5gpn)
- [Create a simple Note-taking app with Deno](https://dev.to/jeferson_sb/create-a-simple-note-taking-app-with-deno-3k7g)
- [Building API's using Deno, Oak and MYSQL](https://codeforgeek.com/building-api-server-using-deno-and-mysql/)
- [Create your first News CLI app using Deno](https://medium.com/javascript-in-plain-english/creating-your-first-news-cli-app-using-deno-e1470398c627)
- [Continuous Integration with Deno](https://semaphoreci.com/blog/continuous-integration-with-deno)
- [The Hidden Superpower of Deno: xeval](https://stefanbuck.com/blog/hidden-superpower-deno-xeval)
- Deno REST API with Oak Tutorial Series [0](https://www.robinwieruch.de/deno-tutorial), [1](https://www.robinwieruch.de/deno-oak), [2](https://www.robinwieruch.de/deno-oak-rest-api)
- [Getting Started with Deno](https://sabe.io/tutorials/getting-started-with-deno)
- [How to deploy a Deno app using Docker](https://sabe.io/tutorials/how-to-deploy-deno-app-docker)

## Presentations

- [10 Things I Regret About Node.js - Ryan Dahl - JSConf EU 2018](https://www.youtube.com/watch?v=M3BM9TB-8yA)
  - [Slides](https://tinyclouds.org/jsconf2018.pdf)
- [JSDC 2018#A01 - Deno, A New Server-Side Runtime By Ryan Dahl](https://www.youtube.com/watch?v=FlTG0UXRAkE)
- [Ryan Dahl. Deno, a new way to JavaScript. JS Fest 2019 Spring](https://www.youtube.com/watch?v=z6JRlx5NC9E)
  - [Slides](https://www.slideshare.net/JSFestUA/js-fest-2019-ryan-dahl-deno-a-new-way-to-javascript)
- [Rafał Pocztarski — From Node.js to Deno - JavaScript/TypeScript runtime built with V8 and Rust [EN]](https://www.youtube.com/watch?v=Aib1OZLy0_c)
- [Ryan Dahl: A secure runtime for JavaScript and TypeScript | js.la April 2019](https://www.youtube.com/watch?v=RAmqgbv247s)
  - [Slides](https://docs.google.com/presentation/d/1CSQVTeH5tFzE4AZVXIpx9Xwew5YS-gxJZ03eRFtNeIc/edit)
- [Ryan Dahl: Deno, a new way to JavaScript - HolyJS 2019 Piter](https://www.youtube.com/watch?v=HjdJzNoT_qg)
  - [Slides](https://docs.google.com/presentation/d/1BjvZx5S8noVfFINptH4jfKfqh9jB9nXlFC0I3oIDtg4/edit)
- [Rafał Pocztarski - What is Deno? A new runtime for modern JavaScript and TypeScript backends for 2020s - Deno Warsaw](https://www.youtube.com/watch?v=aI5A9zvYSjk)
- [Michał Sabiniarz - How to contribute to Deno? - Deno Warsaw](https://www.youtube.com/watch?v=LAtjnKLbPpw)
- [Bartek Iwańczuk - Deno internals, how modern runtime is built - Deno Warsaw](https://www.youtube.com/watch?v=qt7fbmypAFk)
  - [Slides](https://docs.google.com/presentation/d/1LYNGpyjx9PemL-P__7hVC8mSqkX-jL8VQLMhCRehy00/edit?usp=sharing)
- [Ryan Dahl & Kitson Kelly: Deno is a New Way to JavaScript - TSConf 2019](https://www.youtube.com/watch?v=1gIiZfSbEAE)
- [Bert Belder - Deno - dotJS 2019](https://www.youtube.com/watch?v=puXyo1jGQys)
- [Kitson P. Kelly - Deno, and The Future of JavaScript Runtimes - CityJS Conf 2020](https://www.youtube.com/watch?v=2eRyZpX4qvI)
- [Matías Insaurralde - Deno: an experimental approach on V8 interoperability [EN subtitles] - NodeConf Argentina 2019](https://www.youtube.com/watch?v=N0BRE-0n2cU)
  - [Slides](https://speakerdeck.com/matiasinsaurralde/deno-an-experimental-approach-on-v8-interoperability)

## Resources

### Books
- [Modern Web Development with Deno](https://bpbonline.com/products/modern-web-development-with-deno)

## Resources in Other Languages

### Chinese

- [Deno 并不是下一代 Node.js](https://juejin.im/post/5b14a390e51d4506c1300bbc)
- [玩 Deno 遇到问题的解决方案](https://juejin.im/post/5b1245b3f265da6e4c6cf249)
- [让我们一起来学习别人学不动的 Deno](https://segmentfault.com/a/1190000015151287)
- [Design Mistakes in Node zh-CN](https://zhuanlan.zhihu.com/p/37637923)
- [Node之父ry：Node中的设计错误](https://mp.weixin.qq.com/s/7XAiYw18c8YZc-fXk0-wrw)
- [Node之父 - Deno，一个新的JS运行时](https://www.bilibili.com/video/av52038617)

### Hebrew

- [Deno intro in Hebrew (slides in English)](https://www.youtube.com/watch?v=9tJ_LkI6_qw)

### Indonesian

- [Berkenalan dengan Deno](https://medium.com/@redhajuanda/berkenalan-dengan-dengan-deno-c48cdf3aa31e)
- [Perkenalan Deno dan Instalasi](https://youtu.be/V_kpUTJSd9c)
- [Deno Land Indonesia Telegram group](https://t.me/deno_id)

### Italian

- [Deno - L'anagramma di Node](https://www.slideshare.net/FrancescoSciuti/deno-lanagramma-di-node)

### Japanese

- [deno-ja](https://deno-ja.deno.dev/) - Deno Japanese User Group.
- [Node.js における設計ミス By Ryan Dahl](https://yosuke-furukawa.hatenablog.com/entry/2018/06/07/080335)
- [mizchi/deno_code_reading.md](https://gist.github.com/mizchi/31e5628751330b624a0e8ada9e739b1e)
- [Design Mistakes in Node & Deno #kng5 / deno](https://speakerdeck.com/masashi/deno)
- [Dive into Deno：プロセス起動からTypeScriptが実行されるまで](https://blog.leko.jp/post/code-reading-of-deno-boot-process/)

### Korean

- [Deno Korea](https://deno.kr/) - Deno Korean User Group.

### Russian

- [Telegram channel](https://t.me/denoland_ru)
- [Telegram chat](https://t.me/denoland)

### Spanish

- [Hola Deno! . 🦕](https://medium.com/javascript-espa%C3%B1ol/hola-deno-f31f9f6f2c84)
- [Así puedes crear tu primera API REST con Deno](https://medium.com/@mpampols/as%C3%AD-puedes-crear-tu-primera-api-rest-con-deno-a9094ee5c0b2)
- [Primeros pasos con Deno 🦕 El sucesor de NodeJS desarrollado con Rust y TypeScript](https://medium.com/@manurua/primeros-pasos-con-deno-el-nuevo-nodejs-desarrollado-con-rust-y-typescript-b9ac14f7d0c7)
- [Primer vistazo con deno](https://dev.to/buttercubz/first-look-with-deno-spanish-30dh)

### Darija

- [A first look at Deno | BlaBlaConf 2021 🇲🇦](https://www.youtube.com/watch?v=Y_etUvzAa4s)

### Kurdish (Central)

- [A short introduction to Deno](https://devs.krd/about-deno)
