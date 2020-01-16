---
title: Validate and post trade agreement journal lines
TOCTitle: Validate and post trade agreement journal lines
ms:assetid: 396abf77-0fa8-484c-b6e5-446d5a932daf
ms:mtpsurl: https://technet.microsoft.com/library/Dn277351(v=AX.60)
ms:contentKeyID: 54658648
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- journal
- agreement
- trade
audience: Application User
ms.search.region: Global
---

# Validate and post trade agreement journal lines 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic explains how to validate and post trade agreement journal lines when you update sales prices and discounts. These updates can be applied manually or automatically to any related price or discount agreements, also known as trade agreements. For example, as a sales manager, you may want to increase sales prices for a specific product or for all products at the end of every calendar year, or you may want to offer discounted prices on specific products for a limited time as part of a campaign. Regardless of how many sales prices and discounts that you have to update, you can easily identify the prices and discounts to update, make the required changes, check for gaps and overlaps, and post the changes. When you post a trade agreement journal line, any related trade agreements are updated.

The following information describes how to update and validate sales prices, but you can also update and validate discounts in the same way by using the fields for discounts instead of prices.

## 1\. Update a sales price

There are two ways that you can update sales prices for products:

  - Specify a new fixed price

  - Make a general price adjustment based on a percentage or an amount

**Option 1** – Specify a new fixed price in a given currency for a specific product, customer, or customer group. You can selectively apply the price change based on certain criteria. For example, you can indicate that a specific item should cost one price if it is purchased in quantities less than 100, but it should cost a different price if it is purchased in quantities over 100.

To update sales prices by specifying a new fixed price, follow these steps:

1.  Click **Sales and marketing** \> **Journals** \> **Price/discount agreement journals**.

2.  Select a trade agreement journal or click **New** to create a new one. You can only update trade agreement journals that have not been posted.

3.  Click **Lines** to open the **Journal lines, price/discount agreement** form.

4.  Select the trade agreement journal line for the item to update the sales price for. There may be multiple lines for the same item.
    
    –or–
    
    Create a filter to display specific trade agreement journal lines. Click **Select**, and then enter the criteria to filter by. To display only the lines that include sales prices, you must select the **Prices** check box.

5.  In the **Amount in currency** field, enter the new sales price. Repeat this step for all of the lines to update.

6.  In the **From date** and **To date** fields, indicate the effective period for the sales price updates. Repeat this step for all of the lines to update.

**Option 2** – Make a general price adjustment. You can either adjust the price by a specific percentage or by a specific amount. For example, you can indicate that the current sales price for a product should expire on December 31 of the current calendar year and increase by two percent starting on January 1 of the next calendar year.

To update sales prices by making a general price adjustment, follow these steps:

1.  Follow steps 1 through 4 for **Option 1** earlier in this section.

2.  Click **Adjustment** and select **Adjustment** to open the **Price adjustment** form.

3.  In the **Price** field, select **Default sales price**.

4.  To adjust the selected price by a specific percentage, enter a value in the **Percentage** field. To adjust the selected price by a specific amount, enter a value in the **Amount** field.

5.  In the **From date** and **To date** fields, indicate the effective period for the sales price updates.

6.  Click **OK**. Repeat these steps for all of the lines to update.

## 2\. Validate and post a trade agreement journal line

After you have made the necessary price updates, you can validate the trade agreement journal lines, which will check for gaps and overlaps in the amounts or quantities. You must then post the lines to apply the changes to trade agreements.

To validate and post trade agreement journal lines, follow these steps:

1.  Click **Validate** to check the updated trade agreement journal lines for issues, such as gaps or overlaps in amounts or quantities. A message is displayed to provide information about validation issues. You can also see a summary of the validation issues on the **Message log** tab. You can decide whether to address the issues or to continue with posting.

2.  After you have verified the lines, click **Post** to post the lines and register the changes.


> [!NOTE]
> <P>If you have cumulative update 6 for Microsoft Dynamics AX 2012 or a later version installed, you can schedule a batch job to automatically process the validation and posting of all trade agreement lines at a specific time and recurrence. When you click <STRONG>Validate</STRONG> or <STRONG>Post</STRONG>, the <STRONG>Price/discount Journal posting</STRONG> form opens. Select the <STRONG>Batch processing</STRONG> check box, and then click <STRONG>Recurrence</STRONG> to set up a batch processing schedule.</P>



## Next step

After you have updated sales prices, you can continue to create sales orders, as usual. Any changes to sales prices that are effective immediately will be applied to new sales orders when you create them.

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Configuration keys</strong></p></td>
<td><p>No configuration key is required for this task.</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>To update prices and discounts and to validate and post trade agreement journal lines, you must be a member of a security role that includes the following duty:</p>
<ul>
<li><p><strong>Enable quotation to sales order process</strong> (SalesQuotationToSalesOrderProcessEnable)</p></li>
</ul></td>
</tr>
</tbody>
</table>


## See also

[Price adjustment (class form)](https://technet.microsoft.com/library/aa585775\(v=ax.60\))

[Journal lines, price/discount agreement (form)](https://technet.microsoft.com/library/aa553463\(v=ax.60\))

  


