---
title: Configure settings for adjustment transactions
TOCTitle: Configure settings for adjustment transactions
ms:assetid: 964b064e-9b96-4bca-9793-5145448847fb
ms:mtpsurl: https://technet.microsoft.com/library/Hh209399(v=AX.60)
ms:contentKeyID: 36058628
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- transaction status
- adjustment transactions
audience: Application User
ms.search.region: Global
---

# Configure settings for adjustment transactions 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In the **Project parameters** form, you can configure settings that determine how Microsoft Dynamics AX handles transaction adjustments in your organization. These settings determine which kinds of transactions may be adjusted, based on their transactions status. They also determine whether the original transaction date or the adjustment date is used as the project date for adjusted transactions.

Your selections here determine which types of transaction status can be searched for in the **Create adjustment transactions** form when someone in your organization is adjusting a transaction.

1.  Click **Project management and accounting** \> **Setup** \> **Project management and accounting parameters**.

2.  In the **Project parameters** form, click the **General** link, and then in the **Allow adjustment of transaction status** area, select the check box for each transaction status for which you want to enable adjustments.

3.  If you want new transactions to be created whenever an adjustment is posted, select the **Always create adjustment transaction** check box.

4.  If you want related fields to be updated automatically when a field is being edited in the lower set of tabs in the **Adjustment** form, select the **Autoupdate field** check box.

5.  If you want an adjusted transaction to be dated with the adjustment date instead of the project date, select the **Use adjustment date as new project date** check box.

## See also

[View transaction adjustment history](view-transaction-adjustment-history.md)

[Adjust transactions](adjust-transactions.md)

[Project management and accounting parameters (form)](https://technet.microsoft.com/library/aa599440\(v=ax.60\))

[Create adjustment transactions (class form)](https://technet.microsoft.com/library/aa634561\(v=ax.60\))

  


