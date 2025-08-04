# Internet Speed Test Tool

## Description
This Python script measures and displays your current internet connection's download speed, upload speed, and ping using the Speedtest.net service.

## Features
- Measures download speed in Mbps
- Measures upload speed in Mbps
- Displays ping latency in milliseconds
- Simple and straightforward output

## Requirements
- Python 3.x
- `speedtest-cli` library

## Installation
1. Ensure you have Python 3 installed on your system
2. Install the required package using pip:
   ```
   pip install speedtest-cli
   ```

## Usage
Run the script directly from the command line:
```
python speedtest_tool.py
```

The script will automatically:
1. Connect to the nearest Speedtest server
2. Perform download and upload tests
3. Measure ping latency
4. Display the results in the console

## Output Example
```
Download Speed: 45.23 Mbps
Upload Speed: 12.45 Mbps
Ping: 24.56 ms
```

## Notes
- The test may take 10-30 seconds to complete depending on your connection speed
- Results may vary based on network conditions and server load
- For accurate results, ensure no other devices on your network are consuming significant bandwidth during the test

## License
This project is open-source and free to use.
