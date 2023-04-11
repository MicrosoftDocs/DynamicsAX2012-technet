---
title: (RUS) Define parameters for export operations
TOCTitle: (RUS) Define parameters for export operations
ms:assetid: a026e494-c77b-4433-936f-7619d7f2c50b
ms:mtpsurl: https://technet.microsoft.com/library/JJ678546(v=AX.60)
ms:contentKeyID: 49387775
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- parameter
- Export transaction
audience: Application User
ms.search.region: Russia
---

# (RUS) Define parameters for export operations 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You must set up the parameters for export transactions in the **Accounts receivable** and **General ledger** modules before you can create the export transactions. Use the following procedures to set the default operation type for the preliminary processing of transactions, the sales tax type, the sales tax code for the local market, and the period that is required for the collection of data for the value-added tax (VAT) declaration during export operations.

## Set up the default operation type for an export facture

1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  In the **Accounts receivable parameters** form, in the left pane, click **Ledger and sales tax**.

3.  In the **Ledger and sales tax** area, on the **General** FastTab, in the **Operation type** field, select **VAT 0%** or **Unconfirmed VAT 0%** as the default operation type for preliminary facture processing.

## Set up the sales tax codes for export operations

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax codes**.

2.  Press CTRL+N to create a new sales tax code.

3.  In the **Sales tax code** field, enter a code for the sales tax.

4.  In the **Type of tax** field, select **VAT 0%**.

5.  On the **General** tab, in the **Settlement period** field, select the interval at which the tax is calculated and paid to the tax authority.
    

    > [!NOTE]
    > <P>Select the settlement period whose tax reporting date is specified in the <STRONG>Reporting date</STRONG> field in the <STRONG>Sales tax settlement periods</STRONG> form.</P>



6.  In the **Ledger posting group** field, select the ledger posting group for the sales tax code.

7.  In the **Tax code for domestic market** field, select the sales tax code that is used for internal market operations.

8.  In the **VAT operation code** field, select the operation code that is used to collect the document package that confirms the VAT declaration. For more information, see [Sales tax codes (form)](https://technet.microsoft.com/library/aa553257\(v=ax.60\)).

9.  Close the form.

10. Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax groups**.

11. Press CTRL+N to create a sales tax group, and then enter the necessary information. For more information, see [Sales tax groups (form)](https://technet.microsoft.com/library/aa498345\(v=ax.60\)).

12. On the **Setup** tab, in the **Sales tax code** field, select the sales tax code that you created in steps 1 through 8.

13. Close the form.

14. Click **General ledger** \> **Setup** \> **Sales tax** \> **Item sales tax groups**.

15. Press CTRL+N to create an item sales tax group, and then enter the necessary information. For more information, see [Item sales tax groups (form)](https://technet.microsoft.com/library/aa615960\(v=ax.60\)).

16. On the **Setup** tab, in the **Sales tax code** field, select the sales tax code that you created in steps 1 through 8.

## Set up the export confirmation period

1.  Click **Accounts receivable** \> **Setup** \> **Period of documents collection**.

2.  In the **From date** field, select the start date from which the number of days required for the export confirmation period begins.

3.  In the **Export confirmation period** field, enter the number of days that are allowed for the preparation of the documents that confirm the VAT at zero percent for the export of items.
    

    > [!NOTE]
    > <P>The maximum number of days that is allowed for the export confirmation period is 180.</P>



## See also

[(RUS) Create an export facture](rus-create-an-export-facture.md)

[(RUS) Perform preliminary processing of an export facture](rus-perform-preliminary-processing-of-an-export-facture.md)

[(RUS) Perform an outgoing VAT processing transaction](rus-perform-an-outgoing-vat-processing-transaction.md)

[(RUS) Accounts receivable parameters (modified form)](https://technet.microsoft.com/library/jj733289\(v=ax.60\))

[(RUS) Sales tax settlement periods (modified form)](https://technet.microsoft.com/library/jj711340\(v=ax.60\))

  


