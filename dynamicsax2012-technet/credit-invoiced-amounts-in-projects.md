---
title: Credit invoiced amounts in projects
TOCTitle: Credit invoiced amounts in projects
ms:assetid: f29058cb-e32e-467d-bc01-a67a61d297ba
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa551626(v=AX.60)
ms:contentKeyID: 36811439
ms.date: 09/30/2014
mtps_version: v=AX.60
f1_keywords:
- credit note
- credit note proposal
- invoiced amount
---

# Credit invoiced amounts in projects [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Crediting an invoiced amount is a two-step procedure. First, select the invoiced amount that you want to credit. Then, create a credit note. You create a credit note by using the same procedure that is used to generate a customer invoice.

## Select transactions that you want to create a credit for

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. On the **Action Pane**, on the **Manage** tab, in the **Bill** group, click **Invoice journals**.
    
    –or–
    
    Click **Project management and accounting** \> **Common** \> **Projects** \> **Project contracts**. On the **Action Pane**, on the **Maintain** tab, in the **Bill** group, click **Invoice journals**.

2.  In the **Invoice journals** form, on the **Overview** tab, select the invoice or invoices to which you want to apply credit.

3.  Click **Functions** \> **Select for credit note**.

4.  In the **Select for credit note** form, on each tab, select the transactions that you want to create credit notes for.
    
    –or–
    
    To select all transactions on a tab, click the **Select** button on the tab. For example, click **Select hours** on the **Hour** tab.
    
    –or–
    
    To select all transactions on all tabs in the **Select for credit note** form, click **Select all** at the bottom of the form.
    

    > [!NOTE]
    > <P>You can’t select the invoiced prepayments and invoiced project sales orders to create a credit note. After the credit note proposal is posted, the credited transactions are reversed and marked as chargeable, or the transactions are available to invoice again. If the credited transactions need to be changed, you can post an adjustment for the credited transactions before the credited transactions are invoiced again.</P>



## Create and post a credit note proposal

1.  Click **Project management and accounting** \> **Common** \> **Project invoices** \> **Project invoice proposals**.

2.  In the **Invoice proposal** list page, on the **Action Pane**, click **New** \> **Invoice proposal**.

3.  In the **Create invoice proposals** form, on the **General** tab, in the **Invoicing method** field, select **Credit notes** or **Both**.
    

    > [!NOTE]
    > <P>If you select <STRONG>Both</STRONG>, invoice proposals are created for both invoicing and crediting.</P>



4.  In the **Include transaction types** section, select the check boxes of the transaction types that you want to include in the credit note, and then click **OK**.

5.  In the **Invoice proposal** form, delete any proposals that you do not want to include in the posting.

6.  Click **Post** to create the credit note.

## See also

[Invoice journals (form) (Project)](https://technet.microsoft.com/en-us/library/aa618187\(v=ax.60\))

[Invoice proposals (form)](https://technet.microsoft.com/en-us/library/aa615408\(v=ax.60\))

[Create invoice proposals (class form)](https://technet.microsoft.com/en-us/library/aa600958\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

