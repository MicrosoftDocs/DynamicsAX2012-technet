---
title: 'How to: Create a Menu Item for a Report'
TOCTitle: 'How to: Create a Menu Item for a Report'
ms:assetid: 977bb61d-6f9e-4540-9d24-86a006980965
ms:mtpsurl: https://technet.microsoft.com/library/Cc606402(v=AX.60)
ms:contentKeyID: 28119533
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Create a Menu Item for a Report 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can create menu items in Microsoft Dynamics AX to provide access to the reports that you create with the Visual Studio tools for Microsoft Dynamics AX. These menu items are created as output menu items from the **Menu Items** node in the AOT and can display reports in both the client and in Enterprise Portal Web parts. The following procedure explains how to create a menu item for a report.


> [!NOTE]
> <P>Before you create a menu item for a report, be sure that the report has been added to the AOT. For more information, see <A href="how-to-add-reports-to-microsoft-dynamics-ax.md">How to: Add Reports to Microsoft Dynamics AX</A>. If you want to view the report from the menu item, you must deploy the report to a report server. For more information, see <A href="how-to-deploy-reports-to-a-report-server.md">How to: Deploy Reports to a Report Server</A>.</P>



### To create a menu item for a report

1.  In the AOT, expand the **Menu Items** node.

2.  Right-click the **Output** node, and then click **New Menu Item**.

3.  Select the node for the menu item.

4.  In the **Properties** window, set the following properties:
    
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
    <td><p>Type a name for the menu item.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Label</strong></p></td>
    <td><p>Specify a label for the report title.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>ObjectType</strong></p></td>
    <td><p>Set to <strong>SSRSReport</strong>.</p>
    <p>--or--</p>
    <p>If you define a <a href="https://technet.microsoft.com/library/gg940296(v=ax.60)">SrsReportRunController</a> class to run the report, set the <strong>ObjectType</strong> property to <strong>Class</strong>, and then select the controller class from the drop-down menu for the <strong>Object</strong> property.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Object</strong></p></td>
    <td><p>Use the drop-down menu to select the report.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>RunOn</strong></p></td>
    <td><p>Set to <strong>Called from</strong>. If you set the report to run on <strong>Client</strong> and the report is run in a batch, the report will fail. If you set the report to run on <strong>Server</strong> and the report is displayed to the screen, the report will fail.</p></td>
    </tr>
    </tbody>
    </table>


5.  Save the changes in the AOT.

## See also

[Menus and Menu Items](https://technet.microsoft.com/library/aa596556\(v=ax.60\))

[Report Integration and Customization Overview](report-integration-and-customization-overview.md)

[How to: Add Reports to Microsoft Dynamics AX](how-to-add-reports-to-microsoft-dynamics-ax.md)

[How to: Deploy Reports to a Report Server](how-to-deploy-reports-to-a-report-server.md)

[How to: Customize a Report](how-to-customize-a-report.md)

