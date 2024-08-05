# Storage-Containers
## How to Create an Azure Container Storage

# Description

This project displays the straightforward creation of a storage account and container in Microsoft Azure Blob (Binary Level Object) Service, utilized in stockpiling unstructured data like documents and images. Containers are inexhaustible, organizational "boxes" nested underneath the Azure Blob Storage service. Storage accounts are considered hierarchical namespaces for the contained data, with each data type attached to an address that includes the account name. Storage accounts with namespaces can even branch out directories that also include blobs. Such remarkable data stewardship is fancied among sizeable companies. 

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



In the Advanced section, leave everything as is, ensuring the "Minimum TLS version" is set at 1.2:
![Screenshot 2024-08-03 125146](https://github.com/user-attachments/assets/473ee8bf-b189-454f-bf2c-423c237536a8)



In the Networking section, ensure everything remains as is:
![Screenshot 2024-08-03 125320](https://github.com/user-attachments/assets/1f7cb857-7524-4c5c-a121-526312809da7)



In the Data Protection section, DO NOT select the box "Enable point-in-time restore for containers":
![Screenshot 2024-08-03 125846](https://github.com/user-attachments/assets/b1de2441-73a9-40a5-aaa5-e9d672983880)



In the Encryption section, DO NOT select the circle "All service types (blobs, files, tables, and queues)"
![Screenshot 2024-08-03 125950](https://github.com/user-attachments/assets/468013f5-d491-4b8f-9922-116030d6cb17)
