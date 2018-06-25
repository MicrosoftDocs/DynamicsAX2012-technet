---
title: 'How to: Group and Order Report Parameters by Using a Data Contract Class'
TOCTitle: 'How to: Group and Order Report Parameters by Using a Data Contract Class'
ms:assetid: a2582be0-f129-41e4-9151-f0f4d9f7b185
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg724085(v=AX.60)
ms:contentKeyID: 35133443
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Group and Order Report Parameters by Using a Data Contract Class [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to specify the grouping and order of parameters for a report. Report parameters let an end user of a report select or enter the values that are used when the report is printed. A data contract class defines the parameters for a report that is bound to a report data provider (RDP) class. You can specify one or more groups of report parameters, the order of the groups, and the order in which the report parameters appear in a print dialog box. For information about data contracts, see [How to: Use a Report Data Provider Class in a Report](how-to-use-a-report-data-provider-class-in-a-report.md).

You can also define report parameter groups by using Microsoft Visual Studio. The grouping and order of report parameters that you specify in Visual Studio take precedence over the grouping and order that are defined in the data contract. For more information, see [How to: Group and Order Report Parameters by Using Visual Studio](how-to-group-and-order-report-parameters-by-using-visual-studio.md).

You use Visual Studio to define the grouping and order of report parameters when the scenario is complex, such as when you want to use multiple nested groups. The benefit of using a data contract class to define the grouping and order of report parameters is that you maintain consistent formatting when you reuse the data contract in another report or in a SysOperation service.

## Defining the Grouping and Ordering of Report Parameters

You use two constructs to define the grouping of report parameters:

  - A data contract class is used to define the groups, the order of the groups, and alignment in the groups.

  - A data contract method is used to specify the group that a report parameter belongs to, and the order of the report parameter relative to the other report parameters in the group.

## Defining a Data Contract Class

Groups are defined in a data contract class. A data contract class is an X++ class to which getters, setters, and the DataContractAttribute attribute are attached. By grouping two or more report parameters, you indicate that the parameters are related to each other. To define a group, attach the SysOperationGroupAttribute attribute to a data contract class.

A data contract class defines the following properties of a group:

  - The group name

  - The label that is displayed for the group

  - The order of the group relative to other groups

  - The arrangement, either vertical or horizontal of report parameters in the group

### To define groups, the order of groups, and the alignment of groups in a data contract class

1.  In the Application Object Tree (AOT), right-click the **Classes** node, and then click **New Class**.

2.  Right-click the new class, click **Rename**, and then enter **SrsRDPContractSample**.

3.  Expand **SrsRDPContractSample**, right-click **classDeclaration**, and then click **Code**.

4.  Enter the following code in the class declaration to define the class.
    
        [
            DataContractAttribute,
            SysOperationGroupAttribute("AccountsGroup", "@SYS313802", "1", FormArrangeMethod::Vertical),
            SysOperationGroupAttribute("TaxGroup", "@SYS130006", "2")
        ]
        public class SrsRDPContractSample
        {
            AccountNum accountNum;
            CustAccountStatement accountStmt;
            boolean inclTax;
        }

## Defining the Order of Report Parameters in a Data Contract Method

A data contract method defines a report parameter. Each report parameter requires a separate data contract method. You can use a data contract method to indicate that a report parameter belongs to a group. You can also specify the order in which the parameter is displayed relative to the other report parameters in the group.

This section describes how to create a data contract method and configure it in the following ways:

  - Use the DataMemberAttribute attribute to indicate that the method is a data contract method, and to specify the parameter name, AccountNum, that is displayed in Visual Studio when you bind a report data set to an RDP class.
    
    The name that follows the attribute is the parameter name that is displayed in Visual Studio when you bind a report data set to the RDP class.

  - Use the SysOperationGroupMemberAttribute attribute to indicate that the parameter belongs to the AccountGroup group.

  - Use the SysOperationDisplayOrderAttribute attribute to indicate that the parameter is displayed first in the group.

### To define the order of report parameters in a data contract method

1.  Right-click the **SrsRDPContractSample** class, point to **New**, and then click **Method**.

2.  Edit the method so that it contains the following code.
    
        [
            DataMemberAttribute("AccountNum"),
            SysOperationGroupMemberAttribute("AccountsGroup"),
            SysOperationDisplayOrderAttribute("1")
        ]
        public AccountNum parmAccountNum(AccountNum _accountNum = accountNum)
        {
            accountNum = _accountNum;
            return accountNum;
        }

## Next Steps

To use the report parameter groups in the data contract class, define an RDP class. A data contract class defines the report parameters that an RDP class references. For the complete procedure, see [How to: Use a Report Data Provider Class in a Report](how-to-use-a-report-data-provider-class-in-a-report.md). You then use the Visual Studio Reporting Tools for Microsoft Dynamics AX to define a report that has a dataset that is bound to the RDP class. For information about how to bind an RDP class to a report, see [Walkthrough: Creating a Report Bound to a Report Data Provider Class (X++ Business Logic)](walkthrough-creating-a-report-bound-to-a-report-data-provider-class-x-business-logic.md).


> [!NOTE]
> <P>The Visual Studio Report Viewer does not display the grouping and order that you specified in the data contract class. To see the report that has the grouping and order of parameters that you specified in the data contract class, you must deploy and run the report from Microsoft Dynamics AX.</P>



## See also

[How to: Group and Order Report Parameters by Using a Data Contract Class](how-to-group-and-order-report-parameters-by-using-a-data-contract-class.md)

[Guidance for Choosing the Data Source Type](guidance-for-choosing-the-data-source-type.md)

[Creating Reports Overview](creating-reports-overview.md)

[Controls Used to Render Report Parameters](controls-used-to-render-report-parameters.md)

[How to: Define a Report Parameter](how-to-define-a-report-parameter.md)

[How to: Group and Order Report Parameters by Using Visual Studio](how-to-group-and-order-report-parameters-by-using-visual-studio.md)

