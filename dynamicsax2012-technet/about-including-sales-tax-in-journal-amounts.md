---
title: About including sales tax in journal amounts
TOCTitle: About including sales tax in journal amounts
ms:assetid: 220f9c76-2e03-4a52-8d28-0eca0c0c3860
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa496794(v=AX.60)
ms:contentKeyID: 39519066
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- sales tax in journals
audience: Application User
ms.search.region: Global
---

# About including sales tax in journal amounts 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can indicate whether the amounts that are entered in journals include sales tax.

You can specify this setting in the following forms:

  - **General ledger parameters** form – Select or clear the **Amounts include sales tax** check box. This becomes the default setting for all journals, unless the setting is specified for a specific journal or journal name.

  - **Journal names** form – Select or clear the **Amounts include sales tax** check box to override the default setting in the **General ledger parameters** form for lines in journals that use this journal name.

  - Individual journal forms – Select or clear the **Amounts include sales tax** check box in individual journal forms to override the default settings in the **Journal names** and **General ledger parameters** forms. This check box is usually on the **Setup** tab.

The setting with the highest priority is used for journals and journal lines as they are created. However, you can select or clear the **Amounts include sales tax** check boxes at any time.

If you select the **Amounts include sales tax** check box, you must enter gross amounts in journals. Sales taxes are calculated based on the gross amounts, and are posted to the sales tax account. The net amount is posted to the ledger account that is entered in the journal.

If you do not select the **Amounts include sales tax** check box, you must enter net amounts in journals. The net amount is posted to the ledger account that is entered in the journal. The sales taxes are calculated based on the net amount, and are posted automatically.

**Example**

Sales tax is 10 percent, and the **Amount in the journal includes sales tax** check box is selected.

The total invoice amount is 110.00, which you enter in the appropriate **Debit** or **Credit** field in a journal. This amount includes the sales tax.

This information is used to calculate the net amount and the sales tax amount. In this example, the net amount is 100.00 (110.00 / 1.10), and the sales tax amount is 10.00.

  


