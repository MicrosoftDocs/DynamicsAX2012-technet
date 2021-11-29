---
title: (LVA) Generate a fixed asset disposal statement
TOCTitle: (LVA) Generate a fixed asset disposal statement
ms:assetid: 444c3976-a11a-4f6f-91cf-959d387ea1d7
ms:mtpsurl: https://technet.microsoft.com/library/JJ853407(v=AX.60)
ms:contentKeyID: 50396777
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- scrap
- fixed asset
- disposal
- statement
- disposal statement
audience: Application User
ms.search.region: Latvia
---

# (LVA) Generate a fixed asset disposal statement 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The fixed asset disposal statement is a primary accounting document that provides a certified list of the fixed assets that your organization disposed of by sale or as scrap.

1.  Click **Fixed assets** \> **Journals** \> **Fixed assets**.

2.  Click **New**, and then enter the required details.
    
    For more information, see [Journal header (form)](https://technet.microsoft.com/library/aa557917\(v=ax.60\)).

3.  Click **Lines**, and then, in the **Journal voucher** form, click **New**.

4.  In the **Transaction type** field, select **Disposal - sale** or **Disposal - scrap**.

5.  In the **Document** field, enter the number of the fixed asset document that the voucher was generated from.

6.  Click **Post** \> **Post** to post the journal.

7.  Click **Fixed assets** \> **Common** \> **Fixed assets** \> **Fixed assets**.

8.  Select the fixed asset record, and then, on the **Action Pane**, click **Value models**.

9.  In the **Value models** form, click **Transactions**.

10. In the **Fixed asset transactions** form, select the transaction, and then click **Print** \> **Fixed asset disposal statement**.

11. In the **Fixed asset disposal statement** report form, in the **Document number** field, enter the fixed asset document number to include in the printed report.

12. In the **Document date** field, select the date on which the document was generated.

13. Click **OK** to generate the **Fixed asset disposal statement** report.

## See also

[Value models (form)](https://technet.microsoft.com/library/aa590830\(v=ax.60\))

[Journal voucher - Fixed assets (form)](https://technet.microsoft.com/library/aa620564\(v=ax.60\))

  


