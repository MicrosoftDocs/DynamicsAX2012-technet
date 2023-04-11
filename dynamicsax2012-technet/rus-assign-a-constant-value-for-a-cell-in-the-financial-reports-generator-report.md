---
title: (RUS) Assign a constant value for a cell in the Financial reports generator report
TOCTitle: (RUS) Assign a constant value for a cell in the Financial reports generator report
ms:assetid: da3412eb-82f8-4739-b2cc-3cb5540a9f4e
ms:mtpsurl: https://technet.microsoft.com/library/JJ923597(v=AX.60)
ms:contentKeyID: 52075443
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- constant
- financial reports generator
- text value
audience: Application User
ms.search.region: Russia
---

# (RUS) Assign a constant value for a cell in the Financial reports generator report 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Field setup** form to assign a constant numeric or text value for a cell in the Financial reports generator (FRG) report that uses a Microsoft Excel template. In the lower pane of the **Field setup** form, when you create two consecutive lines with numeric values, an arithmetic operation is performed, and the value is displayed in the cell. If one of the lines has a string value, it is concatenated with the line with the numeric value.

**Example**

For the values in the table below, the following line is created: 2500Rubles500Rubles900Rubles.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Operator</strong></p></th>
<th><p><strong>Line type</strong></p></th>
<th><p><strong>Data</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>+</strong></p></td>
<td><p><strong>Constant</strong></p></td>
<td><p>50</p></td>
</tr>
<tr class="even">
<td><p><strong>*</strong></p></td>
<td><p><strong>Constant</strong></p></td>
<td><p>50</p></td>
</tr>
<tr class="odd">
<td><p><strong>/</strong></p></td>
<td><p><strong>Constant</strong></p></td>
<td><p>Rubles</p></td>
</tr>
<tr class="even">
<td><p><strong>+</strong></p></td>
<td><p><strong>Constant</strong></p></td>
<td><p>500</p></td>
</tr>
<tr class="odd">
<td><p><strong>+</strong></p></td>
<td><p><strong>Constant</strong></p></td>
<td><p>Rubles</p></td>
</tr>
<tr class="even">
<td><p><strong>+</strong></p></td>
<td><p><strong>Constant</strong></p></td>
<td><p>300</p></td>
</tr>
<tr class="odd">
<td><p><strong>*</strong></p></td>
<td><p><strong>Constant</strong></p></td>
<td><p>3</p></td>
</tr>
<tr class="even">
<td><p><strong>+</strong></p></td>
<td><p><strong>Constant</strong></p></td>
<td><p>Rubles</p></td>
</tr>
</tbody>
</table>


Use the following procedure to assign a constant value for a cell.

1.  Click **General ledger** \> **Setup** \> **Financial reports generator** \> **Financial reports generator**. Select a report line, and then click **Setup**.
    
    –or–
    
    Click **General ledger** \> **Setup** \> **Financial reports generator** \> **Document templates**. Select a document template, and then click **Report**. Select a report line, and then click **Setup**.

2.  Select a report cell, and then in the lower pane, click **Add** to create a line.

3.  In the **Operator** field, select a mathematical operator that is applied to the cell value.

4.  In the **Line type** field, select **Constant**.

5.  In the **Data** field, enter the value that is used to calculate the cell value.

## See also

[(EEUR) Create report cell operations](eeur-create-report-cell-operations.md)

[(EEUR) Field setup (form)](https://technet.microsoft.com/library/jj910976\(v=ax.60\))

[(EEUR) Create and copy report cells](eeur-create-and-copy-report-cells.md)

[(EEUR) Report (form)](https://technet.microsoft.com/library/jj911237\(v=ax.60\))

  


