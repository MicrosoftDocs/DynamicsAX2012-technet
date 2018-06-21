---
title: (CHN) Setup for monthly closing (validity check)
TOCTitle: (CHN) Setup for monthly closing (validity check)
ms:assetid: 222e2346-fb36-4b07-ae6b-20cc639ab151
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664012(v=AX.60)
ms:contentKeyID: 49384596
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (CHN) Setup for monthly closing (validity check) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can open a fiscal period in the ledger calendar after it has been closed to make the necessary manual entries in the journals for the period.

You can run validation checks for the following checklist items that are displayed in the **Checklist items** field before ending or closing a fiscal period.

  - **Check if the previous month is closed**

  - **Check if all adjustments or settlements (includes: interest calculation, creation of collection letter, exchange adjustment, payment management jobs and inventory costing adjustment in all relevant modules) for this period are completed**

  - **Check if all journal vouchers for this period in general ledger are posted**

  - **Check if all journal vouchers for this period in relevant modules are posted**

  - **Recalculate the period balance and check whether the ledgers balance**

  - **Check if all profit and loss accounts for this period have a zero balance**

  - **Check if all batch posting routines for this period in accounts receivable and accounts payable are completed**

  - **Check if all bridging accounts or error accounts for this period have a zero balance**

  - **Data backup**


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Setup** \> **Periods** \> **Checklist setup**.
    

    > [!NOTE]
    > <P>This form is available only when you select the <STRONG>Extended monthly closing check</STRONG> check box on the <STRONG>Fiscal year close</STRONG> FastTab of the <STRONG>General ledger parameters</STRONG> form.</P>



2.  In the **Monthly stop** field, select one of the following validation checklist statuses for the monthly closing.
    
      - **No validation** – The current checklist is ignored during the validation process.
    
      - **Warning** – A message is displayed if the validation does not pass the current checklist condition. However, you can ignore the warning and continue the validation process.
    
      - **Stop** – A message is displayed and stops the validation process if the validation does not pass the current checklist condition.
    
      - In the **Monthly closing** field, select one of the following validation checklist statuses for monthly closing.
        
          - **No validation** – The current checklist is ignored during the validation process.
        
          - **Warning** – A message is displayed if the validation does not meet the requirements for the current checklist conditions. However, you can ignore the warning and continue the validation process.
        
          - **Stop** – A message is displayed and stops the validation process if the validation does not meet the requirements for the current checklist conditions.
    
    The status for the **Monthly closing** field cannot be set to **No validation** for the following checklist items:
    
      - **Check if the previous month is closed**
    
      - **Check if all journal vouchers for this period in general ledger are posted**
    
      - **Check if all journal vouchers for this period in relevant modules are posted**
    
      - **Recalculate the period balance and check whether the ledgers balance**

## See also

[(CHN) Validation checklist (form)](https://technet.microsoft.com/en-us/library/jj664060\(v=ax.60\))

[(CHN) General ledger parameters (modified form)](https://technet.microsoft.com/en-us/library/jj664137\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

