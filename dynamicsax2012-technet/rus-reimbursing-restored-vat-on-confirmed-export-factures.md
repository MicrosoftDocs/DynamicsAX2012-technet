---
title: (RUS) Reimbursing restored VAT on confirmed export factures
TOCTitle: (RUS) Reimbursing restored VAT on confirmed export factures
ms:assetid: 3b9dbee6-214d-4fcd-b90f-85554ea53d9f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ839660(v=AX.60)
ms:contentKeyID: 50396807
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Reimbursing restored VAT on confirmed export factures 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You must calculate restored value-added tax (VAT) for confirmed export factures before you can reimburse the restored VAT. For more information about calculating restored VAT, see [(RUS) Calculate restored VAT and revenue amounts](rus-calculate-restored-vat-and-revenue-amounts.md). Complete the following tasks to reimburse restored VAT for a confirmed export facture:

  - Create, post, and update the facture for an item.

  - Create an export facture. For more information, see [(RUS) Create an export facture](rus-create-an-export-facture.md).

  - Process the incoming VAT. If the restored VAT amount for the period is not approved in the **VAT restoring journal** form, standard VAT processing is performed. If the restored VAT for the period is approved, the restored VAT is reimbursed.

  - Close inventory.

  - Calculate restored VAT amounts. For more information, see [(RUS) Calculate restored VAT and revenue amounts](rus-calculate-restored-vat-and-revenue-amounts.md).

  - Process the outgoing VAT[(RUS) Perform an outgoing VAT processing transaction](rus-perform-an-outgoing-vat-processing-transaction.md).
    

    > [!NOTE]
    > <P>When you process outgoing VAT for exports, tax-exempt activity, and fixed assets, only factures for the approved period are selected. Factures for restoring VAT cannot be locked.</P>



  - Confirm the export VAT for the facture, and process the export factures. For more information, see [(RUS) Create an export facture](rus-create-an-export-facture.md).
    

    > [!NOTE]
    > <P>Factures with the operation types <STRONG>VAT 0%</STRONG>, <STRONG>VAT 0% with correction</STRONG>, and <STRONG>Overdue confirmation</STRONG> are included in the current VAT processing. When export factures are not confirmed, factures with the operation types <STRONG>Unconfirmed VAT 0%</STRONG> and <STRONG>Unconfirmed VAT 0% with correction</STRONG> are included in the current VAT processing.</P>



  - Close the sales book and purchase book. You can close the sales book and purchase book only after approving the restored VAT amount for the period. All incoming and outgoing VAT for factures must be processed before you close the book. For more information, see [(RUS) Create a sales book](rus-create-a-sales-book.md) and [(RUS) Create a purchase book](rus-create-a-purchase-book.md).

  


