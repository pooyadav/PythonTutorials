# PythonTutorials

Setting up python3 virtual environment at MacOS

Requirements: 
python3 

```
$brew install python3

```
## Installation
```
$ pip3 install virtualenv
```

## Creating a named virtual environment
```
$ virtualenv -p python3 <virtual-environment-path>
```
## Activate the virtual environment before use

```
$ source <<virtual-environment-path>/bin/activate
```
## Deactivate the  virtual environment after use

```
$ deactivate
```
## Troubleshooting
### Installation
```
Could not install packages due to an EnvironmentError: [Errno 13] Permission denied: '/Library/Python/3.7'
Consider using the `--user` option or check the permissions.
```
#### Try this
```
$ pip3 install virtualenv --user
```







