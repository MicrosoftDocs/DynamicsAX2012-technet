---
title: Post multiple journals
TOCTitle: Post multiple journals
ms:assetid: 3d2d2afc-88a7-4b11-9c25-05772d8aa37a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa570269(v=AX.60)
ms:contentKeyID: 36931869
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Post multiple journals [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can post multiple financial journals at the same time.

## Post multiple journals that have the same journal type

You can post multiple journals for the following financial journal types by using the same **Journal** form where you create the journals. If a journal requires approval, that journal must be approved before you can post it. For more information, see [Set up financial journal approvals](set-up-financial-journal-approvals.md).

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Journal type</p></th>
<th><p>Location</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Daily</strong></p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Journals</strong> &gt; <strong>General journal</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Allocation</strong></p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Journals</strong> &gt; <strong>Allocation</strong>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Elimination</strong></p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Journals</strong> &gt; <strong>Elimination</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Post fixed assets</strong></p></td>
<td><p>Click <strong>Fixed assets</strong> &gt; <strong>Journals</strong> &gt; <strong>Fixed assets</strong>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Approval</strong></p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Journals</strong> &gt; <strong>Invoices</strong> &gt; <strong>Invoice journal</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Vendor invoice recording</strong></p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Journals</strong> &gt; <strong>Invoices</strong> &gt; <strong>Invoice journal</strong>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Invoice register</strong></p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Journals</strong> &gt; <strong>Invoices</strong> &gt; <strong>Invoice register</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Vendor disbursement</strong></p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Journals</strong> &gt; <strong>Payments</strong> &gt; <strong>Payment journal</strong>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Vendor draw promissory note</strong></p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Journals</strong> &gt; <strong>Promissory notes</strong> &gt; <strong>Draw promissory note journal</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Vendor redraw promissory note</strong></p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Journals</strong> &gt; <strong>Promissory notes</strong> &gt; <strong>Redraw promissory note journal</strong>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Vendor bank remittance</strong></p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Journals</strong> &gt; <strong>Promissory notes</strong> &gt; <strong>Remittance journal</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Vendor settle promissory note</strong></p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Journals</strong> &gt; <strong>Promissory notes</strong> &gt; <strong>Settle promissory note journal</strong>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Customer payment</strong></p></td>
<td><p>Click <strong>Accounts receivable</strong> &gt; <strong>Journals</strong> &gt; <strong>Payments</strong> &gt; <strong>Payment journal</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Customer draw bill of exchange</strong></p></td>
<td><p>Click <strong>Accounts receivable</strong> &gt; <strong>Journals</strong> &gt; <strong>Bill of exchange</strong> &gt; <strong>Draw bill of exchange journal</strong>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Customer redraw bill of exchange</strong></p></td>
<td><p>Click <strong>Accounts receivable</strong> &gt; <strong>Journals</strong> &gt; <strong>Bill of exchange</strong> &gt; <strong>Redraw bill of exchange journal</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Customer protest bill of exchange</strong></p></td>
<td><p>Click <strong>Accounts receivable</strong> &gt; <strong>Journals</strong> &gt; <strong>Bill of exchange</strong> &gt; <strong>Protest bill of exchange journal</strong>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Customer bank remittance</strong></p></td>
<td><p>Click <strong>Accounts receivable</strong> &gt; <strong>Journals</strong> &gt; <strong>Bill of exchange</strong> &gt; <strong>Remittance journal</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Customer settle bill of exchange</strong></p></td>
<td><p>Click <strong>Accounts receivable</strong> &gt; <strong>Journals</strong> &gt; <strong>Bill of exchange</strong> &gt; <strong>Settle bill of exchange journal</strong>.</p></td>
</tr>
</tbody>
</table>


This procedure uses the **Daily** journal type.

1.  Click **General ledger** \> **Journals** \> **General journal**.

2.  Select two or more journals.

3.  Click **Validate**. The journals and journal lines are validated. Correct errors, if you have to, and validate the journals again.

4.  When you are ready to post, click **Post** \> **Post**.
    

    > [!NOTE]
    > <P>Alternatively, you can click <STRONG>Post</STRONG> &gt; <STRONG>Post and transfer</STRONG>. Transactions that do not have errors are posted, and transactions that have errors are transferred to a new journal.</P>



5.  If the **Show** field is set to **Open**, the journals are no longer displayed in the **Journal** form after they are posted, but you can view them by changing the **Show** field to **Posted** or **All**.

## Post multiple journals that have different journal types

1.  You can post multiple journals for multiple journal types by using the **Post journals** form. You can set up batch processing on the **Batch** tab.

2.  Click **General ledger** \> **Periodic** \> **Journals** \> **Post journals**.

3.  Click **Select** to select multiple open journals to post. The range is already set up to include open journals. Click **OK** to return to the **Post journals** form.

4.  You can also manually add or remove journals from the resulting list of journals to be posted.
    
      - To add a journal, press CTRL+N to create a line, and then select the appropriate journal type and number.
    
      - To remove a journal, press ALT+F9.

5.  If you do not want vouchers that have errors to delay the posting of vouchers that do not have errors, select the **Transfer errors** check box on the individual journal lines.

6.  To configure the transfer of errors for selected lines only, click **Default values**.
    
    1.  In the **Set up posting** dialog box, select or clear the **Transfer errors** check box, and then click **Apply**.
    
    2.  Click **Insert all** to apply the setting to all the selected journal lines.
        
        –or–
        
        Click **User default** to apply the setting to all users. Click **OK** to return to the **Post journals** form.

7.  Click **OK** in the **Post journals** form to start the posting process.

## See also

[Journal header (form)](https://technet.microsoft.com/en-us/library/aa557917\(v=ax.60\))

[Journal names (form)](https://technet.microsoft.com/en-us/library/aa617509\(v=ax.60\))

[Post journals (form)](https://technet.microsoft.com/en-us/library/aa583389\(v=ax.60\))

[Processing batch jobs](processing-batch-jobs.md)

[Posting restrictions (form)](https://technet.microsoft.com/en-us/library/hh227598\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

