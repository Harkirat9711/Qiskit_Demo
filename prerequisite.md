##Steps for Access and System Configuration for QISKit in IBM Q Account.

*Sign up 
  https://quantumexperience.ng.bluemix.net/qx/community

*Go to My account and copy API token.

*At least Python 3.5 or later is needed for using QISKit.

* PIP Installation (a python package manager):
```
  pip3 install qiskit
```
* Git Download the Software Development Kit
```
   git clone https://github.com/QISKit/qiskit-sdk-py
   cd qiskit-sdk-py
```
*Configure your API token and QE credentials
```
    Find Qconfig.py.defaut file and run command below
    cp Qconfig.py.default Qconfig.py
```
*	Open your Qconfig.py, remove the # from the beginning of the API token line, 
  and copy/paste your API token into the space between the quotation marks on that line. 
  Save and close the file.
  
* create conda environment for QISKit:
  ```
    conda create -y -n QISKitenv python=3 pip3 scipy
  ```	
*Activate the environment
 ``` 
    MacOS, Linux: source activate QISKitenv
    pip install -r requirements.txt
```
