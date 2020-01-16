---
title: 'Walkthrough: Customizing a Default Cube'
TOCTitle: 'Walkthrough: Customizing a Default Cube'
ms:assetid: 23b8d390-c2a2-4839-8839-de5e3127bf54
ms:mtpsurl: https://technet.microsoft.com/library/Dd252602(v=AX.60)
ms:contentKeyID: 28119321
author: Khairunj
ms.date: 07/17/2013
mtps_version: v=AX.60
---

# Walkthrough: Customizing a Default Cube 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft Dynamics AX has default cubes included that you can customize. In this walkthrough, you will customize the Customer Relationship Management (CRM) cube by modifying the Status expression in the Sales Key Performance Indicator (KPI) and adding a KPI that reports the average revenue earned for each sale. These KPIs can be displayed from a role center in the Microsoft Dynamics AX client or Enterprise Portal.

## Prerequisites

To complete this walkthrough, you will need:

  - Microsoft Dynamics AX with sample data

  - SQL Server Business Intelligence Development Studio (BIDS)

  - Configure Analysis Services by running the Microsoft Dynamics AX Setup wizard

## Generating an Analysis Services Project

The CRM cube can be modified in BIDS. To edit the cube in BIDS, you must generate an Analysis Services project that contains the CRM cube.

### To generate an Analysis Services project

  - Follow the steps in [Deploy the default cubes](deploy-the-default-cubes.md).

## Customizing an Existing KPI

You can modify an existing KPI to display custom information.

### To customize an existing KPI

1.  Open the Analysis Services project that contains the CRM cube in BIDS. In Solution Explorer, expand the **Cubes** node and then double-click **smmCube.cube**.
    

    > [!NOTE]
    > <P>By default, the Analysis Services project is named Dynamics AX. You can open the project from the AOT under the Analysis Services projects node. To open it from the AOT, right-click the project and then click <STRONG>Edit</STRONG>. If you open the project from the AOT, it is saved locally to a temporary directory. When you finish editing the project, you can save your changes to the AOT by importing the cube. To import the cube, right-click the Analysis Services project in the AOT, and then click <STRONG>Import</STRONG>.</P>



2.  Click the KPIs tab. On the toolbar for the KPIs tab, click **Form View** if you are currently in **Browser View**.

3.  In the **KPI Organizer**, click the Sales KPI.

4.  For the **Status expression** field, revise the expression so that it matches the following.
    
       ```VBScript
       Case
          When 
            KpiValue("Sales") / KpiGoal("Sales") >= .80
          Then 1
          When
            KpiValue("Sales") / KpiGoal("Sales") < .80
          And 
            KpiValue("Sales") / KpiGoal("Sales") >= .60
          Then 0
          Else-1
        End
       ```
    
    This expression provides a basis from which to evaluate progress toward meeting a goal. The status graphic that displays is based on the value the expression returns. The new expression will display the **Gauge** status indicator with the following characteristics:
    
      - The hand is in the green region if the KPI value is within 80 percent of reaching the sales goal
    
      - The hand is in the yellow region if the KPI value is between 60 percent and 80 percent of the sales goal
    
      - The hand is in the red region if the KPI value is less than 60 percent of the sales goal

5.  On the toolbar for the KPIs tab, click **Browser View** to see the KPI.

## Adding a New KPI

You can add new KPIs to default cubes.

In the following procedure, you will create a KPI that reports the average revenue per sale.

### To add a new KPI

1.  In Solution Explorer, expand the **Cubes** node and then double-click **smmCube.Cube**.

2.  Click the KPIs tab.

3.  On the toolbar for the KPIs tab, click **Form View** if you are currently in **Browser View**.

4.  Click **New KPI**. A form appears that allows you to define the KPI.

5.  For the **Name** filed, type **Average Revenue per Sale**.

6.  For the **Value Expression** field, type the following expression.
    
      ```VBScript
       [Measures].[Invoice revenue]/[Measures].[Sales count]
      ```
    
    This expression divides the total invoice revenue by the number of sales.

7.  For the **Goal Expression** field, type the following.
    
       ```VBScript
       17000
       ```
    
    This number represents the goal for the average revenue per sale.

8.  For the **Status expression** field, type the following expression.
    
       ```VBScript
       Case
          When 
            KpiValue("Average Revenue per Sale") / KpiGoal("Average Revenue per Sale") >= 1
          Then 1
          When
            KpiValue("Average Revenue per Sale") / KpiGoal("Average Revenue per Sale") < 1
          And 
            KpiValue("Average Revenue per Sale") / KpiGoal("Average Revenue per Sale") >= .80
          Then 0
          Else-1
        End
       ```
    
    This expression provides a basis from which to evaluate progress toward meeting a goal. The status graphic that displays is based on the value the expression returns. The new expression will display the **Gauge** indicator with the following characteristics:
    
      - The hand is in the green region if the KPI value reaches the revenue per sale goal
    
      - The hand is in the yellow region if the KPI value is within 80 percent of reaching the goal
    
      - The hand is in the red region if the KPI value is less than 80 percent of the revenue per sale goal

9.  For the **Trend indicator** field, select the **Standard arrow** from the drop-down list.

10. For the **Trend expression** field, type the following expression.
    
       ```VBScript
       Case
          When 
            KpiValue("Average Revenue per Sale") < (KpiValue("Average Revenue per Sale"),
            [Date].[Year - Quarter - Month - Week - Date].PREVMEMBER)
          Then -1
          When 
            KpiValue("Average Revenue per Sale") >= 
            1.05 * (KpiValue("Average Revenue per Sale"),
            [Date].[Year - Quarter - Month - Week - Date].PREVMEMBER)
          Then 1
          Else 0
        End
       ```
    
    This expression provides a basis to evaluate the trend toward achieving the goal. The graphic that displays for the trend of the KPI depends upon what value this expression evaluates to.

11. On the **Build** menu, click **Deploy Dynamics AX**. Click **Yes** to overwrite the database. Deploying the project may take several minutes.

12. On the toolbar for the KPIs tab, click **Browser View** to see the KPI.

## Viewing the New and Customized KPIs

After you deploy the project, you can display the KPI data in a Business Overview Web part in a role center page.

### To display the KPIs in a Business Overview Web part

1.  In Enterprise Portal, browse to the CEO role center that is located at http://\<server\>/sites/DynamicsAx/Enterprise%20Portal/RoleCenterCEO.aspx.

2.  In the **Customer KPIs** web part, click **Add KPIs**.

3.  In the **Business Overview - Add KPI** dialog box, select **Customer relationship management cube**, select the **Sales** KPI, select **Amount** for the **Display value as** field, and then click **OK**. The additional KPI will be added to the list displayed by the web part.

4.  In the **Customer KPIs** web part, click **Add KPIs**.

5.  In the **Business Overview - Add KPI** dialog box, select **Customer relationship management cube**, select the **Average Revenue per Sale** KPI, select **Amount** for the **Display value as** field, and then click **OK**. The KPI is added to the web part.

