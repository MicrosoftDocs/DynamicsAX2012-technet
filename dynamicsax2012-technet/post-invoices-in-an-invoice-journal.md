---
title: Post invoices in an invoice journal
TOCTitle: Post invoices in an invoice journal
ms:assetid: a2c339a3-0ce4-483a-b21b-8ec10067f7f9
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa571835(v=AX.60)
ms:contentKeyID: 36058802
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- invoices
- invoice journal
---

# Post invoices in an invoice journal [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to post invoices that are entered in an invoice journal.

(ESP) You must specify a delivery date to calculate the due date for the journal voucher.

1.  Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice journal**.

2.  Create a journal. For more information, see the first steps in [Create and validate journals and journal lines](create-and-validate-journals-and-journal-lines.md).

3.  Click **Lines** and enter information about the first vendor invoice.

4.  By default, the **Date** field contains the system date. If required, you can enter another date, and this date appears on the posted invoice.

5.  Enter the information that is required for posting:
    
      - **Account** – The vendor account number.
    
      - **Invoice** – The vendor's invoice number.
    
      - **Credit** or **Debit** – The invoice amount. The **Credit** field is used for vendor purchases and the **Debit** field is used for credit notes.
    
      - **Offset account** – The offset account must have the same currency as the **Currency** field.

6.  Enter information in other fields, such as **Description**, as required.

7.  (USA) Click the **Invoice** tab. In the **1099 box** field, select the 1099 box code for the original issue discount (OID).

8.  (USA) In the **1099 amount** field, enter the amount to be reported in the 1099 form.

9.  (ESP) On the **General** tab, in the **Delivery date** field, select the date on which the items or services are delivered. On the **Overview** tab, the **Due date** field is updated with the due date that is calculated for the voucher.

10. Click **Validate** \> **Validate voucher only** to run a check that the voucher is ready for posting.
    

    > [!NOTE]
    > <P>If budget control is turned on and the appropriate source documents and journals are enabled for budget control, the <STRONG>Journal voucher</STRONG> form can display a budget check icon. A red X indicates that the budget check failed, a yellow triangle indicates that the budget check passed with warnings, and a green check mark indicates that the budget check passed. Budget check results can be affected by project budget control settings, over budget permissions, and other budget control parameters and settings. For more information, see <A href="about-budget-control.md">About budget control</A>.</P>



11. Click **New** to create another line and enter information about the next invoice.

12. Repeat steps 4 through 10 until you have entered information about all the invoices.
    

    > [!NOTE]
    > <P>Instead of validating each line, you can periodically click <STRONG>Validate</STRONG> &gt; <STRONG>Validate</STRONG> to run a check on all the lines.</P>



13. Click **Post** \> **Post**.
    
    The posted lines can then be settled. For example, you might settle the lines in a payment journal. (Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.)
    

    > [!NOTE]
    > <P>If a message is displayed that mentions posting restrictions, you might be set up to post only journals that you created. For more information, see <A href="https://technet.microsoft.com/en-us/library/hh227598(v=ax.60)">Posting restrictions (form)</A>.</P>



## See also

[(USA) Post a vendor payment journal and generate a 1099 OID report](usa-post-a-vendor-payment-journal-and-generate-a-1099-oid-report.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

