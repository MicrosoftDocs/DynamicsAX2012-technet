---
title: Evaluate the closing setup
TOCTitle: Evaluate the closing setup
ms:assetid: 565bc4a0-8065-417d-aa81-c5843eb92fcf
ms:mtpsurl: https://technet.microsoft.com/library/Aa549054(v=AX.60)
ms:contentKeyID: 37835227
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Evaluate the closing setup 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You should review the following settings before you close the fiscal year. You cannot change some of these settings after you start the year-end closing processes.

1.  Click **General ledger** \> **Setup** \> **Chart of accounts** \> **Chart of accounts**.

2.  Select a chart of accounts. On the **Main accounts** FastTab, click **Edit**.

3.  For each main account that could be subject to adjustments, verify that you have selected the correct option in the **Close** field on the **General** FastTab. This field value determines which field will display adjustments to the account balance. These fields are in the **Totals** field group in the **Closing sheet** form.

4.  Click **General ledger** \> **Setup** \> **General ledger parameters**.

5.  In the **Ledger** area, verify the field values on the **Fiscal year close** FastTab.
    

    > [!NOTE]
    > <P>The <STRONG>Delete close-of-year transactions during transfer</STRONG> check box might be cleared during the closing process. If this occurs, opening transactions and system-generated closing transactions that exist for the year that is being closed will not be deleted when the transfer is processed again in the <STRONG>Opening transactions</STRONG> form. You can select the <STRONG>Delete close-of-year transactions during transfer</STRONG> check box in the <STRONG>General ledger parameters</STRONG> form before you complete the closing process again.</P>



For information about the other fields in the **General ledger parameters** form, see [General ledger parameters (form)](https://technet.microsoft.com/library/aa557286\(v=ax.60\)).

## See also

[Fiscal year closing checklist](fiscal-year-closing-checklist.md)

  


