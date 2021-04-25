# An Introduction to Zero-Knowledge Development

This tutorial will introduce you to the [arkworks-rs](https://arkworks.rs) ecosystem for developing and programming SNARKs.

## Requirements

In order to best assist you during the tutorial (and share common development environment) you should have installed:

+ The Rust programming language;
+ [Git](https://git-scm.com/downloads);
+ [Visual Studio Code](https://code.visualstudio.com/);
+ [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=matklad.rust-analyzer), a Rust extension for Visual Studio Code;

You can install Rust using [rustup](https://rustup.rs/) (and it doesn't require root!). To install Visual Studio Code and rust-analyzer, just head over to their respective page.
Git will be needed solely to clone the repository and quickly get back to a consistent state if you messed things up :)

## Building and running
 To compile, clone this repository using `git` and `cd` into the folder. Then, run:

 ```rust
 cargo build
 ```


## From previous readme
Include panic = 'abort' in your release profiles within cargo.toml
