---
title: '(FRA) Key tasks: Administer purchase agreements (Public sector)'
TOCTitle: '(FRA) Key tasks: Administer purchase agreements (Public sector)'
ms:assetid: c1d8201d-73bc-47ef-a2ab-9a9a002dc37e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh208575(v=AX.60)
ms:contentKeyID: 36056359
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- public sector
- France
- French
- purchase agreement
- purchase agreements
---

# (FRA) Key tasks: Administer purchase agreements (Public sector) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The standard processes related to purchase agreements are augmented for French entities in the public sector.


> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed in the following hotfix for Microsoft Dynamics AX 2012 R3 Cumulative Update 8: KB3047235</P>



These additional capabilities, which include the ability to create tranches and lots, are used to help meet the requirements of the Code des Marchés Publics. They are available only if the following conditions are met:

  - The **Public Sector** configuration key is selected.

  - The **French regulatory** configuration subkey is selected.

  - In Microsoft Dynamics AX 2012 R3 Cumulative Update 8, the **Commitments (France)** regulatory document type is selected in the **Budget parameters** form, when the following hotfix is installed: KB3047235

  - In cumulative update 7 for Microsoft Dynamics AX 2012, the **Use French public sector accounting rules** check box is selected in the **Budget parameters** form.

In versions of Microsoft Dynamics AX 2012 prior to cumulative update 7, only the **Public Sector** configuration key must be selected, but the primary address of the legal entity must be in France.

## What do you want to do?

Learn more about...

Set up purchase agreement classifications

Control access to purchase agreements

Create tranches and lots

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About purchase agreements](about-purchase-agreements.md)

## Set up purchase agreement classifications

To use administrative fields on purchase agreements, you must first create a purchase agreement classification that includes the necessary fields.

1.  Click **Procurement and sourcing** \> **Setup** \> **Purchase agreements** \> **Purchase agreement classification**.

2.  Click **New**. Enter a **Name** and **Description** for the new purchase agreement classification.

3.  Select the check boxes for the administrative information that you want to include on purchase agreements that use this classification.
    
      - To include information about subcontractors, select the **Subcontractors** check box.
        
        Purchase agreements can have a prime contractor, co-contractors, and subcontractors. It is possible to assign the prime contractor to the parent purchase agreement, and a co-contractor or subcontractor to specific child agreements.
    
      - To include information about certifications for vendors, select the **Certifications** check box. Certification information can be used to generate a report that lets you monitor vendor compliance with certification requirements.
    
      - To include information about milestones and tasks, select the **Activities** check box.

4.  To require direct invoicing and to prevent someone from using release orders, select the **Require direct invoicing** check box.

5.  Repeat steps 2, 3, and 4 to create additional purchase agreement classifications.

6.  When you are finished, close the form.

When you create purchase agreements, assign a purchase agreement classification that lets you include all necessary information.

Back to top

## Control access to purchase agreements

You can make sure that only approved departments can access a purchase agreement, and you can limit the amount that each department can spend against the purchase agreement. If a user tries to exceed the maximum amount allocated for a department, they will receive a message and be prevented from confirming the release or processing the invoice.

### Set up the account structure and financial dimensions for department access

1.  Click **Accounts payable** \> **Setup** \> **Accounts payable parameters**.

2.  In the **General** area, enter the following information:
    
      - In the **Account structure** field, select the account structure to use on the **Purchase agreement department access** form to control access to purchase agreements. The account structure must include the financial dimension segment by which you control access to purchase agreements.
        
        For more information about account structures, see [About the Configure account structures form](about-the-configure-account-structures-form.md).
    
      - In the **Financial dimension** field, select the financial dimension by which you control access to purchase agreements. Most often, this will be department, but some organizations may restrict access to purchase agreements to different entities within their organizations.

3.  Close the form.

### Set up access to a purchase agreement

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **Purchase agreements**.
    
    \-or-
    
    Click **Accounts payable** \> **Common** \> **Purchase orders** \> **Purchase agreements**.

2.  Select the purchase agreement you want to control access to. In the **Action Pane**, in the **Maintain** group, click **Department access**.

3.  Click **New**. In the **Purchase agreement department access** field, select a department that is authorized to use this purchase agreement. In the **Authorized amount** field, enter the total amount that this department is authorized to release from this purchase agreement.

4.  Repeat step 3 until all authorized departments have been added to the purchase agreement.

5.  Close the form.

Back to top

## Create tranches and lots

You can create a hierarchy of parent and child purchase agreements. The child purchase agreements serve as the tranches and lots of the parent purchase agreement.

The purchase agreement hierarchy has some specific characteristics:

  - A user can view the parent purchase agreement and see the total activity of the parent and all its related child agreements. This provides a single management view for reviewing and controlling activity on purchase agreements.

  - Some values from the parent purchase agreement are automatically transferred to the child agreements. For example, policies related to competitive advertising can be assigned to the parent purchase agreement. Those policies would then apply to all the child agreements related to that parent.

  - Purchase agreements can have a prime contractor, co-contractors, and subcontractors. It is possible to assign the prime contractor to the parent purchase agreement, and a co-contractor or subcontractor to specific child agreements.


> [!NOTE]
> <P>If you have added lines to a purchase agreement, that purchase agreement cannot be used as a parent agreement. The <STRONG>Create child agreement</STRONG> button will no longer be available. In the same way, if you have created a child purchase agreement, you cannot add lines to the parent purchase agreement.</P>



1.  Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **Purchase agreements**.
    
    \-or-
    
    Click **Accounts payable** \> **Common** \> **Purchase orders** \> **Purchase agreements**.

2.  Select the purchase agreement that will be the parent. In the **Action Pane**, in the **Maintain** group, click **Create child agreement**, and then select the vendor to use on the child purchase agreement.

3.  Verify that the information that was automatically filled in based on the parent purchase agreement is correct for this child agreement.
    
      - If budget funds have been committed for the parent agreement but not for the child agreement, remove the commitment number from the child agreement.

4.  Repeat steps 2 and 3 until you have created all the child purchase agreements that you require.

5.  Close the form.

To see the relationships among parent and child purchase agreements, use the **Purchase agreement tree** form.

Back to top

## Find form help

[Purchase agreements (form)](https://technet.microsoft.com/en-us/library/hh209550\(v=ax.60\))

[(FRA) Purchase agreement department access (form) (Public sector)](https://technet.microsoft.com/en-us/library/hh208584\(v=ax.60\))

[(FRA) Purchase agreement tree (form) (Public sector)](https://technet.microsoft.com/en-us/library/hh208545\(v=ax.60\))

[Accounts payable parameters (form)](https://technet.microsoft.com/en-us/library/aa596348\(v=ax.60\))

## Find related tasks

[Set up purchase or sales agreement functionality](set-up-purchase-or-sales-agreement-functionality.md)

[View history of confirmed purchase agreements](view-history-of-confirmed-purchase-agreements.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

