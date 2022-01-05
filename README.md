# HAPEBEAST #coding-cave Resources #

A curated list of resources, libraries, frameworks and tools for the [HAPEBEAST](https://www.hapebeast.com/) `#coding-cave` discord channel.

![HAPE](images/hape-image.jfif)

## Preface ##

This is a list of useful resources for software development and programming in general. These resources are targetted at the most common questions and topics in the `#coding-cave` channel. I've also added resources that I think are the are most commonly used in the industry and/or are useful for development in the software industry. I've tried to keep the list concise and precise for less experienced programmers. For more resources on even more advanced topics, checkout [awesome](https://github.com/sindresorhus/awesome).

I hope you find something useful that helps you in developing your career or finishing your personal projects!

Also, if your havent checked out the [pinned Notion page](https://hapebeast.notion.site/hapebeast/HAPEBEAST-coding-cave-28adceeed4c64dac85ccdb36216f81f9) yet, please do. It has very helpful and beginner friendly guides on various topics written by other HAPES.

## Git ##

Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

- [Git Flow Cheat Sheet](https://github.com/arslanbilal/git-cheat-sheet#readme) - Git cheat sheet that saves you from learning all the commands by heart.

- [Git-tips](https://github.com/git-tips/tips#readme) - Most commonly used git tips and tricks.

- [GitHub](https://github.com/) - The most popular hosting service for Git repositories:

  - [Official GitHub Courses](https://lab.github.com/)

  - [GitHub Cheat Sheet](https://github.com/tiimgreen/github-cheat-sheet#readme)

## Programming Languages ##

### **Python** ###

[Python](https://www.python.org/) is an interpreted, object-oriented, high-level programming language with dynamic semantics.

Package Managers:

- [pip](https://pip.pypa.io/en/stable/) - The package manager for Python.
  - [pip-tools](https://github.com/jazzband/pip-tools) - Tools for keeping your python packages up to date.
  - [PyPI](https://pypi.org/) - Repository of software for the Python programming language.
- [conda](https://github.com/conda/conda/) - Cross-platform, Python-agnostic binary package manager.
- [poetry](https://github.com/sdispater/poetry) - Python dependency management and packaging made easy.

Environment Management:

- [pyenv](https://github.com/pyenv/pyenv) - Simple Python version management.
- [virtualenv](https://github.com/pypa/virtualenv) - Tool to create isolated Python environments.

Web Frameworks:

- [Django](https://www.djangoproject.com/) - The most popular web framework in Python.
- [Flask](http://flask.pocoo.org/) - Microframework for Python.

RESTful APIs:

- Django
  - [django-rest-framework](http://www.django-rest-framework.org/) - Powerful and flexible toolkit to build web APIs.
  - [django-tastypie](http://tastypieapi.org/) - Webservice API framework for Django.
- Flask
  - [eve](https://github.com/pyeve/eve) - Open source Python REST API framework using Flask and MongoDB.
  - [flask-api](https://github.com/flask-api/flask-api) - Browsable Web APIs for Flask.
- [FastAPI](https://fastapi.tiangolo.com/) - Web framework for building APIs.

Game Development:

- [Pygame](http://www.pygame.org/news.html) - Set of Python modules designed for writing games.
- [Arcade](https://api.arcade.academy/en/latest/) - Modern Python framework for crafting games with compelling graphics and sound.
- [Cocos2d](http://cocos2d.org/) - Framework for building 2D games, demos, and other graphical/interactive applications.

GUI Development:

- [Tkinter](https://wiki.python.org/moin/TkInter) - Python's de-facto standard GUI package.
- [curses](https://docs.python.org/3/library/curses.html) - Built-in wrapper for [ncurses](http://www.gnu.org/software/ncurses/) used to create terminal GUI applications..
- [PyQt](https://riverbankcomputing.com/software/pyqt/intro) - Python bindings for the [Qt](https://www.qt.io/) cross-platform application and UI framework.

Data Visualisation:

- [Matplotlib](http://matplotlib.org/) - Python 2D plotting library.
- [Seaborn](https://github.com/mwaskom/seaborn) - Statistical data visualization using Matplotlib.

Deep Learning:

- [keras](https://github.com/keras-team/keras) - High-level neural networks library and capable of running on top of either TensorFlow or Theano.
- [pytorch](https://github.com/pytorch/pytorch) - Tensors and Dynamic neural networks in Python with strong GPU acceleration.
- [tensorflow](https://github.com/tensorflow/tensorflow) - The most popular Deep Learning framework created by Google.

Testing:

- [pytest](https://docs.pytest.org/en/latest/) - Mature full-featured Python testing tool.

Tutorials and Guides:

- [Full Stack Python](https://www.fullstackpython.com/)
- [Python Cheatsheet](https://www.pythoncheatsheet.org/)
- [Real Python](https://realpython.com)
- [The Hitchhiker’s Guide to Python](https://docs.python-guide.org/)
- [Ultimate Python study guide](https://github.com/huangsam/ultimate-python)

### **JavaScript** ###

[JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) is an object-oriented programming language commonly used within web browsers.

[TypeScript](https://www.typescriptlang.org/) - Superset of the JavaScript language that compiles to JavaScript.

Package Managers:

- [npm](https://docs.npmjs.com/cli/v8/commands/npm) - JavaScript Package Manager.
- [yarn](https://yarnpkg.com/) - Fast, reliable, and secure dependency management.

Frameworks and Libraries:

- [angular](https://github.com/angular/angular) - Development platform for building mobile and desktop web applications using Typescript/JavaScript and other languages.
- [react](https://reactjs.org/) - JavaScript library for building user interfaces.
- [react native](https://reactnative.dev/) - Framework that brings React's declarative UI framework to iOS and Android.
- [vue](https://github.com/vuejs/vue) - Progressive framework for building user interfaces on the web.
- [svelte](https://github.com/sveltejs/svelte) - Compiler that takes your declarative components and converts them into efficient JavaScript that surgically updates the DOM.

API:

- [axios](https://github.com/axios/axios) - Promise-based HTTP Client for node.js and the browser.

Data Visualization:

- [d3](https://github.com/d3/d3) - JavaScript visualization library for HTML and SVG.
- [three.js](https://github.com/mrdoob/three.js) - JavaScript 3D library.

Testing Frameworks:

- [mocha](https://github.com/mochajs/mocha) - Simple, flexible, fun JavaScript test framework for node.js & the browser.
- [jasmine](https://github.com/jasmine/jasmine) - DOM-less simple JavaScript testing framework.
- [chai](https://github.com/chaijs/chai) - BDD / TDD assertion framework for node.js and the browser that can be paired with any testing framework.

QA Tools:

- [prettier](https://github.com/prettier/prettier) - Opinionated code formatter.
- [ESLint](https://github.com/eslint/eslint) - Tool for identifying and reporting on patterns found in ECMAScript/JavaScript code.

Articles, Tutorials and Reads:

- [How JavaScript works](https://blog.sessionstack.com/tagged/tutorial) - Series of articles on how JavaScript works under the hood.
- [Web-workers for multi-threading](https://www.loginradius.com/blog/async/adding-multi-threading-to-javascript-using-web-workers/) - Tutorial on adding multi-threading to JavaScript.
- [this keyword](https://www.loginradius.com/blog/async/breaking-down-this-keyword-in-javascript/) - Everything you need to know about the `this` keyword.
- [JS Tutorials](https://hackr.io/tutorials/learn-javascript) - List of popular JavaScript tutorials.
- [Clean Code JavaScript](https://github.com/ryanmcdermott/clean-code-javascript) - Guide on writing clean JavaScript.
- [ECMAScript 6](http://es6-features.org/#Constants) - JavaScript syntax features.

### **Solidity** ###

[Solidity](https://github.com/ethereum/solidity) is an object-oriented programming language for writing smart contracts on various blockchain platforms, most notably Ethereum.

Official Links:

- [Docs](https://docs.soliditylang.org/en/latest/) - Official documentation.
- [Cheatsheet](https://docs.soliditylang.org/en/latest/cheatsheet.html) - Cheatsheet from the official docs.
- [Ethereum Wiki](https://github.com/ethereum/wiki/wiki) - The Ethereum Wiki.
- [Ethereum Stackexchange](https://ethereum.stackexchange.com/) - Ethereum's Stackexchange board.
- [Gitter](https://gitter.im/ethereum/solidity/) - Gitter channel.
- [ethereum/solidity-examples](https://github.com/ethereum/solidity-examples) - Loose collection of example code.

Development Frameworks:

- [Hardhat](https://hardhat.org/) - Development environment to compile, deploy, test, and debug your Ethereum software.
- [Brownie](https://github.com/eth-brownie/brownie) - Python-based development and testing framework for smart contracts targeting the Ethereum Virtual Machine.
- [Truffle](https://github.com/trufflesuite/truffle) - Development environment, testing framework and asset pipeline for Ethereum.

Libraries:

- [OpenZeppelin](https://github.com/OpenZeppelin/openzeppelin-contracts) - Library for secure smart contract development.

Tutorials:

- [CryptoZombies](https://cryptozombies.io) - Interactive code school that teaches you to write smart contracts through building your own crypto-collectibles game.
- [buildspace.so](https://buildspace.so/) - Hands-on Web3 course especially for beginners. It is completely free and you get an NFT on completion.
- [cryptodevhub.io](https://cryptodevhub.io/) - Community-driven effort to unite like-minded people interested in Blockchain- and Crypto Technologies.
- [Official Ethereum Tutorials](https://ethereum.org/en/developers/tutorials/) - Ethereum community tutorials by topic.

### **Java** ###

[Java](https://www.java.com/en/) is a programming language and computing platform used to power a large share of today’s digital world, by providing the reliable platform on which many services and applications are built.

[Java Development Kit (JDK)](https://java.com/en/download/help/develop.html) - Includes the Java Runtime Environment, the Java compiler and the Java APIs.

GUI:

- [JavaFX](https://wiki.openjdk.java.net/display/OpenJFX/Main) - Successor of Swing.
- [Scene Builder](https://gluonhq.com/products/scene-builder/) - Visual layout tool for JavaFX applications.
- [SWT](https://www.eclipse.org/swt/) - Graphical widget toolkit.

REST Frameworks:

- [Spark](http://sparkjava.com) - Sinatra inspired framework.

Frameworks:

- [Apache JMeter](http://jmeter.apache.org) - Functional testing and performance measurements.
- [JUnit](https://junit.org/junit5/) - Common testing framework.

QA Tools:

- [Mockito](https://github.com/mockito/mockito) - Mocking framework that lets you write tests with a clean and simple API.
- [Clover](https://www.atlassian.com/software/clover) - Relies on source-code instrumentation instead of bytecode instrumentation.
- [Cobertura](https://cobertura.github.io/cobertura/) - Relies on offline (or static) bytecode instrumentation and class loading to collect code coverage metrics. (GPL-2.0-only).

Caching:

- [Ehcache](http://www.ehcache.org) - Distributed general-purpose cache.

Build:

- [Apache Maven](https://maven.apache.org) - Declarative build and dependency management that favors convention over configuration.
- [Gradle](https://gradle.org) - Incremental builds programmed via Groovy instead of declaring XML. Works well with Maven's dependency management.

Game Development:

- [FXGL](https://almasb.github.io/FXGL/) - JavaFX Game Development Framework.
- [libGDX](https://libgdx.com) - All-round cross-platform, high-level framework.
- [LWJGL](https://www.lwjgl.org) - Robust framework that abstracts libraries like OpenGL/CL/AL.

Links and Tutorials:

- [Guru99 Java Tutorials](https://www.guru99.com/java-tutorial.html)
- [Google Java Style](https://google.github.io/styleguide/javaguide.html) - Google's coding standard for Java.
- [Java Algorithms and Clients](https://algs4.cs.princeton.edu/code) - Java programs covering various algorithms and clients.

### **C++** ###

[C++](https://isocpp.org/) is a general-purpose programming language created as an extension of the C programming language, or "C with Classes".

Standard Libraries:

- [C++ Standard Library](https://en.wikipedia.org/wiki/C%2B%2B_Standard_Library) - Collection of classes and functions, which are written in the core language and part of the C++ ISO Standard itself.
- [Standard Template Library](https://en.wikipedia.org/wiki/Standard_Template_Library) - The Standard Template Library (STL).
- [ISO C++ Standards Committee](https://github.com/cplusplus) - ISO/IEC JTC1/SC22/WG21 - The C++ Standards Committee. [website](http://www.open-std.org/JTC1/SC22/WG21/)

Compilers:

- [Clang](http://clang.llvm.org/) - C compiler for LLVM. Supports C++11/14/1z C11. Developed by LLVM Team.
- [GCC](https://gcc.gnu.org/) - GNU Compiler Collection. Supports C++11/14/1z C11 and OpenMP.
- [Intel C++ Compiler](https://software.intel.com/en-us/c-compilers) - Developed by Intel.
- [LLVM](http://llvm.org/) - Collection of modular and reusable compiler and toolchain technologies.

Build Systems:

- [CMake](https://cmake.org/) - Cross-platform free and open-source software for managing the build process of software using a compiler-independent method.

Frameworks:

- [Boost](https://github.com/boostorg) - Large collection of generic C++ libraries. [website](http://www.boost.org/)

Graphics:

- [DirectXTK](https://github.com/Microsoft/DirectXTK) - Collection of helper classes for writing DirectX 11.x code in C++.
- [GLFW](https://github.com/glfw/glfw) - Simple, cross-platform OpenGL wrangling library.

Multimedia:

- [SDL](http://www.libsdl.org/)- Simple DirectMedia Layer.
- [SFML](https://github.com/SFML/SFML)- Simple and Fast Multimedia Library.

Links and Tutorials:

- [C++ Core Guidelines](https://github.com/isocpp/CppCoreGuidelines) - "Official" set of C++ guidelines, reviewed by the author of C++.
- [C++ Dos and Don'ts](http://www.chromium.org/developers/coding-style/cpp-dos-and-donts) - The Chromium Projects > For Developers > Coding Style > C++ Dos and Don'ts.
- [google-styleguide](https://github.com/google/styleguide) - Style guides for Google-originated open-source projects.
- [C++ reference](http://cppreference.com/) - C++98, C++03, C++11, C++14 reference.
- [C++ by Example](http://www.cbyexample.com/) - Learn C++ by Example.
- [cplusplus.com](http://www.cplusplus.com/) - The C++ Resources Network.
- [C++ tutorial](https://hackr.io/tutorials/learn-c-plus-plus) - User ranked online tutorial bank site displaying multiple courses to learn C++ from.

### **Rust** ###

[Rust](https://www.rust-lang.org/) is a multi-paradigm, general-purpose programming language designed for performance and safety, especially safe concurrency.

[Cargo](https://crates.io/) is the package manager for Rust.

Cryptocurrencies:

- [Bitcoin Satoshi's Vision](https://github.com/brentongunning/rust-sv) [[sv](https://crates.io/crates/sv)] — A Rust library for working with Bitcoin SV .
- [ChainX](https://github.com/chainx-org/ChainX) — Fully Decentralized Interchain Crypto Asset Management on Polkadot.
- [Holochain](https://github.com/holochain/holochain) — Scalable P2P alternative to blockchain for all those distributed apps you always wanted to build.
- [Polkadot](https://github.com/paritytech/polkadot) — Heterogeneous multi‑chain technology with pooled security
- [rust-bitcoin](https://github.com/rust-bitcoin/rust-bitcoin) — Library with support for de/serialization, parsing and executing on data structures and network messages related to Bitcoin.
- [rust-cardano](https://github.com/input-output-hk/rust-cardano) — Rust implementation of Cardano primitives, helpers, and related applications
- [Solana](https://github.com/solana-labs/solana) — Incredibly fast, highly scalable blockchain using Proof-of-History.

Tutorials and Learning:

- [Easy Rust](https://github.com/Dhghomon/easy_rust) - Learn Rust in easy English.
- [exercism.org](https://exercism.org/tracks/rust) — programming exercises that help you learn new concepts in Rust.
- [Rust Cookbook](https://rust-lang-nursery.github.io/rust-cookbook/) — Collection of simple examples that demonstrate good practices to accomplish common programming tasks, using the crates of the Rust ecosystem.
- [Rust for professionals](https://overexact.com/rust-for-professionals/) — Quick introduction to Rust for experienced software developers.
- [Rustlings](https://github.com/rust-lang/rustlings) — Small exercises to get you used to reading and writing Rust code

## Web 3.0 ##

Chainlink

## Machine Learning ##

## Programming Paradigms ##

### Object-Oriented Programming (OOP) ###

### Functional Programming ###

## Algorithms and Data Structures ##

## Contributing ##

I am by no means an expert on all or any of these topics, so if you would like to add to this list (or remove anything less relevant from the list), check out `CONTRIBUTING.md` or ping me on discord (`#! donutboy | HAPEBEAST`). HAPES TOGETHER STRONG!

This resource was inspired by [awesome](https://github.com/sindresorhus/awesome).
