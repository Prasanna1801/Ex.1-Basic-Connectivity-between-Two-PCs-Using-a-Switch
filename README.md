## Ex. No 1. 	Basic Connectivity between Two PCs Using a Switch
# Date : 15/10/2026	

# Objective

          “To configure and test basic LAN connectivity between two PCs using a switch.”
________________________________________
# Apparatus/Tools Required
•	Cisco Packet Tracer Software
•	Devices: PCs, Switch, Router, Cables
•	Optional: Wireless Router, Server, Cloud
________________________________________
# Network Topology Diagram

<img width="1913" height="1148" alt="Screenshot 2026-10-22 210750" src="https://github.com/user-attachments/assets/164d65af-d5bf-4104-8724-f88e5cefcd10" />

________________________________________
# IP Addressing Table (if applicable)
Device Name	Interface	IP Address	Subnet Mask
PC0	NIC	192.168.1.2	255.255.255.0
PC1	NIC	192.168.1.3	255.255.255.0
Router0	Fa0/0	192.168.1.1	255.255.255.0
________________________________________
# Procedure
Step-by-step commands/configurations.
Example:
1.	Open Cisco Packet Tracer and add two PCs and one Switch.
2.	Connect the PCs to the switch using straight-through cables.
3.	Assign IP addresses to the PCs.
4.	Use the ping command to verify connectivity.
________________________________________
# Commands Used (if any)

For PC IP assignment:<br>
nginx<br>
CopyEdit<br>
Desktop > IP Configuration > Enter IP: 192.168.1.2 / Subnet: 255.255.255.0<br>
For Router Configuration (CLI):<br>

________________________________________
# Output (Screenshots / Ping Results)

<img width="1919" height="960" alt="Screenshot 2026-10-22 210807" src="https://github.com/user-attachments/assets/7d2da9ac-1393-4e7d-a4f6-b5259b1c1e51" />
<img width="1919" height="1147" alt="Screenshot 2026-10-22 210830" src="https://github.com/user-attachments/assets/0ea5947c-69e2-47d1-82c3-2f4514524f35" />
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/4a53475e-9ed5-47c7-99b6-b494acb35522" />
<img width="1919" height="1147" alt="Screenshot 2026-10-22 211055" src="https://github.com/user-attachments/assets/d64386fc-0c75-40aa-a2f8-79d69f7c2b0a" />

________________________________________
# Result
“Successfully configured and verified basic LAN communication between two PCs using a switch in Cisco Packet Tracer.”
	
