Usefull-Rust-Project
====================

List of community wanted important libraries.

This repo is meant to be used as a list of the community wanted libraries, whether they are already
started and need more hands to be improved / maintained, or if they have to be started from scratch.
Working on having libraries to support the language is at least as important as the language itself and
is a great way to get more familiar with the language.

The point is also to have a place for coders looking to contribute to Rust to find what is really needed.

(it's without shamelessly inspired from @brson [rust links](http://brson.github.io/rustlinks.html), the reason
is mainly to have a community repository that evolves with time instead of a static page)

Feel free to add new projects / libraries via pull requests.

Looking for maintainer
----------------------

* [wxRust](https://github.com/kenz-gelsoft/wxRust) : a wxWidgets bindings.
* [Rust by Example](https://github.com/rust-lang/rust-by-example) : High-quality, well-organized code snippets.
* [rust-windows](https://github.com/klutzy/rust-windows) : work-in-progress Win32/Win64 wrapper for Rust.


Important libraries which could use more contributors
-----------------------------------------------------

* [capnproto-rust](http://rust-ci.org/dwrensha/capnproto-rust) :  Cap'n'Proto implementation. Very high performance cross-process, cross-language messaging.
* [dbgr.cc](http://dbgr.cc/) :  An web-based editor and *debugger*, with Rust support. Potentially useful for newbies.
* [docopt.rs](https://github.com/docopt/docopt.rs) : Better command line argument parsing.
* [gfx-rs](https://github.com/bjz/gfx-rs) : Graphics stack.
* [gl-rs](https://github.com/bjz/gl-rs) : OpenGL.
* [glfw-rs](https://github.com/bjz/glfw-rs) : GLFW handles window setup and input for games.
* [IntelliJ IDEA plugin](http://plugins.jetbrains.com/plugin/7438) : Text editor support is fundamental 
* [Iron](https://github.com/iron/iron) : Web stack. Significance: a pluggable middleware stack. Lets HTTP ecosystem evolve piecemeal.
* [Kiss3D](http://rust-ci.org/sebcrozet/kiss3d) : 3D game engine.
* [nickle.rs](http://nickel.rs/) : Web framework.
* [libovr-rs](https://github.com/csherratt/vr-rs) : Rust bindings to the Occulus Rift.
* [nphysics](http://rust-ci.org/sebcrozet/nphysics) : Rigid-body physics engine. Significance: gaming infrastructure.
* [Piston](http://www.piston.rs/) : User-friendly game engine.
* [Racer](http://github.com/phildawes/racer) :  Rust code completion. Tooling.
* [rust-bindgen](http://rust-ci.org/crabtw/rust-bindgen) : Automatically generate C bindings for Rust.
* [rust-chrono](https://github.com/lifthrasiir/rust-chrono) : Time library. Rust needs one.
* [rust-crypto](http://rust-ci.org/DaGenix/rust-crypto) : Pure-Rust crypto. Significance: crypto is an obvious domain for Rust.
* [rust-csv](https://github.com/BurntSushi/rust-csv) : A CSV parser with type based decoding for Rust.
* [Rust-Empty](https://github.com/bvssvni/rust-empty/) : Popular Makefile template. Significance: making users' lives better.
* [rust-encoding](http://rust-ci.org/lifthrasiir/rust-encoding) : Character encoding. Significance: Rust currently lacks support for most non-utf8 encodings.
* [rust-lua](http://rust-ci.org/kballard/rust-lua) : Significance: some types of apps are going to want to pair Rust with a scripting language. Lua is a good one.
* [rust-openssl](http://rust-ci.org/sfackler/rust-openssl) : OpenSSL bindings.
* [rust-playpen](https://github.com/rust-lang/rust-playpen) : A web interface for running Rust code built using playpen.
* [rust-postgres](http://github.com/sfackler/rust-postgres) : A mature native postgres driver.
* [rust-protobuf](http://rust-ci.org/stepancheg/rust-protobuf) : Implementation of popular data transfer protocol.
* [RustPy](https://github.com/lukemetz/rustpy) : Interop between Rust and Python. Significance: embedding Rust in other stacks is one of Rust's major opportunities.
* [rust-rosetta](https://github.com/hoverbear/rust-rosetta) : Code examples.
* [rustsqlite](http://rust-ci.org/kud1ing/rustsqlite) : Bindings to the best database ever.
* [rust-sdl2](http://rust-ci.org/AngryLawyer/rust-sdl2) : Bindings to SDL2. Popular game-oriented OS abstraction layer, like GLFW. Significance: popular with game programmers, Valve-supported.
* Rust standard library in the [main repository](https://github.com/rust-lang/rust).
* [rust-url](https://github.com/lifthrasiir/rust-url) : Spec-correct URL handling, used by Servo.
* [rust-xml](https://github.com/netvl/rust-xml) : XML. SAX-like. Significance: everybody needs a little XML.
* [RustyXML](https://github.com/Florob/RustyXML) : XML. SAX-like. Significance: everybody needs a little XML.
* [suruga](https://github.com/klutzy/suruga) : TLS in Rust.
* [TeePee](https://github.com/teepee/teepee) : HTTP implementation used by servo.
* [Tiny HTTP](https://github.com/tomaka/tiny-http) : HTTP implementation.
* [Turbine](https://github.com/polyfractal/Turbine) : LMAX Disruptor clone. Very high perf message passing. Significance: need more concurrency libs, prove Rust's suitability for parallel programming.
* [uutils](https://github.com/uutils/coreutils) : Reimplementation of GNU coreutils (command line utilities). Signifance: busybox-killer. Embedded market.
* [VisualRust](https://github.com/PistonDevelopers/VisualRust) : Visual Studio extension for Rust.
* [zinc.rs](http://zinc.rs/) : 'The bare metal stack for Rust'. Makes Rust viable on embedded kits like Arduino, etc. Significance: lots of opportunity in embedded markets, 'Internet of Things', etc. 

TODO from scratch
---------------------

* Either a port or a binding of [Reactivex*](https://github.com/ReactiveX/RxJava), significance : functionnal reactive programming is
a programming paradigm with increasing popularity.
