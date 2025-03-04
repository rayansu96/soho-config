# soho-config

In order to set up a Soho router, your ISP or Internet Service Provider (eg. Spectrum, Verizon) must provide you with a modem.

Step 1: Connect your modem to the router’s WAN port using an Ethernet cable. This connects the router to the internet.
Step 2: Use an Ethernet cable (RJ45) to connect the LAN (Local Area Network) port of your modem to the WAN (Wide Area Network) port of the router.

        The router has many functions:
          - DNS (Domain Name System) which converts a domain's IP address into a readable name for the end user (e.g., converting 8.8.8.8 into google.com)
          - DHCP (Dynamic Host Configuration Protocol) which dynamically assigns an IP address to an device on your network.
          - NAT (Network Address Translator) which translates your private IP address into a public address to provide Internet access to local hosts.
          - Switch Allows LAN, WAN and Ethernet ports to communicate
          - Firewall, which protects your network from any unknown and unwanted access, can be refined using an ACL (Access Control List)
          - WAP (Wireless Access Point) which is your WiFi connection. 
    
Router acts as a switch through LAN ports 

Allows firewall to automatically change settings to open and close ports, diminishing the security. 

Use another Ethernet cable to connect your computer/laptop to one of the LAN ports on the router.
The LAN ports (Local Area Network) are used to distribute the internet connection to wired devices within the network.
Power Up the Router
Plug the router’s power adapter into a wall outlet and turn it on.
Wait for the router to boot up—this usually takes a minute or two.

Step 3: Router Configuration
Access the Router’s Web Interface
Open a web browser and enter the router’s default IP address (e.g., 192.168.1.1 or 192.168.0.1—this is usually printed on the router or in the manual).
Log in with the default username and password (often “admin/admin” or “admin/password”).
Set Up WAN (Internet) Connection
Choose the connection type:
DHCP (Dynamic IP) – Automatically gets an IP address from the ISP (common for most users).
PPPoE (Point-to-Point Protocol over Ethernet) – Requires a username and password provided by your ISP.
Static IP – Requires manually entering an IP address assigned by the ISP.
Configure Wireless (Wi-Fi) Settings
Set an SSID (Wi-Fi network name) and a strong password.
Choose a Wi-Fi security type (WPA2 or WPA3 for best security).
Optionally, configure separate 2.4GHz and 5GHz bands for better device management.
Set Up LAN (Local Network) Configuration
The router assigns IP addresses to connected devices using DHCP (Dynamic Host Configuration Protocol).
You can manually assign static IP addresses for important devices like printers or servers.
Enable Firewall & Security Features
Activate the built-in firewall to block unauthorized access.
Configure port forwarding if needed (for remote access to certain devices).
Set up MAC address filtering to limit which devices can connect to the network.
Save Settings and Reboot
After making changes, save settings and restart the router if necessary.

Step 4: Test the Connection
Check Internet Access
Disconnect the Ethernet cable from the computer and connect via Wi-Fi to test wireless connectivity.
Open a browser and visit a website to confirm internet access.
Check Device Connectivity
Ensure that wired and wireless devices can communicate properly.
If using shared printers or file servers, test network access between devices.

Understanding Each Connection
Connection Type
Purpose
WAN Port (Internet Port)
Connects the router to the modem for internet access.
LAN Ports (Ethernet Ports)
Provides wired connections to local devices (PCs, printers, etc.).
Wi-Fi (2.4GHz & 5GHz)
Wireless network for devices (2.4GHz has longer range, 5GHz is faster).
Power Adapter Port
Supplies power to the router.
USB Port (if available)
Used for external storage, printers, or cellular modem connections.


Final Notes
Keep firmware updated to improve security and performance.
Use QoS (Quality of Service) settings if you need to prioritize bandwidth for certain activities (e.g., VoIP, gaming).
If experiencing connectivity issues, restart the router and modem before troubleshooting further.
Would you like help with any specific router model or advanced configurations like VPN or VLANs?

