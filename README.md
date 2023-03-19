
# Rust guessing number game

This is a fun "guess the number" game built in Rust that you can play from your terminal. It's made by following [this tutorial](https://doc.rust-lang.org/book/ch02-00-guessing-game-tutorial.html).

To run it, you'll need Rust and Cargo installed on your machine. If you don't have them yet, I've included instructions on how to install them.

## How to play

If you are already using Rust and Cargo, just clone this repository, open it from your terminal and run `cargo run`.

Here are the commands to copy paste:

```shell
git clone git@github.com:juliamrch/rust-guessing-game.git
cd rust-guessing-game
cargo run
```

The game will end once you've guessed the correct number. You can also quit the game sooner by typing `control + C`.

If you don't have Rust and Cargo installed yet, don't worry, the installation is quick and painless. Just follow these instructions:

### Installing `rustup` on Linux or macOS

If you’re using Linux or macOS, open a terminal and enter the following command:

`curl --proto '=https' --tlsv1.2 https://sh.rustup.rs -sSf | sh`

You'll need a _linker_  which is a program that Rust uses to join its compiled outputs into one file. If you don't have one installed yet, run:

`xcode-select --install`

### Installing `rustup` on Windows

On Windows, go to [Rust official page](https://www.rust-lang.org/tools/install) and follow the instructions for installing Rust. At some point in the installation, you’ll receive a message explaining that you’ll also need the MSVC build tools for Visual Studio 2013 or later.

To acquire the build tools, you’ll need to install Visual Studio 2022. When asked which workloads to install, include:

“Desktop Development with C++”
The Windows 10 or 11 SDK
The English language pack component, along with any other language pack of your choosing