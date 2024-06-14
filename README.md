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
- Select "Get Started"
- Follow the prompt to create the account 
     - You will need to put in your credit card information, but you will get $200 worth of Azure credit and will have 30 days to use those credits. You will not be charged until then
- Finish the prompt, click Go to Azure Portal, and you are ready to start with Azure!
     - You may also go to [portal.azure.com](https://www.portal.azure.com) to start


![image](https://github.com/ShawnIT-J/resource-groups-and-vms/assets/172000204/eea3cf10-bdbc-4efe-bc1c-553f60f23d83)


<h3>Step 2: Create a Resource Group</h3>

- Go to the search bar at the top and search "resource group"
- Select "Create Resource Group"
- You will need to name the resource group and select the region 
- Select "Review + Create" on the lower left
    - For this example, we will be using RgLab1 for the name and (US) East US for the region (Which ever region you are in the US is fine as well)


![image](https://github.com/ShawnIT-J/resource-groups-and-vms/assets/172000204/e685fdb8-f509-4372-a5fa-7093c28c7b01)

![image](https://github.com/ShawnIT-J/resource-groups-and-vms/assets/172000204/05b944a3-22b7-420b-837c-d3be7a255165)




<h3>Step 4: Create a Virtual Machine</h3>
     
- Go to the search bar and search "virtual machine"
- Select "Create", then select "Azure Virtual Machine"
- You will need to select the same resource group, the same region, and create a name for the virtual machine
    - For thise example, we will name the virtual machine "vm1"


![image](https://github.com/ShawnIT-J/resource-groups-and-vms/assets/172000204/b0f9f461-6aa1-4144-8204-138c65019f4f)

![image](https://github.com/ShawnIT-J/resource-groups-and-vms/assets/172000204/de90b71c-8d8d-453a-9fad-2512315de752)







* You will then need to select the image and size
    - For image we will use Windows 10 Pro
    - For size Standard_E2s_v3 - 2 vcpus, 16 GiB memory (VM size is to support the workload that you want to run. The size that you choose then determines factors such as processing power, memory, and storage capacity.)
* You will then need to make a username and password
    - For username, we will use "labuser"
    - Create your own password
    - Make sure to note what username and password you used
* Click the box under licensing and finally click "Review + Create" (Note- it will take some time for the virtual machine to set up)




![image](https://github.com/ShawnIT-J/resource-groups-and-vms/assets/172000204/56943989-101a-4a60-bdf3-925ff840c3ba)
![image](https://github.com/ShawnIT-J/resource-groups-and-vms/assets/172000204/12659cff-4387-4f21-a223-c2f386eb4d6c)


     

<h3>Step 5: Connect to the Virtual Machine</h3>

- First, you will need to find the public IP address of your virtual machine
   - Select the virtual machine we created and the public IP address will be on the right-hand side of the screen
   - Copy the public IP address


![image](https://github.com/ShawnIT-J/resource-groups-and-vms/assets/172000204/55de9972-f9c6-469a-8511-b33777c20fb3)

![image](https://github.com/ShawnIT-J/resource-groups-and-vms/assets/172000204/0f0a109f-17f8-4714-a6a0-4351f7934f95)



   
* Windows Users
     - Open and use Remote Desktop
     - Paste the public IP Address and select Connect 
     - Enter the username and password from step 4 (You will have to sign in as a differnet user to access the virtual machine)
     - Select "Ok"
  


![image](https://github.com/ShawnIT-J/resource-groups-and-vms/assets/172000204/248bcd24-9a32-4a4e-a218-027a56b3b141)





🎉Congratulations! You have created your first virtual machine within Azure!🎉

![image](https://github.com/ShawnIT-J/resource-groups-and-vms/assets/172000204/89132f3e-6537-41f8-8490-8b77b6eb7eaf)



<h3>Tip</h3>

-  If you want to save your free $200 credits, make sure you delete ALL your resources and resource groups after finishing!    
  
