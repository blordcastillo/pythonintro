# Installation
## MacOS  
Don't use the system python!  
  
1. Install homebrew
2. Install Python (2 and/or 3)
3. Upgrade setuptools and pip
4. pip install virtualenv  


PyEnv  
  
1. Install homebrew
2. Install PyEnv
3. Add new versions 
4. pyenv global
5. pyenv local


More steps  
For your .bashrc  
`export PIP_REQUIRE_VIRTUALENV=true`  
`gpip(){
   PIP_REQUIRE_VIRTUALENV="" pip "$@"
}`
  
  
## Windows  
  
Never use the default arcpy python (unless you have to)  
  
1. Install the msi from https://www.python.org/downloads/windows/  
2. Modify your path in powershell: `[Environment]::SetEnvironmentVariable("Path", "$env:Path;C:\Python27\;C:\Python27\Scripts\", "User")`  
3. Install pip (if needed): https://pip.pypa.io/en/stable/installing/  
4. pip install virtualenv  
5. pip install virtualenvwrapper-win
6. Learn to love http://www.lfd.uci.edu/~gohlke/pythonlibs/  
7. https://pip.pypa.io/en/latest/user_guide/#installing-from-wheels  
  
## Linux  
  
1. Python is already available  
(if not then `sudo yum install python` or  
`sudo apt-get install python`)
2. pip install pyenv
3. Install other versions as needed
4. pip install virtualenv and use that extensively
  
## The [Conda alternatives](https://conda.io/docs/intro.html)
 * Anaconda and Miniconda  
 * [Taking Conda for a test drive](https://conda.io/docs/test-drive.html)
  
## Some great docs  
  
 * [Installing on MacOS](http://sourabhbajaj.com/mac-setup/Python/README.html)  
 * [Installing on Windows](http://docs.python-guide.org/en/latest/starting/install/win/)  
 * [Installing on Linux](http://docs.python-guide.org/en/latest/starting/install/linux/)  
 * [Using Virtual Environments](http://docs.python-guide.org/en/latest/dev/virtualenvs/)
