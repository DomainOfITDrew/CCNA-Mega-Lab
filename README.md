<h1>Cisco Certified Network Associate- Mega Lab</h1>



<h2>Description</h2>
Demonstrated competency with CLI configurations on Cisco IOS through applying configurations that meet enterprise and design requirements.

Base level:

Configured layer 2 network segmentation with emphasis on forwarding optimization, applied layer 3 static and dynamic address assignments through proper subnetting, and ensured secure remote access.
(VLAN, Etherchannel, Trunking, VTP, RSTP, HSRP) (IPv4 & IPv6, OSPF, DHCP) (SSH access)

Network Services:
Ensured consistent centralized date/time and logging through server implementations, conducted device updates remotely through establishing FTP services, and centralized wireless architecture to enable seamless scalable access point deployment.
(NTP, Syslog, SNMP, FTP, WLAN)

Security & Compliance:
Mitigate network risk factors for both internal and external threats through type 9 hashed secrets, ACLs, and layer 2 security features~!
(Encrypted local login, ACLs, Port-Security, DHCP Snooping, Dynamic ARP Inspection)
<br />



<h2>Environments Used </h2>

- Cisco Packet Tracer 9.0.1

<h2>Lab walk-through:</h2>

<p align="center">
Initial Topology: <br/>
<img width="837" height="597" alt="Screenshot 2026-06-09 113230" src="https://github.com/user-attachments/assets/db14b718-af4b-4cec-b412-4c8779af1d4c" />
<br />
<br />
Begin spanning tree migration (RSTP to MST):  <br/>
<img width="625" height="585" alt="Screenshot 2026-06-09 120116" src="https://github.com/user-attachments/assets/a2f6b811-2242-496e-80e1-45362d9bc2e1" />
<br />
<br />
Observed P2P disputes as new MST topology converges: <br/>
<img width="882" height="521" alt="Screenshot 2026-06-09 121340" src="https://github.com/user-attachments/assets/8749a500-9ae0-4c19-9fb0-507dc5355120" />
<br />
<br />
Troubleshooting sub-optimal root port pathing:  <br/>
<img width="763" height="504" alt="Screenshot 2026-06-09 123126" src="https://github.com/user-attachments/assets/4dc77c5b-5a7b-4aa7-951d-32572c44cfa9" />
<img width="831" height="296" alt="Screenshot 2026-06-09 123207" src="https://github.com/user-attachments/assets/95e4dc14-5bb3-4ec4-89e0-b5fe46f7dc0c" />
<br />

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
