---
title: About the provision for foreseeable losses
TOCTitle: About the provision for foreseeable losses
ms:assetid: 7ca3e189-57ac-4277-ba62-c52327e49001
ms:mtpsurl: https://technet.microsoft.com/library/Aa571519(v=AX.60)
ms:contentKeyID: 36058267
author: tfehr
ms.author: daxcpft
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- accrued loss
- completed contract assessment
- completed percentage assessment
- contract cost
- foreseeable loss
- contract revenue
audience: Application User
ms.search.region: Global
---

# About the provision for foreseeable losses 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If you determine that the total contract costs will exceed the total contract revenue, you can use the provision for foreseeable losses to recognize an expected loss on a project as an expense transaction.

If total costs exceed the contract value on an estimate project, the surplus expenses appear with a negative value in the **Accrued loss** field of the **Profit and loss** tab in the **Estimate** form.


> [!NOTE]
> <P>To open the <STRONG>Estimate</STRONG> form, depending on the version of the product that you are using, do one of the following:</P>
> <UL>
> <LI>
> <P>In Microsoft Dynamics AX 2012 R2: Click <STRONG>Project management and accounting</STRONG> &gt; <STRONG>Common</STRONG> &gt; <STRONG>Projects</STRONG> &gt; <STRONG>All projects</STRONG>. Select or open a Fixed-price or Investment project. In the <STRONG>Projects</STRONG> form, on the <STRONG>Revenue recognition</STRONG> FastTab, right-click the <STRONG>Estimate project ID</STRONG> field, and then click <STRONG>View details</STRONG> on the shortcut menu. In the <STRONG>Estimate projects</STRONG> form, in the <STRONG>Related information</STRONG> group, click <STRONG>Estimates</STRONG>.</P>
> <LI>
> <P>Otherwise: Click <STRONG>Project management and accounting</STRONG> &gt; <STRONG>Common</STRONG> &gt; <STRONG>Projects</STRONG> &gt; <STRONG>Estimate projects</STRONG>. On the <STRONG>Action Pane</STRONG>, on the <STRONG>Estimate project</STRONG> tab, in the <STRONG>Related information</STRONG> group, click <STRONG>Estimates</STRONG>.</P></LI></UL>



You can apply the provision for foreseeable losses to fixed-price projects and investment projects. If the total estimated costs on a fixed-price project exceed the contract value, the loss is taken immediately. For investment projects, a maximum capitalization limit applies.

How losses are posted depends on the project type and, for fixed-price projects, the matching principle that has been selected. In general, either accrued revenue is reduced or costs are accrued.

## Fixed-price projects

On a fixed-price project, a foreseeable loss is detected when the total estimated cost exceeds the total contract value.

## The completed contract method of revenue recognition

If the total estimated costs on the project exceed the contract value, costs beyond the contract value are accrued. The costs (amounts entered on the cost lines) are compared with the contract value. When the estimate is posted, the amount that exceeds the contract value is posted as an expense transaction on the WIP-accrued-loss or credit account. It is also posted on the accrued-loss or debit account.

## The completed percentage method of revenue recognition

If the total estimated costs on the project exceed the contract value, the amounts accrued as either sales value or profit is reduced. The costs (amounts entered on the cost lines) are compared with the contract value. When you use the following principles, the estimate is posted and the amount that exceeds the contract value is posted accordingly:

  - **Sales value** matching rule: **Accrued revenue - sales value** is posted to a **WIP - sales value** account.

  - **Production + profit** matching rule: **Accrued revenue - profit** is posted to a **WIP - profit** account.

## Investment projects

On an investment project, you must use maximum capitalization. The maximum capitalization limit determines what the WIP value of the project costs can amount to. The project costs are compared with the maximum capitalization amount, and the amount that exceeds the maximum capitalization limit is posted as an expense transaction on the **WIP - accrued loss** (credit) and the **Accrued loss** (debit) accounts.

Manually enter the maximum capitalization amount on the estimate. If the maximum capitalization limit is exceeded on a project, the surplus expenses appear in the **Accrued loss** field of the **Totals** tab in the **Estimate** form.

Estimate values that have been entered manually are not recalculated automatically if a loss occurs and the foreseeable losses check box is selected. This is so that you can record the percent-complete value for reporting.

## See also

[Estimate (form)](https://technet.microsoft.com/library/aa590971\(v=ax.60\))

[Set up a provision for foreseeable losses](set-up-a-provision-for-foreseeable-losses.md)

[Attach a project to an estimate](attach-a-project-to-an-estimate.md)

  


