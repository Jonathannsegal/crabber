# Crabber 🦀

![Crates.io](https://img.shields.io/crates/d/crabber)
[![Crates.io](https://img.shields.io/crates/v/crabber)](https://crates.io/crates/crabber)
![Crates.io](https://img.shields.io/crates/l/crabber)
[![HitCount](http://hits.dwyl.com/jonathannsegal/crabber.svg)](http://hits.dwyl.com/jonathannsegal/crabber)

## A pointless cli game made in rust

![Gameplay](https://drive.google.com/uc?id=1zJkETfoG7qWq6VmUDMwavvGWljev3AtX)

This is just me playing around with [Rust](https://www.rust-lang.org/) I wanted to make something simple to understand the language on a basic level. This game is kinda like whack a mole where you are 🦀 [ferris the crab](https://rustacean.net/) and you use the arrow keys to move around and squash the bugs.

<div style="background-color: #FAD64C; text-align: center">
<span>
🐛🐛🐛🐛🐛 <br>
🐛🐛🦀🐛🐛 <br>
🐛🐛🐛🐛🐛 <br>
</span>
</div>

## Running Locally 💻

Make sure you have rust installed. The easiest way to do this is with [rustup](https://www.rust-lang.org/learn/get-started)

```bash
$ git clone https://github.com/Jonathannsegal/crabber.git
$ cd crabber
$ cargo run
```

## Install with [crates.io](https://crates.io/crates/crabber) 📦

```bash
$ cargo install crabber
$ crabber
```

This installs the binary to the bin in your rust folder and allows you to run the program.

## TODO 🛠️
- Add support for non emoji terminals
- Package in such a way where you dont need rust locally
- Add an objective
- Use multithreading for input and clock

## Known Issues 🤫
- This only works with terminal emulators that support emojis, command prompt does not if your on windows you can use [Windows Terminal](https://github.com/microsoft/terminal)