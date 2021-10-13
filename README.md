# python notes

**1) Installing Python**: Go to https://www.python.org/downloads/macos/ and download the latest python build for your OS. Then install using the downloaded installer on your machine.

**2) Open latest version of Python:** Open Terminal --> type `python3` to open the latest python version on terminal.

**3) Check python version:** Type `python3 -V`

**4) What is pip?:** pip is a package management system available for python. Any package available for python can be installed using pip.

**5) Installing pip on your machine:** pip comes pre-installed on macbook, with python versions 3. To check if pip is installed, type `pip3 --version`

**6) Understanding the directory where python is installed:** to get the current working directory, type the following.
```
python3
import os
os.getcwd()
print(os.getcwd())
```
This returns the current directory. In my case, it is `/Users/sunnyroykolla`

To change the working directory, type `os.chdir('/Users/sunnyroykolla/Python')`

You can create as many folders as necessary and run python programs accordingly. Everytime a new program saved in another folder has to be run, the current working directory has to be changed as above.

**IDE for Python:** Many IDEs exist for python. For example, Jupyter, Anaconda etc. It is analogous to RStudio for R. R comes with a basic installer, but RStudio is an IDE that makes working on R easy.
**Install JupyterLab using commandline:** 
