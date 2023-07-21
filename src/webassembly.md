# WebAssembly basics

WebAssembly (WASM) is a binary instruction format designed to bring more languages to web browsers (historically, Javascript was the only available choice.) WASM is designed as a portable target for compilation of high-level languages like Rust, enabling it to be used in web applications. WASM has also grown beyond its scope because it can be run in a number of use cases beyond the web, including [nodejs](https://nodejs.dev/en/learn/nodejs-with-webassembly/) or the [Ethereum WebAsssembly Runtime](https://ewasm.readthedocs.io/en/mkdocs/README/)

Rust is often considered as one of the best languages to compile to WebAssembly due to its safety, performance, and rather expansive WASM ecosystem.

# Setting up the environment

There are multiple frameworks to create WASM libraries from Rust. We will focus on [wasm-pack](https://rustwasm.github.io/docs/wasm-pack/introduction.html) and [wasm-bindgen](https://rustwasm.github.io/wasm-bindgen/).

WebAssembly needs to be run in a Browser or a VM, therefore we will use a different set up for this class. Please navigate to [rust-wasm-template](https://github.com/google/comprehensive-rust/tree/main/src/rust-wasm-template) to view the installation instructions. Feel free to either clone the repository to run it locally, or open a new [Codespace on Github](https://codespaces.new/google/comprehensive-rust)