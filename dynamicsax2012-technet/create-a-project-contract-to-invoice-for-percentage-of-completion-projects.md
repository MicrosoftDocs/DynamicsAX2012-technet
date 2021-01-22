---
title: Create a project contract to invoice for percentage-of-completion projects
TOCTitle: Create a project contract to invoice for percentage-of-completion projects
ms:assetid: aad681d2-f7d7-40e4-bd16-1704c0a2c1fe
ms:mtpsurl: https://technet.microsoft.com/library/Hh242694(v=AX.60)
ms:contentKeyID: 36058906
author: Khairunj
ms.author: daxcpft
ms.date: 10/06/2014
mtps_version: v=AX.60
f1_keywords:
- billing rule
- time & material
- time and material
- percent of completion
- percentage of completion
audience: Application User
ms.search.region: Global
---

# Create a project contract to invoice for percentage-of-completion projects 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use these procedures to create a project contract, the related project, and billing rules for a percentage-of-completion project. In a percentage-of-completion project, you create customer invoices when you have completed a specified percentage of a project. You and the customer define the percentages for a percentage-of-completion project in the project contract. You can also specify the timing of the invoices by setting up billing rules for the contract.

**Example**

Your organization is a software consulting firm. You agree to develop part of a product for your customer, a software development company. Your organization agrees to deliver the software code for the product over a period of six months. The customer agrees to pay your organization a total of 100,000 for the deliverables, in increments of 25 percent of the contract. You agree to send an invoice for 25,000 to the customer when each 25-percent increment is completed.

**Prerequisites**

Before you create a contract for a percentage-of-completion project, you must set up following project information in the **Project management and accounting parameters** form:

  - In the **Number sequences** area, set up a number sequence for billing rules.

  - In the **Journals** area, set up a fee journal that is used by default to post billing rules.

## Create a percentage-of-completion contract

Use this procedure to create a project contract that has percentage-of-completion terms.

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **Project contracts**.

2.  On the **Project contracts** list page, on the **Action Pane**, click **Project contract**.

3.  In the **New project contract** form, complete the following fields:
    
      - **Project contract ID**
    
      - **Name**
    
      - **Funding type**
    
      - **Funding source**
    
      - **Sales currency** – By default, this currency is used for customer invoices that are associated with the project contract. However, you can modify the sales currency for a specific customer invoice.
    
    Click **OK**. This information is copied to the header of the **Project contracts** form.

4.  In the **Project contracts** form, complete the rest of the required information for the project. To change default values in the form, on the **Action Pane**, on the **Project contract** tab, click **Edit**.

## Create a project for a percentage-of-completion contract

Use this procedure to create a project and any subprojects that are associated with a contract.

1.  In the **Project contracts** form, on the **Project contract** tab, in the **New** group, click **Project**.

2.  In the **Create project** form, select a project type of **Fixed-price**.

3.  Select a project group. A project group defines posting information for projects that are assigned to the group.

4.  Enter additional information about the project. For example, complete the following fields:
    
      - **Project ID**
    
      - **Project name**
    
      - **Project group**
    
      - **Project contract ID** – This field associates a project contract with the project.
        

        > [!NOTE]
        > <P>The <STRONG>Project contract ID</STRONG> field is automatically filled with the number of the project contract from the <STRONG>Project contracts</STRONG> form. However, you can change the project contract number.</P>

    
      - **Customer**

5.  Enter any additional information that is required, and then click **OK** to create the project.

6.  After you have created the project, set the project stage to **In process**. For more information about how to set a project stage, see [Modify a project stage](modify-a-project-stage.md).

## Create billing rules for a percentage-of-completion project

After you have created the percentage-of-completion contract and project, use this procedure to create the billing rules that you negotiated with the customer.

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **Project contracts**. Select a project contract.

2.  In the **Project contracts** form, on the **Project contract** tab, click **Billing rule**.

3.  In the **Billing rules** form, click **New**.

4.  In the **Line type** field, select **Progress**.

5.  On the **Billing rule line details** FastTab, in the **Contract value** field, enter the total value of the contract.

6.  In the **Project** field, select the project to which the billing rule applies.

7.  In the **Category** field, select the category for the billing rule.

8.  You can assign the billing rule to additional projects. On the **Project** FastTab, in the **Available projects** section, select a project, and then click **Add**. The project is displayed in the **Selected projects** section.

9.  You can enter a percentage to calculate the amount that the customer withholds from payments on an invoice. On the **Payment retention terms** FastTab, select the funding source, and then, in the **Retention percentage** field, enter the retention percentage.

10. Repeat this procedure to create additional billing rules for the project contract.

## See also

[Create billing rules](create-billing-rules.md)

[Billing rules (form)](https://technet.microsoft.com/library/hh227642\(v=ax.60\))

[Project contracts (form)](https://technet.microsoft.com/library/aa586038\(v=ax.60\))

[Projects (form)](https://technet.microsoft.com/library/aa585245\(v=ax.60\))

[Project management and accounting parameters (form)](https://technet.microsoft.com/library/aa599440\(v=ax.60\))

  


