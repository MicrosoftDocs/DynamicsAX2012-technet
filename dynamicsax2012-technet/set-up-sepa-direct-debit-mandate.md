---
title: Set up SEPA direct debit mandate
TOCTitle: Set up SEPA direct debit mandate
ms:assetid: 93f488e1-fbe9-44d2-9d4a-f0db94576f24
ms:mtpsurl: https://technet.microsoft.com/library/Dn268415(v=AX.60)
ms:contentKeyID: 54916952
author: tonyafehr
ms.date: 07/25/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.CustPaymMode
- Forms.CustParameters
- direct debit
- Forms.NumberSequenceDetails
- SEPA
- Forms.NumberSequenceTableListPage
- mandate
audience: Application User
ms.search.region: Global
---

# Set up SEPA direct debit mandate 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012_

This topic explains how to configure Single Euro Payment Area (SEPA) direct debit mandates. A SEPA direct debit lets a creditor collect funds from a customer's bank account, provided that a signed mandate has been granted by the customer to the creditor. The customer signs a mandate that authorizes the creditor to collect a payment and instructs the customer's bank to pay the collection.


> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed for Microsoft Dynamics AX 2012 R3, AX 2012 R2 with the hotfix in <A href="https://mbs2.microsoft.com/knowledgebase/kbdisplay.aspx?scid=kb%3ben-us%3b2902097">KB2902097</A>, and AX 2012 with the hotfix in <A href="https://mbs2.microsoft.com/knowledgebase/kbdisplay.aspx?scid=kb%3ben-us%3b2902097">KB2902097</A>.</P>



The following illustration shows the process of setting up SEPA direct debit mandate settings. The numbers correspond to the procedures later in this topic.

![Set up process for SEPA direct debit mandates](images/Dn268415.SEPA_DD_Mandate_Setup(AX.60).gif "Set up process for SEPA direct debit mandates")

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
<td><p>AX 2012 R3, cumulative 6 or later for AX 2012 R2, or AX 2012</p></td>
</tr>
<tr class="even">
<td><p><strong>Country/region</strong></p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: Austria, Belgium, Germany, Spain, France, Italy, or the Netherlands</p></td>
</tr>
</tbody>
</table>


## 1\. Set up a number sequence for direct debit mandates

Each direct debit mandate must have a unique number. Use the **Number sequences** form to create a number sequence for direct debit mandates.

To set up a number sequence for direct debit mandates, follow these steps:

1.  Click **Organization administration** \> **Common** \> **Number sequences** \> **Number sequences**.

2.  On the **Action Pane**, click **Number sequence**.

3.  In the **Number sequence code** field, enter an identifier. You will use this identifier to assign the number sequence to the direct debit mandate system in the **Accounts receivable parameters** form.

4.  On the **Segments** FastTab, create segments. For example, you might use the following format: **SDD-\#\#\#\#\#\#\#\#\#**

5.  On the **General** FastTab, select the **Manual** check box or the **Continuous** check box to enter a manual number sequence or to generate a continuous number sequence.

6.  In the **Smallest** field, enter the lowest possible value that can be used to automatically generate numbers for the number sequence. This field is available only if you select the **Continuous** check box.

## 2\. Set up Accounts receivable parameters for direct debit mandates

Use the **Accounts receivable parameters** form to set up parameters for direct debit mandates.

To set up parameters for direct debit mandates, follow these steps:

1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  Click **Direct debit**, and then in the **Direct debit** area, make the following selections.
    
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
    <td><p><strong>Days required for the first pre-notification</strong></p>
    <p><strong>Days required for recurring pre-notifications</strong></p></td>
    <td><p>Enter the number of days to allow for pre-notifications when a new mandate is added.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Days required for the first core scheme bank submission</strong></p>
    <p><strong>Days required for recurring core scheme bank submissions</strong></p></td>
    <td><p>Enter the number of days to allow for bank submissions that use the core scheme.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Days required for the first B2B bank submission</strong></p>
    <p><strong>Days required for recurring B2B bank submissions</strong></p></td>
    <td><p>Enter the number of days to allow for bank submissions that use the business-to-business (B2B) scheme.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Days required for the first COR1 bank submission</strong></p>
    <p><strong>Days required for recurring COR1 bank submissions</strong></p>
    <p>These controls are available only when Microsoft Dynamics AX 2012 R3, AX 2012 R2 with the hotfix in KB2902097, and AX 2012 with the hotfix in KB2902097 is installed.</p></td>
    <td><p>Enter the number of days to allow for bank submissions that use the COR1 mandate scheme.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Months between usage and expiration</strong></p></td>
    <td><p>The default entry is 36 months (three years).</p></td>
    </tr>
    </tbody>
    </table>


3.  Click **Number sequences**, and then in the **Number sequences** area, select a number sequence code for the **Direct debit mandate ID** reference.

## 3\. Set up a method of payment for direct debit mandates

You must set up a method of payment for direct debit mandates. You use this method of payment to query on invoices to generate direct debit payments for. Use the **Methods of payment** form to set up the method of payment.

To set up a method of payment for direct debit mandates, follow these steps:

1.  Click **Accounts receivable** \> **Setup** \> **Payment** \> **Methods of payment**.

2.  Enter a name for the method of payment, such as **SEPA direct debit**.

3.  Optional: If you expect each of your customers to have multiple mandates, in the **Period** field, select **Invoice**. This creates a separate payment for each invoice, and each payment uses the mandate that is specified for the invoice.

4.  In the **Payment type** field, select **Electronic payment**.

5.  Select the **Require mandate** check box to create payments using direct debit mandates.
    

    > [!NOTE]
    > <P>The <STRONG>Require mandate</STRONG> check box is available only if you select <STRONG>Electronic payment</STRONG> in the <STRONG>Payment type</STRONG> field.</P>



## Next step

You have finished setting up SEPA direct debit mandates. Next, add direct debit mandate information to a customer record. For more information, see [Add direct debit mandate information to a customer account](add-direct-debit-mandate-information-to-a-customer-account.md).

## Related tasks

[Enter an invoice or transaction for a customer who has a direct debit mandate](enter-an-invoice-or-transaction-for-a-customer-who-has-a-direct-debit-mandate.md)

[Create payments for customers who have direct debit mandates](create-payments-for-customers-who-have-direct-debit-mandates.md)

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
<td><p>No configuration key is required for this task.</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles and duties</strong></p></td>
<td><p>To set up SEPA direct debit mandates, you must be a member of a security role that includes the <strong>Enable invoice and cash process</strong> (CustInvoiceInvoiceAndCashProcessEnable) duty.</p></td>
</tr>
</tbody>
</table>


## See also

[SEPA direct debit overview](sepa-direct-debit-overview.md)

  


