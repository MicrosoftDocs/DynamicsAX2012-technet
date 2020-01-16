---
title: (SWE) Create a Bankgirot payment file that includes Postgirot payments
TOCTitle: (SWE) Create a Bankgirot payment file that includes Postgirot payments
ms:assetid: 8d1b3600-50a1-4ce5-a066-df323c5361f8
ms:mtpsurl: https://technet.microsoft.com/library/Gg242879(v=AX.60)
ms:contentKeyID: 36058488
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Sweden
---

# (SWE) Create a Bankgirot payment file that includes Postgirot payments 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Sweden, vendor invoice payment files are sent to two payment clearing services, Postgirot and Bankgirot. You can include Postgirot payments in a Bankgirot payment file and send only one file that contains both types of payments to Bankgirot.

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Select a journal, and then click **Lines**.

3.  Click **Functions** \> **Generate payments**.

4.  In the **Export format** field, select the **Bankgirot (SE)** export file format.
    

    > [!NOTE]
    > <P>Alternatively, in the <STRONG>Method of payment</STRONG> field, select a method of payment that uses the <STRONG>Bankgirot (SE)</STRONG> export file format.</P>



5.  Click **Dialog**.

6.  In the **Specification to the recipient** field, enter information for the recipient of the file.

7.  In the **Include payment method** field, select a method of payment that uses the **Postgirot (SE)** export file format to include Postgirot payments in the Bankgirot file. Payments that have a postal giro account assigned to them use the Swedish kronor (SEK) currency and are for debit invoices that are included in the Bankgirot payment file.
    

    > [!NOTE]
    > <P>If you leave the <STRONG>Include payment method</STRONG> field blank, only payments that use the <STRONG>Bankgirot (SE)</STRONG> export file format are included in the Bankgirot payment file.</P>



8.  Click **OK**.

9.  In the **Generate payments** form, click **OK** to generate a Bankgirot payment file that includes Postgirot payments.

10. Close the forms.

## See also

[Bankgirot (SE) (form)](https://technet.microsoft.com/library/hh209643\(v=ax.60\))

[Generate payments - vendor (class form)](https://technet.microsoft.com/library/aa586980\(v=ax.60\))

[(SWE) Set up a method of payment for Bankgirot payments](swe-set-up-a-method-of-payment-for-bankgirot-payments.md)

  


