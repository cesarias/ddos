<p align="center">
<img src="https://i.imgur.com/eStWstA.png" height="30%" width="30%" alt="Sentinel logo"/>
</p>

<h1> Azure DDOS Protection </h1>
Azure DDOS protection on a virtual network.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure  
- Remote Desktop
- Breaking Point Cloud


<h2>Operating Systems Used </h2>

- MAC OS / Windows 10(VM)</b> 


<h2> Setting up DDOS Protection Plan </h2>

<p>
<img src="https://i.imgur.com/Y3euG4W.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 After creating a resource group we add the DDOS protection plan to it.  
</p>
<br />

<p>
<img src="https://i.imgur.com/xssxYSG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  DDOS protection plan has deployed. 
</p>
<br />

<p>
<img src="https://i.imgur.com/zn0M50Q.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 Create Virtual Network and enable our DDOS Protection plan with it.  
</p>

<p>
<img src="https://i.imgur.com/45Sn3Qi.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 Created a public IP Address to monitor its metrics.</p>

<p>
<img src="https://i.imgur.com/Ld3AWPd.png" width="80%" alt="Disk Sanitization Steps"/>

<p>
 Setting up diagnostic setting for the public IP Address where it can send data to Log Analytics Workspace.
</p>

<p>
<img src="https://i.imgur.com/M4zBDIW.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 Deployed Analytic workspace .
</p>

<p>
<img src="https://i.imgur.com/yZL1Eoe.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 Create VM and modify it's default IP Address to public IP address created earlier so the DDOS telemetry can be tested . 
</p>

<p>
<img src="https://i.imgur.com/724MKlS.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  Topology of the Virtual Network 
</p>

<p>
<img src="https://i.imgur.com/r7pCXeY.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 Configure DDOS Alerts
</p>

<p>
<img src="https://i.imgur.com/C2LOfac.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  Used breakingpoint.cloud to simulate a DDOS attack.
</p>                                         
                                                                                    
 <p>
<img src="https://i.imgur.com/VXGGifg.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 DDOS attack was simulated and an alert was created .
                                                                                    
 Thank you for viewing                                                                                   
</p>                                                                                   
                                                                                
 
<br />
