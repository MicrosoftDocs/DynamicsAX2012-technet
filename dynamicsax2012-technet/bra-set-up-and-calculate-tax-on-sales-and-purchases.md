---
title: (BRA) Set up and calculate tax on sales and purchases
TOCTitle: (BRA) Set up and calculate tax on sales and purchases
ms:assetid: ad29bccc-5629-45fc-8d24-23488f7b8331
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ683238(v=AX.60)
ms:contentKeyID: 49685119
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- calculate tax
- sales and purchases
- set up tax
- purchases and sales
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up and calculate tax on sales and purchases 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can set up and calculate sales taxes on sales, purchases, transfers between fiscal establishments, delivery of items to a third party, or receipt of items from a third party.

## Set up sales tax parameters

1.  Click **General ledger** \> **Setup** \> **General ledger parameters**.

2.  In the **General ledger parameters** form, in the left pane, click **Sales tax**.

3.  In the **Sales tax** area, in the **Calculation method** field, select **Line**.

4.  Clear the **Apply U.S. taxation rules** and **Conditional sales tax** check boxes.

## Specify a sales tax expense account for a ledger posting group

Use this procedure to specify a sales tax expense account for a ledger posting group. The sales tax expense account is an offset account for the sales tax that is payable. For each tax entry that is generated with the accounts that are configured in the **Sales tax payable** field in the **Ledger posting groups** form, a debit ledger entry is generated with the account that is defined in the **Sales tax expense** field.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Ledger posting groups**.

2.  Select or create a ledger posting group. For more information, see [(BRA) Set up ledger posting groups for sales tax](bra-set-up-ledger-posting-groups-for-sales-tax.md).

3.  In the **Sales tax expense** field, select a sales tax expense account to post the tax expenses to.
    

    > [!NOTE]
    > <P>You can select only a main account for which <STRONG>Sales tax expense</STRONG> is selected in the <STRONG>Posting type</STRONG> field in the <STRONG>Accounts for automatic transactions</STRONG> form.</P>



## Set up sales tax codes

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax codes**.

2.  Select or create a sales tax code. For more information, see the "Create a sales tax code" section in [Create various kinds of sales tax codes](create-various-kinds-of-sales-tax-codes.md).

3.  In the **Settlement period** and **Ledger posting group** fields, select a settlement period and a ledger posting group for the sales tax.

4.  Click the **Calculation** FastTab, and then in the **Tax type** and **Taxation code** fields, select a tax type and a taxation code.

5.  In the **Origin** field, select a method to calculate the selected sales tax code. This calculation method is applied to the tax base amount. For more information, see [About the sales tax calculation methods in the Origin field](about-the-sales-tax-calculation-methods-in-the-origin-field.md).

6.  In the **Marginal base** field, select **Net amount per line**. For more information, see [About the Marginal base field](about-the-marginal-base-field.md).

7.  Select the **Retained tax/to recuperate** check box to retain tax from the supplier for a purchase, or to recover tax from a customer for a sales transaction for the sales tax code. For a purchase transaction, the tax amount is deducted from the total invoice amount that is paid to the vendor. For a sales transaction, the tax amount is deducted from the total invoice amount that is received from the customer. If this check box is selected, the **Included tax** and **Tributary substitution method** fields are not available.
    
    The **Retained tax/to recuperate** check box is selected for the Imposto Nacional de Seguridade Social (**INSS**), Imposto de Renda Retido na Fonte (**IRRF**), Imposto sobre Serviços (**ISS**), and **Retained INSS** tax types.
    

    > [!NOTE]
    > <P>The <STRONG>Retained tax/to recuperate</STRONG> check box is not available if you select <STRONG>Import tax</STRONG>, <STRONG>ICMS-ST</STRONG>, or <STRONG>ICMS-DIF</STRONG> in the <STRONG>Tax type</STRONG> field.</P>



8.  Select the **Included tax** check box to include the sales tax in the sales or purchase price. The total invoice amount includes the tax that is specified on the tax code. If you clear this check box, the sales tax is not included in the sales or purchase price. However, the sales tax is included in addition to the sales price on the invoice. If this check box is selected, the **Retained tax/to recuperate** and **Tributary substitution method** fields are not available.
    
    The **Included tax** check box is selected for the Imposto sobre Circulação de Mercadorias e Serviços (**ICMS**), Program de Integracao Social (**PIS**), and Contribuição para Financiamento da Seguridade Social (**COFINS**) tax types.
    

    > [!NOTE]
    > <P>The <STRONG>Included tax</STRONG> check box is not available if you select <STRONG>Import tax</STRONG> or <STRONG>ICMS-ST</STRONG> in the <STRONG>Tax type</STRONG> field.</P>



9.  In the **Tributary substitution method** field, select **Markup** or **Simplified estimate** as the method to use to calculate the tributary substitution. Tax substitution is the collection of sales tax at the first point of sale, where the markup tax rate is estimated by the fiscal authorities. This is done to expedite the collection of taxes.
    
    If you select **Markup** or **Simplified estimate** in the **Tributary substitution method** field, the **Origin** field is updated to **Percentage of gross amount**. You can select a sales tax code of the **IPI** tax type in the **Sales tax on sales tax** field, and enter the tax value and the markup percentage in the **Value** and **Markup** fields in the **Values** form. The markup represents the estimated markup percentage.
    

    > [!NOTE]
    > <P>The <STRONG>Tributary substitution method</STRONG> field is available only if you select <STRONG>ICMS-ST</STRONG> in the <STRONG>Tax type</STRONG> field.</P>



10. Click **Values** to open the **Values** form.

11. Press CTRL+N to create a record, and then in the **Value** field, specify the tax percentage.

12. In the **Tax reduction pct** field, specify the tax reduction percentage. The tax base reduction percentage is the percentage of the reduced tax base.

13. In the **Markup** field, specify the markup percentage to apply to calculate the tax on the tributary substitution.
    

    > [!NOTE]
    > <P>The markup is calculated only when <STRONG>Markup</STRONG> or <STRONG>Simplified estimate</STRONG> is selected in the <STRONG>Tributary substitution method</STRONG> field in the <STRONG>Sales tax codes</STRONG> form.</P>



## Set up taxes as exempt or without credit

There are some operations that do not grant rights of credit, depending on the fiscal operations in Brazil. These include the following examples:

  - For purchases made for commercialization purposes, IPI does not have rights of tax credit, but it is available in the fiscal document.

  - For purchases made for use and consumption purposes, ICMS does not have rights of tax credit, but it is available in the fiscal document.

  - Exported items are exempt from IPI and ICMS.

  - Small items that are distributed as free samples with no commercialization amount are exempt from IPI and ICMS.

  - Remittance of items as demonstrations or repairs is exempt from IPI and ICMS in intrastate operations.

The following setup is required for taxes without credit:

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Item sales tax groups**.

2.  Select or create an item sales tax group. For more information, see [Create item sales tax groups](create-item-sales-tax-groups.md).

3.  Click the **Setup** FastTab.

4.  Click **Add**, and then in the **Sales tax code** field, select a sales tax code.

5.  Select the **Without tax credit** check box, or select a taxation code with a **3. without credit/debit (other)** fiscal value in the **Taxation code** field to indicate that the sales tax code is without credit.

6.  Select the **Exempt** check box, or select a taxation code with a **2. without credit/debit (exempt or not taxable)** fiscal value in the **Taxation code** field to indicate that the sales tax code is exempt.

Taxes can also be set up as exempt in the **Sales tax groups** form by using a taxation code with a **2. without credit/debit (exempt or not taxable)** fiscal value, or by selecting the **Exempt** check box on the **Setup** FastTab.

When you set up taxes without tax credit:

  - For vendor invoices that do not have credit, the tax amount is not posted to the ledger. The tax amount is added to the cost of the item when the purchase order is invoiced.

  - For customer invoices, tax-related transactions are not generated, but the tax amount is calculated and added to the invoice.

## Calculate tax on sales orders or purchase orders

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.
    
    –or–
    
    Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Select or create a sales order or purchase order. For more information, see [(BRA) Create and post a sales order](bra-create-and-post-a-sales-order.md)

3.  Select or create a sales order line or purchase order line, and then click the **Line details** FastTab.

4.  Click the **Setup** tab.

5.  In the **Sales tax group** and **Item sales tax group** fields, select a sales tax group and an item sales tax group.

6.  In the **Sales order** form, on the **Action Pane**, click **Invoice** \> **Invoice**, and then click **OK** to post the sales order.
    
    –or–
    
    In the **Purchase order** form, on the **Action Pane**, click **Invoice** \> **Invoice**. In the **Vendor invoice** form, on the **Action Pane**, click **Post** \> **Post** to post the purchase order.

7.  Close the form.

8.  Click **General ledger** \> **Inquiries** \> **Tax** \> **Posted sales tax**. Click **OK**.
    
    –or–
    
    Click **Accounts payable** \> **Inquiries** \> **Journals** \> **Invoice journal**. Click **Posted sales tax**.
    
    –or–
    
    Click **Accounts receivable** \> **Inquiries** \> **Journals** \> **Invoice journal**. Click **Posted sales tax**.
    
    –or–
    
    Click **Project management and accounting** \> **Reports** \> **Project invoices** \> **Project invoice journals**. Click **Posted sales tax**.

9.  Click the **Amount** tab to view the following information:
    
      - **Tax reduction pct** – The tax base reduction percentage.
    
      - **Exempt base amount** – The base amount for which the sales tax is exempt. This field is updated when an invoice is posted either with a **2. without credit/debit (exempt or not taxable)** fiscal value, or for the reduced base on which taxes are not calculated.
    
      - **Taxable base amount** – The base amount on which the sales tax is calculated. This field is updated when the invoice is posted with a **1. with credit/debit** fiscal value.
    
      - **Taxable amount** – The sales tax amount when the invoice is posted with a **1. with credit/debit** fiscal value.
    
      - **Other base amount** – The base amount on which the sales tax is calculated without credit or debit. This field is updated when the invoice is posted with a **3. without credit/debit (other)** fiscal value.
    
      - **Other tax amount** – The sales tax amount when the invoice is posted with a **3. without credit/debit (other)** fiscal value.

## See also

[(BRA) Sales tax codes (modified form)](https://technet.microsoft.com/en-us/library/jj663982\(v=ax.60\))

[(BRA) Sales tax groups (modified form)](https://technet.microsoft.com/en-us/library/jj663981\(v=ax.60\))

[(BRA) Item sales tax groups (modified form)](https://technet.microsoft.com/en-us/library/jj682105\(v=ax.60\))

[(BRA) Posted sales tax (modified form)](https://technet.microsoft.com/en-us/library/jj710417\(v=ax.60\))

[General ledger parameters (form)](https://technet.microsoft.com/en-us/library/aa557286\(v=ax.60\))

[(BRA) Posted sales tax (modified form)](https://technet.microsoft.com/en-us/library/jj710417\(v=ax.60\))

  


