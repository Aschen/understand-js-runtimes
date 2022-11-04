# Understanding Javascript Runtimes (Focused on V8)

![logo](https://avatars.githubusercontent.com/u/12933347)

**Stay up to date with technical aspect of programming** :point_right: https://links.aschen.tech/ (Or on [LinkedIn](https://www.linkedin.com/pulse/e-veille-tech-04022-apprentissage-continu-adrien-maret/))

I gathered these various resources about Javascript interpreters and V8 in particular by preparing a conference on understanding how Javascript engines work.

We use theses informations everyday at [Kuzzle](https://github.com/kuzzleio/kuzzle) to develop our scalable open source backend to offer the best performances to our users.

Link to the slides: https://docs.google.com/presentation/d/13AHi75kKZPM74pBLc9zg3s5hBkFSIiM3z_yqwRx7C8E/edit
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

:question::question: If you have any question, you can fill an issue on this repo and I will try to answer you the best I can :point_right: [New Question](https://github.com/Aschen/understand-js-runtimes/issues/new)

Another repository with a lot of articles about Javascript Engine workflow: https://github.com/fraxken/VM-Resources

## Event Loop and Promises

 - [What is the Event Loop?](https://nodejs.org/en/docs/guides/event-loop-timers-and-nexttick/) by Node.js developers - 2022 ([archive](https://web.archive.org/web/20220604191227/https://nodejs.org/en/docs/guides/event-loop-timers-and-nexttick/))
 - [Faster async functions and promises](https://v8.dev/blog/fast-async) by Maya Armyanova (v8) and Benedikt Meurer (v8)- 2018 ([archive](https://web.archive.org/web/20220205034256/https://v8.dev/blog/fast-async))
 
## Optimizations

 - [Closures optimizations & reducing object size](https://www.reaktor.com/blog/javascript-performance-fundamentals-make-bluebird-fast/) by Petka Antonov (Bluebird) - 2019 ([archive](https://web.archive.org/web/20201005091343/https://www.reaktor.com/blog/javascript-performance-fundamentals-make-bluebird-fast/))
 - [Various Tricks to Optimize JS Code](https://alligator.io/js/v8-engine/) by Paul Ryan (Alligator) - 2019 ([archive](https://web.archive.org/web/20200113172808/https://alligator.io/js/v8-engine/))
 
## Objects and Properties

 - [Javascript Types and effect on Hidden Classes](https://v8.dev/blog/react-cliff) by Benedikt Meurer (v8) and Mathias Bynens (v8) - 2019 ([archive](https://web.archive.org/web/20201108003415/https://v8.dev/blog/react-cliff))
 - [Hidden Classes and Inline Cache Explanation](https://mathiasbynens.be/notes/shapes-ics) by Benedikt Meurer (v8) and Mathias Bynens (v8) - 2018 ([archive](https://web.archive.org/web/20210102112650/https://mathiasbynens.be/notes/shapes-ics))
 - [Prototype Chain Explanation](https://mathiasbynens.be/notes/prototypes) by Benedikt Meurer (v8) and Mathias Bynens (v8) - 2018 ([archive](https://web.archive.org/web/20201201040843/https://mathiasbynens.be/notes/prototypes))
 - [Slack Tracking and Backing Store](https://v8.dev/blog/slack-tracking) by Michael Stanton (v8) - 2020 ([archive](https://web.archive.org/web/20201228001113/https://v8.dev/blog/slack-tracking))
 - [Fast vs Slow Properties](https://v8.dev/blog/fast-properties) by Camillo Bruni (v8) - 2017 ([archive](https://web.archive.org/web/20201116074633/https://v8.dev/blog/fast-properties))
 
## Closures
 - [How Closures Works](https://www.quora.com/Technically-how-do-JavaScript-closures-work) by Logan R. Kearsley - 2019 ([archive](https://pastebin.com/gDUwR7z7))
 - [Closures Compilation and Allocation](https://stackoverflow.com/questions/36529656/when-are-closures-allocated-and-compiled-in-node-js-v8) by Bergi - 2016 ([archive](https://web.archive.org/web/20210111103346/https://stackoverflow.com/questions/36529656/when-are-closures-allocated-and-compiled-in-node-js-v8))
 - [Closure Context and Closure Chain](https://davidshariff.com/blog/javascript-scope-chain-and-closures/) by Davic Shariff (Amazon) - 2013 ([archive](https://web.archive.org/web/20191005041434/http://davidshariff.com/blog/javascript-scope-chain-and-closures/))
 - [Are Arrow Function Faster](https://stackoverflow.com/questions/44030645/are-arrow-functions-faster-more-performant-lighter-than-ordinary-standalone-f/44031830) by Mathias Bynens (v8) - 2019 ([archive](https://web.archive.org/web/20210111103553/https://stackoverflow.com/questions/44030645/are-arrow-functions-faster-more-performant-lighter-than-ordinary-standalone-f/44031830))
 
## Javascript Interpreter Workflow

 - [Interpreter and Compiler: hidden classes, inline caching, polymorphism and megamorphism](https://www.freecodecamp.org/news/javascript-essentials-why-you-should-know-how-the-engine-works-c2cc0d321553/) by Rainer Hahnekamp - 2018 ([archive](https://web.archive.org/web/20210102112642/https://www.freecodecamp.org/news/javascript-essentials-why-you-should-know-how-the-engine-works-c2cc0d321553/))
 - [Interpreter Just-In-Time](https://blog.logrocket.com/how-javascript-works-optimizing-the-v8-compiler-for-efficiency/)  by Alvin Wan (LogRocket) - 2019 ([archive](https://web.archive.org/web/20201128140602/https://blog.logrocket.com/how-javascript-works-optimizing-the-v8-compiler-for-efficiency/))
 - [Ignition Design Document](https://docs.google.com/document/d/11T2CRex9hXxoJwbYqVQ32yIPMh0uouUZLdyrtmMoL44/edit?ts=56f27d9d#) by rmcilroy@ and oth@ - 2016 
 - [Turbofan Speculative Optimization](https://ponyfoo.com/articles/an-introduction-to-speculative-optimization-in-v8) by Benedikt Meurer (v8) - 2017 ([archive](https://web.archive.org/web/20201112011845/https://ponyfoo.com/articles/an-introduction-to-speculative-optimization-in-v8))
 - [Ignition Presentation](https://docs.google.com/presentation/d/1HgDDXBYqCJNasBKBDf9szap1j4q4wnSHhOYpaNy5mHU/edit) by Ross McIlroy (Google London)
 - [Inline Caches with Monomorphism, Polymorphism and Megamorphism](https://mrale.ph/blog/2015/01/11/whats-up-with-monomorphism.html) by Vyacheslav Egorov - 2015 ([archive](https://web.archive.org/web/20201113212358/https://mrale.ph/blog/2015/01/11/whats-up-with-monomorphism.html))
 - [Inside JavaScript Engines, Part 1: Parsing](https://medium.com/@yanguly/inside-javascript-engines-part-1-parsing-c519d75833d7) by Yan Hulyi - 2022 ([archive](https://web.archive.org/web/20220627093333/https://medium.com/@yanguly/inside-javascript-engines-part-1-parsing-c519d75833d7))
 - [Sparkplug — a non-optimizing JavaScript compiler](https://v8.dev/blog/sparkplug#a-fast-compiler) by Leszek Swirski - 2021 ([archive](https://web.archive.org/web/20220605204039/https://v8.dev/blog/sparkplug))

## Tools

 - [Node.js Runtime Options List](https://flaviocopes.com/node-runtime-v8-options/) - 2019 ([archive](https://web.archive.org/web/20200920172728/https://flaviocopes.com/node-runtime-v8-options/))
 - [ESlint sort-keys rule](https://eslint.org/docs/rules/sort-keys)
 - [Indicium - System Analyzer](https://v8.dev/blog/system-analyzer) by Zeynep Cankara - 2020 ([archive](https://web.archive.org/web/20201031041641/https://v8.dev/blog/system-analyzer))
 
## Others
 
  - [Differences between Traditional interpreter, JIT compiler, JIT interpreter and AOT compiler](https://softwareengineering.stackexchange.com/questions/246094/understanding-the-differences-traditional-interpreter-jit-compiler-jit-interp) by Jörg W Mittag - 2015 ([archive](https://web.archive.org/web/20201112012702/https://softwareengineering.stackexchange.com/questions/246094/understanding-the-differences-traditional-interpreter-jit-compiler-jit-interp))
  - [Micro Benchmark Issues](https://stackoverflow.com/questions/56740808/how-v8-optimise-code-using-hidden-classes-and-inline-caching) by jmrk (v8) - 2019 ([archive](https://web.archive.org/web/20210111103951/https://stackoverflow.com/questions/56740808/how-v8-optimise-code-using-hidden-classes-and-inline-caching))
  - [Micro Benchmark Fairy tale](https://mrale.ph/blog/2012/12/15/microbenchmarks-fairy-tale.html) by Vyacheslav Egorov - 2012 ([archive](https://web.archive.org/web/20201115141553/https://mrale.ph/blog/2012/12/15/microbenchmarks-fairy-tale.html))
  - [Exploring v8 performance characteristics in Node](https://github.com/davidmarkclements/v8-perf) by David Mark Clements - 2016 ([archive](https://web.archive.org/web/20200906103437/https://github.com/davidmarkclements/v8-perf/))
  - [Understanding Ignition Bytecode](https://medium.com/dailyjs/understanding-v8s-bytecode-317d46c94775) by Franziska Hinkelmann (Google) - 2017 ([archive](https://web.archive.org/web/20201226122534/http://medium.com/dailyjs/understanding-v8s-bytecode-317d46c94775))
  - [Notes and resources related to v8 and thus Node.js performance](https://github.com/thlorenz/v8-perf/) by Thorsten Lorenz - 2018 ([archive](https://web.archive.org/web/20201110071013/https://github.com/thlorenz/v8-perf))
