# Vitual Private Network (VPN)
<p align="center">
<img src="https://github.com/user-attachments/assets/148ea37f-12b6-4db2-9a6d-dd2d9df49395" height="80%" width="80%" alt="vpn"/>
</p>

<h1>VPN - Prerequisites and Installation</h1>
This section examines Virtual Private Networks (VPNs) and how they help secure remote connections within a network infrastructure<br />

<h2>Environments and Technologies Used</h2>

- A VPN (Proton VPN)
- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>STEPS INCLUDED</h2>

- Locate Local IP
- Setting Up VM Using Azure
- Locating IP Through VM 
- Connecting to VPN Through VM
- Locating IP Through VPN 

<h2>Step 1: Find your personal IP address</h2>
<b>By visiting 'www.whatismyipaddress.com,' which will display your local IP. We will use this information later."</b>
<img src="https://i.imgur.com/QxjBt7w.png" width="600" alt="VPN"/>
<p>Next, we will configure our virtual machines on Azure</p>
<br />


<h2>Step 2: Go to Azure to setup our virtual machine</h2>
<b>Create an account, create a resource group and search virtual machine or type vm</b>
<img src="https://i.imgur.com/FOsRkNY.png" width="600" alt="VPN"/>
<br />


<h2>Step 3: Log into the VM and Find IP Address</h2>
<b>Once the virtual machine is create, we will connect using "Remote Desktop Connection" and find the IP address on www.whatismyipaddress.com</b>
<img src="https://i.imgur.com/vWb2vve.png" width="600" alt="VPN"/>
<p>
  When we find the IP address for this VM through www.whatismyipaddress.com it matches 
  <img src="https://i.imgur.com/oGQsUCL.png" width="600" alt="VPN"/>
</p>
<br />


<h2>Step 4: Connecting to VPN (Proton VPN)</h2>
<b>On your local pc, go to protonvpn.com and create a free account. When you are logged into your account, copy the URL(protonvpn.com) and then paste it on the virtual machine browser(</b>
<img src="https://i.imgur.com/xYlaPfC.png" width="600" alt="VPN"/>
<p>
  <ul>
    <li>Login Proton VPN in VM</li>
    <li>Download and install ProtonVPN from within the Azure VM</li>
    <img src="https://i.imgur.com/L8FaXmU.png" width="600" alt="VPN"/>
  </ul>
  - On the left-side of the VPN you're able to select any country you want your VPN to be.
  <img src="https://i.imgur.com/sJUwgNh.png" width="600" alt="VPN"/>
</p>
<p>- The image below shows the VPN being connected and having another IP address</p>
<img src="https://i.imgur.com/uDawnN1.png" width="600" alt="VPN"/>
<br />


<h2>Locating IP through VPN</h2>
<b>Next lets locate the IP through Proton VPN</b>
<p>- We will check the IP address again now that we have connected to the VPN. Go to www.whatismyipaddress.com, it will display a different IP address.</p>
<b>Original VM IP address</b>
<img src="https://i.imgur.com/oGQsUCL.png" width="600" alt="VPN"/>
<b>VM IP address through VPN</b>
<img src="https://i.imgur.com/x8uovgs.png" width="600" alt="VPN"/>
<br />
<p>
  Ultimately, from our local computer with its own IP address(Pennsylvannia), we created a virtual machine on Azure, which was assigned its own IP address (located in Virginia). Within that virtual machine, we then used a VPN to change its IP address location to Texas.
</p>
<br />
