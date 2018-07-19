---
title: Report production orders as finished
TOCTitle: Report production orders as finished
ms:assetid: 48b853f5-d719-40be-96fe-0495bf7a470c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa497003(v=AX.60)
ms:contentKeyID: 36056930
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- final
- complete
- production
- order
- orders
- finished
- report as finished
audience: Application User
ms.search.region: Global
---

# Report production orders as finished 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When the production process is completed, you can report production orders as finished. You can also report production orders as finished when partial or whole order quantities are physically received into inventory. When you report production orders as finished, you post a **Report as finished** journal.

1.  Click **Production control** \> **Common** \> **Production orders** \> **All production orders**. Select the production order that you want to report as finished. On the **Action Pane**, on the **Production order** tab, under **Process**, click **Report as finished**.

2.  Click the **General** tab.

3.  In the **Good quantity** field, enter the number of items that you want to report as finished. By reporting items as finished, you indicate that the items meet quality standards. You can change this quantity.
    
    When you first open the **Report as finished** form, the **Good quantity** field displays the quantity that must still be finished.

4.  In the **Error quantity** field, enter the number of defective items that have been produced.

5.  If you do not expect additional items to be produced for the production order, select the **End job** check box. The status of the production order is changed to **Reported as finished**.

6.  Before you post the journal, you can run a verification process to make sure that all operations are completed, and that material consumption is registered in inventory. To omit the verification process, select the **Accept error** check box. To run the verification process, clear the **Accept error** check box.

7.  Click **OK**. The **Report as finished** journal is posted, and the good quantity of finished items is physically received into inventory.

You can configure the **Report as finished** form, so that the referenced picking list journal and route card journal are automatically posted when you report a production order as finished.

1.  In the **Automatic BOM consumption** field, select the method that you want to use to post the picking list journal.

2.  In the **Automatic route consumption** field, select the method that you want to use to post the route card journal. To post the route card journal for specific operations only, select the operations in the **From Oper. No.** and **To Oper. No.** fields. Then select the **Report as finished** check box if you want to report the production as finished. If you do not specify operations, all operations are included in the route card journal.

## See also

[Production - Report as finished (class form)](https://technet.microsoft.com/en-us/library/aa600184\(v=ax.60\))

  


