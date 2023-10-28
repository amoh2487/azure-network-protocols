<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Resource Groups)
- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

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

![image](https://github.com/amoh2487/azure-network-protocols/assets/148664179/eb03f4e7-0ca4-450b-ad2e-6a5cb351055c)

  
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
