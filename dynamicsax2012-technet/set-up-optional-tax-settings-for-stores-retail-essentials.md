---
title: Set up optional tax settings for stores (Retail essentials)
TOCTitle: Set up optional tax settings for stores (Retail essentials)
ms:assetid: 98dec17f-29e9-4d94-8cd9-771398fdb5e2
ms:mtpsurl: https://technet.microsoft.com/library/Dn736919(v=AX.60)
ms:contentKeyID: 62200400
author: Khairunj
ms.date: 12/17/2014
mtps_version: v=AX.60
---

# Set up optional tax settings for stores (Retail essentials) 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to specify optional sales tax settings for stores. After you set up sales taxes for retail stores, you can specify several additional, optional settings. For example, you can assign sales tax groups to stores, specify inclusive taxes or exclusive taxes, and set up sales tax overrides.

1.  Click **Retail essentials** \> **Channels** \> **Retail stores**.

2.  Open the store that you want to set up tax options for. Alternatively, in the **Retail stores** list, on the **Action Pane**, on the **Store** tab, click **Retail store** to create a new store.

3.  In the **Stores** form, on the **General** FastTab, under **Sales tax**, specify values for any of the following fields that apply to the selected store:
    
      - **Tax identification number (TIN)** – Enter the store's TIN.
        

        > [!NOTE]
        > <P>To print the TIN on receipts, enable the <STRONG>Tax Identification Number</STRONG> element in the <STRONG>Header</STRONG> of the receipt in the <STRONG>Receipt format designer</STRONG> form. For more information, see <A href="set-up-receipt-profiles-retail-essentials.md">Set up receipt profiles (Retail essentials)</A>.</P>

    
      - **Sales tax group** – For more information, see [Assign sales tax groups to stores (Retail essentials)](assign-sales-tax-groups-to-stores-retail-essentials.md).
    
      - **Prices include sales tax** – For more information, see [Specify inclusive or exclusive tax (Retail essentials)](specify-inclusive-or-exclusive-tax-retail-essentials.md).
    
      - **Use destination-based tax** – Select this check box to use the tax that is associated with the customer's shipping address in tax calculations, instead of the store's sales tax group.
    
      - **Use customer-based taxes** – Select this check box to use the customer's sales tax group in tax calculations, instead of the store's sales tax group.
    
      - **Sales tax override group** – Select the sales tax override group that can be used during a transaction.


> [!NOTE]
> <P>In Retail essentials, the form that you use to complete this task includes a subset of the controls that are available for other configurations of Retail. If a topic about this form describes controls that you don't see, it may be because you’re using Retail essentials.</P>



## See also

[Setting up taxes (Retail essentials)](setting-up-taxes-retail-essentials.md)

  


