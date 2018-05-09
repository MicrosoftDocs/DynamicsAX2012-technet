---
title: (CHE) Company identification numbers for tax exemption
TOCTitle: (CHE) Company identification numbers for tax exemption
ms:assetid: 6fba88d7-660e-4ef6-b6c9-fa18c23ac0ef
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn715965(v=AX.60)
ms:contentKeyID: 62200090
ms.date: 04/25/2014
mtps_version: v=AX.60
f1_keywords:
- UID
- company identification number
---

# (CHE) Company identification numbers for tax exemption 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In Switzerland, a legal entity must use the company identification number (UID) instead of the six digit value-added tax (VAT) number, which is the Mehrwertsteuer (MWST) number. You can use the UID to print invoices and for tax reporting purposes. To validate the UID format for a legal entity, in Microsoft Dynamics AX, you must first set up the UID format as a tax registration type, and then assign UID as the legislative type to manage tax registration numbers for legal entities in each country. You can then specify the UID when you create addresses for customer or vendor legal entities, and specify the tax registration information.

## Where can I specify the UID format in Microsoft Dynamics AX and what is the alphanumeric format that I must use for the UID?

You can use the **Format** field in the **Tax registration types** form to specify the format for the UID for your legal entity. For more information, see [Set up a tax registration type](set-up-a-tax-registration-type.md).

You can specify the alphanumeric format for the UID by using the country identification code, a hyphen, and a nine digit number that is grouped into three sets of three digits that are separated by periods. The last number represents the check digit of the UID. The UID number can also be followed by a code that indicates the business type. An example of an UID format is CHE-123.456.789 HR, where HR is the business type that is assigned to the legal entity.

## How can I set UID as the legislative type for my legal entity?

To set UID as the legislative type for your legal entity, you can perform these steps:

1.  In the **Legislative tax registration types** form, in the **Legislative type** field, select **UID**.

2.  In the **Registration type** field, specify a tax registration type for the legal entity.

## How can I add a tax registration type for a customer or a vendor?

To add a tax registration type for a customer or a vendor, you can perform these steps:

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.
    
    –or–
    
    Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.

2.  Create or select a customer or a vendor. For more information, see [Customers (form)](https://technet.microsoft.com/en-us/library/aa590606\(v=ax.60\)) or [Vendors (form)](https://technet.microsoft.com/en-us/library/aa592162\(v=ax.60\)).

3.  In the **Action Pane**, on the **Customer** FastTab, click **Registration** \> **Taxes**.
    
    –or–
    
    In the **Action Pane**, on the **Vendor** FastTab, click **Registration** \> **Taxes**.

4.  In the **Manage addresses** form, create a record for the customer or the vendor.

5.  In the **Tax registration** FastTab, click **Add** to create a record.

6.  In the **Registration type** field, enter the tax registration type for the customer or the vendor.

## How can I set up the parameter that can validate the UID of a legal entity?

To set up the parameter that can validate the UID format, you can follow these steps:

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **External** \> **Country/region parameters**.

2.  Create a record for the legal entity. For more information, see [Country/region parameters (form)](https://technet.microsoft.com/en-us/library/hh242897\(v=ax.60\)).

3.  Select the **Check tax exempt number** check box to validate the tax exempt number based on the UID format for a customer or a vendor.

## Don't see your question here?

We're working to include as many questions as we can, so that Microsoft Dynamics AX Help will be more useful to people just like you.

Tell us what question you would like to add to this topic. Send email to <adocs@microsoft.com>.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

