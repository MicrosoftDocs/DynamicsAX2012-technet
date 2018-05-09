---
title: (JPN) Mark purchase invoices for consolidation and calculate due dates
TOCTitle: (JPN) Mark purchase invoices for consolidation and calculate due dates
ms:assetid: 38893fa7-4b7f-4e4f-b58c-7f5c665bdd0d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711032(v=AX.60)
ms:contentKeyID: 49386443
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (JPN) Mark purchase invoices for consolidation and calculate due dates 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can consolidate several purchase invoices each month. You must mark purchase invoices for consolidation, calculate due dates for payment, and post the consolidated invoice. The payment due date is based on the cutoff day that you specify, and on the holidays that you set up. If you specify the document date, which is the original transaction date, the due date is based on the document date instead of the invoice date.

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**. Double-click a purchase order. For more information, see [Create a purchase order](create-a-purchase-order.md).

2.  In the **Purchase order** form, click **Header view**.

3.  Select the **Target of consolidation** check box to indicate that the invoice for the purchase order will be consolidated later.
    

    > [!NOTE]
    > <P>This field is available only if you select the <STRONG>Consolidated invoice for vendor</STRONG> check box in the <STRONG>Accounts payable parameters</STRONG> form, and if the <STRONG>Consolidation day</STRONG> field in the <STRONG>Vendors</STRONG> form is not set to zero.</P>



4.  Click the **Price and discount** FastTab.

5.  In the **Terms of payment** field, select the terms of payment that have been marked for holiday due date control. For more information, see [(JPN) Set up the terms of payment and the cutoff day for a vendor](jpn-set-up-the-terms-of-payment-and-the-cutoff-day-for-a-vendor.md).
    
    To view the most recently consolidated invoice identification number and the date of the sales order, click **Postings** on the **General** tab. The **Consolidation ID** and **Date** fields display the last consolidated invoice identification number, and the date.

6.  On the **Invoice** tab, click **Invoice**.

7.  In the **Vendor invoice** form, click **Post** \> **Post** to post the purchase order.

8.  Close the forms.

9.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.

10. Select the vendor account for the posted purchase invoice, and then click **Transactions**.

11. In the **Vendor transactions** form, select the posted invoice, and then click the **Payment** tab. The due date for the selected invoice is displayed in the **Due date** field.

12. Close the forms.

## See also

[(JPN) About consolidating invoices](jpn-about-consolidating-invoices.md)

[Purchase order (form)](https://technet.microsoft.com/en-us/library/aa557983\(v=ax.60\))

[(JPN) Terms of payment (modified form)](https://technet.microsoft.com/en-us/library/jj711223\(v=ax.60\))

[(JPN) Purchase order (modified form)](https://technet.microsoft.com/en-us/library/jj711227\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

