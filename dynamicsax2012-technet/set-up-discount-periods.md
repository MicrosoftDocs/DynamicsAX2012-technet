---
title: Set up discount periods
TOCTitle: Set up discount periods
ms:assetid: 49db3819-d47f-4a60-a494-8616ee224a5d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh580630(v=AX.60)
ms:contentKeyID: 39519121
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Set up discount periods [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

A discount period defines the period during which a price adjustment or discount is valid. For example, if multiple discounts are in effect during a particular period, you can assign one discount period to all the discounts.

1.  Click **Retail** \> **Setup** \> **Pricing and discounts** \> **Discount periods**.

2.  Press CTRL+N or click **New** to create a new discount period.

3.  In the **Discount period number** field, type a unique ID number, and then, in the **Description** field, type a brief description.

4.  On the **General** FastTab, enter the following information, as necessary:
    
      - **Start date** – Enter the date that the discount period starts.
    
      - **End date** – Enter the date that the discount period ends.
    
      - **Start time** – Enter the time that the discount period starts.
    
      - **End time** – Enter the time that the discount period ends.
    
      - **Time within bounds** – Select this check box if the start date and end date are included in the discount period.
    
      - **Ending time after midnight** – Select this check box if the end time of the discount period is after midnight, or on in the next day.
    
      - **Dates within bounds** – Select the check box for each day that is included in the discount period.

5.  On the FastTab for each day of the week, enter the following information, as necessary. For example, you might want the discount period to be in effect during different hours on different days.
    
      - **Start time** – Enter the time that the discount period starts on this day.
    
      - **End time** – Enter the time that the discount period ends on this day.
    
      - **Time within bounds** – Select this check box if the start time and end time are included in the discount period.
    
      - **Ending time after midnight** – Select this check box if the end time of the discount period is after midnight, or on the next day.

## See also

[About price adjustments and discounts](about-price-adjustments-and-discounts.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

