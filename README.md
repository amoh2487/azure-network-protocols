<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Resource Groups)
- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Wireshark (Protocol Analyzer)
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Various Command-Line Tools

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Create a resource group for your virtual machines
- Step 2
- Step 3
- Step 4

<h2>Actions and Observations</h2>

<p>
</p>
<p>
  
 ![image](https://github.com/amoh2487/azure-network-protocols/assets/148664179/41f2f143-23b4-426a-8bc2-79cf5e336d6a)


The very first step we do here in order to connect both of the virtual machines is to first create a resource group. The reason we use a resourcce group is because it allows us to the users to manage, organize, and minotor the resources we want to create; such as the two virtual networks here and allows us to create relationships for whatever resource we desire to use.
</p>
<br />

<p>
</p>
<p>

![image](https://github.com/amoh2487/azure-network-protocols/assets/148664179/80dc7063-2a9c-40ba-904e-2ceb1276ad93)


The very next step in inspecting traffic between Azure virtual machines is to create the virtual machines themselves. The first step is to click on new virtual machine button on Azure and contuinue from there. The steps on creating both of the virtual machines are going to be similar such as both of the virtual machines need to be in the same resource group and both of the virtual machines need to have the same features such as being consistent for the regions for both of them and or both of the machines need to have the same security type. But the steps that are different for both of them are going to be the virtual machine's names and images since here we used Windows 10 Pro for virtual machine #1 and Ubuntu Server for virtual machine #2. Also, we need to rememeber the username and password we created for both of the virtual machines in order to connect to desktop.
</p>
<br />

<p>
</p>
<p>

![image](https://github.com/amoh2487/azure-network-protocols/assets/148664179/8605926a-86f9-4673-b927-840cf2234814)


The very next step is to connect our virtual machines that we have created earlier to Remote Desktop Connection successfully. To do this, we copy the Public IP Adress from one of the virtual machines and paste it on the Remote Desktop for when it asks about the Public IP Address. After that is done, we then have to put in the username and password we created earlier for our virtual machines; and if the two previous steps were done successfully, we should now connect to Remote Desktop Connection successfully.
</p>
<br />

<p>
</p>
<p>

![image](https://github.com/amoh2487/azure-network-protocols/assets/148664179/f7c35716-4c74-4584-8a61-77f3e4ac4669)


Once we are inside Remote Desktop Connection, we go to the search browser and install Wireshark. The reason for why we install this software is because Wireshark allows us to see what is happening on our network at a micro level. Also, Wireshark allows us the users understand traffic on our networks and diagnose problems if they arise; and this happens by Wireshark capturing and displaying the data that is over our network in real life time.

