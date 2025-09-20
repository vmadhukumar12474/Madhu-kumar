# Madhu-kumar
# VSD-Tool-Installation.  
**## Comprehensive guidelines for installing all the necessary tools are provided here:**  
**##Tool installation process:**  
**##<u>System Requirements:</u>**   
    -perating System: Ubuntu 20.04 LTS  
    -RAM: Minimum 6 GB  
    -Hard Disk Space: At least 50 GB free space  
    -CPU: 4 vCPUs or equivalent  
    -Dependencies: Basic development tools including python3 and other related libraries  
    -Network: Active Internet connection for package downloads  
    
**<u>Tool Check:.</u>**
**1.<u>Yosys</u>**
```
$ sudo apt-get update
$ git clone https://github.com/YosysHQ/yosys.git
$ cd yosys
$ sudo apt install make               # If make is not installed
$ sudo apt-get install build-essential clang bison flex \
    libreadline-dev gawk tcl-dev libffi-dev git \
    graphviz xdot pkg-config python3 libboost-system-dev \
    libboost-python-dev libboost-filesystem-dev zlib1g-dev
$ make config-gcc
# Yosys build depends on a Git submodule called abc, which hasn't been initialized yet. You need to run the following command before running make
$ git submodule update --init --recursive
$ make 
$ sudo make install ```

<img width="789" height="49" alt="Screenshot from 2025-09-20 19-42-54" src="https://github.com/user-attachments/assets/f2943c18-9718-4a3b-b980-02f281e5b6ff" />
**<2.u>Iverilog</u>**
