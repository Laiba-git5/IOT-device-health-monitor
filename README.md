# Day 2 of Python Learning 🚀
Built an IoT Device Health Monitoring mini-project that dynamically takes user input, analyzes, and gives a full report.

## Features
- Takes input for multiple IoT devices  
- Analyzes battery, signal, and packet loss  
- Groups devices by health status  
- Calculates average packet loss  

## Example Output
Enter number of devices: 2
Enter name of device 1: Oppo
Enter battery % of Oppo: 45
Enter signal strength (negative dBm) of Oppo: -80
Enter packet loss % of Oppo: 10
Enter name of device 2: iPhone
Enter battery % of iPhone: 19
Enter signal strength (negative dBm) of iPhone: -79
Enter packet loss % of iPhone: 50

 Device Health Monitoring Report 

Filtered Devices (critical conditions):
iphone | Battery: 19% | Signal: -79 dBm | Packet Loss: 50%

 Status of All Devices:
oppo → HEALTHY
iphone → CRITICAL

 Average Packet Loss: 30.00%

 Grouped Devices by Status:
HEALTHY: oppo
CRITICAL: iPhone
