# Awesome-Deno [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://api.travis-ci.com/denolib/awesome-deno.svg?branch=master)](https://travis-ci.com/denolib/awesome-deno)

> A curated list of awesome things related to [Deno](https://github.com/denoland/deno).

- [Docs](#docs)
    - [Official Docs](#official-docs)
    - [External Docs](#external-docs)
- [Modules](#modules)
- [Tools](#tools)
- [Articles](#articles)
- [Presentations](#presentations)
- [Newsletters](#newsletters)
- [Resources in Other Languages](#resources-in-other-languages)
  - [Chinese](#chinese)
  - [Hebrew](#hebrew)
  - [Japanese](#japanese)
  - [Korean](#korean)

# Docs

### Official Docs

- [Official Site (deno.land)](https://deno.land)
- [Deno API TypeDoc](https://deno.land/typedoc/)
- [Deno Docs](https://github.com/denoland/deno/blob/master/Docs.md)
- [Deno Registry](https://deno.land/x/)

### External Docs

- [A Guide to Deno Core (Design & For Contributors)](https://denolib.gitbook.io/guide/)
- [V8 Docs for Deno](https://denolib.github.io/v8-docs/)

# Modules

__NOTICE__: Deno has a few official modules that could be found at [deno_std](https://github.com/denoland/deno_std).
Consider submitting to [the deno.land/x](https://github.com/denoland/registry/blob/master/src/database.json) repository.

- [abc](https://github.com/zhmushan/abc) - A better Deno framework to create web application.
- [bytes_formater](https://github.com/manyuanrong/bytes_formater) - Format bytes (Uint8Array、ArrayBufferView...) output, useful when debugging IO functions.
- [cac](https://github.com/cacjs/cac) - Simple yet powerful framework for building command-line apps.
- [camelcase](https://github.com/denolib/camelcase) - Convert a dash/dot/underscore/space separated string to camelCase: foo-bar → fooBar.
- [colors](https://github.com/denoland/deno_std/tree/master/colors) - A basic console color library intended for Deno.
- [cli-spinner](https://github.com/ameerthehacker/cli-spinners) - Show spinners in the terminal while running long tasks
- [csv](https://github.com/hashrock/deno-fnparse/blob/master/parsers/csv.ts) - A simple CSV parser.
- [dcc](https://github.com/BoltDoggy/deno#dcc) - Deno Cache Clean, reloading deps when next running.
- [dejs](https://github.com/syumai/dejs) - ejs template engine for deno.
- [deno-checksum](https://github.com/manyuanrong/deno-checksum) - SHA1/MD5 algorithms.
- deno-dotenv
    - [pietvanzoen/deno-dotenv](https://github.com/pietvanzoen/deno-dotenv) - Dotenv handling for deno.
    - [cardosomarcos/deno-dotenv](https://github.com/cardosomarcos/deno-dotenv) - Loads environment variables from .env for deno projects.
- [deno-fen](https://github.com/fen-land/deno-fen) - Simple web framework.
- [deno-fnparse](https://github.com/hashrock/deno-fnparse) - An extremely simple parser combinator for JavaScript.
- [deno-globrex](https://github.com/hayd/deno-globrex) - Port of globrex to deno, glob to regular expression.
- [deno-mysql](https://github.com/manyuanrong/deno_mysql) - MySQL database driver.
- [deno-opn](https://github.com/hashrock/deno-opn) - Opens stuff like websites, files, executables. Cross-platform.
- [deno-pretty-assert](https://github.com/bokuweb/deno-pretty-assert) - A colorful assertEqual for deno.
- [deno-redis](https://github.com/keroxp/deno-redis) - An experimental implementation of redis client for deno.
- [deno-using](https://github.com/hayd/deno-using) - An python-style with statements for deno.
- [deno-uuid](https://github.com/lucascaro/deno-uuid) - UUID module for deno.
- [deno-ws](https://github.com/keroxp/deno-ws) - An experimental implementation of websocket server for deno.ts.
- [deno-xml-parser](https://github.com/nekobato/deno-xml-parser) - Deno XML parser ported from segmentio/xml-parser.
- [dinatra](https://github.com/syumai/dinatra) - Sinatra like light weight web app framework for deno.
- [expect](https://github.com/allain/expect) - Helpers for writing jest like expect tests in deno.
- [expressive](https://github.com/jinjor/deno-playground/tree/master/expressive) - An express-like web app framework.
- [flags](https://github.com/denoland/deno_std/tree/master/flags) - Command line arguments parser for Deno based on minimist.
- [http](https://github.com/denoland/deno_std/tree/master/http) - HTTP module including a file server.
- [lazy](https://github.com/luvies/lazy) - A linq-like lazy-evaluation iteration module.
- [log](https://github.com/denoland/deno_std/tree/master/log) - Logging module for Deno.
- [marden](https://github.com/muhibbudins/marden) - Markdown Parser for Deno.
- [ms](https://github.com/denolib/ms) - easily convert various time formats to milliseconds.
- [normalize_diacritics](https://github.com/motss/deno_mod/tree/master/normalize_diacritics) - Remove accents/diacritics in string.
- [oak](https://github.com/oakserver/oak) - A middleware framework for Deno's net server.
- [path](https://github.com/denoland/deno_std/tree/master/fs/path) - Deno Path Manipulation Libraries.
- [pogo](https://github.com/sholladay/pogo) - Server framework for Deno
- [postgres](https://github.com/bartlomieju/deno-postgres) - Driver for PostgreSQL database.
- [qs](https://github.com/denolib/qs) - A querystring parser with nesting support.
- [sax-ts](https://github.com/Maxim-Mazurok/sax-ts) - SAX-style XML parser ported from [sax-js](https://github.com/isaacs/sax-js)
- [servest](https://github.com/keroxp/servest) - A progressive HTTP server/router.
- [textproto](https://github.com/denoland/deno_std/tree/master/textproto)
- [watch](https://github.com/jinjor/deno-watch) - A file watcher.
- [wu-diff-js](https://github.com/bokuweb/wu-diff-js) - A diff library to compute differences between two slices using wu(the O(NP)) algorithm.

# Tools

- [denoget](https://github.com/syumai/denoget) - denoget installs executable deno script.
- [denoinit](https://github.com/syumai/deno-libs/tree/master/denoinit) - denoinit generates useful files for deno project.
- [denopkg](https://github.com/denopkg/denopkg.com) - An easier way to use code from GitHub in your Deno project.
- [denoversion](https://github.com/lucascaro/denoversion) - SemVer+git version management for Deno.
- [deno-docker](https://github.com/maxmcd/deno-docker) A docker image.
- [deno-vscode](https://github.com/ameerthehacker/deno-vscode) - Leverage the typedef and intellisense built into vscode using this extension
- [deno_ls_plugin](https://www.npmjs.com/package/deno_ls_plugin) - a TypeScript plugin which will allow TypeScript outside of Deno to resolve modules in a similar way to the way they are resolved inside of Deno.
- [deno_init](https://github.com/zhmushan/deno_init) - Quickly initialize a Deno project.
- [dpm](https://github.com/BoltDoggy/deno#dpm) - Deno Package Manager, install global command for deno. like denoget.
- [dvm](https://github.com/justjavac/dvm) - Deno Version Manager: manage multiple active deno versions.
- [elm-live-reload](https://github.com/jinjor/deno-playground/tree/master/elm-live-reload) - An elm live reloader written in Deno.
- [task-runner](https://github.com/jinjor/deno-playground/tree/master/task-runner) - Write tasks just like npm scripts.
- [typescript-deno-plugin](https://github.com/justjavac/typescript-deno-plugin) - Deno language service plugin, providing intellisense in TypeScript files within editors.
- [vscode-deno](https://github.com/justjavac/vscode-deno) - VS Code extension that provides Deno support using the typescript-deno-plugin.
- [pika deno plugin](https://github.com/pikapkg/builders/tree/master/packages/plugin-build-deno/)

# Articles

- [Develop with Deno and Visual Studio Code](https://medium.com/@kitsonk/develop-with-deno-and-visual-studio-code-225ce7c5b1ba)
- [First thoughts on Deno, the JavaScript/TypeScript run-time](https://43081j.com/2019/01/first-look-at-deno)

# Presentations

- [10 Things I Regret About Node.js - Ryan Dahl - JSConf EU 2018](https://www.youtube.com/watch?v=M3BM9TB-8yA)
    - [Slides](https://tinyclouds.org/jsconf2018.pdf)
- [JSDC 2018#A01 - Deno, A New Server-Side Runtime By Ryan Dahl](https://www.youtube.com/watch?v=FlTG0UXRAkE)
    - [Slides](https://tinyclouds.org/deno_jsdc.pptx)
- [Ryan Dahl. Deno, a new way to JavaScript. JS Fest 2019 Spring](https://www.youtube.com/watch?v=z6JRlx5NC9E)
    - [Slides](https://www.slideshare.net/JSFestUA/js-fest-2019-ryan-dahl-deno-a-new-way-to-javascript)
    
# Newsletters

- [Deno Newsletter](https://deno.news)

# Resources in Other Languages

## Chinese

- [deno.js.cn](https://deno.js.cn/)
- [Deno 并不是下一代 Node.js](https://juejin.im/post/5b14a390e51d4506c1300bbc)
- [玩 Deno 遇到问题的解决方案](https://juejin.im/post/5b1245b3f265da6e4c6cf249)
- [让我们一起来学习别人学不动的 Deno](https://segmentfault.com/a/1190000015151287)
- [Design Mistakes in Node zh-CN](https://zhuanlan.zhihu.com/p/37637923)
- [《Deno进阶开发笔记》](https://github.com/chenshenhai/deno_note/)
- [Deno 手册](https://nugine.github.io/deno-manual-cn/manual-cn.html)
- [Deno 风格指南](https://nugine.github.io/deno-manual-cn/style-guide-cn.html)

## Hebrew

- [Deno intro in Hebrew (slides in English)](https://www.youtube.com/watch?v=9tJ_LkI6_qw)

## Japanese

- [Node.js における設計ミス By Ryan Dahl](https://yosuke-furukawa.hatenablog.com/entry/2018/06/07/080335)
- [mizchi/deno_code_reading.md](https://gist.github.com/mizchi/31e5628751330b624a0e8ada9e739b1e)
- [Denoを読む(1)](https://blog.bokuweb.me/entry/2019/01/11/102706)
- [Design Mistakes in Node & Deno #kng5 / deno](https://speakerdeck.com/masashi/deno)
- [Dive into Deno：プロセス起動からTypeScriptが実行されるまで](https://blog.leko.jp/post/code-reading-of-deno-boot-process/)

## Korean

- [denoland.kr/](https://denoland.kr/)
