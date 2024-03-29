## Challenge 14 : Contoso Company Storage Disaster Recovery

### **Contoso Environment:** 

1. The Contoso environment consists of an Azure **subscription** with **contributor** permissions and a pre-provisioned resource group.

1. To access the Azure portal, open a private/incognito window in your browser and navigate to **[Azure Portal](https://portal.azure.com)**.

1. On the **Sign in to Microsoft Azure** tab you will see a login screen, enter the following email/username and then click on **Next**. 
   * Email/Username: <inject key="AzureAdUserEmail"></inject>
   
     ![](media/email1.png "Enter Email")
     
1. Now enter the following password and click on **Sign in**.
   * Password: <inject key="AzureAdUserPassword"></inject>
   
     ![](media/password2.png "Enter Password")
     
1. If you see the pop-up **Stay Signed in?**, click No.

1. If you see the pop-up **You have free Azure Advisor recommendations!**, close the window to continue the lab.

1. If a **Welcome to Microsoft Azure** popup window appears, click **Maybe Later** to skip the tour.
   
1. Now you will see Azure Portal Dashboard, click on **Resource groups** from the Navigate panel to see the resource groups.

    ![](media/select-rg.png "Resource groups")
   
1. Confirm you have a resource group **Challenge14** present as shown in the below screenshot. You need to use the **Challenge14** resource group through out this challenge.

    ![](media/challenge14-rg.png "Resource groups")

### **Level:** Intermediate 

### **Challenge Objective:**

Contoso Company wants to ensure that their data is available even in the event of a disaster. Your challenge is to implement Azure Storage redundancy and configure object replication to ensure that the data is always available.

### Success Criteria:

1. Create two Azure Blob Storage accounts in different regions.

1. Configure one of the storage accounts as the primary and the other as the secondary.

1. Upload sample data to primary storage account. 

1. Configure object replication to replicate the data from the primary to the secondary storage account.

1. Verify that the data is available even in the event of a disaster.

### Lab Validation:

1. After completing the challenge, you need to visit the **Lab Validation (1)** tab and click on the **VALIDATE (2)** button under Actions to perform the validation steps. Verify that you have met the success criteria of the challenge. 

    ![](media/challenge14-v1.png "Validation")

1. If the validation status displays **Success** for all the validation steps, **congratulations!** This means that you have successfully completed the challenge. 

     ![](media/challenge14-v2.png "Validation")
     
1. If the validation status displays **Fail**, **don't worry!** This could mean that you did not perform the challenge correctly.

     ![](media/challenge14-v3.png "Validation")

1. Hover your mouse over the `i` **(1)** icon to see the error message and determine the root cause of the failure. Based on the error message, revisit the challenge as necessary, and redo the validation by clicking on the **VALIDATE (3)** button again.
      
     ![](media/challenge14-v4.png "Validation") 

1. If you are still having trouble, you can reach out to the support team via `labs-support@spektrasystems.com` for further assistance. The support team is available to help you to troubleshoot and resolve any technical issues or validation issues that may arise while the lab environment is live.
