---
title: (SWE) Export financial information for auditors
TOCTitle: (SWE) Export financial information for auditors
ms:assetid: 30e4ed09-a7e1-4542-a93e-a16a33578497
ms:mtpsurl: https://technet.microsoft.com/library/Gg231030(v=AX.60)
ms:contentKeyID: 36056322
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Sweden
---

# (SWE) Export financial information for auditors 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can export financial data using the formats specified by the Standard Import Export Group (SIE), the organization in Sweden that develops standard formats. Before you export data, you must set up a three-digit Standardiserad Räkenskaps Utdrag (SRU) code for each general ledger account. For more information, see [(SWE) Set up SRU codes for ledger accounts](swe-set-up-sru-codes-for-ledger-accounts.md).

1.  Click **General ledger** \> **Periodic** \> **SIE export**.

2.  Enter the file name and location to create the SIE file.

3.  Using the **From date** and **To date** fields, select the range of financial information to include in the export file.

4.  Enter a budget model to include in the export file.

5.  In the **SIE file type** field, select one of the following options:
    
      - **SIE type 2** – Exports year-end balances and period balances.
    
      - **SIE type 3** – Exports dimension balances.
    
      - **SIE type 4I** – Exports transactions.
    
      - **SIE type 4E** – Exports period balances and transactions.

6.  To include the chart of accounts in the export file, select the **Include chart of accounts** check box.

7.  To include the whole account name in the export file, select the **Full name of account** check box.
    

    > [!NOTE]
    > <P>By default, only the first 30 characters of the account name are included in the export file.</P>



8.  Click **OK**.

## See also

[Export of SIE file (form)](https://technet.microsoft.com/library/bb147523\(v=ax.60\))

  


