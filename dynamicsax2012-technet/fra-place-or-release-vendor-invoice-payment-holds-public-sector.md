---
title: (FRA) Place or release vendor invoice payment holds (Public sector)
TOCTitle: (FRA) Place or release vendor invoice payment holds (Public sector)
ms:assetid: ea5554b6-7a66-4d12-8a36-27393edf6929
ms:mtpsurl: https://technet.microsoft.com/library/Hh208599(v=AX.60)
ms:contentKeyID: 36056386
author: Khairunj
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- public sector
- France
- French
- payment hold
- vendor invoice payment hold
- payment holds
- vendor invoice payment holds
audience: Application User
ms.search.region: France
---

# (FRA) Place or release vendor invoice payment holds (Public sector) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Sometimes the due date for payment on a vendor invoice must be extended. Typical reasons can include disputes about the amount owed, disputes about the details of an order, or missing or incorrect information in a vendor record. When this occurs, you can place a temporary payment hold to extend the payment due date until the issue is resolved.

Payment holds can be placed for all invoices associated with a vendor or for specific invoices for a vendor.


> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed in the following hotfix for Microsoft Dynamics AX 2012 R3 Cumulative Update 8: KB3047235</P>



The standard processes related to vendor invoice payment holds are augmented for French entities in the public sector. These additional capabilities, which are described in this topic, are available only if the following conditions are met:

  - The **Public Sector** configuration key is selected.

  - The **French regulatory** configuration subkey is selected.

  - In Microsoft Dynamics AX 2012 R3 Cumulative Update 8, the **Commitments (France)** regulatory document type is selected in the **Budget parameters** form, when the following hotfix is installed: KB3047235

  - In cumulative update 7 for Microsoft Dynamics AX 2012, the **Use French public sector accounting rules** check box is selected in the **Budget parameters** form.

In versions of Microsoft Dynamics AX 2012 prior to cumulative update 7, only the **Public Sector** configuration key must be selected, but the primary address of the legal entity must be in France.

## Set up rules for vendor invoice payment holds

To place or release a hold, you must be assigned to a user role where rules have been set up for payment holds.

Select a user role, such as accountant, accounting manager, or controller. Enter the minimum number of days that users in that role can place a payment on hold for each invoice and the maximum number of times that those users can place a payment on hold for each invoice.

For example, you create a rule that allows accountants to place an invoice payment hold for a minimum of 7 days. To allow an unlimited number of holds, you enter a large number, such as 9999. You create another rule that allows a director to place an invoice payment hold for a minimum of 15 days, with a limit of 1 time that they can place a hold on each invoice.


> [!NOTE]
> <P>User roles are set up in the <STRONG>Security roles</STRONG> form, and specific users can be assigned to roles in the <STRONG>Assign users to roles</STRONG> form. For more information, see <A href="https://technet.microsoft.com/library/hh227655(v=ax.60)">Security roles (form)</A> and <A href="https://technet.microsoft.com/library/hh209671(v=ax.60)">Assign users to roles (form)</A>.</P>



1.  Click **Accounts payable** \> **Setup** \> **Payment** \> **Terms of payment**.

2.  Open the **Hold** FastTab.

3.  Click **New**.

4.  Select a **User role**, such as accountant, accounting manager, or controller, who can hold a payment under the specified terms of payment.

5.  Enter the minimum number of days that will be added to the invoice payment due date when a user who is assigned to this role releases a hold.

6.  Enter the maximum number of times that a payment on each invoice can be placed on hold by users who are assigned to this role. Do not leave this field blank. To allow unlimited holds, enter a large number, such as 9999.

## Place or release vendor invoice payment holds

Place a payment on hold from the **Vendor transactions**, **Vendor invoice**, or **Invoice journal** forms. On each form, select the **Invoice payment hold** check box to place a payment on hold. Clear the check box to release a hold.

Holds can be placed and released in the following circumstances:

  - Payment terms must be set up for a vendor invoice, or for all vendor invoices for a specific vendor, before you can place a hold. For more information, see [(FRA) Set up vendor terms of payment (Public sector)](fra-set-up-vendor-terms-of-payment-public-sector.md).

  - To place or release a hold, you must be assigned to a user role where rules have been set up for payment holds.

  - If a hold is active for a vendor, you cannot release a hold for an invoice for that same vendor. You must first release the hold for the vendor.

  - You cannot release a hold unless you are the user who placed the hold, or you are assigned to the same user role as the user who placed the hold.

  - You cannot post a vendor invoice if it has a payment hold. The hold must first be released.

## Place or release a payment hold for all invoices for a selected vendor

Place or release a payment hold on the **Vendor transactions** form. If you place a payment hold for a vendor, this hold includes all existing invoices for that vendor. If you release a payment hold for a vendor, this releases the payment hold only for those vendor invoices that do not have individual payment holds.

For example, you place individual payment holds on two different vendor invoices for the same vendor. You later place a payment hold for that vendor. If you later release the payment hold for that vendor, it will not release the individual holds for the two vendor invoices.

For more information about this form, see [Vendor transactions (form)](https://technet.microsoft.com/library/aa572427\(v=ax.60\)).

1.  Open the form from either **Accounts payable** or **Procurement and sourcing**:
    
      - Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.
    
      - Click **Procurement and sourcing** \> **Common** \> **Vendors** \> **All vendors**.

2.  Select a vendor.

3.  On the **Action Pane**, on the **Vendor** tab, click **Transactions**.

4.  On the **Payment** tab, select the **Invoice payment hold** check box to place all invoice payments on hold. Clear the check box to release invoice payment holds for all invoices for this vendor that do not have individual payment holds.

## Place or release a payment hold for a vendor invoice

Place or release a payment hold on the **Vendor invoice** form. For more information about this form, see [Vendor invoice (form)](https://technet.microsoft.com/library/hh209644\(v=ax.60\)).

1.  Click **Accounts payable** \> **Common** \> **Vendor invoices** \> **Pending vendor invoices**.

2.  Select a vendor invoice.

3.  On the **Action Pane**, on the **Vendor invoice** tab, in the **Maintain** group, click **Edit**.

4.  On the **Action Pane**, click **Header view**.

5.  On the **Payment** FastTab, select the **Invoice payment hold** check box to place a payment on hold, or clear the check box to release a hold.

## Place or release a payment hold for a posted vendor invoice

Place or release a payment hold for a posted vendor invoice on the **Invoice journal** form. For more information about this form, see [Vendor invoice journal (form)](https://technet.microsoft.com/library/aa587621\(v=ax.60\)).

1.  Click **Accounts payable** \> **Inquiries** \> **Journals** \> **Invoice journal**.

2.  On the **Overview** tab, select the **Invoice payment hold** check box to place a payment on hold, or clear the check box to release a hold.

## Place or release vendor invoice payment holds before settlement

When you place a payment hold on a vendor invoice, the **Invoice payment hold** check box is automatically selected on the **Settle open transactions** form. This prevents a vendor invoice from being settled until the hold is released. If the check box is selected, and you are assigned to the same user role as the user who placed the hold, you can clear the check box and then settle the vendor invoice.

If a payment hold has not been placed on a vendor invoice, you can select the **Invoice payment hold** check box on the **Settle open transactions** form. This will prevent settlement as long as the payment hold is in effect.

You can place or release payment holds on individual vendor invoices, on all vendor invoices associated with a purchase order, or for all invoices for a selected vendor.

For more information about the **Settle open transactions** form, see [Settle open transactions - vendor (form)](https://technet.microsoft.com/library/aa619609\(v=ax.60\)).

## Place or release a payment hold for all invoices for a vendor before settlement

This action places or releases a payment hold for all invoices for a selected vendor.

1.  Open the form from either **Accounts payable** or **Procurement and sourcing**:
    
      - Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.
    
      - Click **Procurement and sourcing** \> **Common** \> **Vendors** \> **All vendors**.

2.  Select a vendor.

3.  On the **Action Pane**, on the **Invoice** tab, in the **Settle** group, click **Settle open transactions**.

4.  On the **Payment** tab, select the **Invoice payment hold** check box to place a payment on hold, or clear the check box to release a hold.

## Place or release a payment hold for a specific vendor invoice before settlement

This action places or releases a payment hold for a selected vendor invoice.

1.  Click **Accounts payable** \> **Common** \> **Vendor invoices** \> **Open vendor invoices**.

2.  Select a vendor invoice.

3.  On the **Action Pane**, on the **Invoice** tab, in the **Settle** group, click **Settle open transactions**.

4.  On the **Payment** tab, select the **Invoice payment hold** check box to place a payment on hold, or clear the check box to release a hold on the vendor invoice.

## Place or release a payment hold for all vendor invoices associated with a purchase order before settlement

This action places or releases a payment hold for all vendor invoices that are associated with a selected vendor.

1.  Open the form from either **Accounts payable** or **Procurement and sourcing**:
    
      - Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.
    
      - Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Select a purchase order.

3.  On the **Action Pane**, on the **Invoice** tab, in the **Settle** group, click **Open transactions**.

4.  On the **Payment** tab, select the **Invoice payment hold** check box to place a payment on hold, or clear the check box to release a hold.

## See also

[(FRA) Set up vendor terms of payment (Public sector)](fra-set-up-vendor-terms-of-payment-public-sector.md)

[(FRA) Process purchase order encumbrances and commitments at year end (Public sector)](fra-process-purchase-order-encumbrances-and-commitments-at-year-end-public-sector.md)

[(FRA) Vendor invoice payment hold history (form) (Public sector)](https://technet.microsoft.com/library/hh208535\(v=ax.60\))

  


