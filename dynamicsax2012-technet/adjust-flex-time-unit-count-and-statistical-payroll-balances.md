---
title: Adjust flex time, unit count, and statistical payroll balances
TOCTitle: Adjust flex time, unit count, and statistical payroll balances
ms:assetid: 592d0181-361f-4672-95f8-1e9f0c063033
ms:mtpsurl: https://technet.microsoft.com/library/Aa549074(v=AX.60)
ms:contentKeyID: 36057347
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- flex
- count unit
- payroll
- statistical
- balance
- adjust
- correct
audience: Application User
ms.search.region: Global
---

# Adjust flex time, unit count, and statistical payroll balances 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Depending on which types of registrations workers are allowed to make, different types of balances can be generated, for example, flexible hours, or payroll statistics. You can recalculate the balances and, in some cases, make adjustments or set up an opening balance.

## Flexible hours

For workers who work flexible hours, it may be necessary to adjust the flexible hours balance. When you set up time and attendance registrations for workers, it is often relevant to enter an opening flex balance, if flexible hours are transferred from a previously used system.

## Specify an opening flex balance for a worker

1.  Click **Human resources** \> **Common** \> **Workers** \> **Time registration workers**.

2.  Select a worker.

3.  On the **Action Pane**, click the **Time registration** tab.

4.  In the **Setup** group, click **Set up time registration worker** and select **Opening flex balance**.

5.  In the **Opening flex balance** field, insert the number of flex hours to be added to the opening balance.


> [!TIP]
> <P>To recalculate the worker balance, select the <STRONG>Recalculate flex balance</STRONG> check box before you click <STRONG>OK</STRONG>.</P>



## Specify an opening flex balance for multiple workers

You can recalculate balances for several workers at the same time.

1.  Click **Set up time registration worker** button and select **Recalculate worker balances**.

2.  In the **Recalculate worker balances** dialog box, click the **Select** button.

3.  In the **Inquiry** form, on the **Range** tab, click the **Add** button to create a line.

4.  In the **Field** field, select **Worker**.

5.  In the **Criteria** field, select the record ID for each worker.

6.  Repeat steps three through five for each worker.

## Adjust a flex balance

1.  Click **Human resources** \> **Common** \> **Workers** \> **Time registration workers**.

2.  Select a worker.

3.  On the **Action Pane**, click the **Time registration** tab.

4.  In the **Setup** group, click the **Set up time registration worker** button and select **Flex balance**.

5.  Select the flex registration to correct.

6.  Click **Flex correction**.

7.  Press CTRL+N to create a new correction line.

8.  Insert a description of the flex correction in the **Description** field.

9.  Insert the number of flex hours to be adjusted in the **Flex correction** field.


> [!NOTE]
> <P>To make corrections to a worker's pay, in addition to the flex balance, you can select a pay type in the <STRONG>Pay type</STRONG> field and insert the number of paid hours to be adjusted in the <STRONG>Pay units</STRONG> field.</P>



## Recalculate a flex balance

1.  Click **Human resources** \> **Periodic** \> **Time and attendance** \> **Flex** \> **Recalculate flex balance**.

2.  Click **Select**.

3.  Select the workers to recalculate flex balances for and then click **OK**.

## Statistical payroll balances

Statistical payroll balances can be adjusted and recalculated.


> [!NOTE]
> <P>A payroll record must exist for the date that you make the adjustment for.</P>



## Adjust statistical payroll balances for several workers

1.  Click **Human resources** \> **Periodic** \> **Time and attendance** \> **Payroll** \> **Adjust payroll statistics**.

2.  Select the group to adjust in the **Payroll statistics group** field.

3.  In the **Pay type** field, select the pay type to be adjusted.

4.  In the **Date** field, select the date when to make the adjustment.

5.  In the **Adjustment type** field, select how to make the adjustment:
    
      - **Opening balance** – Adjust the opening balance to be the value that you insert in the **Value** field.
    
      - **Balance** – Adjust the current balance for the selected **Pay type** to be the value that you insert in the **Value** field.
    
      - **Adjustment** – Adjust the payroll record on the selected date with value that you insert in the **Value**. For example, if you insert the number 2 in the **Value** field, you will add two hours to the payroll balances of all the workers included in the selected payroll statistics group.

6.  In the **Value** field, insert the number of hours to be adjusted, according to the adjustment method selected in the **Adjustment type** field.

## Adjust the statistical payroll balance for a specific worker

1.  Click **Human resources** \> **Common** \> **Workers** \> **Time registration workers**.

2.  Select a worker, and then click the **Time registration** tab.

3.  In the **Payroll statistics** group, click **Payroll statistics**.

4.  Select the balance to adjust.

5.  Click **Set adjustment**.

6.  Insert the value to use to adjust the balance in the **Adjustment** field. For example, if you insert the number 2 in the field, you will add two hours to the payroll balance of the worker.

## Recalculate statistical payroll balances

You can recalculate statistical payroll balances for a group of workers.

1.  Click **Human resources** \> **Periodic** \> **Time and attendance** \> **Payroll** \> **Recalculate payroll statistics**.

2.  Select a **Payroll statistics group**, a **Pay type**, and, if necessary, a **Period code** (which is the pay period), to be recalculated.

## Recalculate the count unit balance for a worker

1.  Click **Human resources** \> **Periodic** \> **Time and attendance** \> **Payroll** \> **Recalculate worker balances**.

2.  Select a worker to recalculate count unit balances for.


> [!NOTE]
> <P>After you have recalculated a count unit balance for a worker, you can see that the balance was updated. Click <STRONG>Human resources</STRONG> &gt; <STRONG>Common</STRONG> &gt; <STRONG>Workers</STRONG> &gt; <STRONG>Time registration workers</STRONG>. Double-click the worker. On the <STRONG>Action Pane</STRONG>, click the <STRONG>Time registration</STRONG> tab. In the <STRONG>Worker balances</STRONG> group, click <STRONG>Worker balances</STRONG>.</P>



## See also

[About time registration workers](about-time-registration-workers.md)

[Set up payroll statistics for time and attendance](set-up-payroll-statistics-for-time-and-attendance.md)

[Worker (form)](https://technet.microsoft.com/library/hh209054\(v=ax.60\))

  


