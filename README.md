# Welcome Trainers, beware of any C# code :angel:

We will use this repository during class to collaborate on our class project.

### Class Manual

[GitHub for Developers Student Manual](github-for-developers-student-manual.pdf)

### Additional Resources

Here are a few of our favorite resources you may want to check out: [Extended Resources](https://services.github.com/classnotes/)

### Adding files to practice repo

#### Bash

`for d in {1..6}; do touch file$d.md; git add file$d.md; git commit -m "adding file $d"; done`

#### Powershell

`for ($d=1; $d -le 6;$d++) { touch file$d.md; git add file$d.md; git commit -m "adding file$d.md";}`
