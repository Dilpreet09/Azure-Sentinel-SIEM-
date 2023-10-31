<h1>Microsoft Azure Sentinel (SIEM)</h1>

<h2>Description</h2>
When I was preparing for CompTIA Security+, I delved into the concepts of honeypots and the utilization of SIEM tools. Despite grasping these ideas theoretically, I lacked the opportunity for practical, hands-on experience. However, I took the initiative to implement Microsoft Azure's Sentinel in order to produce real-time logs for my vulnerable VM host, essentially setting up a honeypot environment.
<br />


<h2>Language Used</h2>
- <b>PowerShell: Extract RDP failed logon logs from Windows Event Viewer</b> 


<h2>Utilitie Used</h2>
- <b>ipgeolocation.io: IP Address to Geolocation API</b>

<h2>Reference</h2>
- https://youtu.be/RoZeVbbZ0o0?si=8QuRoo-emEhjQEok

<h2>Program walk-through:</h2>

<p align="center">
Attacks from Netherlands coming in and logs being generated in Real Time<br/>
<img src="https://i.imgur.com/7U4YRu6.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Custom logs being output with geodata<br/>
<img src="https://i.imgur.com/J0vct7z.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
World map of incoming attacks after few hours (built custom logs including geodata) <br/>
<img src="https://i.imgur.com/q4kjXom.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Azure's Sentinel dashboard with insightful overview of all the intrusion attempts <br/>
<img src="https://i.imgur.com/gYAxuEX.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
