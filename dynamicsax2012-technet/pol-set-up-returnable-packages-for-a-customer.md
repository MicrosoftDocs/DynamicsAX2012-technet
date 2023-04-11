---
title: (POL) Set up returnable packages for a customer
TOCTitle: (POL) Set up returnable packages for a customer
ms:assetid: 314228b6-e0fa-4535-a38d-033e6af06113
ms:mtpsurl: https://technet.microsoft.com/library/JJ911040(v=AX.60)
ms:contentKeyID: 52075331
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Poland
- returnable packages
audience: Application User
ms.search.region: Poland
---

# (POL) Set up returnable packages for a customer 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Return packages table** form to register packages that are returned by a customer, define packaging codes, and specify the deposit amount that is paid by the customer for each of the returned packages.

You can define the packing units and packing groups for an item in the **Packing units** form. You can set up number sequences for packing vouchers in the **Accounts receivable parameters** form.

## Set up a packaging code and specify the deposit amount

1.  Click **Inventory management** \> **Setup** \> **Packing material** \> **Return packages**.

2.  In the **Packaging code** field, enter a unique code for the returned package.

3.  In the **Package description** field, enter a description for the returned package.

4.  In the **Deposit** field, enter the deposit amount that is paid by the customer for the returned package.

## Create a packing unit for an item and attach an item to a packaging code

1.  Click **Inventory management** \> **Setup** \> **Packing material** \> **Packing units**.

2.  Press CTRL+N to create a new line, and enter the required details to define the packing units for the items. For more information, see [Packing units (form)](https://technet.microsoft.com/library/aa616127\(v=ax.60\)) and [Define packing units and materials](define-packing-units-and-materials.md).

3.  In the **Item code** field, select the item code to define a packing unit. The possible values are **Table**, **Group**, and **All**. If you select **All**, the packing unit applies to all of the items.

4.  In the **Item relation** field, select the relationship to which the packing unit is being added. If you select **Table** in the **Item code** field, you can select an item, and if you select **Group**, you can select a packaging group to define the packing unit in the **Item relation** field.

5.  On the **General** tab, in the **Packing unit** field, select a unit of measure for packing an item.

6.  In the **Packaging code** field, select the code for the package that is returned by the customer.

## Set up a number sequence for packing vouchers

1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  Click **Number sequences**.

3.  Select a journal number sequence for the **Package voucher** reference type.
    

    > [!NOTE]
    > <P>When a sales invoice is posted, a special voucher is used to post the client fee for the package. All deposit transactions are posted to a separate account, which is defined in the <STRONG>Deposits</STRONG> field in the <STRONG>Customer posting profiles</STRONG> form.</P>



## See also

[(POL) Register a package and verify package quantity for a sales order](pol-register-a-package-and-verify-package-quantity-for-a-sales-order.md)

[(POL) Post and print a returned package report](pol-post-and-print-a-returned-package-report.md)

[(POL) Return packages table (form)](https://technet.microsoft.com/library/jj923258\(v=ax.60\))

[(POL) Packing units (modified form)](https://technet.microsoft.com/library/jj681858\(v=ax.60\))

  


