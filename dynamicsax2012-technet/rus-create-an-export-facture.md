---
title: (RUS) Create an export facture
TOCTitle: (RUS) Create an export facture
ms:assetid: ad86c2f1-4cca-4436-ac12-271abe7eb375
ms:mtpsurl: https://technet.microsoft.com/library/JJ711507(v=AX.60)
ms:contentKeyID: 49387832
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- VAT
- export facture
audience: Application User
ms.search.region: Russia
---

# (RUS) Create an export facture 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

A facture is considered to be an export facture if it contains invoices that have a tax type of **VAT 0%**, and if the tax code for the domestic market is set. You can specify the export, package, and confirmation dates, and view the expiration date for the export facture. Use the following procedures to create an export facture and specify how the export facture is processed based on the operation type.


> [!NOTE]
> <P>You must define the <STRONG>Tax code for domestic market</STRONG> value for sales tax codes with a tax type of <STRONG>VAT 0%</STRONG>.</P>



## Create a sales order and update the facture

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  On the **Sales order** tab, in the **New** group, click **Sales order** or press CTRL+N to create a sales order.

3.  On the **Setup** tab, in the **Item sales tax group** field, select the item sales tax group for export operations.

4.  In the **Sales tax group** field, select the sales tax group for export operations.

5.  On the **Sell** tab, click **Sales order confirmation** to confirm the sales order.

6.  Click **Invoice** \> **Facture** to open the **Update facture** form.

7.  Click **OK** to post the facture.

## Process the export facture based on an operation type

1.  Click **Accounts receivable** \> **Inquiries** \> **Journals** \> **Facture**. The **Into processing** check box is selected for an export facture for preliminary processing of the facture, and the **Operation type** field displays the rule that is used for preliminary processing of the export facture.

2.  On the **Foreign trade** tab, in the **Export date** field, select the date when the items were exported under customs export conditions. The **Export date** field displays the date from which the expiration date is calculated to collect the document package that confirms the right to use the value-added tax (VAT) at a rate of zero percent.

3.  In the **Package date** field, select the date of the document package collection.

4.  In the **Confirmation date** field, select the date when the VAT was confirmed by the tax authority at a rate of zero percent.
    
    The **Expiration date** field displays the date when the period that is set to collect the document package to confirm the right to use VAT at a rate of zero percent expires. If the tax authority does not confirm your right before the **Expiration date**, the taxpayer is obligated to calculate VAT by using the rate for **Tax code for domestic market**. This date is calculated according to the **Export date** value and the number of days in the export confirmation period.

5.  Close the form.

6.  Click **Accounts receivable** \> **Periodic** \> **Sales book** \> **Preliminary processing export factures**.

7.  Click **Select...** to select an export facture for processing from the current period with the operation type set to **VAT 0%**.
    

    > [!NOTE]
    > <P>The confirmation date of this export facture is before the expiration date. For more information, see <A href="rus-vat-operation-types-for-export-transactions.md">(RUS) VAT operation types for export transactions</A> and <A href="rus-perform-preliminary-processing-of-an-export-facture.md">(RUS) Perform preliminary processing of an export facture</A>.</P>



8.  Close the form.

9.  Click **Accounts receivable** \> **Periodic** \> **Sales book** \> **Parameters of VAT process**.

10. Press CTRL + N to define the parameters for all operation types. For more information, see [(RUS) Set up parameters for incoming VAT processing](rus-set-up-parameters-for-incoming-vat-processing.md).

11. Close the form.

12. Click **Accounts receivable** \> **Periodic** \> **Sales book** \> **Outgoing VAT processing**.

13. Click **Select...** to process the outgoing VAT transactions at a VAT rate of zero percent, and to create sales tax transactions.For more information,see [(RUS) Perform an outgoing VAT processing transaction](rus-perform-an-outgoing-vat-processing-transaction.md)

14. Close the form.

15. To view the processing of outgoing VAT, click **Periodic** \> **Sales book** \> **VAT processing log** to open the **VAT processing log** form. . For more information, see [(RUS) Perform an outgoing VAT processing transaction](rus-perform-an-outgoing-vat-processing-transaction.md)

16. Close the form.

17. Click **Accounts receivable** \> **Periodic** \> **Sales book** \> **Sales books journal**.

18. Press CTRL + N to create a new sales book and include the facture at a VAT rate of zero percent in the sales book. For more information, see [(RUS) Create a sales book](rus-create-a-sales-book.md).

19. Repeat steps 6 through 18 to process export factures for other operation types.

## See also

[(RUS) Define parameters for export operations](rus-define-parameters-for-export-operations.md)

[(RUS) Facture journal (form)](https://technet.microsoft.com/library/jj923567\(v=ax.60\))

[(RUS) Update facture (form)](https://technet.microsoft.com/library/jj889412\(v=ax.60\))

  


