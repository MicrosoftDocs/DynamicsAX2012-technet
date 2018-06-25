---
title: Create a project contract to invoice for time and materials
TOCTitle: Create a project contract to invoice for time and materials
ms:assetid: 56316370-ab3b-4419-b75b-3e07df6e7fc4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh208965(v=AX.60)
ms:contentKeyID: 36057322
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- category
- time & material
- time and material
- billing rules
---

# Create a project contract to invoice for time and materials [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use these procedures to create a project and project contract, so that you can invoice a customer for the time and materials used for a project. The timing of the invoices is negotiated with the customer.

**Example**

Your organization offers software development services. Your organization agrees to provide five technical consultants to work on a software development project for a customer for the next six months. The customer agrees to pay $150 for each consulting hour posted to the project. Your organization agrees to send an invoice to the customer at the end of each month for the hours posted to the project for the month.

Use these procedures to set up a contract, an associated project, and the billing rules to use to calculate the customer invoice amount at the end of each month.

After you have created the contract and the project, you can set up the details of the project. For example, you can define the activities of the project and assign workers to the project.

## Prerequisites

Before you create a project with billing rules, you must set up the following project information in the **Project management and accounting parameters** form:

  - Set up the number sequence to use when you create a billing rule.

  - Set up a fee journal to use by default for posting invoices on Time and material projects.

## Create a contract for time and materials

Use this procedure to create a project contract for Time and material projects.

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **Project contracts**.

2.  In the **Project contracts** form, on the **Action Pane**, on the **Project contract** tab, click **Project contract**.

3.  In the **New project contract** form, complete the following fields:
    
      - **Project contract ID**
    
      - **Name**
    
      - **Funding type**
    
      - **Funding source**
    
      - **Sales currency** – By default, this is the currency to use for customer invoices associated with the project contract. You can modify the sales currency in a specific customer invoice.
    
    Click **OK**. This information is copied to the header of the **Project contracts** form.

4.  In the **Project contracts** form, complete the rest of the necessary information for the project. To change default values in the form, on the **Action Pane**, on the **Project contract** tab, click **Edit**.

## Create a project for time and materials

Use this procedure to create a project and any subprojects associated with a contract.

1.  In the **Project contracts** form, on the **Action Pane**, on the **Project contract** tab, in the **New** group, click **Project**.

2.  In the **Create project** form, enter a project type of **Time and material**.

3.  Select a project group.

4.  Enter additional project information. For example, complete the following fields:
    
      - **Project ID**
    
      - **Project name**
    
      - **Project group** – A project group defines posting information for projects assigned to the group.
    
      - **Project contract ID** – This associates the project contract with the project.
        

        > [!NOTE]
        > <P>The <STRONG>Project contract ID</STRONG> field is automatically filled with the number of the project contract from the <STRONG>Project contracts</STRONG> form. You can change the project contract to a different contract number.</P>

    
      - **Customer**

5.  Enter any additional required information, and then click **OK** to create the project.

6.  After you have created the project, set the project stage to **In process**. For more information about how to set a project stage, see [Modify a project stage](modify-a-project-stage.md).

## Create billing rules for a time and materials contract

After you have created the contract and the associated project, use this procedure to create the billing rules for the contract.

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **Project contracts**. Select a project contract.

2.  In the **Project contracts** form, on the **Project contract** tab, in the **Set up** group, click **Billing rule**.

3.  In the **Billing rules** form, click **New**.

4.  Select a line type of **Time and material**.

5.  If you want to include indirect costs in the billing rule, on the **Billing rule line details** FastTab, select the **Include indirect costs** check box.

6.  You can assign the billing rule to additional projects. On the **Project** FastTab, in the **Available projects** section, select a project, and then click **Add**. The project is displayed in the **Selected projects** section.

7.  You can select categories to designate the transactions to bill to the customer. On the **Project** FastTab, in the **Selected projects** section, select a project, and then click **Chargeable categories**.
    
    In the **Billing rules setup for project / category** form, select the categories to assign to the project and add to customer invoices.

8.  If you want to enter a payment retention percentage for the billing rule, on the **Payment retention terms** FastTab, select a funding source, and then, in the **Retention percentage** field, enter a retention percentage.

## See also

[Create billing rules](create-billing-rules.md)

[Project contracts (form)](https://technet.microsoft.com/en-us/library/aa586038\(v=ax.60\))

[Projects (form)](https://technet.microsoft.com/en-us/library/aa585245\(v=ax.60\))

[Billing rules (form)](https://technet.microsoft.com/en-us/library/hh227642\(v=ax.60\))

[Project management and accounting parameters (form)](https://technet.microsoft.com/en-us/library/aa599440\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

