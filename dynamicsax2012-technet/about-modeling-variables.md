---
title: About modeling variables
TOCTitle: About modeling variables
ms:assetid: cc21b59e-b09d-4876-9fcf-c7f8e3d47c0e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa572675(v=AX.60)
ms:contentKeyID: 36931880
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About modeling variables 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When a modeling enabled item is selected it must be configured. A modeling enabled item can be configured for one of the following: a sales order, sales quotation, purchase order, production order, project quotation, or item requirement. The customer or user makes all the required choices by using the product model’s user dialog box. The choices made will determine such attributes as the shape, color, size of the finished product. The product model’s set of modeling variables represents an analytical breakdown of the whole range of choices that make up an item's configuration. Modeling variables provide a common reference point for the transfer of default values to a specific product model. Modeling variables also provide for the transfer of variable values between two different product models. Before they can be included in product models and presented in user dialog boxes, these variables must be created in the **Modeling variables** form.


> [!NOTE]
> <P>This information applies only to Product builder.</P>



## Modeling variable types

Modeling variables must belong to a data type. Data types are used to control what the user can do in the input field of a modeling variable. In other words, they represent one form of control over the range of choices that are available in the product model’s user dialog box.

The following table lists the different data types that are available for modeling variables.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Type</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Text</strong></p></td>
<td><p>Variables of this type can hold any kind of text, and any input entered into them are interpreted as text.</p>
<p>If you select the <strong>Notes field</strong> check box on the <strong>General</strong> tab, a multiline field is displayed in the user dialog box instead of a single line of text.</p></td>
</tr>
<tr class="even">
<td><p><strong>Integer</strong></p></td>
<td><p>Variables of this type accept whole numbers only.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Real</strong></p></td>
<td><p>Variables of this type accept decimal numbers only. Use the <strong>Number of decimals</strong> field on the <strong>General</strong> tab to specify how many decimal places should be shown in the user dialog box.</p></td>
</tr>
<tr class="even">
<td><p><strong>Enumerated text</strong></p></td>
<td><p>A set of predefined outcomes or texts that can be attached to variables of this type.</p>
<p>In the user dialog box, the user can select one of these predefined texts. Nothing else can be selected.</p>
<p>Click <strong>Outcomes</strong> to specify the possible outcomes for an enumerated text variable.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Table</strong></p></td>
<td><p>Variables of this type can fetch data from any Microsoft Dynamics AX 2012 table and present it as a list of choices. The table and the table field from which date is fetched must be specified.</p>
<p>You can also specify a range for the table variable. You do this if you want to limit the set of values that will be presented to the user.</p></td>
</tr>
<tr class="even">
<td><p><strong>Boolean</strong></p></td>
<td><p>Variables of this type are presented to the user as a check box.</p>
<div class="alert"> 

> [!NOTE]
> <P>When using variables of this type in logical expressions, specify values for them by using 1 and 0.</P>


</div></td>
</tr>
</tbody>
</table>


## See also

[Modeling variables (form)](https://technet.microsoft.com/en-us/library/aa592160\(v=ax.60\))

  


