---
title: Create and update production routes
TOCTitle: Create and update production routes
ms:assetid: 81608fc1-e252-4156-acf8-6c7fb568cc49
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa571551(v=AX.60)
ms:contentKeyID: 37832513
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- operation
- routes
- production
- operations
- route
---

# Create and update production routes [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can create production routes that guide items through the manufacturing process from raw materials to finished product. The route describes the sequence of resources and work steps that are required to produce an item. You can also create alternative versions of the main route to accommodate variations in the production of the same item.


> [!NOTE]
> <P>To view prerequisites to creating production routes, see <A href="about-working-with-routes-in-production.md">About working with routes in production</A>.</P>



## Create and update production routes

1.  Click **Production control** \> **Common** \> **Routes** \> **All routes**.

2.  On the **Action Pane**, click **Route** to create a new route.

3.  In the **Route details** form, on the **General** FastTab, in the **Route number** field, specify an alphanumeric identifier for the route. You can also use the number that is automatically generated.

4.  In the **Name** field, enter a descriptive name for the route.

5.  In the **Item group** field, select the item group for the item.

6.  To approve the route, on the **Action Pane**, click **Approve**.

7.  In the **Approved by** field, select the worker who approved the route.
    

    > [!NOTE]
    > <P>The name of the person who approved the route is displayed in the <STRONG>Approved by</STRONG> field, and the <STRONG>Approved</STRONG> check box is selected.</P>



8.  Click **OK**.


> [!NOTE]
> <P>The system automatically completes the <STRONG>Approved</STRONG> field when you select a worker in the <STRONG>Approved by</STRONG> field.</P>



## Add versions to the route

You can set up route versions to accommodate variations in the production of an item, and to increase control over the production process.

1.  Click **Production control** \> **Common** \> **Routes** \> **All routes**. Select the route that you want to add versions to, and then click **Route versions** on the **Action Pane**.

2.  On the **Versions** FastTab, click **Add**.

3.  In the **Item number** field, select the item to produce.

4.  If configurations are set up for the item, select the configuration you want to use in the **Configuration** field.

5.  In the **Site** field, select the site where the item is stored.

6.  In the **From date** and **To date** fields, specify a validity period for the route version.

7.  In the **From qty.** field, enter the minimum quantity that is valid for this route version.
    

    > [!TIP]
    > <P>Optional: You can verify that resources are available and match requirements of all operations on the route by clicking the <STRONG>Route feasibility</STRONG> button.</P>



## See also

[Create or update route operations](create-or-update-route-operations.md)

[Routes (form)](https://technet.microsoft.com/en-us/library/aa548486\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

