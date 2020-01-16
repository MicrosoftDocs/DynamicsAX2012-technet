---
title: Create a project contract to invoice for services plus management fees
TOCTitle: Create a project contract to invoice for services plus management fees
ms:assetid: 17ca1dee-54e5-4f11-b864-26c978027029
ms:mtpsurl: https://technet.microsoft.com/library/Hh242152(v=AX.60)
ms:contentKeyID: 36056089
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- category
- billing rule
- fee percentage
- management fee
- services plus a management fee
- time & material
- time and material
audience: Application User
ms.search.region: Global
---

# Create a project contract to invoice for services plus management fees 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use these procedures to create a project and project contract, so that you can invoice a customer for your services plus a management fee. The timing of the invoices is negotiated with the customer.

**Example**

Your organization is a management consulting firm that agrees to provide services to a retail company. The retail customer wants your organization to conduct market research to evaluate the viability of a new product. Your organization enters into an agreement with the customer to provide management consultants to conduct the research for the cost of time and materials. The customer agrees to pay 100.00 per hour for the consultants. The customer also agrees to pay an additional management fee of 10 percent for the consulting hours that are charged to the project.

Use these procedures to set up a contract, an associated project, and the billing rules. The billing rules are used to calculate the invoice amounts for the time and materials that are posted to the project, plus a management fee that equals 10 percent of the costs.

After you have created the contract and the project, you can set up the details of the project. For example, you can define the activities of the project and assign workers to the project.

## Prerequisites

Before you create a project that has billing rules, you must set up the following project information in the **Project management and accounting parameters** form:

  - Set up the number sequence that is used when you create a billing rule.

  - Set up a fee journal that is used by default to post invoices for projects.

## Create a contract for services plus a management fee

Use this procedure to create a project contract for services plus a management fee.

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **Project contracts**. Open a project contract from the list.

2.  In the **Project contracts** form, on the **Action Pane**, on the **Project contract** tab, click **Project contract**.

3.  In the **New project contract** form, complete the following fields:
    
      - **Project contract ID**
    
      - **Name**
    
      - **Funding type**
    
      - **Funding source**
    
      - **Sales currency** – By default, this currency is used for customer invoices that are associated with the project contract. However, you can modify the sales currency for a specific customer invoice.
    
    Click **OK**. This information is copied to the header of the **Project contracts** form.

4.  In the **Project contracts** form, complete the rest of the required information for the project. To change default values in the form, on the **Action Pane**, on the **Project contract** tab, click **Edit**.

## Create a project for services plus a management fee

Use this procedure to create a project and any subprojects that are associated with a contract.

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **Project contracts**. Select a project contract.

2.  In the **Project contracts** form, on the **Action Pane**, on the **Project contract** tab, in the **New** group, click **Project**.

3.  In the **New project** form, enter a project type of **Time and material**.

4.  Select a project group. A project group defines posting information for projects that are assigned to the group.

5.  Enter additional information about the project. For example, complete the following fields:
    
      - **Project ID**
    
      - **Project name**
    
      - **Project group**
    
      - **Project contract ID** – This field associates a project contract with the project.
        

        > [!NOTE]
        > <P>The <STRONG>Project contract ID</STRONG> field is automatically filled with the number of the project contract from the <STRONG>Project contracts</STRONG> form. However, you can change the project contract number.</P>

    
      - **Customer**

6.  Enter any additional information that is required, and then click **OK** to create the project.

7.  After you have created the project, set the project stage to **In process**. For more information about how to set a project stage, see [Modify a project stage](modify-a-project-stage.md).

## Create billing rules for a project that includes management fees

After you have created the contract and the associated project, use this procedure to create the billing rules for the project.

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **Project contracts**. Select a project contract.

2.  In the **Project contracts** form, on the **Project contract** tab, in the **Set up** group, click **Billing rule**.

3.  In the **Billing rules** form, click **New**.

4.  In the **Line type** field, select **Time and material**.

5.  You can assign the billing rule to additional projects. On the **Project** FastTab, in the **Available projects** section, select a project, and then click **Add**. The project is displayed in the **Selected projects** section.

6.  You can select categories to designate the transactions that are billed to the customer. On the **Project** FastTab, in the **Selected projects** section, select a project, and then click **Chargeable categories**.
    
    In the **Billing rules setup for project / category** form, select the categories to assign to the project. These categories are added to customer invoices.

7.  Set up the management fee. In the **Billing rules** form, click **New** to create another billing rule.

8.  In the **Line type** field, select **Fee**.

9.  On the **Billing rule line details** FastTab, select a project and a category for the billing rule.

10. In the **Fee percentage** field, enter the management fee percentage that is specified in the contract.

11. On the **Fee calculation rule** FastTab, in the **Available items** section, select the billing rule to which the management fee applies, and then click **Add** to move the item to the **Selected items** section.

12. If you want to enter a payment retention percentage for the billing rule, on the **Payment retention terms** FastTab, select a funding source. Then, in the **Retention percentage** field, enter a retention percentage.

## See also

[Create billing rules](create-billing-rules.md)

[Project contracts (form)](https://technet.microsoft.com/library/aa586038\(v=ax.60\))

[Projects (form)](https://technet.microsoft.com/library/aa585245\(v=ax.60\))

[Billing rules (form)](https://technet.microsoft.com/library/hh227642\(v=ax.60\))

[Project management and accounting parameters (form)](https://technet.microsoft.com/library/aa599440\(v=ax.60\))

[About project groups](about-project-groups.md)

  


