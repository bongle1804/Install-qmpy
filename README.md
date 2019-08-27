Install qmpy with python2.7 (Mac only):

- There are some required packages only supported by python2.7, then to install qmpy, prefer use python2.7
- We can using both pip and conda. However, using conda has some advantages.
Steps:
Step 1: Create an environment with name qmpy for qmpy:
  conda create -n qmpy python=2.7 

Step 2: activate this environment
  conda activate qmpy 
  
Step 3: install requirement packages, follows the guide in file setup.py in qmpy. In this step, to install each package, we need to search on https://anaconda.org/ to get appropriate syntax. For those package we can not install by conda, we can use pip instead.
https://github.com/wolverton-research-group/qmpy/blob/master/setup.py

Step 4: Using command line to run file setup.py in folder qmpy:
  python setup.py install
  
After that, We already installed qmpy.

Next task, we need add oqmd database on mysql (for who do the materials project).

Step 1: Download and install MySQL, remember name and password (for example: name:"name", pass: "pass")

Step 2: Setting MySQL:
  mysql -u root -p
  # After enter, you will required password: pass

(Continue)
