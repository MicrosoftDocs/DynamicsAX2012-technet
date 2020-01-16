---
title: (CAN) Set up GST/HST and post a purchase order with tax on acquisition details
TOCTitle: (CAN) Set up GST/HST and post a purchase order with tax on acquisition details
ms:assetid: 50e39cac-2c76-4790-8d3b-affa490b7260
ms:mtpsurl: https://technet.microsoft.com/library/Hh208915(v=AX.60)
ms:contentKeyID: 36057244
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Canada
- GST
- HST
audience: Application User
ms.search.region: Canada
---

# (CAN) Set up GST/HST and post a purchase order with tax on acquisition details 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Taxpayers in Canada use form GST 34 to manually file Goods and Services Tax or Harmonized Sales Tax (GST/HST) returns and to remit payments to the Canada Revenue Agency (CRA). However, the CRA allows taxpayers to file and remit taxes calculated on acquired fixed assets electronically. You can file GST/HST returns electronically using any of the following methods:

  - Net file transfer – An Internet-based filing service that allows taxpayers to file their returns directly over the Internet.

  - Electronic Data Interchange (EDI) – A data transfer method that taxpayers can use to file their returns directly with the CRA or through a third-party service provider.

  - GST/HST Internet File Transfer (GIFT) – An uploading tool used to submit text files to the CRA website for filing GST/HST returns and remitting payments.

Before you generate a GIFT file, set up your software identification code, sales tax code, and sales tax group. Use the following procedures to enter legal entity details, sales tax code, and sales tax group for GIFT, and to create sales tax entries for taxes paid on acquisition.

## Set up legal entities for GIFT

1.  Click **Organization administration** \> **Setup** \> **Organization** \> **Legal entities**.

2.  Click the **Statutory reporting** FastTab, and in the **Registration number** field, enter the registration number that the CRA provided to you when you registered for GST/HST.

3.  In the **Software identification code** field, enter "AX030003" as the default value to transfer the returns.

4.  Click **Account identifiers** to open the **Account identifiers** form.

5.  On the **Overview** tab, in the **Program identifier** field, select **GST/HST**.

6.  In the **Reference number** field, enter the reference number provided by the CRA.

7.  Close the forms to save your changes.

## Set up tax codes for GIFT

Use the **Sales tax codes** form to set up tax codes to calculate GST/HST for the GIFT file.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax codes**.

2.  Press CTRL+N to create a new tax code.

3.  In the **Sales tax code** field, enter a code, such as GST/HST, and then enter general information about the sales tax code.

4.  Click the **Calculation** tab and enter the calculation details to calculate the GST/HST amount.

5.  Click **Values** to open the **Values** form. Enter the dates during which the tax code is in effect.

6.  In the **Value** field, enter the percentage for the calculation.

7.  Close the forms to save your changes.

## Set up tax groups for GIFT

Use the **Sales tax groups** form to set up sales tax groups. You can assign the sales tax groups to companies, and the taxes will be calculated based on the tax codes that were in effect when the transactions took place.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax groups**.

2.  Press CTRL+N to create a new sales tax group.

3.  In the **Sales tax group** field, enter a name, such as GST/HST, and then enter general information about the sales tax group.

4.  Click the **Setup** tab, and in the **Sales tax code** field, select a sales tax code to add to the sales tax group.

5.  Close the form to save your changes.

## Create sales tax entries for tax on acquisition

The details of the taxes paid on asset acquisition are recorded in the **Purchase order** form. This procedure helps you to collect the tax information required for the GIFT file from the purchase order.

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**. Click **Purchase order** to create a new purchase order.

2.  Click the **Line details** FastTab, and then click the **Setup** tab, in the **GST/HST** field, select **Tax on acquisition**.

3.  Click the **Fixed assets** tab, and then enter the fixed asset details for the purchase order. For more information, see [About assets acquired through procurement](about-assets-acquired-through-procurement.md) and [About fixed assets integration](about-fixed-assets-integration.md).

4.  Click **Invoice** \> **Invoice** to open the **Vendor invoice** form.

5.  Select the transaction line to be posted.

6.  Click **Process** \> **Post** to post the invoice.

7.  Close the form to save your changes.

## See also

[(CAN) Generate a GIFT file](can-generate-a-gift-file.md)

[Purchase order (form)](https://technet.microsoft.com/library/aa557983\(v=ax.60\))

[(CAN) Account identifiers (form)](https://technet.microsoft.com/library/hh242245\(v=ax.60\))

  


