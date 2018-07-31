---
title: SEPA direct debit overview
TOCTitle: SEPA direct debit overview
ms:assetid: 0815eaa6-1e9b-4fd8-9921-819431357e3a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn268411(v=AX.60)
ms:contentKeyID: 54916949
ms.date: 07/18/2014
mtps_version: v=AX.60
f1_keywords:
- Core
- B2B
- direct debit
- SEPA
- COR1
- PAIN
audience: Application User
ms.search.region: Global
---

# SEPA direct debit overview 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The Single Euro Payments Area (SEPA) is set up by the European Commission, and dictates that all electronic payments are considered domestic, regardless of the country/region where the individual, business, or organization, and the bank are located. There is no difference between national and cross-border payments. The SEPA includes the 27 European Union (EU) member states, plus Iceland, Liechtenstein, Norway, Switzerland, and Monaco. The SEPA helps form a single market for payment transactions within the European Economic Area (EEA). Ultimately, the SEPA is expected to reduce the number of payment formats that banks, businesses, and individuals must work with.


> [!NOTE]
> <P>Unless otherwise noted below, this topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 6 for AX 2012.</P>



## What is the goal of SEPA Direct Debits?

A SEPA Direct Debit allows a creditor to collect funds from a customer’s bank account, provided that a signed mandate has been granted by the customer to the creditor. The customer signs a mandate that authorizes the creditor to collect a payment and instructs the customer’s bank to pay the collection.

SEPA Direct Debits create, for the first time, a payment instrument that can be used for both national and cross-border euro direct debits throughout the 32 SEPA countries/regions.

There are two schemes available: the SEPA Core Direct Debit Scheme and the SEPA Business to Business (B2B) Direct Debit Scheme. Both schemes use the same file format.


> [!NOTE]
> <P>In AX 2012 R3, AX 2012 R2 with the hotfix in <A href="https://mbs2.microsoft.com/knowledgebase/kbdisplay.aspx?scid=kb%3ben-us%3b2902097">KB2902097</A>, and AX 2012 with the hotfix in <A href="https://mbs2.microsoft.com/knowledgebase/kbdisplay.aspx?scid=kb%3ben-us%3b2902097">KB2902097</A>, you can use the COR1 scheme for SEPA Core direct debit mandates.</P>



## What is the Core Direct Debit scheme?

The SEPA Core Direct Debit Scheme is the basic scheme. It has the following attributes:

  - The transfer of funds is in euros (even though the bank accounts may hold funds in other currencies).

  - The customer and creditor must each hold an account with a credit institution that is located within the SEPA.

  - The customer must grant a signed mandate to the creditor.

  - Mandates expire 36 months after the last initiated collection.

  - The creditor must store mandates for as long as the mandate is valid and for at least 14 months after the last collection.

  - The scheme may be used for single (one-time) or recurring direct debit collections.

  - Customers have a “no questions asked” right to receive a refund for up to eight weeks after the debit of their account.

## What is the SEPA Business to Business (B2B) Direct Debit scheme?

The SEPA B2B Direct Debit Scheme applies to business-to-business transactions and builds on the SEPA Core Direct Debit Scheme. The main differences are:

  - The SEPA B2B Direct Debit Scheme is not allowed when the customer is a private individual (consumer).

  - The customer is not entitled to obtain a refund of an authorized transaction.

  - Customer banks must make sure that that the collection is authorized, by verifying the collection against mandate information. Customer banks and customers are required to agree on the verification that will be performed for each direct debit.

  - The scheme offers a shorter timeline for presenting direct debits and reduces the return period.

## Can I use the COR1 scheme for direct debit mandates?

Yes. If you are using AX 2012 R3, AX 2012 R2 with the hotfix in KB2902097, and AX 2012 with the hotfix in KB2902097, you can use the COR1 scheme for SEPA direct debit mandates in Austria, Belgium, Germany, France, Italy, Spain, and the Netherlands. The scheme provides a shorter pre-notification period for the direct debit collection for the creditor.

## What are International Bank Account Numbers (IBAN) and Bank Identifier Codes (BIC)?

The International Bank Account Number (IBAN) and Bank Identifier Code (BIC) are used to identify any account in the 32 SEPA countries/regions. In Microsoft Dynamics AX 2012, enter the BIC in the **SWIFT code** field and the IBAN in the **IBAN** field. Both fields are located on the **Additional identification** FastTab on the **Bank account** tab in the **Bank accounts** form. This is true for both the creditor’s bank account and the customer’s bank account.

## Where do I enter creditor identifiers (Direct debit IDs)?

In the SEPA, each creditor is identified by a unique creditor identifier. This identifier lets the customer and the customer bank filter each direct debit, and then process or reject the direct debit according to customer instructions. Creditors must request this identifier through their bank. In Microsoft Dynamics AX 2012, enter this identifier in the **Direct debit ID** field for the bank account for the legal entity.

## What are mandates?

The customer signs a mandate that authorizes the creditor to collect a payment and instructs the customer’s bank to pay the collection. The customer can issue the mandate in paper form or electronically. By default, the mandate expires 36 months after the direct debit is last initiated. See [Set up SEPA direct debit mandate](set-up-sepa-direct-debit-mandate.md) to configure settings for mandates. See [Add direct debit mandate information to a customer account](add-direct-debit-mandate-information-to-a-customer-account.md) for information about how to record a mandate for a customer.

## Where do I specify the SEPA Direct Debit file format (ISO 20022)?

The SEPA data formats are based on the ISO 20022 message standards. In Microsoft Dynamics AX 2012, you will select the **SEPADirectDebit** format as a payment service when you generate payments for a payment journal. For information about how to configure a payment format by using a service, see [Walkthrough: Configuring and outbound integration port for payments](walkthrough-configuring-an-outbound-integration-port-for-payments.md). The walkthrough describes how to set up the **SEPACreditTransfer** payment format. To configure an outbound port for direct debit payments, use the **SEPADirectDebit** payment format instead.

## In what file formats can I generate SEPA direct debit payment files?

Depending on the version that you are using, you can generate electronic payment files for SEPA direct debits in the following formats:

  - In AX 2012 R3 and cumulative update 7 or later for AX 2012 R2: You can generate SEPA direct debit payment files in the PAIN.008.001.02 XML file format for Belgium, Germany, Spain, France, Italy, and the Netherlands.

  - In AX 2012 R3, AX 2012 R2 with the hotfix in KB2902097, and AX 2012 with the hotfix in KB2902097: You can generate SEPA direct debit payment files in the PAIN.008.001.02 XML file format for Austria, and in the PAIN.008.003.02 XML file format for Germany.

## How do refunds and returns work with SEPA direct debits?

Under both SEPA Direct Debit schemes, customers have certain rights to refunds. The customer is allowed to recall any authorized transactions during an eight-week period after the due date, without having to give a reason. In the case of unauthorized transactions, the period is extended to 13 months after the due date. In Microsoft Dynamics AX 2012, reversals of any payments that have been made are accomplished manually by using the **Cancel payment** button in the **Customer transactions** form.

## Don't see your question here?

We're working to include as many questions as we can, so that Microsoft Dynamics AX Help will be more useful to people just like you.

Tell us what question you would like to add to this topic. Send email to <adocs@microsoft.com>.

## See also

[Set up SEPA direct debit mandate](set-up-sepa-direct-debit-mandate.md)

[Add direct debit mandate information to a customer account](add-direct-debit-mandate-information-to-a-customer-account.md)

[Enter an invoice or transaction for a customer who has a direct debit mandate](enter-an-invoice-or-transaction-for-a-customer-who-has-a-direct-debit-mandate.md)

[Create payments for customers who have direct debit mandates](create-payments-for-customers-who-have-direct-debit-mandates.md)

  


