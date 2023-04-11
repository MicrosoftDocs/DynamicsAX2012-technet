---
title: Create a vendor account
TOCTitle: Create a vendor account
ms:assetid: 6ceffee5-1344-4a3e-9d6e-5b31f9cd11f8
ms:mtpsurl: https://technet.microsoft.com/library/Aa571206(v=AX.60)
ms:contentKeyID: 36058014
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- vendor
- vendors
- vendor account
- create a vendor
- vendor banking information
- vendor hold
- vendor form
- vendor accounts
audience: Application User
ms.search.region: Global
---

# Create a vendor account 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to create accounts for the vendors that you do business with. The role that you are assigned to must have permission to create and modify vendor accounts.

When you create a vendor account, you enter information about the vendor that is used to populate documents automatically and to track activity with the vendor. For example, you can enter the following information for a vendor:

  - Assign a vendor group. Every vendor must be assigned to a vendor group. Vendors in a vendor group have parameters in common. For example, they may have the same terms of payment.

  - Place a vendor on a hold status. By default, no transaction types are on hold for the vendor. For more information, see [Settle open transactions - vendor (form)](https://technet.microsoft.com/library/aa619609\(v=ax.60\)).

  - Allow an existing vendor to do business with another legal entity in your organization.

  - Set up banking information for the vendor, so that you can send payments electronically.

  - Create an opening balance for the vendor.

  - Configure the vendor for catalog import. The vendor can create and update a catalog of the items and services that your workers can order from the vendor.

  - Assign the vendor to procurement categories.

  - Set up tax, delivery, invoice, and payment information for the vendor. By default, these settings are copied to new documents that you create for the vendor.

  - Set up default financial dimensions that are used to automatically post transactions with the vendor to financial accounts.

To speed up the process of creating vendor accounts, you can create templates that are based on the field entries for vendors that you specify as template models. If a template is available when you begin to create a vendor, a list of the available vendor templates is displayed. Select the template that contains the information that applies to the new vendor. The field values of the template are copied to the fields of the new vendor. Make changes to the fields and enter additional information, as appropriate.

## Create a new vendor

1.  Click **Procurement and sourcing** \> **Common** \> **Vendors** \> **All vendors**.
    
    \-or-
    
    Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.

2.  On the **All vendors** list page, on the **Action Pane**, click the **Vendor** tab. Then, in the **New** group, click **Vendor**.

3.  In the **Vendors** form, on the **General** FastTab, in the **Vendor account** field, enter a unique identifier for the vendor. Depending on how the system is configured, the vendor identifier may be generated automatically.

4.  In the **Name** field, enter the name that appears in documents that are created for the vendor.

5.  In the **Group** field, select the vendor group that applies to the vendor.

6.  Enter values on the other FastTabs in the **Vendors** form as appropriate. For more information, see [Vendors (form)](https://technet.microsoft.com/library/aa592162\(v=ax.60\)).

## See also

[Create a party record](create-a-party-record.md)

[Create a vendor group](create-a-vendor-group.md)

[Vendor groups (form)](https://technet.microsoft.com/library/aa550420\(v=ax.60\))

[Vendor bank accounts (form)](https://technet.microsoft.com/library/aa589805\(v=ax.60\))

[Settle open transactions - vendor (form)](https://technet.microsoft.com/library/aa619609\(v=ax.60\))

[Key tasks: Work with vendor search and search results](key-tasks-work-with-vendor-search-and-search-results.md)

[Key tasks: Manually set up user access to the Vendor portal](key-tasks-manually-set-up-user-access-to-the-vendor-portal.md)

[Import a catalog from a vendor](import-a-catalog-from-a-vendor.md)

[Add vendor to legal entities (form)](https://technet.microsoft.com/library/hh209684\(v=ax.60\))

  


