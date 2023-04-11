---
title: Set up a sales tax authority as a vendor
TOCTitle: Set up a sales tax authority as a vendor
ms:assetid: f061cfdc-8a10-4e72-b1f4-cba75f1b8a39
ms:mtpsurl: https://technet.microsoft.com/library/Aa551581(v=AX.60)
ms:contentKeyID: 36059923
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up a sales tax authority as a vendor 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To generate payments to a tax authority when tax payments are due as part of the company's ordinary payment routines, set up a vendor account for the tax authority, run the **Sales tax payments** periodic job, and then perform the payment routine.

1.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.

2.  Click **Vendor** to create a vendor with the name of the sales tax authority.

3.  Enter all the details that are necessary to pay the vendor.
    

    > [!NOTE]
    > <P>If you have entered a value in the <STRONG>Terms of payment</STRONG> field on the <STRONG>Sales tax settlement periods</STRONG> form, you do not have to enter a value in the <STRONG>Terms of payment</STRONG> field on this form. The terms of payment in the <STRONG>Sales tax settlement periods</STRONG> form take precedence over the terms of payment that are entered on the vendor account or on the vendor group that is assigned to the vendor account.</P>



4.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax authorities**. Select the tax authority for which a vendor account is created.

5.  On the **General** tab, select the vendor account for the tax authority in the **Vendor account** field.

6.  At the end of the sales tax settlement period for the sales tax authority, run the **Sales tax payments** periodic job. During this job, the amount that the company owes the sales tax authority for the period is transferred to the sales tax authority's vendor account. When an employee performs the company's usual payment routine, the payment to the sales tax authority is created along with payments to other vendors.

## See also

[Key tasks: Vendor payments and settlements](key-tasks-vendor-payments-and-settlements.md)

  


