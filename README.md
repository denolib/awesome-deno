# Awesome-Deno [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome things related to [Deno](https://github.com/denoland/deno).

[Deno](https://github.com/denoland/deno) is a browser-like secure TypeScript/JavaScript runtime built on V8 JavaScript engine, Rust, and TypeScript. It aims to provide a secure and productive scripting system, making use of latest language features and with certain degree of browser compatibility

# Contents

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

- [A Guide to Deno Core (Design & For Contributors)](https://denolib.gitbook.io/guide)
- [V8 Docs for Deno](https://denolib.github.io/v8-docs/)

# Modules

__NOTICE__: Deno has a few official modules that could be found at [deno_std](https://github.com/denoland/deno_std).

- [abc](https://github.com/zhmushan/abc) - Better Deno framework to create web application.
- [camelcase](https://github.com/denolib/camelcase) - Convert a dash/dot/underscore/space separated string to camelCase: foo-bar → fooBar.
- [colors](https://github.com/denoland/deno_std/tree/master/colors) - Basic console color library intended for Deno.
- [cli-spinner](https://github.com/ameerthehacker/cli-spinners) - Show spinners in the terminal while running long tasks
- [csv](https://github.com/hashrock/deno-fnparse/blob/master/parsers/csv.ts) - Simple CSV parser.
- [dcc](https://github.com/BoltDoggy/deno#dcc) - Reloading deps when next running (Deno Cache Clean).
- [dejs](https://github.com/syumai/dejs) - EJS template engine for deno.
- deno-dotenv
    - [pietvanzoen/deno-dotenv](https://github.com/pietvanzoen/deno-dotenv) - Dotenv handling for deno.
    - [cardosomarcos/deno-dotenv](https://github.com/cardosomarcos/deno-dotenv) - Load environment variables from .env for deno projects.
- [deno-fnparse](https://github.com/hashrock/deno-fnparse) - Extremely simple parser combinator for JavaScript.
- [deno-globrex](https://github.com/hayd/deno-globrex) - Port of globrex to deno, glob to regular expression.
- [deno-opn](https://github.com/hashrock/deno-opn) - Open stuff like websites, files, executables. Cross-platform.
- [deno-pretty-assert](https://github.com/bokuweb/deno-pretty-assert) - Colorful assertEqual for deno.
- [deno-redis](https://github.com/keroxp/deno-redis) - Experimental implementation of redis client for deno.
- [deno-using](https://github.com/hayd/deno-using) - Python-style with statements for deno.
- [deno-uuid](https://github.com/lucascaro/deno-uuid) - UUID module for deno.
- [deno-ws](https://github.com/keroxp/deno-ws) - Experimental implementation of websocket server for deno.ts.
- [deno-xml-parser](https://github.com/nekobato/deno-xml-parser) - Deno XML parser ported from segmentio/xml-parser.
- [dinatra](https://github.com/syumai/dinatra) - Sinatra like light weight web app framework for deno.
- [expressive](https://github.com/jinjor/deno-playground/tree/master/expressive) - Express-like web app framework.
- [flags](https://github.com/denoland/deno_std/tree/master/flags) - Command line arguments parser for Deno based on minimist.
- [http](https://github.com/denoland/deno_std/tree/master/http) - HTTP module including a file server.
- [lazy](https://github.com/luvies/lazy) - Linq-like lazy-evaluation iteration module.
- [log](https://github.com/denoland/deno_std/tree/master/log) - Logging module for Deno.
- [marden](https://github.com/muhibbudins/marden) - Markdown Parser for Deno.
- [ms](https://github.com/denolib/ms) - Convert various time formats to milliseconds easily.
- [normalize-diacritics](https://github.com/motss/normalize-diacritics/tree/deno) - Remove accents/diacritics in string.
- [oak](https://github.com/oakserver/oak) - Middleware framework for Deno's net server.
- [path](https://github.com/denoland/deno_std/tree/master/fs/path) - Deno Path Manipulation Libraries.
- [pogo](https://github.com/sholladay/pogo) - Server framework for Deno
- [postgres](https://github.com/bartlomieju/deno-postgres) - Driver for PostgreSQL database.
- [qs](https://github.com/denolib/qs) - Querystring parser with nesting support.
- [textproto](https://github.com/denoland/deno_std/tree/master/textproto) - Module providing text based protocol helpers.
- [watch](https://github.com/jinjor/deno-watch) - File watcher.
- [wu-diff-js](https://github.com/bokuweb/wu-diff-js) - Diff library to compute differences between two slices using wu(the O(NP)) algorithm.

# Tools

- [denoget](https://github.com/syumai/denoget) - Install executable deno script.
- [denoinit](https://github.com/syumai/deno-libs/tree/master/denoinit) - Generate useful files for deno project.
- [denopkg](https://github.com/denopkg/denopkg.com) - Easier way to use code from GitHub in your Deno project.
- [denoversion](https://github.com/lucascaro/denoversion) - SemVer+git version management for Deno.
- [deno-docker](https://github.com/maxmcd/deno-docker) - Docker image.
- [deno-vscode](https://github.com/ameerthehacker/deno-vscode) - Leverage the typedef and intellisense built into vscode using this extension
- [deno_ls_plugin](https://www.npmjs.com/package/deno_ls_plugin) - TypeScript plugin which will allow TypeScript outside of Deno to resolve modules in a similar way to the way they are resolved inside of Deno.
- [deno_init](https://github.com/zhmushan/deno_init) - Initialize a Deno project quickly .
- [dpm](https://github.com/BoltDoggy/deno#dpm) - Install global command for deno (Deno Package Manager), like denoget.
- [dvm](https://github.com/justjavac/dvm) - Manage multiple active deno versions (Deno Version Manager).
- [elm-live-reload](https://github.com/jinjor/deno-playground/tree/master/elm-live-reload) - Elm live reloader written in Deno.
- [task-runner](https://github.com/jinjor/deno-playground/tree/master/task-runner) - Write tasks just like npm scripts.

# Articles

- [Develop with Deno and Visual Studio Code](https://medium.com/@kitsonk/develop-with-deno-and-visual-studio-code-225ce7c5b1ba)
- [First thoughts on Deno, the JavaScript/TypeScript run-time](https://43081j.com/2019/01/first-look-at-deno)

# Presentations

- [10 Things I Regret About Node.js - Ryan Dahl - JSConf EU 2018](https://www.youtube.com/watch?v=M3BM9TB-8yA)
    - [Slides](https://tinyclouds.org/jsconf2018.pdf)
- [JSDC 2018#A01 - Deno, A New Server-Side Runtime By Ryan Dahl](https://www.youtube.com/watch?v=FlTG0UXRAkE)
    - [Slides](https://tinyclouds.org/deno_jsdc.pptx)
    
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

# License

[![cc0](https://camo.githubusercontent.com/60561947585c982aee67ed3e3b25388184cc0aa3/687474703a2f2f6d6972726f72732e6372656174697665636f6d6d6f6e732e6f72672f70726573736b69742f627574746f6e732f38387833312f7376672f63632d7a65726f2e737667)](https://creativecommons.org/publicdomain/zero/1.0/)
