# Storage-Containers
## How to Create an Azure Container Storage

# Description

This project displays the straightforward, entry-level creation of a storage account and container in Microsoft Azure Blob (Binary Level Object) Service, utilized in stockpiling unstructured data like documents and images. Containers are inexhaustible, organizational "boxes" nested underneath the Azure Blob Storage service. Storage accounts are considered hierarchical namespaces for the contained data, with each data type attached to an address that includes the account name. Storage accounts with namespaces can even branch out directories that also include blobs. Such remarkable data stewardship is fancied among sizeable companies. 

# Environments Used

    Windows (Windows 11 Pro)
    Microsoft Azure

# Technology/Applications/Services

    Azure Storage Accounts
    Azure Virtual Machines 
    Azure Resource Groups

# Program Walk-Through:

Begin by searching "storage accounts" in the search bar and select "Create": 
![Screenshot 2024-08-02 232858](https://github.com/user-attachments/assets/a58e5783-474b-481e-8747-e6bb81b728ba)


Construct a name and region for the account, ensuring a resource group has been created beforehand. Keep performance on "Standard" and  change redundancy to "Locally-redundant storage." Check the box "Make read access to data available in the event of regional unavailability":
![Screenshot 2024-08-02 232956](https://github.com/user-attachments/assets/93a82370-8dc9-4658-8ff6-168197590757)


In the Advanced section, leave everything as is, confirming the "Minimum TLS version" is defaulted at Version 1.2:
![Screenshot 2024-08-03 125146](https://github.com/user-attachments/assets/473ee8bf-b189-454f-bf2c-423c237536a8)


In the Networking section, ensure everything remains as is:
![Screenshot 2024-08-03 125320](https://github.com/user-attachments/assets/1f7cb857-7524-4c5c-a121-526312809da7)


In the Data Protection section, do not select the box "Enable point-in-time restore for containers" as it won't be necessary in this case:
![Screenshot 2024-08-03 125846](https://github.com/user-attachments/assets/b1de2441-73a9-40a5-aaa5-e9d672983880)


In the Encryption section, do not select the circle "All service types (blobs, files, tables, and queues); we are only using blobs for now:"
![Screenshot 2024-08-03 125950](https://github.com/user-attachments/assets/468013f5-d491-4b8f-9922-116030d6cb17)


In the Tags section, create a Name and Value tag for the storage account to categorize its resources:
![Screenshot 2024-08-03 130112](https://github.com/user-attachments/assets/abb8a68d-c1a8-458f-85d5-3345dcc06447)


Once all the information has been reviewed, select the "Review + create" button to deploy the storage account:
![Screenshot 2024-08-03 170924](https://github.com/user-attachments/assets/109234ac-bcb3-4dc4-b7fd-31a22f007a42)


Once deployment is complete, select the "Go to resource" button to display the storage account's overview. Select "Containers" under the "Data storage" tab:
![Screenshot 2024-08-03 175929](https://github.com/user-attachments/assets/b2092146-1dba-4242-b060-e7f023cfa255)


A container must now be made. Select the "Container" button to create one:
![Screenshot 2024-08-03 182550](https://github.com/user-attachments/assets/238cd4ba-b700-4f42-b3bc-8706d3db54e2)


A pop-up box titled "New container" will appear. Generate a name for the container and select "Create": 
![Screenshot 2024-08-03 185125](https://github.com/user-attachments/assets/e2aeb2be-4515-4948-971d-3510a46a22e8)


A container should be created successfully:
![Screenshot 2024-08-03 185146](https://github.com/user-attachments/assets/87b0b7e0-293e-46fa-9212-90480e02cc1a)


Now, a resource (or blob) must be added. In the new container, select "Upload" and a pop-up titled "Upload blob" will appear:
![Screenshot 2024-08-03 185306](https://github.com/user-attachments/assets/ac1e3fb6-0e13-4370-9c81-907a0bf27255)


Once finding your file of choice, select "Upload":
![Screenshot 2024-08-03 192847](https://github.com/user-attachments/assets/3a8c6cdc-0738-4080-bf3c-66c7b088c873)


The blob should be added successfully:
![Screenshot 2024-08-03 192907](https://github.com/user-attachments/assets/edb8d7ac-c933-4e24-bad5-8a4a73eb4774)


Click on the blob and copy its newly-created URL in the Overview section:
![Screenshot 2024-08-03 192932](https://github.com/user-attachments/assets/837c50d2-214a-479b-b52e-bc57b51c8ba6)


Paste the URL in a web browser's search bar:
![Screenshot 2024-08-03 193033](https://github.com/user-attachments/assets/5102f1b2-e45c-4bb1-9ecf-8e232d068cd5)


An error message will appear because the resource doesn't quite exist yet: 
![Screenshot 2024-08-03 193059](https://github.com/user-attachments/assets/5735a6d9-028e-4fee-b6a7-469020fc4530)


Return to the file in the container and select "Change access level":
![Screenshot 2024-08-03 193157](https://github.com/user-attachments/assets/1b4d0378-eb1c-45be-ad33-ec48529daa89)


Change the option from "Private" to "Blob" to make the URL public, and select "OK":
![Screenshot 2024-08-03 193252](https://github.com/user-attachments/assets/93ba008e-5387-4283-b81d-ee5b1530a18d)


Return to the browser once more and refresh the page. The result is a successfully generated build of the blob:
![Screenshot 2024-08-03 193410](https://github.com/user-attachments/assets/07605433-c730-48ff-8fe1-242676633065)


Going back to the storage account, select the "Delete" button to delete the storage account and all its contents:
![Screenshot 2024-08-03 193748](https://github.com/user-attachments/assets/37ec054c-0ded-4a65-b739-856fbc13e9e8)


A confirmation of the deletion will be shown. You will be prompted to type the storage account's name to delete it:
![Screenshot 2024-08-03 193947](https://github.com/user-attachments/assets/e2ea238f-1a35-41f2-9387-ab92af6f40fa)


A pop-up box titled "Delete confirmation" will appear; select "Confirm delete":
![Screenshot 2024-08-03 194057](https://github.com/user-attachments/assets/87102ffe-67ee-4f3e-9e8f-0494109128fa)


The contents should be deleted successfully:
![Screenshot 2024-08-03 194115](https://github.com/user-attachments/assets/1c366980-9ef1-4ed9-83a6-8db68219016f)


You can even observe the deletion by returning to the once-active storage account:
![Screenshot 2024-08-03 194208](https://github.com/user-attachments/assets/1f40a812-b287-4296-a172-e37a771226e4)
