---
title: (BRA) Configure Microsoft Dynamics AX for Retail POS
TOCTitle: (BRA) Configure Microsoft Dynamics AX for Retail POS
ms:assetid: 313ab46d-9208-4032-b674-01fb37d8305d
ms:mtpsurl: https://technet.microsoft.com/library/Dn497714(v=AX.60)
ms:contentKeyID: 62200231
author: tonyafehr
ms.date: 04/28/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.SalesTableListPage
- Forms.SalesTable
- Forms.SalesEditLines
- Forms.RetailHardwareProfile
- Forms.RetailFunctionalityProfile
- Forms.RetailTenderTypeTable
- Forms.RetailTillLayout
- Forms.RetailStoreTable
- Forms.TmpFiscalReference_BR
audience: Application User
ms.search.region: Brazil
---

# (BRA) Configure Microsoft Dynamics AX for Retail POS 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Follow the steps in this topic to configure Microsoft Dynamics AX for Retail POS for the Brazilian market.

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
<td><p><strong>Version</strong></p></td>
<td><p>Retail in AX 2012 R2 or AX 2012 R3 is installed.</p></td>
</tr>
<tr class="even">
<td><p><strong>Country/region</strong></p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: Brazil</p></td>
</tr>
</tbody>
</table>


## Set up a retail store

Use the **Stores** form to set up a retail store.

To perform this task, follow these steps:

1.  Click **Retail** \> **Common** \> **Retail channels** \> **Retail stores**.

2.  Click **Retail store** to create a record, or double-click an existing record to open the **Stores** form. For more information, see [Set up a retail store](set-up-a-retail-store.md).

3.  Select the **Prices include sales tax** check box.

4.  In the **Default customer** field, select a customer account that is marked as the final user and located in the same state as the store.

## Set up a functionality profile, and then assign the functionality profile to a store

Use the **POS functionality profile** form to set up a functionality profile, and then assign it to a store.

To perform this task, follow these steps:

1.  Click **Retail** \> **Setup** \> **POS** \> **Profiles** \> **Functionality profiles**.

2.  Select or create a functionality profile. For more information, see “Set up functionality profiles” in [Set up and assign functionality profiles](set-up-and-assign-functionality-profiles.md).

3.  On the **General** FastTab, in the **ISO** field, select the ISO code for the country/region in which the store is located.

4.  On the **Functions** FastTab, select the **Print X/Z report on POS** check box.

5.  Ensure that the **Aggregate products**, **Aggregate payments**, and **Aggregate products for printing** check boxes are cleared.

6.  Close the form, and then assign the functionality profile to a store. For more information, see “Assign a functionality profile to a store” in [Set up and assign functionality profiles](set-up-and-assign-functionality-profiles.md).

## Set up a hardware profile, and then assign the hardware profile to a POS register

Use the **POS hardware profile** form to set up a hardware profile, and then assign it to a POS register.

To perform this task, follow these steps:

1.  Click **Retail** \> **Setup** \> **POS** \> **Profiles** \> **Hardware profiles**.

2.  Select or create a hardware profile. For more information, see “Set up hardware profiles” in [Set up hardware profiles](set-up-hardware-profiles.md).

3.  On the **Printer** FastTab, in the **Printer** field, select a printer.

4.  In the **Description** field, enter a description for the printer that is assigned to the store.

5.  In the **Management reports** field group, enter information in the **Configuration parameters**, **PAF-ECF identification**, and **Payment methods** fields.
    

    > [!NOTE]
    > <P>The <STRONG>Management reports</STRONG> parameters must have the same values as the management reports that you configured for the fiscal printer.</P>



6.  In the **Gift card totalizer name** field, enter the corresponding non-fiscal totalizer for the fiscal printer.

7.  Close the form, and then assign the hard profile to a POS register. For more information, see “Assign a hardware profile to a register” in [Set up hardware profiles](set-up-hardware-profiles.md).

## Set up fiscal printer integration

The integration with the fiscal printer uses some components that are provided by the fiscal printers’ manufacturers, which can be Daruma or Bematech. To integrate Microsoft Dynamics AX with a fiscal printer, follow these steps:

1.  Obtain the necessary fiscal printer components from the manufacturer of the fiscal printer.
    
      - For Daruma printers, the necessary components are DarumaFrameWork.dll, lebin.dll, and LeituraMFDBin.dll.
    
      - For Bematech printers, the necessary components are BemaFI32.dll, BemaMFD.dll, BemaMFD2.dll, and sign\_bema.dll.

2.  Copy the components into the folder c:\\ProgramFiles\\Microsoft Dynamics AX\\60\\Retail POS or c:\\ProgramFiles (x86)\\Microsoft Dynamics AX\\60\\Retail POS.

For more information about how to configure fiscal printers, see [(BRA) Configure fiscal printers](bra-configure-fiscal-printers.md).

## Set up payment methods for an organization

If the fiscal printer has tender types that were previously configured, these tender types must be associated with the tender types in Microsoft Dynamics AX. You can do this by using the **Payment methods** form.


> [!NOTE]
> <P>You can group payment methods based on the type of payment that they are used for, such as credit card payments or debit card payments.</P>



To associate the fiscal printer’s tender types with the tender types in Microsoft Dynamics AX, follow these steps:

1.  Click **Retail** \> **Setup** \> **Payment methods** \> **Payment methods**.

2.  Select or create a payment method. For more information, see [Set up payment methods for an organization](set-up-payment-methods-for-an-organization.md).

3.  In the **Payment method name in fiscal printer** field, enter the corresponding name of the payment method that is configured for your fiscal printer. You can enter separate values for credit or debit cards, and then map them to the payment method that is assigned to the printer.
    

    > [!IMPORTANT]
    > <P>This payment method configuration is used for all POS terminals for all of the stores that are set up in Microsoft Dynamics AX. Therefore, it’s necessary to enter the same <STRONG>Payment method name in fiscal printer</STRONG> value for each fiscal printer that is assigned to a store.</P>



## Set up tax codes for POS

The POS uses the same sales tax setup that is configured to determine tax rates for Brazil. The Código Fiscal de Operações e Prestações (CFOP) matrix is not used for POS transactions in Brazil. Therefore, you need to specify an item sales tax group for each item. For more information about setting up tax, see [(BRA) Set up ledger posting groups for sales tax](bra-set-up-ledger-posting-groups-for-sales-tax.md), [(BRA) Set up taxation origin for items](bra-set-up-taxation-origin-for-items.md), [(BRA) Set up CFPS codes](bra-set-up-cfps-codes.md), and [(BRA) Set up tax codes](bra-set-up-tax-codes.md).

Apart from the standard tax codes that are used to determine tax rates, you must use the **Sales tax codes** form to set up sales tax codes that begin with the following letters, based on their respective tax exceptions:

  - **F** – Use tributary substitution to determine tax rates for sold items.

  - **I** – Determine tax rates for exempt items.

  - **N** – The sold items are non-taxable.

## Determine CFOP code for fiscal receipts

The CFOP for a fiscal receipt is determined based on the product type of the item, which must be set up based on the Public Digital Bookkeeping System (SPED) fiscal definition. You can specify a product type for the item by using the **Released product details** form. For more information, see [(BRA) Released product details (modified form)](https://technet.microsoft.com/library/jj923408\(v=ax.60\)).


> [!NOTE]
> <P>If the tax code begins with the letter “F,” and if the item is not a service item, the CFOP will be 5.405.</P>



The following table explains how the CFOP is determined for a fiscal receipt.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Operation number</p></th>
<th><p>Operation parameter</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>03, 04, 05, 06</p></td>
<td><p>5.101</p></td>
</tr>
<tr class="even">
<td><p>00, 01, 02, 07, 08, 10, 99</p></td>
<td><p>5.102</p></td>
</tr>
<tr class="odd">
<td><p>09</p></td>
<td><p>5.933</p></td>
</tr>
</tbody>
</table>


## Set up the fiscal document model 2

If the fiscal printer cannot be used because of a hardware problem, or if there is a communication error between Microsoft Dynamics AX and the fiscal printer, all sales that are made during this period are not printed in a standard fiscal receipt. These sales must be registered in the POS system by using the Fiscal document model 2.

To set up the POS to add a Fiscal document model 2, follow these steps:

1.  Create a blank operation.

2.  Set the **Operation name** field to **3**.

3.  Leave the **Blank operation param** field blank.

## Design a screen layout to include the mandatory columns for items

The POS sales screen in Microsoft Dynamics AX must display some mandatory columns for items. You can use the **Screen layouts** form to customize the layout of the POS sales screen.

1.  Click **Retail** \> **Setup** \> **POS** \> **Screen layouts**.

2.  In the **Screen layouts** form, enter the required details for the screen layout. For more information, see [Screen layouts (form)](https://technet.microsoft.com/library/hh597310\(v=ax.60\)).

3.  In the **Button grids** fields, add lines for the following item columns:
    
      - **Item description** or **Item name** – The name and description of the item.
    
      - **Quantity** – The quantity of the item.
    
      - **Unit of measure** – The unit to use to measure the quantity of the item.
    
      - **Item unit price** – The price per unit of the item.
    
      - **Item total price** – The total price of the item.
    
      - **Sale total amount** – The total sale amount.

## Set up POS to generate the Nota Fiscal Paulista file

The Nota Fiscal Paulista file is an electronic fiscal file that contains details about daily sales transactions and must be submitted to the Brazilian tax authorities. It is automatically generated every day after you print the Z report, and is saved in the folder c:\\ProgramFiles\\Microsoft Dynamics AX\\60\\Retail POS\\Arquivos PAF-ECF. This action is performed by a built-in fiscal printer function, which creates one file for each day during which there is movement of items.

To set up the POS to generate the Nota Fiscal Paulista file, follow these steps:

1.  Create a blank operation.

2.  Set the **Operation number** field to **2**.

3.  Leave the **Blank operation param** field blank.

## Attach a fiscal receipt reference to a fiscal document

The fiscal receipt can be replaced by a fiscal document or an electronic fiscal document that is issued as a customer invoice in the **Sales order** form. If the sales order does not use the prices and discounts feature of Microsoft Dynamics AX, you must verify the price and the taxes of the sales order lines to ensure that they match the order lines of the fiscal receipt. The discrepancies must be adjusted manually in the **Fiscal reference** form.

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.
    
    –or–
    
    Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Double-click the sales order for the fiscal document to open the **Sales order** form.

3.  On the **Action Pane**, on the **Invoice** tab, click **Invoice** to open the **Posting invoice** form.

4.  In the lower pane, on the **Setup** tab, click **Fiscal reference** to open the **Fiscal reference** form, where you can attach a fiscal receipt reference to the customer invoice. For more information, see “Attach a fiscal reference to a customer invoice” in [(BRA) Attach a fiscal reference to a fiscal document](bra-attach-a-fiscal-reference-to-a-fiscal-document.md).

5.  In the **Fiscal printer serial number** field, enter the fiscal printer’s serial number.

6.  In the **Fiscal printer number** field, enter the terminal number that is assigned to the printer.

  


