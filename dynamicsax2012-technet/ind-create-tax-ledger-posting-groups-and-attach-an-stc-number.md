---
title: (IND) Create tax ledger posting groups and attach an STC number
TOCTitle: (IND) Create tax ledger posting groups and attach an STC number
ms:assetid: 79528272-a04e-4e04-a573-e4e6aee37b72
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677947(v=AX.60)
ms:contentKeyID: 49385910
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) Create tax ledger posting groups and attach an STC number [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create a ledger posting group for service tax. You can then attach ledger accounts to various components of the service tax for a specific service tax (STC) number or all STC numbers.

The ledger posting group is attached to the service tax code. The posting group contains the ledger accounts that the calculated service tax is posted to.


> [!NOTE]
> <P>You cannot assign the same tax component to a ledger account type more than one time.</P>



1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **India** \> **Tax ledger posting groups**.

2.  Click **New**, and then, in the **Ledger posting group** field, enter a name for the ledger posting group.

3.  In the **Description** field, enter a description of the ledger posting group.

4.  In the **Tax type** field, select **Service tax**.

5.  On the **Setup** FastTab, click **Add**. Then, in the **Account code** field, select the account code. The following options are available:
    
      - **Table** – Define the ledger accounts for the STC number that you specify in the **Registration number** field. The tax type of the registration number must be set to **Service tax**, and the registration number type must be set to **Company**.
    
      - **All** – Define the ledger accounts for all STC numbers for which the tax type is set to **Service tax** and the registration number type is set to **Company**.

6.  If you selected **Table** in the **Account code** field, in the **Registration number** field, select the company’s registration number for service tax.

7.  On the **Ledger accounts** FastTab, select the predefined account type. The following options are available:
    
      - **Payable account**
    
      - **Recoverable account**
    
      - **Interim payable account**
    
      - **Interim recoverable account**
    
      - **Expense account**
    

    > [!NOTE]
    > <P>You can select one predefined account type at a time and attach the ledger account to the service tax components for that predefined account. Alternatively, you can attach the ledger account to the service tax components for all the predefined accounts.</P>



8.  Click **Add**, and then, in the **Tax component** field, select the service tax component.

9.  Select the ledger account that is used to post the service tax component in the ledger.

## See also

[(IND) Tax ledger posting groups (form)](https://technet.microsoft.com/en-us/library/jj664546\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

