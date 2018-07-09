---
title: 'Walkthrough: Displaying KPIs in a Role Center'
TOCTitle: 'Walkthrough: Displaying KPIs in a Role Center'
ms:assetid: 96da7c16-ea81-4e5d-880d-adc10845aca5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dd261507(v=AX.60)
ms:contentKeyID: 28119531
ms.date: 07/17/2013
mtps_version: v=AX.60
---

# Walkthrough: Displaying KPIs in a Role Center [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

After you create an analysis cube and define KPIs for it, you can display the KPIs in a Business Overview web part in a Role Center or Enterprise Portal.

## Prerequisites

To complete this walkthrough, you must first complete [Walkthrough: Creating a Cube](walkthrough-creating-a-cube.md) and [Walkthrough: Defining KPIs for a Cube](walkthrough-defining-kpis-for-a-cube.md).

## Displaying KPIs in a Business Overview Web Part

You can display the KPIs that you created in a web part on your role center page in Microsoft Dynamics AX or Enterprise Portal.

The following procedure explains how to add the Sales Analysis KPI to a web part in the CEO Role Center page.

### To display the KPIs in a Business Overview Web part

1.  Navigate to the CEO role center that is located at http://\<server\>/sites/DynamicsAx/Enterprise%20Portal/RoleCenterCEO.aspx.

2.  On the **Site Actions** menu, click **Edit Page**. Locate the **Middle Column** section, and then click **Add Web Part**

3.  In the **Categories** list, click **Microsoft Dynamics AX**. In the Web Parts list, select **Business overview**, and then click **Add**.

4.  On the drop-down menu for the web part, click **Edit Web Part**. The properties for the web part are displayed.

5.  For the **Select mode** property, select **KPI List**.

6.  Expand the **Business Overview Setup** node.
    

    > [!NOTE]
    > <P>The Business Overview web part points to the default <STRONG>Dynamics AX</STRONG> Analysis Services database. You can use any KPIs that ship with Microsoft Dynamics AX and any KPIs that you add to that database. If you create another database, you must create an Office Data Connection (ODC) file that points to that database. You then must specify the location of the ODC file in <STRONG>Data Connection</STRONG>. For more information, see <A href="how-to-create-an-odc-file-for-a-business-overview-web-part.md">How to: Create an ODC file for a Business Overview Web Part</A>.</P>



7.  For the **Title** property, type Sales KPIs. Click **OK** to save the changes.

8.  In the **Sales KPIs** web part, click **Add KPIs**.

9.  In the **Business Overview - Add KPI** dialog box, select the **Sales Analysis** cube, select the **Customer sales** KPI, select **Amount** for the **Display value as** field, and then click **OK**.
    

    > [!NOTE]
    > <P>If you created a new Analysis Services database that has only the SalesAnalysis cube, you do not need to select a cube in the <STRONG>Business Overview - Add KPI</STRONG> dialog box.</P>



10. Click **Stop Editing** to save the changes made to the page.

## See also

[Walkthrough: Creating a Cube](walkthrough-creating-a-cube.md)

[Walkthrough: Defining KPIs for a Cube](walkthrough-defining-kpis-for-a-cube.md)

