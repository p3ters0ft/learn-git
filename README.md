# learn-git
This repo is used as an introductory to git commands, for a developer, open-source contributor, or even just to learn the basics

Usage
=====
To be able to learn git, you will have to fork this repository and make it your own.
You can [click here](https://github.com/theArtechnology/learn-git/fork) or press the fork button up there.

Once you've completed this step, you should see this URL below in your browser:
```text
https://github.com/YOUR USER NAME/learn-git/
```

<p align="center">
  <img src="https://mrwgifs.com/wp-content/uploads/2013/11/Gandalf-Is-Searching-For-Someone-To-Adventure-With-In-Lord-Of-The-Rings.gif" alt="Gandalf">
</p>

<p align="center">
  <i>you can begin this journey with this simple README.md.</i>
</p>


Tools
=====
### Prerequisites
- Git
- Terminal

If you are not sure if git is installed on your machine, follow the steps below according to your operating sytem type:

#### Windows
If you are using a Windows operating system,  [please follow this link](https://gitforwindows.org/).

#### macOS
If you are using an Apple operating system,  [please follow this link](https://gist.github.com/derhuerst/1b15ff4652a867391f03#file-mac-md).

#### Linux
If you are using Linux based operating system,  [please follow this link](https://git-scm.com/download/linux).

### Checking
 - For Windows, search `Git Bash` on your start menu, and open the terminal.
 - For MacOS/Linux, open your terminal
 
 - Type: `git --version` on your terminal, and it should output the version of your git command without errors.

Learning
========

##### Basics
* First of all, you will need to tell `git` that who you are, type those command below in your terminal, and replace `YOUR NAME HERE` and `YOUR EMAIL HERE`:
    ```bash
    git config --global user.name "YOUR NAME HERE"
    ```
    
    ```bash
    git config --global user.email "YOUR EMAIL HERE"
    ```
  * To check if `git` knows who you are, inspect with 
    ```bash
     git config --list
    ```
  * You should see your name and email.
 
* Your second step is to clone your *forked* (own) version of the repository (see [Usage](#usage)).
    ```bash
     git clone https://github.com/YOUR USER NAME HERE/learn-git.git
    ```
   * After the repository has been cloned:
   ```bash
    cd learn-git
   ```
##### Guidelines
* Open your favourite editor, and open the folder of this project.
* You will notice a file called [TEACHME.txt](TEACHME.txt), it contains a [pangram](https://en.wikipedia.org/wiki/Pangram).
* Your tasks is to manipulate the content of this text file to learn git.
> Important !!!
* We will use other *pangrams* found [here](https://pangrampangram.com/blogs/journal/best-pangrams-a-tool-for-every-graphic-designers).

### Learning git (part 1) - First commit
#### Tasks
- [x] Add a pangram to the [TEACHME.txt](TEACHME.txt) file.
- [x] Save the changes and push it online.

```bash
 git add TEACHME.txt
```
```bash
 git commit -m "Added a new pangram"
```

```bash
 git push origin master
```
Congratulation ! you've completed the first step ! :+1::tada:
> Additional notes: you can look use `git diff` command before doing git add to see what have changed.
 
Additional Notes
================
> TLDR; Git is a command. Github is a website. 

> The *git* and website *github* are not the same. The command *git* is used to do a versioning system so that you can keep records and tracks of the version of your project codes alongside people you are coding with. On the opposite side, github is a website used to *host* the project you are working on, and provide you a visual perspective of the management of your project.
