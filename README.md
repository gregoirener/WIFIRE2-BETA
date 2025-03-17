# WIFIRE 2.0 Beta ALL CODE IN BETA BRANCHE 

## Overview
WIFIRE 2.0 Beta is an advanced network monitoring and analysis tool designed for ethical penetration testing and security assessments. This updated version introduces new capabilities for detecting and logging network activity, capturing handshakes, and identifying potential vulnerabilities in Wi-Fi networks.
## GUI
![wifirepreview](https://github.com/user-attachments/assets/0c428b17-097b-46e9-af9c-9eb33c64cbd1)

## Features
- **Network Device Detection**: Monitors and logs devices connecting to or disconnecting from the network.
- **Handshake Capture**: Utilizes the best available tools for capturing WPA/WPA2 handshakes.
- **Real-Time Logging**: Tracks device activity on the network and maintains detailed logs.
- **Shell-Based Interface**: Provides a command-line interface for flexible and efficient network analysis.
- **Modular Structure**: Allows future expansion with additional attack methods and security features.

## Usage
WIFIRE 2.0 Beta operates through a command-line interface, providing users with control over network monitoring and security analysis. The main functionalities include:
- Scanning for active devices on the network
- Logging device connections and disconnections
- Capturing network handshakes for security testing

### Device Activity Logging
Inside the `detect_devices_on_network()` function, the `log_device_activity()` function should be called when a new device appears or disappears on the network. This ensures that all network changes are properly recorded in the logs.

## Ethical Considerations
WIFIRE 2.0 Beta is intended strictly for ethical use. Unauthorized network monitoring, hacking, or penetration testing without consent is illegal and unethical. Users must obtain explicit permission before performing any network analysis or security testing.

## Future Enhancements
Planned features for future versions include:
- AI-powered anomaly detection for network security
- Expanded attack simulation capabilities
- Integration with additional security tools for comprehensive analysis

## Disclaimer
This tool is for educational and security research purposes only. The developers are not responsible for any misuse or unauthorized use of this software.

