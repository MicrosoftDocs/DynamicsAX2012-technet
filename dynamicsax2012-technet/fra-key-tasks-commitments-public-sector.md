---
title: '(FRA) Key tasks: Commitments (Public sector)'
TOCTitle: '(FRA) Key tasks: Commitments (Public sector)'
ms:assetid: 65456427-ebe1-40df-9c2b-82c3c6244263
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh208538(v=AX.60)
ms:contentKeyID: 36056291
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- commitments
- public sector
- commitment
- France
- French
---

# (FRA) Key tasks: Commitments (Public sector) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Commitments are budget control source documents used by public sector entities in France. Before using commitments, you should be familiar with the budgeting and budget control features that you will use.


> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed in the following hotfix for Microsoft Dynamics AX 2012 R3 Cumulative Update 8: KB3047235</P>Commitments are available only if the following conditions are met: 
> <UL>
> <LI>
> <P>The <STRONG>Public Sector</STRONG> configuration key is selected.</P>
> <LI>
> <P>The <STRONG>French regulatory</STRONG> configuration subkey is selected.</P>
> <LI>
> <P>In Microsoft Dynamics AX 2012 R3 Cumulative Update 8, the <STRONG>Commitments (France)</STRONG> regulatory document type is selected in the <STRONG>Budget parameters</STRONG> form, when the following hotfix is installed: KB3047235</P>
> <LI>
> <P>In cumulative update 7 for Microsoft Dynamics AX 2012, the <STRONG>Use French public sector accounting rules</STRONG> check box is selected in the <STRONG>Budget parameters</STRONG> form.</P></LI></UL>
> <P>In versions of Microsoft Dynamics AX 2012 prior to cumulative update 7, only the <STRONG>Public Sector</STRONG> configuration key must be selected, but the primary address of the legal entity must be in France.</P>



## What do you want to do?

Learn more about...

Set up budget control and related prerequisites

Create a commitment to reserve budget funds

Consume a commitment

Increase or decrease a commitment

Close commitments

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[(FRA) About commitments (Public sector)](fra-about-commitments-public-sector.md)

[Budgeting](budgeting.md)

[Configuring the workflow system](configuring-the-workflow-system.md)

## Set up budget control and related prerequisites

Before you can use commitments, commitment number sequences must be defined, budget control must be set up, and available budget amounts must exist.

1.  Set up number sequences for commitments. For more information, see [Number sequence overview](number-sequence-overview.md).

2.  (Optional) Set up workflow to manage the review process for commitments.
    
    With workflows enabled, a yellow information bar and a **Submit** button or an **Actions** menu appear at the top of the **Commitment** form. If you are the originator of the commitment, you might see a **Submit** button. If you are an approver of the commitment, you might see an **Actions** menu with options to approve or reject the commitment. For more information, see [Submit a document](submit-a-document.md) and [Workflow actions](workflow-actions.md).
    
    Some buttons in the **Commitment** form are not available when a commitment has been submitted for workflow approval.
    
    For more information, see [Set up Budgeting workflows](set-up-budgeting-workflows.md).

3.  Set up budget control following the procedures outlined in [Set up budget control](set-up-budget-control.md). The settings on the **Budget control configuration** form that are listed below are required for commitments. Settings not listed here can be selected according to the needs and practices of your organization.
    
      - In the **Budget funds available** section, select the following check boxes:
        
          - **Original budget**
        
          - **Actual expenditures**
        
          - **Budget reservations for encumbrances**
        
          - **Budget reservations for pre-encumbrances**
        
          - **Budget reservations for unconfirmed pre-encumbrances**
    
      - In the **Select source documents** section, select the **Commitments** check box.
        
        When you do this, the following check boxes will be selected or cleared automatically. You will not be able to change them as long as the **Commitments** check box is selected:
        
          - **Purchase requisitions** – Cleared
            
            You can create purchase requisitions, but you cannot use purchase requisitions to pre-encumber funds.
        
          - **Enable budget control for line item on entry** for purchase requisitions – Cleared
        
          - **Purchase orders** – Selected
        
          - **Enable budget control for line item on entry** for purchase orders – Selected
        
          - **Vendor invoices** – Selected
        
          - **Enable budget control for line item on entry** for vendor invoices – Selected
        
        In addition, although no action is required on your part, the check boxes in the **Commitment accounting** group in the **Ledger** section of the **General ledger parameters** form will be cleared and made unavailable. When you enable commitments, you cannot post budgetary transactions to the general ledger.
    
      - In the **Activate budget control** section, activate the budget control configuration and turn on budget control.

4.  Set up your budget and ensure that there are budget amounts available. For more information, see [Create budget register entries](create-budget-register-entries.md). If you use the apportionment budget type, also see [Create budget register entries (Public sector)](create-budget-register-entries-public-sector.md).

Back to top

## Create a commitment to reserve budget funds

1.  Click **Budgeting** \> **Common** \> **Commitments**. In the **Action Pane**, in the **New** group, click **Commitment**.

2.  The commitment opens in **Line view**. In the **Action Pane**, in the **Show** group, click **Header view**.

3.  In the **Name** field, enter a name that will identify this commitment.

4.  (Optional) In the **Vendor account** field, select the vendor for this commitment.

5.  In the **Action Pane**, in the **Show** group, click **Line view**.

6.  In the **Commitment lines** FastTab, click **Add line**. Enter the information for the first line of your commitment, including a purchase agreement line if the commitment is for a specific purchase agreement. Repeat this step until you have entered all lines.
    

    > [!NOTE]
    > <P>If workflows are enabled, additional controls are displayed at the top of the <STRONG>Commitment</STRONG> form when the first line is saved. You can continue to enter additional lines, but after you click <STRONG>Submit</STRONG> and the commitment is submitted to the workflow, you can no longer add or remove lines.</P>



7.  Click **Submit** on the yellow bar at the top of the commitment form to submit the commitment to workflow for approval. The budget reservation will be confirmed as part of the workflow process.
    
    \-or-
    
    If your organization does not use workflow, in the **Action Pane**, in the **Plan** group, click **Confirm budget reservation**.

8.  Close the form.

Back to top

## Consume a commitment

There are three ways to consume a commitment.

  - Assign a purchase agreement to a commitment line. The commitment is consumed when funds are released from the purchase agreement.
    
    To do this, specify the purchase agreement on the commitment line when you create the commitment.

  - Reference the commitment directly on a purchase order line. The commitment is consumed when the purchase order is confirmed. No purchase agreement is involved.
    
    To do this, create a purchase order according to your usual process. When you add a line to the purchase order, select the commitment to use for this purchase order.

  - Reference the commitment directly on a vendor invoice. There may be a purchase agreement assigned on the header of the invoice, but no purchase order is involved. The commitment is consumed when the invoice is posted.
    
    To do this, create a vendor invoice according to your usual process. When you add a line to the invoice, select the commitment to use for this invoice.

A commitment can be restricted to a specific vendor, or it can be available for assignment to any vendor. If the commitment is restricted to a specific vendor, it is available for selection only when the vendor invoice or purchase order specifies the same vendor.

Back to top

## Increase or decrease a commitment

It is sometimes necessary to change a confirmed commitment. For example, if severe weather results in higher-than-planned spending for snow removal and related services, you may need to increase a commitment.

1.  Click **Budgeting** \> **Common** \> **Commitments**. Double-click the commitment that you want to change.

2.  In the **Action Pane**, in the **Maintain** group, click **Revise**.

3.  Add, delete, or change commitment lines as necessary.
    
    When a commitment line has already been referenced by a purchase order or vendor invoice, your ability to delete or change lines may be limited.

4.  Click **Submit** on the yellow bar at the top of the commitment form to submit the commitment to workflow for approval. The budget reservation will be confirmed as part of the workflow process.
    
    \-or-
    
    If your organization does not use workflow, in the **Action Pane**, in the **Plan** group, click **Confirm budget reservation**.

5.  Close the form.

Back to top

## Close commitments

You can use the purchase order year-end process to close purchase order encumbrances at the end of a fiscal year and re-establish them at the start of a new fiscal year. When you do this, you can also create or update commitments in the new fiscal year. For more information, see [(FRA) Process purchase order encumbrances and commitments at year end (Public sector)](fra-process-purchase-order-encumbrances-and-commitments-at-year-end-public-sector.md).

You can also close a single commitment line directly on a commitment. See [(FRA) Commitment (form) (Public sector)](https://technet.microsoft.com/en-us/library/hh208609\(v=ax.60\)).

Back to top

## Find form help

[(FRA) Balance summary (form) (Public sector)](https://technet.microsoft.com/en-us/library/hh208551\(v=ax.60\))

[(FRA) Commitment (form) (Public sector)](https://technet.microsoft.com/en-us/library/hh208609\(v=ax.60\))

[(FRA) Commitment close (form) (Public sector)](https://technet.microsoft.com/en-us/library/hh208596\(v=ax.60\))

## Find related tasks

[(FRA) Process purchase order encumbrances and commitments at year end (Public sector)](fra-process-purchase-order-encumbrances-and-commitments-at-year-end-public-sector.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

