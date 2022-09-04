# Virtual-Environment-Python
Commands to Run Python's VirtualEnvironment on Windows System
### 1. Install virtual environment :
```terminal
pip install virtualenv
```

### 2. Setup virtual environment :
```terminal
virtualenv ENVIROMENT-NAME
```

### 3. Activating a virtual environment after it has been setup : 
```terminal
ENVIROMENT-NAME\Scripts\activate
```

### 4. Deactivate a virtual environment : 
```terminal
deactivate
```

### 5. Commands to view the Python packages that are installed on your system : 
```terminal
pip freeze > requirment.txt
```

### 6. The command to install all the Python packages in the requirement.txt file is : 
```terminal
pip install -r requirment.txt
```

### 7. This is a command to bring together the virtual environment of all the Python packages your system has : 
```terminal
virtualenv --system-site-packages ENVIROMENT-NAME
```