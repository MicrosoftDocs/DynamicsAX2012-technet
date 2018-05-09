---
title: (JPN) Settle vendor consolidated invoices by using a payment journal
TOCTitle: (JPN) Settle vendor consolidated invoices by using a payment journal
ms:assetid: 19d07e8a-bd65-430d-819a-87d28c5a14a7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711014(v=AX.60)
ms:contentKeyID: 49386424
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (JPN) Settle vendor consolidated invoices by using a payment journal 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Settle open transactions** form to settle open transactions that are related to consolidated invoices after you pay a vendor. You cannot delete a consolidated invoice after it has been settled. For more information, see [(JPN) Settle open transactions - vendor (modified form)](https://technet.microsoft.com/en-us/library/jj711052\(v=ax.60\)) and [Settle open transactions - vendor (form)](https://technet.microsoft.com/en-us/library/aa619609\(v=ax.60\)).

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Create a journal, and then click **Lines**.

3.  In the **Journal voucher** form, create a journal line, and then click **Functions** \> **Settlement**.

4.  In the **Settle open transactions** form, click **Consolidated invoice** \> **Select** to open the **Select transactions** form.

5.  In the **Consolidation ID** field, select the consolidation identification number for the most recent consolidated invoice.
    
    –or–
    
    In the **Consolidation day** field, enter the date when you want the invoices to be consolidated. You can enter a numeric value between 1 and 31. If the consolidation day is set to 0 (zero), the vendor’s invoices will not be consolidated. If the last day of the month falls on a date that has a number that is less than the numeric value that you have specified, the invoices are consolidated on the last business day of the month. For example, if you specify 31 for the consolidation date, and the current month has fewer than 31 days, the invoices are consolidated on the last business day of that month. Therefore, the invoices for April 2012 would be consolidated on April 30, 2012, because that is the last business day of the month.
    

    > [!NOTE]
    > <P>The <STRONG>From date</STRONG> and <STRONG>To date</STRONG> fields are updated with appropriate dates when the consolidation day is set.</P>



6.  Click **OK**. The consolidated invoice transactions are displayed in the **Settle open transactions** form.

7.  Click **Consolidated invoice** \> **Mark all** to settle all of the invoices.

8.  Close the forms.

9.  In the **Journal voucher** form, click **Validate** \> **Validate** to validate the journal.

10. Click **Post** \> **Post** to post the payment voucher, and to settle the transactions. You can settle the transactions fully, or in part, based on the vendor payment amount.
    
    After the transactions have been fully or partially settled, the **Status** field in the **Consolidated invoice** form reflects the **Settled** or **Partially settled** status.

11. Close the form.

## See also

[(JPN) Mark purchase invoices for consolidation and calculate due dates](jpn-mark-purchase-invoices-for-consolidation-and-calculate-due-dates.md)

[Journal header (form)](https://technet.microsoft.com/en-us/library/aa557917\(v=ax.60\))

[Journal voucher - Vendor payment journal (form)](https://technet.microsoft.com/en-us/library/aa599011\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

