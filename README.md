<h2>How To Create An Azure Resource Group And Storage Account<h2>
<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Azure - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of an Azure resource group and storage account.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

1) Create a free subscription: https://azure.microsoft.com/en-us/free/
2) Log into the Azure Portal: https://portal.azure.com
3) Verify you have the proper role assignments (Owner or Contributor) for your subscription.
4) Confirm billing is active and linked to your subscription to avoid deployment errors.
5) Ensure you have a supported web browser (Edge, Chrome, or Firefox) with reliable internet access.
6) Decide on a resource naming convention to keep your environment consistent.
7) Prepare a unique Resource Group name (e.g., Demo-Project-Marcus).
8) Choose the Azure region closest to you or required by your project.
9) Decide if you want to apply optional tags (e.g., Owner: youremail@domain.com) for resource organization.
10) Prepare a globally unique Storage Account name (3–24 lowercase characters, numbers allowed).
11) Decide on the performance tier (Standard or Premium) for your Storage Account.
12) Select the redundancy option (LRS, ZRS, or GRS) based on cost vs. durability.
13) Review networking and security settings to determine if you’ll keep defaults or customize them.

<h2>Installation Steps</h2>

<p>

<h2>Part 1: Create a Resource Group</h2>

<img width="1100" height="213" alt="sc1" src="https://github.com/user-attachments/assets/020eda54-a535-4830-b69a-82ace6935679" />

</p>
<p>
Step 1: Open the Azure Portal

In your browser, go to https://portal.azure.com and log in using your Microsoft Azure account.
Once signed in, you’ll see the Azure Portal dashboard with service icons such as Virtual Machines, Resource Groups, and Storage Accounts.
</p>
<br />
column-gap
<p>
<img width="647" height="224" alt="Sc2" src="https://github.com/user-attachments/assets/1157626b-a411-4cf4-8e4c-0ba5cd0dae32" />
</p>
<p>
Step 2: Open the Resource Groups section
  
From the dashboard, click Resource groups to manage existing groups or create a new one.
You’ll be taken to the Resource Groups page where you can view all groups linked to your subscription.

Step 3: Start creating a new Resource Group

On the Resource Groups page, click + Create at the top.
This opens the Resource Group creation wizard.
</p>
<br />

<p>
<img width="742" height="355" alt="Sc3" src="https://github.com/user-attachments/assets/e41b409d-b0fe-4cdd-898a-784c709a6507" />
</p>
<p>
Step 4: Fill in the Resource Group details
  
Subscription: Select your active subscription (e.g., Azure subscription 1).
Resource group name: Enter a unique name such as Demo-Project-Marcus.
Region: Choose the closest or required region (e.g., (US) East US).
</p>
<br />

<p>
<img width="724" height="356" alt="Sc4" src="https://github.com/user-attachments/assets/530b2c02-96f7-4521-b97f-e71b398edd85" />
</p>

</p>
Step 5: Add optional tags

Click the Tags tab.
Tags are metadata used for organizing resources. Example: Add Owner as the name and your email address as the value
</p>
<br />

<p>
<img width="431" height="398" alt="Sc5" src="https://github.com/user-attachments/assets/326d14c3-6f84-48c9-b718-4c380d1148ba" />
</p>
<p>
Step 6: Review and create the Resource Group
  
Go to the Review + create tab.
Confirm all details: subscription, Resource Group name, region, and tags.
If everything is correct, click Create.
</p>
<br />

<h2>Part 2: Create a Storage Account</h2>

<p>
<img width="546" height="195" alt="Sc6" src="https://github.com/user-attachments/assets/da58f6fc-b609-4714-9e7a-0a3a07adf5d4" />
</p>
<p>
Step 7: Search for Storage Accounts
  
In the search bar at the top of the Azure Portal, type storage accounts.
Select Storage accounts from the results.
</p>
<br />

<p>
<img width="1121" height="174" alt="Sc7" src="https://github.com/user-attachments/assets/85dd416b-5b14-412d-8d23-f2017d19e6aa" />
</p>
<p>
Step 8: Start creating a new Storage Account

In the Storage center, click + Create to launch the storage account wizard.
</p>
<br />

<p>
 <img width="742" height="684" alt="Sc8" src="https://github.com/user-attachments/assets/3dc003b4-a376-4d9e-b10e-d110e4732dc1" />
 </p>
 <p>
 Step 9: Choose subscription and resource group

Under Project details, confirm your subscription.
Select the Resource Group you just created (Demo-Project-Marcus)
</p>
<br />

<p>
<img width="743" height="373" alt="Sc9" src="https://github.com/user-attachments/assets/ef787e09-95d0-4fa0-ade3-afe10070131f" />
</p>
<p>
Step 10: Configure instance details

Enter a globally unique Storage account name (e.g., marcus15storageaccount).
Select the same Region as your Resource Group (e.g., (US) East US).
Performance: Select Standard (recommended for most cases).
Redundancy: Choose Locally-redundant storage (LRS) if cost is more important than durability.
</p>
<br />

<p>
 <img width="733" height="869" alt="Sc10" src="https://github.com/user-attachments/assets/fc630204-5a0e-4240-97f4-8c5c59d36aa5" />
 </p>
 <p>
   Step 11: Review advanced and security settings

Leave advanced options (SFTP, hierarchical namespace, etc.) disabled unless required.
Security defaults:
Secure transfer = Enabled
Blob anonymous access = Disabled
Allow storage account key access = Enabled

Step 12: Review and create the Storage Account

Go to the Review + create tab.
Review all details: subscription, Resource Group, name, region, redundancy, and security.
If everything looks correct, click Create.
 </p>
<br />

<p>
 <img width="1136" height="443" alt="Sc11" src="https://github.com/user-attachments/assets/86539345-e9d9-4835-bbaa-fd5448bc5818" />
 </p>
 <p>
 Step 13: Confirm deployment completion

After a short time, Azure will confirm your deployment.
You’ll see a green check mark and the message Your deployment is complete.
Click Go to resource to open the new Storage Account.
 </p>
<br />

<p>
 <img width="1534" height="878" alt="Sc12" src="https://github.com/user-attachments/assets/0b2e3238-9b7b-44ff-87fa-f972ca865d4a" />
</p>
<p>
  Step 14: View your Storage Account overview

You’ll be redirected to the Storage Account overview page.
Here, you can see all essential details such as:
Resource group (Demo-Project-Marcus)
Location (East US)
Replication (LRS)
Performance (Standard)
On the left-hand menu, you can also manage containers, file shares, tables, and security.
</p>
<br />



