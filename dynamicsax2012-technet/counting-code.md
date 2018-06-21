---
title: Counting code
TOCTitle: Counting code
ms:assetid: 73f9ee17-5a7f-41e4-a3c2-658b8c0a1157
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa586380(v=AX.60)
ms:contentKeyID: 36058150
ms.date: 03/20/2015
mtps_version: v=AX.60
---

# Counting code [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes the counting code options that are available when you are creating a counting group. Choose from **Manual**, **Period**, **Zero**, and **Minimum**.

  - **Manual** – Includes lines every time you run the job. In other words, you decide the counting interval for the counting group.
    

    > [!NOTE]
    > <P>When you create an on-hand or expired batch counting journal, and you select the <STRONG>Activate counting code</STRONG> option, any items that are associated with counting groups that use the <STRONG>Manual</STRONG> counting code will not be selected.</P>



  - **Period** – Includes lines for the period in the counting journal when the period interval has expired.
    
    Suppose that you specified a period of 14 days. Counting occurs on January 1, or 1/1, where lines are generated for the period. If the job is started on January 5 (1/5), 14 days have not passed, and no lines are generated in the journal for that period interval. If you start the job again on January 15 (1/15), lines are generated for the period in the journal, because 14 days have passed.

  - **Zero** – If on-hand inventory reaches zero (0), lines are generated in the counting journal when the job is run. If the on-hand inventory reaches 0 after a count, lines are generated the next time that you start the count.

  - **Minimum** – Inserts lines in the counting journal if the on-hand inventory is equal to or less than the minimum that is specified.

## See also

[Counting groups (form)](https://technet.microsoft.com/en-us/library/aa500813\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

