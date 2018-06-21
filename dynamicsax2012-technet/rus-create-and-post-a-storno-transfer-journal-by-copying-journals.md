---
title: (RUS) Create and post a storno transfer journal by copying journals
TOCTitle: (RUS) Create and post a storno transfer journal by copying journals
ms:assetid: 05a1a672-1696-47cb-a930-dbf2861d97eb
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711354(v=AX.60)
ms:contentKeyID: 49387172
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Create and post a storno transfer journal by copying journals [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

To reverse an entry for a transfer journal, you can use the **Copy** function.

1.  Click **Inventory management** \> **Journals** \> **Item transactions** \> **Transfer**.

2.  Create and post an inventory journal. For more information about inventory journals, see [Inventory journal (form)](https://technet.microsoft.com/en-us/library/aa558607\(v=ax.60\)).

3.  Select the posted journal to correct, and then click **Functions** \> **Copy** to open the **Copy lines to a new journal** form. The **Journal** field displays the journal number of the posted journal. You can modify the journal number, if a new number is required.

4.  In the **Description** field, modify the description of the journal, if a new description is required.

5.  In the **Transaction date** field, select the transaction date.

6.  In the **Detail level** field, select **Inventory transactions** or **Journal lines**.
    
      - If you know that the inventory dimensions on the journal lines that you are copying match the dimensions in the inventory transactions, select **Journal lines**.
    
      - If you are not sure whether the inventory dimensions on the journal lines that you are copying match, select **Inventory transactions**. If you select **Inventory transactions**, the new journal lines are copied from the original journal lines. The copied inventory transactions have the same inventory dimensions as the original inventory transactions. Also, receipt inventory transactions are updated as **Registered**, and issue inventory transactions are updated as **Reserved physical**.

7.  Select the **Return direction** check box to replace inventory dimensions when journal lines are created.
    

    > [!NOTE]
    > <P>When the <STRONG>Return direction</STRONG> check box is selected, the <STRONG>Storno</STRONG> check box is available.</P>



8.  Select the **Storno** check box to reverse the journal transaction.
    

    > [!NOTE]
    > <P>By default, when you select the <STRONG>Storno</STRONG> check box, the <STRONG>Automarking</STRONG> check box is selected and cannot be modified. The inventory lot of the inventory transaction that is copied is linked to a new storno transaction, and the inventory cost is updated in the inventory storno transaction.</P>



9.  Click **OK** to create a storno transfer journal.

10. Select the storno journal that you created, and then click **Lines** to open the **Journal lines, inventory** form.

11. In the **Quantity** field, enter the corrected quantity to post.

12. Click **Post** to open the **Post journal %1.** form.

13. Click **OK** to validate and post the transfer journal.
    

    > [!NOTE]
    > <P>Use the <STRONG>Inventory transactions</STRONG> form to view the storno inventory transactions.</P>



## See also

[Copy lines to a new journal (form)](https://technet.microsoft.com/en-us/library/aa498918\(v=ax.60\))

[(RUS) Copy lines to a new journal (modified form)](https://technet.microsoft.com/en-us/library/jj711455\(v=ax.60\))

[Journal lines, Inventory transfer (form)](https://technet.microsoft.com/en-us/library/aa587291\(v=ax.60\))

[(RUS) Journal lines, Inventory transfer (modified form)](https://technet.microsoft.com/en-us/library/jj665257\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

