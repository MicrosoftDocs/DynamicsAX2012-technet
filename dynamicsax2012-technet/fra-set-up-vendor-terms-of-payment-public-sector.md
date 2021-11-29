---
title: (FRA) Set up vendor terms of payment (Public sector)
TOCTitle: (FRA) Set up vendor terms of payment (Public sector)
ms:assetid: a7b44412-a928-4c82-92db-aa1e83b9b6ee
ms:mtpsurl: https://technet.microsoft.com/library/Hh208567(v=AX.60)
ms:contentKeyID: 36056345
author: Khairunj
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- public sector
- France
- French
- terms of payment
- vendor terms of payment
audience: Application User
ms.search.region: France
---

# (FRA) Set up vendor terms of payment (Public sector) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can set up a default payment term that can be used for all vendors and for related purchase agreements, purchase orders, and vendor invoices. For example, you might create a default term in which payments are due within 30 days of the document date. You can also override a default term for a specific vendor or for a specific vendor invoice by selecting a different term on the **Vendors** form.


> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed in the following hotfix for Microsoft Dynamics AX 2012 R3 Cumulative Update 8: KB3047235</P>The standard processes related to vendor terms of payment are augmented for French entities in the public sector. These additional capabilities, which are described in this topic, are available only if the following conditions are met: 
> <UL>
> <LI>
> <P>The <STRONG>Public Sector</STRONG> configuration key is selected.</P>
> <LI>
> <P>The <STRONG>French regulatory</STRONG> configuration subkey is selected.</P>
> <LI>
> <P>In Microsoft Dynamics AX 2012 R3 Cumulative Update 8, the <STRONG>Commitments (France)</STRONG> regulatory document type is selected in the <STRONG>Budget parameters</STRONG> form, when the following hotfix is installed: KB3047235</P>
> <LI>
> <P>In cumulative update 7 for Microsoft Dynamics AX 2012, the <STRONG>Use French public sector accounting rules</STRONG> check box is selected in the <STRONG>Budget parameters</STRONG> form.</P></LI></UL>
> <P>In versions of Microsoft Dynamics AX 2012 prior to cumulative update 7, only the <STRONG>Public Sector</STRONG> configuration key must be selected, but the primary address of the legal entity must be in France.</P>



## Set up default terms of payment for your organization

1.  Click **Accounts payable** \> **Setup** \> **Payment** \> **Terms of payment**.

2.  Click **New** to create a new term of payment.

3.  Enter a code or a short descriptive name such as “Net30” in the **Terms of payment** field.

4.  Enter a **Description** for the term of payment. For example, enter “Net and 30 days” to describe the “Net30” term of payment.

5.  Select a **Payment method** to calculate the due date. For more information, see [Methods of payment - vendors (form)](https://technet.microsoft.com/library/aa618565\(v=ax.60\)).

6.  Enter the number of **Months** or **Days** to use with the payment method to calculate the due date. For example, enter 30 for a term in which payments are due within 30 days.

7.  Select the **Default terms of payment** check box.

8.  The rest of the fields on this form are optional. Add additional information as needed and close the form. For more information, see [Terms of payment (form)](https://technet.microsoft.com/library/aa588427\(v=ax.60\)).


> [!NOTE]
> <P>You can also open the <STRONG>Hold</STRONG> FastTab to enter rules that specify when payments can be put on hold or delayed. You can select the role of a user and then specify the minimum number of days that can be added to the payment due date when that user releases a hold. You can also specify the number of times that a user in that role can place a payment on hold.</P>
> <P>For more information, see <A href="fra-place-or-release-vendor-invoice-payment-holds-public-sector.md">(FRA) Place or release vendor invoice payment holds (Public sector)</A>.</P>



## Override default terms of payment for a vendor or a new or existing vendor invoice

## Override default terms of payment for a specific vendor

Select a term of payment for a vendor and for all vendor invoices from that vendor.

1.  Open the **Vendors** form from either **Accounts payable** or **Procurement and sourcing**:
    
      - Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.
    
      - Click **Procurement and sourcing** \> **Common** \> **Vendors** \> **All vendors**.

2.  On the **All vendors** list page, on the **Action Pane**, on the **Vendor** tab, click **Vendor** to create a new vendor, or double-click a vendor from the list.

3.  Open the **Payment** FastTab and select a term of payment for the vendor from the **Terms of payment** field.

## Override default terms of payment for a new vendor invoice

Select a term of payment for a new vendor invoice.

1.  Open the form from either **Accounts payable** or **Procurement and sourcing**:
    
      - Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.
    
      - Click **Procurement and sourcing** \> **Common** \> **Vendors** \> **All vendors**.

2.  On the **Action Pane**, on the **Invoice** tab, in the **New** group, click **Invoice**, then click **Vendor invoice**.

3.  Enter the details for the invoice.

4.  On the **Action Pane**, click **Header view**.

5.  Open the **Payment** FastTab and select a term of payment for the vendor invoice from the **Terms of payment** field.

## Override default terms of payment for an existing vendor invoice

Select a term of payment for a pending invoice.

1.  Click **Accounts payable** \> **Common** \> **Vendor invoices** \> **Pending vendor invoices**.

2.  Select a vendor invoice.

3.  On the **Action Pane**, on the **Vendor invoice** tab, in the **Maintain** group, click **Edit**.

4.  On the **Action Pane**, click **Header view**.

5.  Open the **Payment** FastTab and select a term of payment for the vendor invoice from the **Terms of payment** field.

## See also

[Terms of payment (form)](https://technet.microsoft.com/library/aa588427\(v=ax.60\))

[Vendors (form)](https://technet.microsoft.com/library/aa592162\(v=ax.60\))

[(FRA) Place or release vendor invoice payment holds (Public sector)](fra-place-or-release-vendor-invoice-payment-holds-public-sector.md)

  


