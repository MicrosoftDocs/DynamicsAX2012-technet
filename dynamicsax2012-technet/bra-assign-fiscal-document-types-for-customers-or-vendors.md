---
title: (BRA) Assign fiscal document types for customers or vendors
TOCTitle: (BRA) Assign fiscal document types for customers or vendors
ms:assetid: 5b4712d9-e4cc-434f-9ced-397cd8620194
ms:mtpsurl: https://technet.microsoft.com/library/JJ710511(v=AX.60)
ms:contentKeyID: 49384402
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Brazil
---

# (BRA) Assign fiscal document types for customers or vendors 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can assign a default type of fiscal document for customer or vendor fiscal documents. The fiscal document type defines the number sequence, series, and layout of the fiscal documents. You can assign a fiscal document type for a combination of customers or vendors, item types, or fiscal establishments.

1.  Click **Accounts payable** \> **Setup** \> **Assign fiscal document types**.
    
    –or–
    
    Click **Accounts receivable** \> **Setup** \> **Assign fiscal document types**.
    
    –or–
    
    Click **Project management and accounting** \> **Setup** \> **Assign fiscal document types**.

2.  Create a record.

3.  In the **Account code** field, select one of the following options to indicate the account code that the fiscal document type is assigned to:
    
      - **Table** – Assign the fiscal document type to a customer account or a vendor account.
    
      - **Group** – Assign the fiscal document type to a customer group or a vendor group.
    
      - **All** – Assign the fiscal document type to all customers or all vendors.

4.  In the **Account relation** field, select the customer account, customer group, vendor account, or vendor group to assign the fiscal document type to. This field depends on the selection in the **Account code** field.
    

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>Table</STRONG> or <STRONG>Group</STRONG> in the <STRONG>Account code</STRONG> field.</P>



5.  In the **Item type** field, select **Item** or **Service** as the type of item to assign the fiscal document type to.
    

    > [!NOTE]
    > <P>This field is available only from Accounts receivable and Project management and accounting.</P>



6.  In the **Fiscal establishment ID** field, select the fiscal establishment that the fiscal document type is assigned to.

7.  In the **Fiscal document type** field, select the default fiscal document type for the combination of customers or vendors, item type, or fiscal establishment that you selected in the **Account code**, **Account relation**, **Item type**, and **Fiscal establishment ID** fields.

## See also

[(BRA) About updates to fiscal document types](bra-about-updates-to-fiscal-document-types.md)

[(BRA) Assign fiscal document types (form)](https://technet.microsoft.com/library/jj710506\(v=ax.60\))

[(BRA) Fiscal document types (form)](https://technet.microsoft.com/library/jj710551\(v=ax.60\))

  


