# Vinder Command Installation
 
 ## Linux
 ------
 ## Install Anaconda 
 
 Check if anaconda is installed already:
 
 ```
$ conda --version
```
If anaconda is installed, this command will print the conda version, so skip to installing python. Otherwise, do the following commands.

 ```
 sudo apt-get update
 sudo apt-get install curl
 curl –O https://repo.anaconda.com/archive/Anaconda3-2020.02-Linux-x86_64.sh
 bash Anaconda3-2020.02-Linux-x86_64.sh
```
Then, activate and test the installation:

 ```
source ~/.bashrc
conda info
 ```

 ## Install Python
 
 To see version of Python, open a command prompt and run:
 
```
python --version
```
You can easily install Python 3.7 with the following commands:
```
sudo apt-get update
sudo apt-get install python3.7
```
To see if pip is installed, open a command prompt and run:
```
command -v pip
```
If pip is not installed, download the script from https://bootstrap.pypa.io/get-pip.py:
```
python get-pip.py
```
Now you can easily install the following libraries using pip:
```
pip install PyQt5
pip install python-csv
pip install numpy
pip install opencv-python
```
Finally, just run the following command:
```
python interface.py
```

## MacOS
------

 ## Install Anaconda 
 
 Check if anaconda is installed already:
 
 ```
$ conda --version
```
If anaconda is installed, this command will print the conda version, so skip to installing python. Otherwise, go to https://www.anaconda.com/downloads to download Anaconda. Go to the Anaconda Website and choose a Python 3.x graphical installer. You can scroll down a little to the latest version for MacOS. 

 ## Install Python

Then, go to your terminal and type the following command to see if python is installed and see its version:
```
python --version
```
If you have Python 3.7, you’ll run the following (you can change the name of the file based on your bash anaconda file):
```
bash ~/Downloads/Anaconda3-2019.03-MacOSX-x86_64.sh
```
If you don't have python, download the latest installer package from the Python website here: https://www.python.org/downloads/

Once the download is complete, double-click the package to start installing Python. If you’re using Apple M1 Mac, you need to install Rosetta. Rosetta enables Intel-based features to run on Apple silicon Macs. When the installation completes, it will open up the Python folder.

Installing Rosetta: 

If you have a Mac with Apple silicon, you are asked to install Rosetta the first time you open an app built for an Intel-based Mac. Click Install, then enter your user name and password to allow installation to proceed. 

Another option to install Rosetta is by copying and pasting the following command into the command line: 

```
/usr/sbin/softwareupdate –install-rosetta –agree-to-license
```

For installing pip, run the following command:
```
curl https://bootstrap.pypa.io/get-pip.py | python
```
Then, just simply enter the following commands in the terminal:
```
pip install PyQt5
pip install python-csv
pip install numpy
pip install opencv-python
```
Finally, just run the following command:
```
python interface.py
```







