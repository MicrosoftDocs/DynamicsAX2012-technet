---
title: 'Walkthrough: Creating a Chart Control with Data from an Analysis Services Cube'
TOCTitle: 'Walkthrough: Creating a Chart Control with Data from an Analysis Services Cube'
ms:assetid: 49ffba25-1804-4586-bde8-3ace5069a295
ms:mtpsurl: https://technet.microsoft.com/library/Hh965685(v=AX.60)
ms:contentKeyID: 46332000
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
f1_keywords:
- reporting services
- chart
- olap
- chart control
- cube
- enterprise portal
- No F1 keyword
- user control
---

# Walkthrough: Creating a Chart Control with Data from an Analysis Services Cube 


_**Applies To:** Microsoft Dynamics AX 2012 R2_

A Chart Control is a User Control option to display chart data in Enterprise Portal. A Chart Control can display data from a Report Data Provider (RDP) class or from an analysis cube. This walkthrough demonstrates how to use the features in Microsoft Dynamics AX to create and deploy a Chart Control for Enterprise Portal that displays analysis cube data. For information about Chart Controls that display RDP data, see [How to: Create a Chart with Data from a Report Data Provider Class](https://technet.microsoft.com/library/hh975424\(v=ax.60\)). The walkthrough illustrates the following tasks:

  - Creating an EP Web Application project.

  - Creating a Chart Control.

  - Deploying the Chart Control.

  - Viewing the Chart Control in Enterprise Portal.

## Prerequisites

To complete this walkthrough, you will need:

  - Microsoft Dynamics AX

  - The default Analysis Services project, deployed and processed. For more information, see [Configure Analysis Services](configure-analysis-services.md).

  - Visual Studio 2010

  - Enterprise Portal with Administrator status. For more information, see [Configure Analysis Services](configure-analysis-services.md).

## Creating the EP Web Application Project

Use Visual Studio to create User Controls for Enterprise Portal.

### To create the EP Web Application project

1.  Start Visual Studio. If User Account Control (UAC) is active, make sure that you start Visual Studio with administrative privileges. To do this, right-click the shortcut for Visual Studio and then click **Run as administrator**.

2.  In the **File** menu, click **New**, and then click **Project**.

3.  In the **New Project** window, select **.NET Framework 3.5** as the framework version to use.
    

    > [!IMPORTANT]
    > <P>For this release of Microsoft Dynamics AX, the EP Web Application project must target the .NET Framework 3.5 to work correctly.</P>



4.  In the **Installed Templates** list, select **Microsoft Dynamics AX**. If you do not see this project template, make sure that you have Visual Studio Tools for Microsoft Dynamics AX installed. For more information, see [How to: Set Up Visual Studio for Enterprise Portal Development](https://technet.microsoft.com/library/cc572801\(v=ax.60\)).

5.  Choose the EP Web Application template.

6.  Specify a name for the project, and the location of the folder where you want to store the files for the project.

7.  Click **OK** to create the project.

## Creating a Chart Control

Create a Chart Control that displays general ledger profit by date.

### To create a Chart Control

1.  In Visual Studio, use Solution Explorer to select the project you created.

2.  In the **Project** menu, click **Add New Item**.

3.  In the **Add New Item** window, expand the **Visual C\#** group of installed templates.

4.  Click **Microsoft Dynamics AX**, and then click the **EP Chart Control** template.

5.  For the Chart Control name, type AxProfit.ascx.
    
    The name entered identifies the chart in SharePoint.

6.  Click **Add**. The new Chart Control is added to the project.

7.  In Solution Explorer, right-click AxProfit.ascx and then click **View Designer**.

8.  The following components are included in the layout for the general ledger profit chart:
    
      - **AxChartDataSource - AxProfitDataSource**
    
      - Chart - **AxProfitChart**
        
        The **DataSourceID** property of the chart has been set to **AxProfitDataSource**.
    
      - **AxChartBehavior - AxProfitBehavior**

9.  Right-click the **AxChartDataSource – AxProfitDataSource** component in the layout, and then click **Properties**.

10. Verify that the **DataType** property is set to **MDXQuery**, to indicate that the data is coming from an Analysis Services cube.

11. In the **CommandText** property, click the ellipsis button (...) to open the OLAP query builder where you can enter a Multidimensional Expression (MDX) query string to access analysis cube data. For information on MDX syntax, see [MDX Query Fundamentals](http://go.microsoft.com/fwlink/?linkid=247282).

12. In this example, you will enter an MDX query that returns profit for the years 2008, 2009, and 2010. Change the query as needed based on your data. Enter the following MDX query:
    
        SELECT {[Measures].[General ledger gross profit - accounting currency]} ON COLUMNS,{[Transaction date].[Year].&[2008-01-01T00:00:00],[Transaction date].[Year].&[2009-01-01T00:00:00],[Transaction date].[Year].&[2010-01-01T00:00:00]} ON ROWSFROM "General ledger cube"

13. Click the execute query **\!** button. The results of the MDX query are displayed.
    

    > [!NOTE]
    > <P>The column headers of the results provide the XValueMember value and YValueMembers value to update the Series property in the next step.</P>



14. Click **OK** to save the query text.

15. In the **Design**, right-click the **AxProfitChart** component in the layout, and then click **Properties**.

16. In the **Series** property, click the ellipsis (…) button to open the **Series Collection Editor**.

17. In the **Series Collection Editor**, set the following properties:
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Property</p></th>
    <th><p>Value</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>XValueMember</strong></p></td>
    <td><p>[Transaction date].[Year].[Year].[MEMBER_CAPTION]</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>YValueMembers</strong></p></td>
    <td><p>[Measures].[General ledger gross profit - accounting currency]</p></td>
    </tr>
    </tbody>
    </table>


18. Click **OK** to save the Series value members.

19. Use the Properties window to change the look and feel of the chart. For example, you can add text to the **Titles** property that will display as a title on the chart.

20. In Solution Explorer, right-click the chart project, and then click Add \[ProjectName\] to AOT.

21. In the **File** menu, click **Save All**.

## Deploying the Chart Control

After you have created and saved the Chart Control, you can display it in Enterprise Portal to verify its functionality. In this walkthrough, you will use the **Deploy to EP** functionality in the AOT to add the chart to Enterprise Portal. For information about how to display a chart in an existing page, see [How to: Add Web Parts](https://technet.microsoft.com/library/cc604931\(v=ax.60\)) to add a [User Control Web Part](https://technet.microsoft.com/library/cc554683\(v=ax.60\)).

### To deploy the Chart Control

1.  Open the Microsoft Dynamics AX client with administrative privileges. To do this, you must right-click on the icon for Microsoft Dynamics AX and then click **Run as administrator**.

2.  Open the Development Workspace.

3.  Display the AOT.

4.  In the AOT, expand the **Web** \> **Web Content** \> **Managed** node. This node contains all of the User Controls that have been defined for Enterprise Portal.

5.  In the list of managed components, locate the AxProfit node. This is the managed content node for the Chart Control that you just created.

6.  Right-click the AxProfit node, and then click **Deploy to EP**.

7.  The **Deploy to EP** dialog box is displayed. Set the **Web module lookup** to Home\\Sales to indicate that the new resources will be used in the Sales site for Enterprise Portal. Click **OK**.

8.  Microsoft Dynamics AX creates a SharePoint page named AxProfit that is located in the Sales site. This page contains the general ledger profit chart that you created. Microsoft Dynamics AX also creates a web menu item named AxProfit that points to the new page. Click **Close** to close the **Infolog**.

## Viewing the Chart Control in Enterprise Portal

After you have created the page that contains the Chart Control, you can view the page in Enterprise Portal.

### To view the Chart Control in Enterprise Portal

1.  Using a web browser, open Enterprise Portal. The typical URL to access Enterprise Portal is:
    
    http://\<server\>/sites/DynamicsAx/
    
    Substitute the name of the server on which Enterprise Portal is installed.

2.  Click **Sales** on the top link bar to display the Sales module site. This is the site that you deployed the new page to.

3.  In the **Site Actions** menu, click **View All Site Content**.

4.  In the **Document Libraries** section, click **Enterprise Portal**. This is the document library that pages for the Sales site are stored in.

5.  Locate the AxProfit page in the list of pages for the Sales site.

6.  Click the link for the AxProfit page to display it in Enterprise Portal. After a few moments, you should see a page that contains the Chart Control you created, displaying general ledger profit in the current company.

## Next Steps

Recall that a web menu item was created when you deployed the Chart Control. You could add this web menu item to the navigation for Enterprise Portal, and then access the new page through standard Enterprise Portal navigation. See [Page-level Navigation Overview](https://technet.microsoft.com/library/cc600461\(v=ax.60\)) or [Walkthrough: Adding a Page to Navigation](https://technet.microsoft.com/library/cc618510\(v=ax.60\)) for more information about how to add the web menu item to the navigation. Another option is to add the User Control web part to an existing page, like a Role Center page. For information about how to display a chart in an existing page, see [How to: Add Web Parts](https://technet.microsoft.com/library/cc604931\(v=ax.60\)).

## See also

[User Controls Overview](https://technet.microsoft.com/library/cc595764\(v=ax.60\))

[Chart Controls Overview](https://technet.microsoft.com/library/hh965689\(v=ax.60\))

[Walkthrough: Quickly Creating and Deploying a User Control](https://technet.microsoft.com/library/hh745329\(v=ax.60\))

[Walkthrough: Displaying Cube Data in a Report](walkthrough-displaying-cube-data-in-a-report.md)

