# Upgrade pip and install libraries
pip install -U pip
pip install playwright openpyxl

# Install Playwright browser binaries
playwright install

# Run the Playwright Script
python test_automation.py --excel "IT23838802/IT23838802.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open
