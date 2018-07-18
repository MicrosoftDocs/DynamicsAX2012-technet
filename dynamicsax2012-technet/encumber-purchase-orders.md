---
title: Encumber purchase orders
TOCTitle: Encumber purchase orders
ms:assetid: 79668209-8a70-4966-b4f5-eb98548b99eb
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh209259(v=AX.60)
ms:contentKeyID: 36058237
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- purchase order
- purchase orders
- encumbrances
- PO
- purchase order encumbrances
audience: Application User
ms.search.region: Global
---

# Encumber purchase orders 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can enable the encumbrance process for purchase orders. When you create and confirm purchase orders with this process enabled, a budget reservation is created to make sure that actual expenditures do not exceed the available budget. For more information, see [About purchase order encumbrances](about-purchase-order-encumbrances.md).

You can also enable the pre-encumbrance process that is used for purchase requisitions. When you enable the pre-encumbrance process, the encumbrance process is also automatically enabled. If both processes are enabled, you can create purchase requisitions that set aside budget funds when the purchase requisitions are approved. You can then create a purchase order from the approved purchase requisition lines. When the purchase order is approved, an encumbrance is created for the amount of the purchase order. The pre-encumbrance is also relieved for the related lines of the purchase requisitions. This avoids having a budget reservation be counted two times in the general ledger, as both a pre-encumbrance and an encumbrance.

If you are in the public sector and are using general budget reservations, see [Encumber a general budget reservation (Public sector)](encumber-a-general-budget-reservation-public-sector.md).


> [!NOTE]
> <P>General budget reservations are available only if the <STRONG>Public Sector</STRONG> configuration key is selected and if Microsoft Dynamics AX 2012 R3 Cumulative Update 8 is installed with the following hotfix: KB3047235</P>



For information about how to create a purchase order from a purchase requisition, see [Purchase requisition consolidation (form)](https://technet.microsoft.com/en-us/library/hh227441\(v=ax.60\)).


> [!NOTE]
> <P>(FRA) Budget control and the pre-encumbrance process must be enabled before you can create commitment documents. For more information, see <A href="fra-about-commitments-public-sector.md">(FRA) About commitments (Public sector)</A>.</P>



## Enable encumbrance and pre-encumbrance processing

Budget control is often enabled when the encumbrance process is enabled. This is not required, but it can be useful if you use both encumbrances and budget control. For example, the **Purchase order year-end process** form is used to close purchase order encumbrances in the fiscal year that is ending and re-encumber them in the new fiscal year. The process includes an option to carry forward budget amounts to a new fiscal year. This option cannot be used unless budget control is enabled. For more information, see [Process purchase orders at year end](process-purchase-orders-at-year-end.md) and [Set up budget control](set-up-budget-control.md).

1.  Click **Budgeting** \> **Setup** \> **Budget control** \> **Budget control configuration**.

2.  Click **Select source documents**, and then select the **Purchase orders** and **Enable budget control for line item on entry** check boxes.

3.  Close the form.

4.  Click **General ledger** \> **Setup** \> **General ledger parameters**.

5.  Click **Ledger**, and then click the **Accounting rules** FastTab.

6.  Select the **Use posting definitions** check box. Click **Yes** if you are asked to confirm the selection.
    

    > [!IMPORTANT]
    > <P>You should create and test all posting definitions before you select the <STRONG>Use posting definitions</STRONG> check box. When you select that check box, all posting definitions are active immediately. For more information, see <A href="https://technet.microsoft.com/en-us/library/hh227669(v=ax.60)">Test Posting Definition Wizard (form)</A>. Posting definitions can be used only for the transaction posting types that are shown in the <STRONG>Transaction posting definitions</STRONG> form. Transaction posting types that are not shown in this form always use posting profiles. For more information, see <A href="about-posting-definitions.md">About posting definitions</A>, <A href="https://technet.microsoft.com/en-us/library/hh227607(v=ax.60)">Posting definitions (form)</A>, and <A href="https://technet.microsoft.com/en-us/library/hh242550(v=ax.60)">Transaction posting definitions (form)</A>.</P>



7.  Select one or both of the following check boxes:
    
      - Select **Enable encumbrance process** to create encumbrances only.
        

        > [!NOTE]
        > <P>If you are using AX 2012 R3 CU8 with hotfix KB3047235, select <STRONG>Purchase orders</STRONG>.</P>

    
      - Select **Enable pre-encumbrance process** to create both pre-encumbrances and encumbrances. If you select this check box, the **Enable encumbrance process** check box is automatically selected.
        

        > [!NOTE]
        > <P>If you are using AX 2012 R3 CU8 with hotfix KB3047235, select <STRONG>Purchase requisitions</STRONG>. The <STRONG>Purchase orders</STRONG> check box will automatically be selected.</P>



8.  Close the form.

## See also

[Encumbrance summary (form)](https://technet.microsoft.com/en-us/library/hh209473\(v=ax.60\))

[Process purchase orders at year end](process-purchase-orders-at-year-end.md)

  


