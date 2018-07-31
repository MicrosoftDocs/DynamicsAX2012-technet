---
title: Create and post invoice proposals
TOCTitle: Create and post invoice proposals
ms:assetid: 29738be9-5198-4dbd-bcb7-cd32c26c707b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa496846(v=AX.60)
ms:contentKeyID: 36811401
ms.date: 10/06/2014
mtps_version: v=AX.60
f1_keywords:
- invoice proposal
- credit note
- on-account proposal
audience: Application User
ms.search.region: Global
---

# Create and post invoice proposals 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

An invoice proposal is a preliminary invoice that you can review before you create a customer invoice for project transactions. This topic explains how to create an invoice proposal for posted project transactions that are chargeable to a customer. You can also add a customer prepayment or a customer-retained amount to an invoice proposal.

If you are using Microsoft Dynamics AX 2012 R3, you can modify the sales price of the lines in an invoice proposal and add a fee amount to an invoice proposal. When you post the invoice proposal, the sales price and fee amount are added to project transactions. See the section “Modify lines in an invoice proposal in AX 2012 R3,” later in this topic.

## Create an invoice proposal

You can create an invoice proposal for all chargeable project transactions that have a status of **Posted** and for transactions that have a status of **Selected for credit note**.

To create an invoice proposal, follow these steps:

1.  Click **Project management and accounting** \> **Common** \> **Project invoices** \> **Project invoice proposals**. In the **Invoice proposals** list, on the **Action Pane**, click **Invoice proposal**. If billing rules are assigned to the project, click **Invoice proposal from billing rule**.
    
    –or–
    
    Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Select or open the project for which to create an invoice. On the **Action Pane**, on the **Manage** tab, in the **New** group, click **Invoice proposal**.
    
    –or–
    
    Click **Project management and accounting** \> **Common** \> **Projects** \> **Project contracts**. Select or open the project contract for which to create an invoice. On the **Action Pane**, on the **Maintain** tab, in the **New** group, click **Invoice proposal**.

2.  In the **Create invoice proposal** form, enter a project contract and project for which to create an invoice proposal.
    

    > [!NOTE]
    > <P>If you open the invoice proposal form by using the project contract form or the project form, the project contract number, project number, and funding source from the selected project contract or project is automatically entered in the invoice proposal form.</P>



3.  If you are creating an invoice proposal for a project to which no billing rules are assigned, you can select an invoicing method. In the **Create invoice proposal** form, in the **Invoicing method** field, select the types of transactions to include in the invoice proposal:
    
      - **Invoices** – Include transactions that have been posted from journals or other documents and that are ready to be invoiced.
    
      - **Credit notes** – Include transactions that were originally included on an invoice and must now be updated by a credit note.
    
      - **Both** – Include both invoices and credit notes in the proposal.

4.  In the **Select transactions** field group, select the types of transactions to include in the customer invoice.

5.  If you want to include sales orders lines in the invoice proposal, select the **Sales order line** check box. Then, in the **Update item quantity** field, select the stage of the sales order process at which item quantities should be updated in the invoice proposal.

6.  Select a project date range and an invoice date, and then click **Search**.

7.  In the list, select project transactions to include in the invoice proposal.

8.  In the **Reconciliation with customer advances** list, select customer advances to include in the invoice proposal.
    
    Optional: If you want to include only a part of a customer advance, select the customer advance line, and then click **Split advance amount**. In the **Split customer advance transaction** form, in the **Split amount** field, enter the amount to use. This amount is subtracted from the sales value of the project transactions in the invoice proposal. Click **OK**.

9.  In the **Create invoice proposal** form, click **OK**.

10. In the **Invoice proposals** form, view and modify transactions to include in the invoice proposal. To post the invoice proposal, on the **Action Pane**, in the **Functions** group, click **Post**.


> [!TIP]
> <P>You can open the <STRONG>Create invoice proposals</STRONG> form from the <STRONG>Periodic</STRONG> section of the area page in <STRONG>Project management and accounting</STRONG>. If you open the form from this location, you can filter the transactions in the form and then create invoice proposals for multiple projects at the same time.</P>



## Modify lines in an invoice proposal in AX 2012 R3

In AX 2012 R3, you can modify the sales value of lines in an unposted invoice proposal. You can also add a fee to an unposted invoice proposal. Sales taxes, if applicable, are adjusted for the modified lines. Also, if budget checks are enabled for a project, modifications to invoice proposal lines might be restricted by budget limitations that are set up for the project.


> [!NOTE]
> <P>You can’t modify the sales value for a line that was added from a credit note.</P>



To modify lines in an invoice proposal, follow these steps:

1.  Click **Project management and accounting** \> **Common** \> **Project invoices** \> **Project invoice proposals**. Open an invoice proposal that has a status of **Open**.

2.  In the **Invoice proposals** form, modify the unit sales price for lines by using the following steps:
    
    1.  On the **Invoice proposal transactions** FastTab, click **Adjust transactions**.
    
    2.  In the **Adjustment date** field, select a posting date for the adjustment, and then click **OK**.
    
    3.  In the **Adjustments** form, in the lower pane, modify the applicable values.
    
    4.  Optional: You can automatically verify that there are no problems with the adjusted line. To run the verification process, click **Check**.
    
    5.  To post the adjustment as a project journal, click **Post**.

3.  In the **Invoice proposals** form, add fees by using the following steps:
    
    1.  On the **Invoice proposal transactions** FastTab, click **Create fees**.
    
    2.  In the **Create fee journal** form, enter a project, category, currency, and amount for the fees. You can also add a description.
    
    3.  Click **OK**.

## See also

[Create invoice proposal (form)](https://technet.microsoft.com/en-us/library/jj683236\(v=ax.60\))

[Create invoice proposals for projects that have billing rules (form)](https://technet.microsoft.com/en-us/library/jj683235\(v=ax.60\))

[Invoice proposals (form)](https://technet.microsoft.com/en-us/library/aa615408\(v=ax.60\))

[Post invoice proposals (form)](https://technet.microsoft.com/en-us/library/aa620017\(v=ax.60\))

  


