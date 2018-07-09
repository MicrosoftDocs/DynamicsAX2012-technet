---
title: 'Walkthrough: Defining KPIs for a Cube'
TOCTitle: 'Walkthrough: Defining KPIs for a Cube'
ms:assetid: 4cfcf1ab-7771-46ef-a5e1-c5db3c9bf03c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dd261469(v=AX.60)
ms:contentKeyID: 28119352
ms.date: 07/17/2013
mtps_version: v=AX.60
dev_langs:
- sql
---

# Walkthrough: Defining KPIs for a Cube [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A Key Performance Indicator (KPI) is a business metric that can be displayed in places like reports and role center pages. For more information, see [Cube Overview](cube-overview.md).

## Prerequisites

To complete this walkthrough, you will need:

  - Microsoft Dynamics AX with sample data

  - The SalesAnalysis cube from [Walkthrough: Creating a Cube](walkthrough-creating-a-cube.md).

  - SQL Server Business Intelligence Development Studio (BIDS) or SQL Server Data Tools

  - Configure Analysis Services by running the Microsoft Dynamics AX Setup wizard

## Defining a KPI for Inventory Quantity

To display your KPI in a Business Overview web part on a role center, you must define value, goal, status, and trend expressions for the KPI. If you exclude one of the expressions, the KPI will not display properly.

### To create a KPI for Inventory Quantity

1.  In BIDS, open the Analysis Services project that contains the Sales analysis cube, and then double-click **SalesAnalysis.cube**.

2.  Click the **KPIs** tab.

3.  On the toolbar for the **KPIs** tab, click **New KPI**. A form displays that allows you to define the KPI.

4.  For the **Name** field, type **Customer sales**.

5.  For the **Value Expression** field, type the following expression.
    
    ``` sql
    [Measures].[Total customer sales Count]
    ```
    
    This expression retrieves the quantity in inventory units.
    

    > [!NOTE]
    > <P>You can drag measures from the <STRONG>Metadata</STRONG> tab of the <STRONG>Calculation Tools</STRONG> pane to help you create expressions.</P>



6.  For the **Goal Expression** field, type the following expression.
    
    ``` sql
    7500
    ```
    
    This expression identifies the goal for the inventory quantity.

7.  For the **Status indicator** field, select **Gauge** from the drop-down list.

8.  For the **Status expression** field, type the following expression.
    
    ``` sql
    Case
        When
            [Measures].[Total customer sales Count] >= 7500
        Then 1
        When
            [Measures].[Total customer sales Count] < 7500
        AND
            [Measures].[Total customer sales Count] > 6500
        Then 0
        Else-1
    End
    ```
    
    This expression provides a basis to evaluate progress toward meeting the goal. The graphic that displays for status of the KPI depends on what value this expression evaluates to.

9.  For the **Trend indicator** field, select **Standard arrow** from the drop-down list.

10. For the **Trend expression** field, type the following expression.
    
    ``` sql
    Case
        When
            [Measures].[Total customer sales Count] >= 3000
        Then 1
        When
            [Measures].[Total customer sales Count] < 3000
        
        Then -1
    End
    ```
    
    This expression provides a basis to evaluate the status in some historical context. The graphic that displays for the trend of the KPI depends on what value this expression evaluates to. Typically, the trend expression would evaluate the current status relative to a previous status.

### To view the KPI

1.  On the **Build** menu, click **Deploy Dynamics AX SalesAnalysis**.
    

    > [!NOTE]
    > <P>The name of the database may vary.</P>



2.  On the toolbar for the **KPIs** tab, click **Browser View**. The KPI displays in the list.

## Next Steps

For more advanced KPI examples, see the templates that are available in the **Templates** tab of the **Calculation Tools** pane.

After you have defined KPIs for a cube, you can display the KPIs in a Business Overview web part. For more information, see [Walkthrough: Displaying KPIs in a Role Center](walkthrough-displaying-kpis-in-a-role-center.md).

