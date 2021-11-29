---
title: Set up a reapproval rule for purchase orders
TOCTitle: Set up a reapproval rule for purchase orders
ms:assetid: 8b28192a-2525-417d-8611-350a0c2ba2fd
ms:mtpsurl: https://technet.microsoft.com/library/JJ683229(v=AX.60)
ms:contentKeyID: 49684852
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up a reapproval rule for purchase orders 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to set up a reapproval rule that specifies the fields that, when they are changed, require an approved purchase order to be manually reapproved. When you create this kind of rule, you can control when a purchase order requires manual reapproval by the designated approvers in the workflow process that is defined for your organization. Any fields that are not included in the reapproval rule are automatically approved by the workflow process. For example, you might not want a routine change that is considered standard for the purchase order process to require manual reapproval by the approvers in the purchase order workflow, such as when the vendor’s confirmed delivery date is entered. Therefore, you would not include the **Confirmed** field in your reapproval rule.

You must configure a workflow for purchase order reapproval for a reapproval rule to be enforced.


> [!NOTE]
> <P>This functionality is applicable only when change management for purchase orders is enabled. For more information, see <A href="key-tasks-change-management-for-purchase-orders.md">Key tasks: Change management for purchase orders</A>.</P>



## Configure workflow for purchase order reapproval

1.  Click **Procurement and sourcing** \> **Setup** \> **Procurement and sourcing workflows**.

2.  Open the **Purchase order workflow** that has been defined for your organization.

3.  Select the **Approve purchase order** workflow element in the workspace, and then in the **Action Pane**, click **Basic Settings**.

4.  In the **Properties** form, click **Automatic actions**. Add the following condition:
    
      - **Purchase orders**. **Requires purchase order re-approval** is **No**.

5.  In the **Auto complete action** field, select **Approve**.

For more information about how to set up workflows in Procurement and sourcing, see [Set up Procurement and sourcing workflows](set-up-procurement-and-sourcing-workflows.md).

## Set up a reapproval rule for purchase orders

1.  Click **Procurement and sourcing** \> **Setup** \> **Policies** \> **Purchasing policies**.

2.  On the **Purchasing policies** list page, on the **Action Pane**, in the **New** group, click **Policy**. The **Purchasing policy** form is displayed.

3.  On the **General** FastTab, in the **Name** field, enter a name for the policy.

4.  On the **Policy organizations** FastTab, in the **Select organization hierarchy** field, select **Companies**. Select the legal entity that the reapproval rule should apply to, and then click **Add \>\>**. You can add as many legal entities for the policy as required.
    

    > [!NOTE]
    > <P>You can define a reapproval rule for purchase orders only if the hierarchy type is <STRONG>Companies</STRONG>.</P>



5.  Select **Re-approval rule for purchase orders** in the **Policy rule type:** field.

6.  Click **Create policy rule**. The **Re-approval rule for purchase orders** form is displayed.

7.  Select a start date and an end date for the policy rule.

8.  From the list of available fields on the right, select the fields that manual reapproval is required for when changes are made to an approved purchase order and add them to the **Selected** list on the left. The list of available fields reflects the fields that are in the **Purchase order** form, and additional fields from forms that can also be accessed from the **Purchase order** form.
    

    > [!TIP]
    > <P>If you select the <STRONG>Tree view</STRONG>, you can view the fields as they are grouped in the <STRONG>Purchase order</STRONG> form.</P>



9.  Click **OK** to save the policy rule.

## See also

[Purchase order (form)](https://technet.microsoft.com/library/aa557983\(v=ax.60\))

[Re-approval rule for purchase orders (form)](https://technet.microsoft.com/library/jj680083\(v=ax.60\))

[About purchasing policies](about-purchasing-policies.md)

  


