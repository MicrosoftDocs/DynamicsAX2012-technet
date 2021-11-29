---
title: Set up dependent cash flow forecasts in main accounts
TOCTitle: Set up dependent cash flow forecasts in main accounts
ms:assetid: 7b1e6575-4d09-48bc-9373-bc22f42bc35c
ms:mtpsurl: https://technet.microsoft.com/library/Aa550077(v=AX.60)
ms:contentKeyID: 36058254
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up dependent cash flow forecasts in main accounts 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can set up a dependent cash flow forecast for a main account that contains transactions that are directly related to transactions in another main account. For example, expected sales tax payments directly follow the expected transaction amounts in vendor accounts.

1.  Click **General ledger** \> **Setup** \> **Chart of accounts** \> **Chart of accounts**.

2.  Double-click the main account that contains transactions that directly affect another main account, such as a main account for purchases. This account is the primary main account. Any transactions that are forecast for this account generate a corresponding increase in a dependent main account, such as the main account for sales tax payments.

3.  Select **Legal entities** in the **Select the level of main account to display** field and select a legal entity.

4.  On the **Setup** tab, click **Cash flow forecast**.

5.  In the **Set up cash flow forecasts** form, press CRTL+N to create a new line, if you have to.

6.  In the **Main account** lookup field, enter the main account that is affected by transactions in the primary main account.

7.  In the other fields on the line, enter or select appropriate values. You can change the value displayed in the **Percent** text box to reflect the effect of primary main account on the dependent main account.

8.  If transactions to the primary main account affect the amounts in yet another main account, create another line, and enter or select appropriate values in the relevant fields.

9.  Each line that you add creates a cash flow forecast amount in a dependent main account that is a percentage of cash flow amounts to the primary main account that you selected in the **Chart of accounts** form in step 2.

## See also

[Set up cash flow forecasts (form)](https://technet.microsoft.com/library/aa556922\(v=ax.60\))

  


