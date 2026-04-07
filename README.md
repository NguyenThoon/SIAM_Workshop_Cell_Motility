# SIAM Workshop on Mathematical Modeling in C++

Welcome to the SIAM Workshop on Mathematical Modeling in C++.

This is a **non-credit workshop** structured similarly to a course. Over the span of **10 weeks**, we will work on **one large mathematical modeling project**, with each week introducing a short lesson in **C++ programming**, **scientific computing**, and/or the **mathematics behind the model**.

The goal of this workshop is to help students build skills in:

- C++ programming
- mathematical modeling
- scientific computing
- version control with Git and GitHub

By the end of the workshop, you will have worked with a GitHub-based coding project that you can potentially build on and showcase when applying for **research positions, internships, labs, or graduate school**.

## Workshop Notes

- You do **not** need prior C++ experience.
- Prior programming experience may be helpful, but it is **not required**.
- Some ideas from **vector calculus, linear algebra, and probability** may appear, but these are **not prerequisites**.
- Any necessary mathematical background will be introduced during the workshop.
- Please bring a laptop if you want to code along during the sessions.

## The Model We Will Study

In this workshop, we will build a simplified **Sub-Cellular Element (SCE) model**.

An SCE model represents a cell using discrete elements (nodes) that interact through mechanical forces.

In our simplified model:

- the **cell membrane** will be represented by **60 nodes** arranged in a circular structure
- the **cytoplasm** will be represented by **60 randomly distributed nodes** inside the membrane

By simulating interactions between these elements, we can model how cells move, deform, and interact with their environment.

## Before You Begin

You should already have the following installed or created:

- [Git](https://github.com/git-guides/install-git)
- [Visual Studio Code](https://code.visualstudio.com/)
- a GitHub account at [GitHub](https://github.com/)

If you have **not** done that yet, please complete those steps first.

## C++ Setup for VS Code

You will need a **C++ compiler** and debugger in addition to VS Code.

### Windows
Use one of the following setups:

- [Configure VS Code for Microsoft C++](https://code.visualstudio.com/docs/cpp/config-msvc)
- [Using GCC with MinGW in VS Code](https://code.visualstudio.com/docs/cpp/config-mingw)

### macOS
Use one of the following guides:

- [Using C++ on Linux in VS Code](https://code.visualstudio.com/docs/cpp/config-linux)  
- [Using Clang in Visual Studio Code](https://code.visualstudio.com/docs/cpp/config-clang-mac)

> Note: On macOS, the most common setup is Clang through Apple's developer tools.

## What You Will Do

There are two GitHub-related tasks in this workshop:

1. **Download this workshop repository to your computer**
2. **Optionally create your own GitHub repository and push your copy there**

The first step is required if you want to run the code locally.  
The second step is useful if you want your own backup copy or want to showcase your work on your own GitHub profile.

---

# Part 1: Download the Workshop Code to Your Computer

This process is called **cloning** a repository.

## Step 1: Copy the repository URL

On the main page of this GitHub repository:

1. Click the green **Code** button
2. Make sure **HTTPS** is selected
3. Copy the repository URL

It will look something like this:

```bash
[https://github.com/your-workshop-name/siam-workshop.git](https://github.com/NguyenThoon/SIAM_Workshop_Cell_Motility.git)
