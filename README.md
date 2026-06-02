# CREATE A TCP CLIENT 

> **Note:** This project requires **Python 3** (Python 3.6 or above is recommended). Please make sure your device supports it.

## 1. Prerequisites

To create a TCP client, you first need to set up a virtual machine environment. 
You can download VMware from their official website: [https://www.vmware.com/](https://www.vmware.com/)

Then, depending on your needs, choose an operating system:
* For **Kali Linux**: Go to the [Kali Linux VMware download page](https://www.kali.org/get-kali/#kali-virtual-machines) and download the pre-built VM version.
* For **Ubuntu or other OS**: Visit their official websites and download the suitable ISO or virtual machine image.

> **Hardware Requirement:** Make sure your host machine has enough disk space for the operating system and at least **2GB of RAM** allocated for the virtual machine.

## 2. Installation & Environment Setup

### Update System
First, update your Kali Linux system. Open the terminal and run the following commands sequentially:

```bash
sudo apt update
sudo apt upgrade -y
sudo apt dist-upgrade -y
sudo apt autoremove -y
```
> *Each step requires a bit of time, so you might want to grab a coffee while waiting!* ☕

### Install Python 3
Ensure Python 3 and the virtual environment package are installed on your system:

```bash
sudo apt install python3 python3-venv -y
```

### Create a Workspace
Now, let's make a new directory for your project and navigate into it:

```bash
mkdir tcp_client_project
cd tcp_client_project
```

### Install an IDE (VS Code)
It's time to install an IDE to write your code. The easiest way to get the latest version of Visual Studio Code on Kali Linux is to download the `.deb` package from the [official VS Code website](https://code.visualstudio.com/). 

After downloading, run this command in the terminal (make sure you are in the folder where the file was downloaded):

```bash
sudo apt install ./<downloaded_file_name>.deb
```
*(Remember to replace `<downloaded_file_name>.deb` with the actual name of the file you just downloaded).*

## 3. Usage
* You can find the file ```tcp_client.py``` that i have posted and run it in your own
> If you do not know where the file at, follow the instruction below
## Repository Structure
* Below is the directory tree showing where the file is located

```text
Python-Networking/       # my repository
├── README.md            # README
|
└── tcp_client.py        # you should begin at here!
