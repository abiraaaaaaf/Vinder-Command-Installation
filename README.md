# Vinder Command Installation
 
 
 ## Install Anaconda
 
 Step 1: Check if anaconda is installed already:
 
 ```
conda --version
```
If anaconda is installed, this command will print the conda version, so skip to Step2. Otherwise, do the following commands.

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

