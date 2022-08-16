

### Task 2

---

This task will provide the instructions to build the Lab Profile including adding the VM Profile.

 - From the main Skillable Studio menu bar select **Dashboard**
 - From the new Skillable Studio Dashboard clieck [**Create New**](images/003.jpg)
 
 - From the top right of the Template Gallery click **+ Create Custom Environment**
 
 - Complete the Lab Profile with the following settings:
 
#### Basic Information:
 
 > - Number: ++@lab.Variable(initials)++
 > - Name: ++LP-Azure-VM++    
 > - Series: LDW-AUG22    
 > - Virtualization Platform: *Azure*    
 
#### Cloud

> - Cloud Platform: Azure    
> - Subscription Pool: Career RockIT (Skillable)    
> - Datacenter Availability: East US    
> - Resource Groups: **+ Add Resource Group**    
> - Permission: **+ Add Permission**    
>     - User1 Role: Reader    

#### Network 

> - Click **+ Add Network** to add a network adapter.  No requirements to change anything else but change the name to ++Enterprise LAN++
> - If you wish to change the IP Address range you can also do that for example ++172.31.0.0/24++ or ++192.168.100.0/26++ as examples.

#### Virtual Machines

> - Click **+ Add Virtual Machine**
> - Press **Search**
> - Select the virtual machine @lab.Variable(initials)-Azure-VM from the list.  Click **OK**
> - Network Adapter 1: Set to **Enterprise LAN**
> - Cloud Resource Group: *Resource Group1*

Click **Save** to save the Lab Profile

Press **Next** to continue
 
