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

Insert the network topology from Packet Tracer (Screenshot or drawing)
<img width="1912" height="1075" alt="Screenshot 2026-10-15 172840" src="https://github.com/user-attachments/assets/143d8917-d21f-4261-bd9a-1db5140dd690" />

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

Insert screenshots showing ping success, configuration, or simulation results.
<img width="1917" height="1078" alt="Screenshot 2026-10-15 172914" src="https://github.com/user-attachments/assets/acfc9d7a-a0cf-4a53-87b4-1f0136625ee6" />
<img width="1917" height="1078" alt="Screenshot 2026-10-15 172942" src="https://github.com/user-attachments/assets/21c663c6-e4aa-4aa7-b1cf-ab1bf2120b18" />
<img width="1907" height="1078" alt="Screenshot 2026-10-15 173032" src="https://github.com/user-attachments/assets/f855483c-e957-49c1-a609-b7892b1920f8" />

________________________________________
# Result
“Successfully configured and verified basic LAN communication between two PCs using a switch in Cisco Packet Tracer.”
	
