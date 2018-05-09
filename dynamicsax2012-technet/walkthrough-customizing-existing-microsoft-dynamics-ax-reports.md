---
title: 'Walkthrough: Customizing Existing Microsoft Dynamics AX Reports'
TOCTitle: 'Walkthrough: Customizing Existing Microsoft Dynamics AX Reports'
ms:assetid: 1e383292-7dc2-49ba-b44a-23ad3b374b83
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Cc567629(v=AX.60)
ms:contentKeyID: 28119316
ms.date: 04/17/2013
mtps_version: v=AX.60
---

# Walkthrough: Customizing Existing Microsoft Dynamics AX Reports 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In this walkthrough, you will customize the Balance control accounts report which is defined in the LedgerBalanceControlReport model project that is included with Microsoft Dynamics AX. The Balance control accounts report displays in the General ledger module. Model projects in Microsoft Dynamics AX adhere to layered development in the MorphX development environment. This allows model projects to be customized, upgraded, and patched using the built-in layering support. This walkthrough provides an example of how to customize existing reports in Microsoft Visual Studio and see those changes in Microsoft Dynamics AX.

This walkthrough includes the following tasks:

  - Viewing the report

  - Changing the development layer in Microsoft Dynamics AX

  - Customizing reports in Microsoft Visual Studio

  - Saving the customizations to Microsoft Dynamics AX

  - Deploying customized reports to a report server

  - Verifying the results

## Prerequisites

To complete this walkthrough, you will need:

  - Microsoft Dynamics AX with sample data

  - Microsoft Visual Studio 2010

  - Microsoft Visual Studio tools for Microsoft Dynamics AX

## Viewing the Report

You will begin this walkthrough by viewing the report that you will customize in order to familiarize yourself with the report. The following procedure explains how to view the Balance control accounts report within Microsoft Dynamics AX.

### To view the existing report in the application

1.  Open Microsoft Dynamics AX.

2.  Open the Navigation Pane if it is not already open. To do this, click **File** \> **View** \> **Navigation Pane**.

3.  Select the **General ledger** module. The **Area page** for the General ledger module opens.

4.  In the **Setup** section, click **Posting** \> **Balance control accounts**. The Balance control accounts form displays.

5.  Click the **Balance control accounts** button and the Balance control accounts report displays.
    
    In this walkthrough, the changes that you will make to this report include adding a sort order to change the numeric sequence of the main account from ascending to descending. In addition, you will add a report parameter that will control the display of the account name.

## Changing the Development Layer in Microsoft Dynamics AX

Before you customize a report project, be sure that you are working in the correct development layer. There are several layers that are used for making customizations in Microsoft Dynamics AX. For example, the supervisor or administrator of an end-user installation might want to make modifications that are generic to the company. Such modifications are saved in the CUS (CUStomer) layer. For this walkthrough, you will use the default **USR** layer. For more information, see [Layers](https://technet.microsoft.com/en-us/library/aa851164\(v=ax.60\)). The following steps describe how to change the layer if you have a valid access code with your license agreement.

### To change the development layer

1.  Click **Start** \> **Control Panel**\> **Administrative Tools**\> **Microsoft Dynamics AX 2012 Configuration**.

2.  On the **Developer** tab, select the layer you want to work in from the drop-down list in the **Application object layer to open** field, and then click **OK**.

3.  Close and restart the client in the new layer.

## Customizing Reports in Microsoft Visual Studio

Next, you will customize the Balance control accounts report in the LedgerBalanceControlReport model project. When you customize an existing report model project, a copy of the reporting model project for the layer that you are currently working in is created and opened in Microsoft Visual Studio where it can be edited and later imported back into the AOT. In the following procedures, you will add a sort order to sort the main account in a descending sequence. In addition, you will add a report parameter that will control the display of the account name.

### To open the reporting project in Microsoft Visual Studio

1.  Open the Microsoft Dynamics AX Development Workspace. If you changed the application object layer, enter the access code.

2.  In the AOT, expand **Visual Studio Projects** \> **Dynamics AX Model Projects**.

3.  Right-click the **LedgerBalanceControlReport** project, and then click **Edit**.
    
    The LedgerBalanceControlReport project opens in Microsoft Visual Studio with the LedgerBalanceControl report open in the Model Editor.

### To define a sort order for the account ID

1.  In Model Editor, expand the **LedgerBalanceControl** node if it is not already expanded.

2.  Expand the **Designs** node, expand the **Reports** node, and then expand the **LedgerBalanceControlDSTable** node. This is an Auto Design report with a table definition.

3.  Right-click the **Sorting** node, and then click **Add Sort**.

4.  Select the node for the sort order.

5.  In the **Properties** window, specify the following property values.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Property</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Name</strong></p></td>
    <td><p>SortMainAccountID</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Sort By</strong></p></td>
    <td><p>=Fields!MainAccount_MainAccountId.Value</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Sort Order</strong></p></td>
    <td><p><strong>Descending</strong></p></td>
    </tr>
    </tbody>
    </table>


### To define a parameter to control the display of the account name

1.  In Model Editor, right-click the **Parameters** node for the report, and then click **Add Parameter**. The **Parameters** node is located after the **Data Methods** node.

2.  Select the node for the parameter.

3.  In the **Properties** window, specify the following property values.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Property</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Data Type</strong></p></td>
    <td><p><strong>Boolean</strong></p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Default Value</strong></p></td>
    <td><p><strong>True</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Name</strong></p></td>
    <td><p>IncludeAccountName</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Prompt String</strong></p></td>
    <td><p>Include account name</p></td>
    </tr>
    </tbody>
    </table>


4.  From **LedgerBalanceControl** \> **Designs** \> **Report** \> **LedgerBalanceControlDSTable** \> **Data**, select the **AccountName** field.

5.  In the **Properties** window, type =iif(Parameters\!IncludeAccountName.Value = True, True, False) for the **Visible** property.

6.  To preview the report, in the Model Editor toolbar, click **Preview**.
    

    > [!NOTE]
    > <P>Notice that a parameter checkbox was added called <STRONG>Include account name</STRONG> and by default the checkbox is marked.</P>



7.  Click the **Report** tab to view the report. Verify the changes that you made to the report.

8.  Close the **Preview** window.

## Importing Customizations into Microsoft Dynamics AX

Next, you will add the report project into Microsoft Dynamics AX. During the add process, all required project items are identified. These project items are validated, packaged, and then added to the AOT. The customizations made in this walkthrough will be added to the current development layer.

### To import the customized reporting project into Microsoft Dynamics AX

  - In Solution Explorer, right-click the **LedgerBalanceControlReport** reporting project, and then click **Add LedgerBalanceControlReport to AOT**.
    
    When you open Microsoft Dynamics AX, you will notice that the LedgerBalanceControlReport project is now updated in the current customization layer. If you do not see this, close the Microsoft Dynamics AX client, and then reopen it.

## Deploying Customized Reports to a Report Server

Next, you will deploy the customized LedgerBalanceControlReport project to the report server so that the customizations made to the reports are available to the application.

### To deploy the customized report library to the report server

1.  In the AOT, click the **SSRS Reports** node and the **Reports** node.

2.  Right-click the **LedgerBalanceControl** node for the layer that you made the customization, for example, **LedgerBalanceControl(usr)**. Then click **Deploy**.

3.  Review any messages logged during the deployment process, and then close the Infolog form.

## Verifying the Results

Next, you will verify that the customized report now displays in Microsoft Dynamics AX.

### To verify the results

1.  In the Navigation Pane, select the **General ledger** module.

2.  In the **Setup** section, click **Posting** \> **Balance control accounts**. The Balance control accounts form displays.

3.  Click the **Balance control accounts** button. Notice the parameter that controls whether to display the account name has been added.

4.  Unmark the checkbox to display the account name and then click **OK**.
    
    Notice that the account IDs are now in descending order and the main account name does not display.

## See also

[Report Integration and Customization Overview](report-integration-and-customization-overview.md)

