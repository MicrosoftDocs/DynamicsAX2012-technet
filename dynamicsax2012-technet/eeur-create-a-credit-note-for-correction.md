---
title: (EEUR) Create a credit note for correction
TOCTitle: (EEUR) Create a credit note for correction
ms:assetid: 77404e22-50ea-461f-afc4-9ef8dec8f047
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678243(v=AX.60)
ms:contentKeyID: 49386966
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (EEUR) Create a credit note for correction [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to create a credit note. A credit note contains a reference to the original invoice, all corrected and optional corrective lines, and the reason for the correction.

A corrected line contains the same information as the original incorrect line. However, the amount has a sign that is the reverse of the original amount.

A corrective line is a new line that has the correct information and an amount that does not have its sign reversed. You can maintain the corrective line. You can also delete the corrective line.

**Prerequisites**

Before you can complete the procedure in this topic, you must follow these steps.

1.  Click **General ledger** \> **Setup** \> **General ledger parameters**. In the **Ledger** area, on the **Accounting rules** FastTab, select the **Correction** check box. Transactions that have negative amounts can now be posted as corrections in the general ledger.

2.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**. In the **Updates** area, on the **Invoice** FastTab, select the **Credit note as correction** check box.

## Create a credit note for correction

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**. On the **Action Pane**, on the **Sales order** tab, in the **New** group, click **Sales order**.

2.  In the **Create sales order** form, select the customer to whom you are issuing a credit note. Enter any additional information, and then click **OK**.

3.  In the **Sales order** form, on the **Action Pane**, on the **Sell** tab, click **Credit note**.

4.  In the **Create credit note** form, the upper pane displays sales orders that have a status of **Invoiced**.
    
    On the **Invoice** tab, select the sales order for which you are issuing a credit note, and then, in the lower pane, select the sales order lines to correct.
    

    > [!NOTE]
    > <P>By default, the <STRONG>Create corrective lines</STRONG> check box is selected. A selected check box indicates that both the corrected and corrective lines are created. To reverse the original transaction without creating a corrective line, clear the <STRONG>Create corrective lines</STRONG> check box.</P>



5.  Maintain other options, and then click **OK** to generate the credit note transactions and close the **Create credit note** form.
    
    The **Sales order** form displays the corrected and corrective lines. The fields on the corrected line cannot be maintained, because the credit note functionality reverses the original transactions and replaces them with new transactions.

6.  For the corrective line, you can maintain the following fields if they apply to the item:
    
      - **Variant number**
    
      - **Quantity**
    
      - **Unit**
    
      - **Size**
    
      - **Site**
    
      - **Warehouse**
    
      - **Unit price**
    
      - **Discount**
    
      - **Discount percent**
    
      - **Net amount**
    
      - **Deliver now**
    
    You can maintain many fields on the **Line details** FastTab.
    
    You can also delete the corrective line.

7.  When you have finished maintaining the corrective line, on the **Invoice** tab, in the **Generate** group, click **Invoice**.

8.  In the **Posting invoice** form, click **OK** to post the credit note.
    

    > [!TIP]
    > <P>To view the original invoice and the credit note, in the <STRONG>Journals</STRONG> group, click <STRONG>Invoice</STRONG> to open the <STRONG>Invoice journal</STRONG> form.</P>



## See also

[(CZE) Sales orders (modified form)](https://technet.microsoft.com/en-us/library/jj714420\(v=ax.60\))

[(EEUR) Sales orders (modified form)](https://technet.microsoft.com/en-us/library/jj853393\(v=ax.60\))

[(LTU) Sales orders (modified form)](https://technet.microsoft.com/en-us/library/jj678097\(v=ax.60\))

[(LVA) Sales orders (modified form)](https://technet.microsoft.com/en-us/library/dn133841\(v=ax.60\))

[(POL) Sales orders (modified form)](https://technet.microsoft.com/en-us/library/jj678144\(v=ax.60\))

[(POL) Set up credit note parameters](pol-set-up-credit-note-parameters.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

