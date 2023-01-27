# Karinna Monzon Lab Report 1

Karinna Monzon
A17368401

This lab report will go over the processes installing VScode, processes for remotely connecting, and trying commands on the terminal connected to the remote computer.

## **Setting up your CSE15L Account**

1. First set up your CSE15L account at this link: [Link](https://sdacs.ucsd.edu/~icc/index.php)

This should lead you to a site that looks like this:

![Image](https://github.com/karinnamonzon/cse-15l-lab-report/blob/main/Account%20Lookup%20-%20sdacs.ucsd.edu.png?raw=true)

2. Put in your UCSD username (what comes before @ucsd.edu in your email) and student PID in the account lookup fields. Which will lead you to a page that looks like this:

![Image](https://github.com/karinnamonzon/cse-15l-lab-report/blob/main/Login.png?raw=true)

3. Press the button that is circled. And this will lead you to a page with a link **change your password** that will allow you to input your current password and replace it with a new password. 

![Image](https://github.com/karinnamonzon/cse-15l-lab-report/blob/main/ChangepassLink.png?raw=true)

4. Make sure to select "No" for the option to change your TritonLink password. Leave your mouse cursor in the Confirm Password section and press Enter on your keyboard to make the password change.

![Image](https://github.com/karinnamonzon/cse-15l-lab-report/blob/main/ChangingPassPage.png?raw=true)

**This should lead you to a page that confirms your password change. Please wait approximately 15 minutes for this change to be made.**

---

## **Setting up remote Visual Studio Code**

1. The [Visual Studio Code website](https://code.visualstudio.com/) will allow you to download VS Code onto your computer. If you have a Windows system then clock the circled button labelled "DownLoad for Windows." If you do not have a Windows system click the button with an arrow to open a drop-down meny that will link you to other downloads for macOS and Linux.

![Image](https://github.com/karinnamonzon/cse-15l-lab-report/blob/main/VSCode%20website.png?raw=true)

2. After opening the download file, it will lead you a window that will ask you accept an  agreement. Accept it and press Next.
3. It will then allow you to set where Visual Studio Code will be saved. You can change this to your own path or keep it in a default location.. Press Next after you have decided.
4. The next windows it will show you are about your preferences in for the download. Read through these and press Next after you have selected your preferences.

This should eventually download Visual Studio Code which should like this:
![Image](https://github.com/karinnamonzon/cse-15l-lab-report/blob/main/VSCodeOpen.png?raw=true)

---
## **Remote Connecting using your log in credentials and VScode**
1. Open VSCode and open a new terminal by going to terminal at the top and selecting New Terminal or using the shortcut Ctrl+Shift+` and this should show the terminal appear on your screen.
2. With the terminal open type `ssh cs15lwi23zz@ieng6.ucsd.edu` (replace zz with the letters corresponding to youto own account) and press Enter on your keyboard.
3. You will be prompted if you want to continue connecting as shown below. Type yes and press Enter. After, you'll be prompted to type your new password that you reset in earlier steps. Nothing will show up as your type it so make sure you type it correctly then press Enter.

![Image](https://github.com/karinnamonzon/cse-15l-lab-report/blob/main/promptYes.PNG?raw=true)

Afterwards your client should connect to the remote server and look like this:

![Image](https://github.com/karinnamonzon/cse-15l-lab-report/blob/main/remoteConnectedTerminal.png?raw=true)

**Note:**
*This tutorial may not work perfectly the first time*

---
## **Running commands on the remote computer with terminal in VScode**

The remote computer can be accessed from the terminal on your own personal device so that you can continue working away from the lab.
Within the terminal you can run commadns such as:
- `cd ~`
- `cs`
- `ls -lat`
- `ls -a`
- `mkdir`
- `cp /home/linux/ieng6/cs15lwi23/public/hello.txt ~/`
- `cat /home/linux/ieng/cse15lwi23/public/hello.txt`
- `exit or Ctrl-D`

**Examples**

Here is an example of using `ls` and `mkDir`:

![Image](https://github.com/karinnamonzon/cse-15l-lab-report/blob/main/lsAndmkDir.png?raw=true)

In the terminal typing ls lsits the existing files in the home directory which are hello.txt and perl5. After using `mkdir newFile` it creates a new directory for newFile. After `ls` is ran again, the files from before have the addition of newFile.

Here is an example of using `ls`, `cat`, and `cd`:

![Image](https://github.com/karinnamonzon/cse-15l-lab-report/blob/main/terminaltest.png?raw=true)

Typing `ls` in the terminal from the home directory lists 3 files. Using the cat command witht the path to hello.txt print `Hello! Welcome to CSE 15L` on the next line. With the `cd perl5` command it opens the perl5 file. The `ls` command does not produce anything on the next line because the perl5 file is empty. The `cd ~` command returns the path to the home directory.

You can exit the remote computer by typing exit into the terminal or using the Ctrl-D shortcut on you keyboard. This is what exiting the remote computer with exit looks like:

![Image](https://github.com/karinnamonzon/cse-15l-lab-report/blob/main/exitRemote.png?raw=true)


