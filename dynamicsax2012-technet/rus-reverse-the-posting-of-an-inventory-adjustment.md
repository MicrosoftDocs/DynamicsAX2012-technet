---
title: (RUS) Reverse the posting of an inventory adjustment
TOCTitle: (RUS) Reverse the posting of an inventory adjustment
ms:assetid: 7e5a23ee-fa2d-4010-be74-8444e15a972b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678401(v=AX.60)
ms:contentKeyID: 49387631
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Reverse the posting of an inventory adjustment 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Inventory management** \> **Setup** \> **Inventory and warehouse management parameters**.

2.  In the **Inventory and warehouse management parameters** form, select the **Storno for inventory adjustments** check box to allow cost price adjustments.

3.  Click **Inventory management** \> **Periodic** \> **Close and adjustment in currency**.
    

    > [!NOTE]
    > <P>For more information, see "Closing and adjustment (form)" in the Applications and Business Processes Help.</P>



4.  Click **Adjustment** \> **Transactions** to open the **Adjust transactions in currency** form.
    

    > [!NOTE]
    > <P>For more information, see "Adjust transactions (form)" in the Applications and Business Processes Help.</P>



5.  In the **Adjustment** field, enter the adjustment value.
    

    > [!NOTE]
    > <P>If the adjustment increases the transaction value, the transaction is performed with a plus sign (+). If the adjustment decreases the value, the transaction is performed with the minus sign (-) (reverse).</P>



6.  Click **Post** to open the **Adjust transactions** form.

7.  In the **Posting date** field, select the posting date.

8.  In the **Specification** field, select the specification to determine the level of detail that will be posted to the general ledger.
    
      - **Total** – Post the values for each ledger account as a total figure.
    
      - **Item group** – Post the values for each unique item group in the general ledger.
    
      - **Item number** – Post the value for each unique item in the general ledger.

9.  If the adjustment results are to be reflected in ledger accounts, select the **Update ledger** check box.

10. In the **Note** field, enter any comments about the inventory adjustment.

11. Click **OK** to run the transactions with the adjustment.

## See also

[(RUS) Set up reverse transactions](rus-set-up-reverse-transactions.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

