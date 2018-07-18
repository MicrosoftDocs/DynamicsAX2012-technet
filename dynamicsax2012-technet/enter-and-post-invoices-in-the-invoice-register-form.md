---
title: Enter and post invoices in the Invoice register form
TOCTitle: Enter and post invoices in the Invoice register form
ms:assetid: 34e5195d-8d0d-4ab1-a255-e521d94c8e5a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa570120(v=AX.60)
ms:contentKeyID: 36966711
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Enter and post invoices in the Invoice register form 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to enter and post vendor invoices. Another worker will approve and post the invoices.

(ESP) You must specify a delivery date to calculate the due date for the journal voucher.

1.  Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice register**.

2.  Create a journal. For more information, see the first steps in [Create and validate journals and journal lines](create-and-validate-journals-and-journal-lines.md).

3.  Click **Lines**. In the **Journal voucher** form, enter information about the first vendor invoice, as explained in the following steps.

4.  Enter a date for the line. The default date is the system date.

5.  Enter or select the information that is required for posting:
    
      - **Account** – Select the vendor account number.
    
      - **Invoice** – Enter the vendor's invoice number.
    
      - **Credit** or **Debit** – Enter the invoice amount. Usually, the **Credit** field is used for purchases from a vendor, and the **Debit** field is used for credit notes from a vendor.
    
      - **Approved by** – Select the ID of the worker who will approve the invoice line.

6.  Enter information in other fields, such as **Description** and **Purchase order**, as necessary.

7.  (ESP) On the **General** tab, in the **Delivery date** field, select the date on which the items or services are delivered. On the **Overview** tab, the **Due date** field is updated with the due date that is calculated for the voucher.

8.  Click **Validate** \> **Validate voucher only** to validate that the line is ready to be posted.
    

    > [!NOTE]
    > <P>If budget control is turned on, and the appropriate source documents and journals are enabled for budget control, the <STRONG>Journal voucher</STRONG> form can display a budget check icon. A red X indicates that the budget check failed, a yellow triangle indicates that the budget check passed with warnings, and a green check mark indicates that the budget check passed. Budget check results can be affected by project budget control settings, over-budget permissions, and other budget control parameters and settings. For more information, see <A href="about-budget-control.md">About budget control</A>.</P>



9.  Press Ctrl+N or click **New** to enter a new line, and then repeat steps 4 through 8 for the next invoice.

10. Repeat steps 4 through 9 until all the invoices are entered.
    

    > [!NOTE]
    > <P>You do not have to validate each line separately. Instead, you can periodically click <STRONG>Validate</STRONG> &gt; <STRONG>Validate</STRONG> to validate all the lines.</P>



11. Click **Post** \> **Post** to post the voucher.
    

    > [!NOTE]
    > <P>If you receive a message that mentions posting restrictions, you might be set up to post only journals that you created. For more information, see <A href="https://technet.microsoft.com/en-us/library/hh227598(v=ax.60)">Posting restrictions (form)</A>.</P>



## See also

[Enter vendor invoices in journals](enter-vendor-invoices-in-journals.md)

  


