---
title: About budgeting on transactions and total amounts
TOCTitle: About budgeting on transactions and total amounts
ms:assetid: 9f6459e7-4b11-4cb9-8dd5-571aca65d941
ms:mtpsurl: https://technet.microsoft.com/library/Aa571741(v=AX.60)
ms:contentKeyID: 36058759
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About budgeting on transactions and total amounts 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you want to be able to analyze financial performance, you budget on transactions and total amounts by using a flexible budget.

In the **Budget** form, all cost categories, service categories, and cost lines are automatically displayed according to the cost category that is set up in the **Budget model** form. The same applies to dimensions. If specific dimensions are set up in the **Budget model** form, only these dimensions are displayed. Otherwise, you can select all dimensions.

In the **Plan cost values** form, you first fill in the **Dimension** and **Number** fields, and then you can either plan amounts for the whole year or plan a specific amount for each period.

You enter annual amounts for cost categories in the **Total** column in the **Primary costs** section. The amounts are automatically divided into 12 partial amounts, one for each month. If a period key is set up in the **Cost category setup** form, the amounts are divided according to the key.

To plan individual amounts for each month, you enter amounts in the columns for the months in the **Primary costs** section. Click **Calculate** to summarize monthly values in the **Total values** section. Be aware that this calculation is not done automatically.

You plan amounts for a service category or a cost line in the same way. You enter annual amounts in the **Total** column and individual amounts in the column for each the month.

The following table provides guidance for using the planning tabs in the **Plan cost values** form.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Cost categories</strong> tab</p></td>
<td><ul>
<li><p>If you are planning on cost categories, first select a value in the <strong>Cost component</strong> field (either <strong>Fixed costs</strong>, <strong>Variable costs</strong>, or <strong>Full costs</strong>), and then enter plan values for the cost categories.</p>
<div class="alert">

> [!NOTE]
> <P>If there is a calculation setup for a proportional dependency on another cost line in the <STRONG>Budget model</STRONG> form, you cannot manually enter amounts for those cost categories.</P>


</div></li>
<li><p>When you have finished entering plan values, click <strong>Calculate</strong>.</p></li>
<li><p>To display cost balances, click <strong>Cost balance</strong>.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Service categories</strong> tab</p></td>
<td><p>Budgeting on service categories works almost the same as budgeting on cost categories, except you do not have to select a value in the <strong>Cost component</strong> field. Budgeting differs depending on the type of service category. Planning on service categories of the <strong>General quantity itemization</strong> type is identical to planning on cost categories, because transactions are always single-entry (debit). Service categories of the <strong>Internal cost allocation</strong> type have double-entry transactions and are marked blue. You cannot plan on them directly. Instead, you enter the quantity in the lower pane of the form, which is the debit transaction, and then the credit transaction is created automatically in the upper pane.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Cost lines</strong> tab</p></td>
<td><p>If you are planning on cost lines, specify the cost component. You can only plan on the cost lines if the <strong>Budget</strong> check box is selected for the cost line on the <strong>Cost lines</strong> tab of the <strong>Cost category setup</strong> form. (Click <strong>Cost accounting</strong> &gt; <strong>Setup</strong> &gt; <strong>Budget model</strong>. Click <strong>Cost category setup</strong>.) When you select this check box, all cost categories that are included in the cost line are blocked and become blue. If the <strong>Budget</strong> check box is cleared, you can only plan on cost or service categories. In this case, the relevant cost line is blocked and becomes green.</p></td>
</tr>
</tbody>
</table>


## See also

[Flexible budgets](flexible-budgets.md)

  


