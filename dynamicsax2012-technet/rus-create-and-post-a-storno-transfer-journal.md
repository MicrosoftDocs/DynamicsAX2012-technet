---
title: (RUS) Create and post a storno transfer journal
TOCTitle: (RUS) Create and post a storno transfer journal
ms:assetid: 76775a97-fb14-41d6-a470-4229559b74c4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678369(v=AX.60)
ms:contentKeyID: 49387599
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Create and post a storno transfer journal [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can post transfer journals according to the storno option that is used for other inventory journal types. You can mark a journal and its lines with the storno option. Inventory transactions that are created for the lines are also marked as storno, which differentiates the lines on inventory reports. The general ledger transactions for the storno journal are also posted as storno. To simplify the process of creating the storno transfer journal, the extended Copy inventory journal function is available for transfer journals.

You can use storno to reverse a journal transaction that is posted incorrectly.

1.  Click **Inventory management** \> **Journals** \> **Item transactions** \> **Transfer**.

2.  Create a new line, select the name of the journal to correct, and then click the **General** tab. For more information about inventory journals, see [Inventory journal (form)](https://technet.microsoft.com/en-us/library/aa558607\(v=ax.60\)).

3.  Select the **Storno** check box to reverse the journal transaction.

4.  Click **Lines** to open the **Journal lines, inventory** form.

5.  Create a new journal line, and enter the required details. For more information about inventory journals, see [Journal lines, Inventory transfer (form)](https://technet.microsoft.com/en-us/library/aa587291\(v=ax.60\)).

6.  In the **Date** field, select the transaction date.

7.  In the **Item number** field, select the item number of the inventory item to post.

8.  In the **Quantity** field, enter the quantity of the inventory item to post.
    

    > [!NOTE]
    > <P>The <STRONG>Storno</STRONG> check box is updated from the journal header on the <STRONG>General</STRONG> tab.</P>



9.  Click the **Inventory dimensions** tab.

10. In the **From inventory dimensions** field group, select the source dimensions.

11. In the **To inventory dimensions** field group, select the destination dimensions.

12. Click **Post** to open the **Post journal %1.** form.

13. Click **OK** to validate and post the transfer journal.

14. Click **Inventory** \> **Transactions** to open the **Inventory transactions** form. You can view the inventory transactions for the journals that have been posted.
    

    > [!NOTE]
    > <P>You can view the physical and financial vouchers for the transactions. Both receipt and issue inventory transactions are marked as storno. The transaction amount is negative for both the receipt and issue financial transactions.</P>



## See also

[(RUS) Create and post a storno transfer journal by copying journals](rus-create-and-post-a-storno-transfer-journal-by-copying-journals.md)

[(RUS) Journal lines, Inventory transfer (modified form)](https://technet.microsoft.com/en-us/library/jj665257\(v=ax.60\))

[Inventory transactions (form)](https://technet.microsoft.com/en-us/library/aa584374\(v=ax.60\))

[(RUS) Inventory transactions (modified form)](https://technet.microsoft.com/en-us/library/jj733410\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

