---
title: (IND) Define ledger posting groups for tax components
TOCTitle: (IND) Define ledger posting groups for tax components
ms:assetid: 33327460-c7bf-41d0-8de4-468767a335ff
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664603(v=AX.60)
ms:contentKeyID: 49385680
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Define ledger posting groups for tax components 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



You can create a ledger posting group and attach tax components to the group. You can then define the ledger accounts for the tax components.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **India** \> **Tax ledger posting groups**.

2.  Press CTRL+N to create a new tax ledger posting group.

3.  Enter a name for the tax ledger posting group in the **Ledger posting group** field.

4.  Enter a description for the tax ledger posting group in the **Description** field.

5.  Select **India sales tax** in the **Tax type** field.

6.  Click the **Setup** tab. Select the account code from the following options in the **Account code** field:
    
      - **Table** – Set up posting accounts for a specific sales tax registration number.
    
      - **All** – Set up posting accounts for all the sales tax registration numbers.

7.  Select the sales tax registration number in the **Registration number** field if you selected **Table** in the **Account code** field. The description of the sales tax registration number is displayed in the **Description** field.

8.  Click the **Ledger accounts** tab.

9.  Under the **Select** field group, select the account type to define ledger accounts for. The options are:
    
      - **Payable account** – Define the payable account to post the sales tax payable amount.
    
      - **Expense account** – Define the expense account to post the taxes that are paid to the vendor.

10. On the right pane press CTRL+N to create a new line.

11. Select the tax component to define the posting account for in the **Tax component** field.

12. Select the ledger account to post the tax amount to for the tax component in the **Ledger** field.

13. Press CTRL+S or close the form.

## See also

[(IND) Tax ledger posting groups (form)](https://technet.microsoft.com/en-us/library/jj664546\(v=ax.60\))

  


