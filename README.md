# Python Tutorials

Here I'm writing two ways to setup python working environment. 

## Standard Python Virtual environment
Setting up python3 virtual environment at MacOS

Requirements: 
python3 

```
$ brew install python3

```
### Installation
```
$ pip3 install virtualenv
```

### Creating a named virtual environment
```
$ virtualenv -p python3 <virtual-environment-path>
```
### Activate the virtual environment before use

```
$ source <<virtual-environment-path>/bin/activate
```
### Deactivate the  virtual environment after use

```
$ deactivate
```
### Troubleshooting
#### Installation
```
Could not install packages due to an EnvironmentError: [Errno 13] Permission denied: '/Library/Python/3.7'
Consider using the `--user` option or check the permissions.
```
##### Try this
```
$ pip3 install virtualenv --user
```

## Virtual environment using Conda

### Installation

Install anaconda from here: https://docs.anaconda.com/anaconda/install/mac-os/

### Create the environment

Here, we are creating an environment with python 3.7, replace it with your version.

```
$ conda create --name <my-environment-name>  python=3.7
```
### Activate the environment

```
$ conda activate <my-environment-name>
```

### Deactivate the environment

```
$ conda deactivate
```



