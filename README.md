# awesome-haskell

A curated list of awesome Haskell frameworks, libraries and software.

* Learning and Reference
	* [Tutorials and Books](#tutorials-and-books)
	* [Examples and Exercises](#examples-and-exercises)
	* [Awesome Lists and Collections](#awesome-lists-and-collections)
* Language and Tooling
	* [Compilers and Interpreters](#compilers-and-interpreters)
	* [Build Systems](#build-systems)
	* [Package Management](#package-management)
	* [Linters and Formatters](#linters-and-formatters)
	* [Debugging and Profiling](#debugging-and-profiling)
	* [Editor and IDE Support](#editor-and-ide-support)
* Web
	* [Web Frameworks](#web-frameworks)
	* [HTTP and Networking Clients](#http-and-networking-clients)
	* [API and GraphQL](#api-and-graphql)
	* [Frontend and UI Components](#frontend-and-ui-components)
* Data and Storage
	* [Databases](#databases)
	* [Database Clients and ORMs](#database-clients-and-orms)
	* [Serialization and Formats](#serialization-and-formats)
* Machine Learning and AI
	* [Machine Learning Frameworks](#machine-learning-frameworks)
	* [Data Science and Analytics](#data-science-and-analytics)
* Networking and Distributed
	* [Networking](#networking)
	* [RPC and Messaging](#rpc-and-messaging)
	* [Distributed Systems](#distributed-systems)
	* [Cloud and Infrastructure](#cloud-and-infrastructure)
	* [Monitoring and Observability](#monitoring-and-observability)
* User Interface
	* [GUI Toolkits](#gui-toolkits)
	* [Terminal and Console UI](#terminal-and-console-ui)
	* [Applications and End User Tools](#applications-and-end-user-tools)
* Graphics and Media
	* [Graphics and Rendering](#graphics-and-rendering)
	* [Game Development](#game-development)
	* [Audio](#audio)
* Concurrency and Performance
	* [Concurrency and Parallelism](#concurrency-and-parallelism)
	* [Performance and Optimization](#performance-and-optimization)
* Testing and Quality
	* [Testing](#testing)
* Utilities
	* [Command Line Tools](#command-line-tools)
	* [Logging and Configuration](#logging-and-configuration)
	* [Text Processing](#text-processing)
	* [Files and Operating System](#files-and-operating-system)
	* [Automation and Scripting](#automation-and-scripting)
	* [General Purpose Libraries](#general-purpose-libraries)
* Science and Math
	* [Mathematics](#mathematics)
	* [Scientific Computing](#scientific-computing)
	* [Formal Methods and Proofs](#formal-methods-and-proofs)
* [Other](#other)

## Learning and Reference

### Tutorials and Books

* [sdiehl/write-you-a-haskell](https://github.com/sdiehl/write-you-a-haskell) - Building a modern functional compiler from first principles. (http://dev.stephendiehl.com/fun/)
* [caiorss/Functional-Programming](https://github.com/caiorss/Functional-Programming) - Functional Programming concepts, examples and patterns illustrated in Haskell, Ocaml and Python
* [sdiehl/wiwinwlh](https://github.com/sdiehl/wiwinwlh) - What I Wish I Knew When Learning Haskell
* [huangzworks/real-world-haskell-cn](https://github.com/huangzworks/real-world-haskell-cn) - 《Real World Haskell》中文翻译项目
* [haskell-beginners-2022/course-plan](https://github.com/haskell-beginners-2022/course-plan) - 📜 Haskell course info, plan, video lectures, slides
* [google/haskell-trainings](https://github.com/google/haskell-trainings) - Haskell 101 and 102: slides and codelabs *(archived)*
* [quchen/articles](https://github.com/quchen/articles) - Miscellaneous articles. The readme is the table of contents.
* [google/codeworld](https://github.com/google/codeworld) - Educational computer programming environment using Haskell
* [graninas/software-design-in-haskell](https://github.com/graninas/software-design-in-haskell) - Software Design in Haskell. A structured set of materials. How to build real-world applications in Haskell.
* [sdiehl/kaleidoscope](https://github.com/sdiehl/kaleidoscope) - Haskell LLVM JIT Compiler Tutorial
* [kowainik/learn4haskell](https://github.com/kowainik/learn4haskell) - 👩‍🏫 👨‍🏫 Learn Haskell basics in 4 pull requests
* [thma/LtuPatternFactory](https://github.com/thma/LtuPatternFactory) - Lambda the ultimate Pattern Factory: FP, Haskell, Typeclassopedia vs Software Design Patterns
* [bos/stanford-cs240h](https://github.com/bos/stanford-cs240h) - Course materials for Stanford CS240h, "Functional Systems in Haskell"
* [qfpl/applied-fp-course](https://github.com/qfpl/applied-fp-course) - Applied Functional Programming Course - Move from exercises to a working app!
* [alpacaaa/zero-bs-haskell](https://github.com/alpacaaa/zero-bs-haskell) - Learn Haskell, with tiny lessons.
* [quchen/stgi](https://github.com/quchen/stgi) - A user-centric visual STG implementation to help understand GHC/Haskell's execution model.
* [JakeWheat/intro_to_parsing](https://github.com/JakeWheat/intro_to_parsing) - Introduction to parsing with Haskell and Parsec
* [thma/WhyHaskellMatters](https://github.com/thma/WhyHaskellMatters) - In this article I try to explain why Haskell keeps being such an important language by presenting some of its most important and distinguishing features and detailing them with working code examples. The presentation aims to be self-contained and does not require any previous knowledge of the language.
* [winterland1989/magic-haskell](https://github.com/winterland1989/magic-haskell) - 魔力haskell官方网站
* [byorgey/haskell-course](https://github.com/byorgey/haskell-course) - Introductory Haskell course materials (originally CIS 194 @ UPenn)
* [anton-k/ru-haskell-book](https://github.com/anton-k/ru-haskell-book) - учебник по Haskell
* [denisshevchenko/ohaskell.guide](https://github.com/denisshevchenko/ohaskell.guide) - Ваша первая книга о языке Haskell
* [m4dc4p/cheatsheet](https://github.com/m4dc4p/cheatsheet) - A Haskell CheatSheet in PDF and literate source formats.
* [typeclasses/haskell-phrasebook](https://github.com/typeclasses/haskell-phrasebook) - The Haskell Phrasebook: a quick intro to Haskell via small annotated example programs
* [simonmar/par-tutorial](https://github.com/simonmar/par-tutorial) - A tutorial on Parallel and Concurrent Haskell
* [michaelochurch/summer-2015-haskell-class](https://github.com/michaelochurch/summer-2015-haskell-class) - Summer 2015 Haskell Class
* [commercialhaskell/haskelldocumentation](https://github.com/commercialhaskell/haskelldocumentation) - Repository for collaborative Haskell documentation
* [NorfairKing/haskell-dangerous-functions](https://github.com/NorfairKing/haskell-dangerous-functions) - Documentation about Haskell's dangerous functions and a hlint config file to warn about them
* [MondayMorningHaskell/haskellings](https://github.com/MondayMorningHaskell/haskellings) - An automated tutorial to teach you about Haskell!
* [w7cook/AoPL](https://github.com/w7cook/AoPL) - A book on programming languages, using Haskell
* [effectfully/sketches](https://github.com/effectfully/sketches) - A Haskell blog
* [graninas/hierarchical-free-monads-the-most-developed-approach-in-haskell](https://github.com/graninas/hierarchical-free-monads-the-most-developed-approach-in-haskell) - Big article about Hierarchical Free Monads, the most developed approach to build real software in Haskell
* [madjestic/Haskell-OpenGL-Tutorial](https://github.com/madjestic/Haskell-OpenGL-Tutorial) - an attempt to create a concise modern Haskell OpenGL boilerplate with basic IO
* [nanotech/swift-haskell-tutorial](https://github.com/nanotech/swift-haskell-tutorial) - Integrating Haskell with Swift Mac Apps
* [hansroland/reflex-dom-inbits](https://github.com/hansroland/reflex-dom-inbits) - A tutorial for reflex-dom with small code bits
* [mzero/haskell-amuse-bouche](https://github.com/mzero/haskell-amuse-bouche) - A short technical talk about some fun things in Haskell
* [haskellfoundation/error-message-index](https://github.com/haskellfoundation/error-message-index) - A community-driven collection of documentation for Haskell error messages and warnings
* [stepchowfun/effects](https://github.com/stepchowfun/effects) - A brief exploration of the various approaches to modeling side effects in a purely functional programming language. *(archived)*
* [lettier/parsing-with-haskell-parser-combinators](https://github.com/lettier/parsing-with-haskell-parser-combinators) - 🔍 A step-by-step guide to parsing using Haskell parser combinators.
* [haskell-jp/makeMistakesToLearnHaskell](https://github.com/haskell-jp/makeMistakesToLearnHaskell) - Make Mistakes to Learn Haskell - 失敗しながら学ぶHaskell入門
* [llvm-hs/llvm-hs-kaleidoscope](https://github.com/llvm-hs/llvm-hs-kaleidoscope) - Kaleidoscope Tutorial using llvm-hs
* [algas/haskell-servant-cookbook](https://github.com/algas/haskell-servant-cookbook) - Haskell Servant Cookbook
* [ifesdjeen/haskell-ffi-tutorial](https://github.com/ifesdjeen/haskell-ffi-tutorial) - A (missing) Haskell FFI tutorial: how to work with nested Structs and do bi-directional C<->Haskell interop
* [Gabriella439/Haskell-Lens-Tutorial-Library](https://github.com/Gabriella439/Haskell-Lens-Tutorial-Library) - The missing tutorial module for the lens library
* [HaskellZhangSong/Introduction_to_Haskell_2ed_source](https://github.com/HaskellZhangSong/Introduction_to_Haskell_2ed_source) - 这是Haskell函数式编程入门第2版的源码
* [felixmulder/haskell-in-production](https://github.com/felixmulder/haskell-in-production) - Companion to the Haskell in Production series
* [stevana/property-based-testing-stateful-systems-tutorial](https://github.com/stevana/property-based-testing-stateful-systems-tutorial) - A tutorial about how to apply property-based testing to stateful systems.
* [jwiegley/putting-lenses-to-work](https://github.com/jwiegley/putting-lenses-to-work) - A presentation for BayHac 2017 on how I uses lenses at work
* [zhangchiqing/beginner-friendly-haskell-for-web-development](https://github.com/zhangchiqing/beginner-friendly-haskell-for-web-development) - A book about real world web development in beginner friendly Haskell
* [iand675/haskell-checklist](https://github.com/iand675/haskell-checklist) - Preflight checklist for Haskell code. Aspire to greatness!
* [HaskellZhangSong/Introduction_to_Haskell](https://github.com/HaskellZhangSong/Introduction_to_Haskell) - This is source code of my book.
* [HeinrichApfelmus/frp-guides](https://github.com/HeinrichApfelmus/frp-guides) - A collection of tutorials, guidelines, examples, patterns and half-baked ideas on functional reactive programming (FRP).
* [pietervdvn/Haskell](https://github.com/pietervdvn/Haskell) - Introduction to haskell
* [chrisdone-archive/tryhaskell](https://github.com/chrisdone-archive/tryhaskell) - Try Haskell

### Examples and Exercises

* [i-am-tom/haskell-exercises](https://github.com/i-am-tom/haskell-exercises) - A little course to learn about some of the more obscure GHC extensions.
* [BinRoot/Haskell-Data-Analysis-Cookbook](https://github.com/BinRoot/Haskell-Data-Analysis-Cookbook) - Accompanying Source Code for the Haskell Data Analysis Cookbook
* [exercism/haskell](https://github.com/exercism/haskell) - Exercism exercises in Haskell.
* [raviksharma/bartosz-basics-of-haskell](https://github.com/raviksharma/bartosz-basics-of-haskell) - Code and exercises from Bartosz Milewski's Basics of Haskell Tutorial
* [lsmor/snake-fury](https://github.com/lsmor/snake-fury) - a challenge for Haskell beginners
* [simonmar/parconc-examples](https://github.com/simonmar/parconc-examples) - Sample code to accompany the book "Parallel and Concurrent Programming in Haskell"
* [chris-taylor/aima-haskell](https://github.com/chris-taylor/aima-haskell) - Algorithms from AIMA in Haskell
* [Holmusk/three-layer](https://github.com/Holmusk/three-layer) - :three: :cake: Architecture of the Haskell web applications
* [sweirich/dth](https://github.com/sweirich/dth) - Examples of Dependently-typed programs in Haskell
* [HaskVan/HaskellKoans](https://github.com/HaskVan/HaskellKoans) - Haskell Koans for the Vancouver's Haskell UnMeetup
* [haskell-beginners-2022/exercises](https://github.com/haskell-beginners-2022/exercises) - 💻 Exercises for the Haskell Beginners 2022 course
* [bravit/hid-examples](https://github.com/bravit/hid-examples) - Examples to accompany the book "Haskell in Depth"
* [k-bx/owlcloud](https://github.com/k-bx/owlcloud) - OwnCloud for owls done via The Microservice Architecture
* [polyvariadic/haskell-challenges](https://github.com/polyvariadic/haskell-challenges) - Code challenges to solve with Haskell
* [eckyputrady/haskell-scotty-realworld-example-app](https://github.com/eckyputrady/haskell-scotty-realworld-example-app) - Exemplary real world backend API built with Haskell/Scotty https://realworld.io
* [tsoding/haskell-json](https://github.com/tsoding/haskell-json) - Source Code for JSON Parser Video
* [derekmcloughlin/pearls](https://github.com/derekmcloughlin/pearls) - Pearls of Functional Algorithm Design by Richard Bird - Haskell Code
* [thma/PolysemyCleanArchitecture](https://github.com/thma/PolysemyCleanArchitecture) - Showcasing how the Polysemy library can be used to implement a REST application conforming to the guidelines of the Clean Architecture model.
* [g-ford/cradle](https://github.com/g-ford/cradle) - Let's Build a Compiler (in Haskell)
* [fbsamples/ghc-hotswap](https://github.com/fbsamples/ghc-hotswap) - Example code for how we swap compiled code within a running Haskell process. *(archived)*
* [kazu-yamamoto/unit-test-example](https://github.com/kazu-yamamoto/unit-test-example) - Unit test example for Haskell
* [tzemanovic/haskell-yesod-realworld-example-app](https://github.com/tzemanovic/haskell-yesod-realworld-example-app) - Exemplary real world application built with Haskell + Yesod
* [joshcough/HaskellStarter](https://github.com/joshcough/HaskellStarter) - A project that demonstrates getting up and running with Haskell.
* [opqdonut/haskell-exercises](https://github.com/opqdonut/haskell-exercises) - Haskell exercises with automatic tests
* [jaspervdj/fugacious](https://github.com/jaspervdj/fugacious) - An example Haskell web application
* [palf/haskell-sdl2-examples](https://github.com/palf/haskell-sdl2-examples) - SDL2 tutorial code in Haskell
* [tsoding/haskell-music](https://github.com/tsoding/haskell-music) - Source Code from "Making Music with Haskell" video
* [ChrisPenner/wc](https://github.com/ChrisPenner/wc) - Beating unix `wc` in Haskell
* [tfausak/haskeleton](https://github.com/tfausak/haskeleton) - :skull: A Haskell package skeleton. *(archived)*
* [aisamanra/rust-haskell-ffi](https://github.com/aisamanra/rust-haskell-ffi) - Toy example of calling Rust from Haskell
* [syocy/a-tour-of-go-in-haskell](https://github.com/syocy/a-tour-of-go-in-haskell) - Write "Concurrency" section of "A Tour of Go" in Haskell
* [haskelllive/haskelllive](https://github.com/haskelllive/haskelllive) - Source code of the Haskell Live episodes.
* [kazu-yamamoto/recursion-drill](https://github.com/kazu-yamamoto/recursion-drill) - Drill to study recursive programming in Haskell
* [dandoh/web-haskell-graphql-postgres-boilerplate](https://github.com/dandoh/web-haskell-graphql-postgres-boilerplate) - Modern webserver in Haskell: Graphql + Postgresql + Authentication + DB migration + Dotenv and more
* [sweirich/challenge](https://github.com/sweirich/challenge) - Strongly-typed System F in Haskell
* [1HaskellADay/1HAD](https://github.com/1HaskellADay/1HAD) - 1 Haskell A Day exercises
* [well-typed/unfolder](https://github.com/well-typed/unfolder) - Repository with code snippets that accompany episodes of The Haskell Unfolder
* [mvaldesdeleon/haskell-book](https://github.com/mvaldesdeleon/haskell-book) - Exercises and code from "Haskell Programming from First Principles"
* [hspec/hspec-example](https://github.com/hspec/hspec-example) - A Haskell/Hspec skeleton project
* [pasunboneleve/haskellbook](https://github.com/pasunboneleve/haskellbook) - Exercise solutions for haskellbook.com
* [dwayne/haskell-programming](https://github.com/dwayne/haskell-programming) - My notes and solutions to exercises for the book "Haskell Programming from first principles".
* [cyga/real-world-haskell](https://github.com/cyga/real-world-haskell) - parser for code samples from the book "real world haskell" (http://book.realworldhaskell.org/read/)
* [dnikolovv/practical-haskell](https://github.com/dnikolovv/practical-haskell) - A collection of Practical Haskell bits.
* [mark-watson/haskell_tutorial_cookbook_examples](https://github.com/mark-watson/haskell_tutorial_cookbook_examples) - Code samples for my book "Haskell Tutorial and Cookbook"
* [reflex-frp/reflex-examples](https://github.com/reflex-frp/reflex-examples) - See Reflex FRP in action with tinker-friendly code samples you can run yourself.
* [crabmusket/haskell-simple-concurrency](https://github.com/crabmusket/haskell-simple-concurrency) - Small examples of concurrency in Haskell.
* [dstcruz/Write-Yourself-A-Scheme-In-48-Hours](https://github.com/dstcruz/Write-Yourself-A-Scheme-In-48-Hours) - My solutions to the popular Haskell tutorial
* [sdiehl/zurihac-crypto](https://github.com/sdiehl/zurihac-crypto) - Small minimal examples of modern cryptographic techniques in Haskell
* [llvm-hs/llvm-hs-examples](https://github.com/llvm-hs/llvm-hs-examples) - Examples for Haskell bindings to LLVM
* [ryukinix/discrete-mathematics](https://github.com/ryukinix/discrete-mathematics) - A computational way to study discrete mathematics using Haskell
* [i-am-tom/learn-me-a-haskell](https://github.com/i-am-tom/learn-me-a-haskell) - Trying to get back all the stuff I had in JavaScript.
* [politrons/Dive_into_Haskell](https://github.com/politrons/Dive_into_Haskell) - Dive into Haskell: Examples of all features of this Pure Functional programing language
* [wyager/Example-Distributed-App](https://github.com/wyager/Example-Distributed-App) - An example distributed systems application in Haskell using Cloud Haskell
* [ocharles/effect-zoo](https://github.com/ocharles/effect-zoo) - Comparing Haskell effect systems for ergonomics and speed
* [basvandijk/nixtodo](https://github.com/basvandijk/nixtodo) - A demonstration on how to use Nix to build, test and deploy a Haskell application
* [gvolpe/shopping-cart-haskell](https://github.com/gvolpe/shopping-cart-haskell) - :gem: Haskell version of the Shopping Cart application developed in the book "Practical FP in Scala: A hands-on approach"
* [serras/lambdaconf-2015-web](https://github.com/serras/lambdaconf-2015-web) - Projects for LambdaConf 2015 Haskell web workshop
* [nh2/haskell-from-python](https://github.com/nh2/haskell-from-python) - Example how to call Haskell from Python easily (using ctypes.cdll.LoadLibrary)

### Awesome Lists and Collections

* [krispo/awesome-haskell](https://github.com/krispo/awesome-haskell) - A collection of awesome Haskell links, frameworks, libraries and software. Inspired by awesome projects line.
* [hzlmn/haskell-must-watch](https://github.com/hzlmn/haskell-must-watch) - Huge list of videos, talks, courses for Haskell programming language.
* [pushcx/hpffp-resources](https://github.com/pushcx/hpffp-resources) - Haskell Programming From First Principles - Follow-up Resources
* [lotz84/haskell](https://github.com/lotz84/haskell) - A curated list of awesome things related to Haskell. *(archived)*
* [willbasky/Awesome-list-of-Haskell-mentors](https://github.com/willbasky/Awesome-list-of-Haskell-mentors) - An amazing list of Haskell developers who would like to mentor beginner-contributors in open source projects.
* [keera-studios/haskell-game-programming](https://github.com/keera-studios/haskell-game-programming) - A central repository of Haskell Game Programming resources, put together by Keera Studios
* [soupi/rfc](https://github.com/soupi/rfc) - My slides and compilation of resources.
* [haskellweekly/haskellweekly](https://github.com/haskellweekly/haskellweekly) - Publishes curated news about the Haskell programming language.
* [sigrlami/haskellcosm](https://github.com/sigrlami/haskellcosm) - Collecting information about Haskell ecosystem - companies, communities, media, etc.
* [katychuang/getting-started-with-haskell](https://github.com/katychuang/getting-started-with-haskell) - notes on where to find Haskell tutorials and tips to complete them
* [JeanHuguesdeRaigniac/effects-landscape](https://github.com/JeanHuguesdeRaigniac/effects-landscape) - Effects libraries in Haskell
* [chiroptical/declarative-programming-streams](https://github.com/chiroptical/declarative-programming-streams) - Active streaming declarative programmers. See who's online at the following URL:

## Language and Tooling

### Compilers and Interpreters

* [purescript/purescript](https://github.com/purescript/purescript) - A strongly-typed language that compiles to JavaScript
* [unisonweb/unison](https://github.com/unisonweb/unison) - A friendly programming language from the future
* [koka-lang/koka](https://github.com/koka-lang/koka) - Koka language compiler and interpreter
* [ghc/ghc](https://github.com/ghc/ghc) - Mirror of the Glasgow Haskell Compiler. Please submit issues and patches to GHC's Gitlab instance (https://gitlab.haskell.org/ghc/ghc). First time contributors are encouraged to get started with the newcomers info (https://gitlab.haskell.org/ghc/ghc/wikis/contributing).
* [typelead/eta](https://github.com/typelead/eta) - The Eta Programming Language, a dialect of Haskell on the JVM
* [ghcjs/ghcjs](https://github.com/ghcjs/ghcjs) - Haskell to JavaScript compiler, based on GHC
* [tweag/asterius](https://github.com/tweag/asterius) - DEPRECATED in favor of ghc wasm backend, see https://www.tweag.io/blog/2022-11-22-wasm-backend-merged-in-ghc *(archived)*
* [google-research/dex-lang](https://github.com/google-research/dex-lang) - Research language for array processing in the Haskell/ML family
* [clash-lang/clash-compiler](https://github.com/clash-lang/clash-compiler) - Haskell to VHDL/Verilog/SystemVerilog compiler
* [valderman/haste-compiler](https://github.com/valderman/haste-compiler) - A GHC-based Haskell to JavaScript compiler
* [faylang/fay](https://github.com/faylang/fay) - A proper subset of Haskell that compiles to JavaScript
* [evincarofautumn/kitten](https://github.com/evincarofautumn/kitten) - A statically typed concatenative systems programming language.
* [grin-compiler/grin](https://github.com/grin-compiler/grin) - GRIN is a compiler back-end for lazy and strict functional languages with whole program optimization support.
* [augustss/MicroHs](https://github.com/augustss/MicroHs) - Haskell implemented with combinators
* [mattgreen/hython](https://github.com/mattgreen/hython) - Haskell-powered Python 3 interpreter
* [anoma/juvix](https://github.com/anoma/juvix) - A language for intent-centric and declarative decentralised applications
* [ehatti/peridot](https://github.com/ehatti/peridot) - A fast functional language based on two level type theory *(archived)*
* [Gabriella439/Haskell-Morte-Library](https://github.com/Gabriella439/Haskell-Morte-Library) - A bare-bones calculus-of-constructions
* [amuletml/amulet](https://github.com/amuletml/amulet) - An ML-like functional programming language *(archived)*
* [neohaskell/NeoHaskell](https://github.com/neohaskell/NeoHaskell) - ⏩ NeoHaskell is a dialect of Haskell that is focused on newcomer-friendliness and productivity.
* [litxio/ptghci](https://github.com/litxio/ptghci) - High-powered REPL for Haskell, inspired by IPython
* [purenix-org/purenix](https://github.com/purenix-org/purenix) - Nix backend for PureScript. Transpile PureScript code to Nix.
* [haskell/alex](https://github.com/haskell/alex) - A lexical analyser generator for Haskell
* [haskell/happy](https://github.com/haskell/happy) - The Happy parser generator for Haskell
* [justinethier/husk-scheme](https://github.com/justinethier/husk-scheme) - A full implementation of the Scheme programming language for the Haskell Platform.
* [haskell-hint/hint](https://github.com/haskell-hint/hint) - Runtime Haskell interpreter
* [Mesabloo/diagnose](https://github.com/Mesabloo/diagnose) - A simple library for reporting compiler/interpreter errors
* [seliopou/typo](https://github.com/seliopou/typo) - A programming language that runs in Haskell's type system.
* [jyh1/mmaclone](https://github.com/jyh1/mmaclone) - A simple Wolfram Language clone in Haskell
* [blynn/compiler](https://github.com/blynn/compiler) - The adventures of a Haskell compiler
* [bijoutrouvaille/fireward](https://github.com/bijoutrouvaille/fireward) - A concise and readable language for Firestore security rules, similar to Firebase Bolt.
* [luc-tielen/eclair-lang](https://github.com/luc-tielen/eclair-lang) - A minimal, fast Datalog implementation in Haskell that compiles to LLVM IR
* [chrisdone-archive/duet](https://github.com/chrisdone-archive/duet) - A tiny language, a subset of Haskell aimed at aiding teachers teach Haskell *(archived)*
* [axellang/axel](https://github.com/axellang/axel) - Haskell + Lisp
* [david-christiansen/pie-hs](https://github.com/david-christiansen/pie-hs) - An implementation of Pie in Haskell
* [haskell/c2hs](https://github.com/haskell/c2hs) - c2hs is a pre-processor for Haskell FFI bindings to C libraries
* [agda/agda2hs](https://github.com/agda/agda2hs) - Compiling Agda code to readable Haskell
* [haskell-suite/haskell-src-exts](https://github.com/haskell-suite/haskell-src-exts) - Manipulating Haskell source: abstract syntax, lexer, parser, and pretty-printer
* [lemmih/lhc](https://github.com/lemmih/lhc) - The LLVM LHC Haskell Optimization System
* [mikeizbicki/HerbiePlugin](https://github.com/mikeizbicki/HerbiePlugin) - GHC plugin that improves Haskell code's numerical stability
* [ucsd-progsys/elsa](https://github.com/ucsd-progsys/elsa) - Elsa is a lambda calculus evaluator
* [sdiehl/tinyjit](https://github.com/sdiehl/tinyjit) - Haskell JIT
* [finkel-lang/finkel](https://github.com/finkel-lang/finkel) - Haskell in S-expression
* [tree-sitter/haskell-tree-sitter](https://github.com/tree-sitter/haskell-tree-sitter) - Haskell bindings for tree-sitter
* [kofigumbs/codec-beam](https://github.com/kofigumbs/codec-beam) - Generate Erlang VM byte code from Haskell
* [dfinity-side-projects/dhc](https://github.com/dfinity-side-projects/dhc) - Compiles Haskell to WebAssembly
* [mthom/shentong](https://github.com/mthom/shentong) - A Haskell implementation of the Shen programming language.
* [bollu/tiny-optimising-compiler](https://github.com/bollu/tiny-optimising-compiler) - A tiny *optimising* compiler for an imperative programming language written in haskell
* [radian-software/kalyn](https://github.com/radian-software/kalyn) - ⚗️ Self-hosting compiler from a Haskell-like Lisp directly to x86-64, from scratch.
* [ekmett/coda](https://github.com/ekmett/coda) - A language experiment -- irc.freenode.net ##coda
* [quintenkasteel/language-javascript](https://github.com/quintenkasteel/language-javascript) - Parser for JavaScript, in Haskell
* [cu1ch3n/type-inference-zoo](https://github.com/cu1ch3n/type-inference-zoo) - 🦖 Implementations of various type inference algorithms. The new project is now at https://github.com/cu1ch3n/type-inference-zoo-frontend.
* [leepike/Copilot](https://github.com/leepike/Copilot) - A (Haskell DSL) stream language for generating hard real-time C code.
* [SPY/haskell-wasm](https://github.com/SPY/haskell-wasm) - Haskell WebAssembly Toolkit
* [augustss/djinn](https://github.com/augustss/djinn) - Generate Haskell code from a type
* [mchakravarty/language-c-inline](https://github.com/mchakravarty/language-c-inline) - Inline C & Objective-C in Haskell
* [wavewave/fficxx](https://github.com/wavewave/fficxx) - Haskell-C++ Foreign Function Interface Generator
* [grin-compiler/ghc-grin](https://github.com/grin-compiler/ghc-grin) - GRIN backend for GHC
* [hslua/hslua](https://github.com/hslua/hslua) - Haskell bindings to Lua, an embeddable scripting language.
* [ajhc/ajhc](https://github.com/ajhc/ajhc) - A fork of jhc. And also a Haskell compiler.
* [tweag/inline-js](https://github.com/tweag/inline-js) - Call JavaScript from Haskell, and vice versa!
* [bscarlet/llvm-general](https://github.com/bscarlet/llvm-general) - Rich LLVM bindings for Haskell (with transfer of LLVM IR to and from C++, detailed compilation pass control, etc.)
* [ollef/Bidirectional](https://github.com/ollef/Bidirectional) - Haskell implementation of Dunfield and Krishnaswami's "Complete and easy bidirectional typechecking for higher-rank polymorphism"
* [ndmitchell/record-dot-preprocessor](https://github.com/ndmitchell/record-dot-preprocessor) - A preprocessor for a Haskell record syntax using dot
* [google/mlir-hs](https://github.com/google/mlir-hs) - Haskell bindings for MLIR
* [cronokirby/haskell-in-haskell](https://github.com/cronokirby/haskell-in-haskell) - Trying to write an understandable implementation of Haskell, in Haskell
* [sam46/Paskell](https://github.com/sam46/Paskell) - A Pascal to LLVM compiler in Haskell
* [paf31/dovetail](https://github.com/paf31/dovetail) - A PureScript interpreter in Haskell
* [grin-compiler/ghc-whole-program-compiler-project](https://github.com/grin-compiler/ghc-whole-program-compiler-project) - GHC Whole Program Compiler and External STG IR tooling
* [jmorag/mcc](https://github.com/jmorag/mcc) - MicroC example compiler for Stephen Edward's PLT class, but in Haskell
* [ilya-klyuchnikov/lambdapi](https://github.com/ilya-klyuchnikov/lambdapi) - Dependently Typed Lambda Calculus in Haskell
* [cofinalsubnets/wisp](https://github.com/cofinalsubnets/wisp) - small-but-featureful embeddable lisp interpreter written in haskell.
* [tbarnetlamb/hyphen](https://github.com/tbarnetlamb/hyphen) - hyphen - access Haskell modules from Python
* [bos/llvm](https://github.com/bos/llvm) - Haskell bindings to the LLVM compiler infrastructure project.
* [well-typed/hs-bindgen](https://github.com/well-typed/hs-bindgen) - Automatically generate Haskell bindings from C header files
* [RubenVerg/TinyAPL](https://github.com/RubenVerg/TinyAPL) - TinyAPL, a tiny APL dialect and interpreter in Haskell
* [travitch/datalog](https://github.com/travitch/datalog) - A pure Haskell implementation of Datalog
* [japiirainen/fp](https://github.com/japiirainen/fp) - A small, weird and unpractical programming language.
* [lexi-lambda/higher-rank](https://github.com/lexi-lambda/higher-rank) - A small Haskell implementation of Complete and Easy Bidirectional Typechecking for Higher-Rank Polymorphism
* [google/ghc-source-gen](https://github.com/google/ghc-source-gen) - Library for generating Haskell source files and code fragments.
* [talw/crisp-compiler](https://github.com/talw/crisp-compiler) - A compiler for Crisp (Lisp/Scheme-inspired language) in Haskell, with an LLVM backend
* [alt-romes/hegg](https://github.com/alt-romes/hegg) - Fast equality saturation in Haskell
* [thephoeron/quipper-language](https://github.com/thephoeron/quipper-language) - Quipper: embedded, scalable functional programming language for quantum computing (unofficial fork)
* [blackhole89/macros](https://github.com/blackhole89/macros) - A more powerful C/C++ preprocessor.
* [Gabriella439/Haskell-Annah-Library](https://github.com/Gabriella439/Haskell-Annah-Library) - Distributed programming language that desugars to Morte
* [tanakh/Peggy](https://github.com/tanakh/Peggy) - The Parser Generator for Haskell
* [swr1bm86/Ntha](https://github.com/swr1bm86/Ntha) - The Ntha Programming Language
* [JakeWheat/simple-sql-parser](https://github.com/JakeWheat/simple-sql-parser) - SQL parser in Haskell
* [lambdacube3d/lambdacube-compiler](https://github.com/lambdacube3d/lambdacube-compiler) - LambdaCube 3D is a Haskell-like purely functional language for GPU. Try it out:
* [ice1000/Kt2Dart](https://github.com/ice1000/Kt2Dart) - :flashlight: [Deprecated] Transpile Kotlin codes into Dart, Make Flutter Great Again
* [jvranish/MiniKanrenT](https://github.com/jvranish/MiniKanrenT) - An implementation of miniKanren in Haskell
* [nominolo/lambdachine](https://github.com/nominolo/lambdachine) - VM and tracing JIT for Haskell (work in progress)
* [siraben/mini-haskell](https://github.com/siraben/mini-haskell) - A self-hosting mini Haskell compiler with a mini C runtime.
* [barbuz/Husk](https://github.com/barbuz/Husk) - Functional golfing language inspired by Haskell.
* [TerenceNg03/mueval](https://github.com/TerenceNg03/mueval) - A secure sandboxed Haskell interpreter for pure function evaluation
* [haskell-lisp/liskell](https://github.com/haskell-lisp/liskell) - Haskell Semantics with Lisp Syntax
* [mroman42/mikrokosmos](https://github.com/mroman42/mikrokosmos) - (λ) Educational lambda calculus interpreter
* [jdreaver/amy](https://github.com/jdreaver/amy) - Strict Haskell-like programming language that compiles to LLVM
* [con-kitty/categorifier](https://github.com/con-kitty/categorifier) - Interpret Haskell programs into any cartesian closed category.
* [vincenthz/language-java](https://github.com/vincenthz/language-java) - Java parser and printer for haskell *(archived)*
* [jaseemabid/Olifant](https://github.com/jaseemabid/Olifant) - A simple programming language targeting LLVM
* [bydriv/mhc](https://github.com/bydriv/mhc) - Minimal Haskell Compiler
* [Erdwolf/prolog](https://github.com/Erdwolf/prolog) - A prolog interpreter written in Haskell.
* [nponeccop/HNC](https://github.com/nponeccop/HNC) - HN Compiler
* [zepto-lang/zepto](https://github.com/zepto-lang/zepto) - A schemy Lisp backed by Haskell *(archived)*
* [chetant/LibClang](https://github.com/chetant/LibClang) - Haskell FFI to libclang
* [geekrelief/as3tohaxe](https://github.com/geekrelief/as3tohaxe) - An Actionscript 3 to haXe source converter written in Haskell
* [tomahawkins/improve](https://github.com/tomahawkins/improve) - An imperative programming language in Haskell for high assurance embedded applications. ImProve programs are verified with model checking. ImProve compiles to C and Simulink.
* [ehatti/konna](https://github.com/ehatti/konna) - A fast functional language based on two level type theory

### Build Systems

* [commercialhaskell/stack](https://github.com/commercialhaskell/stack) - The Haskell Tool Stack
* [lukexi/halive](https://github.com/lukexi/halive) - Live recompiler for Haskell
* [snowleopard/hadrian](https://github.com/snowleopard/hadrian) - Hadrian: a new build system for the Glasgow Haskell Compiler. Now merged into the GHC tree! *(archived)*
* [jekor/redo](https://github.com/jekor/redo) - djb's redo implementation in Haskell (for Haskell from Scratch video series)
* [haskell-mafia/mafia](https://github.com/haskell-mafia/mafia) - Provides protection against cabal swindling, robbing, injuring or sabotaging people with chopsticks.
* [judah/pier](https://github.com/judah/pier) - Yet another Haskell build system.
* [matthewbauer/ghc-nix](https://github.com/matthewbauer/ghc-nix) - Exploring the options for incremental Haskell builds using Nix

### Package Management

* [haskell/cabal](https://github.com/haskell/cabal) - Official upstream development repository for Cabal and cabal-install
* [sol/hpack](https://github.com/sol/hpack) - hpack: A modern format for Haskell packages
* [haskell/hackage-server](https://github.com/haskell/hackage-server) - Hackage-Server: A Haskell Package Repository
* [NixOS/cabal2nix](https://github.com/NixOS/cabal2nix) - Generate Nix build instructions from a Cabal file
* [haskell/haskell-platform](https://github.com/haskell/haskell-platform) - Distribution of Haskell with batteries included *(archived)*
* [haskell/ghcup-hs](https://github.com/haskell/ghcup-hs) - THIS REPO IS A MIRROR, BUG REPORTS GO HERE:
* [jyp/styx](https://github.com/jyp/styx) - A nix-based Haskell project manager
* [scarf-sh/scarf](https://github.com/scarf-sh/scarf) - An environment manager and development tool powered by Nomia. *(archived)*
* [flora-pm/flora-server](https://github.com/flora-pm/flora-server) - A package index for the Haskell ecosystem
* [cachix/elm2nix](https://github.com/cachix/elm2nix) - Convert Elm project into Nix expressions
* [Paczesiowa/hsenv](https://github.com/Paczesiowa/hsenv) - Virtual Haskell Environment builder
* [Novavero-AI/nova-nix](https://github.com/Novavero-AI/nova-nix) - Windows-native Nix evaluator - Haskell for logic, C99 for data. Parser, lazy evaluator, content-addressed store, builder, binary substituter.
* [commercialhaskell/stackage-server](https://github.com/commercialhaskell/stackage-server) - Server for stable, curated Haskell package sets
* [dhall-lang/dhall-to-cabal](https://github.com/dhall-lang/dhall-to-cabal) - Compile Dhall expressions to Cabal files
* [haskell-nix/hnix-store](https://github.com/haskell-nix/hnix-store) - Haskell implementation of the Nix store
* [sol/tinc](https://github.com/sol/tinc) - A dependency manager for Haskell
* [input-output-hk/nix-tools](https://github.com/input-output-hk/nix-tools) - Translate Cabals Generic Package Description to a Nix expression
* [phadej/cabal-extras](https://github.com/phadej/cabal-extras) - A tool suite to aid Haskell development using `cabal-install`
* [kowainik/policeman](https://github.com/kowainik/policeman) - 👮 Haskell PVP adviser
* [xtendo-org/chips](https://github.com/xtendo-org/chips) - A fast, lightweight, and concurrent plugin manager for the fish shell, written in Haskell
* [Paczesiowa/virthualenv](https://github.com/Paczesiowa/virthualenv) - Virtual Haskell Environment builder
* [blitzcode/hackage-diff](https://github.com/blitzcode/hackage-diff) - Compare the public API of different versions of a Hackage library

### Linters and Formatters

* [koalaman/shellcheck](https://github.com/koalaman/shellcheck) - ShellCheck, a static analysis tool for shell scripts
* [hadolint/hadolint](https://github.com/hadolint/hadolint) - Dockerfile linter, validate inline bash, written in Haskell
* [ndmitchell/hlint](https://github.com/ndmitchell/hlint) - Haskell source code suggestions
* [NixOS/nixfmt](https://github.com/NixOS/nixfmt) - The official formatter for Nix code
* [tweag/ormolu](https://github.com/tweag/ormolu) - A formatter for Haskell source code
* [haskell/stylish-haskell](https://github.com/haskell/stylish-haskell) - Haskell code prettifier
* [joshuaclayton/unused](https://github.com/joshuaclayton/unused) - Deprecated; see https://github.com/unused-code/unused *(archived)*
* [lspitzner/brittany](https://github.com/lspitzner/brittany) - haskell source code formatter
* [kowainik/stan](https://github.com/kowainik/stan) - 🕵️ Haskell STatic ANalyser
* [mihaimaruseac/hindent](https://github.com/mihaimaruseac/hindent) - Haskell pretty printer
* [facebookincubator/retrie](https://github.com/facebookincubator/retrie) - Retrie is a powerful, easy-to-use codemodding tool for Haskell. *(archived)*
* [fourmolu/fourmolu](https://github.com/fourmolu/fourmolu) - A fourk of ormolu that uses four space indentation and allows arbitrary configuration. Don't like it? PRs welcome!
* [haskell-tools/haskell-tools](https://github.com/haskell-tools/haskell-tools) - Developer tools for Haskell
* [yav/graphmod](https://github.com/yav/graphmod) - A utility for displaying the module dependencies of Haskell programs.
* [ennocramer/floskell](https://github.com/ennocramer/floskell) - Floskell is a flexible Haskell source code pretty printer.
* [facebookarchive/lex-pass](https://github.com/facebookarchive/lex-pass) - manipulate a php codebase using haskell to transform the abstract-syntax-tree *(archived)*
* [mpickering/apply-refact](https://github.com/mpickering/apply-refact) - Refactor Haskell source files
* [Synthetica9/nix-linter](https://github.com/Synthetica9/nix-linter) - Linter for the Nix expression language
* [camfort/camfort](https://github.com/camfort/camfort) - Light-weight verification and transformation tools for Fortran
* [RefactoringTools/HaRe](https://github.com/RefactoringTools/HaRe) - The Haskell Refactoring Tool
* [danstiner/hfmt](https://github.com/danstiner/hfmt) - Format Haskell programs. Inspired by the gofmt utility.
* [mumuki/mulang](https://github.com/mumuki/mulang) - :bamboo: Universal, Multi Language, Multi Paradigm code analyzer
* [serokell/importify](https://github.com/serokell/importify) - :space_invader: Importi.fy — it's like Uber, but for Haskell modules. *(archived)*
* [jonascarpay/calligraphy](https://github.com/jonascarpay/calligraphy) - haskell source code visualizer
* [rubik/argon](https://github.com/rubik/argon) - Monitor cyclomatic complexity in Haskell programs
* [alanz/ghc-exactprint](https://github.com/alanz/ghc-exactprint) - GHC version of haskell-src-exts exactPrint
* [tfausak/cabal-gild](https://github.com/tfausak/cabal-gild) - :crown: Format Haskell package descriptions.
* [kowainik/smuggler](https://github.com/kowainik/smuggler) - 🚣 Smuggle all imports *(archived)*
* [migamake/homplexity](https://github.com/migamake/homplexity) - Haskell code complexity and quality measurement

### Debugging and Profiling

* [itchyny/sjsp](https://github.com/itchyny/sjsp) - Simple JavaScript Profiler *(archived)*
* [haskell/ThreadScope](https://github.com/haskell/ThreadScope) - A graphical tool for profiling parallel Haskell programs
* [well-typed/haskell-debugger](https://github.com/well-typed/haskell-debugger) - A modern step-through debugger for GHC Haskell
* [def-/ghc-vis](https://github.com/def-/ghc-vis) - Visualize live Haskell data structures in GHCi
* [nh2/hatrace](https://github.com/nh2/hatrace) - scriptable strace
* [fpco/weigh](https://github.com/fpco/weigh) - Measure allocations of a Haskell functions/values
* [ocharles/what-it-do](https://github.com/ocharles/what-it-do) - Automatically trace all (showable) binds in do expressions
* [chshersh/dr-cabal](https://github.com/chshersh/dr-cabal) - 📊 Haskell dependencies build times profiler
* [bgamari/ghc-debug](https://github.com/bgamari/ghc-debug) - Moved to Haskell.org GitLab.
* [djv/VisualProf](https://github.com/djv/VisualProf) - http://www.reddit.com/r/haskell/comments/cr15z/visualprof_profiles_your_haskell_program_and/?sort=hot

### Editor and IDE Support

* [haskell/haskell-language-server](https://github.com/haskell/haskell-language-server) - Official Haskell IDE support via the language server protocol (LSP)
* [haskell/haskell-ide-engine](https://github.com/haskell/haskell-ide-engine) - The engine for haskell ide-integration. Not an IDE *(archived)*
* [leksah/leksah](https://github.com/leksah/leksah) - Haskell IDE
* [DanielG/ghc-mod](https://github.com/DanielG/ghc-mod) - Happy Haskell Hacking for editors. DEPRECATED *(archived)*
* [haskell/ghcide](https://github.com/haskell/ghcide) - A library for building Haskell IDE tooling *(archived)*
* [haskell/lsp](https://github.com/haskell/lsp) - Haskell library for the Microsoft Language Server Protocol
* [knupfer/haskell-emacs](https://github.com/knupfer/haskell-emacs) - Write Emacs extensions in Haskell
* [neovimhaskell/nvim-hs](https://github.com/neovimhaskell/nvim-hs) - Neovim API for Haskell plugins as well as the plugin provider
* [Avi-D-coder/implicit-hie](https://github.com/Avi-D-coder/implicit-hie) - Auto generate a stack or cabal multi component hie.yaml file
* [haskell/hie-bios](https://github.com/haskell/hie-bios) - Set up a GHC API session for various Haskell Projects
* [nominolo/scion](https://github.com/nominolo/scion) - OLD, DEPRECATED: Use this instead https://github.com/haskell/haskell-ide-engine *(archived)*
* [matsumonkie/izuna](https://github.com/matsumonkie/izuna) - Show Haskell type annotations when doing code review on Github
* [MarcWeber/hasktags](https://github.com/MarcWeber/hasktags) - Produces ctags "tags" and etags "TAGS" files for Haskell programs
* [mvoidex/hsdev](https://github.com/mvoidex/hsdev) - Haskell development tool
* [itchyny/vim-haskell-indent](https://github.com/itchyny/vim-haskell-indent) - If the plugin does not work for some syntax, feel free to report to the issue tracker!
* [haskell/vscode-haskell-syntax-highlighting](https://github.com/haskell/vscode-haskell-syntax-highlighting) - Syntax highlighting support for Haskell in Visual Studio Code
* [google/haskell-indexer](https://github.com/google/haskell-indexer) - Emits code crossreference data for Haskell sources. *(archived)*
* [hdevtools/hdevtools](https://github.com/hdevtools/hdevtools) - Persistent GHC-powered background server for FAST haskell development tools
* [elaforge/fast-tags](https://github.com/elaforge/fast-tags) - Incremental vi and emacs tags for haskell.
* [bitc/lushtags](https://github.com/bitc/lushtags) - Create ctags compatible tags files for Haskell programs
* [jfeltz/dash-haskell](https://github.com/jfeltz/dash-haskell) - dash docset builder for Haskell packages and cabal project dependencies
* [itchyny/miv](https://github.com/itchyny/miv) - Vim plugin manager written in Haskell
* [kazu-yamamoto/hhp](https://github.com/kazu-yamamoto/hhp) - Happy Haskell Programming
* [mrkkrp/ghc-syntax-highlighter](https://github.com/mrkkrp/ghc-syntax-highlighter) - Syntax highlighter for Haskell using the lexer of GHC

## Web

### Web Frameworks

* [wasp-lang/wasp](https://github.com/wasp-lang/wasp) - The batteries-included full-stack framework for the AI era. Develop JS/TS web apps (React, Node.js, and Prisma) using declarative code that abstracts away complex full-stack features like auth, background jobs, RPC, email sending, end-to-end type safety, single-command deployment, and more.
* [digitallyinduced/ihp](https://github.com/digitallyinduced/ihp) - 🔥 The fastest way to build type safe web apps. IHP is a new batteries-included web framework optimized for longterm productivity and programmer happiness
* [jaspervdj/hakyll](https://github.com/jaspervdj/hakyll) - A static website compiler library in Haskell
* [yesodweb/yesod](https://github.com/yesodweb/yesod) - A RESTful Haskell web framework built on WAI.
* [scotty-web/scotty](https://github.com/scotty-web/scotty) - Haskell web framework inspired by Ruby's Sinatra, using WAI and Warp (Official Repository)
* [obsidiansystems/obelisk](https://github.com/obsidiansystems/obelisk) - Functional reactive web and mobile applications, with batteries included.
* [yesodweb/wai](https://github.com/yesodweb/wai) - Haskell Web Application Interface
* [agrafix/Spock](https://github.com/agrafix/Spock) - Another Haskell web framework for rapid development
* [seanhess/hyperbole](https://github.com/seanhess/hyperbole) - Haskell interactive serverside web framework inspired by HTMX, Elm, and Phoenix LiveView
* [tmcgilchrist/airship](https://github.com/tmcgilchrist/airship) - Helium + Webmachine = Airship. A toolkit for building declarative, RESTful web apps.
* [ChrisPenner/slick](https://github.com/ChrisPenner/slick) - Static site generator built on Shake configured in Haskell
* [kowainik/cake-slayer](https://github.com/kowainik/cake-slayer) - 🍰🔪 Architecture of Haskell backend applications
* [srid/ema](https://github.com/srid/ema) - Change-aware static site generator for Haskell programmers
* [srid/rib](https://github.com/srid/rib) - Haskell static site generator based on Shake (superseded by https://github.com/srid/ema)
* [valpackett/magicbane](https://github.com/valpackett/magicbane) - A web framework that integrates Servant, EKG, fast-logger, wai-cli… | now on https://codeberg.org/valpackett/magicbane *(archived)*
* [monadicsystems/okapi](https://github.com/monadicsystems/okapi) - A bidirectional DSL for describing HTTP servers.
* [clckwrks/clckwrks](https://github.com/clckwrks/clckwrks) - A Haskell CMS platform
* [eldr-io/hastl](https://github.com/eldr-io/hastl) - Production ready, modern web-application starter template using haskell and htmx
* [ChrisPenner/Firefly](https://github.com/ChrisPenner/Firefly) - Simple Haskell http framework
* [alsonkemp/turbinado](https://github.com/alsonkemp/turbinado) - MVC Web Framework for Haskell. See http://github.com/turbinado/turbinado-website for example code
* [alexmingoia/twain](https://github.com/alexmingoia/twain) - Tiny web application framework for WAI.
* [anton-k/mig](https://github.com/anton-k/mig) - Lightweight and composable servers for Haskell
* [transient-haskell/axiom](https://github.com/transient-haskell/axiom) - Client-side and server-side web framework over Transient and GHCJS (Haskell to JavaScript compiler)
* [moonmaster9000/bird](https://github.com/moonmaster9000/bird) - A sinatra-ish framework written in haskell, riding on top of Hack

### HTTP and Networking Clients

* [haskell-github/github](https://github.com/haskell-github/github) - The github API for Haskell
* [mrkkrp/req](https://github.com/mrkkrp/req) - An HTTP client library
* [discord-haskell/discord-haskell](https://github.com/discord-haskell/discord-haskell) - Haskell library for writing Discord bots
* [snoyberg/http-client](https://github.com/snoyberg/http-client) - An HTTP client engine, intended as a base layer for more user-friendly packages.
* [klappvisor/haskell-telegram-api](https://github.com/klappvisor/haskell-telegram-api) - Telegram Bot API for Haskell
* [dmjio/stripe](https://github.com/dmjio/stripe) - :moneybag: Stripe API
* [haskell/HTTP](https://github.com/haskell/HTTP) - Haskell HTTP package
* [himura/twitter-conduit](https://github.com/himura/twitter-conduit) - Twitter API package for Haskell, including enumerator interfaces and Streaming API supports.
* [aviaviavi/cryptocompare](https://github.com/aviaviavi/cryptocompare) - Haskell wrapper for the CryptoCompare API - No longer maintained, ping me if you'd like to take over
* [hlian/linklater](https://github.com/hlian/linklater) - A Haskell library for the Slack API (including real-time messaging!)
* [intolerable/reddit](https://github.com/intolerable/reddit) - reddit api for haskell *(archived)*
* [rickeyski/slack-api](https://github.com/rickeyski/slack-api) - Haskell bindings to the Slack RTM API
* [owainlewis/http-dispatch](https://github.com/owainlewis/http-dispatch) - A high level HTTP client for Haskell that focuses on ease of use

### API and GraphQL

* [hasura/graphql-engine](https://github.com/hasura/graphql-engine) - Blazing fast, instant realtime GraphQL APIs on all your data with fine grained access control, also trigger webhooks on database events.
* [PostgREST/postgrest](https://github.com/PostgREST/postgrest) - REST API for any Postgres database
* [haskell-servant/servant](https://github.com/haskell-servant/servant) - Servant is a Haskell DSL for describing, serving, querying, mocking, documenting web applications and more!
* [morpheusgraphql/morpheus-graphql](https://github.com/morpheusgraphql/morpheus-graphql) - Haskell GraphQL Api, Client and Tools
* [haskell-graphql/graphql-api](https://github.com/haskell-graphql/graphql-api) - Write type-safe GraphQL services in Haskell
* [jdnavarro/graphql-haskell](https://github.com/jdnavarro/graphql-haskell) - Haskell GraphQL implementation
* [haskell-servant/servant-elm](https://github.com/haskell-servant/servant-elm) - Automatically derive Elm functions to query servant webservices
* [cdepillabout/servant-checked-exceptions](https://github.com/cdepillabout/servant-checked-exceptions) - type-level errors for Servant APIs.
* [bendyworks/api-server](https://github.com/bendyworks/api-server) - A JSON API server written in Haskell
* [tfausak/hairy](https://github.com/tfausak/hairy) - :haircut: A JSON REST API built in Haskell. *(archived)*
* [hasura/graphql-parser-hs](https://github.com/hasura/graphql-parser-hs) - A GraphQL query parser for Haskell

### Frontend and UI Components

* [dmjio/miso](https://github.com/dmjio/miso) - :ramen: A tasty Haskell web framework
* [reflex-frp/reflex-dom](https://github.com/reflex-frp/reflex-dom) - Web applications without callbacks or side-effects. Reflex-DOM brings the power of functional reactive programming (FRP) to the web. Build HTML and other Document Object Model (DOM) data with a pure functional interface.
* [sebastiaanvisser/clay](https://github.com/sebastiaanvisser/clay) - A CSS preprocessor as embedded Haskell.
* [joelburget/react-haskell](https://github.com/joelburget/react-haskell) - React bindings for Haskell
* [chrisdone-archive/vado](https://github.com/chrisdone-archive/vado) - A demo web browser engine written in Haskell *(archived)*
* [jaspervdj/blaze-html](https://github.com/jaspervdj/blaze-html) - A blazingly fast HTML combinator library for Haskell.
* [takeoutweight/shade](https://github.com/takeoutweight/shade) - Interactive, client-side web apps in Haskell
* [pkamenarsky/replica](https://github.com/pkamenarsky/replica) - A remote virtual DOM library for Haskell
* [pkamenarsky/concur-replica](https://github.com/pkamenarsky/concur-replica) - Server-side VDOM UI framework for Concur
* [meiersi/blaze-react](https://github.com/meiersi/blaze-react) - A blaze-html style ReactJS binding for Haskell using GHCJS
* [commandodev/oHm](https://github.com/commandodev/oHm) - Om with Haskell in it
* [Holmusk/elm-street](https://github.com/Holmusk/elm-street) - :deciduous_tree: Crossing the road between Haskell and Elm
* [isovector/suavemente](https://github.com/isovector/suavemente) - :dancer: an applicative functor that seamlessly talks to HTML inputs
* [codedownio/aeson-typescript](https://github.com/codedownio/aeson-typescript) - Generate TypeScript definition files from your ADTs
* [crufter/haquery](https://github.com/crufter/haquery) - jQuery for Haskell
* [pkamenarsky/concur-static](https://github.com/pkamenarsky/concur-static) - Generate semi-dynamic UIs with Concur

## Data and Storage

### Databases

* [agentm/project-m36](https://github.com/agentm/project-m36) - Project: M36 Relational Algebra Engine
* [hstreamdb/hstream](https://github.com/hstreamdb/hstream) - HStreamDB is an open-source, cloud-native streaming database for IoT and beyond. Modernize your data stack for real-time applications.
* [acid-state/acid-state](https://github.com/acid-state/acid-state) - Add ACID guarantees to any serializable Haskell data structure
* [statebox/cql](https://github.com/statebox/cql) - CQL: Categorical Query Language implementation in Haskell
* [ed-o-saurus/PLHaskell](https://github.com/ed-o-saurus/PLHaskell) - An extension for PostgreSQL that allows embedded Haskell code.
* [honza/redish](https://github.com/honza/redish) - A multi-threaded, TCP, key-value store inspired by Redis implemented in Haskell.
* [bgamari/b-tree](https://github.com/bgamari/b-tree) - Haskell on-disk B* tree implementation
* [jdreaver/eventful](https://github.com/jdreaver/eventful) - Event Sourcing library for Haskell *(archived)*
* [haskell-haskey/haskey](https://github.com/haskell-haskey/haskey) - Transactional key-value store written entirely in Haskell
* [danielwaterworth/siege](https://github.com/danielwaterworth/siege) - [DEPRECATED] A DBMS written in Haskell

### Database Clients and ORMs

* [haskell-beam/beam](https://github.com/haskell-beam/beam) - A type-safe Haskell SQL library
* [nikita-volkov/hasql](https://github.com/nikita-volkov/hasql) - Reliable and fast PostgreSQL driver for Haskell
* [yesodweb/persistent](https://github.com/yesodweb/persistent) - Persistence interface for Haskell allowing multiple storage methods.
* [valderman/selda](https://github.com/valderman/selda) - A type-safe, high-level SQL library for Haskell
* [morphismtech/squeal](https://github.com/morphismtech/squeal) - Squeal, a deep embedding of SQL in Haskell
* [informatikr/hedis](https://github.com/informatikr/hedis) - A Redis client library for Haskell.
* [khibino/haskell-relational-record](https://github.com/khibino/haskell-relational-record) - This repository includes a joined query generator based on typefull relational algebra, and mapping tools between SQL values list and Haskell record type.
* [lpsmith/postgresql-simple](https://github.com/lpsmith/postgresql-simple) - Mid-level client library for accessing PostgreSQL from Haskell
* [mongodb-haskell/mongodb](https://github.com/mongodb-haskell/mongodb) - MongoDB driver for Haskell
* [circuithub/rel8](https://github.com/circuithub/rel8) - Hey! Hey! Can u rel8?
* [hdbc/hdbc](https://github.com/hdbc/hdbc) - Haskell Database Connectivity
* [winterland1989/mysql-haskell](https://github.com/winterland1989/mysql-haskell) - Pure haskell mysql driver
* [nikita-volkov/hasql-th](https://github.com/nikita-volkov/hasql-th) - Template Haskell utilities for Hasql
* [bos/pool](https://github.com/bos/pool) - A high-performance striped resource pooling implementation for Haskell
* [JakeWheat/hssqlppp](https://github.com/JakeWheat/hssqlppp) - SQL parser and type checker in Haskell
* [m4dc4p/haskelldb](https://github.com/m4dc4p/haskelldb) - A library for building re-usable and composable SQL queries.
* [KovalevDima/ClickHaskell](https://github.com/KovalevDima/ClickHaskell) - ClickHouse Native protocol driver in Haskell
* [haskellari/postgresql-simple](https://github.com/haskellari/postgresql-simple) - Mid-level client library for accessing PostgreSQL from Haskell
* [AtnNn/haskell-rethinkdb](https://github.com/AtnNn/haskell-rethinkdb) - RethinkDB client library for Haskell
* [ameingast/postgresql-simple-migration](https://github.com/ameingast/postgresql-simple-migration) - PostgreSQL Schema Migrations for Haskell *(archived)*
* [zmactep/hasbolt](https://github.com/zmactep/hasbolt) - Haskell driver for Neo4j 3+ (BOLT protocol)
* [YoEight/eventstore](https://github.com/YoEight/eventstore) - EventStore Haskell TCP Client *(archived)*
* [alevy/postgresql-orm](https://github.com/alevy/postgresql-orm) - An Haskell ORM (Object Relational Mapping) and migrations DSL for PostgreSQL.
* [kim/leveldb-haskell](https://github.com/kim/leveldb-haskell) - Haskell bindings to LevelDB (https://github.com/google/leveldb)
* [postgres-haskell/postgres-wire](https://github.com/postgres-haskell/postgres-wire) - A native Haskell driver for PostgreSQL
* [tmcgilchrist/postgresql-transactional](https://github.com/tmcgilchrist/postgresql-transactional) - Transactional monadic actions on top of PostgreSQL.

### Serialization and Formats

* [haskell/aeson](https://github.com/haskell/aeson) - A fast Haskell JSON library
* [google/proto-lens](https://github.com/google/proto-lens) - API for protocol buffers using modern Haskell language and library patterns.
* [ndmitchell/tagsoup](https://github.com/ndmitchell/tagsoup) - Haskell library for parsing and extracting information from (possibly malformed) HTML/XML documents
* [haskell-hvr/cassava](https://github.com/haskell-hvr/cassava) - A CSV parsing and encoding library optimized for ease of use and high performance
* [well-typed/cborg](https://github.com/well-typed/cborg) - Binary serialisation in the CBOR format
* [snoyberg/yaml](https://github.com/snoyberg/yaml) - Support for serialising Haskell to and from Yaml.
* [tfausak/rattletrap](https://github.com/tfausak/rattletrap) - :car: Parse and generate Rocket League replays. *(archived)*
* [migamake/json-autotype](https://github.com/migamake/json-autotype) - Automatic Haskell type inference from JSON input
* [msgpack/msgpack-haskell](https://github.com/msgpack/msgpack-haskell) - Haskell implementation of MessagePack / msgpack.org[Haskell]
* [qrilka/xlsx](https://github.com/qrilka/xlsx) - Simple and incomplete Excel file parser/writer
* [kowainik/tomland](https://github.com/kowainik/tomland) - 🏝 Bidirectional TOML serialization
* [UweSchmidt/hxt](https://github.com/UweSchmidt/hxt) - Haskell XML Toolbox
* [ocramz/xeno](https://github.com/ocramz/xeno) - Fast Haskell XML parser
* [haskell/binary](https://github.com/haskell/binary) - Efficient, pure binary serialisation using ByteStrings in Haskell.
* [krisajenkins/elm-export](https://github.com/krisajenkins/elm-export) - Create Elm types and JSON decoders from Haskell source.
* [eskimor/purescript-bridge](https://github.com/eskimor/purescript-bridge) - Create PureScript datatypes from Haskell datatypes
* [mgsloan/store](https://github.com/mgsloan/store) - Fast binary serialization in Haskell
* [haskell-waargonaut/waargonaut](https://github.com/haskell-waargonaut/waargonaut) - JSON decoding/encoding/manipulation library.
* [alphaHeavy/protobuf](https://github.com/alphaHeavy/protobuf) - An implementation of Google's Protocol Buffers in Haskell.
* [zenhack/haskell-capnp](https://github.com/zenhack/haskell-capnp) - Cap'n Proto for Haskell
* [haskell-works/avro](https://github.com/haskell-works/avro) - Haskell Avro Encoding and Decoding Native Support (no RPC)
* [nikita-volkov/jsonifier](https://github.com/nikita-volkov/jsonifier) - Fast and simple JSON encoding toolkit
* [awakesecurity/proto3-suite](https://github.com/awakesecurity/proto3-suite) - Haskell Protobuf Implementation
* [robstewart57/rdf4h](https://github.com/robstewart57/rdf4h) - rdf4h is a library for working with RDF in Haskell
* [k-bx/protocol-buffers](https://github.com/k-bx/protocol-buffers) - Haskell protocol-buffers package
* [ChrisPenner/json-to-haskell](https://github.com/ChrisPenner/json-to-haskell) - In goes JSON, out comes a complete Haskell model complete with instances! CLI and web interface available.
* [sol/aeson-qq](https://github.com/sol/aeson-qq) - JSON quasiquoter for Haskell
* [snoyberg/xml](https://github.com/snoyberg/xml) - Various XML utility packages for Haskell
* [dhall-lang/dhall-json](https://github.com/dhall-lang/dhall-json) - This repository has moved to https://github.com/dhall-lang/dhall-haskell/tree/master/dhall-json *(archived)*
* [ocramz/aeson-schema](https://github.com/ocramz/aeson-schema) - Haskell JSON schema validator and parser generator
* [Quid2/flat](https://github.com/Quid2/flat) - Principled and efficient binary serialization

## Machine Learning and AI

### Machine Learning Frameworks

* [tensorflow/haskell](https://github.com/tensorflow/haskell) - Haskell bindings for TensorFlow *(archived)*
* [HuwCampbell/grenade](https://github.com/HuwCampbell/grenade) - Deep Learning in Haskell
* [hasktorch/hasktorch](https://github.com/hasktorch/hasktorch) - Tensors and neural networks in Haskell
* [jbarrow/LambdaNet](https://github.com/jbarrow/LambdaNet) - Purely functional artificial neural network library implemented in Haskell.
* [hakaru-dev/hakaru](https://github.com/hakaru-dev/hakaru) - A probabilistic programming language
* [mstksg/backprop](https://github.com/mstksg/backprop) - Heterogeneous automatic differentiation ("backpropagation") in Haskell
* [saschagrunert/nn](https://github.com/saschagrunert/nn) - A tiny neural network 🧠
* [brunjlar/neural](https://github.com/brunjlar/neural) - Neural Nets in native Haskell
* [alpmestan/hnn](https://github.com/alpmestan/hnn) - haskell neural network library
* [leopiney/tensor-safe](https://github.com/leopiney/tensor-safe) - A Haskell framework to define valid deep learning models and export them to other frameworks like TensorFlow JS or Keras.
* [mstksg/tensor-ops](https://github.com/mstksg/tensor-ops) - Type-safe tensor manipulation operations in Haskell with tensorflow-style automatic differentiation

### Data Science and Analytics

* [tweag/HaskellR](https://github.com/tweag/HaskellR) - The full power of R in Haskell.
* [tweag/sparkle](https://github.com/tweag/sparkle) - Haskell on Apache Spark.
* [timbod7/haskell-chart](https://github.com/timbod7/haskell-chart) - A 2D charting library for haskell
* [utdemir/distributed-dataset](https://github.com/utdemir/distributed-dataset) - A distributed data processing framework in Haskell.
* [diffusionkinetics/open](https://github.com/diffusionkinetics/open) - DiffusionKinetics open-source monorepo
* [DataHaskell/sabela](https://github.com/DataHaskell/sabela) - A reactive notebook for Haskell
* [Soostone/hadron](https://github.com/Soostone/hadron) - Construct and run Hadoop MapReduce programs in Haskell
* [YPares/porcupine](https://github.com/YPares/porcupine) - Express parametrable, composable and portable data pipelines
* [abarbu/matplotlib-haskell](https://github.com/abarbu/matplotlib-haskell) - Haskell bindings for Python's Matplotlib
* [huffyhenry/sync.soccer](https://github.com/huffyhenry/sync.soccer) - Synchronise event and tracking data using dynamic programming
* [jupyter-xeus/xeus-haskell](https://github.com/jupyter-xeus/xeus-haskell) - jupyter / jupyterlite kernel for Haskell powered by WebAssembly
* [coinmetrics/haskell-tools](https://github.com/coinmetrics/haskell-tools) - Tools for exporting blockchain data to analytical databases

## Networking and Distributed

### Networking

* [jaspervdj/websockets](https://github.com/jaspervdj/websockets) - A Haskell library for creating WebSocket-capable servers
* [Consensys/constellation](https://github.com/Consensys/constellation) - Peer-to-peer encrypted message exchange *(archived)*
* [haskell/network](https://github.com/haskell/network) - Low-level networking interface
* [GaloisInc/haskell-tor](https://github.com/GaloisInc/haskell-tor) - A Haskell implementation of the Tor protocol.
* [glguy/irc-core](https://github.com/glguy/irc-core) - Haskell IRC library and console client - Join us on libera.chat #glirc
* [ocharles/engine.io](https://github.com/ocharles/engine.io) - A Haskell server implementation of the Engine.IO and Socket.IO (1.0) protocols
* [chrisdone-archive/hulk](https://github.com/chrisdone-archive/hulk) - Haskell IRC daemon. *(archived)*
* [GaloisInc/HaNS](https://github.com/GaloisInc/HaNS) - The haskell network stack
* [kazu-yamamoto/quic](https://github.com/kazu-yamamoto/quic) - IETF QUIC library in Haskell
* [cronokirby/haze](https://github.com/cronokirby/haze) - A bittorrent client, for learning purposes
* [qnikst/HaskellNet](https://github.com/qnikst/HaskellNet) - Haskell library which provides client support for POP3, SMTP, and IMAP protocols.
* [iijlab/dnsext](https://github.com/iijlab/dnsext) - A DNS full resolver and a stub command
* [jhickner/smtp-mail](https://github.com/jhickner/smtp-mail) - Making it easy to send SMTP email from Haskell
* [kazu-yamamoto/http3](https://github.com/kazu-yamamoto/http3) - HTTP/3 library in Haskell
* [tfausak/wuss](https://github.com/tfausak/wuss) - :lock: Secure WebSocket (WSS) clients in Haskell.
* [kazu-yamamoto/dns](https://github.com/kazu-yamamoto/dns) - DNS libary in Haskell
* [vincenthz/hs-connection](https://github.com/vincenthz/hs-connection) - simple client connection library in haskell with builtin features: SSL/TLS, SOCKS, session management. *(archived)*
* [rnons/shadowsocks-haskell](https://github.com/rnons/shadowsocks-haskell) - shadowsocks in haskell

### RPC and Messaging

* [higherkindness/mu-haskell](https://github.com/higherkindness/mu-haskell) - Mu (μ) is a purely functional framework for building micro services. *(archived)*
* [awakesecurity/gRPC-haskell](https://github.com/awakesecurity/gRPC-haskell) - Haskell gRPC support
* [facebookincubator/hsthrift](https://github.com/facebookincubator/hsthrift) - The Haskell Thrift Compiler. This is an implementation of the Thrift spec that generates code in Haskell. It depends on the fbthrift project for the implementation of the underlying transport.
* [grpc/grpc-haskell](https://github.com/grpc/grpc-haskell) - gRPC library binding for Haskell.
* [twittner/zeromq-haskell](https://github.com/twittner/zeromq-haskell) - This repository has been moved to https://gitlab.com/twittner/zeromq-haskell *(archived)*
* [nirum-lang/nirum](https://github.com/nirum-lang/nirum) - Nirum: IDL compiler and RPC/distributed object framework for microservices
* [well-typed/grapesy](https://github.com/well-typed/grapesy) - Native Haskell gRPC client and server based on `http2`
* [poor-a/erlang-ffi](https://github.com/poor-a/erlang-ffi) - A Foreign Function Interface that lets Haskell and Erlang programs communicate.

### Distributed Systems

* [input-output-hk/cardano-sl](https://github.com/input-output-hk/cardano-sl) - Cryptographic currency implementing Ouroboros PoS protocol *(archived)*
* [haskell-distributed/distributed-process](https://github.com/haskell-distributed/distributed-process) - Cloud Haskell core libraries
* [aviaviavi/legion](https://github.com/aviaviavi/legion) - Simple blockchain server written in Haskell for educational purposes
* [jepst/CloudHaskell](https://github.com/jepst/CloudHaskell) - A distributed computing framework for Haskell
* [cardano-scaling/hydra](https://github.com/cardano-scaling/hydra) - Implementation of the Hydra Head protocol
* [IntersectMBO/ouroboros-network](https://github.com/IntersectMBO/ouroboros-network) - Specifications of network protocols and implementations of components running these protocols which support a family of Ouroboros Consesus protocols; the diffusion layer of the Cardano Node.
* [kadena-io/chainweb-node](https://github.com/kadena-io/chainweb-node) - Chainweb: A Proof-of-Work Parallel-Chain Architecture for Massive Throughput *(archived)*
* [airalab/hs-web3](https://github.com/airalab/hs-web3) - Web3 API for Haskell
* [gshen42/HasChor](https://github.com/gshen42/HasChor) - Functional choreographic programming in Haskell
* [chrisnc/tangaroa](https://github.com/chrisnc/tangaroa) - A toy implementation of the Raft protocol in Haskell, with an experimental BFT variant.
* [Concordium/concordium-node](https://github.com/Concordium/concordium-node) - The main concordium node implementation.
* [sealchain-project/sealchain](https://github.com/sealchain-project/sealchain) - Financial blockchain based on cardano-sl
* [hailstorm-hs/hailstorm](https://github.com/hailstorm-hs/hailstorm) - Haskell distributed stream processing with exactly-once semantics
* [MichaelBurge/haskoin](https://github.com/MichaelBurge/haskoin) - Proof-of-concept Blockchain in Haskell
* [bkirwi/ethereum-haskell](https://github.com/bkirwi/ethereum-haskell) - An independent reimplementation of Ethereum in Haskell *(archived)*
* [smart-chain-fr/tokenomia](https://github.com/smart-chain-fr/tokenomia) - Tokenomia is built for the Cardashift ICO, it aims to simplify the use of Native Tokens and Smart Contracts above the Cardano Platform. Cardashift is a community-driven startup platform that raises funds, builds and accelerates startups that solve social and environmental problems.
* [geniusyield/atlas](https://github.com/geniusyield/atlas) - Application backend for Plutus smart contracts on Cardano
* [mercury/hs-temporal-sdk](https://github.com/mercury/hs-temporal-sdk) - Unofficial Temporal Haskell SDK
* [ff-notes/ron](https://github.com/ff-notes/ron) - Haskell implementation of RON and RON-RDT
* [takenobu-hs/haskell-ethereum-assembly](https://github.com/takenobu-hs/haskell-ethereum-assembly) - EVM (Ethereum virtual machine) Assembly on Haskell DSL

### Cloud and Infrastructure

* [cachix/cachix](https://github.com/cachix/cachix) - Command line client for Nix binary cache hosting:
* [GaloisInc/HaLVM](https://github.com/GaloisInc/HaLVM) - The Haskell Lightweight Virtual Machine (HaLVM): GHC running on Xen *(archived)*
* [brendanhay/amazonka](https://github.com/brendanhay/amazonka) - A comprehensive Amazon Web Services SDK for Haskell.
* [haskell-CI/haskell-ci](https://github.com/haskell-CI/haskell-ci) - Scripts and instructions for using CI services (e.g. Travis CI or Appveyor) with multiple GHC configurations
* [brendanhay/gogol](https://github.com/brendanhay/gogol) - A comprehensive Google Services SDK for Haskell.
* [theam/aws-lambda-haskell-runtime](https://github.com/theam/aws-lambda-haskell-runtime) - ⚡Haskell runtime for AWS Lambda
* [aristidb/aws](https://github.com/aristidb/aws) - Amazon Web Services for Haskell *(archived)*
* [Nike-Inc/hal](https://github.com/Nike-Inc/hal) - hal provides an AWS Lambda Custom Runtime environment for your Haskell applications.
* [nstack/nstack](https://github.com/nstack/nstack) - Type-safe, composable microservices for data analytics *(archived)*
* [seek-oss/serverless-haskell](https://github.com/seek-oss/serverless-haskell) - Deploying Haskell applications to AWS Lambda with Serverless
* [alpacaaa/quad-ci](https://github.com/alpacaaa/quad-ci) - A CI server written in Simple Haskell.
* [hercules-ci/legacy-old-hercules](https://github.com/hercules-ci/legacy-old-hercules) - Abandoned
* [awakesecurity/nix-deploy](https://github.com/awakesecurity/nix-deploy) - Deploy software or an entire NixOS system configuration to another NixOS system *(archived)*
* [mbj/stratosphere](https://github.com/mbj/stratosphere) - Haskell EDSL and type-checker for AWS CloudFormation templates
* [typeable/octopod](https://github.com/typeable/octopod) - Kubernetes self-service portal
* [abailly/aws-lambda-haskell](https://github.com/abailly/aws-lambda-haskell) - Running Haskell code on AWS Lambda
* [ocharles/micro-ci](https://github.com/ocharles/micro-ci) - A tiny CI server built around GitHub and Nix
* [kubernetes-client/haskell](https://github.com/kubernetes-client/haskell) - Haskell client for the kubernetes API. A work in progress.
* [awakesecurity/hocker](https://github.com/awakesecurity/hocker) - Utilities for interacting with the docker registry and generating nix build instructions
* [hercules-ci/hercules-ci-agent](https://github.com/hercules-ci/hercules-ci-agent) - https://hercules-ci.com build and deployment agent
* [stackbuilders/hapistrano](https://github.com/stackbuilders/hapistrano) - Deploy tool for Haskell applications, like Capistrano for Rails
* [podenv/podenv](https://github.com/podenv/podenv) - a container wrapper
* [denibertovic/docker-hs](https://github.com/denibertovic/docker-hs) - A Haskell library for the Docker Engine API
* [qmuli/qmuli](https://github.com/qmuli/qmuli) - Qmuli - Serverless framework for Haskell

### Monitoring and Observability

* [monoscope-tech/monoscope](https://github.com/monoscope-tech/monoscope) - Monoscope lets you ingest and explore your logs, traces and metrics. We store these in S3 compatible buckets. Query in natural language via LLMs.
* [iand675/hs-opentelemetry](https://github.com/iand675/hs-opentelemetry) - OpenTelemetry support for the Haskell programming language
* [fimad/prometheus-haskell](https://github.com/fimad/prometheus-haskell) - Haskell client library for exposing prometheus.io metrics.
* [ethercrow/opentelemetry-haskell](https://github.com/ethercrow/opentelemetry-haskell) - The OpenTelemetry Haskell Client https://opentelemetry.io
* [bitnomial/prometheus](https://github.com/bitnomial/prometheus) - Prometheus.io Haskell client.

## User Interface

### GUI Toolkits

* [fjvallarino/monomer](https://github.com/fjvallarino/monomer) - An easy to use, cross platform, GUI library for writing Haskell applications.
* [HeinrichApfelmus/threepenny-gui](https://github.com/HeinrichApfelmus/threepenny-gui) - GUI framework that uses the web browser as a display.
* [haskell-gi/haskell-gi](https://github.com/haskell-gi/haskell-gi) - Generate Haskell bindings for GObject-Introspection capable libraries
* [owickstrom/gi-gtk-declarative](https://github.com/owickstrom/gi-gtk-declarative) - Declarative GTK+ programming in Haskell
* [keera-studios/keera-hails](https://github.com/keera-studios/keera-hails) - Keera Hails: Haskell on Rails - Reactive Programming Framework for Interactive Haskell applications
* [gtk2hs/gtk2hs](https://github.com/gtk2hs/gtk2hs) - GUI library for Haskell based on GTK+
* [Gabriella439/Haskell-Typed-Spreadsheet-Library](https://github.com/Gabriella439/Haskell-Typed-Spreadsheet-Library) - Typed and composable spreadsheets
* [haskell-game/dear-imgui.hs](https://github.com/haskell-game/dear-imgui.hs) - Haskell bindings to Dear ImGui, an immediate mode GUI toolkit
* [lettier/webviewhs](https://github.com/lettier/webviewhs) - 🌐 A Haskell binding to the webview library created by Serge Zaitsev.
* [xmonad/X11](https://github.com/xmonad/X11) - A Haskell binding to the X11 graphics library.
* [abooij/sudbury](https://github.com/abooij/sudbury) - Haskell implementation of the wayland protocol
* [bradrn/wlhs](https://github.com/bradrn/wlhs) - Haskell bindings to wlroots (and libwayland)

### Terminal and Console UI

* [jtdaugherty/brick](https://github.com/jtdaugherty/brick) - A declarative Unix terminal UI library written in Haskell
* [jtdaugherty/vty](https://github.com/jtdaugherty/vty) - A high-level ncurses alternative written in Haskell
* [haskell/haskeline](https://github.com/haskell/haskeline) - A Haskell library for line input in command-line programs.
* [reflex-frp/reflex-vty](https://github.com/reflex-frp/reflex-vty) - Build terminal applications using functional reactive programming (FRP) with Reflex FRP.
* [rdnetto/powerline-hs](https://github.com/rdnetto/powerline-hs) - A lightning fast reimplementation of the Powerline prompt generator in Haskell.
* [UnkindPartition/ansi-terminal](https://github.com/UnkindPartition/ansi-terminal) - ANSI terminal support for Haskell, with Windows compatibility
* [sdiehl/repline](https://github.com/sdiehl/repline) - Haskeline wrapper for GHCi-like REPL interfaces
* [kowainik/colourista](https://github.com/kowainik/colourista) - ‎️‍🌈 Convenient interface for printing colourful messages
* [bitc/hs-term-emulator](https://github.com/bitc/hs-term-emulator) - Terminal Emulator written in 100% Haskell
* [skogsbaer/hscurses](https://github.com/skogsbaer/hscurses) - ncurses binding for Haskell
* [yamadapc/haskell-ascii-progress](https://github.com/yamadapc/haskell-ascii-progress) - A simple Haskell progress bar for the console. Heavily borrows from TJ Holowaychuk's Node.JS project

### Applications and End User Tools

* [simplex-chat/simplex-chat](https://github.com/simplex-chat/simplex-chat) - SimpleX - the first messaging network operating without user identifiers of any kind - 100% private by design! iOS, Android and desktop apps 📱!
* [kmonad/kmonad](https://github.com/kmonad/kmonad) - An advanced keyboard manager
* [plaintextaccounting/hledger](https://github.com/plaintextaccounting/hledger) - Robust, fast, intuitive plain text accounting tool with CLI, TUI and web interfaces.
* [xmonad/xmonad](https://github.com/xmonad/xmonad) - The core of xmonad, a small but functional ICCCM-compliant tiling window manager
* [wireapp/wire-server](https://github.com/wireapp/wire-server) - 🇪🇺 Wire back-end services
* [jaspervdj/patat](https://github.com/jaspervdj/patat) - Terminal-based presentations using Pandoc
* [fosskers/aura](https://github.com/fosskers/aura) - A multilingual package manager for Arch Linux and the AUR.
* [smallhadroncollider/taskell](https://github.com/smallhadroncollider/taskell) - Command-line Kanban board/task manager with support for Trello boards and GitHub projects *(archived)*
* [yi-editor/yi](https://github.com/yi-editor/yi) - The Haskell-Scriptable Editor
* [lettier/gifcurry](https://github.com/lettier/gifcurry) - 😎 The open-source, Haskell-built video editor for GIF makers.
* [matterhorn-chat/matterhorn](https://github.com/matterhorn-chat/matterhorn) - A feature-rich Unix terminal client for the Mattermost chat system
* [phuhl/linux_notification_center](https://github.com/phuhl/linux_notification_center) - A notification daemon/center for linux
* [samtay/tetris](https://github.com/samtay/tetris) - A terminal interface for Tetris
* [srid/emanote](https://github.com/srid/emanote) - Emanate a structured view of your plain-text notes
* [jonschoning/espial](https://github.com/jonschoning/espial) - Espial is an open-source, web-based bookmarking server.
* [ad-si/Perspec](https://github.com/ad-si/Perspec) - Scriptable desktop app to correct the perspective of images
* [2mol/pboy](https://github.com/2mol/pboy) - a small .pdf management tool with a command-line UI
* [taffybar/taffybar](https://github.com/taffybar/taffybar) - A gtk based status bar for tiling window managers such as XMonad
* [ChrisPenner/rasa](https://github.com/ChrisPenner/rasa) - Extremely modular text editor built in Haskell
* [xmonad/xmonad-contrib](https://github.com/xmonad/xmonad-contrib) - Contributed modules for xmonad
* [alexwl/haskell-code-explorer](https://github.com/alexwl/haskell-code-explorer) - Web application for exploring and understanding Haskell codebases
* [lettier/movie-monad](https://github.com/lettier/movie-monad) - :tv: A free and simple to use video player made with Haskell.
* [halogenandtoast/ArkhamHorror](https://github.com/halogenandtoast/ArkhamHorror) - An unofficial rules-compliant browser based version of Arkham Horror: The Card Game. Not produced, endorsed, or supported by, or affiliated with Fantasy Flight Games.
* [cdepillabout/termonad](https://github.com/cdepillabout/termonad) - Terminal emulator configurable in Haskell.
* [jtdaugherty/tart](https://github.com/jtdaugherty/tart) - Tart - draw ASCII art in the terminal with your mouse!
* [ozanvos/markup.rocks](https://github.com/ozanvos/markup.rocks) - Pandoc based document editor and converter in your browser.
* [theam/haskell-do](https://github.com/theam/haskell-do) - :pencil2: :bar_chart: - The Haskell code editor focused on interactive development.
* [Yvee1/hascard](https://github.com/Yvee1/hascard) - flashcard TUI with markdown cards
* [NorfairKing/smos](https://github.com/NorfairKing/smos) - A comprehensive self-management System
* [ad-si/TaskLite](https://github.com/ad-si/TaskLite) - The CLI task manager for power users
* [blitzcode/hue-dashboard](https://github.com/blitzcode/hue-dashboard) - A web interface for monitoring and controlling Philips Hue lights
* [ivanperez-keera/haskanoid](https://github.com/ivanperez-keera/haskanoid) - A free and open source breakout clone in Haskell using SDL and FRP, with Wiimote and Kinect support.
* [cmoog/traderjoes](https://github.com/cmoog/traderjoes) - Price tracking program and website for Trader Joe's, updated daily.
* [AllureOfTheStars/Allure](https://github.com/AllureOfTheStars/Allure) - Allure of the Stars is a near-future Sci-Fi roguelike and tactical squad combat game written in Haskell; please offer feedback, e.g., after trying out the web frontend version at
* [jlouis/combinatorrent](https://github.com/jlouis/combinatorrent) - A bittorrent client written in Haskell
* [jgoerzen/twidge](https://github.com/jgoerzen/twidge) - Command-line twitter/identica client [Haskell]
* [apauley/hledger-flow](https://github.com/apauley/hledger-flow) - An hledger/ledger-cli workflow focusing on automated statement import and classification
* [soywod/unfog](https://github.com/soywod/unfog) - ⏱ Minimalist CLI task & time manager, written in Haskell.
* [pmiddend/nixos-manager](https://github.com/pmiddend/nixos-manager) - Manage your NixOS packages and configuration via a simple, intuitive UI
* [haskell/play-haskell](https://github.com/haskell/play-haskell) - Haskell Playground
* [DataKinds/cherchord](https://github.com/DataKinds/cherchord) - 🎸 Find chords for any string instrument quicky & easily 🎸
* [zoomhub/zoomhub](https://github.com/zoomhub/zoomhub) - Share and view high-resolution images effortlessly
* [purebred-mua/purebred](https://github.com/purebred-mua/purebred) - A terminal based mail user agent based on notmuch
* [rnons/ted2srt](https://github.com/rnons/ted2srt) - Download bilingual subtitles of TED talks. https://ted2sub.org now.
* [wavewave/hoodle](https://github.com/wavewave/hoodle) - hoodle : A pen notetaking program written in haskell
* [vimus/vimus](https://github.com/vimus/vimus) - An MPD client with vim-like key bindings, written in Haskell
* [commercialhaskell/haskellers](https://github.com/commercialhaskell/haskellers) - haskellers.com site
* [dustin/gopro](https://github.com/dustin/gopro) - Tools for making the most out of GoPro Plus.
* [rodrigosetti/master-plan](https://github.com/rodrigosetti/master-plan) - Project Management for Hackers
* [pasqu4le/clifm](https://github.com/pasqu4le/clifm) - Command Line Interface File Manager
* [ianthehenry/basilica](https://github.com/ianthehenry/basilica) - It's kinda like a forum.
* [srid/slownews](https://github.com/srid/slownews) - 🐢 Bringing slow news for the nervous among us
* [lazamar/haskell-docs-cli](https://github.com/lazamar/haskell-docs-cli) - Browse Hackage from the terminal
* [gonimo/gonimo](https://github.com/gonimo/gonimo) - gonimo application back & front
* [aelve/guide](https://github.com/aelve/guide) - A workspace for research teams *(archived)*
* [hpdeifel/hledger-iadd](https://github.com/hpdeifel/hledger-iadd) - A terminal UI as drop-in replacement for hledger add.
* [RKlompUU/FPSheet](https://github.com/RKlompUU/FPSheet) - FPSheet: A Spreadsheet program with Haskell as the scripting language
* [2016rshah/heckle](https://github.com/2016rshah/heckle) - :black_nib: Jekyll in Haskell (feat. LaTeX)
* [snowdriftcoop/snowdrift](https://github.com/snowdriftcoop/snowdrift) - An **OUTDATED** mirror of Snowdrift.coop codebase. The active development is now at https://codeberg.org/snowdrift/snowdrift
* [haskellnews/haskellnews](https://github.com/haskellnews/haskellnews) - An aggregation of all online content related to Haskell.
* [TomSmeets/FractalArt](https://github.com/TomSmeets/FractalArt) - Generate colorful wallpapers!
* [agrafix/funblog](https://github.com/agrafix/funblog) - A simple blog software written in Haskell
* [ahushh/monaba](https://github.com/ahushh/monaba) - Imageboard engine written in Haskell and powered by Yesod
* [Haskell-Things/HSlice](https://github.com/Haskell-Things/HSlice) - HSlice - A Haskell based slicer for 3D printing.
* [balsoft/lambda-launcher](https://github.com/balsoft/lambda-launcher) - Application launcher in haskell. Mostly Just For Fun.
* [kowainik/issue-wanted](https://github.com/kowainik/issue-wanted) - 🏷 Web application to help beginners to start contributing into Haskell projects
* [BIYUEHU/SenaVN](https://github.com/BIYUEHU/SenaVN) - A terminal visual novel management, statistics and cloud syncing tool base on Haskell.

## Graphics and Media

### Graphics and Rendering

* [reanimate/reanimate](https://github.com/reanimate/reanimate) - Haskell library for building declarative animations based on SVG graphics
* [rgleichman/glance](https://github.com/rgleichman/glance) - A visual Haskell
* [sleexyz/hylogen](https://github.com/sleexyz/hylogen) - GLSL embedded in Haskell
* [ekmett/quine](https://github.com/ekmett/quine) - haskell, opengl, toy project
* [lambdacube3d/lambdacube-edsl](https://github.com/lambdacube3d/lambdacube-edsl) - Previous version of LambdaCube 3D as Embedded Domain Specific Language in Haskell. Check the latest system:
* [flannelhead/blackstar](https://github.com/flannelhead/blackstar) - A black hole raytracer written in Haskell
* [expipiplus1/vulkan](https://github.com/expipiplus1/vulkan) - Haskell bindings for Vulkan
* [haskell-opengl/OpenGL](https://github.com/haskell-opengl/OpenGL) - Haskell bindings to OpenGL
* [quchen/generative-art](https://github.com/quchen/generative-art) - I wanted to make a nicer sticker for Munihac, then things got out of hand.
* [Twinside/Rasterific](https://github.com/Twinside/Rasterific) - A drawing engine in Haskell
* [ekmett/gl](https://github.com/ekmett/gl) - Complete raw OpenGL bindings for Haskell
* [jaredloomis/andromeda](https://github.com/jaredloomis/andromeda) - OpenGL-based rendering engine with embedded language that compiles to GLSL.
* [ku-fpg/blank-canvas](https://github.com/ku-fpg/blank-canvas) - A Haskell API into HTML5 Canvas
* [bsl/GLFW-b](https://github.com/bsl/GLFW-b) - Haskell bindings to GLFW
* [anton-k/processing-for-haskell](https://github.com/anton-k/processing-for-haskell) - Graphics for kids and artists. Processing implemented in Haskell
* [achirkin/vulkan](https://github.com/achirkin/vulkan) - Low-level low-overhead haskell bindings to vulkan API
* [ivan-m/graphviz](https://github.com/ivan-m/graphviz) - Haskell bindings to the Graphviz toolkit
* [haskell-opengl/GLUT](https://github.com/haskell-opengl/GLUT) - Haskell bindings to GLUT

### Game Development

* [LambdaHack/LambdaHack](https://github.com/LambdaHack/LambdaHack) - Haskell game engine library for roguelike dungeon crawlers; please offer feedback, e.g., after trying out the sample game with the web frontend at
* [jonascarpay/apecs](https://github.com/jonascarpay/apecs) - a fast, extensible, type driven Haskell ECS framework for games
* [dbousamra/hnes](https://github.com/dbousamra/hnes) - :video_game: NES Emulator written in Haskell
* [haskell-game/sdl2](https://github.com/haskell-game/sdl2) - Haskell bindings to the SDL2 library
* [def-/gifstream](https://github.com/def-/gifstream) - Make interactive games in Haskell using GIF streams that can be shown in the web browser
* [jxv/dino-rush](https://github.com/jxv/dino-rush) - 🌋 Endless runner game
* [SimulaVR/godot-haskell](https://github.com/SimulaVR/godot-haskell) - Haskell bindings for GdNative
* [mchakravarty/HaskellSpriteKit](https://github.com/mchakravarty/HaskellSpriteKit) - Haskell binding to Apple's SpriteKit framework
* [haskell-game/tiny-games-hs](https://github.com/haskell-game/tiny-games-hs) - Haskell Tiny Game Jam
* [ocharles/zero-to-quake-3](https://github.com/ocharles/zero-to-quake-3) - Implementing Quake 3 in Haskell & Vulkan
* [aztecs-hs/aztecs](https://github.com/aztecs-hs/aztecs) - A modular game engine and ECS for Haskell
* [rainbyte/frag](https://github.com/rainbyte/frag) - Frag is a 3D first person shooting game written in Haskell, by Mun Hon Cheong
* [ChrisPenner/void-space](https://github.com/ChrisPenner/void-space) - Well-Typed Typing Tutor where you Type Types... in space... yup, you heard me
* [egonSchiele/chips](https://github.com/egonSchiele/chips) - A clone of Chips Challenge in Haskell
* [Anut-py/h-raylib](https://github.com/Anut-py/h-raylib) - Haskell bindings for raylib
* [typedbyte/switch](https://github.com/typedbyte/switch) - A library for interacting with Nintendo Switch controllers, written in Haskell.
* [MedeaMelana/Magic](https://github.com/MedeaMelana/Magic) - Haskell implementation of Magic: The Gathering
* [egonSchiele/dominion](https://github.com/egonSchiele/dominion) - A Dominion simulator in Haskell
* [drummyfish/haskell_game](https://github.com/drummyfish/haskell_game) - Wolfenstein 3D, ray-casting FPS game I make to learn Haskell. No libraries used, rendering is done in terminal.
* [smallhadroncollider/ascii-runner](https://github.com/smallhadroncollider/ascii-runner) - An infinite runner in your terminal
* [axionbuster/mmm](https://github.com/axionbuster/mmm) - Minecraft 1.21.4 Server (pure Haskell)
* [haskell-game/fungen](https://github.com/haskell-game/fungen) - A lightweight, cross-platform, OpenGL-based 2D game engine in Haskell
* [nandor/hcraft](https://github.com/nandor/hcraft) - Haskell clone of a certain game
* [I3ck/HGE2D](https://github.com/I3ck/HGE2D) - 2D game engine written in Haskell
* [gregorulm/h2048](https://github.com/gregorulm/h2048) - An implementation of the game 2048 in Haskell
* [alt-romes/ghengin](https://github.com/alt-romes/ghengin) - Ghengin: A vulkan-based, shader-centric, type-heavy, Haskell game engine
* [jasonstolaruk/CurryMUD](https://github.com/jasonstolaruk/CurryMUD) - A Multi-User Dungeon server in Haskell.
* [sharkdp/yinsh](https://github.com/sharkdp/yinsh) - A web-based version of the board game Yinsh
* [mchakravarty/lazy-lambda](https://github.com/mchakravarty/lazy-lambda) - Lazy Lambda — a Flappy Bird clone in Haskell with SpriteKit
* [asivitz/Hickory](https://github.com/asivitz/Hickory) - Tools for building 3D interactive programs in Haskell
* [hauxir/haskell-tetris](https://github.com/hauxir/haskell-tetris) - Tetris game written in Haskell using ncurses
* [robrix/starlight](https://github.com/robrix/starlight) - spaceships in space
* [lambdacube3d/lambdacube-quake3](https://github.com/lambdacube3d/lambdacube-quake3) - Quake 3 map viewer in Haskell using LambdaCube 3D
* [typedbyte/hagato](https://github.com/typedbyte/hagato) - Haskell Gamedev Toolkit, a library for developing games from scratch.
* [puffnfresh/sonic2](https://github.com/puffnfresh/sonic2) - Sonic the Hedgehog 2 in Haskell
* [seanhess/robotquest](https://github.com/seanhess/robotquest) - RobotQuest is a MMO, programming game. Instead of playing RobotQuest directly, you write a program that plays it for you. Your program communicates with the game server API over HTTP by sending and receiving JSON messages. Written in HTML, Haskell, with MongoDB
* [CGenie/haskell-snake](https://github.com/CGenie/haskell-snake) - Snake game implemetation in Haskell using SDL2

### Audio

* [tidalcycles/Tidal](https://github.com/tidalcycles/Tidal) - Pattern language *(archived)*
* [DimaSamoz/mezzo](https://github.com/DimaSamoz/mezzo) - A Haskell library for typesafe music composition
* [spell-music/csound-expression](https://github.com/spell-music/csound-expression) - Haskell Framework for Electronic Music
* [mtolly/onyx](https://github.com/mtolly/onyx) - Toolkit for converting and building songs for Rock Band, Guitar Hero, Clone Hero, and other similar rhythm games
* [music-suite/music-suite](https://github.com/music-suite/music-suite) - Music in Haskell
* [donya/Kulitta](https://github.com/donya/Kulitta) - A Haskell-based library for algorithmic and automated composition. This library was the subject of my dissertation at Yale university and is the subject of my ongoing work.
* [5outh/Bang](https://github.com/5outh/Bang) - A Drum Machine DSL for Haskell
* [Euterpea/HSoM](https://github.com/Euterpea/HSoM) - Supporting Impelementation for Haskell School of Music
* [lvm/tidal-drum-patterns](https://github.com/lvm/tidal-drum-patterns) - TidalCycles / Haskell modules of drum patterns.
* [elaforge/karya](https://github.com/elaforge/karya) - music sequencer and generalized notation

## Concurrency and Performance

### Concurrency and Parallelism

* [facebook/Haxl](https://github.com/facebook/Haxl) - A Haskell library that simplifies access to remote data, such as databases or web-based services.
* [composewell/streamly](https://github.com/composewell/streamly) - High performance, streaming and concurrent functional programming in Haskell
* [transient-haskell/transient](https://github.com/transient-haskell/transient) - A full stack, reactive architecture for general purpose programming. Algebraic and monadically composable primitives for concurrency, parallelism, event handling, transactions, multithreading, Web, and distributed computing with complete de-inversion of control (No callbacks, no blocking, pure state)
* [jberryman/unagi-chan](https://github.com/jberryman/unagi-chan) - A haskell library implementing fast and scalable concurrent queues for x86, with a Chan-like API
* [haskell/stm](https://github.com/haskell/stm) - Software Transactional Memory
* [rrnewton/haskell-lockfree](https://github.com/rrnewton/haskell-lockfree) - A collection of different packages for CAS based data structures.
* [awkward-squad/ki](https://github.com/awkward-squad/ki) - A structured concurrency library
* [iu-parfunc/lvars](https://github.com/iu-parfunc/lvars) - The LVish Haskell library
* [roman/Haskell-capataz](https://github.com/roman/Haskell-capataz) - OTP-like supervision trees in Haskell

### Performance and Optimization

* [AccelerateHS/accelerate](https://github.com/AccelerateHS/accelerate) - Embedded language for high-performance array computations
* [haskell/criterion](https://github.com/haskell/criterion) - A powerful but simple library for measuring the performance of Haskell code.
* [AccelerateHS/accelerate-llvm](https://github.com/AccelerateHS/accelerate-llvm) - LLVM backend for Accelerate
* [composewell/streaming-benchmarks](https://github.com/composewell/streaming-benchmarks) - Benchmarks to compare Haskell streaming library performance
* [vincenthz/hs-gauge](https://github.com/vincenthz/hs-gauge) - Lean Haskell Benchmarking *(archived)*
* [mrkkrp/zip](https://github.com/mrkkrp/zip) - Efficient library for manipulating zip archives
* [nh2/haskell-cpu-instruction-counter](https://github.com/nh2/haskell-cpu-instruction-counter) - Measuring CPU instructions in Haskell using Linux Performance Counters
* [Bodigrim/tasty-bench](https://github.com/Bodigrim/tasty-bench) - Featherlight benchmark framework, drop-in replacement for criterion and gauge.
* [ezyang/compact](https://github.com/ezyang/compact) - Compact regions library for Haskell
* [tmcdonell/cuda](https://github.com/tmcdonell/cuda) - Haskell FFI bindings to CUDA
* [IFCA-Advanced-Computing/opencl](https://github.com/IFCA-Advanced-Computing/opencl) - Haskell high-level wrapper for OpenCL *(archived)*

## Testing and Quality

### Testing

* [nick8325/quickcheck](https://github.com/nick8325/quickcheck) - Automatic testing of Haskell programs.
* [hspec/hspec](https://github.com/hspec/hspec) - A Testing Framework for Haskell
* [hedgehogqa/haskell-hedgehog](https://github.com/hedgehogqa/haskell-hedgehog) - Release with confidence, state-of-the-art property testing for Haskell.
* [UnkindPartition/tasty](https://github.com/UnkindPartition/tasty) - Modern and extensible testing framework for Haskell
* [sol/doctest](https://github.com/sol/doctest) - An implementation of Python's doctest for Haskell
* [advancedtelematic/quickcheck-state-machine](https://github.com/advancedtelematic/quickcheck-state-machine) - Test monadic programs using state machine based models *(archived)*
* [barrucadu/dejafu](https://github.com/barrucadu/dejafu) - Systematic concurrency testing meets Haskell.
* [nomeata/inspection-testing](https://github.com/nomeata/inspection-testing) - Inspection Testing for Haskell
* [simonmichael/shelltestrunner](https://github.com/simonmichael/shelltestrunner) - Easy, repeatable testing of CLI programs/commands
* [fakedata-haskell/fakedata](https://github.com/fakedata-haskell/fakedata) - Haskell Library for producing quality fake data
* [Bodigrim/smallcheck](https://github.com/Bodigrim/smallcheck) - Test your Haskell code by exhaustively checking its properties
* [hspec/HUnit](https://github.com/hspec/HUnit) - A unit testing framework for Haskell
* [NorfairKing/sydtest](https://github.com/NorfairKing/sydtest) - A modern testing framework for Haskell with good defaults and advanced testing features.
* [Lysxia/generic-random](https://github.com/Lysxia/generic-random) - Generic random generators
* [rudymatela/fitspec](https://github.com/rudymatela/fitspec) - refine properties for testing Haskell programs
* [testcontainers/testcontainers-hs](https://github.com/testcontainers/testcontainers-hs) - Docker containers for your integration tests! http://hackage.haskell.org/package/testcontainers
* [codedownio/sandwich](https://github.com/codedownio/sandwich) - Yet another test framework for Haskell.
* [cjdev2/monad-mock](https://github.com/cjdev2/monad-mock) - A Haskell package that provides a monad transformer for mocking mtl-style typeclasses
* [ocharles/assert-explainer](https://github.com/ocharles/assert-explainer) - Py.test style assertions in Haskell
* [killy971/hpc-coveralls](https://github.com/killy971/hpc-coveralls) - coveralls.io support for haskell code coverage with hpc
* [cjdev/monad-mock](https://github.com/cjdev/monad-mock) - A Haskell package that provides a monad transformer for mocking mtl-style typeclasses

## Utilities

### Command Line Tools

* [maralorn/nix-output-monitor](https://github.com/maralorn/nix-output-monitor) - Pipe your nix-build output through the nix-output-monitor a.k.a nom to get additional information while building.
* [pcapriotti/optparse-applicative](https://github.com/pcapriotti/optparse-applicative) - Applicative option parser
* [kowainik/summoner](https://github.com/kowainik/summoner) - 🔮 🔧 Tool for scaffolding batteries-included production-level Haskell projects
* [chrisdone-archive/jl](https://github.com/chrisdone-archive/jl) - Functional sed for JSON *(archived)*
* [gelisam/hawk](https://github.com/gelisam/hawk) - Haskell text processor for the command-line
* [Gandalf-/coreutils](https://github.com/Gandalf-/coreutils) - Unix core utilities implemented in Haskell
* [passy/givegif](https://github.com/passy/givegif) - GIFs on the command line
* [Gabriella439/optparse-generic](https://github.com/Gabriella439/optparse-generic) - Auto-generate a command-line parser for your datatype
* [fujimura/hi](https://github.com/fujimura/hi) - Generate scaffold for a Haskell project
* [chshersh/iris](https://github.com/chshersh/iris) - 🌈 Haskell CLI Framework supporting Command Line Interface Guidelines
* [ix/calico](https://github.com/ix/calico) - cat, but for colors 😼
* [tfausak/github-release](https://github.com/tfausak/github-release) - :octocat: Upload files to GitHub releases.
* [psibi/tldr-hs](https://github.com/psibi/tldr-hs) - Haskell tldr client
* [andys8/git-brunch](https://github.com/andys8/git-brunch) - Git branch checkout menu
* [ndmitchell/cmdargs](https://github.com/ndmitchell/cmdargs) - Haskell library for command line argument processing
* [Nike-Inc/bartlett](https://github.com/Nike-Inc/bartlett) - A simple Jenkins command line client to serve your needs.
* [kowainik/hit-on](https://github.com/kowainik/hit-on) - :octocat: Kowainik Git Workflow Helper Tool
* [thumphries/hgrep](https://github.com/thumphries/hgrep) - Search Haskell source code from the command line *(archived)*
* [vmchale/command-line-tweeter](https://github.com/vmchale/command-line-tweeter) - Tweets in from a pipe *(archived)*
* [cpennington/h4sh](https://github.com/cpennington/h4sh) - Fork of Don Stewarts h4sh haskell shell scripts
* [Voyrox/Zippy](https://github.com/Voyrox/Zippy) - Zippy is a lightweight CLI that watches a file or directory and reruns your command the moment you save. It keeps your stdout clean, logs to stderr with levels, and stays out of your way during the edit -> build -> run loop.

### Logging and Configuration

* [co-log/co-log](https://github.com/co-log/co-log) - 📓 Flexible and configurable modern #Haskell logging framework
* [Soostone/katip](https://github.com/Soostone/katip) - A structured logging framework for Haskell
* [kazu-yamamoto/logger](https://github.com/kazu-yamamoto/logger) - A fast logging system for Haskell
* [dmjio/envy](https://github.com/dmjio/envy) - :angry: Environmentally friendly environment variables
* [bos/configurator](https://github.com/bos/configurator) - A Haskell library supporting flexible, dynamic file-based configuration.
* [willdonnelly/dyre](https://github.com/willdonnelly/dyre) - A Dynamic Reconfiguration Library for Haskell Programs
* [haskell-hvr/hslogger](https://github.com/haskell-hvr/hslogger) - Logging framework for Haskell
* [stackbuilders/dotenv-hs](https://github.com/stackbuilders/dotenv-hs) - Load environment variables from dotenv files for Haskell

### Text Processing

* [jgm/pandoc](https://github.com/jgm/pandoc) - Universal markup converter
* [lierdakil/pandoc-crossref](https://github.com/lierdakil/pandoc-crossref) - Pandoc filter for cross-references
* [mrkkrp/megaparsec](https://github.com/mrkkrp/megaparsec) - Industrial-strength monadic parser combinator library
* [haskell/attoparsec](https://github.com/haskell/attoparsec) - A fast Haskell library for parsing ByteStrings
* [haskell/text](https://github.com/haskell/text) - Haskell library for space- and time-efficient operations over Unicode text.
* [jgm/texmath](https://github.com/jgm/texmath) - A Haskell library for converting LaTeX math to MathML.
* [ollef/Earley](https://github.com/ollef/Earley) - Parsing all context-free grammars using Earley's algorithm in Haskell.
* [haskell-prettyprinter/prettyprinter](https://github.com/haskell-prettyprinter/prettyprinter) - A modern, extensible and well-documented prettyprinter.
* [cdepillabout/pretty-simple](https://github.com/cdepillabout/pretty-simple) - pretty-printer for Haskell data types that have a Show instance
* [jgm/skylighting](https://github.com/jgm/skylighting) - A Haskell syntax highlighting library with tokenizers derived from KDE syntax highlighting descriptions
* [Daniel-Diaz/HaTeX](https://github.com/Daniel-Diaz/HaTeX) - The Haskell LaTeX library. *(archived)*
* [jgm/citeproc](https://github.com/jgm/citeproc) - CSL citation processing library in Haskell
* [Yuras/pdf-toolbox](https://github.com/Yuras/pdf-toolbox) - A collection of tools for processing PDF files in Haskell
* [dahlia/seonbi](https://github.com/dahlia/seonbi) - SmartyPants for Korean language
* [sol/markdown-unlit](https://github.com/sol/markdown-unlit) - Literate Haskell support for Markdown
* [jgm/commonmark-hs](https://github.com/jgm/commonmark-hs) - Pure Haskell commonmark parsing library, designed to be flexible and extensible
* [mmark-md/mmark](https://github.com/mmark-md/mmark) - Strict markdown processor for writers
* [kosmikus/lhs2tex](https://github.com/kosmikus/lhs2tex) - Preprocessor for typesetting Haskell sources with LaTeX
* [JustusAdam/mustache](https://github.com/JustusAdam/mustache) - Haskell implementation of mustache templates
* [Bodigrim/linear-builder](https://github.com/Bodigrim/linear-builder) - Strict Text and ByteString builder, which hides mutable buffer behind linear types and takes amortized linear time.
* [ncaq/dic-nico-intersection-pixiv](https://github.com/ncaq/dic-nico-intersection-pixiv) - ニコニコ大百科とピクシブ百科事典の共通部分のIME辞書
* [ShabbyX/libpandoc](https://github.com/ShabbyX/libpandoc) - C bindings to Pandoc, a markup converter library written in Haskell.
* [snapframework/heist](https://github.com/snapframework/heist) - An xhtml-based templating engine, allowing Haskell functions to be bound to XML tags.
* [lymar/hastache](https://github.com/lymar/hastache) - Haskell implementation of Mustache template *(archived)*
* [bawolk/hsp](https://github.com/bawolk/hsp) - Haskell command line text stream processor
* [tdammers/ginger](https://github.com/tdammers/ginger) - A Haskell implementation of the Jinja template language.
* [haskell-github-trust/replace-megaparsec](https://github.com/haskell-github-trust/replace-megaparsec) - Stream editing with Haskell Megaparsec parsers
* [jgm/typst-hs](https://github.com/jgm/typst-hs) - Haskell library for parsing and evaluating typst
* [haskell/pretty](https://github.com/haskell/pretty) - Haskell Pretty-printer library
* [guibou/PyF](https://github.com/guibou/PyF) - Haskell QuasiQuoter for String Formatting
* [mrkkrp/modern-uri](https://github.com/mrkkrp/modern-uri) - Modern library for working with URIs
* [lukasmartinelli/hwk](https://github.com/lukasmartinelli/hwk) - A Haskell based awk and sed alternative *(archived)*

### Files and Operating System

* [haskell-fswatch/hfsnotify](https://github.com/haskell-fswatch/hfsnotify) - Unified Haskell interface for basic file system notifications
* [haskell/win32](https://github.com/haskell/win32) - Haskell support for the Win32 API
* [snoyberg/file-embed](https://github.com/snoyberg/file-embed) - Use Template Haskell to embed file contents directly.
* [ZHaskell/z-io](https://github.com/ZHaskell/z-io) - IO lib for haskell
* [haskell/filepath](https://github.com/haskell/filepath) - Haskell FilePath core library

### Automation and Scripting

* [Gabriella439/turtle](https://github.com/Gabriella439/turtle) - Shell programming, Haskell style
* [chrisdone/hell](https://github.com/chrisdone/hell) - Haskell-based shell scripting language
* [gregwebs/Shelly.hs](https://github.com/gregwebs/Shelly.hs) - Haskell shell scripting
* [luke-clifton/shh](https://github.com/luke-clifton/shh) - Simple shell like scripting from Haskell
* [iostreamer-X/FuncShell](https://github.com/iostreamer-X/FuncShell) - Improve your shell by making it functional through Haskell! (An update to Awkward)
* [lambdabot/lambdabot](https://github.com/lambdabot/lambdabot) - A friendly IRC bot and apprentice coder, written in Haskell.
* [tsoding/HyperNerd](https://github.com/tsoding/HyperNerd) - Total Surveillance Automatic Ban Machine for Twitch and Discord
* [schell/steeloverseer](https://github.com/schell/steeloverseer) - A file watcher and development tool.
* [simmsb/calamity](https://github.com/simmsb/calamity) - A library for writing discord bots in haskell
* [fizruk/telegram-bot-simple](https://github.com/fizruk/telegram-bot-simple) - Easy to use library for building Telegram bots in Haskell.
* [y-taka-23/thank-you-stars](https://github.com/y-taka-23/thank-you-stars) - Give your dependencies stars on GitHub! 🌟
* [kowainik/shellmet](https://github.com/kowainik/shellmet) - 🐚 Out of the shell solution for scripting in Haskell
* [randomthought/xmonad-config](https://github.com/randomthought/xmonad-config) - xmonad config
* [jekor/hesh](https://github.com/jekor/hesh) - Haskell Extensible Shell
* [AtifChy/xmonad](https://github.com/AtifChy/xmonad) - my Xmonad configuration
* [TiltMeSenpai/Discord.hs](https://github.com/TiltMeSenpai/Discord.hs) - Have you heard of our lord and savior Haskell? *(archived)*

### General Purpose Libraries

* [ekmett/lens](https://github.com/ekmett/lens) - Lenses, Folds, and Traversals - Join us on web.libera.chat #haskell-lens
* [reflex-frp/reflex](https://github.com/reflex-frp/reflex) - Interactive programs without callbacks or side-effects. Functional Reactive Programming (FRP) uses composable events and time-varying values to describe interactive systems as pure functions. Just like other pure functional code, functional reactive code is easier to get right on the first try, maintain, and reuse.
* [commercialhaskell/rio](https://github.com/commercialhaskell/rio) - A standard library for Haskell
* [snowleopard/alga](https://github.com/snowleopard/alga) - Algebraic graphs
* [kowainik/relude](https://github.com/kowainik/relude) - 🌀 Safe, performant, user-friendly and lightweight Haskell standard library
* [fused-effects/fused-effects](https://github.com/fused-effects/fused-effects) - A fast, flexible, fused effect system for Haskell
* [hasura/eff](https://github.com/hasura/eff) - 🚧 a work in progress effect system for Haskell 🚧
* [HeinrichApfelmus/reactive-banana](https://github.com/HeinrichApfelmus/reactive-banana) - Library for functional reactive programming in Haskell.
* [Gabriella439/pipes](https://github.com/Gabriella439/pipes) - Compositional pipelines
* [ivanperez-keera/Yampa](https://github.com/ivanperez-keera/Yampa) - Functional Reactive Programming domain-specific language for efficient hybrid systems
* [haskell-effectful/effectful](https://github.com/haskell-effectful/effectful) - An easy to use, fast extensible effects library with seamless integration with the existing Haskell ecosystem.
* [haskell-foundation/foundation](https://github.com/haskell-foundation/foundation) - Empire strikes back *(archived)*
* [protolude/protolude](https://github.com/protolude/protolude) - A sensible starting Prelude template.
* [haskell/mtl](https://github.com/haskell/mtl) - The Monad Transformer Library
* [tweag/linear-base](https://github.com/tweag/linear-base) - Standard library for linear types in Haskell.
* [stevenfontanella/microlens](https://github.com/stevenfontanella/microlens) - A lightweight (but compatible with ‘lens’) lenses library
* [goldfirere/singletons](https://github.com/goldfirere/singletons) - Fake dependent types in Haskell using singletons
* [dmbarbour/Sirea](https://github.com/dmbarbour/Sirea) - Simply Reactive! Declarative orchestration in Haskell using RDP
* [VinylRecords/Vinyl](https://github.com/VinylRecords/Vinyl) - Extensible Records for Haskell. Pull requests welcome! Come visit us on #vinyl on freenode.
* [lexi-lambda/freer-simple](https://github.com/lexi-lambda/freer-simple) - A friendly effect system for Haskell
* [evertedsphere/silica](https://github.com/evertedsphere/silica) - optics for Haskell with the most amazing type errors you've seen *(archived)*
* [ivanperez-keera/dunai](https://github.com/ivanperez-keera/dunai) - Classic FRP, Arrowized FRP, Reactive Programming, and Stream Programming, all via Monadic Stream Functions
* [tweag/capability](https://github.com/tweag/capability) - Extensional capabilities and deriving combinators
* [tfausak/flow](https://github.com/tfausak/flow) - :droplet: Write more understandable Haskell.
* [haskell/fgl](https://github.com/haskell/fgl) - A Functional Graph Library for Haskell
* [sayo-hs/heftia](https://github.com/sayo-hs/heftia) - A theory‑backed, type‑safe algebraic effects
* [chrisdone-archive/dynamic](https://github.com/chrisdone-archive/dynamic) - Dynamic typing in Haskell *(archived)*
* [serokell/universum](https://github.com/serokell/universum) - :milky_way: Prelude written in @Serokell
* [mstksg/auto](https://github.com/mstksg/auto) - Haskell DSL and platform providing denotational, compositional api for discrete-step, locally stateful, interactive programs, games & automations. http://hackage.haskell.org/package/auto
* [suhailshergill/extensible-effects](https://github.com/suhailshergill/extensible-effects) - Extensible Effects: An Alternative to Monad Transformers
* [Gabriella439/foldl](https://github.com/Gabriella439/foldl) - Composable, streaming, and efficient left folds
* [well-typed/generics-sop](https://github.com/well-typed/generics-sop) - Generic Programming using True Sums of Products
* [turion/rhine](https://github.com/turion/rhine) - Haskell Functional Reactive Programming framework with type-level clocks
* [lexi-lambda/eff](https://github.com/lexi-lambda/eff) - 🚧 a work in progress effect system for Haskell 🚧
* [haskell/critbit](https://github.com/haskell/critbit) - A Haskell implementation of crit-bit trees.
* [gregorycollins/hashtables](https://github.com/gregorycollins/hashtables) - Mutable hash tables for Haskell, in the ST monad
* [fumieval/extensible](https://github.com/fumieval/extensible) - Extensible records, variants, structs, effects, tangles
* [marcosh/crem](https://github.com/marcosh/crem) - Compositional Representable Executable Machines
* [target/row-types](https://github.com/target/row-types) - A Haskell library for open records and variants using closed type families and type literals *(archived)*
* [ChrisPenner/eve](https://github.com/ChrisPenner/eve) - An extensible event-driven application framework in haskell
* [coclique/cleff](https://github.com/coclique/cleff) - Fast and concise effect handlers
* [ekmett/reflection](https://github.com/ekmett/reflection) - Reifies arbitrary Haskell terms into types that can be reflected back into terms
* [ZHaskell/stdio](https://github.com/ZHaskell/stdio) - Haskell Standard Input and Output
* [dorchard/effect-monad](https://github.com/dorchard/effect-monad) - Provides 'graded monads' and 'parameterised monads' to Haskell, enabling fine-grained reasoning about effects.
* [kowainik/typerep-map](https://github.com/kowainik/typerep-map) - ⚡️Efficient implementation of Map with types as keys
* [snapframework/io-streams](https://github.com/snapframework/io-streams) - Simple, composable, and easy-to-use stream I/O for Haskell
* [monadfix/named](https://github.com/monadfix/named) - Named parameters (keyword arguments) for Haskell
* [ndmitchell/extra](https://github.com/ndmitchell/extra) - Extra Haskell functions
* [owickstrom/motor](https://github.com/owickstrom/motor) - Type-safe effectful state machines in Haskell
* [pa-ba/compdata](https://github.com/pa-ba/compdata) - Haskell library implementing "Data Types a la Carte"
* [Lysxia/first-class-families](https://github.com/Lysxia/first-class-families) - First-class type families
* [haskell-hvr/missingh](https://github.com/haskell-hvr/missingh) - Utility library [Haskell]
* [sellout/yaya](https://github.com/sellout/yaya) - Yet another … yet another recursion scheme library for Haskell
* [xnning/EvEff](https://github.com/xnning/EvEff) - Efficient Haskell effect handlers based on evidence translation.
* [agrafix/superrecord](https://github.com/agrafix/superrecord) - Haskell: Supercharged anonymous records
* [HeinrichApfelmus/operational](https://github.com/HeinrichApfelmus/operational) - Implement monads by specifying instructions and their desired operational semantics.
* [ndmitchell/uniplate](https://github.com/ndmitchell/uniplate) - Haskell library for simple, concise and fast generic operations.
* [tfausak/witch](https://github.com/tfausak/witch) - :mage_woman: Convert values from one type into another.
* [tfausak/rampart](https://github.com/tfausak/rampart) - :european_castle: Determine how intervals relate to each other.
* [ekmett/comonad](https://github.com/ekmett/comonad) - Haskell 98 comonads
* [kowainik/validation-selective](https://github.com/kowainik/validation-selective) - 💂‍♂️ Lightweight pure validation based on Applicative and Selective functors
* [NoRedInk/haskell-libraries](https://github.com/NoRedInk/haskell-libraries) - Libraries we use at NoRedInk
* [ekmett/contravariant](https://github.com/ekmett/contravariant) - Haskell 98 contravariant functors
* [ekmett/profunctors](https://github.com/ekmett/profunctors) - Haskell 98 Profunctors
* [kowainik/prolens](https://github.com/kowainik/prolens) - 👓 Profunctor based lightweight implementation of Lenses
* [turion/essence-of-live-coding](https://github.com/turion/essence-of-live-coding) - Universal Live Coding & Functional Reactive Programming Framework
* [sebastiaanvisser/fclabels](https://github.com/sebastiaanvisser/fclabels) - First class composable record labels for Haskell.
* [jaspervdj/psqueues](https://github.com/jaspervdj/psqueues) - Priority Search Queues in three different flavors for Haskell
* [spl/dlist](https://github.com/spl/dlist) - Difference lists in Haskell
* [dorchard/type-level-sets](https://github.com/dorchard/type-level-sets) - Type-level sets for Haskell (with value-level counterparts and various operations)
* [ekmett/structures](https://github.com/ekmett/structures) - A playground for working on advanced data structures in Haskell
* [Gabriella439/Haskell-Errors-Library](https://github.com/Gabriella439/Haskell-Errors-Library) - Type-safe error handling
* [Gabriella439/Haskell-MVC-Library](https://github.com/Gabriella439/Haskell-MVC-Library) - Model-view-controller
* [haskell-hvr/uuid](https://github.com/haskell-hvr/uuid) - A Haskell library for creating, printing and parsing UUIDs
* [IxpertaSolutions/freer-effects](https://github.com/IxpertaSolutions/freer-effects) - An implementation of "Freer Monads, More Extensible Effects". *(archived)*
* [kowainik/treap](https://github.com/kowainik/treap) - :leaves: :deciduous_tree: :fallen_leaf: Efficient implementation of the implicit treap data structure
* [ekmett/semigroups](https://github.com/ekmett/semigroups) - Haskell 98 semigroups
* [kowainik/membrain](https://github.com/kowainik/membrain) - 🧠 Type-safe memory units
* [Gabriella439/list-transformer](https://github.com/Gabriella439/list-transformer) - List monad transformer
* [basvandijk/monad-control](https://github.com/basvandijk/monad-control) - Lift control operations, like exception catching, through monad transformers
* [kowainik/eio](https://github.com/kowainik/eio) - 🎯 IO with Exceptions tracked on the type-level
* [mrkkrp/facts](https://github.com/mrkkrp/facts) - Refined types
* [etorreborre/registry](https://github.com/etorreborre/registry) - Dependency injection in Haskell

## Science and Math

### Mathematics

* [tweag/monad-bayes](https://github.com/tweag/monad-bayes) - A library for probabilistic programming in Haskell.
* [lehins/massiv](https://github.com/lehins/massiv) - Efficient Haskell Arrays featuring Parallel computation
* [haskell/statistics](https://github.com/haskell/statistics) - A fast, high quality library for computing with statistics in Haskell.
* [ekmett/linear](https://github.com/ekmett/linear) - Low-dimensional linear algebra primitives for Haskell.
* [CyberCat-Institute/open-game-engine](https://github.com/CyberCat-Institute/open-game-engine) - Haskell implementation of open games
* [tromp/ChessPositionRanking](https://github.com/tromp/ChessPositionRanking) - Software suite for ranking chess positions and accurately estimating the number of legal chess positions
* [ekmett/hask](https://github.com/ekmett/hask) - Category theory for Haskell with a lens flavor (you need GHC 7.8.3, not 7.8.2 to build this!)
* [wellposed/numerical](https://github.com/wellposed/numerical) - Numerical is the core library for Numerical Haskell
* [noinia/hgeometry](https://github.com/noinia/hgeometry) - HGeometry is a library for computing with geometric objects in Haskell. It defines basic geometric types and primitives, and it implements some geometric data structures and algorithms.
* [goldfirere/units](https://github.com/goldfirere/units) - The home of the units Haskell package
* [ocramz/sparse-linear-algebra](https://github.com/ocramz/sparse-linear-algebra) - Numerical computation in native Haskell
* [mvr/at](https://github.com/mvr/at) - Effective Algebraic Topology in Haskell
* [bolt12/laop](https://github.com/bolt12/laop) - Linear Algebra of Programming - Algebraic Matrices in Haskell
* [basvandijk/scientific](https://github.com/basvandijk/scientific) - Arbitrary-precision floating-point numbers represented using scientific notation
* [colah/HaskSymb](https://github.com/colah/HaskSymb) - An Experiment in Haskell Symbolic Algebra
* [tonyday567/numhask](https://github.com/tonyday567/numhask) - A haskell numeric prelude, providing a clean structure for numbers and operations that combine them.
* [probcomp/adev](https://github.com/probcomp/adev) - Haskell prototype to accompany the paper "ADEV: Sound Automatic Differentiation of Expected Values of Probabilistic Programs"
* [Bodigrim/poly](https://github.com/Bodigrim/poly) - Fast polynomial arithmetic in Haskell (dense and sparse, univariate and multivariate, usual and Laurent)
* [paulrzcz/hquantlib](https://github.com/paulrzcz/hquantlib) - HQuantLib, financial math in Haskell
* [lm-cyber/symkell](https://github.com/lm-cyber/symkell) - A computer algebra system written in Haskell

### Scientific Computing

* [Haskell-Things/ImplicitCAD](https://github.com/Haskell-Things/ImplicitCAD) - A math-inspired CAD program in haskell. CSG, bevels, and shells; 2D & 3D geometry; 2D gcode generation...
* [bollu/cellularAutomata](https://github.com/bollu/cellularAutomata) - a collection of cellular automata written in Haskell with Diagrams
* [JacquesCarette/Drasil](https://github.com/JacquesCarette/Drasil) - Generate all the things (focusing on research software)
* [ngless-toolkit/ngless](https://github.com/ngless-toolkit/ngless) - NGLess: NGS with less work
* [boundedvariation/quantfin](https://github.com/boundedvariation/quantfin) - quant finance in pure haskell
* [acowley/roshask](https://github.com/acowley/roshask) - Haskell client library for the ROS robotics framework.
* [joe-warren/opencascade-hs](https://github.com/joe-warren/opencascade-hs) - Haskell Bindings for the OpenCASCADE CAD Kernel + A Declarative CAD/Solid Modeling Library
* [alexandersgreen/qio-haskell](https://github.com/alexandersgreen/qio-haskell) - The Quantum IO Monad, implemented in Haskell
* [blarney-lang/blarney](https://github.com/blarney-lang/blarney) - Haskell library for hardware description
* [adamwalker/sdr](https://github.com/adamwalker/sdr) - Software defined radio library in Haskell
* [chris-taylor/Classical-Mechanics](https://github.com/chris-taylor/Classical-Mechanics) - Haskell toolbox for research and teaching in classical mechanics. Includes modules for symbolic algebra and automatic differentiation.
* [jwiegley/control-theory](https://github.com/jwiegley/control-theory) - Control theory in Haskell: Data structures, algorithms and adapters
* [LeventErkok/hArduino](https://github.com/LeventErkok/hArduino) - Control your Arduino board from Haskell, using the Firmata protocol
* [Chase-C/Flocking-Simulation](https://github.com/Chase-C/Flocking-Simulation) - A 3D Boids-like flocking simulation coded in Haskell.

### Formal Methods and Proofs

* [ucsd-progsys/liquidhaskell](https://github.com/ucsd-progsys/liquidhaskell) - Liquid Types For Haskell
* [Copilot-Language/copilot](https://github.com/Copilot-Language/copilot) - A stream-based runtime-verification framework for generating hard real-time C code.
* [rzk-lang/rzk](https://github.com/rzk-lang/rzk) - An experimental proof assistant based on a type theory for synthetic ∞-categories.
* [LeventErkok/sbv](https://github.com/LeventErkok/sbv) - SMT Based Verification in Haskell. Express properties about Haskell programs and automatically prove them using SMT solvers.
* [runtimeverification/haskell-backend](https://github.com/runtimeverification/haskell-backend) - The symbolic execution engine powering the K Framework
* [awakesecurity/spectacle](https://github.com/awakesecurity/spectacle) - Embedded specification language & model checker in Haskell
* [mit-plv/riscv-semantics](https://github.com/mit-plv/riscv-semantics) - A formal semantics of the RISC-V ISA in Haskell
* [vehicle-lang/vehicle](https://github.com/vehicle-lang/vehicle) - A toolkit for enforcing logical specifications on neural networks
* [ekmett/linear-logic](https://github.com/ekmett/linear-logic) - They see me rollin'. They're Heyting. -- Chamillionaire, 2005
* [lsrcz/grisette](https://github.com/lsrcz/grisette) - A monadic library for symbolic evaluation
* [TOTBWF/refinery](https://github.com/TOTBWF/refinery) - ⛏️ A refinement proof framework for haskell

## Other

* [github/semantic](https://github.com/github/semantic) - Parsing, analyzing, and comparing source code across many languages *(archived)*
* [elm/compiler](https://github.com/elm/compiler) - Compiler for Elm, a functional language for reliable webapps.
* [carp-lang/Carp](https://github.com/carp-lang/Carp) - A statically typed lisp, without a GC, for real-time applications.
* [facebook/duckling](https://github.com/facebook/duckling) - Language, engine, and tooling for expressing, testing, and evaluating composable language rules on input strings.
* [system-f/fp-course](https://github.com/system-f/fp-course) - Functional Programming Course
* [HigherOrderCO/Kind](https://github.com/HigherOrderCO/Kind) - A modern proof language
* [idris-lang/Idris-dev](https://github.com/idris-lang/Idris-dev) - A Dependently Typed Functional Programming Language *(archived)*
* [b3nj5m1n/xdg-ninja](https://github.com/b3nj5m1n/xdg-ninja) - A shell script which checks your $HOME for unwanted files and directories.
* [SimulaVR/Simula](https://github.com/SimulaVR/Simula) - Linux VR Desktop
* [IntersectMBO/cardano-node](https://github.com/IntersectMBO/cardano-node) - The core component that is used to participate in a Cardano decentralised blockchain.
* [crytic/echidna](https://github.com/crytic/echidna) - Ethereum smart contract fuzzer
* [agda/agda](https://github.com/agda/agda) - Agda is a dependently typed programming language / interactive theorem prover.
* [diku-dk/futhark](https://github.com/diku-dk/futhark) - :boom::computer::boom: A data-parallel functional programming language
* [nammayatri/nammayatri](https://github.com/nammayatri/nammayatri) - A Direct-to-Driver open mobility platform powering the next-generation of mobility applications in India.
* [jgm/gitit](https://github.com/jgm/gitit) - A wiki using HAppS, pandoc, and git
* [jameysharp/corrode](https://github.com/jameysharp/corrode) - C to Rust translator
* [dapphub/dapptools](https://github.com/dapphub/dapptools) - Dapp, Seth, Hevm, and more
* [lamdu/lamdu](https://github.com/lamdu/lamdu) - lamdu - towards the next generation IDE
* [BurntSushi/erd](https://github.com/BurntSushi/erd) - Translates a plain text description of a relational database schema to a graphical entity-relationship diagram.
* [nmattia/niv](https://github.com/nmattia/niv) - Easy dependency management for Nix projects
* [olivierverdier/zsh-git-prompt](https://github.com/olivierverdier/zsh-git-prompt) - Informative git prompt for zsh
* [mikeizbicki/HLearn](https://github.com/mikeizbicki/HLearn) - Homomorphic machine learning
* [IntersectMBO/plutus](https://github.com/IntersectMBO/plutus) - The Plutus language implementation and tools
* [srid/neuron](https://github.com/srid/neuron) - Future-proof note-taking and publishing based on Zettelkasten (superseded by Emanote: https://github.com/srid/emanote)
* [erebe/greenclip](https://github.com/erebe/greenclip) - Simple clipboard manager to be integrated with rofi - Static binary available
* [fossas/fossa-cli](https://github.com/fossas/fossa-cli) - Fast, portable and reliable dependency analysis for any codebase. Supports license & vulnerability scanning for large monoliths. Language-agnostic; integrates with 20+ build systems.
* [input-output-hk/plutus-pioneer-program](https://github.com/input-output-hk/plutus-pioneer-program) - This repository hosts the lectures of the Plutus Pioneers Program. This program is a training course that the IOG Education Team provides to recruit and train software developers in Plutus, the native smart contract language for the Cardano ecosystem.
* [avh4/elm-format](https://github.com/avh4/elm-format) - elm-format formats Elm source code according to a standard set of rules based on the official Elm Style Guide
* [fullstack-development/developers-roadmap](https://github.com/fullstack-development/developers-roadmap) - How to learn front-end or back-end development
* [GaloisInc/cryptol](https://github.com/GaloisInc/cryptol) - Cryptol: The Language of Cryptography
* [ndmitchell/ghcid](https://github.com/ndmitchell/ghcid) - Very low feature GHCi based IDE
* [B-Lang-org/bsc](https://github.com/B-Lang-org/bsc) - Bluespec Compiler (BSC)
* [uber/queryparser](https://github.com/uber/queryparser) - Parsing and analysis of Vertica, Hive, and Presto SQL.
* [polysemy-research/polysemy](https://github.com/polysemy-research/polysemy) - :gemini: higher-order, no-boilerplate monads
* [utdemir/nix-tree](https://github.com/utdemir/nix-tree) - Interactively browse dependency graphs of Nix derivations.
* [tonymorris/fp-course](https://github.com/tonymorris/fp-course) - Functional Programming Course
* [kitlang/kit](https://github.com/kitlang/kit) - Kit: a magical, high performance programming language, designed for game development.
* [vekatze/neut](https://github.com/vekatze/neut) - A functional programming language with static memory management
* [chrisdone-archive/intero](https://github.com/chrisdone-archive/intero) - *(archived)*
* [aviaviavi/toodles](https://github.com/aviaviavi/toodles) - Project management directly from the TODOs in your codebase
* [kirel/detexify-hs-backend](https://github.com/kirel/detexify-hs-backend) - Detexify Backend written in Haskell
* [egison/egison](https://github.com/egison/egison) - The Egison Programming Language
* [swarm-game/swarm](https://github.com/swarm-game/swarm) - Resource gathering + programming game
* [digital-asset/daml](https://github.com/digital-asset/daml) - The Daml smart contract language
* [snoyberg/conduit](https://github.com/snoyberg/conduit) - A streaming data library
* [radicle-dev/radicle-alpha](https://github.com/radicle-dev/radicle-alpha) - A peer-to-peer stack for code collaboration *(archived)*
* [Gabriella439/bench](https://github.com/Gabriella439/bench) - Command-line benchmark tool
* [haskell/parsec](https://github.com/haskell/parsec) - A monadic parser combinator library
* [kip-dili/kip](https://github.com/kip-dili/kip) - A programming language in Turkish where grammatical case and mood are part of the type system.
* [entropia/tip-toi-reveng](https://github.com/entropia/tip-toi-reveng) - Trying to understand the file format of Tip Toi
* [waymonad/waymonad](https://github.com/waymonad/waymonad) - A wayland compositor based on ideas from and inspired by xmonad
* [simplex-chat/simplexmq](https://github.com/simplex-chat/simplexmq) - ⚙️ SimpleXMQ - A reference implementation of the SimpleX Messaging Protocol for simplex queues over public networks.
* [tmspzz/Rome](https://github.com/tmspzz/Rome) - Carthage cache for S3, Minio, Ceph, Google Storage, Artifactory and many others
* [cardano-foundation/cardano-wallet](https://github.com/cardano-foundation/cardano-wallet) - HTTP server & command-line for managing UTxOs and HD wallets in Cardano.
* [ndmitchell/hoogle](https://github.com/ndmitchell/hoogle) - Haskell API search engine
* [ndmitchell/shake](https://github.com/ndmitchell/shake) - Shake build system
* [AndrasKovacs/elaboration-zoo](https://github.com/AndrasKovacs/elaboration-zoo) - Minimal implementations for dependent type checking and elaboration
* [ollef/sixten](https://github.com/ollef/sixten) - Functional programming with fewer indirections
* [GaloisInc/crucible](https://github.com/GaloisInc/crucible) - Crucible is a library for symbolic simulation of imperative programs
* [elm-lang/elm-platform](https://github.com/elm-lang/elm-platform) - Bundle of all core development tools for Elm *(archived)*
* [zachjs/sv2v](https://github.com/zachjs/sv2v) - SystemVerilog to Verilog conversion
* [awgn/cgrep](https://github.com/awgn/cgrep) - Cgrep: a context-aware grep for source codes
* [granule-project/granule](https://github.com/granule-project/granule) - A statically-typed linear functional language with graded modal types for fine-grained program reasoning
* [oden-lang/oden](https://github.com/oden-lang/oden) - The Oden Programming Language (NO LONGER IN ACTIVE DEVELOPMENT)
* [ajtulloch/dnngraph](https://github.com/ajtulloch/dnngraph) - A DSL for deep neural networks, supporting Caffe and Torch
* [mujx/hakatime](https://github.com/mujx/hakatime) - Wakatime server implementation & analytics dashboard
* [andyarvanitis/purescript-native](https://github.com/andyarvanitis/purescript-native) - A native compiler backend for PureScript (via C++ or Golang)
* [sweirich/pi-forall](https://github.com/sweirich/pi-forall) - A demo implementation of a simple dependently-typed language
* [forest-lang/forest-compiler](https://github.com/forest-lang/forest-compiler) - A multi-syntax functional programming language that compiles to WebAssembly.
* [jagajaga/FP-Course-ITMO](https://github.com/jagajaga/FP-Course-ITMO) - Slides and other materials for functional programming lectures ITMO university
* [tomjaguarpaw/haskell-opaleye](https://github.com/tomjaguarpaw/haskell-opaleye)
* [nix-community/nixpkgs-update](https://github.com/nix-community/nixpkgs-update) - Updating nixpkgs packages since 2018
* [Gabriella439/grace](https://github.com/Gabriella439/grace) - A prompt engineering functional programming language
* [kadena-io/pact](https://github.com/kadena-io/pact) - The Pact Smart Contract Language *(archived)*
* [mortberg/cubicaltt](https://github.com/mortberg/cubicaltt) - Experimental implementation of Cubical Type Theory
* [z0w0/helm](https://github.com/z0w0/helm) - A functionally reactive game engine, with headgear to protect you from the headache of game development provided. *(archived)*
* [adamwespiser/scheme](https://github.com/adamwespiser/scheme) - Write You a Scheme
* [reach-sh/reach-lang](https://github.com/reach-sh/reach-lang) - Reach: The Safest and Smartest DApp Programming Language
* [nasa/ogma](https://github.com/nasa/ogma) - Generator of runtime monitors for flight and robotics applications.
* [adept/full-fledged-hledger](https://github.com/adept/full-fledged-hledger) - Tutorial on Hledger setup with multi-year files, multi-source imports and a range of auto-generated reports
* [sdiehl/bulletproofs](https://github.com/sdiehl/bulletproofs) - Bulletproofs are short non-interactive zero-knowledge proofs that require no trusted setup
* [tamarin-prover/tamarin-prover](https://github.com/tamarin-prover/tamarin-prover) - Main source code repository of the Tamarin prover for security protocol verification.
* [jprupp/haskoin-core](https://github.com/jprupp/haskoin-core) - Haskoin Core is a Bitcoin and Bitcoin Cash library
* [graninas/Functional-Design-and-Architecture](https://github.com/graninas/Functional-Design-and-Architecture) - Code and materials for my book "Functional Design and Architecture"
* [GaloisInc/saw-script](https://github.com/GaloisInc/saw-script) - The Software Analysis Workbench
* [fptudelft/FP101x-Content-2015](https://github.com/fptudelft/FP101x-Content-2015) - FP101x - Functional Programming MOOC 2015 Content Repository
* [gren-lang/compiler](https://github.com/gren-lang/compiler) - Compiler for the Gren programming language
* [isovector/thinking-with-types](https://github.com/isovector/thinking-with-types) - 📖 source material for Thinking with Types
* [mbrubeck/compleat](https://github.com/mbrubeck/compleat) - Generate command-line completions using a simple DSL.
* [gelisam/frp-zoo](https://github.com/gelisam/frp-zoo) - Comparing many FRP implementations by reimplementing the same toy app in each.
* [def-/time.gif](https://github.com/def-/time.gif) - GIF that always shows the current time in UTC
* [Gabriella439/nix-diff](https://github.com/Gabriella439/nix-diff) - Explain why two Nix derivations differ
* [thoughtbot/carnival](https://github.com/thoughtbot/carnival) - An unobtrusive, developer-friendly way to add comments *(archived)*
* [steveshogren/10-minute-vim-exercises](https://github.com/steveshogren/10-minute-vim-exercises) - The exercise files from 10 Minute Vim, for convenience of readers
* [garnix-io/garnix-ci](https://github.com/garnix-io/garnix-ci) - CI and hosting for nix-based, flakified github repos
* [slovnicki/pLam](https://github.com/slovnicki/pLam) - An interpreter for learning and exploring pure λ-calculus
* [channable/vaultenv](https://github.com/channable/vaultenv) - Launch processes with Vault secrets in the environment
* [tommythorn/Reduceron](https://github.com/tommythorn/Reduceron) - FPGA Haskell machine with game changing performance. Reduceron is Matthew Naylor, Colin Runciman and Jason Reich's high performance FPGA softcore for running lazy functional programs, including hardware garbage collection. Reduceron has been implemented on various FPGAs with clock frequency ranging from 60 to 150 MHz depending on the FPGA. A high degree of parallelism allows Reduceron to implement graph evaluation very efficiently. This fork aims to continue development on this, with a view to practical applications. Comments, questions, etc are welcome.
* [vicfryzel/xmonad-config](https://github.com/vicfryzel/xmonad-config) - My xmonad and xmobar configuration, plus necessary scripts to make things more usable.
* [snapframework/snap](https://github.com/snapframework/snap) - Top-level package for the official Snap Framework libraries, includes the snaplets API as well as infrastructure for sessions, auth, and templates.
* [compiling-to-categories/concat](https://github.com/compiling-to-categories/concat) - Compiling to Categories
* [ThoughtWorksInc/DeepDarkFantasy](https://github.com/ThoughtWorksInc/DeepDarkFantasy) - A Programming Language for Deep Learning
* [kadena-io/juno](https://github.com/kadena-io/juno) - Smart Contracts Running on a BFT Hardened Raft *(archived)*
* [bitemyapp/fp-course](https://github.com/bitemyapp/fp-course) - Fork of the original Data61 course to be more Stack friendly
* [DSLsofMath/DSLsofMath](https://github.com/DSLsofMath/DSLsofMath) - Domain-Specific Languages of Mathematics
* [kcsongor/generic-lens](https://github.com/kcsongor/generic-lens) - Generically derive traversals, lenses, and prisms.
* [hablapps/DontFearTheProfunctorOptics](https://github.com/hablapps/DontFearTheProfunctorOptics) - Don't Fear the Profunctor Optics!
* [bitemyapp/bloodhound](https://github.com/bitemyapp/bloodhound) - Haskell Elasticsearch client and query DSL
* [ananthakumaran/webify](https://github.com/ananthakumaran/webify) - webfont generator - converts ttf to woff, eot and svg
* [lazamar/nix-package-versions](https://github.com/lazamar/nix-package-versions) - Search for old versions of Nix packages
* [TheAlgorithms/Haskell](https://github.com/TheAlgorithms/Haskell)
* [owickstrom/komposition](https://github.com/owickstrom/komposition) - The video editor built for screencasters *(archived)*
* [elm-lang/elm-reactor](https://github.com/elm-lang/elm-reactor) - Interactive development tool that makes it easy to develop and debug Elm programs. *(archived)*
* [benl23x5/gloss](https://github.com/benl23x5/gloss) - Painless 2D vector graphics, animations and simulations.
* [smallhadroncollider/brok](https://github.com/smallhadroncollider/brok) - Find broken links in text documents
* [mikeizbicki/subhask](https://github.com/mikeizbicki/subhask) - Type safe interface for working in subcategories of Hask
* [VictorTaelin/Caramel](https://github.com/VictorTaelin/Caramel) - A modern syntax for the λ-calculus.
* [GaloisInc/ivory](https://github.com/GaloisInc/ivory) - The Ivory EDSL
* [davidbrewer/xmonad-ubuntu-conf](https://github.com/davidbrewer/xmonad-ubuntu-conf) - My xmonad config for Ubuntu versions from 20.04 all the way back to 12.04! Including package list, config files, and instructions.
* [haskell-tls/hs-tls](https://github.com/haskell-tls/hs-tls) - TLS/SSL implementation in haskell
* [change-metrics/monocle](https://github.com/change-metrics/monocle) - Monocle helps teams and individual to better organize daily duties and to detect anomalies in the way changes are produced and reviewed.
* [diogob/postgres-websockets](https://github.com/diogob/postgres-websockets) - PostgreSQL + Websockets
* [jgm/yst](https://github.com/jgm/yst) - create static websites from YAML data and string templates
* [kqr/gists](https://github.com/kqr/gists) - With way too messy gist.github pages this is an attempt to organise my snippets
* [nh2/call-haskell-from-anything](https://github.com/nh2/call-haskell-from-anything) - Call Haskell functions from any programming language via serialization and dynamic libraries
* [haskell/vector](https://github.com/haskell/vector) - An efficient implementation of Int-indexed arrays (both mutable and immutable), with a powerful loop optimisation framework .
* [bitemyapp/esqueleto](https://github.com/bitemyapp/esqueleto) - New home of Esqueleto, please file issues so we can get things caught up!
* [haskell-numerics/hmatrix](https://github.com/haskell-numerics/hmatrix) - Linear algebra and numerical computation
* [nomeata/incredible](https://github.com/nomeata/incredible) - The Incredible Proof Machine
* [nix-community/nix-vscode-extensions](https://github.com/nix-community/nix-vscode-extensions) - Nix expressions for VS Code Marketplace and Open VSX extensions [maintainers=@deemp, @ameertaweel]
* [ekmett/ad](https://github.com/ekmett/ad) - Automatic Differentiation
* [well-typed/optics](https://github.com/well-typed/optics) - Optics as an abstract interface
* [silkapp/rest](https://github.com/silkapp/rest) - Packages for defining APIs, running them, generating client code and documentation.
* [haskell/wreq](https://github.com/haskell/wreq)
* [ServiceNow/picard](https://github.com/ServiceNow/picard) - PICARD - Parsing Incrementally for Constrained Auto-Regressive Decoding from Language Models. PICARD is a ServiceNow Research project that was started at Element AI.
* [suhdonghwi/nuri](https://github.com/suhdonghwi/nuri) - 누리 : 함수형 한글 프로그래밍 언어
* [tweag/funflow](https://github.com/tweag/funflow) - Functional workflows
* [purerl/purerl](https://github.com/purerl/purerl) - Erlang backend for the PureScript compiler
* [recursion-schemes/recursion-schemes](https://github.com/recursion-schemes/recursion-schemes) - Generalized bananas, lenses and barbed wire
* [nomeata/arbtt](https://github.com/nomeata/arbtt) - arbtt, the automatic rule-based time-tracker
* [seagreen/Son](https://github.com/seagreen/Son) - Work in progress. Best alternative: https://matrix.org/docs/spec/appendices.html#canonical-json
* [argotorg/hevm](https://github.com/argotorg/hevm) - Symbolic and concrete EVM execution engine
* [haskell/containers](https://github.com/haskell/containers) - Assorted concrete container types
* [Carnap/Carnap](https://github.com/Carnap/Carnap) - A formal logic framework that runs in the browser
* [sinelaw/infernu](https://github.com/sinelaw/infernu) - Type inference and checking for a safer JavaScript.
* [tadeuzagallo/verve-lang](https://github.com/tadeuzagallo/verve-lang) - A functional language for the working hacker
* [ekmett/machines](https://github.com/ekmett/machines) - Networks of composable stream transducers
* [mightybyte/monad-challenges](https://github.com/mightybyte/monad-challenges) - A set of challenges for jump starting your understanding of monads.
* [fimad/scalpel](https://github.com/fimad/scalpel) - A high level web scraping library for Haskell.
* [simonmar/async](https://github.com/simonmar/async) - Run IO operations asynchronously and wait for their results
* [CardanoSolutions/ogmios](https://github.com/CardanoSolutions/ogmios) - ❇️ A WebSocket JSON/RPC bridge for Cardano
* [snapframework/snap-core](https://github.com/snapframework/snap-core) - Core type definitions (Snap monad, HTTP types, etc) and utilities for web handlers.
* [IntersectMBO/cardano-db-sync](https://github.com/IntersectMBO/cardano-db-sync) - A component that follows the Cardano chain and stores blocks and transactions in PostgreSQL
* [bjpop/berp](https://github.com/bjpop/berp) - An implementation of Python 3
* [ambulancja/mariposa](https://github.com/ambulancja/mariposa) - A toy programming language with time travel
* [chrisdone/lucid](https://github.com/chrisdone/lucid) - Clear to write, read and edit DSL for writing HTML
* [frank-lang/frank](https://github.com/frank-lang/frank) - Frank compiler
* [jameshaydon/lawvere](https://github.com/jameshaydon/lawvere) - A categorical programming language with effects
* [willtim/Expresso](https://github.com/willtim/Expresso) - A simple expressions language with polymorphic extensible row types.
* [dpiponi/quine-central](https://github.com/dpiponi/quine-central) - A quine generator
* [fpco/inline-c](https://github.com/fpco/inline-c)
* [i-am-tom/holmes](https://github.com/i-am-tom/holmes) - A reference library for constraint-solving with propagators and CDCL.
* [berberman/nvfetcher](https://github.com/berberman/nvfetcher) - Generate nix sources expr for the latest version of packages
* [ekmett/trifecta](https://github.com/ekmett/trifecta) - Parser combinators with highlighting, slicing, layout, literate comments, Clang-style diagnostics and the kitchen sink
* [haskell/bytestring](https://github.com/haskell/bytestring) - An efficient compact, immutable byte string type (both strict and lazy) suitable for binary or 8-bit character data.
* [HigherOrderCO/HVM3](https://github.com/HigherOrderCO/HVM3) - HVM3
* [acowley/Frames](https://github.com/acowley/Frames) - Data frames for tabular data.
* [callum-oakley/gotta-go-fast](https://github.com/callum-oakley/gotta-go-fast) - A command line utility for practicing typing and measuring your WPM and accuracy.
* [Gabriella439/slides](https://github.com/Gabriella439/slides) - Slides from talks that I give
* [IntersectMBO/plutus-apps](https://github.com/IntersectMBO/plutus-apps) - The Plutus application platform *(archived)*
* [jgm/pandoc-citeproc](https://github.com/jgm/pandoc-citeproc) - Library and executable for using citeproc with pandoc *(archived)*
* [parsonsmatt/servant-persistent](https://github.com/parsonsmatt/servant-persistent) - A brief example of Servant with Persistent
* [elm/package.elm-lang.org](https://github.com/elm/package.elm-lang.org) - website for browsing packages and exploring documentation
* [IntersectMBO/cardano-ledger](https://github.com/IntersectMBO/cardano-ledger) - The ledger implementation and specifications of the Cardano blockchain.
* [tkonolige/dbignore](https://github.com/tkonolige/dbignore) - .gitignore for Dropbox *(archived)*
* [Deltaphish/UwUpp](https://github.com/Deltaphish/UwUpp) - The next generation esoteric language
* [MichaelXavier/Angel](https://github.com/MichaelXavier/Angel) - Process Monitoring/Management, Like Daemontools
* [chrisdone-archive/z](https://github.com/chrisdone-archive/z) - A strict, impure, curried, partially applied programming language with rather peculiar syntax. *(archived)*
* [argotorg/act](https://github.com/argotorg/act) - Smart contract specification language
* [cdosborn/lit](https://github.com/cdosborn/lit) - A modern tool for literate programming
* [ollef/sixty](https://github.com/ollef/sixty) - Dependent type checker using normalisation by evaluation
* [RaphaelJ/friday](https://github.com/RaphaelJ/friday) - Fast image IO and transformations.
* [tomahawkins/atom](https://github.com/tomahawkins/atom) - A DSL for embedded hard realtime applications.
* [ekmett/guanxi](https://github.com/ekmett/guanxi) - Relational programming in Haskell. Mostly developed on twitch.
* [nick8325/quickspec](https://github.com/nick8325/quickspec) - Equational laws for free
* [standardsemiconductor/lion](https://github.com/standardsemiconductor/lion) - Where Lions Roam: RISC-V on the VELDT
* [DataHaskell/dataframe](https://github.com/DataHaskell/dataframe) - A fast, safe, and intuitive DataFrame library.
* [snoyberg/keter](https://github.com/snoyberg/keter) - Web app deployment manager
* [mwotton/Hubris](https://github.com/mwotton/Hubris) - Bridge from Ruby to Haskell
* [LaurentRDC/pandoc-plot](https://github.com/LaurentRDC/pandoc-plot) - Render and include figures in Pandoc documents using your plotting toolkit of choice
* [wh5a/Algorithm-W-Step-By-Step](https://github.com/wh5a/Algorithm-W-Step-By-Step) - Classic Algorithm W for type inference.
* [yannick-cw/korb](https://github.com/yannick-cw/korb) - REWE delivery CLI
* [GaloisInc/macaw](https://github.com/GaloisInc/macaw) - Open source binary analysis tools.
* [pdobsan/oama](https://github.com/pdobsan/oama) - OAuth credential Manager
* [CDSoft/pp](https://github.com/CDSoft/pp) - PP - Generic preprocessor (with pandoc in mind) - macros, literate programming, diagrams, scripts... *(archived)*
* [honest-technology/api.unverified.email](https://github.com/honest-technology/api.unverified.email) - A service to help with testing of sending the right emails
* [frp-arduino/frp-arduino](https://github.com/frp-arduino/frp-arduino) - Arduino programming without the hassle of C.
* [nikita-volkov/record](https://github.com/nikita-volkov/record) - Anonymous records
* [commercialhaskell/stack-templates](https://github.com/commercialhaskell/stack-templates) - Project templates for stack new
* [haskell-github-trust/Juicy.Pixels](https://github.com/haskell-github-trust/Juicy.Pixels) - Haskell library to load & save pictures
* [system-f/lets-lens](https://github.com/system-f/lets-lens) - Course material for lens
* [39aldo39/klfc](https://github.com/39aldo39/klfc) - Keyboard Layout Files Creator
* [cpeikert/Lol](https://github.com/cpeikert/Lol) - Λ ⚬ λ: Functional Lattice Cryptography
* [tweag/inline-java](https://github.com/tweag/inline-java) - Haskell/Java interop via inline Java code in Haskell modules.
* [Euterpea/Euterpea2](https://github.com/Euterpea/Euterpea2) - Euterpea version 2
* [fugue/fregot](https://github.com/fugue/fregot) - Fugue Rego Toolkit
* [ruHaskell/ruhaskell](https://github.com/ruHaskell/ruhaskell) - Главный сайт сообщества
* [diagrams/diagrams](https://github.com/diagrams/diagrams) - Embedded domain-specific language for declarative vector graphics (wrapper package)
* [incoherentsoftware/defect-process](https://github.com/incoherentsoftware/defect-process) - Defect Process (2d hack n' slash game) full source code
* [ermine-language/ermine](https://github.com/ermine-language/ermine) - The Ermine Programming Language - Join us on irc.freenode.net #ermine
* [goldfirere/glambda](https://github.com/goldfirere/glambda) - The home of the Glamorous Glambda interpreter
* [purescript/psc-package](https://github.com/purescript/psc-package) - A package manager for PureScript based on package sets
* [aristanetworks/nix-serve-ng](https://github.com/aristanetworks/nix-serve-ng) - A drop-in replacement for nix-serve that is faster and more reliable
* [geophf/1HaskellADay](https://github.com/geophf/1HaskellADay)
* [yesodweb/yesod-cookbook](https://github.com/yesodweb/yesod-cookbook) - Cookbook documentation
* [bos/pronk](https://github.com/bos/pronk) - A small command line application for load testing web servers. Think of it as similar to httperf or ab, only more modern and simpler to deal with.
* [harpocrates/inline-rust](https://github.com/harpocrates/inline-rust) - Use snippets of Rust inline in your Haskell programs
* [haskell-unordered-containers/unordered-containers](https://github.com/haskell-unordered-containers/unordered-containers) - Efficient hashing-based container types
* [Agda-zh/PLFA-zh](https://github.com/Agda-zh/PLFA-zh) - 《编程语言基础：Agda 描述》，Programming Language Foundations in Agda 中文版
* [morloc-project/morloc](https://github.com/morloc-project/morloc) - A strongly-typed, polyglot compiler
* [elm-lang/elm-package](https://github.com/elm-lang/elm-package) - Command line tool to share Elm libraries *(archived)*
* [evmar/c-repl](https://github.com/evmar/c-repl) - a C read-eval-print loop (abandoned)
* [tromp/AIT](https://github.com/tromp/AIT) - Algorithmic Information Theory, using Binary Lambda Calculus
* [graninas/Hydra](https://github.com/graninas/Hydra) - Hydra is a full-fledged framework for building web services, multithreaded and concurrent applications with SQL and KV DB support.
* [Tarrasch/antigen-hs](https://github.com/Tarrasch/antigen-hs) - A fast zsh plugin manager
* [goldfirere/thesis](https://github.com/goldfirere/thesis) - Richard A. Eisenberg's PhD Dissertation
* [ehamberg/9m](https://github.com/ehamberg/9m) - 9m Unicode URL Shortener
* [ff-notes/ff](https://github.com/ff-notes/ff) - A distributed note taker and task manager.
* [haskell-webdriver/haskell-webdriver](https://github.com/haskell-webdriver/haskell-webdriver) - A Haskell client for the Selenium WebDriver protocol.
* [LuxMiranda/herms](https://github.com/LuxMiranda/herms) - :stew::fork_and_knife: A command-line manager for delicious kitchen recipes
* [Rasie1/shortcut-highlighter](https://github.com/Rasie1/shortcut-highlighter) - set of tools and services for highlighting shortcuts from applications and system with RGB keyboard
* [noelmarkham/learn-you-a-haskell-exercises](https://github.com/noelmarkham/learn-you-a-haskell-exercises)
* [CategoricalData/hydra](https://github.com/CategoricalData/hydra) - Graph programming language
* [jozefg/higher-order-unification](https://github.com/jozefg/higher-order-unification) - A small implementation of higher-order unification
* [snapframework/snap-server](https://github.com/snapframework/snap-server) - A fast HTTP server library, which runs Snap web handlers.
* [walck/learn-physics](https://github.com/walck/learn-physics) - A library of functions for vector calculus, calculation of electric field, electric flux, magnetic field, and other quantities in mechanics and electromagnetic theory.
* [CIFASIS/QuickFuzz](https://github.com/CIFASIS/QuickFuzz) - An experimental grammar fuzzer in Haskell using QuickCheck
* [nikita-volkov/refined](https://github.com/nikita-volkov/refined) - Refinement types with static checking
* [Peaker/git-mediate](https://github.com/Peaker/git-mediate) - Become a conflict resolution hero
* [corsis/PortFusion](https://github.com/corsis/PortFusion) - Haskell-powered cross-platform transport-layer distributed reverse / forward proxy & tunneling solution – currently available for all TCP protocols (RDP, VNC, HTTP(S), SSH, ...).
* [dktr0/estuary](https://github.com/dktr0/estuary) - Platform for collaboration and learning through live coding
* [caotic123/PomPom-Language](https://github.com/caotic123/PomPom-Language) - The cuteness implementation of a dependently typed language.
* [channable/alfred-margaret](https://github.com/channable/alfred-margaret) - Fast Aho-Corasick string searching
* [josephsumabat/static-ls](https://github.com/josephsumabat/static-ls)
* [Eelis/cxxdraft-htmlgen](https://github.com/Eelis/cxxdraft-htmlgen) - Generates https://eel.is/c++draft
* [ekmett/free](https://github.com/ekmett/free) - free monads
* [smallhadroncollider/cmt](https://github.com/smallhadroncollider/cmt) - Write consistent git commit messages based on a custom template *(archived)*
* [Mzk-Levi/texts](https://github.com/Mzk-Levi/texts)
* [aymannadeem/foldilocks](https://github.com/aymannadeem/foldilocks) - Tutorial using ghci to make folds easier. Come for the tutorial, stay for the fold puns.
* [l29ah/muesli](https://github.com/l29ah/muesli) - An alternative approach to food
* [ocharles/weeder](https://github.com/ocharles/weeder) - A re-implementation of weeder using HIE files
* [jwiegley/gitlib](https://github.com/jwiegley/gitlib)
* [lenary/idris-erlang](https://github.com/lenary/idris-erlang) - Erlang Backend for Idris Compiler *(archived)*
* [actonlang/acton](https://github.com/actonlang/acton) - Actor-based, safely typed, fast programming language.
* [agda/cornelis](https://github.com/agda/cornelis) - agda-mode for neovim
* [Eelis/geordi](https://github.com/Eelis/geordi) - IRC C++ eval bot
* [ekmett/propagators](https://github.com/ekmett/propagators) - The Art of the Propagator. See also:
* [lykahb/groundhog](https://github.com/lykahb/groundhog) - This library maps datatypes to a relational model, in a way similar to what ORM libraries do in OOP. See the tutorial https://www.schoolofhaskell.com/user/lykahb/groundhog for introduction
* [AndrasKovacs/flatparse](https://github.com/AndrasKovacs/flatparse) - Fast parsing from bytestrings
* [ditto/ditto](https://github.com/ditto/ditto) - A Super Kawaii Dependently Typed Programming Language
* [eldexterr/ttyd64](https://github.com/eldexterr/ttyd64) - PM64 romhack that adds TTYD's gameplay into the original Paper Mario.
* [GaloisInc/what4](https://github.com/GaloisInc/what4) - Symbolic formula representation and solver interaction library
* [prowdsponsor/esqueleto](https://github.com/prowdsponsor/esqueleto) - Bare bones, type-safe EDSL for SQL queries on persistent backends.
* [discus-lang/ddc](https://github.com/discus-lang/ddc) - The Disco Discus Compiler
* [input-output-hk/lobster-challenge](https://github.com/input-output-hk/lobster-challenge) - Simple Plutus contract to help give Charles' stuffed lobster a name
* [msakai/cpl](https://github.com/msakai/cpl) - An interpreter of Hagino's Categorical Programming Language (CPL).
* [edwinb/idris-php](https://github.com/edwinb/idris-php) - Yes, really...
* [elm-lang/elm-make](https://github.com/elm-lang/elm-make) - A build tool for Elm projects *(archived)*
* [mmirman/caledon](https://github.com/mmirman/caledon) - higher order dependently typed logic programing
* [passy/android-lint-summary](https://github.com/passy/android-lint-summary) - Prettier display of Android Lint issues
* [haskell-streaming/streaming](https://github.com/haskell-streaming/streaming) - An optimized general monad transformer for streaming applications, with a simple prelude of functions
* [purescript/pursuit](https://github.com/purescript/pursuit) - Website for hosting and searching PureScript API documentation
* [liamoc/holbert](https://github.com/liamoc/holbert) - A graphical interactive proof assistant designed for education
* [A1kmm/proofsweeper](https://github.com/A1kmm/proofsweeper) - Play Minesweeper by formally proving your moves in Idris
* [aloiscochard/codex](https://github.com/aloiscochard/codex) - A ctags file generator for cabal/stack project dependencies. *(archived)*
* [bitc/hdevtools](https://github.com/bitc/hdevtools) - REPO UNMAINTAINED!!! Try this: https://github.com/hdevtools/hdevtools/
* [elm-lang/elm-repl](https://github.com/elm-lang/elm-repl) - A REPL for Elm *(archived)*
* [i-am-tom/higgledy](https://github.com/i-am-tom/higgledy) - Higher-kinded data via generics
* [KeliLanguage/compiler](https://github.com/KeliLanguage/compiler) - The compiler for Keli
* [polux/lambda-diagrams](https://github.com/polux/lambda-diagrams) - Animations of lambda term reduction sequences
* [tomjaguarpaw/bluefin](https://github.com/tomjaguarpaw/bluefin)
* [github/deli](https://github.com/github/deli) - *(archived)*
* [isovector/algebra-driven-design](https://github.com/isovector/algebra-driven-design) - Source material for Algebra-Driven Design
* [nushio3/learn-haskell](https://github.com/nushio3/learn-haskell)
* [therepanic/openleetcode](https://github.com/therepanic/openleetcode) - we have democratized the LeetCode tests
* [GrammaticalFramework/gf-core](https://github.com/GrammaticalFramework/gf-core) - Grammatical Framework core: compiler, shell & runtimes
* [NorfairKing/validity](https://github.com/NorfairKing/validity) - Validity and validity-based testing
* [ucsd-progsys/liquid-fixpoint](https://github.com/ucsd-progsys/liquid-fixpoint) - Horn Clause Constraint Solving for Liquid Types
* [FPtje/GLuaFixer](https://github.com/FPtje/GLuaFixer) - Linter for Garry's mod Lua.
* [jaspervdj/lorem-markdownum](https://github.com/jaspervdj/lorem-markdownum) - A lorem ipsum generator for markdown
* [digital-asset/ghc-lib](https://github.com/digital-asset/ghc-lib) - The GHC API, decoupled from GHC versions
* [jekor/gressgraph](https://github.com/jekor/gressgraph) - visualize your iptables firewall
* [snoyberg/mono-traversable](https://github.com/snoyberg/mono-traversable) - Type classes for mapping, folding, and traversing monomorphic containers
* [tobbebex/GPipe-Core](https://github.com/tobbebex/GPipe-Core) - Core library of new GPipe, encapsulating OpenGl and providing a type safe minimal library
* [aviaviavi/curl-runnings](https://github.com/aviaviavi/curl-runnings) - A declarative test framework for quickly and easily writing integration tests against JSON APIs.
* [Bodigrim/arithmoi](https://github.com/Bodigrim/arithmoi) - Number theory: primes, arithmetic functions, modular computations, special sequences
* [IntersectMBO/cardano-addresses](https://github.com/IntersectMBO/cardano-addresses) - Addresses and mnemonic manipulation & derivations
* [plaidfinch/ComonadSheet](https://github.com/plaidfinch/ComonadSheet) - A library for expressing "spreadsheet-like" computations with absolute and relative references, using fixed-points of n-dimensional comonads.
* [MaybeJustJames/zephyr](https://github.com/MaybeJustJames/zephyr) - Tree shaking breeze for PureScript CoreFn AST
* [msakai/toysolver](https://github.com/msakai/toysolver) - My sandbox for experimenting with solver algorithms.
* [rberenguel/glancer](https://github.com/rberenguel/glancer) - Glance over some technical videos
* [haskell-servant/servant-auth](https://github.com/haskell-servant/servant-auth) - *(archived)*
* [pgenie-io/pgenie](https://github.com/pgenie-io/pgenie) - SQL-first, type-safe PostgreSQL client code generator
* [bjpop/blip](https://github.com/bjpop/blip) - A bytecode compiler for Python 3
* [graninas/Pragmatic-Type-Level-Design](https://github.com/graninas/Pragmatic-Type-Level-Design) - Code and materials for my book "Pragmatic Type Level Design"
* [jez/pandoc-sidenote](https://github.com/jez/pandoc-sidenote) - Convert Pandoc Markdown-style footnotes into sidenotes
* [LumiGuide/haskell-opencv](https://github.com/LumiGuide/haskell-opencv) - Haskell binding to OpenCV-3.x
* [silky/awesome-open-science](https://github.com/silky/awesome-open-science) - some links to projects/tools related to "open science". *(archived)*
* [GU-CLASP/TypedFlow](https://github.com/GU-CLASP/TypedFlow) - Typed frontend to TensorFlow and higher-order deep learning
* [kindl/Hypatia](https://github.com/kindl/Hypatia) - A ML-family Language Compiled to Lua
* [mstksg/hamilton](https://github.com/mstksg/hamilton) - Simulate physics on generalized coordinate systems using Hamiltonian Mechanics and automatic differentiation. Don't throw away your shot.
* [gelisam/klister](https://github.com/gelisam/klister) - an implementation of stuck macros
* [sonyxperiadev/dataflow](https://github.com/sonyxperiadev/dataflow) - Render graphs using a declarative markup.
* [haskell-works/hw-kafka-client](https://github.com/haskell-works/hw-kafka-client) - Kafka client for Haskell, including auto-rebalancing consumers
* [kofigumbs/elm-beam](https://github.com/kofigumbs/elm-beam) - Exploring Elm on the Erlang VM *(archived)*
* [bgavran/Compositional_Deep_Learning](https://github.com/bgavran/Compositional_Deep_Learning) - Deep learning via category theory and functional programming
* [fpco/unliftio](https://github.com/fpco/unliftio) - The MonadUnliftIO typeclass for unlifting monads to IO
* [jaspervdj/digestive-functors](https://github.com/jaspervdj/digestive-functors) - A general way to consume input using applicative functors
* [ranjitjhala/sprite-lang](https://github.com/ranjitjhala/sprite-lang) - An tutorial-style implementation of liquid/refinement types for a subset of Ocaml/Reason.
* [kmyk-jikka/Jikka](https://github.com/kmyk-jikka/Jikka) - an automated solver for problems of competitive programming
* [nadia-polikarpova/synquid](https://github.com/nadia-polikarpova/synquid)
* [conal/lambda-ccc](https://github.com/conal/lambda-ccc) - Convert lambda expressions to CCC combinators
* [creswick/cabal-dev](https://github.com/creswick/cabal-dev) - A wrapper program around cabal and cabal-install that maintains sandboxed build environments.
* [JeffreyBenjaminBrown/hode](https://github.com/JeffreyBenjaminBrown/hode) - rslt, take five-ish
* [nwf/dyna](https://github.com/nwf/dyna) - Dyna2 compiler and REPL *(archived)*
* [sweirich/tal](https://github.com/sweirich/tal) - An implementation of Typed Assembly Language (Morrisett, Walker, Crary, Glew)
* [audreyt/regex-genex](https://github.com/audreyt/regex-genex) - Given a list of regexes, generate all possible strings that matches all of them.
* [yannick-cw/notion-ocr](https://github.com/yannick-cw/notion-ocr) - Adding OCR support to Notion
* [bmillwood/pointfree](https://github.com/bmillwood/pointfree) - Maintenance of the pointfree Hackage package.
* [kazu-yamamoto/mighttpd2](https://github.com/kazu-yamamoto/mighttpd2) - File/CGI web server on Warp
* [owickstrom/pandoc-include-code](https://github.com/owickstrom/pandoc-include-code) - A Pandoc filter for including code from source files
* [haskell-repa/repa](https://github.com/haskell-repa/repa) - High performance, regular, shape polymorphic parallel arrays.
* [nurpax/sqlite-simple](https://github.com/nurpax/sqlite-simple) - Mid-level bindings for sqlite
* [haskell-servant/example-servant-elm](https://github.com/haskell-servant/example-servant-elm) - Example for a web app with a servant backend and an elm frontend
* [kerkomen/rei](https://github.com/kerkomen/rei) - Process lists easily
* [nomeata/ghc-proofs](https://github.com/nomeata/ghc-proofs) - Let GHC prove program equations for you
* [simhu/cubical](https://github.com/simhu/cubical) - Implementation of Univalence in Cubical Sets
* [marvinborner/bruijn](https://github.com/marvinborner/bruijn) - :abacus: Programming with pure lambda calculus
* [ekmett/discrimination](https://github.com/ekmett/discrimination) - Fast linear time sorting and discrimination for a large class of data types
* [UU-ComputerScience/uhc](https://github.com/UU-ComputerScience/uhc)
* [mchakravarty/BigPixel](https://github.com/mchakravarty/BigPixel) - Pixel art for games
* [yesodweb/shakespeare](https://github.com/yesodweb/shakespeare) - Haml-like template files that are compile-time checked
* [ruuda/blog](https://github.com/ruuda/blog) - My personal site
* [visi-lang/visi](https://github.com/visi-lang/visi) - The Visi Language and iPad IDE
* [diagrams/diagrams-lib](https://github.com/diagrams/diagrams-lib) - Diagrams standard library
* [ollef/rock](https://github.com/ollef/rock) - Build system
* [transient-haskell/transient-universe](https://github.com/transient-haskell/transient-universe) - A Cloud monad based on transient for the creation of Web and reactive distributed applications that are fully composable, where Web browsers are first class nodes in the cloud
* [siraben/freenode-exodus](https://github.com/siraben/freenode-exodus) - Projects and channels that have decided to leave Freenode. (Final leave count: 1056) *(archived)*
* [CardanoSolutions/kupo](https://github.com/CardanoSolutions/kupo) - 🐹 Fast, lightweight & configurable chain-index for Cardano.
* [fpco/safe-exceptions](https://github.com/fpco/safe-exceptions) - Safe, consistent, and easy exception handling
* [frasertweedale/hs-jose](https://github.com/frasertweedale/hs-jose) - Haskell JOSE and JWT library
* [freizl/hoauth2](https://github.com/freizl/hoauth2) - Haskell oauth2 binding
* [NorfairKing/autodocodec](https://github.com/NorfairKing/autodocodec) - self(auto)- documenting encoders and decoders
* [bschwb/cis194-solutions](https://github.com/bschwb/cis194-solutions) - Solutions for CIS 194 - Spring 2013
* [channable/icepeak](https://github.com/channable/icepeak) - Icepeak is a fast JSON document store with push notification support.
* [haskell/time](https://github.com/haskell/time) - A time library
* [larrytheliquid/Lemmachine](https://github.com/larrytheliquid/Lemmachine) - REST'ful web framework in Agda
* [typed-wire/typed-wire](https://github.com/typed-wire/typed-wire) - Language independent type-safe communication
* [yaxu/feedforward](https://github.com/yaxu/feedforward)
* [garnix-io/nixos-compose](https://github.com/garnix-io/nixos-compose)
* [Xetera/placewaifu](https://github.com/Xetera/placewaifu) - 🎀 An incredibly cute placeholder service
* [bamboo/idris-cil](https://github.com/bamboo/idris-cil) - A Common Intermediate Language backend for Idris 1
* [GaloisInc/grease](https://github.com/GaloisInc/grease) - CLI tool, Ghidra plug-in, and Haskell library for analyzing binaries using under-constrained symbolic execution
* [glotcode/glot-www](https://github.com/glotcode/glot-www) - glot.io website *(archived)*
* [msp-strath/TypOS](https://github.com/msp-strath/TypOS) - being an operating system for typechecking processes
* [owickstrom/idris-vimscript](https://github.com/owickstrom/idris-vimscript) - Compile Idris to Vimscript, like you always wanted. *(archived)*
* [Plutonomicon/plutarch-plutus](https://github.com/Plutonomicon/plutarch-plutus) - Typed eDSL for writing UPLC /ˈpluː.tɑːk/
* [ghcjs/jsaddle](https://github.com/ghcjs/jsaddle) - JavaScript interface that works with GHCJS or GHC
* [machine-intelligence/Botworld](https://github.com/machine-intelligence/Botworld) - A cellular automaton for studying self-modifying agents which are embedded in their environment
* [ndmitchell/bake](https://github.com/ndmitchell/bake) - UNMAINTAINED: Continuous integration server
* [UnkindPartition/regex-applicative](https://github.com/UnkindPartition/regex-applicative) - Regex-based parsing with an applicative interface
* [ekmett/bound](https://github.com/ekmett/bound) - Combinators for manipulating locally-nameless generalized de Bruijn terms
* [smudgelang/smudge](https://github.com/smudgelang/smudge) - A domain-specific language for state machines.
* [caotic123/Kei](https://github.com/caotic123/Kei) - A small and expressive dependently typed language
* [ChrisPenner/lens-regex-pcre](https://github.com/ChrisPenner/lens-regex-pcre) - Text lenses using PCRE regexes
* [commercialhaskell/path](https://github.com/commercialhaskell/path) - Typed filepath
* [hreinhardt/amqp](https://github.com/hreinhardt/amqp) - Haskell AMQP client library
* [knupfer/type-of-html](https://github.com/knupfer/type-of-html) - High performance type safe html generation
* [seagreen/plate](https://github.com/seagreen/plate) - Algebraic type based schema system *(archived)*
* [expipiplus1/update-nix-fetchgit](https://github.com/expipiplus1/update-nix-fetchgit) - A program to automatically update fetchgit values in Nix expressions
* [fragnix/fragnix](https://github.com/fragnix/fragnix) - Fragment-based code distribution!
* [simonmar/monad-par](https://github.com/simonmar/monad-par)
* [adamgundry/type-inference](https://github.com/adamgundry/type-inference) - Unification and type inference algorithms
* [agda/agda-language-server](https://github.com/agda/agda-language-server) - Language Server for Agda
* [awalterschulze/category-theory-for-programmers-challenges](https://github.com/awalterschulze/category-theory-for-programmers-challenges) - Challenges from Category Theory for Programmers
* [dropbox/datagraph](https://github.com/dropbox/datagraph)
* [jozefg/pcf](https://github.com/jozefg/pcf) - A small compiler for PCF
* [ndmitchell/weeder](https://github.com/ndmitchell/weeder) - Detect dead exports or package imports
* [nomeata/ghc-justdoit](https://github.com/nomeata/ghc-justdoit) - A magic typeclass that just does it
* [phadej/cabal-fmt](https://github.com/phadej/cabal-fmt) - An experiment of formatting .cabal files
* [ziman/idris-py](https://github.com/ziman/idris-py) - Python backend for Idris (generates Python source, not bytecode).
* [iokasimov/ya](https://github.com/iokasimov/ya) - Я - extremely composable embeddable programming language
* [lamdu/hypertypes](https://github.com/lamdu/hypertypes) - Hypertypes - generic programming for heterogeneous recursive types
* [egonSchiele/HandsomeSoup](https://github.com/egonSchiele/HandsomeSoup) - Easy HTML parsing for Haskell
* [haskell-servant/servant-swagger](https://github.com/haskell-servant/servant-swagger) - Swagger for Servant
* [haskell/primitive](https://github.com/haskell/primitive) - This package provides various primitive memory-related operations.
* [haskell/unix](https://github.com/haskell/unix) - POSIX functionality
* [jaspervdj/jaspervdj](https://github.com/jaspervdj/jaspervdj) - Source code of my personal home page.
* [jgm/pandoc-types](https://github.com/jgm/pandoc-types) - types for representing structured documents
* [ymherklotz/verismith](https://github.com/ymherklotz/verismith) - Verilog Fuzzer to test the major simulators and sythesisers by generating random, valid Verilog.
* [elisehuard/game-in-haskell](https://github.com/elisehuard/game-in-haskell)
* [haskellari/these](https://github.com/haskellari/these) - An either-or-both data type, with corresponding hybrid error/writer monad transformer.
* [NicolasT/kontiki](https://github.com/NicolasT/kontiki) - An implementation of the Raft consensus protocol
* [OscarSouth/theHarmonicAlgorithm](https://github.com/OscarSouth/theHarmonicAlgorithm) - The Harmonic Algorithm by Oscar South - A Project Spanning Music Analysis, Functional Programming & Machine Learning. Check out the website below for docs, demonstrations and articles, Please leave a star on the repo above if you think this thing looks cool :)
* [lehins/hip](https://github.com/lehins/hip) - Haskell Image Processing Library
* [ptol/oczor](https://github.com/ptol/oczor) - Oczor is a simple statically typed language that compiles to JavaScript, Lua, Ruby and Emacs Lisp
* [ChrisPenner/SitePipe](https://github.com/ChrisPenner/SitePipe) - Yet another static site generator - non-opinionated, value-level. Less magic == easier to understand
* [docopt/docopt.hs](https://github.com/docopt/docopt.hs) - A command-line interface description language and parser that will make you smile
* [fission-codes/fission](https://github.com/fission-codes/fission) - Fission CLI & server
* [juspay/euler-hs](https://github.com/juspay/euler-hs) - EulerHS: full-fledged framework for creating web backends
* [GregorySchwartz/too-many-cells](https://github.com/GregorySchwartz/too-many-cells) - Cluster single cells and analyze cell clade relationships with colorful visualizations.
* [ncaq/uBlacklistRule](https://github.com/ncaq/uBlacklistRule) - This rule is for uBlacklist. there is also a rule for uBlock Origin in Firefox for Android.
* [stevana/elastically-scalable-thread-pools](https://github.com/stevana/elastically-scalable-thread-pools) - An experiment in controlling the size of a thread pool using a PID controller.
* [fpco/ide-backend](https://github.com/fpco/ide-backend) - ide-backend drives the GHC API to build, query, and run your code
* [mikeizbicki/ifcxt](https://github.com/mikeizbicki/ifcxt) - constraint level if statements
* [conjure-cp/conjure](https://github.com/conjure-cp/conjure) - Conjure: The Automated Constraint Modelling Tool
* [danchoi/herbalizer](https://github.com/danchoi/herbalizer) - Convert HAML to ERB
* [fpco/typed-process](https://github.com/fpco/typed-process) - Alternative API for processes, featuring more type safety
* [imeckler/mote](https://github.com/imeckler/mote)
* [unison-code/unison](https://github.com/unison-code/unison) - Unison's source code
* [andreasabel/miniagda](https://github.com/andreasabel/miniagda) - A prototypical dependently typed languages with sized types and variances
* [bjornbm/dimensional](https://github.com/bjornbm/dimensional) - Dimensional library variant built on Data Kinds, Closed Type Families, TypeNats (GHC 7.8+).
* [jappeace/cut-the-crap](https://github.com/jappeace/cut-the-crap) - Automated video editing for streamers
* [Soostone/retry](https://github.com/Soostone/retry) - Retry combinators for monadic actions that may fail
* [wyager/Neks](https://github.com/wyager/Neks) - A dead simple networked key/value store
* [cobbpg/elerea](https://github.com/cobbpg/elerea) - A simple FRP library providing leak-free first-class streams.
* [DanBurton/tardis](https://github.com/DanBurton/tardis)
* [fumieval/deriving-aeson](https://github.com/fumieval/deriving-aeson) - Scrap your hand-rolled aeson instances
* [ndmitchell/rattle](https://github.com/ndmitchell/rattle) - Forward build system with speculation and caching
* [neurocyte/android-haskell-activity](https://github.com/neurocyte/android-haskell-activity) - An example of an Android Activity written in Haskell
* [serras/hinc](https://github.com/serras/hinc) - Haskell In New Clothes
* [haskell-cryptography/cacophony](https://github.com/haskell-cryptography/cacophony) - A Haskell library implementing the Noise protocol.
* [haskell-miso/miso-lynx](https://github.com/haskell-miso/miso-lynx) - :ramen: 🐈 A tasty Haskell mobile framework
* [lspitzner/exference](https://github.com/lspitzner/exference) - Haskell tool to generate expressions from types
* [albertoruiz/easyVision](https://github.com/albertoruiz/easyVision) - Haskell packages for computer vision, image processing, and pattern recognition
* [jspahrsummers/ObjectiveHaskell](https://github.com/jspahrsummers/ObjectiveHaskell) - Tools for making it easier to integrate Haskell and Objective-C. *(archived)*
* [dpp/LispHaskellIPad](https://github.com/dpp/LispHaskellIPad) - An iPad app that's a Lisp interpretter... written in Haskell (heh heh heh)
* [jcollard/unm-hip](https://github.com/jcollard/unm-hip) - The University of New Mexico's Haskell Image Processing Library
* [saurabhnanda/odd-jobs](https://github.com/saurabhnanda/odd-jobs) - Haskell job queue with admin UI and loads of other features.
* [mmirman/ImperativeHaskell](https://github.com/mmirman/ImperativeHaskell) - Proof that Haskell can look and act like an imperative language.
* [turtlesoupy/haskakafka](https://github.com/turtlesoupy/haskakafka) - Kafka bindings for Haskell
* [abhin4v/hastatic](https://github.com/abhin4v/hastatic) - hastatic is a tiny static content web server for Docker
* [acowley/ffmpeg-light](https://github.com/acowley/ffmpeg-light) - Minimal Haskell bindings to the FFmpeg library
* [haskellfoundation/tech-proposals](https://github.com/haskellfoundation/tech-proposals) - The Haskell Foundation Tech Proposal Process
* [sol/reserve](https://github.com/sol/reserve) - Universal and robust reloading for Haskell web applications
* [raaz-crypto/raaz](https://github.com/raaz-crypto/raaz) - Cryptographic library for Haskell
* [vaibhavsagar/duffer](https://github.com/vaibhavsagar/duffer) - A git-compatible content tracker in Haskell.
* [vincenthz/hs-git](https://github.com/vincenthz/hs-git) - git protocol and storage in pure haskell *(archived)*
* [tibbe/hyena](https://github.com/tibbe/hyena) - A Haskell web application server.
* [haskell-tls/hs-certificate](https://github.com/haskell-tls/hs-certificate) - Certificate and Key Reader/Writer in haskell
* [picnoir/ex-hack](https://github.com/picnoir/ex-hack) - Example-based Haskell Documentation Engine
* [davean/waldo](https://github.com/davean/waldo) - A small Haskell server for generating visual stories based on some ascertainable data about the requester.
* [fortytools/holumbus](https://github.com/fortytools/holumbus) - A Haskell library which provides the basic building blocks for creating powerful indexing and search applications.
* [giovanifss/Dumb](https://github.com/giovanifss/Dumb) - Dumain Bruteforcer - a fast and flexible domain bruteforcer *(archived)*
