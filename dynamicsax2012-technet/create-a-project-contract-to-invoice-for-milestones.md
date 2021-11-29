---
title: Create a project contract to invoice for milestones
TOCTitle: Create a project contract to invoice for milestones
ms:assetid: 7b8b3f7e-b779-4c5b-a709-c08c3d099102
ms:mtpsurl: https://technet.microsoft.com/library/Hh209265(v=AX.60)
ms:contentKeyID: 36058257
author: Khairunj
ms.date: 10/06/2014
mtps_version: v=AX.60
f1_keywords:
- billing rule
- time & material
- time and material
- milestone
- milestone billing
- prepayment journal
- project milestone
audience: Application User
ms.search.region: Global
---

# Create a project contract to invoice for milestones 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use these procedures to create a project and project contract to invoice the customer when a project milestone is reached. The milestones are defined when the contract is negotiated.

**Example**

Your organization offers to conduct market research on a consumer product that a customer plans to sell. The customer agrees to use your services for a period of three months, starting in March. Your organization bills the customer at the end of each milestone. The project has three milestones:

  - Milestone 1: Collect consumer data. The scheduled completion date is March 31.

  - Milestone 2: Analyze consumer data. The scheduled completion date is April 30.

  - Milestone 3: Present a product viability proposal. The scheduled completion date is May 31.

Use these procedures to set up a contract, an associated project, and the billing rules to use to invoice the customer at the end of each milestone.

After you have created the contract and the project, you can set up the details of the project. For example, you can define the activities of the project and assign workers to the project.

As a prerequisite to performing these procedures, a system administrator must set up the number sequence that you use when you create a billing rule.

## Create a contract for milestones

Use the following procedure to create a contract to invoice a customer upon completion of milestones.

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **Project contracts**. Open a project on the list page.

2.  In the **Project contracts** form, on the **Action Pane**, on the **Project contract** tab, click **Project contract**.

3.  In the **New project contract** form, enter the project contract number, the contract name, the funding type, the funding source, and the currency to use for customer invoices created for the project contract, and then click **OK**. This information is copied to the header of the **Project contracts** form.

4.  In the **Project contracts** form, complete the rest of the necessary information for the contract. To change default values in the form, on the **Action Pane**, on the **Project contract** tab, click **Edit**.

## Create the associated project for milestones

Use the following procedure to create a project and any subprojects associated with a contract for milestones.

1.  In the **Project contracts** form, on the **Action Pane**, on the **Project contract** tab, in the **New** group, click **Project**.

2.  In the **New project** form, enter a project type of **Time and material**.

3.  Select a project group.

4.  Enter additional project information, such as the following:
    
      - Project ID
    
      - Project name
    
      - Project group
    
      - Project contract ID – This associates a project contract with the project.
        

        > [!NOTE]
        > <P>The <STRONG>Project contract ID</STRONG> field is automatically filled with the number of the project contract from the <STRONG>Project contracts</STRONG> form. You can change the project contract to a different contract number.</P>

    
      - Customer

5.  Enter any additional required information, and then click **OK** to create the project.

6.  After you have created the project, set the project stage to **In process**.

## Create the milestones for the project

After you have created the projects, use the following procedure to add the milestones for the project.

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Select the Time and material project that you just created.

2.  Depending on your version of Microsoft Dynamics AX, do one of the following:
    
    1.  In Microsoft Dynamics AX 2012 R2, in the **Projects** form, on the **Action Pane**, on the **Manage** tab, in the **Bill** group, click **Invoice proposals**.
        
        In the **Invoice proposals** details form, select the invoice proposal, and then, on the **Action Pane**, click **Post**.
    
    2.  Otherwise, in the **Projects** form, on the **Action Pane**, on the **Manage** tab, in the **Bill** group, click **New on-account**.
        
        In the **Prepayment journal voucher** form, create an on-account transaction for each milestone. The transaction includes the amount to invoice the customer for each milestone.

## Create billing rules for the milestone contract

After you have created the contract and the associated project, use this procedure to create the billing rules for the contract.

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **Project contracts**. Select a project.

2.  In the **Project contracts** form, on the **Action Pane**, on the **Project contract** tab, click **Project contract**.

3.  In the **Project contracts** form, on the **Project contract** tab, in the **Set up** group, click **Billing rule**.

4.  In the **Billing rules** form, click **New**.

5.  Select a line type of **Milestone**.

6.  On the **Details** FastTab, move milestone transactions from the **Available items** section to the **Selected items** section.

7.  You can enter a percentage to calculate the amount that the customer withholds from payments on an invoice. On the **Payment retention terms** FastTab, select the funding source, and then, in **Retention percentage** field, enter the retention percentage.

## See also

[Create billing rules](create-billing-rules.md)

[Project contracts (form)](https://technet.microsoft.com/library/aa586038\(v=ax.60\))

[Projects (form)](https://technet.microsoft.com/library/aa585245\(v=ax.60\))

[Billing rules (form)](https://technet.microsoft.com/library/hh227642\(v=ax.60\))

[About project stages](about-project-stages.md)

[Project management and accounting parameters (form)](https://technet.microsoft.com/library/aa599440\(v=ax.60\))

  


