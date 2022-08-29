# Getting Familiar with the Terminal

In this activity, you'll get more practice with terminal commands.

## Instructions

1. Open the terminal in this folder.

2. Use the `ls` command to see the contents of this folder.

3. Use the `pwd` command to find the current path you're in.

4. Create a new directory named `Activity-1`. Then list the contents of the current directory again, to make sure it worked.

5. Navigate into the directory you just created.

6. Create a new file named `hello.md`. List the contents of the current directory again.

7. Copy the file you just made to a file named `world.md`.

8. Rename the `hello.md` file to `coding.md`.

9. Create a new directory named `terminal`.

10. Move the `world.md` file into the `terminal` folder you just made.

11. Delete the `terminal` folder.

## Hint

Use the Terminal Cheatsheet if you need guidance on which terminal commands should be used for each step.

---

© 2020 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.

(base)
jersk@MSI MINGW64 ~
$ cd 003_FinTech/
(base)
jersk@MSI MINGW64 ~/003_FinTech
$ cd git/
(base)
jersk@MSI MINGW64 ~/003_FinTech/git
$ ls
02.2_Python/           ftb02_Python_Intro/  python-homework/  Untitled1.ipynb
ftb01_IntroToFinTech/  ftb03_PythonPandas/  Untitled.ipynb
(base)
jersk@MSI MINGW64 ~/003_FinTech/git
$ pwd
/c/Users/jersk/003_FinTech/git
(base)
jersk@MSI MINGW64 ~/003_FinTech/git
$ cd ftb03_PythonPandas/
(base)
jersk@MSI MINGW64 ~/003_FinTech/git/ftb03_PythonPandas (main)
$ ls
Activities/  Challenge_03/  code/  data/  images/  README.md  references/
(base)
jersk@MSI MINGW64 ~/003_FinTech/git/ftb03_PythonPandas (main)
$ mkdir Activity-1
(base)
jersk@MSI MINGW64 ~/003_FinTech/git/ftb03_PythonPandas (main)
$ cd Activity-1/
(base)
jersk@MSI MINGW64 ~/003_FinTech/git/ftb03_PythonPandas/Activity-1 (main)
$ touch hello.md
(base)
jersk@MSI MINGW64 ~/003_FinTech/git/ftb03_PythonPandas/Activity-1 (main)
$ cp hello.md world.md
(base)
jersk@MSI MINGW64 ~/003_FinTech/git/ftb03_PythonPandas/Activity-1 (main)
$ ls
hello.md  world.md
(base)
jersk@MSI MINGW64 ~/003_FinTech/git/ftb03_PythonPandas/Activity-1 (main)
$ mkdir terminal
(base)
jersk@MSI MINGW64 ~/003_FinTech/git/ftb03_PythonPandas/Activity-1 (main)
$ mv world.md terminal/
(base)
jersk@MSI MINGW64 ~/003_FinTech/git/ftb03_PythonPandas/Activity-1 (main)
$ ls
hello.md  terminal/
(base)
jersk@MSI MINGW64 ~/003_FinTech/git/ftb03_PythonPandas/Activity-1 (main)
$ cd terminal/
(base)
jersk@MSI MINGW64 ~/003_FinTech/git/ftb03_PythonPandas/Activity-1/terminal (main)
$ ls
world.md
(base)
jersk@MSI MINGW64 ~/003_FinTech/git/ftb03_PythonPandas/Activity-1/terminal (main)
$ cd ..
(base)
jersk@MSI MINGW64 ~/003_FinTech/git/ftb03_PythonPandas/Activity-1 (main)
$ rm -r terminal/
(base)
jersk@MSI MINGW64 ~/003_FinTech/git/ftb03_PythonPandas/Activity-1 (main)
$ ls
hello.md
(base)
jersk@MSI MINGW64 ~/003_FinTech/git/ftb03_PythonPandas/Activity-1 (main)
$