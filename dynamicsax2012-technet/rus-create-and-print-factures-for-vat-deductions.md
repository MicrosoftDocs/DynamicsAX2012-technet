---
title: (RUS) Create and print factures for VAT deductions
TOCTitle: (RUS) Create and print factures for VAT deductions
ms:assetid: 65b9653a-3607-4636-b369-c37a4d4d2dae
ms:mtpsurl: https://technet.microsoft.com/library/JJ665460(v=AX.60)
ms:contentKeyID: 49387547
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Create and print factures for VAT deductions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use the **Update facture** form to create and print factures for journals that have been posted. You can then view the factures that you created or updated in the **Facture journal** form.

Before you can create and print a facture report for received invoices, issued invoices, purchases, or sales in estimates of value-added tax (VAT), you must complete the following tasks:

1.  Set up the parameters for a tax agent transaction.

2.  Define a vendor as a tax agent.

3.  Create and post a purchase order that has a sales tax group and an item sales tax group.

4.  Create a payment proposal, and post the payment.

The facture report displays the number and date of the payment order, the base amount without VAT, and the computational tax rate (VAT value / VAT value + 100).


> [!NOTE]
> <P>If the source of the facture is <STRONG>Tax correction</STRONG>, enter an explanatory note about the details of the invoice line in the <STRONG>Note</STRONG> field in the <STRONG>Facture journal</STRONG> form. This information is displayed on the facture report.</P>



1.  Click **Accounts payable** \> **Inquiries** \> **Journals** \> **Invoice journal**.

2.  Select the journal line for the posted journal, and then click **Create facture** \> **Update facture**.

3.  In the **Facture** field, enter an identification number for the facture.

4.  In the **Date of the registration** field, select the date when the facture is registered.

5.  In the **Facture date** field, select the date when the facture is created.
    

    > [!NOTE]
    > <P>You can select the facture date only if you clear the <STRONG>Same as</STRONG> check box. Otherwise, this field displays the same date that you select in the <STRONG>Date of the registration</STRONG> field.</P>



6.  In the lower pane, on the **Invoice** tab, select the **To facture** check box to update the facture by using the selected invoice.

7.  In the upper pane, click **Posting** \> **Update and print** to update and print the facture.
    

    > [!TIP]
    > <P>Click <STRONG>Posting</STRONG> &gt; <STRONG>Update</STRONG> to update changes to the facture, but without printing the facture.</P>
    > <P>–or–</P>
    > <P>Click <STRONG>Posting</STRONG> &gt; <STRONG>Print</STRONG> to print the facture without posting it.</P>



8.  Click **Accounts payable** \> **Inquiries** \> **Journals** \> **Facture**. You can view the facture that you created or updated in the **Facture journal** form. These factures can be registered in the sales book. For more information, see [(RUS) Create a sales book](rus-create-a-sales-book.md).

## See also

[(RUS) Create vendor tax agent transactions](rus-create-vendor-tax-agent-transactions.md)

[(RUS) Set up the tax agent transactions](rus-set-up-the-tax-agent-transactions.md)

[(RUS) Create a payment proposal for a tax agent invoice](rus-create-a-payment-proposal-for-a-tax-agent-invoice.md)

[(RUS) Update facture (form)](https://technet.microsoft.com/library/jj889412\(v=ax.60\))

[(RUS) Facture journal (form)](https://technet.microsoft.com/library/jj923567\(v=ax.60\))

  


