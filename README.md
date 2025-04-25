Installation:

Clone the repository: git clone https://github.com/yourusername/web-scraping.git cd web-scraping
Create a virtual environment and activate it: python -m venv venv source venv/bin/activate # On Windows, use venv\Scripts\activate
Install dependencies: pip install -r requirements.txt

Configuration:

Edit config.py to add your proxy details:

config.py
PROXY_URL = 'socks5://login:password@ip:port'

Usage:

Command-Line Version
To run the command-line version:
1. Open a terminal or command prompt.
2. Navigate to the project directory.
3. Run the script: python google_search.py
You will be prompted to enter a search query and the number of results to retrieve. The results will be saved to results/results.csv

GUI Version
To run the GUI version:
1. Open a terminal or command prompt.
2. Navigate to the project directory.
3. Run the script: python google_search_gui.py
A window will open where you can enter a search query and the number of results to retrieve. The results will be saved to results/results.csv

Contributing:
Feel free to open issues or submit pull requests with improvements or new features.

License:
This project is licensed under the MIT License.
