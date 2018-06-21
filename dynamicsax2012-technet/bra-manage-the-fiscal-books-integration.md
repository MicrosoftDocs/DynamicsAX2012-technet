---
title: (BRA) Manage the fiscal books integration
TOCTitle: (BRA) Manage the fiscal books integration
ms:assetid: b6d06caa-5dbb-4060-97ab-4a3cc90a9b9e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn305880(v=AX.60)
ms:contentKeyID: 54912981
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.FBBookingPeriodListPage_BR
- Forms.FBFiscalDocument_BR
- MsDynAx060.Forms.FBBookingPeriodListPage_BR
- MsDynAx060.Forms.FBFiscalDocument_BR
---

# (BRA) Manage the fiscal books integration [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The fiscal books integration allows users to generate SPED Fiscal obligations and Sped EFD contribution for transactions originating in Microsoft Dynamics AX 2009 or other software packages. After the integration is complete, all fiscal documents are transferred automatically into Microsoft Dynamics AX 2012 R2. The integration functionality is included in the hotfix that is available in Knowledge base article 2850595 and Knowledge base article 2839295.


> [!NOTE]
> <P>This topic applies only if KB 2839295 and KB 2850595 for Microsoft Dynamics AX 2012 R2 are installed, if cumulative update 6 or later for AX 2012 R2 is installed, or if AX 2012 R3 is installed.</P>



## Process overview

The Fiscal books integration lets you do the following things:

  - Manage your business in Microsoft Dynamics AX 2009. As transactions are processed, fiscal documents and inventory transactions are created.

  - Periodically, transfer fiscal documents and inventory transactions to Microsoft Dynamics AX 2012 R2. When you transfer the fiscal documents and inventory transactions, they go into a staging area. You can review them and correct any errors that you find while the fiscal documents and inventory transactions are in this staging area.

  - When you are satisfied that all errors have been corrected, validate the fiscal documents and inventory transactions. Then you can create booking periods and perform other fiscal books and tax reporting tasks in Microsoft Dynamics AX 2012 R2.

## Staging area

To view the fiscal documents that were transferred as part of the integration:

1.  Click **Fiscal books** \> **Periodic** \> **Staging** \>**All staged fiscal documents**.

2.  In the **All staged fiscal documents** form you can:
    
      - Edit or delete fiscal documents.
    
      - Validate a specific fiscal document or all fiscal documents in the list.
    
      - View referenced fiscal documents, complementary information or error messages that are attached to the fiscal document.

## Process staging area

The fiscal documents must be posted into the fiscal document framework before users can use Fiscal books.

To post the fiscal documents with a validation status of **Valid** into the Microsoft Dynamics AX 2012 R2 fiscal document framework:

1.  Click **Fiscal books** \> **Periodic** \> **Staging** \>\> **Process staging data**.

2.  Click **OK**.

3.  To view the fiscal documents on the **All fiscal documents** list page after they are posted into the fiscal document framework, click **General ledger** \> **Inquiries** \> **Fiscal documents** \> **All fiscal documents**.

## Staged inventory on hand

As part of the transfer process from your existing Microsoft Dynamics AX 2009 to Microsoft Dynamics AX 2012 R2, the integration transfers the inventory position and all the related transactions to a specific staging area.

1.  Click **Fiscal books** \> **Periodic** \>**Staging**\> **All staged inventory on hand**.

2.  The **Inventory on hand** form displays the inventory position per fiscal establishment and the related fiscal information for an item.

3.  You can validate a specific fiscal document or all fiscal documents that are available.

## Fiscal receipts

The integration process transfers fiscal receipts that were generated in the Retail module in Microsoft Dynamics AX 2009.

1.  Click **Fiscal books** \> **Periodic** \> **Staging** \> **All staged fiscal receipts**.

2.  The process of staging data will collect the transactions with a validation status of **Valid** to post into the Fiscal document framework data source.

## Z reports

The integration process also transfers the Z reports that are generated in the Retail module in Microsoft Dynamics AX 2009. You can validate the Z Reports that are transferred and fix the any errors.

## See also

[Fiscal books integration](http://go.microsoft.com/fwlink/?linkid=306013)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

