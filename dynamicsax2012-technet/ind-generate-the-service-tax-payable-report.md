---
title: (IND) Generate the service tax payable report
TOCTitle: (IND) Generate the service tax payable report
ms:assetid: 17a2f107-b438-4994-bc97-33c10e88e358
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn344873(v=AX.60)
ms:contentKeyID: 56117704
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.TaxReportVoucher
- Forms.ServiceTaxPayableDetailed_IN
- Forms.ServiceTaxTransactions_IN
- Forms.TaxServiceTaxPayable_IN
- MsDynAx060.Forms.TaxReportVoucher
- MsDynAx060.Forms.ServiceTaxPayableDetailed_IN
- MsDynAx060.Forms.ServiceTaxTransactions_IN
- MsDynAx060.Forms.TaxServiceTaxPayable_IN
---

# (IND) Generate the service tax payable report 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012_

Use the **Sales tax payments** form to generate the service tax payable report. This report contains details about service tax payable information by component for each accounting code that is used to make payment to the tax authorities.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 6 for AX 2012 R2.</P>



1.  Click **General ledger** \> **Reports** \> **External** \> **Sales tax payments**.

2.  In the **Sales tax payments** form, select transactions that have a tax type of **Service tax**.

3.  Click **Payable service tax** to open the **Payable service tax** form, where you can view the service tax payable details for each accounting code.

4.  Select a service code, and then click **Tax details** to open the **Service tax payment** form, where you can view the accounting code and other information that is related to the tax amounts for the service code.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Service code</strong></p></td>
    <td><p>The identification code for the service.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Accounting code</strong></p></td>
    <td><p>The accounting code that is related to the service code.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Tax component</strong></p></td>
    <td><p>The identification code for the tax component.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Tax payable amount</strong></p></td>
    <td><p>The tax amount that is payable for the tax component.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Tax recoverable settled</strong></p></td>
    <td><p>The recoverable tax amount that is settled for the tax component.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Other tax settled</strong></p></td>
    <td><p>The service tax recoverable amount that is settled for other taxes, such as Excise duty.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Balance tax</strong></p></td>
    <td><p>The balance tax amount for the tax component that is paid to the tax authority.</p></td>
    </tr>
    </tbody>
    </table>


5.  Click **Transactions** to open the **Service tax payment transactions** form, where you can view details about the recoverable and payable tax amounts for transactions.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Recoverable amount in total</strong></p></td>
    <td><p>The total recoverable tax amount for the selected tax component.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Payable amount in total</strong></p></td>
    <td><p>The total payable tax amount for the selected tax component.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Voucher</strong></p></td>
    <td><p>The voucher number in the ledger.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Date</strong></p></td>
    <td><p>The transaction date.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Source</strong></p></td>
    <td><p>The type of document for which the sales tax transaction is posted.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Tax type</strong></p></td>
    <td><p>The tax type for the sales tax transaction.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Sales tax code</strong></p></td>
    <td><p>The identification code of the sales tax for the sales tax transaction.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Recoverable amount</strong></p></td>
    <td><p>The recoverable tax amount for the sales tax code.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Payable amount</strong></p></td>
    <td><p>The payable tax amount for the sales tax code.</p></td>
    </tr>
    </tbody>
    </table>


6.  Close the **Service tax payment transactions**, **Service tax payment**, and **Payable service tax** forms.

7.  In the **Sales tax payments** form, click **Print report**, and then click **OK** to generate the service tax payable report.

## See also

[(IND) Create a tax setoff rule to settle an excise recoverable amount](ind-create-a-tax-setoff-rule-to-settle-an-excise-recoverable-amount.md)

[(IND) About accounting codes for services](ind-about-accounting-codes-for-services.md)

[(IND) Set up service codes for service goods](ind-set-up-service-codes-for-service-goods.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

