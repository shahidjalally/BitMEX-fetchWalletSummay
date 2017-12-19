# BitMEX-fetchWalletSummay
BitMEX Exchange API script add-on to fetch Wallet Summ

This little payton script is required https://github.com/BitMEX/easy-data-scripts repository to work.

put this file into same directory wheres you have already downloaded above repository.

# Using the script:

# View help
# Generate CSV file
python fetchWalletSummary.py > walletsummary.csv
# Filter results to a single contract
python fetchWalletSummary.py --filter='{"symbol": "XBTUSD"}' > walletsummary.csv
