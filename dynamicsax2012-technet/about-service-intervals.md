---
title: About service intervals
TOCTitle: About service intervals
ms:assetid: e565dc20-334b-40f2-b0b2-129a6fb6af96
ms:mtpsurl: https://technet.microsoft.com/library/Aa573169(v=AX.60)
ms:contentKeyID: 36059790
author: Khairunj
ms.author: daxcpft
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About service intervals 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The service-agreement interval indicates the frequency with which service-order lines are created for service-agreement lines when you create service orders automatically.

When you create service orders automatically, service-order lines are created according to the interval that you have specified for the service-agreement line from the start date of the agreement line.


> [!NOTE]
> <P>If the <STRONG>Interval</STRONG> field of a service-agreement line in the <STRONG>Service agreements</STRONG> form is blank, the line is a one-time event, and it is not used to create service orders repeatedly.</P>



## Example

This example illustrates how a service interval will affect service-agreement lines and service-order lines on a service order.

## Create service agreement

First, you create a service agreement and set the **Combine service orders** option to **By service agreement**.

1.  Click **Service management** \> **Common** \> **Service agreements** \> **Service agreements**.

2.  On the **Action Pane**, on the **Service agreement** tab, in the **New** group, click **Service agreement** to create a new service agreement.

3.  On the **General** FastTab, enter a description, select a project in the **Project ID** field, and enter a date in the **Start date** field.

4.  In the **Combine service orders** field, select **By service agreement**.

You have now created the following service agreement:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Project</p></th>
<th><p>Start date</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Your project</p></td>
<td><p>The date you specified for the project. In this example, the current date is used.</p></td>
</tr>
</tbody>
</table>


## Create service-agreement line

Next, you create a service-agreement line that has the transaction type **Hour**.


> [!IMPORTANT]
> <P>To complete this part of the example, you must create a service interval of 10 days in the <STRONG>Service intervals</STRONG> form. For information about setting up the service interval, see <A href="set-up-service-intervals.md">Set up service intervals</A>.</P>



1.  Select the service agreement that you just created. On the **Lines** FastTab, click the **Add** button to create a new line in the lower pane of the **Service agreements** form.

2.  In the **Transaction type** field, select **Hour**.

3.  In the **Worker** field, select the worker who will deliver the service.

4.  In the **Service interval** field, select the 10 days interval.

You have now created a service-agreement line with the following information:

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Transaction type</p></th>
<th><p>Start date</p></th>
<th><p>Service interval</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Hour</strong></p></td>
<td><p>The current date.</p></td>
<td><p>Every 10 days</p></td>
</tr>
<tr class="even">
<td><p><strong>Worker</strong></p></td>
<td><p>The worker who will perform the service.</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>



> [!NOTE]
> <P>There is no time window specified for the line. For more information about time windows, see <A href="about-time-windows.md">About time windows</A>.</P>



## Create planned service orders

You can now create planned service orders and service-order lines for the coming month.

1.  In the **Service agreements** form, on the **Action Pane**, on the **Deliver** tab, click **Planned service orders**.

2.  In the **Create service orders** form, enter the current date in the **From date** field and a date that is one month from the current date in the **To date** field.

3.  Select the **Hour** check box.

4.  Click **OK**.

Because there is no grouping on the service order (defined by the **By service agreement** option in the **Combine service orders** field), one service-order line is created per service order.

## Service orders created

Three service-order lines have been created within the time frame that you specified in the **Create service orders** dialog box. You can view the service-order lines in the **Service agreements** form (**Action Pane** \> **Deliver** tab \> **View** button).

## See also

[Set up service intervals](set-up-service-intervals.md)

[Create service orders automatically](create-service-orders-automatically.md)

[About automatically creating service orders](about-automatically-creating-service-orders.md)

  


