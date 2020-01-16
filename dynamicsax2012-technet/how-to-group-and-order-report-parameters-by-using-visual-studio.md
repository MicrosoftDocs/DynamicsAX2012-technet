---
title: 'How to: Group and Order Report Parameters by Using Visual Studio'
TOCTitle: 'How to: Group and Order Report Parameters by Using Visual Studio'
ms:assetid: 590da96d-44e3-4a8f-835b-123e55701b03
ms:mtpsurl: https://technet.microsoft.com/library/Gg731925(v=AX.60)
ms:contentKeyID: 35132854
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Group and Order Report Parameters by Using Visual Studio 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to use Visual Studio tools for Microsoft Dynamics AX to group and order report parameters on a parameter form for a report. Parameters are used to limit data retrieved from the data source to only the data needed for the report. When you define a report you will see two kinds of parameters as shown in the following illustration:

![Model Editor Screenshot with Parameters](images/Hh528478.DatasetandReportParametersinaReport(AX.60).png "Model Editor Screenshot with Parameters")

The dataset parameters are in the **Parameters** node under the dataset. Dataset parameters are the parameters that are generated for that dataset. Report parameters are under the **Parameters** node at the report level. Report parameters are the parameters that the end-user of the report sees when they run the report. Dataset parameters must reference a report parameter.

The following screenshot illustrates the parameter form that displays when you select the internal account statement report in Microsoft Dynamics AX. The **Customers** parameter group on the form groups the parameters that are related to customer data. You can also change the order that the parameters and parameter groups display in the form.

![Internal account statement report parameter form](images/Gg731925.GroupOrderParameters(AX.60).png "Internal account statement report parameter form")

## Managing Report Parameters

The following sections describe how to add parameter groups, and how to change the order of report parameters or parameter groups.

### To add parameter groups

1.  In Model Editor, expand the node for the report that you want to work with. For more information, see [How to: Access a Report for Edit](how-to-access-a-report-for-edit.md).

2.  In Model Editor, right-click the **Parameters** node for the report, point to **Add** and then click **Parameter group**. A new parameter group is added in the **Parameters** node with a name like **ParameterGroup1**.

3.  In the Properties window, use the properties as needed for your report. The following table describes the properties for a parameter group:
    
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
    <td><p><strong>Caption</strong></p></td>
    <td><p>The caption displayed for the parameter group. The caption of a parameter group is localizable text. It is a best practice to reference a label ID for the caption text.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Layout direction</strong></p></td>
    <td><p>The layout direction of the parameters in the parameter group. The options are <strong>Horizontal</strong> or <strong>Vertical</strong>.</p></td>
    </tr>
    <tr class="odd">
    <td><p>Name</p></td>
    <td><p>The name of the parameter group.</p></td>
    </tr>
    </tbody>
    </table>


4.  Drag report parameters from the **Parameters** node onto the parameter group. The parameter now displays under the parameter group node.
    

    > [!NOTE]
    > <P>If you have a dataset parameter in your report that references the report parameter that you moved to the parameter group, you must update the dataset parameter reference or you will get an error that the <STRONG>Dataset parameter must reference a valid report parameter</STRONG>. The following steps describe how to update the reference to the report parameter.</P>
    > <OL>
    > <LI>
    > <P>The default naming convention for a report parameter is <STRONG>[DatasetName]_[DatasetParameterName]</STRONG>. In Model Editor, expand the dataset that contains a reference to the report parameter that you added to the parameter group, and then select the dataset parameter.</P>
    > <LI>
    > <P>In the Properties window, select the <STRONG>Report parameter</STRONG> drop-down list and then select the report parameter that you added to the parameter group.</P></LI></OL>



5.  Right-click the report design and click **Preview** to see your changes.

### To change the order of report parameters or parameter groups

1.  In Model Editor, expand the node for the report that you want to work with. For more information, see [How to: Access a Report for Edit](how-to-access-a-report-for-edit.md).

2.  In Model Editor, expand the **Parameters** node for the report.

3.  Right-click a parameter or parameter group, and then select a direction to move the element. The options to order parameters or parameter groups are **Move to Top**, **Move Up**, **Move Down**, **Move to Bottom**, **Sort Ascending**, and **Sort Descending**.

4.  Right-click the report design and click **Preview** to see your changes.

Now you may wish to see the changes in the Microsoft Dynamics AX client or Enterprise Portal. For more information, see [How to: Create a Menu Item for a Report](how-to-create-a-menu-item-for-a-report.md) and [Enterprise Portal Reports](https://technet.microsoft.com/library/cc571238\(v=ax.60\)).

