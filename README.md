# BitQuant BOT
BitQuant BOT

- Register Here : [BitQuant](https://www.bitquant.io/?invite=OjMqAq9_5yUyjg)
- Sign With New SOL Wallet

## Features

  - Auto Get Account Information
  - Auto Run With [Proxyscrape Free Proxy](https://proxyscrape.com/free-proxy-list) - `Choose 1`
  - Auto Run With Private Proxy - `Choose 2`
  - Auto Run Without Proxy - `Choose 3`
  - Auto Rotate Invalid Proxies - `y` or `n`
  - Auto Perform Daily Chats
  - Multi Accounts

## Requiremnets

- Make sure you have Python3.9 or higher installed and pip.
- 2captcha key

## Instalation

1. **Clone The Repositories:**
   ```bash
   git clone https://github.com/airdropbomb/BitQuantpy.git && cd BitQuantpy
   ```

2. **Install Requirements:**
   ```bash
   pip install -r requirements.txt #or pip3 install -r requirements.txt
   ```

## Configuration

- **accounts.txt:** You will find the file `accounts.txt` inside the project directory. Make sure `accounts.txt` contains data that matches the format expected by the script. Here are examples of file formats:
  ```bash
    your_solana_private_key_1 (base58)
    your_solana_private_key_2 (base58)
  ```

- **2capctha_key.txt:** You will find the file `2capctha_key.txt` inside the project directory. Make sure `2capctha_key.txt` contains data that matches the format expected by the script. Here are examples of file formats:
  ```bash
    your_2captcha_key
  ```

- **proxy.txt:** You will find the file `proxy.txt` inside the project directory. Make sure `proxy.txt` contains data that matches the format expected by the script. Here are examples of file formats:
  ```bash
    ip:port # Default Protcol HTTP.
    protocol://ip:port
    protocol://user:pass@ip:port
  ```

## Run

```bash
python bot.py #or python3 bot.py
```

