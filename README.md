# Git Basics Commands for Beginners

This repo will contain all basics git commands and theirs uses.

### Step 01

### Installing Git on your PC

To download Git:

- [x] Go to https://git-scm.com/downloads download the software for Windows.
- [x] Install Git choosing all of the default options.
- [x] Once everything is installed, you should be able to run following command on the CMD. If it displays the usage information, then Git is installed on your PC.
<pre><code>git</code></pre>

### Step 02

### Git Configuration

Before you can start using Git, you need to configure it. Run each of the following lines on the command line to make sure everything is set up.  
Sets up Git with Your Name

<pre><code>git config --global user.name "Your-Full-Name"</code></pre>

Sets up Git with Your Email

<pre><code>git config --global user.email "Email Address"
</code></pre>

Makes sure that Git output is colored.

<pre><code>git config --global color.ui auto
</code></pre>

Displays the original state in a conflict.

<pre><code>git config --global merge.conflictstyle diff3
git config --list
</code></pre>

### Step 03

### Git & Code Editor

The last step of configuration is to get Git working with your code editor. Below are three of the most popular code editors.
VS Code Setup

<pre><code>git config --global core.editor "code --wait"</code></pre>

Sublime Text Setup

<pre><code>git config --global core.editor "'Your Sublime Exe Path' -n -w"</code></pre>

Atom Editor Setup

<pre><code>git config --global core.editor "atom --wait"</code></pre>

### Initializing Git Repo and Connecting remote Repo.

Use the git following command to create a new, empty repository in the current directory.

<pre><code>git init</code></pre>

> 'init' is short form of 'initialize'

Add readme file

<pre><code>git add README.md</code></pre>

Following command will create a commit to your local repo

<pre><code>git commit -m "Your Commit Message"</code></pre>

<pre><code>git branch -M main</code></pre>

<pre><code>git commit -m "Your Commit Message"</code></pre>

<pre><code>git remote add origin [Your GitHub Link]</code></pre>

<pre><code>git push -u origin main</code></pre>

### Reference

Udacity Free Course  
[Version Control with Git](https://www.udacity.com/course/version-control-with-git--ud123 "Version Control with Git")
