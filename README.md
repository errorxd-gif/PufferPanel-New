# This Is Some Important Commands If You Dont Run This Command Your Pufferpanel Will Not Install Successfully

1. Update Your Vps With This Command

'''apt update'''

2. Install Sudo With This Command

'''apt install sudo'''

3. Install Systemctl With This Command

'''apt install systemctl'''


# Now Installing Panel
1. Install Packages

'''curl -s https://packagecloud.io/install/repositories/pufferpanel/pufferpanel/script.deb.sh?any=true | sudo bash'''

2. Update

'''sudo apt update'''

3. Install Pufferpanel

'''sudo apt-get install pufferpanel'''

4.Adding An Admin Account

'''sudo pufferpanel user add'''

5.Enabling Pufferpanel

'''sudo systemctl enable --now pufferpanel'''

