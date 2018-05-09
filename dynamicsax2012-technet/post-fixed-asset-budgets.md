---
title: Post fixed asset budgets
TOCTitle: Post fixed asset budgets
ms:assetid: 5b106fcc-0872-4a80-b57b-cdf544e11d0f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa549083(v=AX.60)
ms:contentKeyID: 36057357
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Post fixed asset budgets 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can create budgets for fixed asset value models and generate a budget-related depreciation proposal that corresponds to the depreciation proposal in the fixed asset ledger journal.

To update fixed asset budgets in General ledger, the same accounts as the accounts that are set up for realized fixed asset transactions are used for posting. These are the accounts from the **Fixed asset posting profiles** form. The transaction type of the budget account entry, together with the fixed asset and the value model of the budget journal line, will be used to update the accounts in the posting profile.

Use the **Journal voucher** form to post fixed asset budget journals. For more information, see [Journal voucher - Fixed asset budget (form)](https://technet.microsoft.com/en-us/library/aa585887\(v=ax.60\)).

1.  Click **Fixed assets** \> **Journals** \> **Fixed asset budget**. Select the fixed asset budget journal to post and then click **Lines**. Click **Post** and then click one of the following options.
    
      - Click **Transfer to fixed asset budget** to transfer lines as budget register entries to fixed asset budgets.
    
      - Click **Transfer to fixed asset and ledger budget** to transfer lines as budget register entries to fixed asset budgets and ledger budgets.

2.  To view and transfer fixed asset budget journals to the ledger, use the **Fixed assets budget register entries** form. (Click **Fixed assets** \> **Inquiries** \> **Fixed assets budget register entries**. Click **Transfer**.)

3.  To view fixed asset budget journals, print the **Future value of fixed assets** report. (Click **Fixed assets** \> **Reports** \> **Budget** \> **Future value of fixed assets**.)

## See also

[Post fixed asset journals](post-fixed-asset-journals.md)

[Fixed assets budget register entries (form)](https://technet.microsoft.com/en-us/library/aa577095\(v=ax.60\))

[Future value of fixed asset report (AssetFutureValue)](future-value-of-fixed-asset-report-assetfuturevalue.md)

[Budget model (form)](https://technet.microsoft.com/en-us/library/aa586905\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

