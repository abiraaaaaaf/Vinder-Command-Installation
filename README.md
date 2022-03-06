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
 
 To see version of Python3, open a command prompt and run:
 
```
python3 --version
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
 
## MacOS
------

You can go to https://www.anaconda.com/downloads to download Anaconda. Then scroll down a little to the latest version for MacOS.
Then, go to your terminal and type the following command to see if python is installed and see its version:
```
python
```
If you have Python 3.7, you’ll run:
```
bash ~/Downloads/Anaconda3-2019.03-MacOSX-x86_64.sh
```








