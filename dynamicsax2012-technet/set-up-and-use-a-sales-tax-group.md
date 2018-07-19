---
title: Set up and use a sales tax group
TOCTitle: Set up and use a sales tax group
ms:assetid: 6e26615e-d473-4d7d-a9db-2c706d9a681f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa571215(v=AX.60)
ms:contentKeyID: 36058035
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up and use a sales tax group 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

1.  Create sales tax codes in the **Sales tax codes** form. For more information, see [Set up and use sales tax codes](set-up-and-use-sales-tax-codes.md).

2.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax groups**.

3.  Click **New** to create a line for a new sales tax group, and enter a unique code for the sales tax group in the **Sales tax group** field. You can also enter a name for the sales tax group in the **Description** field.

4.  View or change the default values in the following fields:
    
      - **Sales tax group setup**
    
      - **Rounding by**
    
      - **Print**

5.  On the **Setup** tab, add the sales tax codes that apply to the selected sales tax group.
    

    > [!NOTE]
    > <P>If the company operates in the United States, you can also add sales tax jurisdictions that contain sales tax codes to the sales tax group. For more information, see <A href="set-up-sales-tax-groups-for-jurisdictions.md">Set up sales tax groups for jurisdictions</A>.</P>

    
    The description and the percentage or amount of the sales tax code are entered automatically.

6.  If the sales tax code on the sales tax group is used for tax exemption, intra-community VAT, or use tax, select the appropriate check boxes. Select a value in the **Exempt code** field, if appropriate. For more information, see [Sales tax groups (form)](https://technet.microsoft.com/en-us/library/aa498345\(v=ax.60\)).

7.  On the **Invoice and delivery** tab of the **Customers** form, select a sales tax group for each customer. This is the default sales tax group for transactions that involve the customer. You can change this value on individual transactions.

8.  On the **Invoice and delivery** tab of the **Vendors** form, select a sales tax group for each vendor. This is the default sales tax group for transactions that involve the vendor. You can change this value on individual transactions.

9.  On the **Setup** tab of the **Main accounts - chart of accounts: %1** form, select a default sales tax group for each ledger account to which purchases or sales that do not include a customer or vendor are posted. An example might be a ledger account for office equipment.
    
    You must select **Legal entities** in the **Select the level of main account to display** field and select a legal entity to view the sales tax information.


> [!NOTE]
> <P>For reporting purposes in some countries/regions, you might have to create a sales tax group that contains a single sales tax code with a sales tax percentage or amount of zero. This sales tax group is applied to customers who are exempt from sales taxes and to ledger accounts to which sales taxes do not apply, such as bank accounts.</P>


  


