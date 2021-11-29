---
title: Create route groups
TOCTitle: Create route groups
ms:assetid: f299f567-8a1b-4ed1-b2eb-c19c223ba7ee
ms:mtpsurl: https://technet.microsoft.com/library/Aa551628(v=AX.60)
ms:contentKeyID: 37832549
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create route groups 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Create routing groups to define parameters for a group of routes. You can specify how costs are calculated, how planning occurs, how jobs are managed, and the kind of feedback that you want for the group.


> [!NOTE]
> <P>You must set up routing groups before you can set up routes.</P>



1.  Click **Production control** \> **Setup** \> **Routes** \> **Route groups**.

2.  On the toolbar, click **New** to create a new line.

3.  In the **Route group** field, enter an identifier of up to ten alphanumeric characters.

4.  In the **Name** field, enter a short description of the routing group.

5.  Click the **General** tab.

6.  Under **Estimation and costing**, select any of the following check boxes:
    
      - To include the setup time for the operations resource in the cost estimate for the item, select the **Setup time** check box. Because setup times are often part of the price that is calculated for an item, this check box is usually selected.
    
      - To include the run time for the operations resource in the cost estimate for the item, select the **Run time** check box. Because run times are often part of the price that is calculated for an item, this check box is usually selected.
    
      - To include the planned quantity of the finished product in the estimate, select the **Quantity** check box. The planned quantity is calculated for every operation on the route.

7.  Under **Automatic route consumption**, select any of the following check boxes:
    
      - To enable automatic consumption of setup time when a production is started or finished, select the **Setup** check box.
    
      - To enable automatic consumption of run time when a production is started or finished, select the **Run time** check box.
    
      - To enable the number that was produced to be automatically reported as finished when a production is started or reported as finished, select the **Quantity** check box.
    
      - To manually report operations that are associated with the current routing group as finished, select the **Report operation as finished** check box. This setting can be overwritten when you report productions as finished. Select the check box when feedback from routes and job journals is used to determine whether the operation is finished.

8.  Click the **Setup** tab.

9.  In the **Route/job type** column, view the route type or job type that the parameters are set for.

10. In the **Activation** column, select the check box to activate this route type or job type in cost calculations, planning, and feedback.

11. In the **Job management** column, select the check box to include job management on this route type or job type. If the check box is selected, jobs are scheduled by the system.

12. In the **Working time** column, select the check box to include this route type or job type on the working time calendars. If the check box is selected, the system uses the working calendar to plan the operation. If the check box is cleared, the system uses the standard 24-hour Gregorian calendar.

13. In the **Capacity** column, select the check box to include capacity reservations for the selected route type or job type. If the check box is selected, the system reserves capacity during planning. The system does not reserve an operations resource if the resource can be used for another job at that time.

## See also

[About working with routes in production](about-working-with-routes-in-production.md)

[Create and update production routes](create-and-update-production-routes.md)

  


