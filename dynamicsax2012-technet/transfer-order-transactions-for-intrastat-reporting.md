---
title: Transfer order transactions for Intrastat reporting
TOCTitle: Transfer order transactions for Intrastat reporting
ms:assetid: 4d730f63-f684-47db-b8a9-ebf9df151610
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn304976(v=AX.60)
ms:contentKeyID: 54899962
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Transfer order transactions for Intrastat reporting 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012_

You can include Intrastat transactions for the internal transfer of items for a European Union (EU) legal entity on the Intrastat report. To include transfer order transactions on the Intrastat report, complete the following tasks:

1.  Set up foreign trade parameters for transfer orders.

2.  Create, ship, and receive transfer orders by specifying Intrastat details.

3.  Generate an Intrastat report that includes transfer order transactions.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 6 for AX 2012 R2.</P>



## What transactions can I include on an Intrastat report?

You can include the following types of Intrastat transactions on an Intrastat report:

  - Free text invoices

  - Customer invoices

  - Customer packing slips

  - Vendor invoices

  - Vendor product receipts

  - Project invoices

  - Transfer orders

## Are there any parameters that I need set to include transfer orders on the Intrastat report?

Yes. You must create a transaction code for transfer orders, and then select that transaction code in the **Transfer order** field on the **Foreign trade parameters** form. For more information, see [Set up and transfer the transfer order transactions for Intrastat reporting](set-up-and-transfer-the-transfer-order-transactions-for-intrastat-reporting.md).

## Where can I set up the Intrastat information for a transfer order?

You can specify the Intrastat information for a transfer order on the **Foreign trade** tab in the upper pane in the **Transfer orders** form. You can also specify the Intrastat details for a transfer order line on the **Foreign trade** tab in the lower pane in the **Transfer orders** form.

## On what basis does the Intrastat generation process operate?

The Intrastat generation process operates based on the countries that are specified on the **From warehouse** and **To warehouse** fields in the **Transfer orders** form. The process also considers the scrapped quantity for arrivals.

## Which countries does this update apply to?

This update applies to the following European countries:

  - Austria

  - Belgium

  - Czech Republic

  - Denmark

  - Estonia

  - Finland

  - France

  - Germany

  - Hungary

  - Italy

  - Latvia

  - Lithuania

  - Netherlands

  - Poland

  - Spain

  - Sweden

  - United Kingdom

## Don't see your question here?

We're working to include as many questions as we can, so that Microsoft Dynamics AX Help will be more useful to people just like you.

Tell us what question you would like to add to this topic. Send email to <adocs@microsoft.com>.

## See also

[About Intrastat](about-intrastat.md)

  


