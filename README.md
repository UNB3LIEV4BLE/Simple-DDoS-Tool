# Simple-DDoS-Tool
Simple DDoS Tool ;)

- Deployment

Pre-requisits:
Install Python3 (Python 3.7.3) with pip3
Quick Setup
Clone the repository: git clone https://github.com/Lekssays/ddos-tool.git
Install pip requirements: pip3 install -r requirements.txt
Run the program
Usage: python3 script.py [-h] [-u USER_AGENTS] -t TARGET -tr THREADS -s SLEEP
Example: python3 script.py -u user_agents.txt -t http://example.com -tr 1000 -s 200
-h: to display help menu
-t: to specify the target (REQUIRED)
-u: to specify user-agents text file (REQUIRED)
-tr: to specify number of threads (OPTIONAL, by default 1000)
-s: to specify number of threads executed before a break of 10 seconds (OPTIONAL, by default 100)
Disclaimer
This project is fully implemented for educational purposes only and I am not responsible by any means for any misuse.
