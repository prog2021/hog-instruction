## Hog Application

These instructions describe how to get started with the [Hog Project][hog]
of [Composing Programs][compose-progs].

### Download the Assignment

1. Go to this Assignment URL and accept the assignment:    
   <https://classroom.github.com/a/CHAQ2BIa>

   - Github will create a 'git' repository for you containing starter code.
   - You *may* need to refresh the screen to see your repository URL.

2. Open a Terminal or Command Line (cmd) window, and change to a directory
   on your computer where you store computer code (each project in a separate
   subdirectory of this directory).    
   For example, a directory named `projects` inside your home directory.
   ```
   # This is for MacOS, Git/Bash shell, or Linux
   cd projects

3. When you accepted the assignment On Github (Step 1), Github created an
   online repository for you and shows you the URL.  
   The URL is similar to: `https://github.com/prog2021/hog-yourgithubid`    
   with your actual Github login instead of `yourgithubid`.    
   There is a button on Github to copy this URL to your clipboard.
   In the Terminal/command line, enter the following command (as shown on Github):    
   ```
   git clone https://github.com/prog2021/hog-yourgithubid hog
   ```
   this will copy the Github code into a **new** subdirectory named `hog`.    
   Note: If you don't enter the last parameter (`hog`) then your local directory will by named `hog-yourgithubid` (same as the location on Github). This is OK, but kind of long.

4. In your local `hog` directory (or `hog-yourgithubid`), complete the assignment, one part at a time.

### What to Do

1. Complete the code for [The Game of Hog][hog] as described at the link.

2. Test your code frequently.

3. Save and submit your work regularly using Git -- do this everytime you work on something, not just when you finish the assignment.

### Test Your Code

`hog.py` contains doctests in comments that you can run using:
```
python3 -m doctest hog.py
```
Only doctests that fail are printed on the console.

The `test` directory contains test code using the Python unittest package.
Run all the tests using:
```
python3 -m unittest 
```
If you want to test only the code for one Phase, run:
```
# Tests of Phase 1 problems
python3 -m unittest test/test_phase1.py
# Tests of Phase 2 problems
python3 -m unittest test/test_phase2.py
```

While you are working on the assignment, it is normal for some tests to fail.
When you finish, all tests should pass.

The unit tests don't test *everything*!    
You should thoroughly test and review your own code.


### Save Your Work Using Git and Submit to Github

Use Git to regularly add your work to your local repository and send it to Github.  This is a good software development practice.

The commands are:

1. Check what files you have changed:
   ```
   git status

   Modified files:
      hog.py
   ```
2. Tell git you want to save the modified files (hog.py) or add a new file (doesn't apply here):
   ```
   git add hog.py
   ```
3. Commit to the repository:
   ```
   git commit -m "write a message describing what work you did"
   ```
   Or, combine step 2 and step 3 into one command:
   ```
   git commit -am "write a message describing what work you did"
   ```
4. Copy your local repository to Github:
   ```
   git push
   ```

### What to Submit

You should "push" (upload) your code (`hog.py`) to Github.
You can do this many times up until the project deadline.

### Git

You need the "git" client program on your computer
and added to your environment's PATH.

Get Git from <https://git-scm.com/downloads>.


[hog]: https://inst.eecs.berkeley.edu//~cs61a/fa13/proj/hog/hog.html
[compose-progs]: http://composingprograms.com/
