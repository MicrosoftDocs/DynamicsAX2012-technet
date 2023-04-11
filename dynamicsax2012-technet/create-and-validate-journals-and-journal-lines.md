---
title: Create and validate journals and journal lines
TOCTitle: Create and validate journals and journal lines
ms:assetid: f251e5ca-2419-4a39-bc42-cb11a2d87da5
ms:mtpsurl: https://technet.microsoft.com/library/Aa551623(v=AX.60)
ms:contentKeyID: 36059961
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- create general journals
- create journal lines
- validate journal
- journal lines
- journal voucher
- general journals
audience: Application User
ms.search.region: Global
---

# Create and validate journals and journal lines 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use journal forms to create and validate journals and journal lines. You can then post the lines in the **Journal voucher** form or in the **Journal** form.

1.  Open the journal in which to create journal lines.
    
    For example, open the general journal. (Click **General ledger** \> **Journals** \> **General journal**.)

2.  Click **New** to create a line.

3.  Select a journal name in the **Name** field.

4.  Enter information in other fields as appropriate. Default field information from the **Journal names** form is displayed.

5.  Click **Lines** to open the **Journal voucher** form. Some of the fields might display default values from the **Journal** form.
    

    > [!IMPORTANT]
    > <P>If budget control is turned on and the appropriate source documents and journals are enabled for budget control, the <STRONG>Journal voucher</STRONG> form can display a budget check icon. A red X indicates that the budget check failed, a yellow triangle indicates that the budget check passed with warnings, and a green check mark indicates that the budget check passed. Budget check results can be affected by project budget control settings, over budget permissions, and other budget control parameters and settings. For more information, see <A href="about-budget-control.md">About budget control</A>.</P>



6.  In the first line on the **Overview** tab, enter values in the relevant fields, such as the following fields. The fields that are available vary, depending on which journal you are using.
    
      - **Account type**
    
      - **Account**
    
      - **Description**
    
      - **Debit** or **Credit**, as appropriate
    
      - **Offset account type**
    
      - **Offset account** (You can use two or more lines to specify more than one offset account for the same voucher)

7.  Click **New** to create another line, and then enter information about the next voucher.

8.  After you enter all the lines, click **Validate**, and select to validate that all the lines or the selected lines are ready for posting. For example, in the general journal **Journal voucher** form, you can select **Validate the general journal** or **Validates the current voucher**.
    
    You can also validate all the lines in the journal in the **Journal** form.

## See also

[Approve a journal](approve-a-journal.md)

[Post and print a journal or journal lines](post-and-print-a-journal-or-journal-lines.md)

[Journal names setup (form)](https://technet.microsoft.com/library/aa552517\(v=ax.60\))

[About migrating project data from other ERP systems](about-migrating-project-data-from-other-erp-systems.md)

[Migrating project data from other ERP systems](migrating-project-data-from-other-erp-systems.md)

[Create a project beginning balance](create-a-project-beginning-balance.md)

  


