# python notes

**1) Installing Python**: Go to https://www.python.org/downloads/macos/ and download the latest python build for your OS. Then install using the downloaded installer on your machine.

**2) Open latest version of Python:** Open Terminal --> type `python3` to open the latest python version on terminal.

**3) Check python version:** Type `python3 -V`

**4) What is pip?:** pip is a package management system available for python. Any package available for python can be installed using pip.

**5) Installing pip on your machine:** pip comes pre-installed on macbook, with python versions 3. To check if pip is installed, type `pip3 --version`

**6) Installing packages using pip:** So first we need to understand that python and pip are separate things. In order to start python, you type `python3` on the terminal and then you run programs. To install packages using pip, you should not be in pip. First, `exit()` from python3, then install the packages using pip. The code would be as follows.

```
exit()
pip3 install jupyterlab --upgrade pip
```

**7) Understanding the directory where python is installed:** to get the current working directory, type the following.
```
python3
import os
os.getcwd()
print(os.getcwd())
```
This returns the current directory. In my case, it is `/Users/sunnyroykolla`

To change the working directory, type `os.chdir('/Users/sunnyroykolla/Python')`

You can create as many folders as necessary and run python programs accordingly. Everytime a new program saved in another folder has to be run, the current working directory has to be changed as above.  
Information related to directories is available at https://www.programiz.com/python-programming/directory. 

**8) IDE for Python:** Many IDEs exist for python. For example, Jupyter, Anaconda etc. It is analogous to RStudio for R. R comes with a basic installer, but RStudio is an IDE that makes working on R easy.

**9) Install JupyterLab using commandline:** 
```pip3 install jupyterlab --upgrade pip
   jupyter notebook
```
The second command opens Jupyter notebook on Chrome/other browser.

**10) Installing datascience libraries**
> Top Data science libraries: https://towardsdatascience.com/top-10-python-libraries-for-data-science-cd82294ec266
>> Pandas. 
>>
>> NumPy. 
>> 
>> SciPy 
>> 
>> MatplotLib. 
>> 
>> Seaborn. 
>> 
>> SciKit Learn 
>> 
>> Tensorflow. 
>> 
>> Keras. 
>> 
>> Statsmodels 
>> 
>> PLotly 

**11) Running first python program using Jupyter notebook**



