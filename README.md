<p align="center">
<img src=https://i.imgur.com/wWxNb0n.png/>
</p>

<h1>Linux Ubuntu Virtual Machine Configuration in Azure</h1>
This project tutorial outlines the set up and configuration of a Linux Ubuntu Virtual Machine inside of Microsoft Azure.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop


<h2>Operating Systems Used </h2>

- Linux/Ubuntu</b> 

<h2>List of Prerequisites</h2>

- Computer Desktop/Laptop
- Azure Account
- Remote Desktop
- Wifi Connection

<h2>Configuration Steps</h2>
Step 1: Go to the Azure Virtual Machine homepage and press create azure virtual machine in dropdown menu.
<p>
<img src="https://i.imgur.com/ESYlyEa.png"/>
</p>
<p>

<br />
Step 2: In the resource group box select PANlab_RG.
<p>
<img src="https://i.imgur.com/Gd1Gwai.png"/>
</p>
<p>

</p>
<br />
Step 3: For the virtual machine name call it LinuxUbuntu. Choose a region thats appropiate to your location.
<p>
<img src="https://i.imgur.com/B2iUSfh.png"/>
</p>
<p>

</p>
<br />
Step 4: Choose an availability zone.
<p>
<img src="https://i.imgur.com/mAseLt5.png"/>
</p>
<p>

</p>
<br />
Step 5: For image choose Ubuntu Server 22.04 LTS - x64 Gen2 and for size use the standard_D4s_V3 - 4 vcpus, 16 GiB memory
<p>
<img src="https://i.imgur.com/Ti9fAZd.png"/>
</p>
<p>
Step 6: Next, under Administrator Account select the password option.
</p>
<br />

<p>
<img src="https://i.imgur.com/sa1yPQC.png"/>
</p>
<p>

</p>
<br />
Step 7: Create a usename and password in order to proceed with the virtual machine creation. Press Next:Disks, then Next:Networking on the next page.
<p>
<img src="https://i.imgur.com/YIctvqS.png"/>
</p>
<p>

</p>
<br />
Step 8:On the networking page select the virtual network that was created for the windows10-vm in the previous project tutorial. Then press review and create.
<p>
<img src="https://i.imgur.com/WyFzAmG.png"/>
</p>
<p>

</p>
<br />
Step 9:  Validation banner should come up. Press Create.
<p>
<p>
<img src="https://i.imgur.com/W2BMWGf.png"/>
</p>
<p>

</p>
<br />
Step 10: Deployment should be in progress. This step usually takes a minute or two to process.
<p>
<img src="https://i.imgur.com/qZcadiA.png"/>
</p>
<p>

</p>
<br />
Step 11: Deployment should be completed.
<p>
<img src="https://i.imgur.com/M44pKAz.png"/>
</p>
<p>

</p>
<br />
Step 12: Next go onto the virtual machines page.
<p>
<img src="https://i.imgur.com/a78y0Eu.png"/>
</p>
<p>

</p>
<br />
Step 13: You will see here both the windows10-vm and linux ubuntu virtual machines have been created and that both of them share the same resource group.
<p>
<img src="https://i.imgur.com/FmOPetv.png"/>
</p>
<p>

</p>
<br />
Step 14: If you look down at both of these images closely you will observe that both of these virtual machines share the same virtual network as well, that being lab2-vnet.
<p>
<img src="https://i.imgur.com/CmVNxiC.png"/>
 
<img src="https://i.imgur.com/0ZPgKqp.png"/> 

</p>
<p>

</p>
<br />















