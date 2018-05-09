---
title: (IND) Set up general ledger parameters for the duty drawback (DBK) incentive scheme
TOCTitle: (IND) Set up general ledger parameters for the duty drawback (DBK) incentive scheme
ms:assetid: 8ed1c678-3a6a-4446-b8c4-9d9b01b54a9e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678032(v=AX.60)
ms:contentKeyID: 49385993
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- parameters
- general ledger parameters
- (IND)
- india
- incentive scheme
- DBK incentive scheme
---

# (IND) Set up general ledger parameters for the duty drawback (DBK) incentive scheme 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **General ledger parameters** form to activate the Export-Import (EXIM) incentive schemes. Then set up the duty drawback parameters for the Duty Drawback (DBK) incentive scheme. You can use the **Incentive scheme parameters** form to set up the duty drawback parameters.

1.  Click **General ledger** \> **Setup** \> **General ledger parameters**.

2.  In the **General ledger parameters** form, in the left pane, click **Sales tax**, and then select the **Activate incentive schemes** check box to activate EXIM incentive schemes.
    

    > [!NOTE]
    > <P>This check box is available only if you select the <STRONG>Customs</STRONG> check box in the <STRONG>Apply India taxes</STRONG> group in the <STRONG>Sales tax</STRONG> area in the <STRONG>General ledger parameters</STRONG> form.</P>



3.  Click **Incentive schemes**.

4.  In the **Incentive scheme parameters** form, in the left pane, click **DBK**, and then select the **Duty drawback** check box to activate the Duty Drawback incentive scheme.

5.  In the **Benefit account** field, select a ledger account to post the transactions for the duty drawback benefit to.

6.  In the **Receivable account** field, select a receivable ledger account to post the transactions to when you apply for the duty drawback.
    
    If you do not select a receivable account, the transactions are posted to the ledger account that is selected for the port authority that is specified in the **Customer account** field in the **EXIM ports** form.

7.  In the **Minimum pct. for duty drawback** and **Minimum amount for duty drawback** fields, enter the minimum percentage and minimum amount of the Free On Board (FOB) value that is required before you can apply for duty drawback.

8.  In the left pane, click **Number sequences**, and then select number sequence codes to use for references for the DBK voucher and the DBK internal ID references.

## See also

[(IND) About EXIM duty drawback (DBK) incentive schemes](ind-about-exim-duty-drawback-dbk-incentive-schemes.md)

[(IND) Incentive scheme parameters (form)](https://technet.microsoft.com/en-us/library/jj677946\(v=ax.60\))

[General ledger parameters (form)](https://technet.microsoft.com/en-us/library/aa557286\(v=ax.60\))

[(IND) General ledger parameters (modified form)](https://technet.microsoft.com/en-us/library/jj677901\(v=ax.60\))

[(IND) Incentive scheme parameters (form)](https://technet.microsoft.com/en-us/library/jj677946\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

