# Paybag

Create metasploit payload easily using Paybag

![Screenshot]()


# Installation

### For Linux users -
    sudo apt-get install python3 python3-pip net-tools
    
    git clone https://github.com/anya-hacker/PC_HACKING_By_Anya.git
    
    cd Paybag
    
    sudo pip3 install -r requirements.txt
    
    python3 paybag.py
    
### For Termux users -
    apt install python wget 
    
    git clone https://github.com/anya-hacker/PC_HACKING_By_Anya.git
    
    cd Paybag
    
    pip install -r requirements.txt
    
    python paybag.py



# What's New in v1.4?

1) Bugs Fixed

- There are some issues while installing Metasploit in Termux. This update will not install Metasploit in termux. Users need to install it manually.



# Usage

**1) Create a payload**
- Create a payload by just giving LHOST and LPORT and send it to victim.

**2) Start Listner**
- After creating payload,send it to victim & execute it on victim machine.
- After execution,Select **'Start Listner'**,select LHOST from table and enter LPORT which used while creating payload.
- Now wait until a successfull connection.

**3) Launch Metasploit**
- Start Metasploit using **Launch Metasploit** option.

-----------------------------------------------------------------------------------------------------

### All payloads are stored in 'payload' folder.

-----------------------------------------------------------------------------------------------------

### Tested on - Ubuntu 20.04, Kali linux & Termux

-----------------------------------------------------------------------------------------------------

### If you have any issue regarding this,report an issue [here]()


-----------------------------------------------------------------------------------------------------

## P.S. - Somebody already stole this script and even I'm not surprised ;)

