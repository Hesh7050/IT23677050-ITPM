# IT23677050 - Transliteration Accuracy Testing

## Setup Instructions

### Prerequisites
- Python 3.11 or 3.12
- Google Chrome

### Install dependencies
pip3 install -U pip
pip3 install playwright openpyxl
playwright install

### Run the tests
python3 test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open