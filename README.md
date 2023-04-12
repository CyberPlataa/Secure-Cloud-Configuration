<h1>Secure Cloud Configurations Pt. 3</h1>

 ### [Azure Honeynet Lab](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
Project consists of going through the created virtual network and adjusting keyvault/storage/networks to be in compliance with NIST 800-53 SC7 Standards.


<h2>Languages and Utilities Used</h2>
Powershell, Windows 10

<h2>Environments Used </h2>

- <b>Microsoft Azure</b> 

<h3>Network Topology Before Applying NST 800-53 SC7 Standards</h3>
<a href="https://imgur.com/0Pa4xhV"><img src="https://i.imgur.com/0Pa4xhV.png" title="source: imgur.com" /></a>


<h2>Configuration walk-through:</h2>

<p align="center">
<h3>Go to networking of keyvaults/storage accounts sections and use these settings for private endpoint connection</h3> <br/>
<a href="https://imgur.com/SMC6Wgc"><img src="https://i.imgur.com/SMC6Wgc.png" title="source: imgur.com" /></a>
<br />
<br />

<h3><a href="https://imgur.com/0Wb0FtD"><img src="https://i.imgur.com/0Wb0FtD.png" title="source: imgur.com" /></a></h3>


<h3>Observe the now secure subnet of the keyvault: Computers outside of the subnet should not be able to access it. AS in the case of using my PC to connect</h3>  <br/>
<a href="https://imgur.com/0vz7Cso"><img src="https://i.imgur.com/0vz7Cso.png?1" title="source: imgur.com" /></a>
</p>


<a href="https://imgur.com/NnGG13V"><img src="https://i.imgur.com/NnGG13V.png" title="source: imgur.com" /></a>


<h3>Network Topology With Application of NST 800-53 SC7 Standards</h3>
<a href="https://imgur.com/XvzmsGz"><img src="https://i.imgur.com/XvzmsGz.png" title="source: imgur.com" /></a>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
