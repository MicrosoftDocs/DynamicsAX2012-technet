---
title: Set up outbound rules
TOCTitle: Set up outbound rules
ms:assetid: 96f519f6-a496-420a-b4a8-926314e87854
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg232237(v=AX.60)
ms:contentKeyID: 36058666
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- shipment
- handle outbound process
- rules for shipment process
- outbound rules
- outbound process
---

# Set up outbound rules 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic applies to features in the **Inventory management** module. It does not apply to features in the [Warehouse management](warehouse-management.md) module.

You can set up outbound rules to determine how you want the program to handle the outbound process. You can use these rules to enable or disable the shipment staging functions to control the shipment process and, in particular, at which stage in the process you can send a shipment.

1.  Click **Inventory management** \> **Setup** \> **Distribution** \> **Outbound rules**.

2.  Click **New** to create a new outbound rule.

3.  In the **Outbound rule ID** and **Description** fields, enter an ID and description for the rule.

4.  Select the **Deliver picked items** field if you want to be able to specify a different to location for delivering the picked items. If you do not select this field, the items are automatically delivered to the default location.

5.  In the **Set picking line status to** field, select the status for the picking line after delivery.
    

    > [!NOTE]
    > <P>If you select <STRONG>Completed</STRONG>, when you deliver the last item in the shipment, the shipment will automatically be sent.</P>



6.  In the **Allow send from shipment status** field, select the status that defines when the shipment can be sent. The shipment status is always based on the lowest denominator of the shipment lines status. All the shipment lines must at least have the status **Picked** for them to be shipped.

7.  Select whether you want the program to ship the items automatically when the shipment status reaches the one that you have specified in the **Allow send from shipment status** field.

8.  Select whether you want a bill of lading created and a shipment list printed automatically when you ship.

## See also

[About shipments](about-shipments.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

