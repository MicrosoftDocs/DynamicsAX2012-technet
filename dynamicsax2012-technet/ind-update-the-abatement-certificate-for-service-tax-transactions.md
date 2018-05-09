---
title: (IND) Update the abatement certificate for service tax transactions
TOCTitle: (IND) Update the abatement certificate for service tax transactions
ms:assetid: 7ddd6806-f6bf-4c20-a860-86588392ad4f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677953(v=AX.60)
ms:contentKeyID: 49385915
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) Update the abatement certificate for service tax transactions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



You can update the abatement certificate for service tax transactions that are eligible for abatement and that are posted for a GTA vendor in the **Purchase order** form or in the **Journal voucher** form.

For a GTA vendor, you can define the criteria to display the service tax transactions to update in the abatement certificate, and you can select the service tax transactions that should be updated with the abatement certificate number.

1.  Click **General ledger** \> **Periodic** \> **India** \> **Abatement certificate**.

2.  Select the GTA vendor in the **GTA vendor** field that the service tax transactions with abatement should be displayed for.

3.  In the **Source** field, select the source that the service tax transaction should be displayed from the following options:
    
      - **All** – Displays the service tax transactions that are posted by using the purchase order and journals for the selected GTA vendor.
    
      - **Purchase order** – Displays the service tax transactions that are posted by using the purchase order for the selected GTA vendor.
    
      - **Voucher** – Displays the voucher transactions for the selected GTA vendor.

4.  Enter the date in the **Date** field. The service tax transactions that were not updated prior to this date for the abatement certificate are displayed.

5.  Enter the abatement certificate number in the **Certificate number** field for the service tax transactions that should be updated in the abatement certificate.
    

    > [!NOTE]
    > <P>You can enter a maximum of 20 characters in the <STRONG>Certificate number</STRONG> field.</P>



6.  Click **Show data**. The service tax transactions that the abatement certificate is not updated for are listed in the lower section of the form, based on the criteria entered in the header section.

7.  Select the **Mark** check box for each service tax transaction to include on the abatement certificate.

8.  View the details of the service tax transactions that the abatement certificate should include.

9.  Click **Update** to update the abatement certificate in the related vouchers for the selected transactions.
    

    > [!NOTE]
    > <P>You can view the updated transactions in the <STRONG>Service tax inquiry</STRONG> form</P>



## See also

[(IND) Abatement certificate (form)](https://technet.microsoft.com/en-us/library/jj664822\(v=ax.60\))

[(IND) Service tax inquiry (form)](https://technet.microsoft.com/en-us/library/jj664526\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

