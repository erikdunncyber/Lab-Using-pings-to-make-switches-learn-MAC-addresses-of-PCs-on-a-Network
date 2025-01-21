<h1>Packet Tracer - Using Pings to Make Switches Learn MAC Addresses of PCs on a Network</h1>

<p align="center">
I created a simple LAN with 4 PCs interconnected between 2 switches: <br/>
<img src="https://i.imgur.com/7JzKopx.png" height="80%" width="80%"/>
<br />
<br />
I'll start by using PC1 to ping PC4. I'll enter "ping 192.168.1.4" into PC1's command prompt to do this: <br/>
<img src="https://i.imgur.com/1FpAtZo.png" height="80%" width="80%"/>
<br />
<br />
Now I'll use PC2 to ping PC3. I'll enter "ping 192.168.1.3" into PC2's command prompt to do this: <br/>
<img src="https://i.imgur.com/d3G31MN.png" height="80%" width="80%"/>
<br />
<br />
To verify if the switches have learned the PCs' MAC addresses, I'll check the MAC address tables of each switch. Starting with switch 1, I'll access the switch's CLI and enter Priveleged Exec mode. Then I'll enter the "show mac address-table" command. The MAC address table for switch 1 shows all 4 MAC addresses for the PCs: <br/>
<img src="https://i.imgur.com/7tKSjo7.png" height="80%" width="80%"/>
<br />
<br /> 
Now I'll verify if switch 2 has learned the PCs' MAC addresses. The MAC address table shows all 4 PCs' MAC addresses: <br/>
<img src="https://i.imgur.com/iCQ3u0D.png" height="80%" width="80%"/>
<br />
<br /> 
</p>

