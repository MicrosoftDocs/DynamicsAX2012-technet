---
title: View, modify, delete, or cancel a general budget reservation (Public sector)
TOCTitle: View, modify, delete, or cancel a general budget reservation (Public sector)
ms:assetid: aa9220f9-5e69-4cd4-a3f1-2bd98cf480ea
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn792459(v=AX.60)
ms:contentKeyID: 65205504
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- public sector
- budget reservation
- Forms.BudgetReservationListPage_PSN
- Forms.BudgetReservationTable_PSN
- budget reservations
- general budget reservation
- general budget reservations
- budget reservation cancellation
- budget reservation changes
- budget reservation deletion
- budget reservation edits
- budget reservation views
- general budget reservation views
- general budget reservation edits
- general budget reservation cancellation
- general budget reservation deletion
- general budget reservation changes
---

# View, modify, delete, or cancel a general budget reservation (Public sector) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

You can view the details of a general budget reservation, including information about the vendor, items or services ordered, and budget specifics. You can also access the source documents that the reservation applies to.


> [!NOTE]
> <P>General budget reservations are available only if the <STRONG>Public Sector</STRONG> configuration key is selected and if Microsoft Dynamics AX 2012 R3 Cumulative Update 8 is installed with the following hotfix: KB3047235</P>



## View a general budget reservation

To view an existing general budget reservation, use the following steps.

1.  Click **Budgeting \> Common \> General budget reservations \> All general budget reservations**.
    

    > [!NOTE]
    > <P>You can also choose to look only at general budget reservations that are in draft status, that are active, or that have expired.</P>



2.  On the list page, double-click the reservation that you want. The details window opens.

3.  Optional: On the **Action Pane**, in the **Accounting** group, click **View distributions**, **Subledger journal**, or **Vouchers** to see those entries.

4.  (Optional) To view any related purchase requisition, click the **Line details** FastTab, and then click the purchase requisition reference number.

5.  (Optional) To see a summary of the financial accounting, on the **Action Pane**, on the **Manage** tab, click **Financial summary**. In the **Reservation line** list, you can select the line for which you want to see details.

6.  (Optional) To see details of the budget reservation relief, on the **Action Pane**, on the **Manage** tab, click **Relief details**. To see the original document that relieves this general budget reservation (such as an invoice or purchase order), on the Action strip, click **View relieving document**.
    

    > [!NOTE]
    > <P>You can also access the <STRONG>General budget reservation relief details</STRONG> form from the <STRONG>General budget reservation financial summary</STRONG> form, by clicking <STRONG>Relief details</STRONG> on the Action strip.</P>



## Modify a general budget reservation

Use this procedure to make changes to a general budget reservation.


> [!NOTE]
> <P>If the reservation is in workflow, recall the workflow status to <STRONG>Draft</STRONG> status, follow the steps below, and then resubmit the amended reservation to workflow. For more information, see <A href="submit-a-general-budget-reservation-to-workflow-public-sector.md">Submit a general budget reservation to workflow (Public sector)</A>.</P>



1.  Click **Budgeting \> Common \> General budget reservations \> All general budget reservations**.

2.  On the list page, click the reservation that you want.

3.  On the **Action Pane**, in the **Maintain** group, click **Edit**.

4.  Make any changes you want, including adding or deleting lines.
    

    > [!NOTE]
    > <P>When a reservation line has already been referenced by a purchase order or vendor invoice, your ability to delete or change lines may be limited.</P>



5.  On the **Action Pane**, in the **Plan** group, click **Post**.

## Delete a general budget reservation

Use this procedure to delete a general budget reservation that is in draft status. For other general budget reservations, you can cancel them, but not delete them entirely.

1.  Click **Budgeting \> Common \> General budget reservations \> Draft general budget reservations**.

2.  On the list page, click the reservation that you want to delete.

3.  On the **Action Pane**, in the **Maintain** group, click **Delete**.

4.  In the confirmation dialog box, click **Yes**.

## Cancel a general budget reservation

Use this procedure to cancel a general budget reservation that has been posted. This does not delete the reservation but cancels it, generating the accounting and budget entries to reverse the impact of the originally posted document.


> [!NOTE]
> <P>You can cancel an entire general budget reservation, not individual lines.</P>



1.  Click **Budgeting \> Common \> General budget reservations \> All general budget reservations**.

2.  On the list page, click the reservation that you want to cancel.

3.  On the **Action Pane**, click **Cancel**.

4.  In the confirmation dialog box, click **Yes**.
    
    The general ledger and budget control updates occur and the transaction is recorded in the Transaction log.

## See also

[About general budget reservations (Public sector)](about-general-budget-reservations-public-sector.md)

[Create a general budget reservation (Public sector)](create-a-general-budget-reservation-public-sector.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

