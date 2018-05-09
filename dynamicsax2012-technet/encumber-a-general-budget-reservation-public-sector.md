---
title: Encumber a general budget reservation (Public sector)
TOCTitle: Encumber a general budget reservation (Public sector)
ms:assetid: c3a1ba47-f3b1-4335-9445-ff492e2aca52
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn762315(v=AX.60)
ms:contentKeyID: 65205505
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- public sector
- encumbrance
- encumber
- budget reservation
- encumbrances
- budget reservations
- general budget reservation
- general budget reservations
---

# Encumber a general budget reservation (Public sector) 


If you are in the public sector, you can enable the encumbrance process for general budget reservations. This involves configuring the settings for budget control and commitment accounting. When you enable encumbrance processing, the pre-encumbrance and encumbrance processes for both the purchase requisition and purchase order are also enabled, which ensures that the correct relieving entries are created for the general budget reservation.


> [!NOTE]
> <P>General budget reservations are available only if the <STRONG>Public Sector</STRONG> configuration key is selected and if Microsoft Dynamics AX 2012 R3 Cumulative Update 8 is installed with the following hotfix: KB3047235</P>



When the encumbrance process has been enabled, the following two entries are created when you create a general budget reservation:

  - A budget source tracking entry is created to make sure that actual expenditures do not exceed the available budget.

  - A general ledger accounting entry is created to reflect the financial accounting impact.

You can specify that the general budget reservation can either precede or follow a purchase requisition. You will see the selection options for the purchase requisition and purchase order as either pre-selected or required on the various configuration forms.

## Enable encumbrance and pre-encumbrance processing

Budget control is often enabled when the encumbrance process is enabled. This is not required, but it can be useful if you use both encumbrances and budget control. For example, the **Purchase order year-end process** form is used to close general budget reservation encumbrances in the fiscal year that is ending and to re-encumber them in the new fiscal year. The process includes an option to carry forward budget amounts to a new fiscal year. This option cannot be used unless budget control is enabled. For more information, see [Carry forward general budget reservation information to a new fiscal year (Public sector)](carry-forward-general-budget-reservation-information-to-a-new-fiscal-year-public-sector.md), [Process purchase orders at year end](process-purchase-orders-at-year-end.md), and [Set up budget control](set-up-budget-control.md).

To enable encumbrance and pre-encumbrance processing, follow these steps.

1.  Click **Budget \> Setup \> Budget control \> Budget control configuration**.

2.  Click **Select source documents**, and then select the **General budget reservation** and **Enable budget control for line item on entry** check boxes.

3.  Close the form.

4.  Click **General ledger \> Setup \> General ledger parameters**.

5.  Click **Ledger**, and then click the **Accounting rules** FastTab.

6.  Select the **Use posting definitions** check box. Click **Yes** if you are asked to confirm the selection.
    

    > [!IMPORTANT]
    > <P>You should create and test all posting definitions before you select the <STRONG>Use posting definitions</STRONG> check box. When you select that check box, all posting definitions are active immediately. For more information, see <A href="https://technet.microsoft.com/en-us/library/hh227669(v=ax.60)">Test Posting Definition Wizard (form)</A>. Posting definitions can be used only for the transaction posting types that are shown in the <STRONG>Transaction posting definitions</STRONG> form. Transaction posting types that are not shown in this form always use posting profiles. For more information, see <A href="about-posting-definitions.md">About posting definitions</A>, <A href="https://technet.microsoft.com/en-us/library/hh227607(v=ax.60)">Posting definitions (form)</A>, and <A href="https://technet.microsoft.com/en-us/library/hh242550(v=ax.60)">Transaction posting definitions (form)</A>.</P>



7.  Select the **General budget reservations** check box. The **Purchase requisition** and **Purchase order** check boxes are automatically selected. You can also select the **Enable budget control for line item on entry** check box.

8.  Close the form.

## See also

[About general budget reservations (Public sector)](about-general-budget-reservations-public-sector.md)

[Use project accounting with general budget reservations (Public sector)](use-project-accounting-with-general-budget-reservations-public-sector.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

