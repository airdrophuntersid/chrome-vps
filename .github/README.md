## Chrome VPS (Chromium)
> Recommended Using Ubuntu/Debian (Linux)

### Update & Upgrade Package
    sudo apt update && sudo apt upgrade -y

### Install Requirements
    sudo apt install -y apt-transport-https ca-certificates curl software-properties-common gnupg

### Enable Port & Setup Firewall
    sudo ufw enable
    sudo ufw allow 3010
    sudo ufw allow 3011

### Setup Your Config
  * File rename.env to .env

  <kbd>
Change the rename.env file to .env and fill in your username & password for later login.
  </kbd>

### Running
    docker-compose up --build -d

### Access using IP VPS
    https://IP_VPS:3010 or https://IP_VPS:3011

  <kbd>
Login: Username dan password which was previously set in the .env file
  </kbd>

### Stop Chromium
    docker stop chromium
