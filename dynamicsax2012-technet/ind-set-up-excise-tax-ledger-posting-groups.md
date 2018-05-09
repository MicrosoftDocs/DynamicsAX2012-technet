---
title: (IND) Set up excise tax ledger posting groups
TOCTitle: (IND) Set up excise tax ledger posting groups
ms:assetid: 142758f6-a7fe-4787-a39d-69b1de34abf8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664507(v=AX.60)
ms:contentKeyID: 49385586
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) Set up excise tax ledger posting groups 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



Create the ledger posting group for excise tax. You can attach the ledger accounts to various components of the excise duty for a specified excise register number or for all the excise registration numbers, and attach the ledger posting group to the excise tax code. The posting group contains the ledger accounts that the calculated excise tax is posted to. The number of ledger posting groups that you must create depends on the number of warehouses that the company has.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **India** \> **Tax ledger posting groups**.

2.  Press CTRL+N and enter a name for the ledger posting group in the **Ledger posting group** field. The name must be a unique identification of the ledger posting group.

3.  Enter a description of the ledger posting group.

4.  Select **Excise** in the **Tax type** field.

5.  Click the **Setup** tab.

6.  Select the account code in the **Account code** field from the following options:
    
      - **Table** – Define the ledger accounts for the excise registration number that is specified in the **Registration number** field. The registration number must have the tax type set as **Excise** and the registration number type set as **Company**.
    
      - **All** – Define the ledger accounts for all the tax registration numbers with the **Excise** tax type and the registration number type set as **Company**.

7.  Select the excise registration number of the company in the **Registration number** field if you have selected the **Table** option in the **Account code** field.

8.  Enter a description for the registration number in the **Description** field.

9.  Click the **Ledger accounts** tab. Select the predefined account types—one at a time—and attach the ledger account to the excise tax components. Likewise, attach ledger accounts from the following list to the excise tax components for all the predefined accounts:
    
      - **Payable account**
    
      - **Recoverable account**
    
      - **Deferred account**

10. Expense account

11. Press CTRL+N in the right pane of the form to create a new record.

12. Select the excise tax component in the **Tax component** field.

13. Select the ledger account in the **Ledger account** field to post the excise component duty to in the ledger.
    

    > [!NOTE]
    > <P>You cannot assign the same tax component to a ledger account type more than once.</P>



14. Press CTRL+S or close the form.

## See also

[(IND) Tax ledger posting groups (form)](https://technet.microsoft.com/en-us/library/jj664546\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

