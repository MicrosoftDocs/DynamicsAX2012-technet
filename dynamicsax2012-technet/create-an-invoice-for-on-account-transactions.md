---
title: Create an invoice for on-account transactions
TOCTitle: Create an invoice for on-account transactions
ms:assetid: 0d1c3e3b-4046-4204-8d93-c7c125d206b4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa569760(v=AX.60)
ms:contentKeyID: 36056003
ms.date: 10/06/2014
mtps_version: v=AX.60
f1_keywords:
- invoice
- on-account
---

# Create an invoice for on-account transactions [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to create invoice proposals for on-account transactions that can be charged to the customer for a project. After the invoice proposal is reviewed and posted, you can create a project invoice to send to the customer.

1.  Click **Project management and accounting** \> **Common** \> **Project invoices** \> **Project invoice proposals**.
    
    –or–
    
    Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Select or open the project for which to create an invoice. On the **Action Pane**, on the **Manage** tab, in the **New** group, click **Invoice proposal**.
    
    –or–
    
    Click **Project management and accounting** \> **Common** \> **Projects** \> **Project contracts**. Select or open the project contract for which to create an invoice. On the **Action Pane**, on the **Maintain** tab, in the **New** group, click **Invoice proposal**.

2.  On the **Invoice proposals** list page, on the **Action Pane**, click **Invoice proposal**. If billing rules are assigned to the project, click **Invoice proposal from billing rule**.

3.  In the **Create invoice proposal** form, enter a project contract and project for which to create an invoice proposal.
    

    > [!NOTE]
    > <P>If you open the <STRONG>Invoice proposals</STRONG> form by using the <STRONG>Project contracts</STRONG> form or the <STRONG>Projects</STRONG> form, the project contract number, project number, and funding source from the selected project contract or project are automatically entered in the <STRONG>Invoice proposals</STRONG> form.</P>



4.  In the **Invoicing method** list, select whether to include only invoices, only credit notes, or both transaction types in the invoice proposal.

5.  In the **Start date** field, select the date of the earliest on-account transaction to include in the search.

6.  In the **End date** field, select the date of the most recent on-account transaction to include in the search.

7.  In the **Select transactions** section, select only the **On-account** check box, and then click **Search**.

8.  In the search results, select the on-account transactions to include in the invoice proposal.
    

    > [!NOTE]
    > <P>Transactions from both the projects and subprojects that are attached to the selected project contract are included in the search results.</P>



9.  To create the invoice proposal, click **OK**.

10. In the **Invoice proposals** form, examine the contents of the invoice proposal and the transactions that are attached to the proposal.
    
    If the information requires an adjustment, delete the line from the proposal, and adjust the transaction. Alternatively, depending on the number of adjustments, you can cancel the invoice proposal, adjust the project transactions, and then create the invoice proposal again.

11. To post the invoice proposal and create a project invoice for the transactions in the invoice proposal, on the **Action Pane**, in the **Functions** group, click **Post**.
    

    > [!NOTE]
    > <P>If your organization uses workflow, click <STRONG>Submit</STRONG> to submit the invoice proposal to workflow for review.</P>



If the on-account invoice proposal is approved, the reviewer posts the invoice, and you can then send the invoice to the customer.

## See also

[Create on-account invoices for all projects](create-on-account-invoices-for-all-projects.md)

[Create invoice proposals for projects that have billing rules (form)](https://technet.microsoft.com/en-us/library/jj683235\(v=ax.60\))

[Invoicing](invoicing.md)

[Invoice proposals (form)](https://technet.microsoft.com/en-us/library/aa615408\(v=ax.60\))

[Projects (form)](https://technet.microsoft.com/en-us/library/aa585245\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

