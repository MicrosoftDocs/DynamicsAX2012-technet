---
title: (FRA) Set up NAF codes and siret numbers
TOCTitle: (FRA) Set up NAF codes and siret numbers
ms:assetid: 55e1d802-7493-4024-99a4-33a5549f982a
ms:mtpsurl: https://technet.microsoft.com/library/Hh208962(v=AX.60)
ms:contentKeyID: 36057318
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- France
- NAF
audience: Application User
ms.search.region: France
---

# (FRA) Set up NAF codes and siret numbers 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can create Nomenclature des Activités Françaises (NAF) codes, and then set up NAF codes for legal entities, customers, vendors, and prospects in Microsoft Dynamics AX 2012. You can set up siret numbers for customers, vendors, and prospects.

## Create an NAF code

Use the **NAF codes** form to create an NAF code that you can assign to a legal entity, a customer, a vendor, or a prospect.

1.  Click **Organization administration** \> **Setup** \> **Addresses** \> **NAF codes**.

2.  Click **New** or press CTRL+N to create a record.

3.  In the **NAF code** field, enter an NAF code, which consists of four digits and one letter.

4.  In the **Description** field, enter a description of the items that are represented by the NAF code.

## Set up commerce registration, a legal form, and an NAF code for a legal entity

Use the **Legal entities** form to set up the commerce registration, a legal form, and an NAF code for a legal entity.

To perform this task, follow these steps:

1.  Click **Organization administration** \> **Setup** \> **Organization** \> **Legal entities**.

2.  Select or create a legal entity. For more information, see [Create or modify a legal entity](create-or-modify-a-legal-entity.md).

3.  In the **Commerce registration** field, enter the name of the French agency where the legal entity is registered, such as the Registre du commerce et des sociétés.

4.  In the **Legal form** field, enter the legal type of the legal entity, such as non-profit organization, manufacturing company, or financial institution.

5.  In the **NAF code** field, select the NAF code for the legal entity.

## Set up an NAF code and a siret number for a customer

Use the **Customers** form to set up an NAF code and a siret number for a customer.

To perform this task, follow these steps:

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  Select or create a customer record, and then click **Edit**. For more information, see [Create a customer record](create-a-customer-record.md).

3.  On the **Sales demographics** FastTab, in the **French Siret** field, enter the siret number for the customer.

4.  In the **NAF code** field, select the NAF code for the customer.

## Set up an NAF code and a siret number for a vendor

Use the **Vendors** form to set up an NAF code and a siret number for a vendor.

To perform this task, follow these steps:

1.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.

2.  Select or create a vendor record, and then click **Edit**. For more information, see [Create a vendor account](create-a-vendor-account.md).

3.  On the **Purchasing demographics** FastTab, in the **French Siret** field, enter the siret number for the vendor.

4.  In the **NAF code** field, select the NAF code for the vendor.

## Set up an NAF code and a siret number for a prospect

Use the **Prospects** form to set up an NAF code and a siret number for a prospect.

To perform this task, follow these steps:

1.  Click **Sales and marketing** \> **Common** \> **Prospects** \> **All prospects**.

2.  Select or create a prospect record, and then click **Edit**. For more information, see [Create or update a prospect record](create-or-update-a-prospect-record.md).

3.  On the **Sales demographics** FastTab, in the **French Siret** field, enter the siret number for the prospect.

4.  In the **NAF code** field, select the NAF code for the prospect.

## See also

[(FRA) NAF codes (form)](https://technet.microsoft.com/library/hh227617\(v=ax.60\))

[(FRA) NAF codes and siret numbers](fra-naf-codes-and-siret-numbers.md)

  


