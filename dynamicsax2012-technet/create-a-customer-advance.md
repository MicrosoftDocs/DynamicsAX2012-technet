---
title: Create a customer advance
TOCTitle: Create a customer advance
ms:assetid: 22551e8f-229d-42a2-9371-1e32e3d71932
ms:mtpsurl: https://technet.microsoft.com/library/Hh208473(v=AX.60)
ms:contentKeyID: 36056173
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- customer advance
- customer advance amount
- customer advance percentage
audience: Application User
ms.search.region: Global
---

# Create a customer advance 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Some projects require a significant financial investment before the project starts. You may want to request an advance payment from the customer when you negotiate a project contract. The customer advance amount can be stated as a specific amount or as a percentage of the total revenue for the project. As work progresses on the project, you can subtract part or all of the amount of the advance from project invoices. The amount of the advance and the terms for subtracting the advance are specified in the project contract.

You can request an advance amount from a customer only if the project stage is **In process**.

## Set up a customer advance

Use this procedure to enter a customer advance percentage that you can apply to budget lines for a project. The percentage and description appear on the selected budget lines in the **Customer advance** form. You can use the same percentage for all lines in the budget by creating a default advance setting for a project. For more information about how to set up a default value for customer advances, see [Customer advance (form)](https://technet.microsoft.com/library/hh242232\(v=ax.60\)).

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. On the **All projects** list page, on the **Action Pane**, on the **Project** tab, in the **New** group, click **Project** to create a new project. Or, select a project in the list.

2.  In the **Projects** form, on the **Action Pane**, on the **Manage** tab, in the **Bill** group, click **Customer advance**.

3.  In the **Customer advance** form, in the **Advance percentage** field, enter the percentage to use to calculate the amount of a customer advance for the selected budget transaction type.
    
    Optional: To enter or modify a percentage and description for all the lines at the same time, click **Default settings**. In the **Update default values** form, enter the percentage and description for the default percentage, and then select the **Apply current settings** check box. Click **OK** to save the default settings.

4.  In the **Customer advance** form, click **OK** to save your information and open the **Invoice proposals** form. The amount of the customer advance is displayed in the form.

## Create an invoice for a customer advance

Use this procedure to create a customer invoice to request an advance payment for a project.

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. On the **All projects** list page, on the **Action Pane**, on the **Project** tab, click **Project** to create a new project, or select a project in the list.

2.  On the **Action Pane**, on the **Manage** tab, in the **Bill** group, click **Customer advance**.

3.  Follow the steps in the “Set up a customer advance” procedure in this topic to calculate the amount of a customer advance.

4.  In the **Invoice proposals** form, review the preliminary information that appears on the customer invoice for the project. When you are ready to create the invoice and submit it for approval, click **Submit**.
    

    > [!NOTE]
    > <P>Before you can submit an invoice for approval, workflow for processing invoice proposals must be set up.</P>



The invoice for the customer advance is routed to workflow. If the invoice is approved, the invoice is posted to the ledger accounts, and a copy is sent to the customer for payment.

## See also

[Customer advance (form)](https://technet.microsoft.com/library/hh242232\(v=ax.60\))

[Update default values (form)](https://technet.microsoft.com/library/hh209610\(v=ax.60\))

  


