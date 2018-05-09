---
title: Set up a sales tax on a sales tax
TOCTitle: Set up a sales tax on a sales tax
ms:assetid: 5722a578-9930-4f79-a55d-0df5b0aced59
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa549055(v=AX.60)
ms:contentKeyID: 39519141
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- sales tax
---

# Set up a sales tax on a sales tax 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can calculate sales tax as a percentage of another sales tax amount. This is called sales tax on sales tax.

To set up a sales tax on a sales tax, you must create a sales tax code and add it to the appropriate sales tax groups.

## Create a sales tax code based on another sales tax code

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax codes**.

2.  Click **New** to create a sales tax code.

3.  Enter information in the required fields. For more information, see [Sales tax codes (form)](https://technet.microsoft.com/en-us/library/aa553257\(v=ax.60\)).

4.  On the **Calculation** FastTab, in the **Origin** field, select **Percentage of sales tax**.

5.  In the **Sales tax on sales tax** field, select the code for the sales tax on which to calculate sales tax.
    

    > [!IMPORTANT]
    > <P>Do not select a sales tax code for which <STRONG>Percentage of gross amount</STRONG> is selected in the <STRONG>Origin</STRONG> field. Otherwise, the gross amount will include sales tax on the tax amount and tax on the sales tax amount.</P>



6.  Enter or select information in the other fields.

## Add a sales tax code to a sales tax group

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax groups**.

2.  Select the sales tax group to assign the sales tax code to.

3.  On the **Setup** FastTab, click **Add**.

4.  Select the sales tax code that you created in the previous procedure. The group must also include the sales tax code that you selected in the **Sales tax on sales tax** field in the previous procedure.

## Example

Invoice net amount = 10.00

Sales tax code Standard = 25%

Sales tax code Tax on tax = 10%

Sales tax is calculated as 10.00 x 25% = 2.50

Sales tax on sales tax is calculated as 10% of the sales tax amount = 2.50 x 10% = 0.25

Total sales tax = 2.50 + 0.25 = 2.75

## See also

[Sales tax codes (form)](https://technet.microsoft.com/en-us/library/aa553257\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

