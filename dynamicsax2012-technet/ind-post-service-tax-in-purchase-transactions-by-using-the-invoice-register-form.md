---
title: (IND) Post service tax in purchase transactions by using the Invoice register form
TOCTitle: (IND) Post service tax in purchase transactions by using the Invoice register form
ms:assetid: a3082937-4e46-41a2-812a-27fac753f01b
ms:mtpsurl: https://technet.microsoft.com/library/JJ664754(v=AX.60)
ms:contentKeyID: 49386085
author: Khairunj
ms.date: 05/06/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.LedgerJournalTransInvoiceRegister
- Forms.LedgerJournalTable
- Forms.TaxTmpWorkTrans
audience: Application User
ms.search.region: India
---

# (IND) Post service tax in purchase transactions by using the Invoice register form 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012_

Use the **Invoice register** form to post service tax in purchase transactions. You can specify the service code and service category for each journal line before you post the journal.

1.  Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice register**.

2.  Click **New** to create a journal, enter the journal details, and then click **Lines**. For more information, see [Create and validate journals and journal lines](create-and-validate-journals-and-journal-lines.md).

3.  In the **Journal voucher** form, on the **Overview** tab, enter the invoice details.

4.  In the **Sales tax group** field, select the sales tax group for the vendor.

5.  In the **Item sales tax group** field, select the item tax group that you have created for the vendor. The sales tax group and the item sales tax group for a journal line must contain tax codes that have a tax type of **Service tax**.

6.  On the **Tax information** tab, in the **Company information** field group, you can modify the name and current address of the legal entity.

7.  In the **Service code** field, select a service code that is attached to goods of the type **Service**.
    

    > [!NOTE]
    > <P>In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2: The accounting code for the service is updated in the <STRONG>Accounting code</STRONG> field based on the service code that you select. For more information, see <A href="ind-set-up-service-codes-for-service-goods.md">(IND) Set up service codes for service goods</A>.</P>



8.  In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2: In the **Service category** field, select one of the following options to indicate the service category for the journal line:
    
      - **Inward** – Select this option when you purchase goods from a vendor.
    
      - **Inter unit or input** – Select this option either when you transfer goods between two units within your legal entity, or when you transfer goods from the legal entity to a subcontractor for additional processing. For example, you can select this option when the goods are manufactured in one unit and then transferred to the packing unit of your legal entity.
    
      - **Others** – Select this option for other service categories. The input tax amount for this category is posted to the expense account instead of to the recoverable account or the interim recoverable account.

9.  On the **Overview** tab, in the **Consignment note number** field, enter the consignment note number for the vendor.

10. Click **Sales tax** to view the calculated service tax in the **Sales tax transactions** form.

11. Close the **Sales tax transactions** form.

12. Validate and post the journal voucher for the invoice register. The service tax amounts are credited to the tax payable accounts.

## Example

An invoice journal line is created for a purchase transaction with the account combination of Ledger (debit)-Vendor (credit) in the **Invoice register** form. The journal line amount is 1,000, which is the credit amount. The rate of service tax is 12 percent, the rate of primary education cess (PE Cess) is 2 percent, and the rate of secondary and higher education cess (SHE Cess) is 1 percent. The **Point of taxation basis** option is selected in the **Accounting basis** field. The reverse charge percentage is 0 percent. The **Load on inventory %** check box is selected, and the percentage is defined as 100 percent for all three service tax components in the **Item sales tax groups** form.

The formula for the calculation of service tax is defined in the **Formula designer** form, as illustrated in the following table.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Tax code/component</p></th>
<th><p>Tax based on</p></th>
<th><p>Calculation expression</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Service tax</p></td>
<td><p>Line amount</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>PE Cess</p></td>
<td><p>Line amount is excluded</p></td>
<td><p>+[Service tax]</p></td>
</tr>
<tr class="odd">
<td><p>SHE Cess</p></td>
<td><p>Line amount is excluded</p></td>
<td><p>+[Service tax]</p></td>
</tr>
</tbody>
</table>


The **Price incl. tax** check box is selected for all of the three service tax components.

According to this example, service tax is calculated in the invoice register journal as shown in the following table.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Tax</p></th>
<th><p>Formula</p></th>
<th><p>Value</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Service tax</p></td>
<td><p>[1,000 - (1,000*12.36/112.36)]</p></td>
<td><p>INR 890</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p>(890.00 * 12%)</p></td>
<td><p>INR 106.38</p></td>
</tr>
<tr class="odd">
<td><p>PE Cess</p></td>
<td><p>(106.38 * 2%)</p></td>
<td><p>INR 2.13</p></td>
</tr>
<tr class="even">
<td><p>SHE Cess</p></td>
<td><p>(106.38 * 1%)</p></td>
<td><p>INR 1.07</p></td>
</tr>
</tbody>
</table>


The original amount and the tax amounts that are calculated are displayed in the **Sales tax transactions** form.

When you validate and post the journal, the total tax amount is credited to the inventory account, and the service tax and the cess are added to the cost of the goods.

If the **Load on inventory %** check box is cleared, the tax amounts are debited to the interim tax recoverable accounts.

The following table displays the journal entries.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Ledger account</p></td>
<td><p>INR 890.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Service tax recoverable account</p></td>
<td><p>INR 106.80</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>PE Cess recoverable account</p></td>
<td><p>INR 2.13</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>SHE Cess recoverable account</p></td>
<td><p>INR 1.07</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Vendor account</p></td>
<td><p></p></td>
<td><p>INR 1000.00</p></td>
</tr>
</tbody>
</table>


## See also

[(IND) Journal voucher - Invoice register (modified form)](https://technet.microsoft.com/library/jj664527\(v=ax.60\))

  


