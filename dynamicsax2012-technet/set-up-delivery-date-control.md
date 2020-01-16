---
title: Set up delivery date control
TOCTitle: Set up delivery date control
ms:assetid: ab9a588b-f524-4544-ab4b-51ada91a0a08
ms:mtpsurl: https://technet.microsoft.com/library/Aa498551(v=AX.60)
ms:contentKeyID: 36058913
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- control delivery dates
- delivery date control
- shipping point
- delivery dates
- receiving point
- set up delivery dates
audience: Application User
ms.search.region: Global
---

# Set up delivery date control 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This procedure helps you set up delivery date control for sales order delivery dates.


> [!NOTE]
> <P>Before you start this procedure, verify that the following prerequisites have been set up:</P>
> <UL>
> <LI>
> <P>The <STRONG>Working times</STRONG> form is set up. For more information, see <A href="create-working-time-calendars.md">Create working time calendars</A>.</P>
> <LI>
> <P>The shipping point, receiving point, and duration for the various forms of transport are set up.</P></LI></UL>



1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  Click **Shipments**.

3.  Enter the number of days of sales lead time in the **Sales lead time** field, and the order deadline times for the days of the week in the ATP fields.

4.  To automatically calculate the ship date when you select a receipt date, select a method in the **Delivery date control** field. This method then becomes the default delivery date control method for new orders.

5.  To view the available receipt and ship dates and transfer them to the order, in the **Sales order** form, click **Simulate delivery dates** on the **Delivery** tab on the order line as relevant.


> [!NOTE]
> <P>The procedure for selecting dates is the same for both requested and confirmed dates. If you select a ship or receipt date that is not valid, the <STRONG>Simulate delivery dates</STRONG> form is displayed so that you can select alternative dates.</P>



## See also

[About delivery dates](about-delivery-dates.md)

[About order entry deadlines](about-order-entry-deadlines.md)

[Set up the transport calendar](set-up-the-transport-calendar.md)

  


