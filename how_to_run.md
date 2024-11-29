# How to run the code in a virtual environment
### Description

This file is intended to explain how to create a virtual environment and how to install the packages needed to run the code included in the "Q01.py" file. The packages needed to run the code are listed in the "requirements.txt" file.


### How to create a virtual environment and install the packages

#### Create virtual environment

First, we need to create a virtual environment. This is achieved by opening a terminal (in the venv-viclope587 repository) and using the following command :
```
python -m venv my_env
```
This command will create a virtual environment called "my_env".


#### Activate virtual environment

Now that we have created a virtual environment, we need to activate the virtual environment. This step can be achieved by using the following command :
```
source my_env/bin/activate  # Mac/Linux
my_env\Scripts\activate     # Windows
```


#### Install packages in the virtual environment

Having activated the virtual environment, we can now install the required packages to run the code. In order to install said packages in the virtual environment, we need to use the following command :
```
pip install -r requirements.txt
```


#### Run the code

Finally, we can now run the code. Use this command to run the code :
```
python Q01.py
```