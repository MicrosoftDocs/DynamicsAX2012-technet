---
title: (IND) Apply for duty drawback (DBK) for an export order
TOCTitle: (IND) Apply for duty drawback (DBK) for an export order
ms:assetid: 98e4fa44-5d89-4960-b687-3a3f42cc431a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678062(v=AX.60)
ms:contentKeyID: 49386023
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (IND)
- india
- export order
- apply DBK
---

# (IND) Apply for duty drawback (DBK) for an export order 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Complete the following steps to apply for duty drawback, and to generate the duty drawback transactions and accounting entries:

1.  Run the EXIM duty drawback periodic process.

2.  View the duty drawback transactions, and post the accounting entries.

After you complete the procedures, the following actions are performed:

  - The duty drawback is posted. The DBK voucher number is generated according to the number sequence that is specified in the **Incentive scheme parameters** form.

  - The duty drawback amount is posted to the port authority customer account that is specified in the **EXIM ports** form. If the port authority customer account is not specified, the duty drawback amount is posted to the receivable account that is specified in the **Incentive scheme parameters** form.

  - The posted shipping bills are cleared from the **Total duty drawback amount** form.

  - An entry is created in the **EXIM Duty Drawback schemes** form. The drawback ID is generated according to the **DBK internal ID** number sequence that is specified in the **Number sequences** area in the **Incentive scheme parameters** form. Also, the status of the transaction line is updated to **Applied**.

**Run the EXIM duty drawback process**


> [!NOTE]
> <P>You can complete this procedure only if the <STRONG>Duty drawback</STRONG> check box is selected in the <STRONG>DBK</STRONG> area in the <STRONG>Incentive scheme parameters</STRONG> form.</P>



1.  Click **General ledger** \> **Periodic** \> **India** \> **EXIM duty drawback**.

2.  In the **Duty drawback** form, in the **Port ID** field, select the port ID that is assigned to the shipping bills to process.

3.  In the **Product group** field, select the product group that includes the items for which you are applying for duty drawback.

4.  In the **Start date/time** field, select the start date and start time for the period that includes the shipping bills to process.

5.  In the **End date/time** field, select the end date and end time for the period that includes the shipping bills to process.

6.  In the **Transaction date/time** field, select the date and time to use to post the transaction in the ledger. This is the date that is assigned to the ledger transactions when they are generated.

7.  In the **Detail level** field, select **Details** or **Summary** to specify the summarization level for the shipping bills.

8.  Click **OK**.

**View the duty drawback transactions and post accounting entries**

1.  In the **Total duty drawback amount** form, view the following information.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Location in the form</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>The <strong>Total drawback amount allowed</strong> field</p></td>
    <td><p>The sum of the allowed drawback amounts for the specified date range. This amount is calculated based on the criteria that you select when you apply for duty drawback.</p></td>
    </tr>
    <tr class="even">
    <td><p>The <strong>Overview</strong> FastTab</p></td>
    <td><p>The shipping bill line details.</p></td>
    </tr>
    <tr class="odd">
    <td><p>The <strong>Drawback amount</strong> field</p></td>
    <td><p>The amount of the duty drawback.</p></td>
    </tr>
    <tr class="even">
    <td><p>The <strong>Allowed drawback</strong> field</p></td>
    <td><p>The amount of the duty drawback that is eligible to be claimed.</p>
    <p>For more information about how the allowed drawback amount is calculated, see <a href="ind-about-exim-duty-drawback-dbk-incentive-schemes.md">(IND) About EXIM duty drawback (DBK) incentive schemes</a>.</p></td>
    </tr>
    <tr class="odd">
    <td><p>The <strong>General</strong> FastTab</p></td>
    <td><p>Any updates to sales order fields and customer fields for the duty drawback transactions.</p></td>
    </tr>
    </tbody>
    </table>


2.  Click **Financial dimensions** to enter the financial dimensions for the account or offset account for each line item.

3.  Click **OK** to generate the accounting entries for the duty drawback transactions.

## See also

[(IND) Duty drawback (form)](https://technet.microsoft.com/en-us/library/jj664713\(v=ax.60\))

[(IND) Total Duty Drawback amount (form)](https://technet.microsoft.com/en-us/library/jj678025\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

