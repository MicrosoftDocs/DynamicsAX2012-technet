---
title: 'How to: Add a URL Drill Through Action on a Report'
TOCTitle: 'How to: Add a URL Drill Through Action on a Report'
ms:assetid: 0baf8146-571b-4baf-9a66-aab61e43d915
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Cc582049(v=AX.60)
ms:contentKeyID: 28119303
ms.date: 11/07/2012
mtps_version: v=AX.60
dev_langs:
- csharp
---

# How to: Add a URL Drill Through Action on a Report [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A *URL drill through action* lets you add a hyperlink so that users can access a web page, an Enterprise Portal page, or a form in the Microsoft Dynamics AX client by clicking a linked item in a report. The hyperlink can be a static URL or an expression that evaluates to a URL. If a field in a database table contains a URL, that field can be used to create an expression that is used for a dynamic list of hyperlinks.

To see an example of a URL to display the Worker form from the Absence setup report, in the Microsoft Dynamics AX client go to **Human resources** \> **Reports** \> **Absence** \> **Absence setup**. To generate URLs to display forms in the Microsoft Dynamics AX client and Enterprise Portal pages, you must create data methods that generate an appropriate URL based on the report context. After you have created a data method, you can use the data method in the expression that defines the URL drill through action.

If you are creating a URL drill through action for a precision design report, we recommended that you create a drill through action using an auto design report first, and then create a precision design report from the auto design report. The auto design expression editor provides the names of the data methods that you will need when creating the drill through for the precision design report.

If you add the URL drill through action in the precision design, you must provide the name of the data method in the Expression dialog box. For example, the expression for the PersonnelNumber field in the Absence setup report is =DrillWorker(Parameters\!AX\_ReportContext.Value,Fields\!PersonnelNumber.Value).

Adding a URL drill through action is a multiple-step process. The following are the basic steps:

Determine which business logic project will be needed for the report. If you are accessing common resources like the main account or a form in Microsoft Dynamics AX, you can use the SRSDrillThroughCommon project, which already has the code for several drill-through actions defined. If you are creating a URL drill through action to your own form or EP page, then you will need to create your own business logic project that contains the code needed for the URL drill through. The AX\_ReportContext report parameter is recognized by the Microsoft Dynamics AX reporting framework. When a request is made to display a URL that has the AX\_ReportContext defined, the framework, based on the AX\_ReportContext value, will navigate to the appropriate Microsoft Dynamics AX form or Enterprise Portal (EP) page.

If you are creating a drill-through that doesn’t exist in the SRSDrillThroughCommon project, you must create a business logic project that contains a method to perform the drill through action.

When the business logic for the URL drill through is in place, you can create the actual drill-through for the report.

The following procedures provide detailed steps that explain how to add a URL drill through action.

### To determine which business logic project to use

1.  In Application Explorer, go to **Visual Studio Projects** \> **C Sharp Projects** \> right-click **SRSDrillTHroughCommon** and then click **Edit**. The SRSDrillThroughCommon project will open in Visual Studio.

2.  In Solution Explorer, double-click DrillThroughCommonHelper.cs to open the code file in code editor.

3.  Press CTRL-F to search for the method that renders the URL that you want to set as the target of your drill through action. For example, in the **Find and Replace** window, type the name of the form like BankPromissoryNote.
    
    If you find the form or constant that you want to set as the target, then you will use the SRSDrillThroughCommon project to generate the URL for your URL drill through action. If the form is a new form that you have added, then you must create your own business logic project. The following procedures provide the steps for both options.

### To use the SRSDrillThroughCommon business logic project

1.  In Visual Studio, in Application Explorer, open the reporting project to which you want to add a URL drill through action. For information on how to open a project for edit, see [How to: Access a Report for Edit](how-to-access-a-report-for-edit.md).

2.  In Application Explorer, right-click **Visual Studio Projects** \> **C Sharp Projects** \> **SRSDrillThroughCommon** and then click **Edit**. This adds the SRSDrillThroughCommon project to your solution.

3.  In Solution Explorer, double-click the report to work with.

4.  In Model Editor, right-click the **Data Methods** node and then click **Add Data Method**. A data method is added with a name like **DataMethod1**. In Solution Explorer, a C\# business logic project is added with the same name as your reporting project, like **HcmAbsenceSetupReport.BL**.

5.  In Solution Explorer, right-click the business logic project and then click **Add Reference**.

6.  In the Add Reference window, select the **SRSDrillThroughCommon** project and then click **OK**.

7.  In Model Editor, double-click the data method that you added, like **DataMethod1**. This opens code editor with the C\# template added for a data method.

8.  In code editor, add the following using statement:
    
        using Microsoft.Dynamics.AX.Application.Reports;

9.  The following code uses the DrillThroughCommonHelper class to get a URL to the worker form in Microsoft Dynamics AX. You would replace the ToHcmWorker method with the name of the method in the DrillThroughCommonHelper class that generates the URL for the form that you want as the target of your drill through action. Add the following data method so that your code looks like the following:
    
    ``` csharp
    [DataMethod(), PermissionSet(SecurityAction.Assert, Name = "FullTrust")]
    public static string DrillWorker(string reportContext, string personnelNumber)
    {
        return DrillThroughCommonHelper.ToHcmWorker(reportContext, personnelNumber);
    }
    ```

10. In Solution Explorer, right-click the solution and then click **Build Solution**. The report project, business logic project and SRSDrillThroughCommon project should build successfully.

11. In Model Editor, expand the **Designs** node for the report.

12. Expand the node for the auto design that you want to modify, and then expand the node for the data region that contains the field or image that you want to add a URL drill through action to.
    
    You can use a field or image located below the **Data** node, or you can use fields that are used to define groupings for the data region.

13. Right-click the field or image, point to **Add**, and then click **URL Drill Through Action**.

14. Select the node for the URL drill through action.

15. In the **Properties** window, specify the following properties.
    
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
    <td><p><strong>Expression</strong></p></td>
    <td><p>A URL, an expression that evaluates to a URL, or a field in a database table that contains a URL. You can type the value or build the value using the Expression Editor. To open the Expression Editor, click the <strong>Expression</strong> property drop-down and then click <strong>&lt;Expression…&gt;</strong>. To use a data method to get a URL, type or build the following: =[MethodName](Fields![LinkedFieldorImageName].Value)</p>
    <p>For example, using the data method you added to the project in the previous steps, type or build the following in the Expression Editor window:</p>
    <p>=DataMethod1(Parameters!AX_ReportContext.Value,Fields!PersonnelNumber.Value)</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Name</strong></p></td>
    <td><p>Type a name for the URL drill through action.</p></td>
    </tr>
    </tbody>
    </table>


Next, you can preview the report in Visual Studio and you will see the drill through action reflected as blue text but you must view the report in Microsoft Dynamics AX to use the link to drill to a form. For information about how to view a report in Microsoft Dynamics AX, see [How to: Create a Menu Item for a Report](how-to-create-a-menu-item-for-a-report.md).

### To create your own business logic project

1.  In Visual Studio, in Application Explorer, open the reporting project to which you want to add a URL drill through action. For information on how to open a project for edit, see [How to: Access a Report for Edit](how-to-access-a-report-for-edit.md).

2.  In Solution Explorer, double-click the report to work with.

3.  In Model Editor, right-click the **Data Methods** node and then click **Add Data Method**. A data method is added with a name like **DataMethod1**. In Solution Explorer, a C\# business logic project is added with the same name as your reporting project, like **HcmAbsenceSetupReport.BL**.

4.  In Model Editor, double-click the data method that you added, like **DataMethod1**. This opens code editor with the C\# template added for a data method.

5.  In code editor, add the following using statement:
    
        using Microsoft.Dynamics.AX.Application.Reports;

6.  The following example can be found in the Facility Management sample in the FCMWorkOrders report for the DrillThroughLinkToRoom data method. The code calls the GenerateLinkToAXMenuItem helper method that is defined by the reporting framework to generate a URL to the Rooms form. Modify the following code for your needs:
    
    ``` csharp
    [DataMethod(), PermissionSet(SecurityAction.Assert, Name = "FullTrust")]
        public static string DrillThroughLinkToRoom(string reportContext, object fieldValue)
        {
            string tableName = "FCMRooms";
            Dictionary<string, object> fields = new Dictionary<string, object>();
            fields.Add("RecId", fieldValue);
    
            if (RuntimeReportContext.IsClientContext(reportContext))
            {
                // The report is being run from the Microsoft Dynamics AX client.
                return DrillthroughHelper.GenerateLinkToAXMenuItem(reportContext, "FCMRoomsForm", MenuItemType.Display, tableName, fields);
            }
            else
            {
                // The report is being run from Enterprise Portal.
                return DrillthroughHelper.GenerateLinkToAXMenuItem(reportContext, "RoomDetails", MenuItemType.WebMenuItemTypeUrl, tableName, fields);
            }
    ```

7.  In Solution Explorer, right-click the solution and then click **Build Solution**. The report project, business logic project and SRSDrillThroughCommon project should build successfully.

8.  In Model Editor, expand the **Designs** node for the report.

9.  Expand the node for the auto design that you want to modify, and then expand the node for the data region that contains the field or image that you want to add a URL drill through action to. In the FCMWorkOrders report, the URL drill through action was added to the RoomRecID\_RoomName field.
    
    You can use a field or image located below the **Data** node, or you can use fields that are used to define groupings for the data region.

10. Right-click the field or image, point to **Add**, and then click **URL Drill Through Action**.

11. Select the node for the URL drill through action.

12. In the **Properties** window, specify the following properties.
    
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
    <td><p><strong>Expression</strong></p></td>
    <td><p>A URL, an expression that evaluates to a URL, or a field in a database table that contains a URL. You can type the value or build the value using the Expression Editor. To open the Expression Editor, click the <strong>Expression</strong> property drop-down and then click <strong>&lt;Expression…&gt;</strong>. To use a data method to get a URL, type or build the following: =[MethodName](Fields![LinkedFieldorImageName].Value)</p>
    <p>In the FCMWorkOrders report example, the expression is the following:</p>
    <p>=DrillthroughLinkToRoom(Parameters!AX_ReportContext.Value,Fields!RoomRecId.Value)</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Name</strong></p></td>
    <td><p>Type a name for the URL drill through action like <strong>URLDrillThroughAction</strong>.</p></td>
    </tr>
    </tbody>
    </table>


### To add a URL drill through action (auto design to precision design)

  - Follow the steps to add a URL drill through action in an auto design, right-click the design, and then click **Create Precision Design**.

  - Select the field to which you added the URL drill through action.

  - In the Properties window, click the **Action** property ellipses button (…) to open a dialog about the hyperlink options.
    
    You can update the details of the URL drill through action.

### To add a URL drill through action (precision design)

  - Follow the steps to add a data method for a drill through action in an auto design,

  - In Model Editor, expand the node for the report that you want to work with.

  - Expand the **Designs** node for the report.

  - Right-click the precision design that you want to modify, and then click **Edit Using Designer...**
    
    You can add a URL drill through action to a textbox or image.

  - Select the text box or image, in the Properties window, click the **Action** ellipses button (…).

  - Click **Go to URL** and then click the **Select URL** Expression (**fx**) button to open the Expression dialog box.

  - Write an expression for the URL drill through that has the following syntax: =\<DataMethodName\>(Parameters\!AX\_ReportContext.Value,Fields\!\<FieldNameWithDrillThroughAction\>). For example, the expression for the PersonnelNumber field in the Absence setup report is =DrillWorker(Parameters\!AX\_ReportContext.Value,Fields\!PersonnelNumber.Value).

For more information, see [How to: Add a Hyperlink (SQL Report Designer)](http://go.microsoft.com/fwlink/?linkid=106192).

## See also

[How to: Add a Report Drill Through Action on a Report](how-to-add-a-report-drill-through-action-on-a-report.md)

[Walkthrough: Creating a Drillthrough Report](walkthrough-creating-a-drillthrough-report.md)

