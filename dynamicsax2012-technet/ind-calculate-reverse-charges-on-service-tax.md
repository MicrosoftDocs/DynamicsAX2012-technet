---
title: (IND) Calculate reverse charges on service tax
TOCTitle: (IND) Calculate reverse charges on service tax
ms:assetid: ce73c410-ffc8-479c-9f6f-97c1dd03b627
ms:mtpsurl: https://technet.microsoft.com/library/Dn304996(v=AX.60)
ms:contentKeyID: 54900004
author: tonyafehr
ms.date: 11/17/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.TaxReportVoucher
- Forms.PurchTableListPage
- Forms.PurchTable
- Forms.LedgerJournalTransVendPaym
- Forms.VendEditInvoice
- Forms.LedgerJournalTable
- accrue payable
- Accrue payable service tax
- reverse charge
audience: Application User
ms.search.region: India
---

# (IND) Calculate reverse charges on service tax 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the following procedure to create and post a purchase order that has a reverse charge on the service tax.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 1 for AX 2012 R2.</P>



## Prerequisites

The following table shows the prerequisites that must be in place before you start.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Version</strong></p></td>
<td><p>Microsoft Dynamics AX 2012 R3</p></td>
</tr>
<tr class="even">
<td><p><strong>Country/region</strong></p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: India</p></td>
</tr>
<tr class="odd">
<td><p><strong>Related setup tasks</strong></p></td>
<td><ol>
<li><p>In the <strong>General ledger parameters</strong> form, in the <strong>Sales tax</strong> pane, in the <strong>Apply India taxes</strong> field group, select the <strong>Service tax</strong> check box. For more information, see <a href="https://technet.microsoft.com/library/jj677901(v=ax.60)">(IND) General ledger parameters (modified form)</a>.</p></li>
<li><p>In the <strong>Service tax</strong> field group, in the <strong>Accounting basis</strong> field, select <strong>Point of taxation basis only</strong>.</p></li>
</ol></td>
</tr>
</tbody>
</table>


## Create and post a purchase order that has a reverse charge on the service tax

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Create a purchase order, and then create purchase order lines. For more information, see [Create a purchase order](create-a-purchase-order.md) and [(IND) Purchase orders (modified form)](https://technet.microsoft.com/library/jj664798\(v=ax.60\)).

3.  In the **Purchase order** form, on the **Purchase order lines** FastTab, enter the quantity and the purchase price of the items.

4.  On the **Line details** FastTab, on the **Setup** tab, select the sales tax group and item sales tax group for the service tax. For more information, see [(IND) Sales tax groups (modified form)](https://technet.microsoft.com/library/jj664688\(v=ax.60\)) and [(IND) Item sales tax groups (modified form)](https://technet.microsoft.com/library/jj710918\(v=ax.60\)).

5.  On the **Tax information** tab, modify the details as required.
    

    > [!NOTE]
    > <P>If you attached a service tax code (STC) number to the address of the legal entity in the <STRONG>Manage tax information</STRONG> form, the <STRONG>STC number</STRONG> field is updated with the STC number of the legal entity. The STC number is used to identify the ledger accounts that service tax amounts are posted to. For more information, see <A href="ind-key-tasks-tax-information-for-legal-entities.md">(IND) Key tasks: Tax information for legal entities</A>.</P>



6.  On the **Action Pane**, on the **Purchase** tab, click **Confirm** to confirm the purchase order.

7.  On the **Action Pane**, on the **Invoice** tab, click **Invoice** to open the **Vendor invoice** form, where you can generate an invoice for the purchase order. For more information, see [(IND) Vendor invoice (modified form)](https://technet.microsoft.com/library/jj664905\(v=ax.60\)).
    

    > [!NOTE]
    > <P>On the <STRONG>Tax information</STRONG> tab, the <STRONG>Recoverable/Expense on tax settlement</STRONG> check box is selected. A selected check box indicates that the service tax is posted to the recoverable account or the expense account after the tax settlement process is completed.</P>



8.  Click **Post** to post the purchase order, and then close the form. The tax amount for the vendor is posted to the payable account instead of an interim payable account. The service tax for the vendor is posted to the service tax receivable account and the service cost account. For more information, see [(IND) Create tax ledger posting groups and attach an STC number](ind-create-tax-ledger-posting-groups-and-attach-an-stc-number.md).
    

    > [!NOTE]
    > <P>In the <STRONG>Item sales tax groups</STRONG> form, select the <STRONG>Accrue payable service tax at invoicing</STRONG> check box. A selected check box indicates that the payable service tax is accrued when an invoice is posted in the reverse charge mechanism.</P>



9.  Create and post the journal to settle the invoice in the **Payment journal** and **Journal voucher** forms. For more information, see [Journal header (form)](https://technet.microsoft.com/library/aa557917\(v=ax.60\)), [(IND) Journal voucher - Vendor payment journal (modified form)](https://technet.microsoft.com/library/jj664794\(v=ax.60\)), and [(IND) Calculate service tax using a vendor payment journal](ind-calculate-service-tax-using-a-vendor-payment-journal.md).

10. In the **Sales tax payments** form, complete the sales tax payment process. For more information, see [(IND) Calculate sales tax settlements](ind-calculate-sales-tax-settlements.md) and [(IND) Sales tax payments (modified form)](https://technet.microsoft.com/library/jj677884\(v=ax.60\)).

11. Create and post the journal to pay the service tax to the tax authority by using the **Payment journal** and **Journal voucher** forms.

  


