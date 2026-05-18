## CREATE A TCP CLIENT
> This version requires **Python 2.9** or above, ideally make sure your devices support **Python 3**

## 1. Prerequisites

* To create a **tcp client**, first you have to run a **virtual machine** and setting an enviroment for it.
You can download VMware at the link: https://www.vmware.com/. 

Then, depending on your needs:
* If you want to run **Kali Linux** in a virtual machine, go to: https://www.kali.org/get-kali/#kali-virtual-machines and download the version for VMware.
* If you want to run **Ubuntu or other operating systems**, just go to their official websites and download the suitable version for VMware.
> Make sure your disks have enough space for one opertaing systems and the memmory required is **2GB**

## 2. Installation

* First, you need to setting up **Python3**. After running Kali Linux, turn on **terminal** and execute the following:

  **sudo apt update**
  
  **sudo apt upgrade**
  
  **sudo apt dist upgrade**
  
  **sudo apt autoremove**
  > Each step required a bit of time, so you rather have a coffee while waiting it

Then, you type in ```sudo apt get-upgrade python3``` and ```sudo apt-get install python3-venv```
* Now, you can create an environment. Let's make new directory to work and create the environment
* In the new terminal, you type in ```mkdir hello``` to generate new directory, then types ```cd hello```

Now, you have created a directory and jump into it, its time to install and IDE, followings these steps
 Type in ```apt-get install code``` or to get the latest version of VSCode ```apt-get install -f./code_1.39.2-1571154070_amd64.deb```


  
