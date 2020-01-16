---
title: (POL) Set up credit note parameters
TOCTitle: (POL) Set up credit note parameters
ms:assetid: 7c818026-0a6b-44ea-8ea6-b55d5abd54e4
ms:mtpsurl: https://technet.microsoft.com/library/JJ678253(v=AX.60)
ms:contentKeyID: 49386975
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Poland
---

# (POL) Set up credit note parameters 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In Poland, you must print credit notes in a specified format. A credit note must contain a reference to the original invoice, all corrected and corrective lines, and the reason that the correction was made. A corrected line is the original invoice line with a negative sign, and cannot be modified. A corrective line is the original invoice line with a positive sign, which can be modified.

A corrective invoice with a positive amount is treated as a credit note.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  In the **Accounts receivable parameters** form, click the **Updates** link. In the **Invoice** field group, select the **Credit note as correction** check box. This enables the transfer of required information from the original invoice to the credit note.

3.  Press CTRL+S or close the form.

4.  Click **Accounts receivable** \> **Setup** \> **Customers** \> **Customer reasons**.

5.  In the **Customer reasons** form, click **New**.

6.  In the **Reason code** field, enter a unique name for the reason to use for a credit note.

7.  In the **Default comment** field, enter a description of the reason for creating the credit note.

8.  Select the **Customer** check box to use the reason code for customer transactions.

## See also

[(EEUR) Create a credit note for correction](eeur-create-a-credit-note-for-correction.md)

[(POL) Accounts receivable parameters (modified form)](https://technet.microsoft.com/library/jj678183\(v=ax.60\))

[(POL) Reason (modified form)](https://technet.microsoft.com/library/jj678160\(v=ax.60\))

  


