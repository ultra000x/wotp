# wotp
WhatsApp OTP acquisition engine for Termux. Fast and reliable number renting + OTP retrieval tool.

<h1><b>WOTP - WhatsApp OTP Engine</b></h1>

### Description
**wotp** is a lightweight and fast Python script for Termux designed to obtain WhatsApp numbers and receive OTPs quickly and easy.

##

### Installation

```bash
apt update && apt upgrade -y
apt install git python -y
pip install requests colorama qrcode pillow
rm -rf wotp
git clone --depth=1 https://github.com/ultra000x/wotp.git
cd wotp
python run.py
```

##

### Features
- Fast scanning for the cheapest available numbers
- Multi-network crypto top-up support (USDT & USDC on Polygon, Solana, TON, Arbitrum, BSC)
- Automatic resecure funds (cancels pending numbers on crash or network issues)
- QR code generation for easy wallet top-up
- Session balance tracking and detailed spending report

### Requirements
- Termux (fdroid version recommended)
- Termux API
- Python 3

### Notes
- Prices and availability can change at any time depending on the provider.
- Always send funds to the correct network when topping up (wrong network = funds lost).
- For fast top-up (10-59 minutes) or any support, contact me directly.
- The tool is designed for personal and educational use.

### Disclaimer
This tool is provided for educational and personal use only. ultraX is not responsible for any misuse, account bans, or violations of any service terms. Users are solely responsible for their actions and must comply with all applicable laws in their country. Use at your own risk.

##

```python
print("Goodluck!")
```
```
