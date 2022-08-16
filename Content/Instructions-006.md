### Task 1

---

This task will provide the instructions to build the VM Profile.  Items in *italics* are parts that are different from settings you might have traditionally used when building VM profiles for Hyper-V or ESX.

 - From the main Skillable Studio menu bar select **Admin**
 - From the Admin page select **Create Virtual Machine Profile**
 [Create VM image](images/001.jpg)
 
 - Complete the Virtual Machine Profile with the following settings:
 
 #### Basic Information:
 
 > - Name: ++@lab.Variable(initials)-AWS-VM++    
 > - Series: LDW-AUG22    
 > - Platform: *AWS*    
 > - *Machine Type: t2.medium (2 Cores, 4GB Memory)*    
 > - *Machine Image Image Name: ++Windows-Server-2019-With-Apps++*    
 > - *Location/Region: US East (Virgina)*
 > - *Machine Owner Account: ++812627450842++*    
 > - Username: ++LabUser++    
 > - Password: ++Pa55w0rd!++    
 
>[!TIP]The image name was set when creating the AMI as shown in the video.

>[!KNOWLEDGE] Notice the pages that are missing compared to Hyper-V or ESX VM's    
>![Hyper-V/ESX Lab Profile Example](images/004.jpg)

Press **Next** to continue
 
