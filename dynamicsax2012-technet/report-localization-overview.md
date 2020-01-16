---
title: Report Localization Overview
TOCTitle: Report Localization Overview
ms:assetid: fbd98161-7d23-423c-8a75-2fc7aaf83b6b
ms:mtpsurl: https://technet.microsoft.com/library/Cc642770(v=AX.60)
ms:contentKeyID: 28119625
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Report Localization Overview 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic provides information on labels and previewing a localized Microsoft Dynamics AX report. When creating reports using the Microsoft Visual Studio tools for Microsoft Dynamics AX, some things happen automatically for localization and do not require developer effort. For example, date values in reports are formatted based on the Microsoft Dynamics AX language specified for the user. The controls that appear in the report parameter dialogs use the Windows system regional settings. Other things require the use of labels, which does require work on the part of the developer.

## Labels

You can use labels for localizable text. Labels are created in the [Label Editor](https://technet.microsoft.com/library/aa617477\(v=ax.60\)). Labels are used on reports similarly to how they are used on forms. The style is slightly different to comply with the way that SQL Server Report Services references in the report definitions.

As you design your reports, you can create expressions that identify which labels to use. For example, the expression =Labels\!@SYS12345 indicates that a label with the Label ID of @SYS12345 is to be used. For more information about how to create expressions, see [Edit Expression Overview](edit-expression-overview.md).


> [!NOTE]
> <P>For precision design reports, the stock expression editor is used. You may receive a false error in the expression when you use a Microsoft Dynamics AX label in the expression. The label will appear correctly in the report.</P>



### Creating and Editing Labels

Use the Label Editor to find, edit, and create labels. To open the label editor:

  - In a Microsoft Dynamics AX Development Workspace, click **Tools** \> **Label** \> **Label editor**.

Labels can be single words, phrases, or sentences; sentence fragments should not be used because they cannot easily be translated. Labels can be up to 2000 characters long. For additional guidelines about how to create labels, see [Best Practices for Labels](https://technet.microsoft.com/library/aa586081\(v=ax.60\)) and [HelpText Guidelines](https://technet.microsoft.com/library/aa884538\(v=ax.60\)).

### Using Labels in Column Headings

To provide a label for the report column header, in Model Editor, click **Dataset** \> **Fields** and then click the field for which you want to provide a label. In the Properties window, enter a label in the **Caption** property.


> [!NOTE]
> <P>If you set the preview language to a non-English value, but data is displayed incorrectly in English, the field may be a dimension that requires that you manually set the label for the report column header.</P>
> <P>Examples of dimensions that are included with Microsoft Dynamics AX include Main Account, Department, Cost Center, and Purpose. Dimensions are based on extended data types that are defined as arrays.</P>



## Previewing Localized Reports at Design Time

When previewing a report at design time, you can preview a report for a particular culture as long as translated resources exist for that culture. To preview a report for a particular culture, select the culture from the **Preview Language** field in the **Preview** window in Microsoft Visual Studio.

## See also

[Globalizing and Localizing Applications](https://go.microsoft.com/fwlink/?linkid=108249)

