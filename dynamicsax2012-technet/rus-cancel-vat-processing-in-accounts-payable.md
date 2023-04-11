---
title: (RUS) Cancel VAT processing in Accounts payable
TOCTitle: (RUS) Cancel VAT processing in Accounts payable
ms:assetid: fc1045ad-0fe0-4b17-9bc4-2926730d7210
ms:mtpsurl: https://technet.microsoft.com/library/JJ678646(v=AX.60)
ms:contentKeyID: 49388128
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Cancel VAT processing in Accounts payable 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



After processing VAT, you can cancel the processing results in part or in full. However, you can cancel only those vouchers with an open tax period.

1.  Click **Accounts payable** \> **Periodic** \> **Purchase book** \> **Canceling processed VAT**. form to open the **Purchase book (Canceling processed VAT)** form.

2.  Click **Select** to open the **Canceling processed VAT-select data for period** form, and then specify the criteria for creating a list of the factures that were used for VAT processing.

3.  In the **From date** and **To date** fields, specify the VAT processing period.

4.  Click **OK**. A list of factures is displayed in the **Purchase book (Canceling processed VAT)** form for which the VAT processing was done.
    

    > [!NOTE]
    > <P>The factures are displayed in the upper pane of the form. Tax distribution vouchers for each facture are shown in the lower section of the form. Only vouchers that pertain to the open tax period are canceled.</P>



5.  In the upper section of the form, select the **Marked** check box to select all factures for canceling.

6.  Click **Mark** \> **Mark all** to select all factures for canceling.
    
    –or–
    
    Click **Mark** \> **Unmark all** to clear the **Marked** check box for all lines in the form.

7.  Click **Post**. The VAT processing is canceled with the reversing refund or closure of VAT transactions in the ledger with the specified date.
    

    > [!NOTE]
    > <P>To view the VAT processing log, click Click <STRONG>Accounts payable</STRONG> &gt; <STRONG>Periodic</STRONG> &gt; <STRONG>Purchase book</STRONG> &gt; <STRONG>VAT processing log</STRONG>.</P>



## See also

[(RUS) VAT processing log (form)](https://technet.microsoft.com/library/jj923606\(v=ax.60\))

  


