# Installation Instructions

We will be installing the following software:

**All Users**
- Python3.7
- Nodejs
- Git
- Visual Studio Code
- Visual Studio Code plugins
- Docker
- Postman

**Mac Users**
- Homebrew

**Windows Users**
- Windows Sub System for Linux

We are all installing everything required for both teams so that it's easy for anyone to switch between teams or work in both teams.

There are some things missing, such as some Python and Nodejs/JavaScript modules we need to install, but we'll install them as we go along.

## Instructions

### Mac

1. Open the "Terminal" Application on your Mac. A black window should appear with the ability to start typing. To learn how to use the terminal, here is a guide: [https://www.pcsteps.com/5010-basic-linux-commands-terminal/](https://www.pcsteps.com/5010-basic-linux-commands-terminal/)

**NOTE:** The Mac Terminal is mostly similar to the Linux terminal, so you can use almost all the same commands. The one command which will be different is when you see in a guide "apt-get" is used. In Mac, we use "brew" (which is an application we will install next).

2. Run the following command to install Homebrew (paste into your Mac Terminal and press enter):

`/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"` - [Homebrew Website](https://brew.sh/) - [What is a package manager?](https://blog.idrsolutions.com/2018/07/what-is-a-package-manager-and-why-should-you-use-one/)

Verify by running `brew -v` and this should give the version of Homebrew printed on your Terminal

3. Run the following command to install Python3.7 (paste into your Mac Terminal and press enter):

`brew install python3.7`

Verify by running `python3.7 --version` and `pip3.7 --version`. Both commands should not crash and should not print "Not found" on the terminal screen.

4. Run the following command to install Nodejs and Npm (paste into your Mac Terminal and press enter):

`brew install node`

Verity by running `node -v` and `npm -v`. Both should print out their respective version numbers.

Now you can run all the above commands from any directory inside your terminal

5. Install Docker by going to this link here: [https://docs.docker.com/docker-for-mac/install/](https://docs.docker.com/docker-for-mac/install/)

6. Install Visual Studio code by going to this link here: [https://code.visualstudio.com/download](https://code.visualstudio.com/download) and select the right version for Mac.

Now you should be able to navigate to a folder in your Terminal and type `code .` and it will open Visual Studio Code in that folder.

7. Run the following command to install pylint (paste into your Mac Terminal and press enter):

`pip3.7 install pylint`

8. Install Git using the instructions on this link: [https://git-scm.com/book/en/v2/Getting-Started-Installing-Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

9. Visual Studio Code Plugins + Extras

Add the following plugins and extras via the plugins window in vscode:

- Python Languate extension by Microsoft
- Docker Syntax Highlighting
- Python docstring
- Trailing spaces
- Gitlens
- Markdown all in one
- Auto rename tag
- ESLint
- Jest snippets
- NPM Intellisense
- Prettier
- React Snippets

Formating code on save can be done via vscode settings. You can find this by searching Google.

10. Install Postman: [https://www.getpostman.com/downloads/](https://www.getpostman.com/downloads/)
