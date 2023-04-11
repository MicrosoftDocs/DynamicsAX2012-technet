---
title: (LTU) Generate the fixed asset repair report
TOCTitle: (LTU) Generate the fixed asset repair report
ms:assetid: 516125d5-7e61-4281-b047-a8a4e046dcc7
ms:mtpsurl: https://technet.microsoft.com/library/JJ856109(v=AX.60)
ms:contentKeyID: 50406408
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- repair
- fixed asset
- fixed asset repair
- repair cost
- acquisition value
audience: Application User
ms.search.region: Lithuania
---

# (LTU) Generate the fixed asset repair report 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

When the repair cost for a fixed asset exceeds 50 percent of its acquisition value, the net balance value of the asset is increased by the repair amount. Therefore, comprehensive repair information is recorded for all fixed assets. You can print a report that contains information about the repair costs.

1.  Click **Fixed assets** \> **Reports** \> **Transactions** \> **Periodic** \> **Fixed assets repair**.

2.  In the **Value model** field, select the value model for which to generate the fixed asset report.

3.  Enter the start and end dates for the reporting period.

4.  To include repair transactions on the report, select the **Show report transactions** check box.

5.  In the **Print from repair percent** field, enter the percentage of the fixed asset’s acquisition value that can be spent on repairs before the fixed asset must be included on the report.
    
    The report includes only those fixed assets for which the ratio of repair costs to acquisition value is higher than the percentage you enter in this field.

6.  Click **Select** to enter any additional criteria to use to select fixed assets to include on the report.

7.  Click **OK** to generate the report.

## See also

[(LTU) Repair (form)](https://technet.microsoft.com/library/jj665105\(v=ax.60\))

  


