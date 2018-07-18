---
title: (GBR) Set up reverse charge VAT
TOCTitle: (GBR) Set up reverse charge VAT
ms:assetid: 2eb0f836-0bcd-4cff-be12-0a332719a8c5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg231022(v=AX.60)
ms:contentKeyID: 36056280
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: United Kingdom
---

# (GBR) Set up reverse charge VAT 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can account for reverse charge value added tax (VAT) that is required on sales and purchases of mobile telephones, computer chips, microprocessors, or central processing units for business purposes in the United Kingdom. Under reverse charge VAT rules, the purchaser of the goods, instead of the seller, is liable to account for VAT on the sale.

The vendor does not charge VAT, but any items that are subject to reverse charge VAT and the total amount of reverse charge VAT are noted on the invoice. These items are also identified on VAT 100 reports as being subject to reverse charge. You can use the **Reverse charge sales list** report to periodically view information about reverse charge sales and purchases. For more information, see [(GBR) Print - UK report (RCSalesList\_UK)](gbr-print-uk-report-rcsaleslist-uk.md).

## Set up general information for reverse charge VAT

Before you begin, switch to a legal entity whose primary address is in the United Kingdom.

1.  Click **Organization administration** \> **Setup** \> **Foreign trade** \> **Foreign trade parameters**.

2.  Click the **Country/region properties** link, and then click **New**.

3.  In the **Country/region** field, select the country/region code for the United Kingdom, such as **GBR**. Select **Domestic** in the **Country/region type** field.

4.  Close the form.

5.  Click **General ledger** \> **Setup** \> **Sales tax** \> **External** \> **Sales tax reporting codes**.

6.  Click **New**.

7.  In the **Report layout** field, select **English report layout**.

8.  In the **Reporting code** field, enter the number to represent the position for reporting information on tax reports, such as 9.

9.  In the **Report text** field, enter text to print on the report, such as Reverse charges, and then close the form.

10. Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax authorities**.

11. Click **New**.

12. In the **Authority** field, enter a unique identifier for the new authority.

13. In the **Name** field, enter the name of the new sales tax authority.

14. In the **Report layout** field, select **English report layout**. This will be used as the default entry in the **Sales tax codes** form.

15. Close the form.

## Set up sales tax codes for reverse charge VAT

You must set up negative and positive sales tax codes for reverse charge VAT. You will assign the negative sales tax code to an item sales tax group, and then assign that item sales tax group to the items that are subject to reverse charge VAT. For more information, see [Set up and use sales tax codes](set-up-and-use-sales-tax-codes.md).

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax codes**.

2.  Click **New**. Enter a sales tax code, such as **+17.5**, and a name.

3.  Select a settlement period.

4.  Select a ledger posting group.

5.  Click **Values**. On the **General** tab, enter the current tax rate as a positive number in the **Value** field. Close the form.

6.  In the **Sales tax codes** form, click the **Report setup** FastTab.

7.  Select the reporting code value that you entered in the **Sales tax reporting codes** form (for example, 9) in the following fields:
    
      - **Taxable sales**
    
      - **Taxable purchases**

8.  Select **Domestic** in the **Country/region type** field.

9.  Select the **Excluded** check box.
    

    > [!NOTE]
    > <P>This check box must be selected for tax codes that are set up for reverse charge VAT because vendor invoices that are entered in Accounts payable cannot appear on the European Union (EU) sales list.</P>



10. Click **New**.

11. Enter a sales tax code for negative sales taxes, such as -17.5, and a name.

12. Select the **Negative sales tax percentage** check box.

13. Repeat steps 3 through 11 to set up the tax code to use for reverse charge items. In step 6, enter the tax amount as a negative number.

14. Close the form.

## Set up a sales tax group for reverse charge VAT

You must set up a sales tax group for sales and purchases that are subject to reverse charge VAT. For more information, see [Set up and use a sales tax group](set-up-and-use-a-sales-tax-group.md).

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax groups**.

2.  Click **New**. Enter a name for the sales tax group, such as RC\_VAT.

3.  Select the **Reverse sales tax on cash discount** check box.

4.  On the **Setup** FastTab, click **Add**. Select the sales tax codes that you created in the previous procedure.

5.  Close the form.

## Update an item sales tax group for reverse charge VAT

You can use an existing item sales tax group for sales and purchases that are subject to reverse charge VAT.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Item sales tax groups**.

2.  Select an item sales tax group.

3.  On the **Setup** FastTab, click **Add**. Select the sales tax codes that you created in the "Set up sales tax codes for reverse charge VAT" procedure.

4.  Close the form.

## Set up inventory information for reverse charge VAT

Use this procedure to set up one or more item groups that can be assigned to items that are subject to reverse charge. Assign the item group to item records for mobile telephones, computer chips, microprocessors, or central processing units that you buy or sell for business purposes in the United Kingdom.

1.  Click **Inventory management** \> **Setup** \> **Inventory** \> **Item groups**.

2.  Click **New**. Enter an item group identifier, such as RevCharge, and a name.

3.  Set up an item group to identify products for which reverse charges are applicable. For more information, see [About item groups](about-item-groups.md) and [Item group (form)](https://technet.microsoft.com/en-us/library/aa575515\(v=ax.60\)).

4.  Click **Product information management** \> **Common** \> **Released products**.

5.  Select an item that is subject to reverse charge and then click **Edit** on the **Action Pane**.

6.  On the **Manage costs** FastTab, in the **Item group** field, select the item group that you created in step 2.

7.  Repeat steps 4 through 6 for the other items that are subject to reverse charge VAT.

8.  Close the form.

## Set up General ledger parameters for reverse charge VAT

Use this procedure to set up the minimum amount for an invoice or line item that is subject to reverse charge VAT, and to specify other information that is printed on invoices and reports. Before you begin, switch to a legal entity whose primary address is in the United Kingdom.


> [!NOTE]
> <P>The threshold amount is set by the United Kingdom government. For more information, contact your tax accountant.</P>



1.  Click **General ledger** \> **Setup** \> **General ledger parameters**.

2.  Click the **Reverse charge** link.

3.  Select the **Enable reverse charge** check box.

4.  In the **Invoice threshold** field group, you can select the **Invoice level threshold** check box and enter the minimum amount for an invoice to be considered for reverse charge VAT, such as 5000. Reverse charge VAT applies to the value of individual line items that do not meet the threshold amount, but whose total value on the invoice is equal to or exceeds the threshold amount.

5.  In the **Item line threshold** field group, you can select the **Item line threshold** check box for individual item lines to be considered for reverse charge VAT.

6.  In the **Item group** field, select the item group that you created in the "Set up inventory information for reverse charge VAT" section and enter the minimum amount for an invoice line to be considered for reverse charge VAT, such as 5000. Reverse charge VAT applies to the value of individual line items that are equal to or exceed the threshold amount.

7.  In the **Purchase order sales tax group** field, select the sales tax group that you created in the "Set up a sales tax group for reverse charge VAT" section.

8.  In the **Sales order sales tax group** field, select the sales tax group that you created in the "Set up a sales tax group for reverse charge VAT" section.

9.  In the **Contact details** field group, enter contact information to be printed on the **Reverse charge sales list** report that is submitted to the tax authority.

10. In the **Invoice text** field group, enter text to be printed on invoices, such as Customer to pay VAT to HMRC. An asterisk is printed next to each invoice line that contains an item that is subject to reverse charge VAT. The text that you enter here is printed at the bottom of the invoice.

11. Close the form.

## Specify a VAT number for your legal entity

Use this procedure to enter your legal entity’s VAT number for use with reverse charge VAT.

1.  Click **Organization administration** \> **Setup** \> **Organization** \> **Legal entities**.

2.  Select a legal entity.

3.  On the **Addresses** FastTab, select an address that has a country/region code for the United Kingdom in the **Address** field. For example, this might be GBR.

4.  On the **Tax registration** FastTab, enter your legal entity’s VAT number in the **Tax registration number** field.

5.  Close the form.

## Specify a VAT number for customers

Use this procedure to set up reverse charge VAT for a customer who purchases certain goods for a business purpose. If you do not specify a VAT number for the customer, the standard VAT rate is charged. For more information, see [Assign a tax exempt number to a customer](assign-a-tax-exempt-number-to-a-customer.md).

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  Double-click a customer account.

3.  On the **Invoice and delivery** FastTab, enter the customer's VAT registration number in the **Tax exempt number** field.

4.  Repeat steps 1 through 3 for the remaining customers who are subject to reverse charge VAT.

5.  Close the form.

## Specify a VAT number for vendors

Use this procedure to set up reverse charge VAT for a vendor from which you purchase certain goods for a business purpose. If you do not specify a VAT number for the vendor, the standard VAT rate is charged.

1.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.
    
    \-or-
    
    Click **Procurement and sourcing** \> **Common** \> **Vendors** \> **All vendors**.

2.  Double-click a vendor account.

3.  On the **Invoice and delivery** FastTab, enter the vendor's VAT registration number in the **Tax exempt number** field.

4.  Repeat steps 1 through 3 for the remaining vendors who are subject to reverse charge VAT.

5.  Close the form.

## See also

[(GBR) Create a purchase order that includes items subject to reverse charge VAT](gbr-create-a-purchase-order-that-includes-items-subject-to-reverse-charge-vat.md)

[(GBR) Create a sales order that includes items subject to reverse charge VAT](gbr-create-a-sales-order-that-includes-items-subject-to-reverse-charge-vat.md)

  


