---
title: (IND) Calculate service tax by using the Free text invoice form
TOCTitle: (IND) Calculate service tax by using the Free text invoice form
ms:assetid: 1efe9daf-48df-45bf-9fe8-e7a864bf0a30
ms:mtpsurl: https://technet.microsoft.com/library/JJ664541(v=AX.60)
ms:contentKeyID: 49385620
author: Khairunj
ms.date: 05/06/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.CustFreeInvoice
audience: Application User
ms.search.region: India
---

# (IND) Calculate service tax by using the Free text invoice form 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012_

Use the **Free text invoice** form to create and post a free text invoice for which service tax is calculated. You can specify the service code for each invoice line before you post the free text invoice.

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  Select or create a free text invoice, and then select or create invoice lines. For more information, see [Key tasks: Free text invoices](key-tasks-free-text-invoices.md).

3.  In the **Free text invoice** form, in the **Invoice lines** area, in the **Sales tax group** and **Item sales tax group** fields, select the sales tax group and item sales tax group for the invoice line. The sales tax group and the item sales tax group for a journal line must contain tax codes that have a tax type of **Service tax**.

4.  On the **Line details** FastTab, on the **Tax information** tab, in the **Company information** field group, in the **Location** field, modify the location of the legal entity, if necessary. The address of the legal entity is updated in the **Address** field.

5.  In the **STC number** field, select the service tax code (STC) number of the legal entity. The ledger accounts for posting the service tax amounts are identified by the STC number.

6.  In the **Service code** field, select the service code for the invoice line.
    

    > [!NOTE]
    > <P>In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2: The accounting code for the service is updated in the <STRONG>Accounting code</STRONG> field based on the service code that you select. For more information, see <A href="ind-set-up-service-codes-for-service-goods.md">(IND) Set up service codes for service goods</A>.</P>



7.  Post the free text invoice.
    

    > [!NOTE]
    > <P>If you post the invoice first, the service tax amounts that are calculated for the invoice lines are credited to the service tax payable accounts as defined in the tax ledger posting group for the STC number. If you make the payment first, the service tax amounts are posted to the interim service tax payable accounts.</P>



## See also

[(IND) Free text invoice (modified form)](https://technet.microsoft.com/library/jj664875\(v=ax.60\))

[(IND) Service codes (form)](https://technet.microsoft.com/library/jj664830\(v=ax.60\))

  


