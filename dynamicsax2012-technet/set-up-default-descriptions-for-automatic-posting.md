---
title: Set up default descriptions for automatic posting
TOCTitle: Set up default descriptions for automatic posting
ms:assetid: d195456d-df67-44d3-94a0-b897bc3da664
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677363(v=AX.60)
ms:contentKeyID: 49384138
ms.date: 10/15/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up default descriptions for automatic posting 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic explains how to set up default text that is used to describe accounting entries that are posted automatically to the general ledger. You can set up default description text by using freeform text or by selecting fixed variables.


> [!NOTE]
> <P>For certain transaction types in some countries/regions, you can also include text from fields in the Microsoft Dynamics AX database that are related to those transaction types. These transaction types and countries/regions are listed in Optional: Add other text to default descriptions, later in this topic.</P>



## Set up default descriptions

1.  Click **Organization administration** \> **Setup** \> **Default descriptions**.

2.  On the menu bar, click **New**.

3.  In the **Description** field, select the type of transaction to create a default description for.

4.  In the **Language** field, select the language that this description applies to.

5.  In the **Text** field, enter the default description. You can type text in the field, or you can use one or more of the following free text variables:
    
      - %1 – Add the transaction date.
    
      - %2 – Add an identifier that corresponds to the document type that is being posted to the general ledger. For example, for transaction types that are related to invoices, the %2 variable adds the invoice number.
    
      - %3 – Add an identifier that is related to the document type that is being posted to the general ledger. For example, for transaction types that are related to invoices, the %3 variable adds the customer account number.

## Optional: Add other text to default descriptions

For certain transactions types in some countries/regions, you can include text in your default descriptions that come from fields in the Microsoft Dynamics AX database that are related to those transaction types. The following lists show the transaction types and countries/regions for which this option is available.

**Transaction types**

You can add other text to default descriptions for transaction types that are related to the following document types:

  - Customer invoices

  - Customer credit notes

  - Customer cash payments

  - Vendor payments

  - Sales orders

  - Purchase orders

  - Inventory journals

  - Master planning (MRP)

  - Fixed assets

**Countries/regions**

This option is available for the following countries/regions:

  - Brazil

  - China

  - Czech Republic

  - Eastern Europe

  - Hungary

  - India

  - Japan

  - Lithuania

  - Latvia

  - Poland

  - Russia

**Add text to default descriptions**

After you complete the steps in Set up default descriptions, earlier in this topic, follow these steps to add other text to the default descriptions:

1.  In the **Parameters** area, click **Add**.

2.  In the **Reference table** field, select the database table from which to add parameter data to the description.

3.  In the **Reference field** field, select the field from which to add parameter data to the description.

4.  Repeat steps 1 through 3 to add more parameters.

## See also

[Default descriptions (form)](https://technet.microsoft.com/en-us/library/aa615730\(v=ax.60\))

  


