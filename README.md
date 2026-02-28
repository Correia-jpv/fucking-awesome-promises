<a href="https://promisesaplus.com/">
    <img src="https://promisesaplus.com/assets/logo-small.png" alt="Promises/A+ logo" align="right" />
</a>

# Awesome Promises [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of useful resources for JavaScript Promises

Inspired by the <b><code>441201⭐</code></b> <b><code>&nbsp;33334🍴</code></b> [awesome](https://github.com/sindresorhus/awesome)) list thing. Not to be confused with other awesome promises like "I promise you a million dollars" or "I promise you'll stay fit and never have to go to the gym again".

**Table of Contents**

- [Resources, Blogs, and Books](#resources-blogs-and-books)
- [Promises/A+ Implementations (ES6/ES2015 compatible)](#promisesa-implementations-es6es2015-compatible)
  - [Strict Implementations](#strict-implementations)
  - [Implementations with extras](#implementations-with-extras)
  - [Fallbacks](#fallbacks)
- [Convenience Utilities](#convenience-utilities)

## Resources, Blogs, and Books

### For beginners
* <b><code>&nbsp;&nbsp;1618⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;191🍴</code></b> [Promise Cookbook](https://github.com/mattdesl/promise-cookbook)) - The why, what, and how. "A brief introduction [...] primarily aimed at frontend developers".
* [Promises for Asynchronous Programming](http://exploringjs.com/es6/ch_promises.html) - Chapter from [Exploring ES6](http://exploringjs.com/)
* <b><code>184441⭐</code></b> <b><code>&nbsp;33636🍴</code></b> [You Don't Know JS: Promises](https://github.com/getify/You-Dont-Know-JS/blob/master/async%20&%20performance/ch3.md)) - Chapter from <b><code>184441⭐</code></b> <b><code>&nbsp;33636🍴</code></b> [You Don't Know JS: Async & Performance](https://github.com/getify/You-Dont-Know-JS/tree/master/async%20%26%20performance))
* 🌎 [JavaScript Promises: an Introduction](developers.google.com/web/fundamentals/getting-started/primers/promises) - Basics of JavaScript's native promise implementation.
* [JavaScript with Promises](http://shop.oreilly.com/product/0636920032151.do) - from O'Reilly. Short and to-the-point. Uses native and bluebird.
* <b><code>&nbsp;&nbsp;&nbsp;738⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;220🍴</code></b> [Promise it won't hurt](https://github.com/stevekane/promise-it-wont-hurt)) - An interactive 🌎 [nodeschool](nodeschool.io/) workshop
* [ES6 Kata Promises](http://es6katas.org/) - Promises Katas : [Basics](http://tddbin.com/#?kata=es6/language/promise/basics)
* 🌎 [ES6 Promises in Depth](ponyfoo.com/articles/es6-promises-in-depth)
* [An Incremental Tutorial on Promises](http://www.sohamkamani.com/blog/2016/08/28/incremenal-tutorial-to-promises/) - An FAQ styled tutorial for beginners.

### Deep Dive
* <b><code>&nbsp;&nbsp;5125⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;137🍴</code></b> [Promise Fun](https://github.com/sindresorhus/promise-fun)) - @sindresorhus's notes, patterns, and solutions to common Promise problems
* 🌎 [You're Missing the Point of Promises](blog.domenic.me/youre-missing-the-point-of-promises/) - Promises are much more than callback aggregation, and that jQuery's implementation (prior to 3.0) isn't enough.
* 🌎 [We have a problem with promises](pouchdb.com/2015/05/18/we-have-a-problem-with-promises.html) - "Many of us are using promises without really understanding them."
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Promise anti-patterns](https://github.com/petkaantonov/bluebird/wiki/Promise-anti-patterns)) - Common misuses and how to avoid them.
* [Promise anti-patterns (2)](http://taoofcode.net/promise-anti-patterns/) - Another set of promises anti-patterns
* 🌎 [Promise Ponderings, (Anti-)Patterns, and Apologies](sdgluck.github.io/2015/08/24/promise-ponderings-patterns-apologies/) - Promise behaviour demonstrated and explained by common questions and their answers.
* [Javascript Promises...In Wicked Detail](http://www.mattgreer.org/articles/promises-in-wicked-detail/) - Recreate the promise implementation
* 🌎 [Writing Promise-Using Specifications](www.w3.org/2001/tag/doc/promises-guide) - "This document gives guidance on how to write specifications that create, accept, or manipulate promises"
* 🌎 [Async functions - making promises friendly](developers.google.com/web/fundamentals/getting-started/primers/async-functions)

### References
* 🌎 [Promises/A+ specification](promisesaplus.com/)
* [caniuse promises](http://caniuse.com/#feat=promises)
* <b><code>&nbsp;&nbsp;1257⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;93🍴</code></b> [Fates and States](https://github.com/domenic/promises-unwrapping/blob/master/docs/states-and-fates.md)) - Quick definitions of possible states.
* 🌎 [Promisees](bevacqua.github.io/promisees/) - Promise visualization playground for the adventurous.

## Promises/A+ Implementations (ES6/ES2015 compatible)

### Strict Implementations
These implement no more or less than the es6 spec. They make great polyfills and are exceptionally compatible with native promises.

* <b><code>&nbsp;&nbsp;&nbsp;138⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [pinkie](https://github.com/floatdrop/pinkie)) - Ponyfill. Node-oriented, but <b><code>&nbsp;14731⭐</code></b> <b><code>&nbsp;&nbsp;1197🍴</code></b> [browserifyable](https://github.com/substack/node-browserify)). *Extremely* small implementation.
* <b><code>&nbsp;&nbsp;&nbsp;717⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68🍴</code></b> [native-promise-only](https://github.com/getify/native-promise-only)) - Polyfill. Browser and node-compatible.
* <b><code>&nbsp;&nbsp;7289⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;589🍴</code></b> [es6-promise](https://github.com/stefanpenner/es6-promise)) - Opt-in polyfill. A strict-spec subset of rsvp.js.
* <b><code>&nbsp;&nbsp;&nbsp;741⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60🍴</code></b> [lie](https://github.com/calvinmetcalf/lie)) - Small, browserifyable with an opt-in polyfill.

### Implementations with extras
All of these provide more features than the language yet remain compatible. Node + Browsers for all.

* <b><code>&nbsp;20759⭐</code></b> <b><code>&nbsp;&nbsp;2326🍴</code></b> [bluebird](https://github.com/petkaantonov/bluebird)) - Fully featured, extremely performant. Long stack traces & generator/coroutine support.
* <b><code>&nbsp;&nbsp;&nbsp;278⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [creed](https://github.com/briancavalier/creed)) - Hyper performant & full featured like Bluebird, but FP-oriented. Coroutines, generators, promises, ES2015 iterables, & fantasy-land spec.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [rsvp.js](https://github.com/tildeio/rsvp.js/)) - Lightweight with a few extras. Compatible down to IE6!
* <b><code>&nbsp;15228⭐</code></b> <b><code>&nbsp;&nbsp;1187🍴</code></b> [Q](https://github.com/kriskowal/q)) - One of the original implementations. Long stack traces and other goodies.
* <b><code>&nbsp;&nbsp;2591⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;311🍴</code></b> [then/promise](https://github.com/then/promise)) - Small with `nodeify`, `denodify` and `done()` additions.
* <b><code>&nbsp;&nbsp;3431⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;390🍴</code></b> [when.js](https://github.com/cujojs/when)) - Packed with control flow, functional, and utility methods.


### Fallbacks
* 🌎 [native-or-bluebird](www.npmjs.com/package/native-or-bluebird) - Helps transition to completely native.
* <b><code>&nbsp;&nbsp;&nbsp;116⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [pinkie-promise](https://github.com/floatdrop/pinkie-promise)) - Use native, or fall back to `pinkie`. Great for node library authors.
* <b><code>&nbsp;&nbsp;&nbsp;181⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [any-promise](https://github.com/kevinbeaty/any-promise)) - Loads the first available implementation. Safe for browserify.

## Convenience Utilities
Native and strictly spec-compliant promises are awesome for compatibility, future-proofness, library authors, and browsers. However, libraries like bluebird patch goodies onto the `Promise` constructor and prototype. Solution? tiny modules of course!

### sindresorhus's many Promise utilities (<b><code>&nbsp;&nbsp;5125⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;137🍴</code></b> [see notes](https://github.com/sindresorhus/promise-fun)))
* <b><code>&nbsp;&nbsp;&nbsp;627⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [delay](https://github.com/sindresorhus/delay)) - Delay a promise a specified amount of time.
* <b><code>&nbsp;&nbsp;1514⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;70🍴</code></b> [pify](https://github.com/sindresorhus/pify)) - Promisify ("denodify") a callback-style function.
* <b><code>&nbsp;&nbsp;&nbsp;282⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [loud-rejection](https://github.com/sindresorhus/loud-rejection)) - Make unhandled promise rejections fail loudly instead of the default silent fail.
* <b><code>&nbsp;&nbsp;&nbsp;107⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [hard-rejection](https://github.com/sindresorhus/hard-rejection)) - Make unhandled promise rejections fail hard right away instead of the default silent fail
* <b><code>&nbsp;&nbsp;4134⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;198🍴</code></b> [p-queue](https://github.com/sindresorhus/p-queue)) - Promise queue with concurrency control
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [p-break](https://github.com/sindresorhus/p-break)) - Break out of a promise chain
* <b><code>&nbsp;&nbsp;&nbsp;285⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [p-lazy](https://github.com/sindresorhus/p-lazy)) - Create a lazy promise that defers execution until `.then()` or `.catch()` is called
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;84⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [p-defer](https://github.com/sindresorhus/p-defer)) - Create a deferred promise
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;63⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [p-if](https://github.com/sindresorhus/p-if)) - Conditional promise chains
* <b><code>&nbsp;&nbsp;&nbsp;134⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [p-tap](https://github.com/sindresorhus/p-tap)) - Tap into a promise chain without affecting its value or state
* <b><code>&nbsp;&nbsp;1481⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64🍴</code></b> [p-map](https://github.com/sindresorhus/p-map)) - Map over promises concurrently
* <b><code>&nbsp;&nbsp;&nbsp;344⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [p-all](https://github.com/sindresorhus/p-all)) - Run promise-returning & async functions concurrently with optional limited concurrency
* <b><code>&nbsp;&nbsp;2800⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;127🍴</code></b> [p-limit](https://github.com/sindresorhus/p-limit)) - Run multiple promise-returning & async functions with limited concurrency
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [p-times](https://github.com/sindresorhus/p-times)) - Run promise-returning & async functions a specific number of times concurrently
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [p-catch-if](https://github.com/sindresorhus/p-catch-if)) - Conditional promise catch handler
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;72⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [p-time](https://github.com/sindresorhus/p-time)) - Measure the time a promise takes to resolve
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [p-log](https://github.com/sindresorhus/p-log)) - Log the value/error of a promise
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;80⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [p-filter](https://github.com/sindresorhus/p-filter)) - Filter promises concurrently
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;94⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [p-settle](https://github.com/sindresorhus/p-settle)) - Settle promises concurrently and get their fulfillment value or rejection reason
* <b><code>&nbsp;&nbsp;&nbsp;437⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [p-memoize](https://github.com/sindresorhus/p-memoize)) - Memoize promise-returning & async functions
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [p-whilst](https://github.com/sindresorhus/p-whilst)) - Calls a function repeatedly while a condition returns true and then resolves the promise
* <b><code>&nbsp;&nbsp;&nbsp;512⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [p-throttle](https://github.com/sindresorhus/p-throttle)) - Throttle promise-returning & async functions
* <b><code>&nbsp;&nbsp;&nbsp;234⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [p-debounce](https://github.com/sindresorhus/p-debounce)) - Debounce promise-returning & async functions
* <b><code>&nbsp;&nbsp;&nbsp;990⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;77🍴</code></b> [p-retry](https://github.com/sindresorhus/p-retry)) - Retry a promise-returning or async function
* <b><code>&nbsp;&nbsp;&nbsp;166⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [p-wait-for](https://github.com/sindresorhus/p-wait-for)) - Wait for a condition to be true
* <b><code>&nbsp;&nbsp;&nbsp;299⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [p-timeout](https://github.com/sindresorhus/p-timeout)) - Timeout a promise after a specified amount of time
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [p-race](https://github.com/sindresorhus/p-race)) - A better `Promise.race()`
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [p-try](https://github.com/sindresorhus/p-try)) - `Promise#try()` ponyfill - Starts a promise chain
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [p-finally](https://github.com/sindresorhus/p-finally)) - `Promise#finally()` ponyfill - Invoked when the promise is settled regardless of outcome
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [p-any](https://github.com/sindresorhus/p-any)) - Wait for any promise to be fulfilled
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [p-some](https://github.com/sindresorhus/p-some)) - Wait for a specified number of promises to be fulfilled
* <b><code>&nbsp;&nbsp;&nbsp;127⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [p-pipe](https://github.com/sindresorhus/p-pipe)) - Compose promise-returning & async functions into a reusable pipeline
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [p-each-series](https://github.com/sindresorhus/p-each-series)) - Iterate over promises serially
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [p-map-series](https://github.com/sindresorhus/p-map-series)) - Map over promises serially
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [p-reduce](https://github.com/sindresorhus/p-reduce)) - Reduce a list of values using promises into a promise for a value
* <b><code>&nbsp;&nbsp;&nbsp;200⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [p-props](https://github.com/sindresorhus/p-props)) - Like `Promise.all()` but for `Map` and `Object`

### Others
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [promise-method](https://github.com/wbinnssmith/promise-method)) - Standalone `bluebird.method`. Turn a synchronously-returning method into a promise-returning one.
* <b><code>&nbsp;&nbsp;&nbsp;282⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [is-promise](https://github.com/then/is-promise)) - Determine if something looks like a Promise.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [sprom](https://github.com/then/sprom)) - Resolve when a stream ends. Optional buffering (be careful with this!)
* <b><code>&nbsp;&nbsp;1628⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;72🍴</code></b> [task.js](https://github.com/mozilla/task.js)) - Write async functions in a blocking style using promises and generators. Like `bluebird.coroutine`.
* <b><code>&nbsp;11873⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;784🍴</code></b> [co](https://github.com/tj/co)) - Like `task.js` and `bluebird.coroutine`, but supports thunks too.
* 🌎 [lie-fs](www.npmjs.com/package/lie-fs) - Promise wrappers for Node's FS API.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [promise-do-until](https://github.com/busterc/promise-do-until)) - Calls a function repeatedly until a condition returns true and then resolves the promise.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [promise-do-whilst](https://github.com/busterc/promise-do-whilst)) - Calls a function repeatedly while a condition returns true and then resolves the promise.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [promise-semaphore](https://github.com/samccone/promise-semaphore)) - Push a set of work to be done in a configurable serial fashion
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [promise-nodeify](https://github.com/kevinoid/promise-nodeify)) - Standalone `nodeify` method which calls a Node-style callback on resolution or rejection.

## License
Licensed under the 🌎 [Creative Commons CC0 License](creativecommons.org/publicdomain/zero/1.0/).

## Source
<b><code>&nbsp;&nbsp;1699⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;123🍴</code></b> [wbinnssmith/awesome-promises](https://github.com/wbinnssmith/awesome-promises))