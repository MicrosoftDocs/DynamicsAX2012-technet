---
title: Set up catalog source codes
TOCTitle: Set up catalog source codes
ms:assetid: f8bcf272-fa88-47c0-a018-5fc9138c74f1
ms:mtpsurl: https://technet.microsoft.com/library/Dn497858(v=AX.60)
ms:contentKeyID: 62200188
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.TAMPromoStatistic
- MsDynAx060.Forms.TAMPromoStatistic
- Forms.MCRListBrokerTable
- Forms.MCRSourceCodeSetup
- Forms.MCRTargetSetup
- Forms.MCRRentalTypeTable
- Forms.MCRListTypeTable
- MsDynAx060.Forms.MCRTargetSetup
- MsDynAx060.Forms.MCRRentalTypeTable
- MsDynAx060.Forms.MCRSourceCodeSetup
- MsDynAx060.Forms.MCRListTypeTable
- MsDynAx060.Forms.MCRListBrokerTable
- source codes
- catalog campaigns
- catalog codes
audience: Application User
ms.search.region: Global
---

# Set up catalog source codes 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Companies that produce printed catalogs can use source codes to track the customer response to particular catalogs. Source codes are often printed on the back of a catalog and are entered in the sales order when a customer makes a purchase. This topic describes how to set up a source code for a catalog.

The process for setting up a source code includes the following tasks:

1.  Define a target market, which is a list of potential customers that the catalog is targeting.

2.  Create a source code.

3.  Associate the source code with both a catalog and a target market.

By tracking the codes that are entered in sales orders, the company can analyze the effectiveness of catalog mailings that are sent to various groups of customers.

## Prerequisites

The following table shows the prerequisites that must be in place before you start.

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
<td><p>Related setup tasks</p></td>
<td><p><a href="create-call-center-catalogs.md">Create call center catalogs</a></p></td>
</tr>
</tbody>
</table>


## 1\. Define a target market

A target market is a list of potential customers that a catalog is targeting. This list can be created internally by a company, or it can be purchased or rented.

First, you must define list types for the customer lists that you use, such as purchased or rented. You can also optionally define list brokers. To define list types and list brokers, follow these steps.

1.  Click **Call center** \> **Setup** \> **Types** \> **Lists** \> **List types**.

2.  Click **New** to create a new list type, and then enter a name and a description for the list type.

3.  In the **List type** field, select the type of list that you are creating: rented, purchased, or other.

4.  Repeat steps 2 through 3 to add all the list types that you require, and then close the **List types** form.

5.  Optional: Click **Call center** \> **Setup** \> **Types** \> **Lists** \> **List brokers**.

6.  Click **New** to create a new list broker record, and then enter a name and a description for the list broker. Repeat this step to add all the list brokers that you require, and then close the **List brokers** form.

Next, you must define a target market that has an associated list of customers. To define a target market, follow these steps.

1.  Click **Call center** \> **Journals** \> **Target market**.

2.  Click **New** to create a new target market.

3.  In the **Target market ID** field, enter a unique ID for the target market.

4.  In the **List name** field, select the type of list that is being used: rented, purchased, or other.

5.  Optional: On the **General** FastTab, enter the demographics for the list. This information indicates how recently and frequently purchases have been made for the customer list as a whole, and also the monetary value of those purchases.

6.  Optional: Under **Customer records**, enter the following information:
    
      - **Purchased** – The number of names that were purchased when the list was brokered.
    
      - **Used** – The number of names from the list to include in the target market.

7.  On the **Customers** FastTab, click **New**, and then enter the account number and name of a customer or prospective customer who is in the target market. Repeat this step to add more customers to the list.

8.  Close the **Target market definition** form.

## 2\. Create a source code

The source code associates a catalog with a target market. You can optionally add budget information to the source code, such as projected sales, printing and mailing costs, and distribution quantity. You can also associate the code with a campaign.

To create a source code, follow these steps.

1.  Click **Retail** \> **Common** \> **Catalogs** \> **Catalogs**.

2.  Select the catalog to associate with a source code, and then, on the **Action Pane**, click **Edit**.

3.  On the **Source codes** FastTab, click **Add**.

4.  In the **Source code ID** field, enter a unique ID for the source code.

5.  In the **Target market ID** field, enter the ID of the target market that you created in the previous procedure.

6.  Optional: On the **Source codes** FastTab, click **Details**. In the **Source code definition** form, on the **General** tab, enter additional data for the source code:
    
      - In the **Budgets** section, enter any budget data to track for the source code, such as projected sales, mailing costs, and printing costs.
    
      - In the **Drop information** section, enter information about the mail drop that will contain catalogs that have the source code.
    
      - In the **Campaign** section, enter the ID of the campaign that the source code is associated with, if the source code is associated with a campaign.

7.  Publish the catalog, as described in [Create call center catalogs](create-call-center-catalogs.md).


> [!NOTE]
> <P>Before you can use source codes in sales orders, the <STRONG>Enable directed selling</STRONG> check box must be selected in the channel settings for the call center. For more information, see <A href="set-up-a-call-center.md">Set up a call center</A>.</P>



## 3\. Optional: Set up source codes for exchanges

You can set parameters to specify which source code to use when customers make exchanges. For more information, see the **RMA/Return** section in [Configuring parameters and initial settings (Call center)](configuring-parameters-and-initial-settings-call-center.md).

## Next step

After a source code has been set up, you can use the source code in sales orders. For more information, see [Enter a catalog source code](enter-a-catalog-source-code.md). After sales orders have been created that reference the source code, you can view and analyze sales data for the source code. For more information, see [Analyze source code data](analyze-source-code-data.md).

## Related tasks

[Create call center catalogs](create-call-center-catalogs.md)

[Enter a catalog source code](enter-a-catalog-source-code.md)

[Analyze source code data](analyze-source-code-data.md)

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
<td><p><strong>Retail Headquarters</strong> configuration key</p>
<p><strong>Call center</strong> configuration key</p>
<p><strong>Source code</strong> configuration key</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>Sales manager</p></td>
</tr>
</tbody>
</table>


## See also

[Perform a catalog area analysis](perform-a-catalog-area-analysis.md)

  


