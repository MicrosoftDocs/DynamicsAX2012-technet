---
title: (RUS) Post a cash voucher with cash reimbursements and cash disbursements
TOCTitle: (RUS) Post a cash voucher with cash reimbursements and cash disbursements
ms:assetid: 834c0a66-7960-48d7-9f07-23094c5c6e15
ms:mtpsurl: https://technet.microsoft.com/library/JJ678435(v=AX.60)
ms:contentKeyID: 49387666
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Post a cash voucher with cash reimbursements and cash disbursements 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can post a cash voucher with confirmation by selecting the **Use Confirm Status** check box in the **Bank parameters** form. To post the cash voucher without confirmation, clear the **Use Confirm Status** check box. The confirmation method is most efficient when the chief accountant and cashier certify creation of the cash orders and reimbursement or disbursements of cash.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>




> [!NOTE]
> <P>You must enter the voucher transactions with cash reimbursement and cash disbursement details in the <STRONG>Journal voucher</STRONG> form. For more information, see "<A href="rus-register-reimbursement-or-disbursement-slips.md">(RUS) Register reimbursement or disbursement slips</A>".</P>



After you confirm and approve a cash voucher, the cash voucher can have various statuses, depending on the method that you selected.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Validation method</strong></p></td>
<td><p><strong>Approval status</strong></p></td>
</tr>
<tr class="even">
<td><p>With confirmation</p></td>
<td><p><strong>None</strong>, <strong>Confirmed</strong>, <strong>Approved</strong>, or <strong>Rejected</strong></p></td>
</tr>
<tr class="odd">
<td><p>Without confirmation</p></td>
<td><p><strong>None</strong> or <strong>Approved</strong></p></td>
</tr>
</tbody>
</table>


After you confirm a voucher, a cash order number is assigned, and you can post it to the ledger accounts.

You can reject the current status of a cash voucher. When rejected, **Approved** vouchers revert to **Confirmed** and **Confirmed** vouchers revert to **None**.

You can reject the confirmed cash vouchers as needed. Rejected vouchers are displayed in the cash order reimbursement and the disbursement registration journal, but they are not registered in the cash book report.

## Post a cash voucher with confirmation

1.  Click **Cash and bank management** \> **Setup** \> **Cash and bank management parameters**.

2.  Select the **Use Confirm Status** check box to post a cash voucher with confirmation.

3.  Press CTRL+S or close the form.

4.  Click **Cash and bank management** \> **Journals** \> **Slip journal**.

5.  Select the required cash journal, and then click **Lines** to open its corresponding **Journal voucher** form.

6.  Click **Documents Approval \> Confirm** to confirm the cash order.

7.  In the **Approval parameters** form, enter the percentage amount for the VAT value and the sales tax value to be printed on the **Cash reimbursement slip**.

8.  Click **OK**. After confirmation, a number is generated for the current cash document that corresponds to the number sequence in the **Order Number** field. The **approval status** is displayed as **Confirmed**.

9.  Click **Document Approval** \>**Approve** to approve the document. In the **Approval Status** field, the document status is displayed as **Approved** and the **Post** button is activated. The **Cash order** menu item in the **Print** button is activated. You cannot modify the details.
    

    > [!NOTE]
    > <P>The cash voucher reflects the reimbursement or the disbursement amounts, and the cash balance is updated.</P>



10. Click **Document Approval** \>**Reset Status** to change the current status.
    

    > [!NOTE]
    > <P>When you reset the status, the <STRONG>Approval Status</STRONG> changes from <STRONG>Approved</STRONG> to <STRONG>Confirmed</STRONG> and from <STRONG>Confirmed</STRONG> to <STRONG>None</STRONG>.</P>



11. Click **Post** to post the document.

12. Click **Print \> Cash order** to print the order.

## Post a cash voucher without confirmation

1.  Click **Cash and bank management** \> **Setup** \> **Cash and bank management parameters**.

2.  Clear the **Use Confirm Status** check box to post a cash voucher without confirmation.

3.  Press CTRL+S or close the form.

4.  Click **Cash and bank management** \> **Journals** \> **Slip journal**.

5.  Select the required cash journal, and then click **Lines** to open its corresponding **Journal voucher** form.
    

    > [!NOTE]
    > <P>If they were not previously entered, enter the transaction text and the debit and credit details for the cash voucher.</P>



6.  Click **Document Approval** \> **Approve**. The **Approval Status** is displayed as **Approved**. You cannot modify the details. The **Cash order** option from the**Print** button is activated.
    

    > [!NOTE]
    > <P>The <STRONG>Approved</STRONG> status of the cash voucher reflects the reimbursement or disbursement of the cash voucher. Consequently, the open slip journal lines display the <STRONG>Approved</STRONG> status, and the total debit and total credit amounts are updated.</P>



7.  Click **Document Approval** \>**Reset Status** to change the current status to **None**.

8.  Click **Post** to post the voucher.

9.  Click **Print** \>**Cash Order** to print the voucher.

## See also

[(RUS) Cash and bank management parameters (modified form)](https://technet.microsoft.com/library/jj711566\(v=ax.60\))

  


