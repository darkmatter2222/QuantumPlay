A qiskit starter pack for newbies. 
![](https://imgur.com/0y3rWip.png)

# Prereqs
1. Python 3.6.6 (64bit) installed (https://www.python.org/downloads/release/python-366/)
2. virtualenv already installed  
  "pip install virtualenv"
3. IBM Quantum Experiance account (Free) (https://quantum-computing.ibm.com/)
4. Qiskit token, can be found under your IBM Quantum Experiance account
5. Qiskit token stored in a text document at:  
  '''C:\Tokens\Qiskit\IBMQ.txt'''
6. According to https://qiskit.org/documentation/install.html, you may need VS 2015 and 2017 C++ redistributables 

# Getting Started (Using Jupyter)
1. Clone  
2. Navigate to root of repo
3. install virtualenv (base python 3.6.6)  
  ```virtualenv --python="C:\Users\<User>\AppData\Local\Programs\Python\Python36\python.exe" .venv```  
4. Activate virtualenv  
  ```.venv\Scripts\activate```
5. Install all dependiencies  
  ```pip install -r requirements.txt```  
6. Install kernal  
  ```ipython kernel install --user --name=.venv```
7. Start Jupyter Lab  
  ```Jupyter lab```

# Have All the Above Finished? Now go here...  
Check this out first: Notebooks\FirstQuantumCircuit.ipynb  
There after, check out: Notebooks\ExploringGates.ipynb (WIP)

# Need help?
Great resource here: https://quantum-computing.ibm.com/jupyter/tutorial/1_start_here.ipynb

