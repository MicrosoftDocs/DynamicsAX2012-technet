---
title: (RUS) Set up tax rates
TOCTitle: (RUS) Set up tax rates
ms:assetid: ffc9eece-c934-467d-8f31-0e48ea4a897c
ms:mtpsurl: https://technet.microsoft.com/library/JJ678660(v=AX.60)
ms:contentKeyID: 49388142
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up tax rates 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Tax rates are used in calculating a register line, and these rates are set up in special rate directories rather than in the calculation algorithm.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Setup** \> **Profit tax** \> **Rates**.

2.  In the upper pane, press CTRL+N to create a new line.

3.  In the **Rate code** field, enter the identification of the rate.

4.  In the **Description** field, enter a description of the rate.

5.  In the **Calculation method** field, select a rate calculation method from the following options:
    
      - **Whole amount** – The value is calculated for the whole amount. The line value does not depend on the amount.
    
      - **Interval** – The value is calculated for intervals. The line value is defined depending on the amount.

6.  In the lower pane, press CTRL+N to create a new line. The tabs and fields displayed in the form are based on the calculation method that you select.

7.  If you select the **Whole amount** calculation method, enter the starting date for the value going into effect in the **Start date** field.

8.  In the **Value** field, enter the rate value.

9.  If you select the **Interval** calculation method, enter the starting date in the **Start date** field.

10. In the **Criterion type** field, select **Minimum** or **Maximum** as the criterion type for calculating the rate.

11. Click the **Intervals** tab, and, in the **For amount** field, enter the amount for which you want to apply the rate.

12. In the **Value** field, enter the rate value.

13. Press CTRL+S or close the form.

## See also

[(RUS) Rates (form)](https://technet.microsoft.com/library/jj856179\(v=ax.60\))

  


