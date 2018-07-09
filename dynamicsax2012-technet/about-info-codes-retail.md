---
title: About info codes (Retail)
TOCTitle: About info codes (Retail)
ms:assetid: b4a9ce05-7a6c-4b5d-aa0a-bbccad371db7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh597212(v=AX.60)
ms:contentKeyID: 39519284
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Reason codes
- retail
- subcodes
- reason code
---

# About info codes (Retail) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Info codes provide a way for you to capture data at a point-of-sale (POS) register. You can use info codes to prompt the cashier to enter information during various actions at the POS, such as item sales, item returns, or selecting customers. Cashiers can select input from a list or enter it as a code, a number, a date, or text. You can assign info codes to predefined store actions, retail items, payment methods, customers, or specific point-of-sale activities.


> [!NOTE]
> <P>In versions of Microsoft Dynamics AX 2012 prior to AX 2012 R3, info codes in Retail were called reason codes. This topic refers to info codes, but the information also pertains to Retail reason codes in earlier versions of AX 2012, unless otherwise indicated.</P>



You can use info codes to do the following:

  - Capture additional information at transaction time, such as a flight number or the reason for a return.

  - Prompt the register cashier to select from a list of prices for specific products.

  - Link a subcode to an info code that prompts the cashier for input when performing a specific activity. For example, when a customer returns a product, you can prompt the cashier to ask why the product is being returned. Then you can use subcodes to display a list of reasons that the cashier can choose from.

  - Sell a product as a regular sale, discounted sale, or free product.

  - If you are using Microsoft Dynamics AX 2012 R3 or cumulative update 7 or later for AX 2012 R2, you can prompt the cashier to enter a value or select from a list of subcodes when they open the register drawer without performing a sales operation.

## About info codes in Retail in Microsoft Dynamics AX 2012 R3

In Retail in Microsoft Dynamics AX 2012 R3, you can create groups of info codes. Info code groups add flexibility by enabling you to define fewer info codes and then use them in more versatile ways.

You can use info code groups in the following ways:

  - Define fewer info codes and easily re-use them. Info codes that are included in info code groups have no predefined dependencies on other info codes. You can include the same info code in multiple info code groups and then use prioritization to present the same info codes in the order that makes sense in any particular situation.

  - Link info codes to other info codes or info code groups to gather information about a product or transaction in the way that you need without having to define a separate info code or linked info code for each scenario.

**Example 1: Reuse info codes**

In earlier releases of Microsoft Dynamics AX 2012, you can link info codes so that when one info code is triggered, another info code is triggered immediately after it. For example, when you sell certain products, you want to prompt the cashier to ask the customer if they want to purchase batteries and a product warranty. For other products, you want to prompt the cashier to ask the customer if they want to purchase batteries and also collect their postal code.

If you create linked info codes for these scenarios, you must set up every variation of the info code so that the cashier is prompted to ask for the right information. But if you use info code groups, common info codes, such as asking for batteries, can be set up once and then reused in multiple info code groups. You can also use prioritization in the info code groups to identify the order in which the prompts are displayed.

**Example 2: Link info codes to info code groups**

When you sell certain products, for example mobile devices, you always want to collect a set of specific information, such as telephone number, mobile equipment identifier (MEID), and serial number. However, you also want to collect different information for a tablet versus a mobile phone. You can set up an info code group that includes prompts for the telephone number, MEID, and the serial number and then link the info code group to an individual info code. When the product-specific info code is triggered, the info code group can be triggered next to enable you to collect the common data without having to define multiple sets of linked info codes for each device.

## See also

[Set up info codes](set-up-info-codes.md)

[Set up subcodes](set-up-subcodes.md)

[Set up info code groups](set-up-info-code-groups.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

