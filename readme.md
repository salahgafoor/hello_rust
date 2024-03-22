# Welcome to world of Rust
## Setting up things
* For online IDE : [Rust Playground](https://play.rust-lang.org/?version=stable&mode=debug&edition=2021&ref=inpyjama.com)

* For Windows : [Install Rust up](https://www.rust-lang.org/tools/install)

Note: You may need to install the Visual Studio C++ Build tools when prompted to do so

## Make use of Cargo
Cargo is the built-in build system and package manager for Rust. This project has been created using Cargo.
If you want to create a new project using Cargo

`cargo new <project_name>`

This will create a new directory named `project_name` called workspace and `Cargo.toml`, `src/`, `.gitignore` are also created along with that. Basically this command also setup a git repo for our project.

## Building and running the project
Navigate to the workspace and execute.

`cargo build`

To run the project

`cargo run`