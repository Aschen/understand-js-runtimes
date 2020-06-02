# Understanding Javascript Runtimes (Focused on V8)

![logo](https://kuzzle.io/static/public/images/logo_black.png)

I gathered these various resources about Javascript interpreters and V8 in particular by preparing a conference on understanding how Javascript engines work.

We use theses informations everyday at [Kuzzle](https://github.com/kuzzleio/kuzzle) to develop our scalable open source backend to offer the best performances to our users.

Link to the slides: https://docs.google.com/presentation/d/13AHi75kKZPM74pBLc9zg3s5hBkFSIiM3z_yqwRx7C8E/edit
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

:question::question: If you have any question, you can fill an issue on this repo and I will try to answer you the best I can :point_right: [New Question](https://github.com/Aschen/understand-js-runtimes/issues/new)

## Optimizations

 - [Closures optimizations & reducing object size](https://www.reaktor.com/blog/javascript-performance-fundamentals-make-bluebird-fast/) by Petka Antonov (Bluebird) - 2019
 - [Various Tricks to Optimize JS Code](https://alligator.io/js/v8-engine/) by Paul Ryan (Alligator) - 2019
 
## Objects Hidden Classes

 - [Javascript Types and effect on Hidden Classes](https://v8.dev/blog/react-cliff) by Benedikt Meurer (v8) and Mathias Bynens (v8) - 2019
 - [Hidden Classes and Inline Cache Explanation](https://mathiasbynens.be/notes/shapes-ics) by Benedikt Meurer (v8) and Mathias Bynens (v8) - 2018
 - [Prototype Chain Explanation](https://mathiasbynens.be/notes/prototypes) by Benedikt Meurer (v8) and Mathias Bynens (v8) - 2018
 
## Closures
 - [How Closures Works](https://www.quora.com/Technically-how-do-JavaScript-closures-work) by Logan R. Kearsley - 2019
 - [Closures Compilation and Allocation](https://stackoverflow.com/questions/36529656/when-are-closures-allocated-and-compiled-in-node-js-v8) by Bergi - 2016
 - [Closure Context and Closure Chain](https://davidshariff.com/blog/javascript-scope-chain-and-closures/) by Davic Shariff (Amazon) - 2013
 - [Are Arrow Function Faster](https://stackoverflow.com/questions/44030645/are-arrow-functions-faster-more-performant-lighter-than-ordinary-standalone-f/44031830) by Mathias Bynens (v8) - 2019
 
## Javascript Interpreter Workflow

 - [Interpreter and Compiler: hidden classes, inline caching, polymorphism and megamorphism](https://www.freecodecamp.org/news/javascript-essentials-why-you-should-know-how-the-engine-works-c2cc0d321553/) by Rainer Hahnekamp - 2018
 - [Interpreter Just-In-Time](https://blog.logrocket.com/how-javascript-works-optimizing-the-v8-compiler-for-efficiency/)  by Alvin Wan (LogRocket) - 2019
 - [Ignition Design Document](https://docs.google.com/document/d/11T2CRex9hXxoJwbYqVQ32yIPMh0uouUZLdyrtmMoL44/edit?ts=56f27d9d#) by rmcilroy@ and oth@ - 2016 
 - [Turbofan Speculative Optimization](https://ponyfoo.com/articles/an-introduction-to-speculative-optimization-in-v8) by Benedikt Meurer (v8) - 2017
 - [Ignition Presentation](https://docs.google.com/presentation/d/1HgDDXBYqCJNasBKBDf9szap1j4q4wnSHhOYpaNy5mHU/edit) by Ross McIlroy (Google London)
 - [Inline Caches with Monomorphism, Polymorphism and Megamorphism](https://mrale.ph/blog/2015/01/11/whats-up-with-monomorphism.html) by Vyacheslav Egorov - 2015

## Tools

 - [Node.js Runtime Options List](https://flaviocopes.com/node-runtime-v8-options/) - 2019
 - [ESlint sort-keys rule](https://eslint.org/docs/rules/sort-keys)
 
## Others
 
  - [Differences between Traditional interpreter, JIT compiler, JIT interpreter and AOT compiler](https://softwareengineering.stackexchange.com/questions/246094/understanding-the-differences-traditional-interpreter-jit-compiler-jit-interp) by Jörg W Mittag - 2015
  - [Micro Benchmark Issues](https://stackoverflow.com/questions/56740808/how-v8-optimise-code-using-hidden-classes-and-inline-caching) by jmrk (v8) - 2019
  - [Micto Benchmark Fairy tale](https://mrale.ph/blog/2012/12/15/microbenchmarks-fairy-tale.html) by Vyacheslav Egorov - 2012
  - [Exploring v8 performance characteristics in Node](https://github.com/davidmarkclements/v8-perf) by David Mark Clements - 2016
  - [Understanding Ignition Bytecode](https://medium.com/dailyjs/understanding-v8s-bytecode-317d46c94775) by Franziska Hinkelmann (Google) - 2017
  - [ Notes and resources related to v8 and thus Node.js performance](https://github.com/thlorenz/v8-perf/) by Thorsten Lorenz - 2018
  - [Understanding V8 bytecode](https://medium.com/dailyjs/understanding-v8s-bytecode-317d46c94775) by Franziska Hinkelmann - 2017
