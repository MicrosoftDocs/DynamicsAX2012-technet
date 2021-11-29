---
title: 'How to: Use a Label in a Report'
TOCTitle: 'How to: Use a Label in a Report'
ms:assetid: 99dcfb10-30a5-4314-b133-970f1db626b3
ms:mtpsurl: https://technet.microsoft.com/library/Gg724077(v=AX.60)
ms:contentKeyID: 35133434
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
dev_langs:
- csharp
---

# How to: Use a Label in a Report 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You should use labels for localizable text on reports. Labels are created in the [Label Editor](https://technet.microsoft.com/library/aa617477\(v=ax.60\)). Labels are used on reports in a similar manner to how they are used on forms. This topic describes how to reference label values in an auto design report, how to reference label values in a precision design report, and how to reference label values programmatically for reports that are bound to a report data provider (RDP) class. For RDP based reports, you can programmatically set the label identifier in the data contract. If it is not specified in the data contract, the label ID of the underlying EDT that is used in the data member will be used as the label ID. For query based reports, the parameter label is derived from the extended data type (EDT) of the query range that is used.


> [!NOTE]
> <P>Labels can be used in any report expression except for parameter prompt strings.</P>



To create a new label, you must create or update a label file. For more information, see [How to: Create a Label File](https://technet.microsoft.com/library/aa844896\(v=ax.60\)) and [How to: Create and Use Labels](how-to-create-and-use-labels.md). Labels are resolved by the framework as the report is rendered. This allows for faster deployment of one generic report. The language that was used to display the localizable text is determined by the language of the user who is running the report in Microsoft Dynamics AX or Enterprise Portal. You can override the language to specify the language you want the report printed in if you are running a report through code. For more information, see the M:SrsReportRdlDataContract.parmLanguageId method.

### To reference auto design report labels

1.  In Model Editor, expand the node for the auto design report that you want to work with.

2.  Expand the **Dataset** node for the report, expand the **Fields** node, and then select a field.

3.  In the Properties window, set the **Caption** property to the label ID that you want to use on the report. For example, <strong>@SYS7149</strong>. For information about how to look up a label, see [How to: Find a Label](https://technet.microsoft.com/library/cc624360\(v=ax.60\)).

### To reference precision design report labels

1.  In Model Editor, double-click the precision design report that you want to work with.

2.  Double-click the **\<\<Expr\>\>** for the field for which you want to provide a label.

3.  In the **Placeholder Properties** window, set the **Label** value. For information about how to look up a label, see [How to: Find a Label](https://technet.microsoft.com/library/cc624360\(v=ax.60\)).

### To reference report labels programmatically for an RDP report

  - A report parameter provides a way to choose report data, connect related reports together, and vary the report presentation. The parameters that an RDP class will reference are defined in a data contract class. You can attach the SysOperationLabelAttribute attribute to specify a label for a data member in a contract. You will see the text for the label identifier in the following places for reports:
    
      - For the label property for a parameter in Visual Studio.
    
      - For the parameter UI when the report displays in the Microsoft Dynamics AX client.
    
      - For the parameter UI when the report displays in Enterprise Portal.
    
    The following data contract parameter example illustrates the label identifier set to @SYS1334 in the InventABCContract class:
    
    ``` csharp
    [
        DataMemberAttribute(‘CategoryA’),
        SysOperationLabelAttribute(literalstr("@SYS1334"))
    ]
    public Percent parmCategoryA(Percent _categoryA = categoryA) 
    {
        categoryA = _categoryA; 
        return category;
    }
    
       
    ```

For information about how to pass parameters through code in Enterprise Portal, see [Report Parameters](https://technet.microsoft.com/library/hh330284\(v=ax.60\)).

