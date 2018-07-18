---
title: "What's new: Microsoft Office Add-in features"
TOCTitle: Microsoft Office Add-in features
ms:assetid: 30d87b6c-448c-4523-b020-63614776816d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn507091(v=AX.60)
ms:contentKeyID: 59623184
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# What's new: Microsoft Office Add-in features 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

We have changed and added functionality to the Office Add-ins for Microsoft Dynamics AX feature area for Microsoft Dynamics AX 2012. For more information, see the table that applies to your version of the product.

For more information, see [Integrating Microsoft Dynamics AX with Microsoft Office](integrating-microsoft-dynamics-ax-with-microsoft-office.md) in the Microsoft Dynamics AX 2012 Technical Library on TechNet. For more information about the Office Add-ins API, see [Using the Office Add-ins API](https://technet.microsoft.com/en-us/library/jj677288\(v=ax.60\)) on MSDN.

## What’s new in AX 2012

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>What’s new</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Integration with Microsoft Word is supported by Microsoft Dynamics AX.</p></td>
<td><p>This new feature lets you use Word to build templates and documents that combine structured and unstructured information from Microsoft Dynamics AX.</p>
<p>For more information, see <a href="about-using-the-microsoft-dynamics-ax-add-in-for-word.md">About using the Microsoft Dynamics AX Add-in for Word</a>.</p></td>
</tr>
<tr class="even">
<td><p>View and update data from Office tools.</p></td>
<td><p>You can use the Add-ins for Microsoft Excel and Word to view and analyze information in Microsoft Dynamics AX. You can use the Add-in for Excel to update information in Microsoft Dynamics AX.</p>
<p>For more information, see <a href="about-using-the-microsoft-dynamics-ax-add-in-for-excel.md">About using the Microsoft Dynamics AX Add-in for Excel</a>.</p></td>
</tr>
<tr class="odd">
<td><p>More enhancements to the integration with Excel are supported by the Microsoft Dynamics AX add-in.</p></td>
<td><p>The enhancements to this feature let you update data from Excel by using web services for Microsoft Dynamics AX Application Integration Framework (AIF). An opt-in checklist for built services is also available.</p>
<p>For more information, see <a href="use-microsoft-excel-to-import-and-export-data.md">Use Microsoft Excel to import and export data</a>.</p></td>
</tr>
</tbody>
</table>


## What’s new in Microsoft Dynamics AX 2012 R2

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Add descriptions to financial dimensions.</p></td>
<td><p>When you create an Excel workbook by using the Office Add-ins, you can add descriptions of financial dimensions to the ledger accounts that you select for the workbook, such as when you create a budget template.</p>
<p>For more information, see <a href="create-budget-plan-templates-manually.md">Create budget plan templates manually</a>.</p></td>
</tr>
<tr class="even">
<td><p>Lock a template that is created by using the Office Add-ins.</p></td>
<td><p>In budget planning scenarios, a partner or central administrator designs and deploys budget templates, and department leads or other personas fill in the numbers. To reduce the chance of error, the template designer can lock a template. This lock is not a security constraint. Template users can enter data into the locked template but cannot modify the template structure.</p>
<p>For more information, see <a href="https://technet.microsoft.com/en-us/library/jj677287(v=ax.60)">How to: Use Office Add-ins to Lock an Excel Spreadsheet</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Filter a workbook.</p></td>
<td><p>When you create a workbook by using the Office Add-ins, you can add filters to the data in the workbook. Users of the workbook can then view only the data that is selected in the filters. Additionally, you can add a <strong>readonly</strong> property to selected fields in the field list of the workbook.</p>
<p>For more information, see <a href="https://technet.microsoft.com/en-us/library/jj677294(v=ax.60)">How to: Add an Office Add-in Filter to a Spreadsheet</a>.</p></td>
</tr>
<tr class="even">
<td><p>Localize data in the Office Add-ins.</p></td>
<td><p>The Office Add-ins for AX 2012 R2 respect the current language setting of Microsoft Dynamics AX for the current user. A worksheet that was created by using the Office Add-ins matches the language selection, and labels in the workbook are displayed in the same language.</p></td>
</tr>
</tbody>
</table>


## What’s new in cumulative update 7 for Microsoft Dynamics AX 2012 R2

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Improved performance when you use the Office Add-ins</p></td>
<td><p>When you modify data that you exported from AX 2012 into an Excel workbook, and you then import the data back into Microsoft Dynamics AX, the import process requires less time.</p>
<p>For more information, see <a href="use-microsoft-excel-to-import-and-export-data.md">Use Microsoft Excel to import and export data</a>.</p></td>
</tr>
<tr class="even">
<td><p>Validate dimensions.</p></td>
<td><p>In the Add-in for Excel, a new <strong>Validate dimensions</strong> button helps you locate and correct financial dimensions that were entered incorrectly or that are suspended. This feature helps you perform tasks such as budgeting for dimensions.</p>
<p>For more information, see <a href="set-up-financial-dimensions-for-integrating-applications-excel-and-management-reporter.md">Set up financial dimensions for integrating applications (Excel and Management Reporter)</a> and <a href="create-budget-plan-templates-manually.md">Create budget plan templates manually</a>.</p></td>
</tr>
</tbody>
</table>

  


