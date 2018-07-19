---
title: 'Key tasks: Manage pay-when-paid projects'
TOCTitle: 'Key tasks: Manage pay-when-paid projects'
ms:assetid: 092d5135-8e25-47f2-bee0-e7d17d71bcd7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh351817(v=AX.60)
ms:contentKeyID: 36676365
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- retention
- project add-in
- vendor payments
- pay when paid
- vendor retention
- customer payments
- PWP projects
- payment terms
- PWP
audience: Application User
ms.search.region: Global
---

# Key tasks: Manage pay-when-paid projects 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you approve a vendor as a subcontractor for a project, you can withhold payment to the vendor or subcontractor until you have been paid by your customer for the project. In Microsoft Dynamics AX, you set up pay-when-paid (PWP) terms when you set up a purchase order with the vendor.

## What do you want to do?

Learn more about...

Set up PWP terms for the project

Create a purchase order with PWP terms

Update customer payment information and pay the vendor

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About pay-when-paid projects](about-pay-when-paid-projects.md)

## Set up PWP terms for the project

Set up the PWP threshold percentage for the project. The percentage that you enter sets the minimum amount that the customer must pay on the project before you pay the vendor. The threshold amount is automatically calculated on the customer invoices that you create for the project.

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Open the project from the project list page.

2.  On the **Vendor agreements** FastTab, click **Add line**.

3.  In the **Account code** field, select from the following options:
    
      - **Table** – The PWP terms apply to a single vendor.
    
      - **Group** – The PWP terms apply to all vendors in a vendor group.
    
      - **All** – The PWP terms apply to all vendors.

4.  In the **Vendor/Vendor group** field, select the vendor or vendor group to which the PWP terms apply. If you selected **All** in the previous step, this field is unavailable.

5.  If the project also has vendor retention terms set up for the vendor, in the **Vendor retention terms** field, select the rule ID for the retention terms. For more information about vendor retention terms, see [About vendor payment retention for projects](about-vendor-payment-retention-for-projects.md).

6.  In the **PWP threshold percentage** field, enter the threshold percentage for the project. The percentage that you enter for the project sets the minimum amount that you must be paid by the customer before you pay the vendor.

Back to top

## Create a purchase order with PWP terms

Create a purchase order for the vendor. When you post an invoice from the vendor, and the vendor is subject to PWP terms, the PWP terms are displayed on the purchase order lines.

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**. On the **Action Pane**, on the **Purchase order** tab, in the **New** group, click **Purchase order**. In the **Create purchase order** form, enter the required information, and then click **OK**. Alternatively, open a purchase order in the **All purchase orders** list.

2.  In the **Purchase order** form, on the **Purchase order lines** FastTab, review the details of the purchase order line for the vendor. The **Pay when paid** check box is automatically selected, and the **PWP threshold percentage** value is automatically copied to this form from the **PWP threshold percentage** field in the **Projects** form.

3.  If you do not want to apply PWP terms to the vendor for this purchase order line, you can clear the **Pay when paid** check box. If you do clear the check box, the **PWP threshold percentage** field for this purchase order line is set to 0 (zero).

Back to top

## Update customer payment information and pay the vendor

When the vendor finishes work on the project and sends you an invoice, review the project status and customer invoices to see whether the PWP terms were met for the project. If the PWP terms for the vendor were met, you can determine which lines on the vendor invoice to pay, based on the customer payments for the project.

If you decide to pay the vendor even if the PWP terms were not met, you can override the PWP terms in the **Vendor invoices with retention** form.


> [!NOTE]
> <P>In Microsoft Dynamics AX 2012 Feature Pack and Microsoft Dynamics AX 2012, this form was named <STRONG>Vendor invoice</STRONG>.</P>



1.  Click **Project management and accounting** \> **Inquiries** \> **Retention** \> **Vendor invoices with pay when paid**. In the **Vendor invoices with retention** form, enter values in the **Filter** section to find the vendor invoice to review, and then click **Search**.

2.  On the **Vendor invoice lines** FastTab, review the lines in the vendor invoice for the project, and select the line for which to make changes.

3.  If the PWP conditions are met for the invoice line, click **Release vendor payment**. This clears the **Pay when paid** check box, and the status of the **Ready for payment** field changes to **Yes**.

Back to top

## Find form help

[Projects (form)](https://technet.microsoft.com/en-us/library/aa585245\(v=ax.60\))

[Purchase order (form)](https://technet.microsoft.com/en-us/library/aa557983\(v=ax.60\))

[Vendor invoices with pay when paid (form)](https://technet.microsoft.com/en-us/library/hh227358\(v=ax.60\))

## Find related tasks

[Key tasks: Manage vendor payment retention for projects](key-tasks-manage-vendor-payment-retention-for-projects.md)

  


