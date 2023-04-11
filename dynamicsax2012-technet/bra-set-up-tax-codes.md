---
title: (BRA) Set up tax codes
TOCTitle: (BRA) Set up tax codes
ms:assetid: c53c7ba6-9ce2-4aa2-b7f8-cbccbad8dff7
ms:mtpsurl: https://technet.microsoft.com/library/JJ682106(v=AX.60)
ms:contentKeyID: 49655602
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- sales tax codes
- tax codes
- Brazil
- (BRA)
- set up sales tax
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up tax codes 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can specify which tax types require taxation codes. You can create taxation codes for tax types. You can set up a default taxation code that is used for a sales tax code when you create the sales tax code, attach the sales tax code to a sales tax group, or attach the sales tax code to an item sales tax groups.

## Specify mandatory tax types

Use this procedure to specify which tax types require taxation codes.

1.  Click **Organization administration** \> **Setup** \> **Brazil** \> **Brazilian parameters**.

2.  Click **Taxation code**, and then in the **Taxation code** area, select the **Mandatory** check box for each tax that requires a taxation code.

## Set up taxation codes

You can set up Sistema Público de Escrituração Digital (SPED) taxation codes that are used when you set up sales tax codes, sales tax groups, and item sales tax groups. You can specify fiscal values for the taxation codes. You can specify the SPED code, input taxation code, and output taxation code for the Imposto sobre Produtos Industrializados (IPI) tax type.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Taxation code**.

2.  Create a taxation code.

3.  In the **From date** and **To date** fields, specify the starting and ending dates of the period for which the taxation code is valid.

4.  In the **Tax type** field, select the type of tax for the taxation code.

5.  In the **Taxation code** and **Description** fields, enter the SPED taxation code and its description.

6.  In the **Fiscal value** field, select one of the following options to indicate the fiscal value of the taxation code:
    
      - **1. with credit/debit** – The transactions of the selected tax type are booked as credit in incoming fiscal documents or debit in outgoing fiscal documents. The calculated base and tax amounts are included as the taxable base amount and actual sales tax amount.
    
      - **2. without credit/debit (exempt or not taxable)** – The transactions of the selected tax type are not taxable. The tax base amount is included as the exempt base amount.
    
      - **3. without credit/debit (other)** – The transactions of the selected tax type are without credit in incoming fiscal documents or debit in outgoing fiscal documents. Tax is calculated but not booked separately. The calculated base and tax amounts are included as other base and other tax amounts.

7.  In the **SPED code** field, enter the second character of the IPI taxation code for the input taxation code or the output taxation code.
    

    > [!NOTE]
    > <P>This field is available only if you selected <STRONG>IPI</STRONG> in the <STRONG>Tax type</STRONG> field.</P>



8.  In the **Input taxation code** and **Output taxation code** fields, enter the first character of the input and output IPI taxation codes to specify the type of operation that is performed for incoming or outgoing item or service transactions.
    

    > [!NOTE]
    > <P>These fields are available only if you selected <STRONG>IPI</STRONG> in the <STRONG>Tax type</STRONG> field.</P>



## Set up a taxation code for a sales tax

You can set up a default taxation code for a sales tax code.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax codes**.

2.  Select or create a sales tax code. For more information, see the "Set up sales tax codes" section in [(BRA) Set up and calculate tax on sales and purchases](bra-set-up-and-calculate-tax-on-sales-and-purchases.md).

3.  Click the **Calculation** FastTab, and then in the **Tax type** and **Taxation code** fields, select a tax type and a taxation code.

You can set up taxation codes for each sales tax code that is attached to a sales tax group in the **Taxation code** field on the **Setup** FastTab in the **Sales tax groups** form.

## Specify exempt tax codes for sales tax groups

You can specify which tax codes in a sales tax group are exempt.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax groups**.

2.  Select or create a sales tax group. For more information, see [Set up and use a sales tax group](set-up-and-use-a-sales-tax-group.md).

3.  Click the **Setup** FastTab, and then in the **Sales tax code** field, select a sales tax code.

4.  Select the **Exempt** check box to indicate that the sales tax code is exempt.

5.  In the **Taxation code** field, select a taxation code for the sales tax code.
    

    > [!NOTE]
    > <P>The taxation code that you select must be for the same tax type as the sales tax that you selected in the <STRONG>Sales tax code</STRONG> field. Additionally, the taxation code must have a fiscal value of <STRONG>2. without credit/debit (exempt or not taxable)</STRONG> in the <STRONG>Taxation code</STRONG> form.</P>



## Set up tax codes for item sales tax groups

You can set up item sales tax groups in the **Item sales tax groups** form. You can specify which of the sales tax codes in the item sales tax group include credit, are exempt, or do not include credit.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Item sales tax groups**.

2.  Select or create an item sales tax group. For more information, see [Create item sales tax groups](create-item-sales-tax-groups.md).

3.  Click the **Setup** FastTab, and then in the **Sales tax code** field, select a sales tax code. The **Taxation code** field is updated with the taxation code for the sales tax codes that you selected in the **Taxation code** field on the **Calculation** FastTab in the **Sales tax codes** form. You can also update other taxation codes in the **Taxation code** field. The following fields are updated based on the fiscal value of the taxation code:
    
      - If the fiscal value for the taxation code is **2. without credit/debit (exempt or not taxable)** in the **Fiscal value** field in the **Taxation code** form, the **Exempt** check box is selected.
    
      - If the fiscal value for the taxation code is **3. without credit/debit (other)** in the **Fiscal value** field in the **Taxation code** form, the **Without tax credit** check box is selected.

4.  Select the **Exempt** check box to indicate that the transactions for the selected tax type are not taxable. If the taxation code that is selected in the **Taxation code** field has a fiscal value other than **2. without credit/debit (exempt or not taxable)**, the **Taxation code** field is cleared.
    

    > [!NOTE]
    > <P>You can select the <STRONG>Exempt</STRONG> check box if the taxation code for the tax type of the sales tax code is not set as mandatory.</P>



5.  Select the **Without tax credit** check box to indicate that the transactions for the selected tax type do not include credit or debit. If the taxation code that is selected in the **Taxation code** field has a fiscal value other than **3. without credit/debit (other)**, the **Taxation code** field is cleared.
    

    > [!NOTE]
    > <P>You can select the <STRONG>Without tax credit</STRONG> check box if the taxation code for the tax type of sales tax code is not set as mandatory.</P>



## See also

[(BRA) Brazilian parameters (form)](https://technet.microsoft.com/library/jj822920\(v=ax.60\))

[(BRA) Taxation code (form)](https://technet.microsoft.com/library/jj682104\(v=ax.60\))

[(BRA) Sales tax codes (modified form)](https://technet.microsoft.com/library/jj663982\(v=ax.60\))

[(BRA) Sales tax groups (modified form)](https://technet.microsoft.com/library/jj663981\(v=ax.60\))

[(BRA) Item sales tax groups (modified form)](https://technet.microsoft.com/library/jj682105\(v=ax.60\))

  


