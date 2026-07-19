# compile-python
This is a repo for compiling and installing python

## Compile Python and Create VirtualEnv with It

'sudo apt-get install build-essential gdb lcov libbz2-dev libffi-dev libgdbm-dev liblzma-dev libncurses5-dev libreadline6-dev libsqlite3-dev libssl-dev lzma lzma-dev tk-dev uuid-dev zlib1g-dev'

'wget https://www.python.org/ftp/python/3.14.6/Python-3.14.6.tgz'

'tar zxvf Python-3.14.6.tgz'

'rm Python-3.14.6.tgz'

'./configure --enable-optimizations'

### Saturate all cores while using the make command

'make -j 16'

'sudo make altinstall'

### Make Python the default in bashrc

'nano ~/.bashrc'

'alias python="/usr/local/bin/python3.14"'

'source ~/.bashrc'

### create python venv and directory

'python -m venv ~/.venv'

### return to bashrc in nano:

'source ~/.venv/bin/activate

### set up template for python projects

'touch requirements.txt'

'touch Makefile'