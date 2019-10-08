---
title: Set other tax options for stores
TOCTitle: Set other tax options for stores
ms:assetid: cdeaab6e-2176-4965-9611-bc39d9d4807c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh597245(v=AX.60)
ms:contentKeyID: 39519323
ms.date: 10/07/2019
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set other tax options for stores 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

When you set up sales taxes for retail stores, you can specify several settings. For example, you can assign sales tax groups to stores, specify inclusive taxes or exclusive taxes, and set up overrides.

1.  Click **Retail** \> **Common** \> **Retail channels** \> **Retail stores**.

2.  Open the store to set up tax options for. Alternatively, on the **Store** tab, on the **Action Pane**, click **Retail store** to create a new store.

3.  In the **Stores** form, on the **General** FastTab, under **Sales tax**, specify values for any of the following fields that apply to the store:
    
      - **Tax identification number (TIN)** – Type the store's TIN.
        

        > [!NOTE]
        > <P>To print the TIN on receipts, enable the <STRONG>Tax Identification Number</STRONG> element in the <STRONG>Header</STRONG> of the receipt in the <STRONG>Receipt format designer</STRONG> form.</P>

    
      - **Sales tax group** – For more information, see [Assign sales tax groups to stores](assign-sales-tax-groups-to-stores.md).
    
      - **Prices include sales tax** – For more information, see [Specify inclusive or exclusive tax](specify-inclusive-or-exclusive-tax.md).
    
      - (IND) **STC number** – Type the service tax code for the store. If this field is left blank, the service tax code for the company is used in tax calculations.
        

        > [!NOTE]
        > <P>This field is intended for use in India. To print the service tax code on receipts, modify the form's layout by adding a <STRONG>Text</STRONG> field that contains the service tax code.</P>

    
      - **Use destination-based tax** – Select this check box to use the customer's shipping address in tax calculations, instead of the store's sales tax group.
    
      - **Use customer-based taxes** – Select this check box to use the customer's sales tax group in tax calculations, instead of the store's sales tax group.

      - **Calculate customer tax exempt** - Select this check box in tax-exclusive scenarios when taxes are store-based or destination-based, but some customers may still need to be exempt from certain taxes. This will check the effective taxes for the transaction against the customer's taxes. If one of the effective taxes for the transaction is marked as "exempt" for the customer, it will not be calculated. This feature is currently only supported for tax-exclusive scenarios, but support for tax-inclusive scenarios will be added in a future release. 


      > [!NOTE]
      > <P>This functionality is new for Microsoft Dynamics 365 Finance and Operations apps version 10.0.7.</P>

## See also

[About setting up taxes](about-setting-up-taxes.md)

  


