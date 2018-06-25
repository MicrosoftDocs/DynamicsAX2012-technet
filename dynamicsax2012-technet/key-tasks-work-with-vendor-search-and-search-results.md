---
title: 'Key tasks: Work with vendor search and search results'
TOCTitle: 'Key tasks: Work with vendor search and search results'
ms:assetid: 01f5affc-6ade-4ec0-9a43-cde7e080082c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242095(v=AX.60)
ms:contentKeyID: 36055923
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- search results
- Forms.VendSearchAddCategory
- Vendor search
- MsDynAx060.Forms.VendSearchAddCategory
---

# Key tasks: Work with vendor search and search results [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You may want to select a group of vendors or locate a specific vendor in your organization's list of approved vendors. For example, you are creating a request for quotations (RFQ), and you want to contact all of the approved vendors who are in a specific geographical area. Because your organization has many vendors, locating all of the vendors that you want can be time-consuming. However, you can search for a vendor or a group of vendors by defining criteria, such as geographical area, in the **Vendor search** form.

In the search results, you can view the profile for current, prospective, and unsolicited vendors. You can request to add an unsolicited vendor as an approved vendor for your organization. If your assigned role has the required permissions, you can create an RFQ, a purchase requisition, or a purchase order for a current vendor. You can also add a current vendor to another legal entity and create a new vendor from an unsolicited vendor who is listed in the search results.

## What do you want to do?

Select search criteria

Modify search criteria

View a vendor profile from search results

View the transaction history for a current vendor

Create a request for quotation for a current vendor

Create a purchase requisition for a current vendor

Create a purchase order for a current vendor

Add a current vendor to another legal entity

Create a current vendor from an unsolicited vendor

Request to add an unsolicited vendor

Find form help

## Select search criteria

Use this procedure to select your search criteria. The search criteria that you select are combined. For example, if you select a city and a procurement category, the search results contain only vendors who are in the selected city and the selected procurement category.

1.  Click **Procurement and sourcing** \> **Inquiries** \> **Vendors** \> **Vendor search**.

2.  In the **Vendor search criteria** form, select the types of vendors that you want to include in your search:
    
      - **Current vendors** – Include vendors who are approved to do business with your organization.
    
      - **Prospective vendors** – Include prospective vendors. Requests to add these vendors are in review.
    
      - **Unsolicited vendors** – Include vendors who have requested to do business with your organization.
    
      - **Employees that are vendors** – Include vendors who are also employees of your organization.
    
      - **All legal entities** – Include all vendors in all legal entities of your organization.

3.  On the **Common criteria** FastTab, select procurement categories, part of a vendor name, a location, and diversity status classifications that apply to all vendor types.

4.  On the **Vendor specific criteria** FastTab, select criteria that apply only to approved vendors, such as a hold status and procurement category. If you want to search for vendor performance ratings in a specific procurement category, select the vendor evaluation criterion group or vendor evaluation criteria that you want to include in your search.

5.  On the **Advanced search query** FastTab, you can view and modify the search expression that represents your search criteria. If you want to search for specific words, enter terms in the **Enter search expression** field, and then click **Update**.

6.  To view the number of vendors of each type that are returned by your search criteria, click the **Refresh** link in the **Search results summary** section.

7.  To view the search results, click **OK**.

Back to top

## Modify search criteria

1.  Click **Procurement and sourcing** \> **Inquiries** \> **Vendors** \> **Vendor search**.

2.  Select search criteria, and then click **OK**.

3.  In the **Vendor search results** form, on the **Action Pane**, click **Search criteria**.

4.  In the **Vendor search criteria** form, modify your search criteria.
    

    > [!TIP]
    > <P>To view the number of vendors of each type that your modified search criteria return, click the <STRONG>Refresh</STRONG> link in the <STRONG>Search results summary</STRONG> section.</P>



5.  Click **OK** to view the results of your modified search.

Back to top

## View a vendor profile from search results

Use this procedure to view the profile of a current, prospective, or unsolicited vendor who is listed in the search results.

To remove a vendor from the list, select the check box on the row for the vendor, and then click **Remove**.

1.  Click **Procurement and sourcing** \> **Inquiries** \> **Vendors** \> **Vendor search**.

2.  Select search criteria, and then click **OK**.

3.  In the **Vendor search results** form, on the **Current vendors** FastTab, click **Details** to open the **Vendors** form.

4.  On the **Prospective vendors** FastTab, click **Details** to open the **Prospective vendor profile** form.

5.  On the **Unsolicited vendors** FastTab, click **Details** to open the **Unsolicited vendors** form.

Back to top

## View the transaction history for a current vendor

Use this procedure to view the transactions, such as invoices and payments, with a vendor who is listed in the **Current vendors** search results.

1.  Click **Procurement and sourcing** \> **Inquiries** \> **Vendors** \> **Vendor search**.

2.  Select search criteria, and then click **OK**.

3.  In the **Vendor search results** form, on the **Current vendors** FastTab, select the vendor that you want to view transactions for.

4.  Click **Inquiries**, and then click **Transactions** to open the **Vendor transactions** form.

Back to top

## Create a request for quotation for a current vendor

Use this procedure to create a request for quotation (RFQ) for a vendor who is listed in the **Current vendors** search results.

You can create an RFQ for a current vendor if the vendor has a hold status of **No**, **Invoice**, **Payment**, or **Never**. You cannot create an RFQ if the vendor has a hold status of **All** or **Requisition**. A vendor can have the following hold statuses:

  - **No** – No transaction types are on hold for the vendor.

  - **Invoice** – No invoices can be created or posted for the vendor.

  - **All** – All transactions with this vendor are on hold.

  - **Payment** – No payments can be generated for the vendor.

  - **Requisition** – No requisitions can be created for the vendor.

  - **Never** – No transaction types are on hold for the vendor, and the vendor cannot automatically be put on hold because of inactivity. This status is used for vendors who are used regularly but infrequently. For example, you can use the **Never** hold status for a vendor who does some kind of annual maintenance.

<!-- end list -->

1.  Click **Procurement and sourcing** \> **Inquiries** \> **Vendors** \> **Vendor search**.

2.  Select search criteria, and then click **OK**.

3.  In the **Vendor search results** form, on the **Current vendors** FastTab, select the vendor that you want to create an RFQ for.

4.  Click **Functions**, and then click **Request for quotation** to open the **New request for quotation** form. For more information about how to create an RFQ, see [New request for quotation (form)](https://technet.microsoft.com/en-us/library/hh209104\(v=ax.60\)).

Back to top

## Create a purchase requisition for a current vendor

Use this procedure to create a new purchase requisition for a vendor who is listed in the **Current vendors** search results. You cannot create a purchase requisition for a vendor who has a hold status of **Requisition**. For more information about vendor holds, see "Create a request for quotation for a current vendor," earlier in this topic.

1.  Click **Procurement and sourcing** \> **Inquiries** \> **Vendors** \> **Vendor search**.

2.  Select search criteria, and then click **OK**.

3.  In the **Vendor search results** form, on the **Current vendors** FastTab, click **Purchase requisition** to open the **Prepare a new purchase requisition** form. For more information about how to create purchase requisitions, see [Key tasks: Create and submit a purchase requisition](key-tasks-create-and-submit-a-purchase-requisition.md).

Back to top

## Create a purchase order for a current vendor

Use this procedure to create a new purchase order for a vendor who is listed in the **Current vendors** search results. You can create purchase orders only for vendors who have a hold status of **No**. A status of **No** indicates that there is no hold on transactions with the vendor. For more information about vendor holds, see "Create a request for quotation for a current vendor," earlier in this topic.

1.  Click **Procurement and sourcing** \> **Inquiries** \> **Vendors** \> **Vendor search**.

2.  Select search criteria, and then click **OK**.

3.  In the **Vendor search results** form, on the **Current vendors** FastTab, select the vendor that you want to create a purchase order for.

4.  Click **Functions**, and then click **Purchase order**.

5.  In the **Transfer vendor information?** dialog box, click **Yes** to copy the name, address, buyer group, currency, and language from the vendor profile to the new purchase order. Click **No** if you want to copy only the vendor name and address to the new purchase order. For more information about how to create a purchase order, see [Create purchase order (form)](https://technet.microsoft.com/en-us/library/aa570189\(v=ax.60\)).

Back to top

## Add a current vendor to another legal entity

Use this procedure to add a vendor who is listed in the **Current vendors** search results to another legal entity in your organization.


> [!NOTE]
> <P>To perform this task, you must select <STRONG>All legal entities</STRONG> in your search criteria.</P>



1.  Click **Procurement and sourcing** \> **Inquiries** \> **Vendors** \> **Vendor search**.

2.  Select search criteria, and then click **OK**.

3.  In the **Vendor search results** form, on the **Current vendors** FastTab, select a vendor.

4.  Click **Add vendor to another legal entity**.

5.  In the **Add vendor to another legal entity** form, select a legal entity. Select a vendor group, currency, and vendor hold status, if there is any hold for the vendor, and then click **OK**.

6.  In the **Vendors** form, enter any additional information about the vendor for the selected legal entity.

Back to top

## Create a current vendor from an unsolicited vendor

Use this procedure to create a new vendor for your organization from a vendor who is listed in the **Unsolicited vendors** search results. Your assigned role must have permissions to create new vendors.


> [!NOTE]
> <P>If your assigned role does not have permissions to create new vendors, you can request to add an unsolicited vendor. See "Request to add an unsolicited vendor," later in this topic.</P>



1.  Click **Procurement and sourcing** \> **Inquiries** \> **Vendors** \> **Vendor search**.

2.  Select search criteria, and then click **OK**.

3.  In the **Vendor search results** form, on the **Unsolicited vendors** FastTab, select an unsolicited vendor.

4.  Click **Functions**, and then click **Create new vendor**.

5.  In the **Add vendor to another legal entity** form, select the legal entity that you want to add the vendor to.

6.  Select a vendor group and a currency for the vendor.

7.  Select a vendor hold status, if there is any hold for the vendor, and then click **OK**. For more information about vendor holds, see "Create a request for quotation for a current vendor," earlier in this topic.

8.  In the **Vendors** form, enter any additional information, such as contact information, about the new vendor.

Back to top

## Request to add an unsolicited vendor

Use this procedure to request to add an unsolicited vendor to your organization as an approved vendor.

1.  Click **Procurement and sourcing** \> **Inquiries** \> **Vendors** \> **Vendor search**.

2.  Select search criteria, and then click **OK**.

3.  In the **Vendor search results** form, on the **Unsolicited vendors** FastTab, select a vendor.

4.  Click **Functions**, and then click **Create vendor request** to open a new vendor request on the **Vendor requests** page in Enterprise Portal for Microsoft Dynamics AX.

5.  Complete and submit your request to add the unsolicited vendor.

Back to top

## Find form help

[Vendor search criteria (form)](https://technet.microsoft.com/en-us/library/hh209336\(v=ax.60\))

[Vendor search results (form)](https://technet.microsoft.com/en-us/library/hh242677\(v=ax.60\))

[New request for quotation (form)](https://technet.microsoft.com/en-us/library/hh209104\(v=ax.60\))

[Purchase requisitions (form)](https://technet.microsoft.com/en-us/library/hh209453\(v=ax.60\))

[Purchase order (form)](https://technet.microsoft.com/en-us/library/aa557983\(v=ax.60\))

[Unsolicited vendors (form)](https://technet.microsoft.com/en-us/library/hh209226\(v=ax.60\))

[Add vendor to legal entities (form)](https://technet.microsoft.com/en-us/library/hh209684\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

