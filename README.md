# BCTJV-GP-Tutorial  
A Gaussian Process Tutorial @BCTJV   
Jan 9, 2017 @ SNU   
Instructor: Sangwoong Yoon (swyoon@idnstory.com)   

## How to start : Running on the localhost 
Assuming that you are creating a new virtual environment and already have python and pip.  
The following commands are tested on Ubuntu 14.04 and MacOS 10.12.2.
First, setting up the virtrualenv.


1. ```[sudo] pip install virtualenv```
2. ```virtualenv [your_env]```
3. ```source [your_env]/bin/activate```

Clone and install required packages.

1. ```git clone https://github.com/swyoon/BCTJV-GP-Tutorial.git```
2. ```cd BCTJV-GP-Tutorial```
3. ```pip install -r requirements.txt```

Enable ipywidgets.

1. ```jupyter nbextension enable --py --sys-prefix widgetsnbextension```

Run jupyter on your local host. Additional settings (port and password) are required to run a remote server.

1. ```jupyter notebook```

You should be able to see jupyter on your browser.

