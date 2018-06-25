---
title: Manage trade allowance funds
TOCTitle: Manage trade allowance funds
ms:assetid: f691d673-82aa-4c43-9bf3-1b074e073272
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn497857(v=AX.60)
ms:contentKeyID: 62381661
ms.date: 05/27/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.TAMListPage
- Forms.TAMFundUsage
- Forms.TAMTradePromotionAnalysis
---

# Manage trade allowance funds [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Trade allowance funds are used when your organization is participating in promotional activities with customers. After your organization has approved the use of funds for trade allowance activities, such as customer rebates, you can create and distribute those funds appropriately. This topic explains how to create a trade allowance fund and assign it to a trade allowance agreement and how to distribute the trade allowance funds.

## Create a trade allowance fund and assign it to a trade allowance agreement

Use this procedure to set up a trade allowance fund and assign it to a trade allowance agreement. For more information about how to create trade allowance agreements, see Create a trade allowance agreement.

1.  Click **Trade allowance management** \> **Periodic** \> **Funds**.

2.  In the **Funds** form, click **New**.

3.  If a fund ID is not automatically generated, enter one, and then enter a description of the fund.

4.  On the **General** FastTab, enter the following information:
    
      - In the **Type** field, select whether the fund is discretionary.
    
      - In the **From date** and **To date** fields, enter the time period for which the fund is active.
    
      - In the **Fund budgeted** field, enter the amount that is budgeted for fund.
    
      - Enter any additional notes about the fund, and in the **Usage** field, select the usage type for the fund. For example, the usage type might be Marketing or Promotions.

5.  On the **Customers** FastTab, in the **Hierarchy** filter, select the customer category hierarchy for the fund.

6.  Select the appropriate nodes to add to the list, and then click **\>**.

7.  After you have added all of the customers to the fund, select a customer, and in the **Budgeted** field, enter the amount of the fund that is budgeted for that customer.
    
    For example, if you have a budget of 10,000.00 and you have 10 customers, you would enter 1,000.00 for each customer budget.

8.  On the **Items** FastTab, click **Add products**.

9.  In the **Add products** form, select the appropriate product group in the **Hierarchy** field and then select the appropriate product node.

10. In the **Available products** pane, select the products to add to the fund, and then click **Add**.

11. Click **OK** to add the products.

12. In the **Funds** form, on the **General** FastTab, in the **Status** field, select **Approved**.

## Distribute a trade allowance fund

Trade allowance funds are distributed through a trade allowance agreement. Use this procedure to add fund information to a trade allowance agreement.

1.  Click **Trade allowance management** \> **Common** \> **Trade allowance agreements**.

2.  Create a new trade allowance agreement or open an existing agreement. For more information about how to create a trade allowance agreement, see Create a trade allowance agreement.

3.  In the **Trade allowance agreements** form, on the **Funds** FastTab, click **Add line**.

4.  In the **Fund ID** field, select the trade allowance fund for the agreement.

5.  In the **Event cost allocation %** field, enter the amount of the selected fund that is allocated for this agreement.

## See also

Set up trade allowance funds

Process trade allowance claims

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

