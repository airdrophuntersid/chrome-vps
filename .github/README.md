## Chrome VPS
> Recommended Using Ubuntu

### Update & Upgrade Package
    sudo apt update && sudo apt upgrade -y

### Install Requirements
    sudo apt-get install -y wget curl gnupg ca-certificates supervisor lsb-release

### Enable Port & Setup Firewall
    sudo ufw allow 5800
    sudo ufw allow 80
    sudo ufw allow 443
    sudo ufw reload

### Setup Your Config
  * File rename.env to .env

  <kbd>
Change the rename.env file to .env and fill in your username & password for later login.
  </kbd>

### Running
    docker-compose up --build -d


### Access using VPS IP
    https://VPS_IP

  <kbd>
Login: Username dan password which was previously set in the .env file
  </kbd>
