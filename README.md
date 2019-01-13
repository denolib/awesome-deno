## Awesome-Deno [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://api.travis-ci.com/denolib/awesome-deno.svg?branch=master)](https://travis-ci.com/denolib/awesome-deno)

### 

> A curated list of awesome things related to [Deno](https://github.com/denoland/deno).

- [Docs](#docs)
    - [Official Docs](#official-docs)
    - [External Docs](#external-docs)

- [Modules](#modules)

- [Tools](#tools)

- [Presentations](#presentations)

- [Resources in Other Languages](#resources-in-other-languages)

# Docs

### Official Docs

- [Official Site (deno.land)](https://deno.land)
- [Deno API TypeDoc](https://deno.land/typedoc/)
- [Deno Docs](https://github.com/denoland/deno/blob/master/Docs.md)
- [Deno Registry](https://deno.land/x/)

### External Docs

- [A Guide to Deno Core (Design & For Contributors)](https://denolib.gitbook.io/guide)
- [V8 Docs for Deno](https://denolib.github.io/v8-docs/)

# Modules

__NOTICE__: Deno has a few official modules that could be found at [deno_std](https://github.com/denoland/deno_std).

- [abc](https://github.com/zhmushan/abc) - A better Deno framework to create web application.
- [camelcase](https://github.com/denolib/camelcase) - Convert a dash/dot/underscore/space separated string to camelCase: foo-bar → fooBar.
- [colors](https://github.com/denoland/deno_std/tree/master/colors) - A basic console color library intended for Deno.
- [csv](https://github.com/hashrock/deno-fnparse/blob/master/parsers/csv.ts) - A simple CSV parser.
- [dejs](https://github.com/syumai/dejs) - ejs template engine for deno.
- deno-dotenv
    - [pietvanzoen/deno-dotenv](https://github.com/pietvanzoen/deno-dotenv) - Dotenv handling for deno.
    - [cardosomarcos/deno-dotenv](https://github.com/cardosomarcos/deno-dotenv) - Loads environment variables from .env for deno projects.
- [deno-fnparse](https://github.com/hashrock/deno-fnparse) - An extremely simple parser combinator for JavaScript.
- [deno-opn](https://github.com/hashrock/deno-opn) - Opens stuff like websites, files, executables. Cross-platform.
- [deno-pretty-assert](https://github.com/bokuweb/deno-pretty-assert) - A colorful assertEqual for deno.
- [deno-redis](https://github.com/keroxp/deno-redis) - An experimental implementation of redis client for deno.
- [deno-ws](https://github.com/keroxp/deno-ws) - An experimental implementation of websocket server for deno.ts.
- [deno-xml-parser](https://github.com/nekobato/deno-xml-parser) - Deno XML parser ported from segmentio/xml-parser.
- [dinatra](https://github.com/syumai/dinatra) - Sinatra like light weight web app framework for deno.
- [expressive](https://github.com/jinjor/deno-playground/tree/master/expressive) - An express-like web app framework.
- [flags](https://github.com/denoland/deno_std/tree/master/flags) - Command line arguments parser for Deno based on minimist.
- [log](https://github.com/denoland/deno_std/tree/master/log) - Logging module for Deno.
- [marden](https://github.com/muhibbudins/marden) - Markdown Parser for Deno.
- [ms](https://github.com/denolib/ms) - easily convert various time formats to milliseconds.
- [http](https://github.com/denoland/deno_std/tree/master/http) - HTTP module including a file server.
- [oak](https://github.com/kitsonk/oak) - A middleware framework for Deno's net server.
- [path](https://github.com/denoland/deno_std/tree/master/fs/path) - Deno Path Manipulation Libraries.
- [qs](https://github.com/denolib/qs) - A querystring parser with nesting support.
- [watch](https://github.com/jinjor/deno-watch) - A file watcher.
- [wu-diff-js](https://github.com/bokuweb/wu-diff-js) - A diff library to compute differences between two slices using wu(the O(NP)) algorithm.

# Tools

- [deno_ls_plugin](https://www.npmjs.com/package/deno_ls_plugin) a TypeScript plugin which will allow TypeScript outside of Deno to resolve modules in a similar way to the way they are resolved inside of Deno.
- [deno-docker](https://github.com/maxmcd/deno-docker) A docker image
- [denoget](https://github.com/syumai/deno-libs/tree/master/denoget) - denoget installs executable deno script.
- [denoinit](https://github.com/syumai/deno-libs/tree/master/denoinit) - denoinit generates useful files for deno project.
- [denopkg](https://github.com/denopkg/denopkg.com) - An easier way to use code from GitHub in your Deno project.
- [dvm](https://github.com/justjavac/dvm) - Deno Version Manager: manage multiple active deno versions.
- [elm-live-reload](https://github.com/jinjor/deno-playground/tree/master/elm-live-reload) - An elm live reloader written in Deno.
- [task-runner](https://github.com/jinjor/deno-playground/tree/master/task-runner) - Write tasks just like npm scripts.

# Presentations

- [10 Things I Regret About Node.js - Ryan Dahl - JSConf EU 2018](https://www.youtube.com/watch?v=M3BM9TB-8yA)
    - [Slides](https://tinyclouds.org/jsconf2018.pdf)
- [JSDC 2018#A01 - Deno, A New Server-Side Runtime By Ryan Dahl](https://www.youtube.com/watch?v=FlTG0UXRAkE)
    - [Slides](https://tinyclouds.org/deno_jsdc.pptx)

# Resources in Other Languages

## Chinese

- [deno.js.cn](https://deno.js.cn/)
- [Deno 并不是下一代 Node.js](https://juejin.im/post/5b14a390e51d4506c1300bbc)
- [玩 Deno 遇到问题的解决方案](https://juejin.im/post/5b1245b3f265da6e4c6cf249)
- [让我们一起来学习别人学不动的 Deno](https://segmentfault.com/a/1190000015151287)

## Japanese

- [Node.js における設計ミス By Ryan Dahl](https://yosuke-furukawa.hatenablog.com/entry/2018/06/07/080335)
- [mizchi/deno_code_reading.md](https://gist.github.com/mizchi/31e5628751330b624a0e8ada9e739b1e)
- [Denoを読む(1)](https://blog.bokuweb.me/entry/2019/01/11/102706)
