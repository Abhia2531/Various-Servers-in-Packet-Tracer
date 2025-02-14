# Various-Servers-in-Packet-Tracer

## Overview
This project is a **Cisco Packet Tracer** network simulation that includes **five different servers** configured for various network services. It is designed to simulate a realistic networking environment for learning and testing purposes.

## Features
- **Five Different Servers:**
  - **Web Server** (Hosts a basic website)
  - **DNS Server** (Handles domain name resolution)
  - **DHCP Server** (Assigns dynamic IP addresses)
  - **FTP Server** (Allows file transfers)
  - **Email Server** (Handles email communication)
- **Router and Switch Configuration**
- **Client Workstations for Testing**
- **Basic Security Configurations**

## Installation & Setup
### Prerequisites
Ensure you have the following:
- **Cisco Packet Tracer (Latest Version)** installed.
- The `.pkt` file for the network simulation.

### Steps to Open the Project
1. Download the `.pkt` file from this repository.
2. Open **Cisco Packet Tracer**.
3. Click on **File > Open**, and select the `.pkt` file.

## Network Configuration
### Router Setup
- The router is configured with basic **static routes**.
- Uses **NAT (Network Address Translation)** to enable external communication.

### Server Details
| Server Type  | IP Address | Function |
|-------------|-----------|----------|
| Web Server  | 192.168.1.10 | Hosts a sample website |
| DNS Server  | 192.168.1.20 | Resolves domain names |
| DHCP Server | 192.168.1.30 | Assigns dynamic IPs |
| FTP Server  | 192.168.1.40 | Manages file transfers |
| Email Server | 192.168.1.50 | Handles email services |

## Testing the Network
1. **Check connectivity** using the `ping` command.
   ```sh
   ping 192.168.1.10  # Test Web Server connectivity
   ```
2. **Access the Web Server** via a browser in Packet Tracer.
3. **Verify DHCP Configuration** on a client workstation.
4. **Use an FTP client** to connect to the FTP Server.
5. **Send a test email** through the configured email server.

## Future Enhancements
- Implement **firewall rules** for better security.
- Add **VPN support** for secure remote access.
- Configure **Load Balancing** for Web and Email Servers.

## Contributing
Feel free to fork this repository and submit **pull requests** for improvements.
