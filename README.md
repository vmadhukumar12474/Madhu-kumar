# Madhu-kumar
# VSD-Tool-Installation.  
## **Comprehensive guidelines for installing all the necessary tools are provided here:**  
### **Tool installation process:**  
### **System Requirements:**   
- perating System: Ubuntu 20.04 LTS  
- RAM: Minimum 6 GB  
- Hard Disk Space: At least 50 GB free space  
- CPU: 4 vCPUs or equivalent  
- Dependencies: Basic development tools including python3 and other related libraries  
- Network: Active Internet connection for package downloads  
    
<u>**Tool Check:**</u>  
<u>**1.Yosys**</u>  
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
$ sudo make install
```  
 <img width="1200" height="49" alt="Screenshot from 2025-09-20 19-42-54" src="https://github.com/user-attachments/assets/bf38a8ab-4a98-4d2e-b08b-ba06bf2048e7" />
    

<u>**2.Iverilog**</u>

```
$ sudo apt-get update
$ sudo apt-get install iverilog
```
<img width="1200" height="994" alt="Screenshot from 2025-09-20 19-45-32" src="https://github.com/user-attachments/assets/bbc64fe4-7500-4cbb-9ee4-4e4f1133014f" />
<img width="1200" height="612" alt="Screenshot from 2025-09-20 19-45-50" src="https://github.com/user-attachments/assets/8fd84950-5cd4-4173-a368-5ead231e9109" />

<u>**3.gtkwave**</u>
```
$ sudo apt-get update
$ sudo apt install gtkwave
```
<img width="1200" height="122" alt="Screenshot from 2025-09-20 19-46-49" src="https://github.com/user-attachments/assets/1d9dec23-57c7-4485-9df3-8733c27a4ef9" />

