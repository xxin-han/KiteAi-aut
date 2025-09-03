# Kite AI Ozone BOT
Kite AI Ozone BOT

- Register Here : [Kite AI Ozone](https://testnet.gokite.ai?referralCode=8SOHH7LG)
- Sign With New EVM Wallet
- Connect Social Media
- Complete Onboarding Tasks

## Features

  - Auto Get Account Information
  - Auto Run With Proxy - `Choose 1`
  - Auto Run Without Proxy - `Choose 2`
  - Auto Rotate Invalid Proxies - `y` or `n`
  - Auto Claim Faucets `Need 2Captcha Key`
  - Auto Deposit KITE Token
  - Auto Withdraw Tokens
  - Auto Unstake KITE Token
  - Auto Stake KITE Token
  - Auto Claim Stake Reward
  - Auto Complete Daily Quiz
  - Auto Interact With AI Agent
  - Auto Make Random Swap
  - Auto Make Random Bridge
  - Multi Accounts


## Requiremnets

- Make sure you have Python3.9 or higher installed and pip.
- 2captcha key (optional)
- Base Sepolia Faucet
- KITE Faucet

## Instalation

1. **Clone The Repositories:**
   ```bash
   git clone https://github.com/xxin-han/KiteAi-aut.git
   ```
   ```bash
   cd KiteAi-aut
   ```

2. **Create environment**
   ```bash
    python3 -m venv .venv
    source .venv/bin/activate
   ```   
4. **Install dependensi**
   ```bash
   pip install -r requirements.txt
   ```

## Configuration

- **accounts.txt:** You will find the file `accounts.txt` inside the project directory. Make sure `accounts.txt` contains data that matches the format expected by the script. Here are examples of file formats:
  ```bash
    your_private_key_1
    your_private_key_2
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
python bot.py
```
