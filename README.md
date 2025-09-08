# Crypto Price Tracker

 A Python tool that fetches real-time cryptocurrency prices (e.g., Bitcoin, Ethereum, Solana) from a public API and displays them in the terminal 
Useful for developers, traders, or anyone who wants quick access to crypto price data.

## Features
- Get live prices for popular cryptocurrencies
- Supports multiple coins
- Lightweight and easy to run
- Extendable for your own needs

## Installation
```bash
# Clone the repository
git clone https://github.com/username/crypto-price-tracker.git

# Enter the project directory
cd crypto-price-tracker

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

## Usage
```bash
# Run the script
python tracker.py
```

Example output:
```
BT: $63,241.55
ETH: $3,127.20
SOL: $148.90
```

## Configuration
You can edit `config.json` to choose which coins to track.

## Contributing
Pull requests are welcome. Please open an issue first to discuss any major changes.

## License
This project is licensed under the MIT License.
