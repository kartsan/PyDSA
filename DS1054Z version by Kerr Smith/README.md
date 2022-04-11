Spectrum Analyzer for the Rigol DS1054Z digital scope    

Original code:
https://github.com/rheslip/PyDSA

This version uses python-vxi11 package to connect to the scope via network. NI-VISA is then not required. Please install python-vxi11 first:
https://github.com/python-ivi/python-vxi11/

For Ubuntu, you probably need to install these extra packages:

    # apt-get install python-tk python-numpy

## Usage

Start with a host address to your Rigol scope:

    $ python PyDSA.py 192.168.1.55

Changelog:  
4-10-2022 - first release
