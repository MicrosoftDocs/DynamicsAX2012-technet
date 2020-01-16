---
title: 'Walkthrough: Creating an Analyze Data Button on a List Page'
TOCTitle: 'Walkthrough: Creating an Analyze Data Button on a List Page'
ms:assetid: f5ad431e-69e7-4c04-bd4a-7fef5aa9e09f
ms:mtpsurl: https://technet.microsoft.com/library/JJ945385(v=AX.60)
ms:contentKeyID: 51442775
author: Khairunj
ms.date: 06/26/2015
mtps_version: v=AX.60
---

# Walkthrough: Creating an Analyze Data Button on a List Page 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use Power View to create interactive ad-hoc reports in Microsoft Dynamics AX. Several list pages have an **Analyze data** button that launches a Power View report designer. The Power View report designer connects to an Analysis Cube and allows you to drag and drop fields for quick analysis. This topic describes how to add an **Analyze data** button to additional list pages.

To add an Analyze data button to a list page, you must:

  - Create a data source that connects your Power View report to a cube.

  - Create a class that gets the URL of the Power View report designer.

  - Create a menu item that specifies the class you created.

  - Create a button that points to the menu item you created.

### Prerequisites

  - Microsoft SharePoint Server 2010 or 2013 must be installed.

  - Microsoft SQL Server Reporting Services 2012 Service Pack 1 must be installed in SharePoint integrated mode with [cumulative update 4](https://support.microsoft.com/kb/2833645/en-us) applied.

  - The Power View site collection feature in SharePoint must be activated. For instructions about how to activate this feature, see the information in the [Install Reporting Services SharePoint Mode as a Single Server Farm](http://technet.microsoft.com/en-us/library/gg492276.aspx) topic.

  - Microsoft SQL Server Analysis Services 2012 Service Pack 1 must be installed in multidimensional mode with [cumulative update 4](https://support.microsoft.com/kb/2833645/en-us) applied.

  - Microsoft Dynamics AX 2012 R2 must be installed. The following components are required:
    
      - Enterprise Portal and Role Centers must be deployed to SharePoint. For more information, see [Checklist: Deploy an internal Enterprise Portal site that has Role Centers](checklist-deploy-an-internal-enterprise-portal-site-that-has-role-centers.md).
    
      - The cubes that are included with Microsoft Dynamics AX must be deployed to Analysis Services. For more information, see [Checklist: Configure Analysis Services and deploy cubes](checklist-configure-analysis-services-and-deploy-cubes.md).

  - Cumulative update 6 for Microsoft Dynamics AX 2012 R2 must be installed. For more information about how to install cumulative update 6 for Microsoft Dynamics AX 2012 R2, see the Knowledge Base article for [cumulative update 6](http://go.microsoft.com/fwlink/?linkid=309870).
    
    After you install cumulative update 6, you must redeploy three page definitions. To deploy these page definitions, complete the following steps. Keep in mind, when you redeploy the Role Center pages, you will lose customizations made to the pages.
    
    1.  Open the AOT.
    
    2.  Expand the **Web** \> **Web Files** \> **Page Definitions** node.
    
    3.  Right-click **RoleCenterCFOPV** and click **Deploy Element**.
    
    4.  Right-click **RoleCenterTreasurerPV** and click **Deploy Element**.
    
    5.  Right-click **PowerViewDataSourceGeneratorPV** and click **Deploy Elements**.

## Creating a Data Source

You must add a data source to your SharePoint library to connect a Power View report designer to a cube.

### To create a data source

1.  Open your browser and go to the Enterprise Portal site. The URL for the Enterprise Portal site is typically http://\[SharePointServerName\]/sites/DynamicsAX.
    

    > [!NOTE]
    > <P>For security reasons, integrating Power View with Microsoft Dynamics AX is not supported in environments where the Enterprise Portal site is configured for multiple data partitions.</P>



2.  Go to the **Power View Reports** folder. The URL for this folder is typically http://\[SharePointServerName\]/sites/DynamicsAX/Power%20View%20Reports.

3.  Click **Documents** \> **New Document** \> **Report Data Source**. The **Data Source Properties** page is displayed.

4.  In the **Name** field, enter a name for the data source. For example, if the data source will connect to the Retail cube, you may want to name the data source *Retail cube*.

5.  In the **Data Source Type** area, select **Microsoft BI Semantic Model for Power View**.

6.  In the **Connection string** area, enter the following connection string:
    
    Provider=MSOLAP.4;Integrated Security=SSPI;Persist Security Info=True;Data Source=\[ServerName\];Initial Catalog=\[DatabaseName\];Locale identifier=\[LocaleID\];Cube=\[CubeName\]
    
    The following table lists the documentation conventions that are used in the connection string.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Value</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>[ServerName]</p></td>
    <td><p>The name of the server on which Analysis Services is installed.</p></td>
    </tr>
    <tr class="even">
    <td><p>[DatabaseName]</p></td>
    <td><p>The name of the Analysis Services database that contains the cube that you want to connect to.</p></td>
    </tr>
    <tr class="odd">
    <td><p>[LocaleID]</p></td>
    <td><p>The identifier that designates the language of the labels to display on the report. For example, if you want measures and dimensions to be shown in German, you must add German translations to the cube and specify the locale identifier for German.</p>
    <p>For more information about how to add translations to a cube, see <a href="how-to-update-an-existing-sql-server-analysis-services-project.md">Update an Existing SQL Server Analysis Services Project</a>. For a list of the locales that are supported by both Enterprise Portal and SharePoint, see <a href="install-enterprise-portal-on-a-single-server.md">Install Enterprise Portal on a single server</a>.</p></td>
    </tr>
    <tr class="even">
    <td><p>[CubeName]</p></td>
    <td><p>The name of the cube that contains the data that you want to display on the report.</p></td>
    </tr>
    </tbody>
    </table>
    
    For example, if you want to connect to the Retail cube that is provided with Microsoft Dynamics AX, the default connection string is:
    
    Provider=MSOLAP.4;Integrated Security=SSPI;Persist Security Info=True;Data Source=\[ServerName\];Initial Catalog=Dynamics AX initial;Locale identifier=1033;Cube=Retail cube

7.  In the **Credentials** area, select **Windows authentication (integrated) or SharePoint user**.
    

    > [!NOTE]
    > <P>If Analysis Services and Enterprise Portal are installed on different computers, you must use Kerberos security. To configure Kerberos security, see <A href="http://www.microsoft.com/en-us/download/details.aspx?id=16080">this white paper.</A> After you have configured Kerberos security to work with the servers, complete the following steps:</P>
    > <OL>
    > <LI>
    > <P>In the <STRONG>Credentials</STRONG> area, select <STRONG>Stored credentials</STRONG>.</P>
    > <LI>
    > <P>Enter the user name and the password for the account that is assigned to the Analysis Services server administrator role. In most cases, this is the Business Connector proxy account. For more information, see the <STRONG>Assign the Business Connector proxy account to the Analysis Services server administer role</STRONG> section in <A href="before-you-configure-analysis-services.md">Before you configure Analysis Services</A>.</P>
    > <LI>
    > <P>Select the <STRONG>Use as Windows credentials</STRONG> check box.</P>
    > <LI>
    > <P>Select the <STRONG>Set execution context to this account</STRONG> check box.</P></LI></OL>



8.  Click **Test Connection** to verify the connection to the cube.

9.  In the **Availability** area, select the **Enable this data source** check box.

10. Click **OK**. The data source is created.

## Creating a Class

You need a class that uses the Power View integration framework to get the URL of a Power View report designer with a cube. The [PowerViewReporting](https://technet.microsoft.com/library/jj772359\(v=ax.60\)) class generalizes this implementation and fulfills specific error handling requirements. If you use the PowerViewReporting class, be aware that the data source name and cube name must be an exact match, and you must pass the name of the cube as the first parameter on the action menu item in the next section. The following procedure demonstrates how to create your own class called MyPVClass.

### To create a class

1.  In the AOT, right-click **Classes**, and then click **New Class**. Name the class MyPVClass. For more information about classes, see [Classes in X++](https://technet.microsoft.com/library/aa868834\(v=ax.60\)).

2.  Right-click the class you created, point to **New**, and then click **Method**.

3.  In Code Editor, add code for method1 to name the method main and to get the URL of the Power View designer for the cube. The following code example shows how to verify that Power View is available and how to get the URL of the data source:
    
        public static void main(Args args)
        {
                if (SrsReportHelper::isPowerViewModelDeployed('Accounts receivable cube'))
            {
                infolog.urlLookup(SrsReportHelper::getPowerViewDataSourceUrlClient('Accounts receivable cube'));
            }
            else
            {
               // Cube has not been deployed – display error message
            }
        
        }

## Creating a Menu Item

After you create the class, you create a menu item that references that class. The class indicates the cube the Power View report designer connects to. If you use the existing PowerViewReporting class, you must specify the cube the Power View report designer connects to in the **Parameters** property.

### To create a menu item

1.  In the AOT, right-click **AOT** \> **Menu Items** \> **Action**, and then click **New Menu Item**.

2.  Right-click the new menu item and then click **Properties**.

3.  Set the following properties:
    
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
    <td><p><strong>Name</strong></p></td>
    <td><p>Specify a name for your menu item. For example, CreatePowerViewReportAccountsReceivableCube.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Label</strong></p></td>
    <td><p><strong>Analyze data</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>HelpText</strong></p></td>
    <td><p>Provide help text for the button.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>ObjectType</strong></p></td>
    <td><p><strong>Class</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Object</strong></p></td>
    <td><p>Specify the class you created. For example, MyPVClass. You can also use the PowerViewReporting class if you specify the cube to connect to using the <strong>Parameters</strong> property.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Parameters</strong></p></td>
    <td><p>If you use the PowerViewReporting class instead of creating your own class, specify the name of the cube to connect the Power View report designer to.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>NormalImage</strong></p></td>
    <td><p><strong>12578</strong></p></td>
    </tr>
    <tr class="even">
    <td><p><strong>ImageLocation</strong></p></td>
    <td><p><strong>EmbeddedResource</strong></p></td>
    </tr>
    </tbody>
    </table>


## Creating a Button

After you create a menu item, you can create a button that points to the menu item. The following procedure demonstrates how to create an **Analyze data** button to launch a Power View report designer page.

### To create a button

1.  In the AOT, navigate to the list page form that you want to add an Analyze Data button to.

2.  Expand **Designs** \> **Design** \> **ActionPane** \> **ActionPaneTab**, and identify the button group you want to add the button to.

3.  Right-click the button group control, point to **New Control**, and then click **MenuItemButton**.
    

    > [!NOTE]
    > <P>To specify the location of the button in the button group, use the ALT+UP ARROW or ALT+DOWN ARROW to position the button before or after an existing button.</P>



4.  Specify the following properties for the new button:
    
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
    <td><p><strong>Name</strong></p></td>
    <td><p>Specify a name for the button. For example, <strong>AnalyzeData</strong>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Big</strong></p></td>
    <td><p><strong>Yes</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>MenuItemType</strong></p></td>
    <td><p><strong>Action</strong></p></td>
    </tr>
    <tr class="even">
    <td><p><strong>MenuItemName</strong></p></td>
    <td><p>Specify the menu item you created in the previous section. For example, CreatePowerViewReportAccountsReceivableCube</p></td>
    </tr>
    </tbody>
    </table>


5.  Add logic to the form load event to hide the button if Power View is not configured. For example, expand the **Methods** node of the form, and then double-click the init method. Add the following line of code:
    
        ReportingGroup.visible(SrsReportHelper::isPowerViewConfigured());

To view the button, right-click the form name in the AOT, and then click **Open**. The client displays the button in the list page action pane. To test the button action, click the button.

  


