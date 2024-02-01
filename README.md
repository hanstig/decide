# DD2480 - DECIDE

## About

This is a theoretical program for an anti-ballistic missile system, implemented in C++ according to the requirement specifications. The program decides through multiple different input variables whether to launch or not launch a missile, outputting "YES" or "NO".

The variables are collected through theoretical instruments, but in this project the input variables are set through a constructor class. Afterwards, the decode method can be executed in order to determine if a launch should be made, needing to pass 15 "LIC's" which are functions that check the input data against certain conditions.

Each LIC's have different conditions, and in order to understand these, each LIC has at least two unit tests, one positive and one negative, and sometimes additional tests. Furthermore, there are tested for the entire launch program.

## Prerequisites

Before downloading the source code and atempting to build the project, ensure you have the following requirements:

* You have installed one of the following C++ compilers: 'GCC' or 'clang'.
* You have installed 'cmake' and 'make'.
* You have a 'Linux/Mac/Windows' machine.

## How To Build

To build with `cmake`

```bash
mkdir build && cd build
cmake ..
make
```

## Run and Test

To run the program

```bash
cd build
```

```bash
./decide ../test/example_input.txt
```

To run the tests

```bash
cd build
```

```bash
./CMVTest
```

## Contributing to DECIDE

To contribute to the DICDE code, follow these steps:

1. Fork this repository
2. Create a branch: `git checkout -b <branch_name>`
3. Add changes and commit them, if possible link to a relevant issue: `git commit -m '<commit_message>'`
4. Fetch and merge into main: `git merge origin/main`
5. Resolve any merge issues, push to remote: `git push -u origin <branch-name>`
6. Create a pull request to merge into main.

Pull request will be reviewed before being accepted.

## Dependecncies

Here are the dependecies used:

* [**Google Test**](https://google.github.io/googletest/primer.html): A testing framework for C++ programming, used for unit testing in this project.

## Contributions

Ahmed:

* write here

ZOU Hetai (Ed):

* Implemeted LIC 1, 6, and 11
* Implemented multiple unit tests for LIC 1, 6, and 11. (9 in total)
* Contributed to create the build system using MakeFile and CMake.
* Contributed to create the unit test system using Google Test.
* Contributed to managing and creating issues, reviewing colleagues pull requests and discussing different implementation methods.
* Detailed the README file about the build instructions and the unit test instructions.

Elliot:

* Implemented LIC 2, 7 and 12
* Implemented multiple unit tests for LIC 2, 7, 12. (9 in total)
* Contributed to managing and creating issues, reviewing colleagues pull requests and discussing different implementation methods.
* Implemented the CMV function.
* Debugging and solving bug issues related to the LIC's.
* Expanded the README file to enhance its content and structure. Also writing the about, prerequisites and dependencies section.

Hannes:
- Did some work on creating a skeleton structure for the decide class
- Implemented LIC 3, 8 and 13 
- Implmented unit test for said LIC methods (9 in total)
- Implemented the Calc_PUM() Method
- Helped manage git workflow by reviewing pull requests and resolving merge conflicts.
- Implemeted some tests for the whole decide program. 

Yening:

* Implemented LIC 4, 9 and 14.
* Implemented multiple unit tests for LIC 4, 9, 14.
* Implemented the FUV function.
* Helped documenting unit tests for LICs.

## Essence

Assessing the workflow within the team, we have come to the conclusion that our Way-of-Working is currently at the state of **In-Use**. Specifically we have reached the point of “Procedures are in place to handle feedback on the team’s way of working”. 

Looking at the two previous states, they are related to the foundation of the workflow, such as establishing the principles, tools and methods we will use during the collaboration. We all agreed to use GitHub and related workflows such as issues, pull requests, and reviews to assure the quality of the work. We also very early agreed upon the programming language as well as expectations of the project, i.e. what we will try to achieve, a passing grade. 

Furthermore, communication was handled through discord, we mainly worked together in the same call so the workflow could easily be adapted. For example if someone needed help with the tools, or if someone found a bug, they could quickly share their screen to resolve any issues. The tools were also adapted towards our needs, since they were evolving with the project's progress. For instance, we switched from primarily using `make` to `cmake` in order to implement unit testing. This change was swift and caused little hassle.

The checkpoint we are currently on is creating a procedure to handle feedback on the team's way of working. This is a task we have not considered yet as a team, since we have mainly been focused on coding and finalizing the project. To overcome this obstacle we will try to create a blameless and transparent working culture. This will be fostered by having a small feedback discussion session at the beginning of each meeting (in the future). Hopefully this gives room for colleagues to voice their conscience in a respectful and mature environment.

To reach the next state “In-Place” we need to get more comfortable with the tools and practices to allow us to work more seamlessly. Pull-requests and merges should happen in the background so we don’t need to have long meetings in order to solve them. Referencing issues in commits, as well as creating issues, should also become a habit to everyone. We should not even need to actively think about it, just do it.

## TODO

### Compulsory

* [ ] good README with a statement of contributions
* [ ] functional program
* [x] unit tests, 2 per LIC
* [ ] collaboration i.e. commits
* [ ] workflow and its documentation

### Optional

* [ ] commits linked to issues
* [ ] "something remarkable"
