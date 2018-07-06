---
title: About calculation variables
TOCTitle: About calculation variables
ms:assetid: cfab19ea-bd7e-433e-90be-32d3e63fcd5e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa550989(v=AX.60)
ms:contentKeyID: 36059481
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- product builder
- Calculation variables
---

# About calculation variables 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Unlike the modeling variables, calculation variables are invisible in the user dialog box. They can be used for various types of intermediate calculations in the product model, or to retrieve data from other parts of the system. For example, if a calculation must be performed by the product model, you can define calculation variables to handle the tasks. Calculation variables are created using the tabs in the upper pane of the **Product model** form. The tabs are described in the following table.


> [!NOTE]
> <P>This information applies only to Product builder.</P>



<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Tab page</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>System</strong></p></td>
<td><p>You can create system variables of the following variable types:</p>
<ul>
<li><p><strong>Transfer variable</strong></p></li>
<li><p><strong>BOM identification</strong></p></li>
<li><p><strong>Route identification</strong></p></li>
<li><p><strong>Lot ID</strong></p></li>
<li><p><strong>Item number</strong></p></li>
<li><p><strong>Configuration</strong></p></li>
<li><p><strong>Quantity</strong></p></li>
</ul>
<p><strong>System variable</strong> of the <strong>Lot ID</strong>, <strong>Item number</strong>, <strong>Configuration</strong>, and <strong>Quantity</strong> types are useful for transferring information from the order line or the quotation line to the current item configuration.</p>
<p>All system variables can be used to transfer values between parent and child product models.</p>
<div class="alert"> 

> [!NOTE]
> <P>Create only one system variable of each type, except for <STRONG>Transfer variable</STRONG>.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Simple</strong></p></td>
<td><p>Define calculation variables of the following types: <strong>Text</strong>, <strong>Integer</strong>, <strong>Real</strong>, and <strong>Enumerated text</strong>. Simple variables have no special functionality attached to them. They are used to hold calculation data.</p>
<p>Define variables using any Microsoft Dynamics AX extended data type, such as <strong>AccountNum</strong>, a data type intended to hold account numbers.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Data type</strong></p></td>
<td><p>Define variables using any Microsoft Dynamics AX extended data type, such as <strong>AccountNum</strong>, a data type intended to hold account numbers.</p></td>
</tr>
<tr class="even">
<td><p><strong>Table</strong></p></td>
<td><p>Define table variables. For example, this kind of calculation variable can be used within X++ code to handle any table defined in Microsoft Dynamics AX.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>Define class variables. For example, these variables can be used within X++ code to handle any class defined in Microsoft Dynamics AX.</p></td>
</tr>
</tbody>
</table>


Except for modeling variables, **Simple** and **Data type** variables are the most common variable types that are used in intermediate calculations and for building the logical conditions for the product model.

**Table** and **Class** variables are intended for users who have some programming experience. Their purpose is to allow the nodes for the product model, in the modeling tree, to handle Microsoft Dynamics AX tables and classes.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

