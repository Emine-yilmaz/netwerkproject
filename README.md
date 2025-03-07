# Network Design Project: LAN-1 and LAN-2

This project involves the design and integration of two separate LAN networks (LAN-1 and LAN-2). Both networks have been configured with DHCP, DNS, HTTP servers, and wireless network settings. Additionally, routing and network configurations have been implemented to ensure communication between LAN-1 and LAN-2.

## Project Requirements

### **LAN-1 Design Requirements**
1. **Network Components:**
   - A computer, laptop, access point, and switch will be added.
2. **IP Configuration:**
   - Computers and laptops will automatically receive IPs.
   - LAN-1 IP address range: **192.168.25.1-254**.
3. **Server0 Configuration:**
   - **Server0** will be the DHCP server and will automatically distribute IP addresses between 192.168.25.20 and 192.168.25.40.
   - **Server0** will be the DNS server and will perform IP name resolution for all computers and laptops.
   - **Server0** will be the HTTP server.
4. **Wireless Network:**
   - LAN-1 will have the SSID **VIT1B**, and WPA2 encryption will be used for wireless connection.
5. **Router Configuration:**
   - LAN-1 router connection IP: **192.168.25.1**.
6. **Communication:**
   - All computers and laptops in LAN-1 must be able to communicate with each other.

### **LAN-2 Design Requirements**
1. **Network Components:**
   - A computer, laptop, access point, and switch will be added.
2. **IP Configuration:**
   - Computers and laptops will automatically receive IPs.
   - LAN-2 IP address range: **192.168.35.1-254**.
3. **Server1 Configuration:**
   - **Server1** will be the DHCP server and will automatically distribute IP addresses between 192.168.35.120 and 192.168.35.140.
   - **Server1** will be the DNS server and will perform IP name resolution for all computers and laptops.
   - **Server1** will be the HTTP server.
4. **Wireless Network:**
   - LAN-2 will have the SSID **VIT2B**, and WPA2 encryption will be used for wireless connection.
5. **Router Configuration:**
   - LAN-2 router connection IP: **192.168.35.1**.
6. **Communication:**
   - All computers and laptops in LAN-2 must be able to communicate with each other and with devices in LAN-1.

## Technologies Used
- **Cisco Packet Tracer**: Used for network design and simulation.
- **DHCP (Dynamic Host Configuration Protocol)**: Used for automatic IP distribution.
- **DNS (Domain Name System)**: Used to provide name resolution services.
- **HTTP Server**: Used to provide web server services.
- **WPA2 Encryption**: Used for securing the wireless network.

## Project Setup
1. **Separate router connections were created for LAN-1 and LAN-2.**
2. **DHCP servers were configured for both networks, and IP address ranges were set.**
3. **Server0 and Server1 were configured to provide DNS and HTTP services.**
4. **Wireless networks were created with SSIDs, and WPA2 security protocols were implemented.**
5. **Routing was configured between LAN-1 and LAN-2 to enable communication between the networks.**

## Project Configuration Steps
1. **A new project was created in Cisco Packet Tracer.**
2. **Network devices (PC, laptop, switch, router, server) were added for both LANs.**
3. **VLAN subinterfaces were created on the routers, and IP addresses were assigned.**
4. **DHCP servers were configured, and IP distribution ranges were defined.**
5. **DNS servers were configured.**
6. **HTTP servers were set up, and web pages were created.**
7. **Wireless networks were configured with SSIDs and WPA2 encryption.**

## Installation and Running
1. **Download and install Cisco Packet Tracer** software on your computer.
2. Download and open the project file: `netwerkproject.pkt`.
3. Simulate the project in Cisco Packet Tracer and verify that both networks are working correctly.
