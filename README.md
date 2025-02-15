Excited to have a new laptop and next step is to install Ubuntu along with Windows.
1. inside windwos, turn off encryption, turn off security, turn of bitlocker
1.1 download latest iso image
1.2 burn it into usb memory stick
2. Enter into BIOS (HP using F10 key, and Dell using F2 key)
3. Inside BIOS, 
3.1 use The BIOS is set to UEFI
3.2 SATA Operation is set to Advanced Host Controller Interface (AHCI) 
3.3 Disable the Legacy option Read-Only Memory (ROM)s
3.4 Disable the secure boot 
3.5 Change boot order and make USB to the top
3. Restart the computer and enter into Try-or-install Ubuntu
3.1 all default setting
3.2 along with windows
3.3 adjust the volume for ubuntu
all done, remove usb and restart the computer

4. set up
4.1 download Chrome as default browser
4.2 install Pycharm
4.3 Terminal install git $sudo apt install git
4.4 clone this repo for further instruction $git clone https://github.com/42195CA/ubuntu_abc.git



5. Python Env
5.1 create a folder /home/xliu/Documents/Code
5.2 $whereis python3
python3: /usr/bin/python3 /usr/lib/python3 /etc/python3 /usr/share/python3 /usr/share/man/man1/python3.1.gz
5.2 $python3    #check version, it is 3.12 
5.3 sudo apt install python3.12-venv
5.4 python3 -m venv venv_py312  # create a new venv nameed venv_py312
5.5 source venv_py312/bin/activate #active this venv
5.6 Pycharm 
5.6.1 New Project - Git - Custom environment - type (virtual env) - 
