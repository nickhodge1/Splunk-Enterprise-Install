<h1>Splunk Enterprise Install - Windows</h1>


<h2>Description</h2>
This project demonstrates installing Splunk Enterprise on Windows devices (specifically Windows 11 Pro & Windows Server 2022 Standard). This install also includes configuring Windows firewall settings to work with Splunk Enterprise, as well as installing the Splunk forwarder to receive all Windows logs.
<br>
<br>
- <b>Install and Configure the Splunk Enterprise Application</b>
<br>
- <b>Configure a Splunk Client</b>
<br>
- <b>Collect Logs using Splunk Enterprise</b>
<br>
<br>
Existing domain account used for Splunk installation. Account for Splunk Enterprise created during installation.

<h2>Application Installed</h2>

- <b>Splunk Enterprise</b> 

<h2>Environments Used </h2>

- <b>Windows Server 2022 Standard</b> (21H2)
- <b>Windows 11 Pro</b> (21H2)

<h2>Program Screenshots:</h2>

<p align="center">
<b>Screenshot of downloads folder - Splunk Enterprise Installer (Windows 11 Pro device):</b> <br/>
<img src="https://imgur.com/ZkyqhAb.png" height="80%" width="80%" alt="Splunk Enterprise Install"/>
<br />
<br />
<b>Splunk Enterprise installation options - customize options (domain account) Windows 11 Pro device:</b> <br/>
<img src="https://imgur.com/yKYWPFM.png" height="80%" width="80%" alt="Splunk Enterprise Install"/>
<br />
<br />
<b>Splunk Install Progress (Windows 11 Pro device):</b> <br/>
<img src="https://imgur.com/8F34451.png" height="80%" width="80%" alt="Splunk Enterprise Install"/>
<br />
<br />
<b>Splunk Enterprise Successful Installation (Windows 11 Pro device):</b>  <br/>
<img src="https://imgur.com/tivZIOj.png" height="80%" width="80%" alt="Splunk Enterprise Install"/>
<br />
<br />
<b>Splunk Enterprise Dashboard - Microsoft Edge Browser (127.0.0.1:8000) - Windows 11 Pro device):</b>  <br/>
<img src="https://imgur.com/fQ83RiZ.png" height="80%" width="80%" alt="Splunk Enterprise Install"/>
<br />
<br />
<b>Addition of new receiving port for Splunk - port 9997 (Windows 11 Pro device):</b>  <br/>
<img src="https://imgur.com/NBTmObu.png" height="80%" width="80%" alt="Splunk Enterprise Install"/>
<br />
<br />
<b>Configure Windows Firewall - Advanced Settings (Windows 11 Pro device):</b>  <br/>
<img src="https://imgur.com/eX1LA6y.png" height="80%" width="80%" alt="Splunk Enterprise Install"/>
<br />
<br />
<b>Configure new inbound firewall rule (Windows 11 Pro device):</b>  <br/>
<img src="https://imgur.com/7Zyvw2z.png" height="80%" width="80%" alt="Splunk Enterprise Install"/>
<br />
<br />
<b>New inbound firewall rule titled "Splunk" can be seen in the rules list (Windows 11 Pro device):</b>  <br/>
<img src="https://imgur.com/Wa82WFY.png" height="80%" width="80%" alt="Splunk Enterprise Install"/>
<br />
<br />
<b>Splunk universal forwarder install - domain account (Windows Server 2022 Standard):</b>  <br/>
<img src="https://imgur.com/M1MVgU3.png" height="80%" width="80%" alt="Splunk Enterprise Install"/>
<br />
<br />
<b>Splunk universal forwarder - Windows event logs (Windows Server 2022 Standard):</b>  <br/>
<img src="https://imgur.com/qnDRTCe.png" height="80%" width="80%" alt="Splunk Enterprise Install"/>
<br />
<br />
<b>(Windows Server 2022 Standard) Splunk universal forwarder - deployment server configuration (192.168.0.3:8089 - Windows 11 Pro device):</b>  <br/>
<img src="https://imgur.com/hyOsIJr.png" height="80%" width="80%" alt="Splunk Enterprise Install"/>
<br />
<br />
<b>(Windows Server 2022 Standard) Splunk universal forwarder - receiving indexer configuration (192.168.0.3:9997 - Windows 11 Pro device):</b>  <br/>
<img src="https://imgur.com/AGQHr4w.png" height="80%" width="80%" alt="Splunk Enterprise Install"/>
<br />
<br />
<b>Splunk universal forwarder installation success (Windows Server 2022 Standard):</b>  <br/>
<img src="https://imgur.com/Q3XHbqH.png" height="80%" width="80%" alt="Splunk Enterprise Install"/>
<br />
<br />
<b>Splunk Enterprise dashboard (Windows 11 Pro device) - add data (explore Splunk Enterprise pane):</b>  <br/>
<img src="https://imgur.com/dr5CuEj.png" height="80%" width="80%" alt="Splunk Enterprise Install"/>
<br />
<br />
<b>Scroll down in explore Splunk Enterprise pane to "forward data from a Splunk forwarder (Windows 11 Pro device):</b>  <br/>
<img src="https://imgur.com/Pif8CMn.png" height="80%" width="80%" alt="Splunk Enterprise Install"/>
<br />
<br />
<b>(Windows 11 Pro device) enter server class name (in this case "ACIDMO1 Logs". Next choose the appropriate forwarder (WINDOWS ACIDM01 - Windows Server 2022 Standard):</b>  <br/>
<img src="https://imgur.com/cbumvRG.png" height="80%" width="80%" alt="Splunk Enterprise Install"/>
<br />
<br />
<b>Click on "collect local event logs from this machine" (Windows logs). This will be the Windows logs from the server ACIDM01:</b>  <br/>
<img src="https://imgur.com/WYhNT0X.png" height="80%" width="80%" alt="Splunk Enterprise Install"/>
<br />
<br />
<b>Review the forwarder selected and log data selected before submitting:</b>  <br/>
<img src="https://imgur.com/VJw2kCx.png" height="80%" width="80%" alt="Splunk Enterprise Install"/>
<br />
<br />
<b>Windows log results from server (ACIDM01 - Windows Server 2022 Standard):</b>  <br/>
<img src="https://imgur.com/nFeYztt.png" height="80%" width="80%" alt="Splunk Enterprise Install"/>
<br />
<br />
<b>Additional view of Windows log results from server (ACIDM01 - Windows Server 2022 Standard):</b>  <br/>
<img src="https://imgur.com/aaP7TdZ.png" height="80%" width="80%" alt="Splunk Enterprise Install"/>
<br />
<br />

