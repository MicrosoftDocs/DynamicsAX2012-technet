---
title: Create a one-time vendor and invoice (Public sector)
TOCTitle: Create a one-time vendor and invoice (Public sector)
ms:assetid: c0b7d933-3c25-4d48-922d-bb83d3b3f62b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn762314(v=AX.60)
ms:contentKeyID: 63384522
ms.date: 11/14/2014
mtps_version: v=AX.60
f1_keywords:
- invoices
- invoice
- vendor invoice
- Forms.SysOperationTemplateForm
- vendor invoices
- Forms.VendOpenInvoicesListPage
- create invoice
- one-time vendor
- Forms.VendOneTimeVendInvoice_PSN
- create vendor
- one-time vendors
---

# Create a one-time vendor and invoice (Public sector) 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

You might have a situation where you have to create an invoice for a new vendor with whom you have no regular relationship. When approval or a contract in the form of a purchase order is not required, you can quickly create an invoice at the same time as creating a record for the vendor. For example, you might have to pay referees or refunds, where a master vendor record does not exist.


> [!NOTE]
> <P>This feature is available only if Microsoft Dynamics AX 2012 R3 Cumulative Update 8 is installed, and if the <STRONG>Public Sector</STRONG> configuration key is selected.</P>



## Create a single one-time vendor and invoice

Use this procedure to quickly create an invoice for a one-time-only vendor and a record for the vendor at the same time.


> [!NOTE]
> <P>If you want to create multiple one-time vendors and invoices, see <A href="import-and-create-one-time-vendors-and-invoices-public-sector.md">Import and create one-time vendors and invoices (Public sector)</A>.</P>



1.  Click **Accounts payable** \> **Common** \> **Vendor invoices** \> **Open vendor invoices**.

2.  On the **Action Pane**, in the **New** group, click **Invoice**, and then click **One-time vendor and invoice**.

3.  In the **Create a one-time vendor and invoice** form, in the **Record type** field, specify whether the vendor is a person or an organization.

4.  Fill out the other fields as necessary, and then click **Create**. The **Vendor invoice** form opens, displaying the vendor information.
    

    > [!NOTE]
    > <P>For fields in the <STRONG>Create a one-time vendor and invoice</STRONG> form that you don’t enter new values into, the vendor record you are creating uses values from the default one-time vendor account. That account is specified on the <STRONG>General</STRONG> tab in the <STRONG>Accounts payable parameters</STRONG>. To view the account details, go to the <STRONG>All vendors</STRONG> list page and double-click the vendor account number of the default one-time vendor.</P>



## See also

[Key tasks: Vendor invoices](key-tasks-vendor-invoices.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

