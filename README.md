xiaoyang.liu@gmail.com
Feb 14, 2025

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

6. Git
6.1 $git status,  git add .  git commit -m "log",  git push
6.2 need a token, below is how to get a token from github.com
https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens#creating-a-personal-access-token-classic
Verify your email address, if it hasn't been verified yet.
In the upper-right corner of any page on GitHub, click your profile photo, then click  Settings.
In the left sidebar, click  Developer settings.
In the left sidebar, under  Personal access tokens, click Tokens (classic).
Select Generate new token, then click Generate new token (classic).
In the "Note" field, give your token a descriptive name.
To give your token an expiration, select Expiration, then choose a default option or click Custom to enter a date.
Select the scopes you'd like to grant this token. To use your token to access repositories from the command line, select repo. A token with no assigned scopes can only access public information. For more information, see Scopes for OAuth apps.
Click Generate token.
Optionally, to copy the new token to your clipboard, click .
Screenshot of the "Personal access tokens" page. Next to a blurred-out token, an icon of two overlapping squares is outlined in orange.
To use your token to access resources owned by an organization that uses SAML single sign-on, authorize the token. For more information, see Authorizing a personal access token for use with SAML single sign-on in the GitHub Enterprise Cloud documentation.





