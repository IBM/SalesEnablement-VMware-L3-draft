While some of the modules in the **{{guide.name}}** use click-through demonstrations, other modules use pre-provisioned VMware Cloud Foundation (VCF) as a Service instances running in IBM Cloud in an IBM Technology Zone (ITZ) owned IBM Cloud account. The resources in this IBM CLoud account are shared by all users with an active ITZ reservation for the environment. To access these resources, you must first create a reservation in ITZ for the environment. Detailed steps for creating the reservation and accessing the environment are provided below.

!!! Important "About the IBM Technology Zone (ITZ) environment"

    Before proceeding, read and understand the details about the ITZ environment and your access in the ITZ IBM Cloud account.

    - You must first accept the invitation to join the ITZ IBM Cloud account before you will be able to access it. Details below in the step-by-step guidance
    
    - Your user ID in the ITZ IBM Cloud account is limited. You will **NOT** be able create, delete, or modify the pre-provisioned resources.
    
    - Your user ID **will** have permission to create, delete, and modify resources in the provisioned VCF as a Service instances. 
    
    - In the VCF as a Service instances, do not delete or modify any of the pre-provisioned resources as described in the demonstration guide.
    
    - In the VCF as a Service instances, you are responsible for deleting any resources you create. Do this before your ITZ reservation expires.
    
    - Remember, that the environment is shared by all users of the environment. Do **NOT** delete or modify resources created by other users.
  
## Creating a reservation
Follow these steps to create a reservation in ITZ.

1. Click the link below to open a browser to the reservation page of the **{{itz.collectionName}}**.

    <a href="{{itz.environment}}" target="_blank">{{itz.collectionName}} - reservation page</a>

2. Click **Reserve now**.

    The **Reserve now** option requests the reservation be created now. You can optionally schedule the reservation for later if you like.

    ![](_attachments/itzRSVPReserveNow.png)

3. Complete the form 