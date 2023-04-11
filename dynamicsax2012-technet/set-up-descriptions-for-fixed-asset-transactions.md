---
title: Set up descriptions for fixed asset transactions
TOCTitle: Set up descriptions for fixed asset transactions
ms:assetid: 053f9c70-cda6-4d8a-b9c2-58df7f6a95a7
ms:mtpsurl: https://technet.microsoft.com/library/Aa569711(v=AX.60)
ms:contentKeyID: 36055950
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up descriptions for fixed asset transactions 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this information to set up descriptions for fixed asset transactions.

## Default transaction descriptions for fixed assets

You can set up default descriptions for transactions that are created automatically, such as depreciation transactions that are created based on depreciation disposal. (Click **Organization administration** \> **Setup** \> **Default descriptions**.)

Fixed asset transactions can be created from a purchase order, a free text invoice, fixed asset journals, depreciation book journals, general journals, and accounts payable.

The following description options are for transactions that are created in the **Purchase order** form.

  - For updates of the vendor account – The text set up for **Purchase order - invoice, vendor**.

  - For updates of the general ledger – The text set up for **Purchase order - invoice, ledger**.

In the fixed asset journals, the transaction type of the transaction is used as the description. This is usually **Acquisition** or **Acquisition adjustment**.

The following description options are for transactions that are created in the **Free text invoice** form.

  - For updates of the customer account – The text set up for **Customer - invoice, customer**.

  - For updates of the general ledger – The text set up for **Customer - invoice, ledger**.

  - For updates of the fixed asset – The posting description that is entered manually on the free text invoice in the **Description** field is used as the transaction description.

However, most fixed asset transactions are posted through journals. The description is fixed only in the **Inventory to fixed assets** journal according to the setup of the description for the **Inventory - journal - transaction** transaction type. In all other journals, the description can be entered manually.

## Create default descriptions

The following default description options are available for fixed assets.

**Fixed asset - posting, ledger** – Used as the default description for all other fixed asset transactions that are created in a journal using one of the system proposals: value models and depreciation books.

**Fixed asset - reversal of reserve** – Used only for the special functionality of the dissolution of provisions for profit on sold assets, which is set up in the **Fixed assets provision types** form.

Follow these steps to create the default descriptions for fixed asset transactions.

1.  Click **Organization administration** \> **Setup** \> **Default descriptions**.

2.  Click **New**.

3.  In the **Description** field, select **Fixed asset - posting, ledger**.

4.  In the **Language** field, enter the language to display the description in.

5.  Enter text in the **Text** field.

6.  Click **New**.

7.  In the **Description** field, select **Fixed asset - reversal of reserve**.

8.  Repeat steps 4 and 5.

For both description options, text variables can be used that include one or more variables in the text.

The following variables are available for fixed asset transactions:

Variables for **Fixed asset - reversal of reserve**:

  - **Transaction date** %1

  - **Voucher** %3

  - **Fixed asset number for the reserve transaction** %4

  - **Value model for the reserve transaction** %5

Variables for **Fixed asset - posting, ledger**:

  - **Transaction date** %1

  - **Voucher** %3

  - **Fixed asset** %4

  - **Fixed asset group** %5

## Journal descriptions

You also use journal descriptions for fixed asset transactions and depreciation book transactions. You can create journal descriptions to easily enter transaction descriptions in journal lines.

To create journal descriptions, use the **Journal descriptions** form. (Click **General ledger** \> **Setup** \> **Journals** \> **Journal descriptions**.)

  


