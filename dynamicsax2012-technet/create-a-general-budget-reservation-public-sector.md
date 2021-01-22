---
title: Create a general budget reservation (Public sector)
TOCTitle: Create a general budget reservation (Public sector)
ms:assetid: 375d1e32-5bbb-4738-ae3d-015a5a59c643
ms:mtpsurl: https://technet.microsoft.com/library/Dn792454(v=AX.60)
ms:contentKeyID: 65205496
author: Khairunj
ms.author: daxcpft
ms.date: 05/05/2015
mtps_version: v=AX.60
f1_keywords:
- public sector
- commitment
- Forms.BudgetControlConfiguration
- Forms.AssetGroup
- Forms.BudgetParameters
- Forms.JournalizingDefinitionTrans
- Forms.LedgerParameters
- Forms.JournalizingDefinition
- Forms.NumberSequenceTableListPage
- budget reservation
- Forms.BudgetReservationType_PSN
- Forms.BudgetReservationCreate_PSN
- Forms.BudgetReservationListPage_PSN
- Forms.BudgetReservationTable_PSN
- budget reservations
- general budget reservation
- general budget reservations
- new budget reservation
- new general budget reservation
audience: Application User
ms.search.region: Denmark, France
---

# Create a general budget reservation (Public sector) 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

After you set up your system to use general budget reservations, you can create reservation documents. For more information, see [Set up general budget reservation rules and reservation types (Public sector)](set-up-general-budget-reservation-rules-and-reservation-types-public-sector.md).


> [!NOTE]
> <P>General budget reservations are available only if the <STRONG>Public Sector</STRONG> configuration key is selected and if Microsoft Dynamics AX 2012 R3 Cumulative Update 8 is installed with the following hotfix: KB3047235</P>



General budget reservations are available to the documents required for the purchasing method you choose. These methods include purchase order, purchase requisition, and vendor invoice.

## Create a general budget reservation document

To create a general budget reservation, use the following steps.

1.  Click **Budgeting \> Common \> General budget reservations \> All general budget reservations**.

2.  On the **Action Pane**, in the **New** group, click **General budget reservation**.

3.  In the **Create a new general budget reservation** form, under **Transaction**, fill in the fields as necessary.

4.  Under **Reason**, enter a code and description of the reason for the reservation.

5.  Click **OK**.

6.  In the details form, fill in the fields as necessary in the **General budget reservation header**.

7.  Under **General budget reservation lines**, click **Add line**. Enter the information for the first line of your reservation. Repeat this step until you have entered all lines.
    

    > [!NOTE]
    > <P>In the <STRONG>Account</STRONG> column, select an account prefix code from the drop-down list, and then select a category.</P>



8.  Optional: If a purchase requisition applies to the budget reservation, on the **Line details** FastTab, you can select the purchase requisition line that the selected line in the budget reservation references. Items and services on the selected requisition line, including procurement category, are passed to the general budget reservation line. This is true for both procurement catalog items and non-catalog items.
    

    > [!NOTE]
    > <P>Any child amounts on a referenced purchase requisition, such as discounts, charges, or taxes, will not be reflected on the general budget reservation line.</P>



9.  Optional: If you use project accounting, on the **Line details** FastTab, click the **Project** tab, and then fill out the fields as necessary. For more information, see [Use project accounting with general budget reservations (Public sector)](use-project-accounting-with-general-budget-reservations-public-sector.md).

10. Optional: If you use project accounting, on the **Line details** FastTab, on the Action strip, click **Committed costs**. The **Committed costs** form opens, displaying the committed costs related to the selected line.

11. When you are finished filling out the various fields, on the **Action Pane**, in the **Post** group, click **Budget reservation**.

12. If you use workflow, a yellow bar appears at the top of the form. Click **Submit** to submit the general budget reservation to workflow. For more information, see [Submit a general budget reservation to workflow (Public sector)](submit-a-general-budget-reservation-to-workflow-public-sector.md).

13. Click **Close**.

## Reference a general budget reservation on a purchase order, purchase requisition, or vendor invoice

After you create the general budget reservation, open the appropriate source document that you want to refer to the budget reservation.

There are three main ways to consume or relieve a general budget reservation after it has been posted:

  - **Purchase order** - Reference the general budget reservation directly on a purchase order line. The reservation is relieved when the purchase order is confirmed. No purchase agreement is involved. To do this, create a purchase order according to your usual process. This might also involve using a purchase requisition. When you add a line to the purchase order, select the general budget reservation to use for the purchase order.

  - **Vendor invoice** - Reference the general budget reservation directly on a vendor invoice. You can assign a purchase agreement on the header of the invoice, but no purchase order is involved. The reservation is relieved when the invoice is posted. To do this, create a vendor invoice according to your usual process. When you add a line to the invoice, select the general budget reservation to use for the invoice.

  - **Purchase requisition** – Reference a general budget reservation line in a purchase requisition. The reservation is relieved when funds are released from the requisition. To do this, specify the purchase requisition on the budget reservation line when you create the reservation.
    

    > [!NOTE]
    > <P>Purchase requisitions require workflow. For more information, see <A href="overview-of-a-purchase-requisition-workflow.md">Overview of a purchase requisition workflow</A>. Also see <A href="set-up-general-budget-reservation-workflows-public-sector.md">Set up general budget reservation workflows (Public sector)</A>.</P>

    
    For more information about referencing general budget reservations in these documents, see the following topics:

<!-- end list -->

  - [Encumber a general budget reservation (Public sector)](encumber-a-general-budget-reservation-public-sector.md)

  - [Create a purchase order](create-a-purchase-order.md)

  - [Key tasks: Create and submit a purchase requisition](key-tasks-create-and-submit-a-purchase-requisition.md)

  - [Key tasks: Vendor invoices](key-tasks-vendor-invoices.md)

Use the following steps to reference a general budget reservation on a purchase order, purchase requisition, or vendor invoice.

1.  Do one of the following:
    
      - Click **Procurement and sourcing \> Common \> Purchase orders \> All purchase orders**
    
      - Click **Procurement and sourcing \> Common \> Purchase requisitions \> All purchase requisitions**.
    
      - Click **Accounts payable \> Common \> Vendor invoices \> Pending vendor invoices**.

2.  Create the document you want. You can also select a document and then, on the **Action Pane**, click **Edit**.

3.  Optional: Select specific lines.

4.  On the **Line details** FastTab, under **General budget reservation**, select a reservation number and line to apply to the document or selected lines. You can click **Advanced selection options** to search for more reservations.

## See also

[About general budget reservations (Public sector)](about-general-budget-reservations-public-sector.md)

[Set up general budget reservation rules and reservation types (Public sector)](set-up-general-budget-reservation-rules-and-reservation-types-public-sector.md)

[Create a purchase order](create-a-purchase-order.md)

[Key tasks: Create and submit a purchase requisition](key-tasks-create-and-submit-a-purchase-requisition.md)

[Key tasks: Vendor invoices](key-tasks-vendor-invoices.md)

[View, modify, delete, or cancel a general budget reservation (Public sector)](view-modify-delete-or-cancel-a-general-budget-reservation-public-sector.md)

[Set up Budgeting workflows](set-up-budgeting-workflows.md)

[Relieve a general budget reservation (Public sector)](relieve-a-general-budget-reservation-public-sector.md)

  


