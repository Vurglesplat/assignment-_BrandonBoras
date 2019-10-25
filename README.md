# CSI281 Assignment 8

In this assignment you will be implementing a graph method, `edgeExists()`, and two search methods `dfs()` and `bfs()`, for breadth-first and depth-first search respectively. The rest of a `Graph` class is already implemented for you. It has some useful debug print methods you can use as well.

You should follow the pseudo-code we went over in class. You may not add any additional methods to `Graph`. You should just fill in the existing ones.

In addition there are some questions for you to answer in `questions.txt`.

## Basic Instructions

1. Download the contents of this repository.
2. Create your own private repository and add the contents of this repository to it.
3. Add me (@davecom) as a collaborator on your private repository.
4. Implement the missing parts where it says "YOUR CODE HERE"
5. Test it by following the build directions below.
6. Answer all of the questions in `questions.txt` in your own file `answers.txt`.
7. Submit the URL to your private repository on Canvas.

## Standard Library Restrictions

There are no standard library restrictions.

## Directory Structure and Files

- `/` Main directory including this `README.md`, the build scripts, the make files, and `questions.txt`.
- `/lib` Library testing your work. There's no need to touch this.
- `/src` Source files, some of which you should modify and some of which you should not.

### Specific Files

*indicates do not modify
&indicates you must modify
%indicates you must create

- `GNUMakefile`* make file for GNU Make on macOS and GNU/Linux
- `Makefile`* make file for nmake/Visual Studio on Windows
- `README.md`* this file
- `LICENSE` MIT License
- `questions.txt`* Questions that you are expected to answer.
- `answers.txt`% Your answers to the questions in `questions.txt`

- `lib/catch.h`* a unit testing library

- `src/Graph.h`& the `Graph` class
- `src/main.cpp` the main file that runs the tests and makes the chart
- `src/test.cpp`* the unit tests to prove your code works

## Building and Running

### macOS and GNU/Linux

CD to the appropriate directory and run `make` and `./assignment8` to run all of the tests. Run `make clean` to remove all objects files, and the executable.

### Windows

From the start menu (assuming you have installed Visual Studio 2019) open the "Developer Command Prompt." CD to the appropriate directory and run `nmake` and `assignment8` to run all of the tests. Run `nmake clean` to remove all objects files, and the executable.

## Checklist for Submission

- [ ] Did you add me (@davecom) as a collaborator on the repository?
- [ ] Did you replace every area that said "YOUR CODE HERE" with your code?
- [ ] Did you ensure you are passing all of the unit tests?
- [ ] Did you cite all sources, especially any place that you copied code from? Put code citations right next to where you inserted it.
- [ ] Did you add sufficient comments?
- [ ] Did you double check your code for good style?
- [ ] Did you remember to free any memory you manually allocated on the heap?
- [ ] Did you put your name below mine at the top of any files you modified and any other appropriate places?
- [ ] Did you try cleaning, building, and running once to make sure everything is in working order before submitting?
- [ ] If you were working with an IDE, did you test building on the command line with make or nmake? I will only test your work with make or nmake.
- [ ] Did you check the repository is free of your object files and other garbage and just contains source files?
- [ ] Did you remember to include your `answers.txt` file with answers to every question?
- [ ] Did you implement tests to check every method in your code?
- [ ] Did you submit the URL to your repository on Canvas?
