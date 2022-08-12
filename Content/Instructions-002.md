## Summary

### Task 1

---

This task will provide the instructions to build the VM Profile.  Items in *italics* are parts that are different from settings you might have traditionally used when building VM profiles for Hyper-V or ESX.

 - From the main Skillable Studio menu bar select **Admin**
 - From the Admin page select **Create Virtual Machine Profile**
 [IMAGE](images/001.jpg)
 
 - Complete the Virtual Machine Profile with the following settings:
 
 #### Basic Information:
 
 > Name: ++@lab.Variable(initials)-Azure-VM++    
 > Series: LDW-AUG22    
 > Platform: *Azure*    
 > *Machine Type: DS2 v2 (2cores, 7GB memory)*    
 > *Use Image Libray: Selected*    
 > *Machine Image Image Definition: ++Aug_LDW_Windows++*    
 > *Machine Image Image Version: ++1.0.0++*    
 > Username: ++labuser++    
 > Password: ++Pa55w0rd1234++    
 
>[!TIP]If you wish to experiement with the Audio & Clipboard Redirect features please do.

#### Network Adapters

> Click **+ Add Network Adapter** to add a network adapter.  No requirements to change anything else.

>[!KNOWLEDGE] Notice the pages that are missing compared to Hyper-V or ESX VM's
>[!IMAGE](images/002.jpg)

Press **Next** to continue
 
