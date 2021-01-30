## Hog Assignment Getting Started - How to Download the Assignment

These instructions describe how to get started with the [Hog Project][hog]
from [CS61A][cs61a].

After you perform these instructions you will have a Git repository
containing all the starter code for the Hog Project.    
You **do not** need to download a ZIP file from the cs61a web site;
your Git repo already contains that code.


1. Go to this Assignment URL and accept the assignment: 
   <https://classroom.github.com/a/CHAQ2BIa>

   - Github will create a 'git' repository for you containing starter code
   - Github will show the URL for your Github repo. See below for how to clone this.
   - You *may* need to refresh the screen to see your repository URL.

2. Open a Terminal or Command Line (cmd) window on your computer, and change to a directory
   where you will store computer code (each assignment should be a separate
   subdirectory of this directory).    
   For example, if you use a directory named `projects` inside your home directory.
   ```
   # This is for MacOS, Git/Bash shell, or Linux
   cd projects
   ```

3. In Step 1 (accept the assignment on Github), Github created an
   online repository for you and showed you the URL.  
   The URL is similar to: `https://github.com/prog2021/hog-yourgithubid`    
   with your actual Github login instead of `yourgithubid`.    
   (There is a button on Github to copy this URL to your clipboard.)    
   In the Terminal/Command window, enter the following command, as shown on Github:    
   ```
   git clone https://github.com/prog2021/hog-yourgithubid hog
   ```
   this will copy the Github code into a **new** subdirectory named `hog`.    
   Note: If you don't enter the last parameter (`hog`) then your local directory will by named `hog-yourgithubid` (same as the location on Github). This is OK, but kind of long.

4. In your local `hog` directory (or `hog-yourgithubid`), complete the assignment, one part at a time.

### What to Do

Complete the code for [The Game of Hog][hog] as described at the link.

Instructions for how to "push" your work to Github are described
in your repository README file.

[hog]: https://cs61a.org/proj/hog/
[cs61a]: https://cs61a.org/
