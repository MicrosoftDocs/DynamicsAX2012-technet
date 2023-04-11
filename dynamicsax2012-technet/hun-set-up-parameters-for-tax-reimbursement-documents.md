---
title: (HUN) Set up parameters for tax reimbursement documents
TOCTitle: (HUN) Set up parameters for tax reimbursement documents
ms:assetid: e117a608-cf6a-4af8-a9a8-adebce1501d2
ms:mtpsurl: https://technet.microsoft.com/library/JJ664392(v=AX.60)
ms:contentKeyID: 49385480
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Hungary
---

# (HUN) Set up parameters for tax reimbursement documents 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

A customer might be a person who resides in a country/region that is not a member of the European Union (EU). A customer of this kind might request reimbursement of value-added tax (VAT) that was paid on purchases in Hungary. The customer might also ask you to provide documentation for the amount of VAT that he or she paid to you. You can create a tax reimbursement document from the customer invoice. For more information, see [(HUN) Create and print a tax reimbursement document](hun-create-and-print-a-tax-reimbursement-document.md).

Use these procedures to set up parameters for tax reimbursement documents.

## Set up a default exchange rate

Use this procedure to set up an exchange rate that is automatically selected in tax reimbursement documents.

1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  In the **Accounts receivable parameters** form, in the left pane, click **Updates**.

3.  In the **Tax reimbursement slip** field, select the type of exchange rate to use by default for tax reimbursement documents. For more information about exchange rate types, see [Exchange rate types (form)](https://technet.microsoft.com/library/hh242857\(v=ax.60\)).

## Set up a number sequence

Use this procedure to set up a number sequence that is automatically assigned to tax reimbursement documents.

1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  In the **Accounts receivable parameters** form, in the left pane, click **Number sequences**.

3.  In the **Reference** field, select **Tax reimbursement document**.

4.  In the **Number sequence code** field, select a number sequence for tax reimbursement documents.

5.  Complete the remaining optional fields. For more information, see [Accounts receivable parameters (form)](https://technet.microsoft.com/library/aa576993\(v=ax.60\)).

## See also

[(HUN) Accounts receivable parameters (modified form)](https://technet.microsoft.com/library/jj714534\(v=ax.60\))

[Setting up and maintaining Accounts receivable](setting-up-and-maintaining-accounts-receivable.md)

  


