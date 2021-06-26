Miscellaneous articles, blog posts, etc that have been helpful for choosing & 
conceptually understanding particular toolchains, or for navigating dependency 
hell.

## Makefiles & build systems

- [Makefiles for Go developers | TutorialEdge](https://tutorialedge.net/golang/makefiles-for-go-developers/)
- [explanation/comparison of JS bundlers (written 2018) | AJ Meyghani](https://medium.com/@ajmeyghani/javascript-bundlers-a-comparison-e63f01f2a364); discusses how JS modules & module loaders work, and compares bundle size & build time for Webpack, Rollup, Parcel, Browserify, Fusebox.

## Data analysis

- [Quick reference for data analysis with Python | Linna Li](https://linnali.com/posts/quick_reference_for_data_analysis_with_python/)
- [10 minutes to pandas](https://pandas.pydata.org/pandas-docs/stable/user_guide/10min.html)

## WebGL & WebGPU

- [xemantic's favorite WebGL abstractions](https://xemantic.github.io/shader-web-background/#alternatives)
- [dmnsgn's list of WebGL/WebGPU frameworks](https://gist.github.com/dmnsgn/76878ba6903cf15789b712464875cfdc)
- [WebGLFundamentals article on GLSL uniform types](https://webglfundamentals.org/webgl/lessons/webgl-shaders-and-glsl.html)


# Wrangling data

- [`jq` cheat sheet](https://gist.github.com/olih/f7437fb6962fb3ee9fe95bda8d2c8fa4)


# Specific languages/frameworks

## Webassembly

- [Lin Clark's intro to WASM](https://hacks.mozilla.org/2017/02/a-cartoon-intro-to-webassembly/)
- [languages with WASM build support](https://github.com/appcypher/awesome-wasm-langs)
	- [golang -> WASM experimental port](https://github.com/golang/go/wiki/WebAssembly)
- [TinyGo](https://tinygo.org/): a subset of Golang designed to be run on embedded systems or in WebAssembly

## Clojure

Released in 2007. An expressive functional language that runs on the JVM and has built-in concurrency and immutable data structures. Was specifically created to address frustrations with the weaknesses of OOP (object-oriented programming) in dealing with concurrent programming.

- [_The Joy of Clojure_](https://www.manning.com/books/the-joy-of-clojure-second-edition), Michael Fogus & Chris Hauser, 2014. A Socratic exploration of the reasoning behind Clojure's design paradigms and idiomatic usage, and how to think in Clojure.
- [Leiningen](http://leiningen.org/), invoked as `lein`, is a commonly used Clojure project manager that helps you manage dependencies, run tests, package your project, etc.
- [`lein` quickstart by BraveClojure](https://www.braveclojure.com/getting-started/), with bonus explanation of how Clojure utilizes the JVM
- [ClojureScript Koans](http://clojurescriptkoans.com/): interactive website that poses simple expressions to which you write solutions to learn how to think in the Clojure paradigm.

## Python 3

### Asynchronous programming

#### `asyncio`
- [8-part video series](https://www.youtube.com/watch?v=Xbl7XjFYsN4&list=PLhNSoGM2ik6SIkVGXWBwerucXjgP1rHmB) on how asyncio works, stepping through the event loop, using coroutines, the inner workings of coroutines. Also includes a prelude on the history and context of its design.

#### `twisted`
- https://www.infoq.com/presentations/Twisted-Python/
