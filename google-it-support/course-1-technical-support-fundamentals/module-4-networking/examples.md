# 🧪 Examples — Module 4 Networking


## Example: Client-Server Interaction
- A user opens **Google Chrome** and enters `www.example.com`.  
- The browser (client) sends a request to the **web server**.  
- The server responds with the webpage, which the client displays.  

---

## Example: Web Server
- A **web server** (e.g., Apache, Nginx) hosts HTML and CSS files.  
- Clients (browsers) request these files via HTTP/HTTPS.  
- The server delivers them to be rendered.  

---

## Example: ISP Role
- Home user → Router → ISP → Internet.  
- ISP assigns a **public IP address** to the router.  
- Allows devices on the LAN to connect to the Internet.  

---

## Example: Checking IP Address
- On Linux:
  ```bash
  ip addr show

- On Windows:
 powershell
 ipconfig

---

## Example: Finding MAC Address
- On Linux:
  ```bash
  ip link show

- On Windows:
 powershell
 getmac

## Example: Connecting to a Network
- **Ethernet**: plug an Ethernet cable into the network port.  
- **Wi-Fi**: select the wireless network, enter the password, and connect.  

---

## Example: Fiber Optic
- Used by ISPs for high-speed Internet.  
- Transfers data as light pulses inside glass fibers.  

---

## Example: Router Packet Flow
- Device sends data → router checks IP → forwards to correct destination.  
- Inside LAN: router/switch sends to another device locally.  
- Outside LAN: router sends to ISP → Internet backbone → destination.  

---

## Example: TCP/IP Stack
- **Application**: HTTP request  
- **Transport**: TCP segments the data  
- **Network**: IP adds source/destination addresses  
- **Link**: Ethernet transmits frames over cable  

---

## Example: Hub vs Switch
- **Hub**: sends data to all connected devices.  
- **Switch**: sends data only to the target device (based on MAC).  

---

## Example: Website and URL
- URL: `https://www.example.com/page?id=2`  
  - Protocol: `https://`  
  - Domain: `www.example.com`  
  - Path: `/page`  
  - Query: `?id=2`  

---

## Example: DNS Resolution
1. User types `www.google.com`.  
2. Browser queries DNS.  
3. DNS server returns IP address (e.g., 142.250.190.68).  
4. Browser connects to that IP.  

---

## Example: IPv4 vs IPv6
- IPv4: `192.168.0.1`  
- IPv6: `2001:0db8:85a3::8a2e:0370:7334`  

---

## Example: NAT in Practice
- Home network devices (192.168.0.x) share one public IP via the router.  
- NAT translates private addresses to public when accessing the Internet.  

---

## Example: IoT Device
- Smart bulb connects to Wi-Fi.  
- Controlled via mobile app using the Internet.  

---

## Example: Privacy and Security
- User uses HTTPS for secure browsing.  
- VPN hides IP and encrypts traffic.  

---

## Example: ARPANET History
- 1969: first ARPANET message sent between UCLA and Stanford.  
- Basis of today’s Internet.  




