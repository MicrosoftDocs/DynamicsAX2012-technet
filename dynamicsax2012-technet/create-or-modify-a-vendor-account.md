---
title: Create or modify a vendor account
TOCTitle: Create or edit a vendor account
ms:assetid: 554b8343-2d1c-4fb4-aae4-9a6e96588839
ms:mtpsurl: https://technet.microsoft.com/library/Hh271536(v=AX.60)
ms:contentKeyID: 36384168
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- EPVendTableCreate
- EPVendTableEdit
audience: Application User
ms.search.region: Global
---

# Create or modify a vendor account 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

As a purchasing agent for your organization, you can create new vendors in Enterprise Portal for Microsoft Dynamics AX and maintain vendor account information. For example, you can do the following:

  - Update account information, such as address information, for vendors that do business with your organization.

  - Modify the contacts that are associated with a vendor account.

  - Delete a vendor from the vendor master list.


> [!IMPORTANT]
> <P>Your user role in Microsoft Dynamics AX must have permission to create and modify vendor accounts.</P>



## Create a vendor account

1.  Click **Procurement** on the top link bar, and then click **Vendors** on the Quick Launch.

2.  On the **Action Pane**, in the **New** group, click **Vendor**.

3.  On the **New vendor** page, on the **General** FastTab, do the following:
    
    1.  In the **Group** field, select a vendor group. Vendors in a vendor group have common characteristics, such as payment terms, settle period, and sales tax group.
    
    2.  In the **Record type** field, select whether the vendor is a person or an organization.
    
    3.  In the **Name** field, enter a unique name for the vendor. This name is printed on documents that you send to the vendor, such as invoices and statements.
    
    4.  In the **Search name** field, enter a short name for the vendor. This name is used when you search for vendor data. If you do not enter a search name, the value in the **Name** field is used when you search for vendor data.
    
    5.  In the **Address books** field, select the legal entities that this vendor is approved to do business with.
    
    6.  In the **Language** field, select the language that is used for external documents that are sent to the vendor, such as purchase orders.

4.  On the **Address** FastTab, click **Add**, and then enter address information for the vendor.

5.  On the **Contact information** FastTab, click **Add**, and then enter information about contacts at the vendor organization.

6.  On the **Details** FastTab, do the following:
    
    1.  In the **Currency** field, select the currency that is used for vendor invoices.
    
    2.  In the **Vendor hold** field, select the transaction types, if any, that have been placed on hold for the vendor account:
        
          - **No** – No holds have placed on the vendor.
        
          - **Invoice** – No invoices can be created or posted for the vendor.
        
          - **All** – The vendor is on hold for all transaction types.
        
          - **Payment** – No payments can be generated for this vendor.
        
          - **Requisition** – No purchase requisitions can be created for this vendor.
        
          - **Never** – The vendor cannot automatically be put on hold for inactivity.
    
    3.  In the **Buyer group** field, select a buyer group for the vendor. The buyer group defines the group of purchasing agents in your organization who can interact with the vendor.

7.  On the remaining FastTabs, enter information about the new vendor, as applicable.

8.  Click **Save and close** to add the new vendor to the vendor master list for the address books that you selected on the **General** FastTab.

## Modify the vendor information

1.  Click **Procurement** on the top link bar, and then click **Vendors** on the Quick Launch.

2.  On the **Vendors** page, click the vendor account ID for the vendor record that you want to modify.

3.  On the **View vendor** page, on the **Action Pane**, click **Edit**. After you finish modifying the information, click **Save and close**.

## Delete a vendor

1.  Click **Procurement** on the top link bar, and then click **Vendors** on the Quick Launch.

2.  On the **Vendors** page, select the vendor that you want to delete.

3.  On the **Action Pane**, on the **Vendor** tab, click **Delete**.

## See also

[View vendor accounts](view-vendor-accounts.md)

  


