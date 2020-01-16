---
title: Process purchase orders at year end
TOCTitle: Process purchase orders at year end
ms:assetid: 8010f4a6-dcc1-40cb-b225-4bded6971d48
ms:mtpsurl: https://technet.microsoft.com/library/Hh209300(v=AX.60)
ms:contentKeyID: 36058338
author: Khairunj
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- purchase order
- purchase orders
- year-end close
- year end
- year-end
- PO
- end of the year
audience: Application User
ms.search.region: Global
---

# Process purchase orders at year end 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If you record encumbrances for purchase orders in the general ledger, which includes purchase orders for projects, you can generate closing entries to the general ledger and against budget reservations at the end of each fiscal year. At the start of the new fiscal year, you can create opening entries to correctly record the encumbrances and budget reservations. These entries help make sure that the reservations for purchase order encumbrances are correctly recorded on the year-end financial statements and in budget control.

For projects, the account that distributions are assigned to in the new fiscal year is the account that is defined in the **Purchase order year-end process** form in General ledger. It is not the account that is defined in the **Ledger posting setup** form in Project management and accounting.

If you are in the public sector and are using general budget reservations, see also [Finalize a general budget reservation (Public sector)](finalize-a-general-budget-reservation-public-sector.md) and [Carry forward general budget reservation information to a new fiscal year (Public sector)](carry-forward-general-budget-reservation-information-to-a-new-fiscal-year-public-sector.md).


> [!NOTE]
> <P>General budget reservations are available only if the <STRONG>Public Sector</STRONG> configuration key is selected and if Microsoft Dynamics AX 2012 R3 Cumulative Update 8 is installed with the following hotfix: KB3047235</P>



In the case of a partially invoiced purchase order, only the amount that has not been invoiced is closed and then reopened in the next fiscal year.

Closing purchase order encumbrances is a separate process from closing a fiscal year, and is usually performed before a fiscal year is closed. For information about closing a fiscal year, see [Fiscal year closing checklist](fiscal-year-closing-checklist.md).


> [!NOTE]
> <P>(FRA) French public sector entities can also create or update commitments in the new fiscal year. For more information, see <A href="fra-about-commitments-public-sector.md">(FRA) About commitments (Public sector)</A> and <A href="fra-process-purchase-order-encumbrances-and-commitments-at-year-end-public-sector.md">(FRA) Process purchase order encumbrances and commitments at year end (Public sector)</A>.</P>



## Prerequisites

Before you start this process, make sure that the following prerequisites have been set up.

## Enable budget control

Budget control is often enabled when encumbrances are created for purchase orders. You do not have to enable budget control to use this process, but budget register entries are not created unless you do. The **Process and carry forward budget** year-end option also cannot be used unless budget control is enabled. For more information, see [Set up budget control](set-up-budget-control.md).

## Enable the encumbrance process

The encumbrance process must be enabled before encumbrances for purchase orders can be recorded in the general ledger, and before you can run the purchase order year-end process successfully. For more information, see [Encumber purchase orders](encumber-purchase-orders.md).

## Set up posting definitions

Open the **Posting definitions** form to set up the following posting definitions in the **Purchasing** module, if they do not already exist:

  - **Purchase order year end** – This posting definition is used to reverse encumbrances and outstanding budget reservations for purchase orders in the fiscal year that is ending, and to generate year-end closing entries in the general ledger.

  - **Purchase order encumbrances** – This posting definition defines how encumbered amounts are recorded in the general ledger. It is also used in the new fiscal year to reverse year-end closing entries and to re-establish encumbrances in the general ledger.

For more information, see [Set up posting definitions](set-up-posting-definitions.md).

## Assign posting definitions to transaction posting types

Use the **Transaction posting definitions** form to assign posting definitions to the transaction posting definitions that correspond to them. You also select the criteria that originating transactions must meet for a specific posting definition to be used.

Select the following transaction posting types in the **Purchasing** module, and then follow the steps in [Assign posting definitions to transaction posting types](assign-posting-definitions-to-transaction-posting-types.md):

  - **Purchase order year-end close** – Select the posting definition that you created for purchase order year-end.

  - **Purchase order** – Select the posting definition that is used for purchase order encumbrances.

## Year-end processing options

Select one of the following year-end processing options to close purchase order encumbrances in the fiscal year that is ending and to re-encumber them in the new fiscal year.


> [!NOTE]
> <P>The year-end processing option that you select is used for encumbrances on all of the purchase orders that you select. If the <STRONG>Public Sector</STRONG> configuration key is selected, you can override this selection and substitute a different year-end processing option for specific funds that you select in the <STRONG>Funds</STRONG> form. For more information, see <A href="https://technet.microsoft.com/library/hh208514(v=ax.60)">Funds (form) (Public sector)</A>.</P>



<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Option</p></th>
<th><p>Closing and opening steps that occur for purchase order encumbrances</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Process and do not carry forward budget</strong></p></td>
<td><p><strong>Closing steps:</strong></p>
<ol>
<li><p>The remaining encumbrances in the general ledger and outstanding budget reservations for encumbrances are reversed.</p></li>
<li><p>Year-end closing entries are generated in the general ledger.</p></li>
</ol>
<p><strong>Opening steps:</strong></p>
<ol>
<li><p>Closing entries are reversed.</p></li>
<li><p>Encumbrances are re-established in the general ledger.</p></li>
<li><p>Budget reservations for encumbrances are created for the purchase orders that are being processed.</p></li>
</ol></td>
</tr>
<tr class="even">
<td><p><strong>Process and carry forward budget</strong></p></td>
<td><div class="alert">

> [!NOTE]
> <P>This option is available only if budget control has been enabled.</P>


</div>
<p><strong>Closing steps:</strong></p>
<ol>
<li><p>The remaining encumbrances in the general ledger and outstanding budget reservations for encumbrances are reversed.</p></li>
<li><p>Year-end closing entries are generated in the general ledger.</p></li>
<li><p>Budget adjustments are created to reduce the budget in the fiscal year that is being closed.</p></li>
</ol>
<p><strong>Opening steps:</strong></p>
<ol>
<li><p>Closing entries are reversed.</p></li>
<li><p>Encumbrances are re-established in the general ledger.</p></li>
<li><p>Budget reservations for encumbrances are created for the purchase orders that are being processed.</p></li>
<li><p>Budget adjustments are created in the new fiscal year to re-establish the budget register entries that were carried forward from the previous fiscal year.</p></li>
</ol></td>
</tr>
</tbody>
</table>


## Select purchase orders and run the purchase order year-end process

1.  Click **General ledger** \> **Periodic** \> **Fiscal year close** \> **Purchase order year-end process**.

2.  Click **Retrieve purchase orders** in the lower pane to select purchase orders for the year-end process. This opens a query form where you can select purchase orders by criteria such as the date, date range, vendor account, purchase order type, purchase order balance, or financial dimensions. For more information, see [Inquiry (form)](https://technet.microsoft.com/library/aa575929\(v=ax.60\)).

3.  Click **OK** in the **Inquiry** form.

4.  The results of the query are displayed in the lower pane of the **Purchase order year-end process** form. Select the **Include** check box for each purchase order to include in the year-end processing. Encumbrances for those purchase orders will be reversed in the fiscal year that is ending, and the encumbered amounts will be made available in the new fiscal year. You can click **Include all** to select all of the purchase orders in the list, or click **Exclude all** to clear the selections.
    

    > [!TIP]
    > <P>You can view the details of a purchase order by clicking <STRONG>View purchase order</STRONG>. You can also click <STRONG>View subledger journal</STRONG> to view the year-end closing and opening entries that will be generated for individual purchase orders.</P>



5.  In the **Year-end option** field, select how to process purchase order encumbrances.

6.  Select an original budget code, if you selected the **Process and carry forward budget** year-end option. This code is used for budget adjustments that are made in the closing fiscal year. The code that you select must not have a workflow selected, because the year-end processing would stop for workflow approvals. For more information, see [Budget codes (form)](https://technet.microsoft.com/library/hh209638\(v=ax.60\)).

7.  Select a carry forward budget code, if you selected the **Process and carry forward budget** year-end option. This code is used for budget adjustments that are made in the new fiscal year. The code that you select must not have a workflow selected, because the year-end processing would stop for workflow approvals. For more information, see [Budget codes (form)](https://technet.microsoft.com/library/hh209638\(v=ax.60\)).

8.  Verify the default values in the **Calendar** and **Fiscal year** fields, and make any changes. You can change the fiscal year value here, but you must use the **Ledger** form to change the selected fiscal calendar.
    
    You can click the calendar name to open the **Fiscal calendars** form, where you can view a description of the fiscal calendar, and the fiscal years that are included in the fiscal calendar.

9.  Verify the default values for the **Closing parameters** fields, and make any changes to the fields that can be changed.
    
      - The **Accounting date** field indicates the last day of the selected fiscal year. You cannot change this date.
    
      - The **Type** field is typically set to **Operating** for a period that can be used to record accounting transactions. You can select **Closing** if you are using a closing period to separate the closing entries. For information about how to create closing periods, see [Key tasks: Fiscal calendars, fiscal years, and periods](key-tasks-fiscal-calendars-fiscal-years-and-periods.md).
    
      - If you selected a type of **Closing**, select the closing period to use.

10. Verify the values for the **Opening parameters** fields. These fields cannot be changed.
    
      - The **Accounting date** field indicates the first day of the opening fiscal year.
    
      - The **Period** field indicates the first period that has a type of **Operating** in the opening fiscal year. This type of period is used to record accounting transactions.

11. Click **Process** when you are ready to run the purchase order year-end process.

12. If any messages are displayed, make the necessary corrections, and then run the process again for the affected purchase orders.
    

    > [!IMPORTANT]
    > <P>Verify the budget register entries that were created in the previous and current fiscal years to help ensure the accuracy of the year-end encumbrance closing process. You can view the budget register entries in the <STRONG>Budget register entries</STRONG> form.</P>



## See also

[Assign posting definitions to transaction posting types](assign-posting-definitions-to-transaction-posting-types.md)

[Encumber purchase orders](encumber-purchase-orders.md)

[Posting definitions (form)](https://technet.microsoft.com/library/hh227607\(v=ax.60\))

[Purchase order year-end process (form)](https://technet.microsoft.com/library/hh209522\(v=ax.60\))

[Set up posting definitions](set-up-posting-definitions.md)

[Subledger journal (form)](https://technet.microsoft.com/library/hh208685\(v=ax.60\))

[Transaction posting definitions (form)](https://technet.microsoft.com/library/hh242550\(v=ax.60\))

[Finalize a general budget reservation (Public sector)](finalize-a-general-budget-reservation-public-sector.md)

  


