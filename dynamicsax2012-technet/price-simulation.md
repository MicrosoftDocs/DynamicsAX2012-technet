---
title: Price simulation
TOCTitle: Price simulation
ms:assetid: cf4de4e8-e145-4eda-8518-5463c2172b42
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa550974(v=AX.60)
ms:contentKeyID: 36059478
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Price simulation 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A price simulation for a quotation shows a new total amount, based on a proposed new price. A price simulation can also show a new amount for a specific line that is created in an existing quotation. You can enter a price simulation and apply it later. Alternatively, you can use the original quotation without a price simulation, and make more changes as you work through the sales process with your customer.

A price simulation does not change the price in the quotation. If the price simulation is applied to a whole quotation, it is treated as a special discount on the quotation header. If the price simulation is applied to specific items, it is treated as a special discount on the quotation lines. The unit sales price on a quotation line that is created does not change when a price simulation is applied. Instead, a discount percentage that corresponds to the price reduction of the quotation line is applied. When a price simulation is applied, the unit sales price and the discount percentage are transferred to the quotation line or the quotation header.


> [!NOTE]
> <P>When you perform a price simulation, only the current sales currency is used to create the simulation. However, when you view the quotation totals, you see a combination of the company currency and the sales currency.</P>



Adding supplementary items to quotation lines can trigger line discounts or multiline discounts. Adding supplementary items can also trigger total discounts that change the contribution margins and contribution ratios of the quotation lines and the whole discount.

You can run multiple price simulations to track the effects of price adjustments on the targets of a quotation. By running these simulations, you can adjust the overall price of the quotation, or the price of one or more specific lines in the quotation, and then apply the price simulation that is most likely to help you close the sale.

When you create a quotation, you can set up an alert. Alerts have several uses. These include the following:

  - They can keep you informed about the status of quotations in the organization.

  - They can trigger a review of a specific quotation or inform you when discount limits are exceeded.

  


