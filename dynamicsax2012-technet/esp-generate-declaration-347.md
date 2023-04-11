---
title: (ESP) Generate Declaration 347
TOCTitle: (ESP) Generate Declaration 347
ms:assetid: 36b5b6f9-f543-4640-8569-721a243d0d96
ms:mtpsurl: https://technet.microsoft.com/library/Dn304970(v=AX.60)
ms:contentKeyID: 54899949
author: tonyafehr
ms.date: 05/09/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.TaxReport347Table
- Forms.Dialog
- ES - 00003
audience: Application User
ms.search.region: Spain
---

# (ESP) Generate Declaration 347 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012_

Use the **Transactions** form to modify the information for the customer transactions and vendor transactions before you generate the report as an ASCII file.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 3 for AX 2012.</P>



1.  Click **General ledger** \> **Periodic** \> **Report 347** \> **Declaration 347**.

2.  In the **Declaration 347** form, click **Generate** to open the **Declaration 347** dialog box. For more information, see [(ESP) Generate declaration 347 (class form)](https://technet.microsoft.com/library/aa589594\(v=ax.60\)).

3.  Specify the criteria for transferring the transactions to the **Declaration 347** form. For more information, see [(ESP) Generate the Declaration 347 report](esp-generate-the-declaration-347-report.md).

4.  Click **OK** to transfer the transactions.

5.  In the **Declaration 347** form, click **Transactions** to verify the customer transactions and vendor transactions for the report. For more information, see [(ESP) Declaration 347 transactions (form)](https://technet.microsoft.com/library/aa587699\(v=ax.60\)).

6.  On the **General** tab, in the **Amounts in cash** field, modify the total cash amount for the transaction, if required.

7.  In the **Invoice year for cash** field, modify the year of the invoice that is associated with cash payments in the transaction line, if required. By grouping the transactions by year, you can calculate the total cash amount that is collected from a customer in that year.
    

    > [!NOTE]
    > <P>This field is available only when the cash amount is entered in the <STRONG>Amounts in cash</STRONG> field.</P>



8.  Close the form.

9.  In the **Declaration 347** form, click **Output**, and then click **Export to ASCII file**.

10. In the **Export to ASCII file** dialog box, enter the path and file name for the ASCII file.

11. Click **OK** to generate the Declaration 347 report.

  


