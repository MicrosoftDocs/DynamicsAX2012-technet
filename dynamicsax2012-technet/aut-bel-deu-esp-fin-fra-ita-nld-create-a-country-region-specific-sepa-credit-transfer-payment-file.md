---
title: (AUT, BEL, DEU, ESP, FIN, FRA, ITA, NLD) Create a country/region-specific SEPA credit transfer payment file
TOCTitle: (AUT, BEL, DEU, ESP, FIN, FRA, ITA, NLD) Create a country/region-specific SEPA credit transfer payment file
ms:assetid: e7658fb6-9a69-47b1-95d8-d1fb01cc5b1c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh227461(v=AX.60)
ms:contentKeyID: 36059816
ms.date: 05/06/2014
mtps_version: v=AX.60
f1_keywords:
- Classes.CustVendCreatePaymJournal_Vend
- Classes.VendSumForPaym
- Forms.CustVendPaymentProcessingData
- Forms.LedgerJournalTransVendPaym
- Forms.LedgerJournalTable
- credit transfer
- credit transfer payment
- FR - 00020
- DE - 00016
- FI - 00001
- ES - 00024
- IT - 00034
audience: Application User
ms.search.region: Austria, Belgium, Germany, Spain, Finland, Italy, Netherlands
---

# (AUT, BEL, DEU, ESP, FIN, FRA, ITA, NLD) Create a country/region-specific SEPA credit transfer payment file 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Single European Payment Area (SEPA) is an initiative in European Union (EU) countries/regions to provide a common electronic banking system to transfer payments within EU countries/regions. The process of sending payments electronically to a vendor is called credit transfer. The electronic file format for SEPA credit transfer is based on XML ISO 20022. The European Payment Council (EPC) has specified a general XML format that you can use to generate the SEPA credit transfer payment file.


> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed for Microsoft Dynamics AX 2012 R3, AX 2012 R2 with the hotfix in <A href="https://mbs2.microsoft.com/knowledgebase/kbdisplay.aspx?scid=kb%3ben-us%3b2902097">KB2902097</A>, and AX 2012 with the hotfix in <A href="https://mbs2.microsoft.com/knowledgebase/kbdisplay.aspx?scid=kb%3ben-us%3b2902097">KB2902097</A>.</P>



Depending on the version that you are using, you can generate electronic payment files for SEPA in the following formats:

  - In AX 2012 R3 or cumulative update 7 or later for AX 2012 R2: The SEPA credit transfer format supports the PAIN.001.001.03 version for Germany, Spain, Finland, France, and Italy. You can select a country or region to generate vendor payments for in the XML format.

  - In AX 2012 R3, AX 2012 R2 with the hotfix in KB2902097, and AX 2012 with the hotfix in KB2902097: You can generate electronic payment files for SEPA credit transfers in the PAIN.001.001.03 XML file format for Austria, and in the PAIN.001.003.03 XML file format for Germany.

You can create electronic payment files by using the Application Integration Framework (AIF) and the Extensible Stylesheet Language for Transformations (XSLT) for Austria, Belgium, Germany, Spain, Finland, France, Italy, or the Netherlands. Electronic payments are processed by using the electronic payment services in the AIF. A single comprehensive export payment XML schema is available to export a payment in the XML format. The transform files for selected formats such as **SEPACreditTransfer** or **SEPADirectDebit** are available. You must set up the outbound ports for the AIF and map the transform files for the SEPA payment format to create a SEPA credit transfer payment file. For more information, see [Set up an outbound payment format](set-up-an-outbound-payment-format.md).

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
<td><p>AX 2012 R3, AX 2012 R2, or AX 2012</p></td>
</tr>
<tr class="even">
<td><p><strong>Country/region</strong></p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: Austria, Belgium, Germany, Spain, Finland, France, Italy, and the Netherlands.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Related set up tasks</strong></p></td>
<td><ul>
<li><p>Set up the legal entity information on the <strong>Statutory reporting</strong> tab in the <strong>Legal entities</strong> form. For more information, see <a href="https://technet.microsoft.com/en-us/library/hh242860(v=ax.60)">Legal entities (form)</a>.</p></li>
<li><p>Set up an outbound integration port for payments. For more information, see <a href="set-up-an-outbound-payment-format.md">Set up an outbound payment format</a>.</p></li>
<li><p>Set up company bank accounts for SEPA credit transfers. For more information, see <a href="set-up-a-bank-account-for-a-customer-account.md">Set up a bank account for a customer account</a>.</p></li>
<li><p>Set up vendors and vendor bank accounts for SEPA credit transfers. For more information, see <a href="specify-when-a-vendor-bank-account-is-active.md">Specify when a vendor bank account is active</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


Use the following procedure to create and send a vendor payment as a SEPA credit transfer file for Austria, Belgium, Germany, Spain, Finland, France, Italy, or the Netherlands.

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Create a journal, and then click **Lines** to open the **Journal voucher** form. For more information, see [Create and validate journals and journal lines](create-and-validate-journals-and-journal-lines.md).

3.  Select a journal line, and then click **Payment proposal** \> **Create payment proposal**.

4.  In the **Vendor payment proposal** form, click **Select**, specify the criteria for retrieving payments for the SEPA credit transfer, and then click **OK**.

5.  In the **Vendor payment proposal** form, click **OK** to transfer the payments to the **Journal voucher** form.

6.  Click **Functions** \> **Generate payments**.

7.  Select **Payment method**, and then in the **Method of payment** field, select the method of payment for SEPA credit transfers.

8.  Select **Export payment using service**, and then in the **Payment format** field, select an export format such as **SEPACreditTransfer** to generate payments by using the payment format. You can create payment formats for AIF services in the **Outbound ports for electronic payments** form.

9.  In the **Bank account** field, select the bank account for SEPA credit transfer.

10. Click **OK** to open the **Payment processing data** form.

11. In the **Payment processing data** form, modify the information that is specific to the SEPA credit transfer payment format.

12. In AX 2012 R3 and cumulative update 7 or later for AX 2012 R2: To generate the country/region specific version of the credit transfer file, in the **Value** field, enter the two-digit country or region code. Leave this field blank to use the generic credit transfer file format.

13. Select the **Control report** check box to print a control report for the electronic payment file.

14. Click **OK** to generate the electronic payment file in the format of the selected country.

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.

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
<td><p><strong>Configuration keys</strong></p></td>
<td><p><strong>LedgerBasic</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Security role and duty</strong></p></td>
<td><p>To create a country/region-specific SEPA credit transfer payment file, you must be a member of the <strong>Accounts payable payments clerk</strong> (PaymAccountsPayablePaymentsClerk) security role that includes the <strong>Maintain vendor</strong> (PaymVendorPaymentsMaintain) duty.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Security role and privilege</strong></p></td>
<td><p>To create a country/region-specific SEPA credit transfer payment file, you must be a member of the <strong>Accounts payable payments clerk</strong> (PaymAccountsPayablePaymentsClerk) security role that includes the <strong>Generate vendor payments report</strong> (VendOutPaymGenerate) privilege.</p></td>
</tr>
</tbody>
</table>


## See also

[Outbound ports for electronic payments (form)](https://technet.microsoft.com/en-us/library/hh208616\(v=ax.60\))

[Payment processing data (form)](https://technet.microsoft.com/en-us/library/hh242773\(v=ax.60\))

  


