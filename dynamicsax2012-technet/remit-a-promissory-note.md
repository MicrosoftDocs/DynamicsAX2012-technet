---
title: Remit a promissory note
TOCTitle: Remit a promissory note
ms:assetid: 2057a405-7686-4f53-b626-c9058303ed8a
ms:mtpsurl: https://technet.microsoft.com/library/Aa496785(v=AX.60)
ms:contentKeyID: 36966699
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Remit a promissory note 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use a remittance journal to generate a remittance file that you can send to your bank. The file can contain information about drawn promissory notes, redrawn promissory notes, and invoices that have been posted.

1.  Click **Accounts payable** \> **Journals** \> **Promissory notes** \> **Remittance journal**.

2.  Create a journal.

3.  Click the **Promissory note** tab, and then select a bank account.

4.  Click **Lines**.

5.  In the **Journal voucher** form, select the vendor account for the invoice, and then click **Functions** \> **Settlement**.

6.  In the **Settle open transactions** form, in the **Mark** column, select the check box for the invoice transaction that has an **Invoiced** status. Also select the check box for the promissory note payment transaction that has a **Drawn** status. Close the form to transfer the selected transactions to journal lines.
    

    > [!NOTE]
    > <P>Any remaining amount on the transactions must be settled. You cannot create a partial settlement in a remittance journal.</P>



7.  In the **Journal voucher** form, click the **Payment fee** tab. Verify that the payment fee that is included with the remittance is correct.

8.  To create the remittance file for the bank, click **Functions** \> **Generate remittance**.

9.  Click **Post** \> **Post**.
    
    A new line is created for the promissory note. This line has a **Remitted** status and a sequence number of 1 or greater. Additionally, a vendor transaction is created for the invoice. This transaction has an **Invoice remitted** status. Both the promissory note and the vendor transaction are shown in the **Promissory note journal** inquiry form. In the **Promissory note statistics** inquiry form, the number in the **Remitted and remitted-confirmed documents** row is increased, and the number in the **Drawn and invoice-confirmed documents** row is decreased.
    
    When you remit a drawn promissory note, the promissory note summary account is debited, and the remitted promissory notes summary account is credited.
    
    When you remit an invoice, the vendor summary account is debited, and the invoice-remitted summary account is credited.
    

    > [!NOTE]
    > <P>If you receive a message that mentions posting restrictions, you might be set up to post only journals that you created. For more information, see <A href="https://technet.microsoft.com/library/hh227598(v=ax.60)">Posting restrictions (form)</A>.</P>



## See also

[Settle a promissory note](settle-a-promissory-note.md)

[Redraw a promissory note](redraw-a-promissory-note.md)

[Create and validate journals and journal lines](create-and-validate-journals-and-journal-lines.md)

[Journal header (form)](https://technet.microsoft.com/library/aa557917\(v=ax.60\))

[Promissory note statistics (form)](https://technet.microsoft.com/library/aa550186\(v=ax.60\))

[About payment types](about-payment-types.md)

[Print copies of payments as non-negotiable checks](print-copies-of-payments-as-non-negotiable-checks.md)

  


