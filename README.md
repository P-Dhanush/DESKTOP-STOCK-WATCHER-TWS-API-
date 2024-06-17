# DESKTOP-STOCK-WATCHER-TWS-API-


## Required Application : 
We use the TWS Workstation, to implement this. So, to make use of the API, you must first download it. You can use the demo account for testing out the code.
Setup Interactive Brokers TWS/Gateway
Download and install Interactive Brokers TWS or IB Gateway.
Ensure TWS/Gateway is running and properly configured for API access:
Open TWS/Gateway.
Go to File -> Global Configuration -> API -> Settings.
Check Enable ActiveX and Socket Clients.
Set the socket port (default is 7497 for paper trading).
Make sure to add 127.0.0.1 to the Trusted IP Addresses.


## Installation :

1. Clone the repository:
```sh
git clone https://github.com/P-Dhanush/DESKTOP-STOCK-WATCHER-TWS-API-.git
```
2. Navigate to the project directory:
```sh
cd DESKTOP-STOCK-WATCHER-TWS-API-
```

3. Install dependencies:
```sh
pip install -r requirements.txt
```
NOTE: You will be unable to download ibapi from pypi, so as mentioned previously you must dowload the workstation from which you'll be able to access it. Download that zip file into this location, and unzip. The module will become accessible.

Credits
This project is based on a tutorial from the blog Hacking the Markets. Many thanks to the original author for providing a comprehensive guide on using the Interactive Brokers TWS API.
