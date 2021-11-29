---
title: Create billing rules
TOCTitle: Create billing rules
ms:assetid: eb70b651-fd81-477d-b9c1-be881898a3af
ms:mtpsurl: https://technet.microsoft.com/library/Hh227487(v=AX.60)
ms:contentKeyID: 36059872
author: Khairunj
ms.date: 10/06/2014
mtps_version: v=AX.60
f1_keywords:
- project add-in
- funding source
- project invoice
- billing rules
- unit of delivery
- milestone
- customer retention
- project contracts
- billing milestones
- billing rule identification numbers
- time and material billing rules
- progress billing rules
- automatic invoice
audience: Application User
ms.search.region: Global
---

# Create billing rules 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic explains how to set up billing rules that are used to automatically calculate the timing and amount of customer invoices for a project. Billing rules are based on the project terms that are specified in the project contract. The billing rules that you can create depend on the terms of the project contract and the project type, such as Time and material or Fixed-price, that you associate with the billing rule.

You can create more than one billing rule for a project contract. You can also assign a billing rule to multiple projects that are associated with the same project contract and have similar billing terms.

You can create the following types of billing rules for customer invoices:

  - **Milestone** – Create an invoice for a specified amount when a milestone date is reached.

  - **Progress** – Create an invoice when a predetermined percentage of work is completed.

  - **Time and material** – Create an invoice for the value of hours and materials that were posted to a project.

  - **Fee** – Create a project invoice for administrative fees, such as a change order fee.

  - **Unit of delivery** – Create an invoice when a specified unit of delivery is completed for a project.

For **Time and material** and **Progress** billing rules, you can assign chargeable categories. Chargeable categories indicate the transactions that should be included in customer invoices.

For all types of billing rules, you can specify a retention percentage to deduct from a customer invoice until a project reaches an agreed-upon stage. The payment retention percentage is specified in the project contract. The amount is calculated on and subtracted from the total value of the lines in a customer invoice.

## Prerequisites

A system administrator must set up a number sequence, so that a billing rule identification number is automatically generated when you create a billing rule. For more information about how to set up number sequences, see [Project management and accounting parameters (form)](https://technet.microsoft.com/library/aa599440\(v=ax.60\)).

## Create a Milestone billing rule

Use the following procedure to create a billing rule for milestones. In the billing rule, select an amount to add to a customer invoice and the date on which the invoice is automatically created.

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **Project contracts**. In the **Project contracts** list, select a project contract, or create a new project contract.

2.  Depending on the version that you’re using, follow one of these steps:
    
      - In Microsoft Dynamics AX 2012 R3: In the **Project contracts** form, on the **Billing rules** FastTab, click **Add**.
    
      - In Microsoft Dynamics AX 2012 R2: In the **Project contracts** form, on the **Action Pane**, on the **Project contract** tab, in the **Set up** group, click **Billing rule**.

3.  In the **Billing rules** form, click **New**, and then, in the **Line type** field, select **Milestone**.

4.  Depending on the version that you’re using, follow one of these steps:
    
      - In AX 2012 R3: On the **Milestone** FastTab, click **New**, and then, in the **Project date** field, enter a date on which to create an invoice. By default, the current date is automatically entered.
    
      - In AX 2012 R2: Create the milestones for the project by using the **On-account transactions** form. Then, in the **Billing rules** form, on the **Milestone** FastTab, select the milestones to apply the billing rule to.

5.  In the **Project ID** field, select the Fixed-price project to apply the milestone to.

6.  In the **Sales currency** field, select the currency to use in an invoice for the milestone. By default, the currency is copied from the project contract for the project that you selected in the **Project ID** field.

7.  In the **Sales price** field, enter an amount to bill a customer when the milestone date is reached.

8.  Optional: If an amount must be retained from payments that are paid by funding sources, you can specify the percentage to retain for each funding source. On the **Payment retention terms** FastTab, in the **Retention percentage** field, enter the percentage of the invoice amount that the funding source should retain from payments on project invoices until the retention terms are met.

## Create a Progress billing rule

Use the following procedure to create a billing rule to invoice a customer when progress on a project reaches a certain completed percentage.

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **Project contracts**. In the **Project contracts** list, select a project contract, or create a new project contract.

2.  Depending on the version that you’re using, follow one of these steps:
    
      - In AX 2012 R3: In the **Project contracts** form, on the **Billing rules** FastTab, click **Add**.
    
      - In AX 2012 R2: In the **Project contracts** form, on the **Action Pane**, on the **Project contract** tab, in the **Set up** group, click **Billing rule**.

3.  In the **Billing rules** form, click **New**, and then, in the **Line type** field, select **Progress**.

4.  On the **Billing rule line details** FastTab, in the **Contract value** field, enter the amount of the project contract that the billing rule applies to. For example, the total value of a project contract is 100,000, and 80,000 of this amount will be invoiced in increments of 25 percent. The remaining 20,000 is due when the project is concluded. The contract value for this progress billing rule is 80,000.

5.  If there is a change order for a modification to the original project contract, in the **Change order number** field, enter the change order number.

6.  In the **Project** field, select a project to apply the billing rule to. If a project contract is associated with multiple projects, you can select some or all of the projects to apply the billing rule to.

7.  In the **Category** field, select a project category to use to post progress invoices that are created from the billing rule.

8.  In the **Sales tax group** field, select the sales tax group to use to compute the tax amount on an invoice that is created from the billing rule. By default, the sales tax group from the project contract is displayed.

9.  On the **Project** FastTab, in the **Available projects** pane, select a project to apply the billing rule to. If a project contract is associated with multiple projects, you can select one or more of the projects. Click **Add** to move a project to the **Selected projects** pane.

10. To select project categories for the billing rule, click **Chargeable categories**. In the **Billing rules setup for project / category** form, you can select one or more chargeable categories for the selected project. When you assign a chargeable category to a billing rule, the project transactions that use the chargeable category can be included in a customer invoice that is created from the billing rule.

11. Optional: If an amount must be retained from payments that are paid by funding sources, you can specify the percentage to retain for each funding source. On the **Payment retention terms** FastTab, in the **Retention percentage** field, enter a percentage of the invoice amount that the funding source will retain from payments on project invoices until the retention terms are met.

## Create a Time and material billing rule

Use the following procedure to create a billing rule to invoice a customer for hours, items, and expenses that are posted to a project.

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **Project contracts**. In the **Project contracts** list, select a project contract, or create a new project contract.

2.  Depending on the version that you’re using, follow one of these steps:
    
      - In AX 2012 R3: In the **Project contracts** form, on the **Billing rules** FastTab, click **Add**.
    
      - In AX 2012 R2: In the **Project contracts** form, on the **Action Pane**, on the **Project contract** tab, in the **Set up** group, click **Billing rule**.

3.  In the **Billing rules** form, click **New**, and then, in the **Line type** field, select **Time and material**.

4.  If there is a change order for a modification to the original project contract, on the **Billing rule line details** FastTab, in the **Change order number** field, enter the change order number.

5.  To include indirect costs, such as allocated overhead costs, in the calculation of the amount to bill a customer, select the **Include indirect costs** check box. For more information, see [About indirect costs for projects](about-indirect-costs-for-projects.md).

6.  On the **Project** FastTab, in the **Available projects** pane, select a project to apply the billing rule to. If a project contract is associated with multiple projects, you can select one or more of the projects. Click **Add** to move a project to the **Selected projects** pane.

7.  To select project categories for a billing rule, click **Chargeable categories**. In the **Billing rules setup for project / category** form, you can select one or more chargeable categories to assign to the project. When you assign a chargeable category to a billing rule, the project transactions that use the chargeable category can be included in a customer invoice that is created from the billing rule.

8.  Optional: If an amount must be retained from payments that are paid by funding sources, you can specify the percentage to retain for each funding source. On the **Payment retention terms** FastTab, in the **Retention percentage** field, enter a percentage of the invoice amount that the funding source will retain from payments on project invoices until the retention terms are met.

## Create a Fee billing rule

Use the following procedure to create a billing rule to invoice a customer for fees. For example, you can add a management fee to a project and then invoice the customer for the fees as work on the project is completed.

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **Project contracts**. In the **Project contracts** list, select a project contract, or create a new project contract.

2.  Depending on the version that you’re using, follow one of these steps:
    
      - In AX 2012 R3: In the **Project contracts** form, on the **Billing rules** FastTab, click **Add**.
    
      - In AX 2012 R2: In the **Project contracts** form, on the **Action Pane**, on the **Project contract** tab, in the **Set up** group, click **Billing rule**.

3.  In the **Billing rules** form, click **New**, and then, in the **Line type** field, select **Fee**.

4.  If there is a change order for a modification to the original project contract, on the **Billing rule line details** FastTab, in the **Change order number** field, enter the change order number.

5.  In the **Project** field, select a project to apply the billing rule to. If a project contract is associated with multiple projects, you can select some or all of the projects to apply the billing rule to.

6.  In the **Category** field, select a project category to use to post progress invoices that are created from the billing rule.

7.  In the **Fee percentage** field, enter a percentage of the total amount of a contract sales amount to add to an invoice that is created from the billing rule.

8.  In the **Sales tax group** field, select the sales tax group to use to compute the tax amount on an invoice that is created from the billing rule. By default, the sales tax group from the project contract is displayed.

9.  On the **Fee calculation rule** FastTab, select the billing rule types to apply the fee percentage to. Only billing rule types for the current project contract are displayed. In the **Available items** pane, select a billing rule type, and then click **Add**.

10. Optional: If an amount must be retained from payments that are paid by funding sources, you can specify the percentage to retain for each funding source. On the **Payment retention terms** FastTab, in the **Retention percentage** field, enter a percentage of the invoice amount that the funding source will retain from payments on project invoices until the retention terms are met.

## Create a Unit of delivery billing rule

Use the following procedure to create a billing rule to invoice a customer for delivery of a predefined unit of a project. For example, a company agrees to deliver four training seminars to a customer’s employees. The customer agrees to pay the company when each seminar is concluded. A seminar is considered the unit of delivery.

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **Project contracts**. In the **Project contracts** list, select a project contract, or create a new project contract.

2.  Depending on the version that you’re using, follow one of these steps:
    
      - In AX 2012 R3: In the **Project contracts** form, on the **Billing rules** FastTab, click **Add**.
    
      - In AX 2012 R2: In the **Project contracts** form, on the **Action Pane**, on the **Project contract** tab, in the **Set up** group, click **Billing rule**.

3.  In the **Billing rules** form, click **New**, and then, in the **Line type** field, select **Unit of delivery**.

4.  On the **Billing rule line details** FastTab, in the **Unit** field, select a unit of measure for the billing rule. A unit of measure can be a count, size, volume, or weight.

5.  In the **Quantity** field, enter the number of units to deliver. In the seminar example, the quantity is 4.

6.  In the **Unit sales price**, enter the sales value of each unit that is delivered.

7.  If there is a change order for a modification to the original project contract, in the **Change order number** field, enter the change order number.

8.  In the **Project** field, select a project to apply the billing rule to. If a project contract is associated with multiple projects, you can select some or all of the projects to apply the billing rule to.

9.  In the **Category** field, select a project category to use to post progress invoices that are created from the billing rule.

10. In the **Sales tax group** field, select the sales tax group to use to compute the tax amount on an invoice that is created from the billing rule. By default, the sales tax group from the project contract is displayed.

11. Optional: If an amount must be retained from payments that are paid by funding sources, you can specify the percentage to retain for each funding source. On the **Payment retention terms** FastTab, in the **Retention percentage** field, enter a percentage of the invoice amount that the funding source will retain from payments on project invoices until the retention terms are met.

## See also

[About billing rules](about-billing-rules.md)

[Billing rules (form)](https://technet.microsoft.com/library/hh227642\(v=ax.60\))

[On-account transactions (form)](https://technet.microsoft.com/library/aa557380\(v=ax.60\))

  


