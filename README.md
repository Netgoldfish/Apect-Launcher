 remake this file to make it fancier:

# Apect Launcher - Installation & Compilation Guide


Welcome to the **Apect Launcher** project! This guide will walk you through setting up the Rust environment on your machine and compiling the project from source.


## 🚀 Prerequisites


Before you begin, ensure your system is up to date. This project is built using the Rust programming language and requires the `cargo` package manager.


---


## 1. Install Rust (rustup)


The recommended way to install Rust is through `rustup`, which manages Rust versions and associated tools.


### On Linux (Mint, Ubuntu, Debian, etc.) or macOS

Open your terminal and run:

## Cargo Build

Restart your terminal or run source $HOME/.cargo/env to apply changes.

## On Windows

Download and run rustup-init.exe.

 You will likely need the C++ build tools for Visual Studio 2013 or later. The installer will prompt you if they are missing.

## 2. Install System Dependencies


Depending on your OS, you may need specific libraries for the GUI and networking components.

Linux (Debian/Ubuntu/Mint) 

### sudo apt update

#### sudo apt install build-essential pkg-config libssl-dev libdbus-1-dev libgtk-3-dev


## 3. Clone the Project


Clone the repository to your local machine:

### git clone [https://github.com/netgoldfishtoo/Apect-Launcher/]

### cd ApectLauncher


## 4. Compiling and Running

Development Mode


To compile and run the project immediately:

### cargo run


This will download all 900+ dependencies (this may take a while on the first run).

The binary will be compiled with debug symbols (slower execution, but faster compilation).


Release Mode (Optimized)


For the best performance and smallest file size, compile in release mode:

Bash


### cargo build --release


The resulting executable will be located at ./target/release/apect. 
