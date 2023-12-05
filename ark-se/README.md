# ark-se

## Password setup

Create a `.env` file in this folder with the following content:

```bash
SERVER_PASSWORD=my_very_secret_password
SERVER_ADMIN_PASSWORD=my_very_secret_admin_password
```

## Setup firewall

```bash
sudo ufw allow 7777/udp
sudo ufw allow 7778/udp
sudo ufw allow 27015/udp
sudo ufw allow 27020/tcp
```
