---
title: (ESP) Generate Report 340
TOCTitle: (ESP) Generate Report 340
ms:assetid: 3690afc3-6ab8-49c5-b1a1-fa8f9db1c41e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn304972(v=AX.60)
ms:contentKeyID: 54899950
ms.date: 06/07/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.TaxReportTable
- ES - 00002
- MsDynAx060.Forms.TaxReportTable
---

# (ESP) Generate Report 340 [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

After you post vendor and customer transactions, you can generate Report 340 for all vendor invoices and customer invoices. You can transfer vendor invoices and customer invoices to the **Spanish VAT reports** form. You can then verify the information for each line, and generate the report as an ASCII file. For more information about Report 340, see [(ESP) Report 340](esp-report-340.md).


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 3 for AX 2012.</P>



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
<td><p><strong>Related setup task</strong></p></td>
<td><p>Set up the cash ledger account for Report 340. For more information, see <a href="https://technet.microsoft.com/en-us/library/hh242856(v=ax.60)">(ESP) Cash ledger accounts (form)</a>.</p></td>
</tr>
<tr class="even">
<td></td>
<td><p>Set up a sales tax settlement period. For more information, see <a href="set-up-a-sales-tax-settlement-period.md">Set up a sales tax settlement period</a> and <a href="https://technet.microsoft.com/en-us/library/aa633944(v=ax.60)">Sales tax settlement periods (form)</a>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Setup</strong></p></td>
<td><p>In the <strong>General ledger parameters</strong> form, on the <strong>Sales tax</strong> FastTab, select the <strong>Special regime for cash accounting method</strong> check box to ensure that the cash accounting method is active for the legal entity.</p>
<p>In the <strong>Vendors</strong> form, on the <strong>Invoice and delivery</strong> FastTab, select the <strong>Special regime for cash accounting method</strong> check box to ensure that the cash accounting method is active for the selected vendor.</p></td>
</tr>
</tbody>
</table>


## 1\. Create Report 340

Use the **Spanish VAT list** form to transfer vendor invoices and customer invoices to the **Spanish VAT reports** form. You can specify a threshold for the cash amount that is received from a customer in the **Spanish VAT list** form. If the cash amount of the combined transactions for the customer exceeds the specified limit, then the amount is included in the report.

To create Report 340, follow these steps:

1.  Click **General ledger** \> **Periodic** \> **Sales tax payments** \> **Spain** \> **Spanish VAT reports**.

2.  Click **Create new** to open the **Spanish VAT list** form. For more information, see [(ESP) Spanish VAT list (form)](https://technet.microsoft.com/en-us/library/aa577152\(v=ax.60\)).

3.  Specify the criteria for transferring the invoices to the **Spanish VAT reports** form.

4.  In the **Minimum payment amount in cash** field, enter the threshold value of the cash amount in the accounting currency that is received from the customer. This value is used to filter the invoices that are transferred to the report.

5.  Click **OK** to transfer the invoices to the **Spanish VAT reports** form. For more information, see [(ESP) Spanish VAT reports (form)](https://technet.microsoft.com/en-us/library/aa554510\(v=ax.60\)).

## 2\. Verify the VAT report lines and generate Report 340

You can verify the **Operation type** field values for the VAT report lines, and then generate the report as an ASCII file.

To verify the VAT report lines and generate Report 340, follow these steps:

1.  Click **General ledger** \> **Periodic** \> **Sales tax payments** \> **Spain** \> **Spanish VAT reports**.

2.  In the **Spanish VAT reports** form, click **VAT report lines** to open the **VAT report lines** form. For more information, see [(ESP) VAT report lines (form)](https://technet.microsoft.com/en-us/library/aa557419\(v=ax.60\)).

3.  On the **Overview** tab, verify the report lines.

4.  In the **Operation type** field, enter one of the options listed in the following table.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Operation type</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>A</p></td>
    <td><p>Generates a report that contains transactions for sold properties.</p>
    <p>In the <strong>Amount of property sale subject to VAT</strong> field, enter the amount that is received from the sale of the property.</p></td>
    </tr>
    <tr class="even">
    <td><p>R</p></td>
    <td><p>Generates a report that contains transactions for the rental of business properties.</p>
    <ol>
    <li><p>If the rented property has a property tax account number, in the <strong>Property tax account number</strong> field, enter the tax account number for the property.</p></li>
    <li><p>In the <strong>Location code for the building/property</strong> field, enter the location code of the property.</p></li>
    </ol></td>
    </tr>
    <tr class="odd">
    <td><p>S</p></td>
    <td><p>Generates a report that contains transactions for subventions or grants that are received from public administrations or private companies.</p></td>
    </tr>
    <tr class="even">
    <td><p>T</p></td>
    <td><p>Generates a report that contains transactions for income from copyrights.</p></td>
    </tr>
    <tr class="odd">
    <td><p>U</p></td>
    <td><p>Generates a report that contains transactions that are based on insurance operations.</p></td>
    </tr>
    <tr class="even">
    <td><p>V</p></td>
    <td><p>Generates a report that contains transactions for the purchase of services from travel agencies.</p></td>
    </tr>
    <tr class="odd">
    <td><p>W</p></td>
    <td><p>Generates a report that contains transactions for services and transactions for the import of items that have a production tax associated with them in the cities of Ceuta and Melilla.</p></td>
    </tr>
    <tr class="even">
    <td><p>X</p></td>
    <td><p>Generates a report that contains transactions for agricultural operations.</p></td>
    </tr>
    <tr class="odd">
    <td><p>Z</p></td>
    <td><p>Generates a report that contains transactions for posted payment or transactions for posted collections that involve cash accounting method.</p></td>
    </tr>
    </tbody>
    </table>
    

    > [!NOTE]
    > <P>Leave the <STRONG>Operation type</STRONG> field blank to generate a report that contains transactions that have a cash amount that exceeds the specified limit. In the <STRONG>Cash received</STRONG> field, enter the cash amount that is received by the legal entity for the property. In the <STRONG>Fiscal year of invoice(s) for cash received</STRONG> field, enter the year during which the cash is received from the customer.</P>



5.  Close the form.

6.  Optional: In the **Spanish VAT reports** form, click **Summary** to preview the summary of the Spanish VAT register book.

7.  Click **Output**, and then click **Export to ASCII file** to open the **Export to ASCII file** dialog box.

8.  In the **File name** field, enter the path and file name for the ASCII file.

9.  Click **OK** to generate Report 340 as an ASCII file.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

