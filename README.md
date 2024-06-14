<p align="center">
<img src="https://i.imgur.com/4wqxHID.png" height="40%" width="60%" alt="Microsoft Azure Logo"/>
</p>

<h1>Microsoft Azure</h1>
Azure is a cloud computing platform and an online portal that allows you to access and manage cloud services and resources provided by Microsoft. To get access to these resources and services, all you need to have is an active internet connection and the ability to connect to the Azure portal. This guide will demonstrate how to create an Azure account and create a virtual machine.

<h2>Requirements</h2>

- Computer with Internet Connection
- Credit Card (Required for free Azure credits)

<h2>Configuration Steps</h2>


<h3>Step 1: Create an Azure Account</h3>


Create an Azure account [here](https://azure.microsoft.com/en-us/free/).
- Select Start Free
- Follow the prompt to create the account 
     - You will need to put in your credit card information, but you will get $200 worth of Azure credit and will have 30 days to use those credits. You will not be charged until then
- Finish the prompt, click Go to Azure Portal, and you are ready to start with Azure!
     - You may also go to [portal.azure.com](https://www.portal.azure.com) to start


![image](https://github.com/ShawnIT-J/resource-groups-and-vms/assets/172000204/eea3cf10-bdbc-4efe-bc1c-553f60f23d83)


<h3>Step 2: Create a Resource Group</h3>

- Go to the search bar at the top and search "resource group"
- Select Create Resource Group
- You will need to name the resource group and select the region 
- Select Review + Create on the lower left
    - For this example, we will be using RgLab1 for the name and (US) East US for the region (Which ever region you are in the US is fine as well)

![image](https://github.com/ShawnIT-J/resource-groups-and-vms/assets/172000204/cecd4f28-564c-43eb-a091-2e72f1644902)
![image](https://github.com/ShawnIT-J/resource-groups-and-vms/assets/172000204/a90cf9aa-d0b8-478e-a633-f7d7424263b8)



<h3>Step 4: Create a Virtual Machine</h3>
     
- Go to the search bar and search "virtual machine"
- Select Create, then select Azure Virtual Machine
- You will need to select the same resource group, the same region, and create a name for the virtual machine
    - For thise example, we will name the virtual machine "vm1"

![image](https://github.com/ShawnIT-J/resource-groups-and-vms/assets/172000204/c7426a66-bc8b-4cee-9f89-017e6bbb04c1)





* You will then need to select the image and size
    - For image we will use Windows 10 Pro
    - For size Standard_E2s_v3 - 2 vcpus, 16 GiB memory (VM size is to support the workload that you want to run. The size that you choose then determines factors such as processing power, memory, and storage capacity.)
* You will then need to make a username and password
    - For username, we will use "labuser"
    - Create your own password
    - Make sure to note what username and password you used
* Click the box under licensing and finally click Review + Create




![image](https://github.com/ShawnIT-J/resource-groups-and-vms/assets/172000204/56943989-101a-4a60-bdf3-925ff840c3ba)
![image](https://github.com/ShawnIT-J/resource-groups-and-vms/assets/172000204/12659cff-4387-4f21-a223-c2f386eb4d6c)


     

<h3>Step 5: Connect to the Virtual Machine</h3>

- First, you will need to find the public IP address of your virtual machine
   - Select the virtual machine we created and the public IP address will be on the right-hand side of the screen
   - Copy the public IP address

<p align="center">
<img src="https://i.imgur.com/T4Oc2RX.png" height="80%" width="80%" alt="Azure Free Account"/>

* Mac Users 
   - Download Microsoft Remote Desktop
   - Open the application and click Add PC
   - Paste the public IP address and select Add
   - Double-click on the virtual machine and enter the username and password from step 4
   - Select Continue
   
* Windows Users
     - Open and use Remote Desktop
     - Paste the public IP Address and select Connect
     - Enter the username and password from step 4
     - Select OK
  
     
     
 <p align="center">
<img src="https://i.imgur.com/14pPOdv.png" height="70%" width="70%" alt="Azure Free Account"/> <img src="https://i.imgur.com/Og3LKyd.png" height="70%" width="70%" alt="Azure Free Services"/>
</p>





🎉Congratulations! You have created your first virtual machine within Azure!🎉

<p align="center">
<img src="https://i.imgur.com/rEBpL8Y.png" height="80%" width="80%" alt="Azure Free Account"/>

<h3>Tip</h3>

-  If you want to save your free $200 credits, make sure you delete ALL your resources and resource groups after finishing!    
  
