---
title: (RUS) Create a ledger journal of tax difference transactions
TOCTitle: (RUS) Create a ledger journal of tax difference transactions
ms:assetid: 51bb9b74-3888-4ee5-880d-b78134c2e1fd
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ911378(v=AX.60)
ms:contentKeyID: 52075382
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- ledger journal
- tax difference
---

# (RUS) Create a ledger journal of tax difference transactions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Transactions in the tax difference journal are based on the calculations in the **Calculation of temporary tax differences** and **Calculation of constant tax differences** registers.

The following criteria must be met before you can create a journal for tax difference transactions:

  - The tax register journal must be created for the period during which the amortization is performed.

  - The **Calculation of temporary tax differences** and **Calculation of constant tax differences** registers must be calculated and approved.

<!-- end list -->

1.  Click **General ledger** \> **Journals** \> **Tax register journal**.

2.  Click **Lines**, and then select the line that corresponds with the **Calculation of temporary tax differences** register.

3.  Click **Calculate current** to calculate the register.

4.  Select the line that corresponds with the **Calculation of constant tax differences** register, and then click **Calculate current** to calculate the register.

5.  Select the **Approved** check box for each line to approve the register calculation for.

6.  In the **Worker** field, select the name of the employee who approved the registers.

7.  Click **Ledger journal** \> **Tax differences**.

8.  Create a journal that contains journal lines that are based on the register data and the assigned grouping level.
    

    > [!NOTE]
    > <P>Click <STRONG>Lines</STRONG> to view the journal lines.</P>



9.  Click **Post** \> **Post** to post the transactions that have tax differences in the specified ledger accounts.

## See also

[(RUS) Tax register journal (form)](https://technet.microsoft.com/en-us/library/jj856114\(v=ax.60\))

[(RUS) Register journal lines (form)](https://technet.microsoft.com/en-us/library/jj839663\(v=ax.60\))

[(RUS) Journal header (modified form)](https://technet.microsoft.com/en-us/library/jj911370\(v=ax.60\))

[(RUS) General ledger parameters (modified form)](https://technet.microsoft.com/en-us/library/jj923603\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

