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



Create a name and desired region; keep performance "Standard" and redundancy "Geo-redundant storage." Check the box "Make read access to data available in the event of regional unavailability":
![Screenshot 2024-08-02 232956](https://github.com/user-attachments/assets/93a82370-8dc9-4658-8ff6-168197590757)



In the Advanced section, leave everything as is, ensuring the "Minimum TLS version" is set at Version 1.2:
![Screenshot 2024-08-03 125146](https://github.com/user-attachments/assets/473ee8bf-b189-454f-bf2c-423c237536a8)



In the Networking section, ensure everything remains as is:
![Screenshot 2024-08-03 125320](https://github.com/user-attachments/assets/1f7cb857-7524-4c5c-a121-526312809da7)



In the Data Protection section, DO NOT select the box "Enable point-in-time restore for containers":
![Screenshot 2024-08-03 125846](https://github.com/user-attachments/assets/b1de2441-73a9-40a5-aaa5-e9d672983880)



In the Encryption section, DO NOT select the circle "All service types (blobs, files, tables, and queues)"
![Screenshot 2024-08-03 125950](https://github.com/user-attachments/assets/468013f5-d491-4b8f-9922-116030d6cb17)



In the Tags section, create a Name and Value tag for the storage account to categorize its resources:
![Screenshot 2024-08-03 130112](https://github.com/user-attachments/assets/abb8a68d-c1a8-458f-85d5-3345dcc06447)



Once all the information has been reviewed, select the "Review + create" button to deploy the storage account:
![Screenshot 2024-08-03 170924](https://github.com/user-attachments/assets/109234ac-bcb3-4dc4-b7fd-31a22f007a42)


Once deployment is complete, select the "Go to resource" button to display the storage account's overview. Select "Containers" under the "Data storage" tab:
![Screenshot 2024-08-03 175929](https://github.com/user-attachments/assets/b2092146-1dba-4242-b060-e7f023cfa255)


Select the "Container" button to create a container:
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



![Screenshot 2024-08-03 192932](https://github.com/user-attachments/assets/837c50d2-214a-479b-b52e-bc57b51c8ba6)
