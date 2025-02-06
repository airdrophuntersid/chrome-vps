## Chrome VPS (Chromium)
> Recommended Using Ubuntu/Debian (Linux)
> shm size: 1gb

### Update & Upgrade Package
    sudo apt update && sudo apt upgrade -y

### Install Requirements
    sudo apt install -y apt-transport-https ca-certificates curl software-properties-common

### Enable Port & Setup Firewall
    sudo ufw allow 3010
    sudo ufw allow 3000

### Setup Your Config
  * File rename.env to .env

  <kbd>
Change the rename.env file to .env and fill in your username & password for later login.
  </kbd>

### Running
    docker-compose up --build -d

### Access using VPS IP
    https://VPS_IP:3010 or https://VPS_IP:3011

  <kbd>
Login: Username dan password which was previously set in the .env file
  </kbd>
