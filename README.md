# SIAM Workshop on Mathematical Modeling in C++

Welcome to the SIAM Workshop on Mathematical Modeling in C++.

This is a **non-credit workshop** structured similarly to a course. Over the span of **10 weeks**, we will work on **one large mathematical modeling project**, with each week introducing a short lesson in **C++ programming**, **scientific computing**, and/or the **mathematics behind the model**.

The goal of this workshop is to help students build skills in:

- C++ programming
- mathematical modeling
- scientific computing
- version control with Git and GitHub

By the end of the workshop, you will have contributed to a GitHub-based project that you can potentially build on and showcase when applying for **research positions, internships, labs, or graduate school**.

## Workshop Notes

- You do **not** need prior C++ experience.
- Prior programming experience may be helpful, but it is **not required**.
- Some ideas from **vector calculus**, **linear algebra**, and **probability** may appear, but these are **not prerequisites**.
- Any necessary mathematical background will be introduced during the workshop.
- Please bring a laptop if you would like to code along during the sessions.

## The Model We Will Study

In this workshop, we will build a simplified **Sub-Cellular Element (SCE) model**.

An SCE model represents a cell using discrete elements (nodes) that interact through mechanical forces.

In our simplified model:

- the **cell membrane** will be represented by **60 nodes** arranged in a circular structure
- the **cytoplasm** will be represented by **60 randomly distributed nodes** inside the membrane

By simulating interactions between these elements, we can model how cells move, deform, and interact with their environment.

## Before You Begin

You should already have the following:

- [Git](https://github.com/git-guides/install-git)
- [Visual Studio Code](https://code.visualstudio.com/)
- a [GitHub account](https://github.com/)

If you have **not** done that yet, please complete those steps first.

You will also need a **C++ compiler** and debugger in addition to VS Code.

### Windows setup

Use one of the following guides:

- [Configure VS Code for Microsoft C++](https://code.visualstudio.com/docs/cpp/config-msvc)
- [Using GCC with MinGW in VS Code](https://code.visualstudio.com/docs/cpp/config-mingw)

### macOS setup

Use one of the following guides:

- [Using Clang in Visual Studio Code](https://code.visualstudio.com/docs/cpp/config-clang-mac)
- [Using C++ on Linux in VS Code](https://code.visualstudio.com/docs/cpp/config-linux)

> Note: For most Mac users, the Clang setup is the standard choice.

## Quick Start

To get the workshop code onto your computer, open a terminal in VS Code or your system terminal and run:

```bash
git clone https://github.com/NguyenThoon/SIAM_Workshop_Cell_Motility.git
cd SIAM_Workshop_Cell_Motility
code .
```
Once the project is open in VS Code:

1. Open the appropriate .cpp file
2. Build and run the program using your configured C++ setup
3. Follow lesson-specific instructions in each lesson folder

