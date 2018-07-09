---
title: (RUS) Adjust the cost price from the ledger account
TOCTitle: (RUS) Adjust the cost price from the ledger account
ms:assetid: 0e1460c6-65c7-4801-a426-3da4836b28cd
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711388(v=AX.60)
ms:contentKeyID: 49387206
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Adjust the cost price from the ledger account [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



You can use this wizard to create and run cost price adjustments for on-hand transactions and inventory transactions.

1.  Click **Inventory management** \> **Periodic** \> **Closing and adjustment**. Click **Adjustment** and then click **Wizard**
    

    > [!NOTE]
    > <P>To use the wizard for on-hand inventory adjustments, select the type as <STRONG>Closing</STRONG> in the <STRONG>Closing and adjustment</STRONG> form. If you use the standard adjustment functions <STRONG>On-hand</STRONG> or <STRONG>Transactions</STRONG>, the adjustments will be posted into the profit and loss accounts as usual.</P>



2.  In the **Wizard for cost value adjustment of inventory transactions or entire on-hand inventory** form, select the method of cost value adjustment as **On-hand** or **Transactions**.

3.  In the **Select on-hand inventory** form, click **Select** to specify the selection criteria for on-hand inventory and inventory dimensions transactions.
    

    > [!NOTE]
    > <P>In the form, <STRONG>Exclude Reverse</STRONG> is active by default. If you are making both positive and negative adjustments to the cost price, perform each adjustment as a separate step.</P>



4.  Click **Next** to select the adjustment calculation method as **From ledger account.**

5.  Click **Next** to perform the adjustment.

6.  In the **Ledger account** field, select the account number for posting in ledger.

7.  In the **Balance on the date** field, select the date.

8.  Select **Balance account** option or **Balance from ledger account and dimensions option**.

9.  In the **Focus** field, select the available focuses dimension.
    

    > [!NOTE]
    > <P><STRONG>Focus</STRONG> field is activated only when selecting the <STRONG>Balance from ledger account and dimensions</STRONG> option.</P>



10. Click **Next** to open the **Balance from ledger account or dimensions** page.

11. In the **Allocation principle** field, select the method as **Value** or **Quantity**.

12. In the **Specification** field, select the specification to determine the level of detail that will be posted to the general ledger.
    
      - **Total** – Post the values for each ledger account as a total figure.
    
      - **Item group** – Post the values for each unique item group in the general ledger.
    
      - **Item number** – Post the value for each unique item in the general ledger.

13. In the **Note** field, enter any comments.

14. Click **Next** to open the **Finish wizard** page.

15. Select the **Show ledger Voucher list** check box to view the list of posted transactions.

16. Click **Finish** to run the wizard.

17. If necessary, click **Cancel** to cancel the adjustments made by the wizard.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

