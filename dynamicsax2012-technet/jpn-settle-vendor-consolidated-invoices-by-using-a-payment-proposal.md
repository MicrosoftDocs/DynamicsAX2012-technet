---
title: (JPN) Settle vendor consolidated invoices by using a payment proposal
TOCTitle: (JPN) Settle vendor consolidated invoices by using a payment proposal
ms:assetid: f2f2b651-ae4d-4bfe-890f-ab190c3dbba9
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664989(v=AX.60)
ms:contentKeyID: 49386573
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (JPN) Settle vendor consolidated invoices by using a payment proposal [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Vendor payment proposal** form to settle open transactions that are related to consolidated invoices after you pay a vendor. You cannot delete a consolidated invoice after it has been settled. For more information, see [(JPN) Vendor payment proposal (modified form)](https://technet.microsoft.com/en-us/library/jj711029\(v=ax.60\)).

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Create a payment journal, and then click **Lines** to open the **Journal voucher** form.

3.  Click **Payment proposal** \> **Create payment proposal** to create a new payment proposal.

4.  In the **Vendor payment proposal** form, click **Select** to define the filter, and then click **OK**. The transactions that are based on the criteria that you specify are updated in the **Vendor payment proposal** form.

5.  In the **Consolidation ID** field, select the consolidation identification number for the most recent consolidated invoice.
    
    –or–
    
    In the **Consolidation day** field, enter the date when you want the invoices to be consolidated, using a numeric value between 1 and 31. If the consolidation day is set to zero, the vendor’s invoices will not be consolidated. If the last day of the month is on a date with a number that is less than the numeric value that you have specified, then the invoices are consolidated on the last business day of the month. For example, if you specify 31 for the consolidation date, and the current month has fewer than 31 days, then the invoices are consolidated on the last business day of that month. So, the invoices for April 2012 would be consolidated on April 30, 2012, as that is the last business day of the month.
    

    > [!NOTE]
    > <P>The <STRONG>From date</STRONG> and <STRONG>To date</STRONG> fields are updated with appropriate dates when the consolidation day is set.</P>



6.  Close the form. Payment proposal lines for the criteria that you have specified are updated in the **Edit payment proposal** form.

7.  In the **Journal voucher** form, click **Payment proposal** \> **Edit payment proposal**.

8.  In the **Edit payment proposal** form, verify the payment proposal line, and then click **Transfer** \> **OK** to transfer the payment to the **Journal voucher** form.

9.  In the **Journal voucher** form, click **Functions** \> **Generate payments**.

10. In the **Generate payments** form, click **OK** to generate the payments and close the form.

11. In the **Journal voucher** form, click **Validate** \> **Validate** to validate the journal.

12. Click **Post** \> **Post** to post the journal.

## See also

[(JPN) About consolidating invoices](jpn-about-consolidating-invoices.md)

[(JPN) Settle vendor consolidated invoices by using a payment journal](jpn-settle-vendor-consolidated-invoices-by-using-a-payment-journal.md)

[Vendor payment proposal - Edit (form)](https://technet.microsoft.com/en-us/library/aa616323\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

