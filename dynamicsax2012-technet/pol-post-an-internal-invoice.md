---
title: (POL) Post an internal invoice
TOCTitle: (POL) Post an internal invoice
ms:assetid: bacc41f3-9019-446b-af6a-0c80873cd021
ms:mtpsurl: https://technet.microsoft.com/library/JJ711259(v=AX.60)
ms:contentKeyID: 49387077
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Poland
---

# (POL) Post an internal invoice 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

An internal invoice documents how taxes are calculated for purchases that are made within the European Union (EU). The internal invoice is a tax calculation document that is separate from the vendor invoice. You can create one EU internal invoice for multiple transactions or you can create an EU invoice for each transaction.

Before you can post an internal invoice for a transaction that occurred within the EU, you must create a vendor record and an item sales tax group. You can then create a purchase order and post the invoice.

### Create a vendor

1.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**. On the **Action Pane**, on the **Vendor** tab, in the **New** group, click **Vendor**.
    
    For more information about the fields in this form, see [Vendors (form)](https://technet.microsoft.com/library/aa592162\(v=ax.60\))

2.  On the **Invoice and delivery** FastTab, in the **Sales tax group** field, select the sales tax group.

3.  Select the **VAT date is required** check box to specify that the value-added tax (VAT) date is required on all transactions that include sales tax for this vendor.

4.  Enter any remaining information about the vendor.

### Create an item sales tax group

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Item sales tax groups**.

2.  Click **New** and enter the name and a description of the item sales tax group.
    

    > [!NOTE]
    > <P>For more information about the fields in this form, see <A href="https://technet.microsoft.com/library/aa615960(v=ax.60)">Item sales tax groups (form)</A>.</P>



3.  On the **Setup** FastTab, click **Add**, and in then the **Sales tax code** field, select a sales tax code to assign to the sales tax group.
    
    You can add one or more sales tax codes to the item sales tax group.

### Create a purchase order and generate an invoice

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**. On the **Action Pane**, on the **Purchase order** tab, in the **New** group, click **Purchase order**.

2.  Enter the required details.
    
    For more information about the fields in this form, see [Purchase order (form)](https://technet.microsoft.com/library/aa557983\(v=ax.60\))

3.  On the **Action Pane**, on the **Invoice** tab, in the **Generate** group, click **Invoice**.

4.  In the **Vendor invoice** form, in the **Number** field, enter the invoice number, and then, on the **Action Pane**, click **Post** \> **Post**.

### Create and print an internal EU invoice

1.  Click **Organization administration** \> **Periodic** \> **Foreign trade** \> **EU internal invoice**. Select the records for which to create an internal invoice, and then click **Create**.

2.  In the **Internal EU Invoice** form, in the **Invoice date** field, select the internal invoice date, and then close the form.

3.  Click **Organization administration** \> **Inquiries** \> **Foreign trade** \> **EU internal invoices**.

4.  Click **Print** to print the internal invoice.

  


