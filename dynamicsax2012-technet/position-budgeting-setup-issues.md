---
title: Position budgeting setup issues
TOCTitle: Position budgeting setup issues
ms:assetid: 43f7a88a-2058-4715-8fb9-ab9a65e0cc9c
ms:mtpsurl: https://technet.microsoft.com/library/Dn527693(v=AX.60)
ms:contentKeyID: 59626225
author: Khairunj
ms.date: 11/14/2014
mtps_version: v=AX.60
f1_keywords:
- issues
- budget
- issue
- position budget
- position budgeting
audience: Application User
ms.search.region: Global
---

# Position budgeting setup issues 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic contains answers to questions that you might have when you configure position budgeting. It addresses frequently asked questions about how to create budget cost elements, compensation groups, and compensation grids.

For detailed instruction about how to set up position budgeting, see [Set up position budgeting](set-up-position-budgeting.md).


> [!NOTE]
> <P>These features are available only if Microsoft Dynamics AX 2012 R3 or cumulative update 7 or later for AX 2012 R2 is installed and the <STRONG>Budget planning configuration key</STRONG> is selected.</P>



## Why can’t I delete a budget cost element?

You can’t delete a budget cost element that is assigned to a forecast position. Remove the budget cost element from all forecast positions before you delete it.


> [!TIP]
> <P>To locate all the positions that are assigned to a budget cost element, select the cost element in the <STRONG>Budget cost elements</STRONG> form and select <STRONG>Update positions</STRONG>. The positions that use the cost element are listed in the upper grid.</P>



## Is there a way to remove a cost element from multiple forecast positions without opening each one?

You can’t remove a cost element, but if you change the start and end date so that it falls outside of the budget planning cycle dates, it will no longer be assigned to the forecast positions in that budget planning cycle. To do this, open the budget cost element and click **Change dates** on the **Cost calculation** tab. Change the effective or expiration dates and click **OK** to automatically update all forecast positions that have the cost element assigned.


> [!TIP]
> <P>If you use this method, be aware that it will remove the budget cost element from ALL forecast positions in which the date is no longer within the appropriate range. If this is not what you are intending, you will need to open each forecast position that you want to remove the budget cost element from and manually make the change.</P>



## Why can’t I change the budget cost type from “earning” to another budget cost type?

Some budget cost elements use the “earning” cost element as a calculation basis. To change this field, remove the “earning” cost element from the **Calculation basis** tab of all budget cost elements.

## Why can’t I enter an annual amount in the Cost calculation tab of the budget cost element?

You can’t enter an annual amount if there are budget cost elements on the **Calculation basis** tab, because, the system requires a percentage to calculate the value. Remove all budget cost elements from the **Calculation basis** tab to change this value.

## Why can’t I change the date on budget cost element lines for a budget cost element?

You can’t change the date when a budget cost element is used by a forecast position. This is to make sure that the forecast positions are always within the guidelines of the budget cost element. To change the date, click the **Change dates** button on the **Cost calculation** tab and then click **Update positions** to update the positions that have the cost element assigned.

## Why can’t I change the costs for a budget cost element in the Compensation group form?

You can create and change budget cost elements only in the **Budget cost elements** form.

## Why do I get an error when I change the dates for a cost element on a forecast position?

The dates on the forecast position cost element line must fall within the following ranges:

  - The activation and retirement dates of the position.

  - The activation and expiration dates of the budget cost element.

  - The starting and ending dates of the budget cycle that is associated with the budget planning process of the forecast position.

## Don't see your question here?

We're working to include as many questions as we can, so that Microsoft Dynamics AX Help will be more useful to people just like you.

Tell us what question you would like to add to this topic. Send email to <adocs@microsoft.com>.

  


