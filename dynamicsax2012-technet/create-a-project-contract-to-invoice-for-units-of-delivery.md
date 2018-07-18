---
title: Create a project contract to invoice for units of delivery
TOCTitle: Create a project contract to invoice for units of delivery
ms:assetid: 52131642-440e-4d30-8027-39452079e575
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh208944(v=AX.60)
ms:contentKeyID: 36057281
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- category
- billing rule
- unit
- unit of delivery
- unit of measure
- UOM
audience: Application User
ms.search.region: Global
---

# Create a project contract to invoice for units of delivery 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use these procedures to create a project and project contract, so that you can invoice a customer when you have completed a unit of delivery that is defined in the contract. The timing of the invoices is negotiated with the customer.

**Example**

Your organization offers to provide training for a customer’s products. The customer agrees to use your services for a total of five training sessions across the United States, at a cost of $10,000 per training session. Your organization bills the customer after each training session. In this example, the training session is the unit of delivery.

Use these procedures to set up a contract, an associated project, and the billing rules. The billing rules are used to calculate the amount that is included in invoices to the customer when the units of work that are specified in the project contract are delivered.

After you have created the contract and the project, you can set up the details of the project. For example, you can define the activities of the project and assign workers to the project.

## Prerequisites

Before you create a project that has billing rules, you must set up the following project information in the **Project management and accounting parameters** form:

  - Set up the number sequence that is used when you create a billing rule.

  - Set up a fee journal that is used by default to post invoices for a project contract that specifies units of delivery.

  - Set up any specific units of measure that are used when you create the billing rules. For example, create **Session** as a unit of measure.

## Create a contract for units of delivery

Use this procedure to create a project contract for a unit of delivery project.

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **Project contracts**.

2.  In the **Project contracts** form, on the **Action Pane**, on the **Project contract** tab, click **Project contract**.

3.  In the **New project contract** form, complete the following fields:
    
      - **Project contract ID**
    
      - **Name**
    
      - **Funding type**
    
      - **Funding source**
    
      - **Sales currency** – By default, this currency is used for customer invoices that are associated with the project contract. However, you can modify the sales currency for a specific customer invoice.
    
    Click **OK**. This information is copied to the header of the **Project contracts** form.

4.  In the **Project contracts** form, complete the rest of the required information for the contract. To change default values in the form, on the **Action Pane**, on the **Project contract** tab, click **Edit**.

## Create a project for units of delivery

Use this procedure to create a project and any subprojects that are associated with a contract.

1.  In the **Project contracts** form, on the **Action Pane**, on the **Project contract** tab, in the **New** group, click **Project**.

2.  In the **Create project** form, enter a project type of **Time and material**.

3.  Select a project group. A project group defines posting information for projects that are assigned to the group.

4.  Enter additional information about the project. For example, complete the following fields:
    
      - **Project ID**
    
      - **Project name**
    
      - **Project group**
    
      - **Project contract ID** – This field associates the project contract with the project.
        

        > [!NOTE]
        > <P>The <STRONG>Project contract ID</STRONG> field is automatically filled with the number of the project contract from the <STRONG>Project contracts</STRONG> form. However, you can change the project contract number.</P>

    
      - **Customer**

5.  After you have created the project, set the project stage to **In process**. For more information about how to set a project stage, see [Modify a project stage](modify-a-project-stage.md).

6.  Enter any additional information that is required, and then click **OK** to create the project.

## Create billing rules for units of delivery

After you have created the contract and the associated project, use this procedure to create the billing rules for the contract.

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **Project contracts**. Select a project contract.

2.  In the **Project contracts** form, on the **Project contract** tab, in the **Set up** group, click **Billing rule**.

3.  In the **Billing rules** form, click **New**.

4.  In the **Line type** field, select **Unit of delivery**.

5.  On the **Billing rule line details** FastTab, in the **Unit** field, select a unit of measure that is related to the project contract.

6.  In the **Quantity** field, enter the total number of units to deliver in the project contract.

7.  In the **Unit sales price** field, enter the price per unit. The total amount for the billing rule is automatically calculated.

8.  In the **Project** field, select the project or task that uses this billing rule.

9.  In the **Category** field, select a project category to assign to the fee transaction.

10. You can enter a percentage to calculate the amount that the customer withholds from payments on an invoice. On the **Payment retention terms** FastTab, select the funding source, and then, in the **Retention percentage** field, enter the retention percentage.

11. Repeat this procedure to create additional billing rules for the project contract.

## See also

[Create billing rules](create-billing-rules.md)

[Project contracts (form)](https://technet.microsoft.com/en-us/library/aa586038\(v=ax.60\))

[Projects (form)](https://technet.microsoft.com/en-us/library/aa585245\(v=ax.60\))

[Billing rules (form)](https://technet.microsoft.com/en-us/library/hh227642\(v=ax.60\))

[Project management and accounting parameters (form)](https://technet.microsoft.com/en-us/library/aa599440\(v=ax.60\))

[Units (form)](https://technet.microsoft.com/en-us/library/hh209233\(v=ax.60\))

  


