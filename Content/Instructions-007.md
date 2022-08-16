

### Task 2

---

This task will provide the instructions to build the Lab Profile including adding the VM Profile.

 - From the main Skillable Studio menu bar select **Dashboard**
 - From the new Skillable Studio Dashboard **Create**
 [IMAGE](images/003.jpg)
 
 - From the top right of the Template Gallery click **+ Create Custom Environment**
 
 - Complete the Lab Profile with the following settings:
 
#### Basic Information:
 
 > - Number: ++@lab.Variable(initials)++
 > - Name: ++LP-AWS-VM++    
 > - Series: LDW-AUG22    
 > - Virtualization Platform: *AWS*    
 
#### Cloud

> - Cloud Platform: AWS    
> - Subscription Pool: Career RockIT (Skillable)    
> - Datacenter Availability: US East (N. Virginia)    
> - Remove User1 (**X** on the right hand side)
> - Resource Groups: **+ Add Stack Deployment**    
  

#### Virtual Machines

> - Click **+ Add Virtual Machine**
> - Press **Search**
> - Select the virtual machine @lab.Variable(initials)-AWS-VM from the list.  Click **OK**
> - Cloud Resource Group: *Stack1*

Click **Save** to save the Lab Profile

Press **Next** to continue
 
