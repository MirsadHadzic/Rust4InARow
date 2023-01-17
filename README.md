# Rust4InARow

![alt text](https://github.com/MirsadHadzic/Rust4InARow/blob/master/images.png)


# Quick Overview

4-in-a-Row // Connect Four is a two-player connection board game, in which the players choose a color and then take turns dropping colored tokens into a vertically suspended grid. Whichever player manages to connect 4 tokens of the same color horizontally, vertically or diagonally wins the game.

This project was implemented in Ruby programming language, for purposes of IT 305 Programming Languages course at International Burch University.

In this project, we created the logic of a Connect 4 game, and were able to display it in ASCII form for the user to play in the terminal.
We wrote this software as a way of learning the language Rust.

# About Rust

Rust is a systems programming language that was invented by Graydon Hoare, a Mozilla employee, in 2006. He started working on the language as a personal project, with the goal of creating a systems programming language that would be safe from memory-related bugs such as buffer overflows and use-after-free errors.

In 2010, Mozilla became involved in the project and began sponsoring its development. Over the next few years, the language matured and grew in popularity, with version 1.0 of the language being released in May 2015.

Since then, Rust has continued to evolve and improve, with new features and tools being added to the language on a regular basis.

One of the key features of Rust is its emphasis on safety. The language provides a number of built-in safety mechanisms that help prevent common programming errors such as null or dangling pointer references. This is achieved through a combination of a strict type system, automatic memory management (through the use of a garbage collector), and a borrow checker that enforces strict ownership and lifetime rules.

Today, Rust is a widely-used language with a large and active community of users and developers.

# Team members

Colleagues that worked with me are:
- Iman Lukomirak (https://github.com/imanll)
- Faris Kovac (https://github.com/Faris-Kovac)

# Environment

For this project, we needed to install VS Code, Rust, the Rust extension in Visual Studio Code, and create a rust project through the command prompt.
For this project, we didn't need to import lots of libraries. The only library we needed was std. This allowed us to use std::io:stdin() for getting input from the user, and std::process::exit() to kill the program when necessary.

# Useful Websites
1. https://www.rust-lang.org/tools/install
2. https://stackoverflow.com/questions/30355185/how-to-read-an-integer-input-from-the-user-in-rust-1-0

# Running the project
To run the project, you will first need to install Rust. You can find detailed instructions on this link (https://www.rust-lang.org/tools/install).
If you want to run the rust file, go to VS Code and click on Run button. Way to run in terminal is to cd and give the path of the file, then type in rustc main.rs

