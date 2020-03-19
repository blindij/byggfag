INSTALLING PYTHON ON YOUR COMPUTER

The first thing we recommend you to do, is to install Python using the Anaconda distribution,
because (almost) every single module that you choose to import will be 
pre-installed / installed on-the-fly, instead of you having to manually add them each time.

Link below to the Anaconda distribution:
    https://www.anaconda.com/distribution/

Choose which OS (Windows, Mac, Linux), choose Python 3.7 (not 2.7), and 
follow the installation instructions.

When Anaconda ask you if you want to include Python in your PATH variables, select YES. 
This will let you write 'python' as a command in a terminal/command window. 
This is the primary source of error when installing Python.

When the installation is complete, try typing 'python' in the cmd/terminal. 
If it launches a Python interpreter ('>>>' is shown), you are good to go!
If 'python' isn't recognized, uninstall Anaconda and install it anew, and remember to 
    select YES to the question about including Python in your PATH variables.
    OR, add the 'python.exe' to your PATH. If you don't know what this means, it 
    is easier to re-install Anaconda...
    
    
    

RUNNING PYTHON SCRIPTS 
With the Anaconda distribution of Python installed, you will have the option to run Python 
scripts from the command line (The "cmd" / PowerShell on Windows), or using the 
IDE "Spyder". In Spyder, you have an "Editor" where you write your entire script, 
and an "IPython Console" where your code executes when pressing the button "Enter". 
You can also mark code in your editor, and press "Shift + Enter" to execute only this code, 
which is a very handy shortcut. We recommend using Spyder, for both beginner's and pro's.

If you have a Python installation, but not the Anaconda distribution, you must install all packages 
manually. To run the script herein, you will need to install numpy, matplotlib and jupyter.
Open a cmd/terminal (as Administrator), and type:
    pip3 install numpy
    pip3 install matplotlib 
    pip3 install jupyter




JUPYTER NOTEBOOK:
If you want an introduction to how to plot data and write/read files in Python, it is recommended 
to take a look at the 'Python_Intro.ipynb' notebook.
To open a Jupyter Notebook, open a terminal/command window. This is e.g done by navigating to the 
correct folder where you have the .ipynb (jupyter notebook) file. Instead of opening the folder, 
press "Shift + Right Mouseclick", and choose "Open a PowerShell window here", or "Open a command window here"
or "Open a terminal here", depending on your OS (Windows/Mac/Linux). 

On Windows, you can choose to open either a PowerShell or a Command Window, as both are terminals
(they let you give commands to the computer). If your are on Mac/Linux, open the Command Line. 
Then type in and press Enter afterwards:
    jupyter notebook
The folder will now open in your web browser, and you can simply click 
on 'Python_Intro.ipynb' to open it.





SOLUTION PROPOSAL
A solution proposal that solves the programming part of the Lab exercise is included.
You are all recommended to try to understand what happens in the script, 
instead of only using the results. 

The script saves all generated plots in the same directory as your data files, as .png images.

In order to run the solution proposal script, open a terminal / PowerShell / cmd, and type in:
    python Solution_Proposal.py

    

Good luck with the lab report!
  
 