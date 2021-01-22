---
title: Configure budget planning security
TOCTitle: Configure budget planning security
ms:assetid: c0ce741e-fc9a-49e7-a1d1-5356fc4abba0
ms:mtpsurl: https://technet.microsoft.com/library/Dn887225(v=AX.60)
ms:contentKeyID: 63378893
author: Khairunj
ms.author: daxcpft
ms.date: 11/19/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Configure budget planning security 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

In budget planning, you can limit a user’s access to the budget plans based on their assignment in the budgeting organization hierarchy. For example, a budgeting organization hierarchy might consist of Finance department at the top of the hierarchy and Sales, Operations, IT and Human resources at the bottom of the hierarchy. In this hierarchy it’s possible to limit user access to the budget plans, so users can only view the Sales and Operations department’s budget plans.

There are two security models available that allow two different ways in which to access the budgeting organization:

  - Based on security organizations - All users who have access to an organization in the security roles can access the budget plans for that organization. To enable this security model, the organization hierarchy used must have both Security and Budget planning purposes assigned.

  - Based on worker positions – All budget plan preparers who are associated with workers and have a position in an organization unit in the budget planning organization hierarchy can access the budget plans.

To select a security model, in the **Budget planning configuration** form, you can select the security model that will be used by the legal entity. Click **Budgeting** \> **Setup** \> **Budget planning** \> **Budget planning configuration**. In the **Parameters** form, in the **Security model** field, select the security model.

## Example: Set up user security using Based on security organizations security model

To set up access based on security organizations, you need to assign a security purpose to the organizational hierarchy that is used for budget planning.

1.  Click **Organization administration** \> **Setup** \> **Organization** \> **Organization hierarchies**.

2.  In the **Organization hierarchies** form, in the **View** group, click **Organization hierarchy** to open the **Hierarchy designer -** form.

3.  On the **Action pane**, click **Purposes**.

4.  In the **Organization hierarchy purposes** form, select **Security** from the **Purposes** list, and then click **Add**.

5.  Select the budgeting organization hierarchy and click **OK**.

Next, assign user access to the organizational hierarchy.

1.  Click **System administration** \> **Common** \> **Users** \> **Users**.

2.  Select the user and click **Edit**.

3.  On the **User's roles** FastTab, the user must have the Budget manager and the Budget clerk security roles assigned.

4.  Click **Assign organizations**.

5.  In the **Organizations for the user %1 in role %2** form, select **Grant access to specific organizations individually**.

6.  In the **Select organization hierarchy** field, select **Budgeting – Departments**.

7.  Select the organizational units that the user has access to and click **Grant** or **Grant with children**. **Grant** will give the user access to the selected organizational unit only. The **Grant with children** option will give the user access to the selected organizational unit and its children organizations.

## Example: Set up user security using Based on worker positions security model

To set up access based on worker position, you need to associate the worker with a position that is assigned to a department and part of the budgeting organizational hierarchy.

1.  Click **Human resources** \> **Common** \> **Organization** \> **Positions** \> **Positions**.

2.  On the **Action Pane**, click **Position** to create a new position.

3.  Select a **Job** for the position and click **Create positions**.

4.  In the **Position** form, confirm that the department selected in the **Department** field is assigned in the budgeting organizational hierarchy.

Next, create a new worker for this position.

1.  In the **Position** form, click **Hire**. Fill in the information about the worker.

2.  Close the form.

3.  Now, associate the user with the newly created worker. Click **System administration** \> **Common** \> **Users** \> **Users**.

4.  Select the user and on the **Action pane**, in the **Set up** group, click **Relations**.

5.  In the **User relations** form, click **New**. Select the person who was created in the previous step.

## Grant access to budget plans by user group

In addition to the security model selected, you can grant access to budget plans using budget planning groups.

1.  Click **Budgeting** \> **Setup** \> **Budget planning** \> **Budget planning configuration**.

2.  Select the **Parameters** form.

3.  Select the **Allow access to budget plans by user group** check box. If this check box is selected, the **Budget planning user group** is available on the **Create a budget plan** form when a new budget plan is created. All users who are assigned to the selected user group will be able to see this budget plan.
    

    > [!NOTE]
    > <P>Users who have the system administrator role assigned will have access to all budget plans. Users who are not system administrators must have the budget manager or budget clerk security role assigned to have access to the budgeting area page.</P>


  


