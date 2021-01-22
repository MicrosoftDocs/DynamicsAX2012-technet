---
title: Create advanced account structures and rules for budget planning
TOCTitle: Create advanced account structures and rules for budget planning
ms:assetid: 5d488e9f-f098-438b-b4f6-6368f34becfb
ms:mtpsurl: https://technet.microsoft.com/library/JJ677341(v=AX.60)
ms:contentKeyID: 49384115
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- budget
- account structures
- budget planning
- account structures and rules
- rules for budget planning
audience: Application User
ms.search.region: Global
---

# Create advanced account structures and rules for budget planning 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create budget planning rules that provide additional financial dimensions that are part of the account combination, but are not included in the account structure.

An advanced rule structure includes one or more financial dimensions that contain information that your organization wants to use for budget planning, but that are not part of the account structure. Each budget planning rule is associated with a specific account structure and can consist of one or more advanced rule structures.

Advanced account structures that are associated with budget planning rules can have blank financial dimensions. When a budget plan uses an account structure that has a blank financial dimension, financial details can be added during the budget planning process and at different levels of the organization.

Budget planning rules are identical to advanced rules, and both types of rules can be used for budget plans. However, budget planning rules can be used in budget plans to support and validate financial dimensions that are not part of the account structures for the general ledger.


> [!NOTE]
> <P>We recommend that you use Management Reporter for Microsoft Dynamics ERP to create, maintain, deploy, and view financial reports that include budget planning data. Management Reporter lets you design financial reports based on ledger accounts and financial dimensions, drill down to transaction-level detail, and use web-based report viewing. For more information about how to print financial reports by using Management Reporter, see <A href="https://go.microsoft.com/fwlink/?linkid=324762">Management Reporter for Microsoft Dynamics ERP</A>.</P>
> <P>You can use Management Reporter to report on budget planning data only if you have rollup 4 or later for Management Reporter 2012 installed.</P>



## Create an advanced rule structure

1.  Click **General ledger** \> **Setup** \> **Chart of accounts** \> **Advanced rule structures**.

2.  Click **New**, enter the ID and description of an advanced rule structure, and then click **OK**.

3.  Click **Add segment** to add criteria, and then select the appropriate options to create the criteria. You might have to scroll down to view all the criteria. For more information, see the example later in this topic.

4.  Click **Activate**, and then close the form.

5.  Complete the next procedure to create a budget planning rule that you can assign the advanced rule structure to.

## Create a budget planning rule

1.  Click **General ledger** \> **Setup** \> **Chart of accounts** \> **Configure account structures**.

2.  Select the account structure to apply the budget planning rule to.

3.  On the **Action Pane**, in the **Setup** group, click **Budget planning rules**.

4.  Click **New**.
    

    > [!NOTE]
    > <P>To add or modify advanced rules for an account structure, the account structure must be in <STRONG>Draft</STRONG> status. If the account structure has a status of <STRONG>Active</STRONG>, and you try to create a new advanced rule or modify an existing advanced rule, a message is displayed. Click <STRONG>Edit advanced rule</STRONG> to change the status of the account structure from <STRONG>Active</STRONG> to <STRONG>Draft</STRONG>.</P>



5.  Enter the ID and name of an advanced rule, and then click **OK**.

6.  Click **Add filter** to add criteria, and then select the appropriate options to create the criteria. You might have to scroll down to view all the criteria.

7.  On the **Advanced rule structures** FastTab, click **Add**. Select the advanced rule structure to use when the advanced rule is used. Only active advanced rule structures are displayed.

8.  To activate the advanced rule, you must activate the account structure. In the **Configure account structures** form, on the **Action Pane**, click **Activate**.

## Example

Your organization is developing a budget plan for new Sales positions. In the budget for a position, the salary account requires a position number. Because this information is not required in the general ledger, you must create an advanced account structure and a budget planning rule.

1.  Create the following advanced rule structure to track the position number for the salary account:
    
    **Advanced rule structure** = Position number

2.  Create the following advanced rule to determine when the advanced rule structure is used:
    
    Where Department **is** Human Resources

3.  Add the **Position number** advanced rule structure so that it is used when the advanced rule is used.

4.  In the **Configure account structures** form, activate the account structure.

  


