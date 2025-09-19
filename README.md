# VSD-Tapeout
**WEEK 0**

  **Task-2:**    Install Tools and Update Repo

Before you begin, ensure your virtual machine meets the following requirements:

    Operating System: Ubuntu 20.04+
    RAM: 6GB
    HDD: 50 GB
    vCPU: 4

  ( Even u can do it in windows through virtual machine )

  **Install the Tools**

Follow the provided commands to install each tool. Open a terminal in your Ubuntu virtual machine and execute the commands in the order listed.

Before that just update your system using 
<div >

```
$ sudo apt-get update
```

</div>

<img width="859" height="270" alt="Image" src="https://github.com/user-attachments/assets/6fa08007-bc14-48eb-a725-ab735d82eff8" />




**1.Yosys**

**Yosys synthesizes Verilog code, converting a circuit's behavioral description into an optimized netlist of logic gates.**


Clone the repo of yosys 
<div >

```
git clone https://github.com/YosysHQ/yosys.git
```

</div>

<img width="777" height="148" alt="Image" src="https://github.com/user-attachments/assets/b22993d4-bebf-44c1-972f-9b3bb8fe6b53" />


Once cloned run the below commands 
<div >

```
git clone https://github.com/YosysHQ/yosys.git cd yosys
sudo apt install make (If make is not installed please install it)
sudo apt-get install build-essential clang bison flex \libreadline-dev gawk tcl-dev libffi-dev git \graphviz xdot pkg-config python3 libboost-system-dev \libboost-python-dev libboost-filesystem-dev zlib1g-dev
make config-gcc
make
sudo make install
```

</div>
This commands installs the necessary packages



**Now you are done with Yosys**

**2.Iverilog**

**Icarus Verilog (iverilog) is a Verilog compiler and simulator used to verify the functionality of a digital circuit design.**

Just run the commands
<div >

```
sudo apt-get update
sudo apt-get install iverilog
```

</div>



