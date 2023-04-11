---
title: Create a project contract to invoice for progress billings
TOCTitle: Create a project contract to invoice for progress billings
ms:assetid: ba3bc52c-c93b-432f-b871-73d10df89674
ms:mtpsurl: https://technet.microsoft.com/library/Hh242766(v=AX.60)
ms:contentKeyID: 36059124
author: tonyafehr
ms.date: 10/06/2014
mtps_version: v=AX.60
f1_keywords:
- project budget
- billing rule
- budget categories
- cost budget
- progress billing
- percentage of work complete
- percentage
audience: Application User
ms.search.region: Global
---

# Create a project contract to invoice for progress billings 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use these procedures to create a project and project contract, so that you can create invoices for the customer based on a percentage of work that is completed. The invoice amounts are automatically calculated for the budget categories of work that you set up for a project. The timing of invoices is set up when you negotiate the project contract with the customer.

**Example**

Your organization is a software development firm. You agree to develop a payroll accounting package for a customer for a total fee of $20,000. Your organization agrees to send an invoice to the customer as you complete specified percentages of work on the project. You set up project categories for the work to use in the billing process. You set up billing rules that automatically calculate the invoice amounts for the percentage of work that is completed for each category. The categories for the project include the following:

  - Consulting

  - Design

  - Installation

Your budget manager creates a budget for the project categories. The amount of completed work is automatically calculated as a percentage of actual work compared to the budgeted amounts.

Use these procedures to set up a contract, an associated project, and the billing rules to use to calculate invoice amounts for the budget categories of work that you set up for the project.

After you have created the contract and the project, you can set up the details of the project. For example, you can define the activities of the project and assign workers to the project.

## Prerequisites

Before you create a project with billing rules, you must set up the following project information in the **Project management and accounting parameters** form:

  - Set up the number sequence to use when you create a billing rule.

  - Set up a fee journal to use by default for posting progress billings.

## Create a contract for progress billings

Use this procedure to create a project contract for a Fixed-price project. You create a project invoice when the work completed on the project reaches a specified percentage.

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **Project contracts**. Open a project contract from the list.

2.  In the **Project contracts** form, on the **Action Pane**, on the **Project contract** tab, click **Project contract**.

3.  In the **New project contract** form, complete the following fields:
    
      - **Project contract ID**
    
      - **Name**
    
      - **Funding type**
    
      - **Funding source**
    
      - **Sales currency** – By default, this is the currency to use for customer invoices associated with the project contract. You can modify the sales currency in a specific customer invoice.
    
    Click **OK**. This information is copied to the header of the **Project contracts** form.

4.  In the **Project contracts** form, complete the rest of the necessary information for the project. To change default values in the form, on the **Action Pane**, on the **Project contract** tab, click **Edit**.

## Create a project for progress billings

Use this procedure to create a project and any subprojects associated with a contract.

1.  In the **Project contracts** form, on the **Action Pane**, on the **Project contract** tab, in the **New** group, click **Project**.

2.  In the **Create project** form, enter a project type of **Time and material**.

3.  Select a project group. A project group defines posting information for projects assigned to the group.

4.  Enter additional project information, such as the following:
    
      - Project ID
    
      - Project name
    
      - Project group
    
      - Project contract ID – This associates a project contract with the project.
        

        > [!NOTE]
        > <P>The <STRONG>Project contract ID</STRONG> field is automatically filled with the number of the project contract from the <STRONG>Project contracts</STRONG> form. You can change the project contract to a different contract number.</P>

    
      - Customer

5.  Enter any additional required information, and then click **OK** to create the project.

6.  After you have created the project, set the project stage to **In process**. For more information about how to set a project stage, see [Modify a project stage](modify-a-project-stage.md).

## Create a budget for a project

Use this procedure to create the budget categories for the estimated costs in a project. The budget categories are used to automatically calculate the amounts to invoice a customer for the percentage of work that is completed for each category.

1.  In the **Projects** form, on the **Action Pane**, on the **Plan** tab, in the **Budget** group, click **Project budget**.

2.  Create a budget for the project. In the **Project budget** form, enter an estimated cost for each category in the project. The budget categories are used to automatically calculate amounts to invoice the customer for the percentage of completed work for each category.

## Create billing rules for progress billings

After you have created the contract and the associated project, use this procedure to create the billing rules for the contract.

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **Project contracts**. Select a project contract.

2.  In the **Project contracts** form, on the **Project contract** tab, in the **Set up** group, click **Billing rule**.

3.  In the **Billing rules** form, click **New**.

4.  Select a line type of **Progress**.

5.  In the **Billing rule line details** section, in the **Contract value** field, enter the total value of the contract.

6.  In the **Project** field, select the project that uses this billing rule.

7.  In the **Category** field, select the category to post the fee transaction to.

8.  You can assign the billing rule to additional projects. On the **Project** FastTab, in the **Available projects** section, select a project, and then click **Add**. The project is displayed in the **Selected projects** section.

9.  You can enter a percentage to calculate the amount that the customer withholds from payments on an invoice. On the **Payment retention terms** FastTab, select the funding source, and then, in the **Retention percentage** field, enter the retention percentage.

10. Repeat this procedure to create additional billing rules for the project contract.

## See also

[Create billing rules](create-billing-rules.md)

[Project contracts (form)](https://technet.microsoft.com/library/aa586038\(v=ax.60\))

[Projects (form)](https://technet.microsoft.com/library/aa585245\(v=ax.60\))

[Billing rules (form)](https://technet.microsoft.com/library/hh227642\(v=ax.60\))

[Project management and accounting parameters (form)](https://technet.microsoft.com/library/aa599440\(v=ax.60\))

[Project budget (form)](https://technet.microsoft.com/library/hh227438\(v=ax.60\))

[Create and submit an original project budget](create-and-submit-an-original-project-budget.md)

  


