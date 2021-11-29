---
title: (EST) Set up the export of telebank payments to vendors
TOCTitle: (EST) Set up the export of telebank payments to vendors
ms:assetid: f3fec70a-6484-45b7-913e-4f5864e747b0
ms:mtpsurl: https://technet.microsoft.com/library/JJ664208(v=AX.60)
ms:contentKeyID: 49385299
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Estonia
---

# (EST) Set up the export of telebank payments to vendors 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can export telebank payments that are made to vendors, and import the payments into the accounts receivable payment journal. Exported telebank payments can use any of the generally accepted telebanking formats: Teleteenus (EE) v. 2.3, Telehansa (EE) v. 5.116, or Telehansa (INT) v. 5.116. The imported payments are linked to specific vendor invoices by using reference numbers.

1.  Click **Accounts payable** \> **Setup** \> **Payment** \> **Methods of payment**.

2.  Select a method of payment. To create a method of payment, click **New**, and then enter the required details.

3.  On the **File formats** FastTab, click **Setup** to open the **File formats for methods of payment** form.

4.  On the **Export** tab, in the **Available** list, select **Telehansa (EE) v. 5.116**, and then click **\<** to add this file format to the **Selected** list.

5.  Close the **File formats for methods of payment** form to return to the **Methods of payment - vendors** form.

6.  On the **File formats** FastTab, in the **Export format** field, select the **Telehansa (EE) v. 5.116** file format.

7.  Repeat steps 2 through 6 for the **Telehansa (INT) v. 5.116** and **Teleteenus (EE) v. 2.3** file formats.

## See also

[(EST) Set up the import of telebank payments from customers](est-set-up-the-import-of-telebank-payments-from-customers.md)

[(EST) File formats for methods of payment (form)](https://technet.microsoft.com/library/jj710825\(v=ax.60\))

  


