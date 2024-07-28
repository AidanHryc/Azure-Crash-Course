<p align="center">
<img src="https://www.xpand-it.com/wp-content/uploads/2021/05/Banner_Azure_1920x500.png"/>
</p>

Azure is very versatile cloud platform that will allow us to do pretty much anything we want when it comes to storage.

*Categories*
<p align="center">
<img src="https://github.com/AidanHryc/Azure-Crash-Course/blob/main/assets/Screenshot_20240728_165651.png"/>
</p>

You can think of Azure resources as a tiered system, where a Tenant would represent an organization/business, and many subscriptions can fit into the tenant.
Subscriptions each are attached to a method of payment i.e. credit card, and they hold resource groups.  Resource groups allow us to logically separate different resources within our subscription
In a given resource group you can put in something like Virtual Machines, Databases, or Storage Accounts.



So, create your account and it will automatically generate you a subscription after you enter billing information

*Empty Tenent*
<p align="center">
<img src="https://github.com/AidanHryc/Azure-Crash-Course/blob/main/assets/Screenshot_20240728_171012.png"/>
</p>

Go to the search bar and type in resource group and click it.

*Resource group starter*
<p align="center">
<img src="https://github.com/AidanHryc/Azure-Crash-Course/blob/main/assets/Screenshot_20240728_171807.png"/>
</p>

Then create a resource group, by picking your subscription, naming it, and giving the location.

*Finished resource group*
<p align="center">
<img src="https://github.com/AidanHryc/Azure-Crash-Course/blob/main/assets/Screenshot_20240728_175210.png"/>
</p>

Now, for this lab we're going to be creating a storage account as one of the resources in our created resource group.
Go to the search bar and type in Storage Account, and start creating one

*Storage account creation*
<p align="center">
<img src="https://github.com/AidanHryc/Azure-Crash-Course/blob/main/assets/Screenshot_20240728_180758.png"/>
</p>

Our subscription & resource group will already be there because they are our only ones.
Name the storage account accordingly, and then select review & create. Every other tab in this case is beyond the scope of this lab and is not neccessary to change from default.
Wait for the service to verify, create, and let it provision the resources. This might take a minute or two.

After it is completed, go into the Storage account, then click the containers tab on the left.  
Contianers are similar to folders within the storage account, if you will. For this lab we will upload a simple .txt file and edit it inside Azure.

So, we will create a container:

*Container creation*
<p align="center">
<img src="https://github.com/AidanHryc/Azure-Crash-Course/blob/main/assets/Screenshot_20240728_181722.png"/>
</p>

Go into the created container.
Now on your desktop, create a text file and put whatever you want in it, save it, and then upload it to the container in Azure.

*Uploaded txt file*
<p align="center">
<img src="https://github.com/AidanHryc/Azure-Crash-Course/blob/main/assets/Screenshot_20240728_182156.png"/>
</p>

Right click on the text file, select the "View/edit" option.
This will bring up the text editor.

*Text editor*
<p align="center">
<img src="https://github.com/AidanHryc/Azure-Crash-Course/blob/main/assets/Screenshot_20240728_182320.png"/>
</p>

Edit it however you want and then save it.

*Edited text*
<p align="center">
<img src="https://github.com/AidanHryc/Azure-Crash-Course/blob/main/assets/Screenshot_20240728_182411.png"/>
</p>

You can download the edited version and see that it worked for yourself.

Storage accounts can be immensely complex and versatile. You can put whole public websites with databases within a single storage account. 
There are countless options you can do with storage accounts, and that is just one form of the many resources in Azure.

Having all of this up costs money, so in order to not waste money when you don't have any of this in use you will need to delete the resource group.
Go to the resource groups list, select the one we made, and click the delete button on the top.
It will ask you to type in the name of the resource group as a form of saying you are aware of the exact resource group you intend to delete.

*Deleting resource group*
<p align="center">
<img src="https://github.com/AidanHryc/Azure-Crash-Course/blob/main/assets/deletion.png"/>
</p>

Deleting may take a few minutes. Azure is deallocating the space from the resource group in the background.
You can keep tabs on the deletion by looking at the notifications, the bell icon, in the top right of the screen.

*Deleted resource group and empty subscription*
<p align="center">
<img src="https://github.com/AidanHryc/Azure-Crash-Course/blob/main/assets/Screenshot_20240728_183726.png"/>
</p>


This concludes the simple lab of creating containers, resource groups, and storage accounts in Azure.















