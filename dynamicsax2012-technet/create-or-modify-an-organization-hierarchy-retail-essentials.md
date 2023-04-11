---
title: Create or modify an organization hierarchy (Retail essentials)
TOCTitle: Create or modify an organization hierarchy (Retail essentials)
ms:assetid: afdc1246-b1d8-4819-a4d4-d8aae9ca5f2e
ms:mtpsurl: https://technet.microsoft.com/library/Dn736936(v=AX.60)
ms:contentKeyID: 62200413
author: tonyafehr
ms.date: 11/13/2014
mtps_version: v=AX.60
---

# Create or modify an organization hierarchy (Retail essentials) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

You can use organizational hierarchies to view and report on a business from various perspectives. For example, you can set up one hierarchy for tax, legal, or statutory reporting. You can then set up another hierarchy to report financial information that is not legally required, but that is used for internal reporting. This topic describes how to create and modify an organizational hierarchy.

## Create organizations

Before you create an organizational hierarchy, you must create organizations. For more information, see [Create or modify a legal entity](create-or-modify-a-legal-entity.md) or [Create or modify an operating unit](create-or-modify-an-operating-unit.md). For information about how to create departments and teams, see [Key tasks: New worker positions](key-tasks-new-worker-positions.md) and [Manage teams](manage-teams.md).

## Create a hierarchy

To set up an organization hierarchy, follow these steps:

1.  Click **Retail essentials** \> **Channels** \> **Organization hierarchies**.

2.  In the **Organization hierarchies** form, click **New**.

3.  In the **Name** field, enter a unique name for the organizational hierarchy.

4.  Press CTRL+S to save the new hierarchy.

## Assign a purpose to the hierarchy

Before you can add organizations to a hierarchy, you must select a purpose for the hierarchy. The purpose that you select determines the types of organizations that can be included in the hierarchy. For more information about the various hierarchy purposes, see [Organization hierarchies](organization-hierarchies.md).

To assign a purpose to a hierarchy, follow these steps:

1.  Click **Retail essentials** \> **Channels** \> **Organization hierarchies**. In the **Organization hierarchies** form, select a hierarchy, and then, on the **Purposes** FastTab, click **Assign purpose**.

2.  In the **Organization hierarchy purposes** form, in the **Purposes** pane, select a purpose, and then click **Add**. Close the form.

3.  In the **Organization hierarchies** form, select the organizational hierarchy to assign the purpose to, and then click **OK**.

## Add organizations to a hierarchy

You add organizations to the hierarchy to represent the structure of a business. You can include legal entities and operating units in the same hierarchy, if both organization types can be used for the purpose that you selected for the hierarchy.

To add organization types to a hierarchy, follow these steps:

1.  Click **Retail essentials** \> **Channels** \> **Organization hierarchies**.

2.  In the **Organization hierarchies** form, on the **Action Pane**, click **View**.

3.  In the **Hierarchy designer -** form, on the **Action Pane**, click **Edit**.

4.  On the **Action Pane**, click **Insert**, and then select an organization type. In the form that is displayed for the selected organization type, select an organization, and then click **OK**.
    
    To add levels underneath an organization, select the organizational unit to add the levels to, and then click **Insert**.

5.  To save the modifications that you made to the hierarchy, press CTRL+S.
    
    To save the modifications as a draft, click **Save as draft**. Your changes are saved, but the hierarchy does not become active. When you have finished making changes to the hierarchy, click **Publish and close**. When you publish a hierarchy, you must specify an effective date. The effective date indicates when the hierarchy becomes active.
    

    > [!WARNING]
    > <P>If you close the <STRONG>Hierarchy designer -</STRONG> form without saving your changes, a dialog box appears. You can either save the hierarchy as a draft or discard your changes. If you close the dialog box without making a selection, your changes are discarded.</P>



## Modify an organization hierarchy

If a reorganization, merger, or acquisition occurs, you can modify an existing organizational hierarchy to represent the new structure.

You can view or modify a hierarchy as of any future date or as of an effective date that has been published. However, you cannot publish updates to the hierarchy between existing effective dates. Changes must take effect after the last effective date that was published for the hierarchy.


> [!NOTE]
> <P>To view or modify a draft hierarchy, you must first view the published hierarchy that the draft is based on and then click <STRONG>Edit</STRONG>. Draft hierarchies cannot be accessed directly.</P>



1.  Click **Retail essentials** \> **Channels** \> **Organization hierarchies**.

2.  In the **Organization hierarchies** form, select a hierarchy, and then click **View**.

3.  In the **Hierarchy designer -** form, on the **Action Pane**, click **Edit**.
    
    If a draft already exists for the hierarchy, a message appears. You can either continue to work on the draft, or delete the draft and start a new one. You can save a draft for each effective date that is published.

4.  Add or remove organizations, change the position of organizations in the hierarchy, and make other modifications as applicable for your organization.

5.  To save the modified hierarchy as a draft, click **Save as draft**. Your changes are saved, but the modified hierarchy does not become active. When you have finished making changes to the hierarchy, click **Publish and close**. When you publish a hierarchy, you must specify an effective date. If versions of the hierarchy already exist that have future effective dates, your changes must take effect after the last effective date that was published for the hierarchy.
    

    > [!WARNING]
    > <P>If you close the <STRONG>Hierarchy designer -</STRONG> form without saving changes, a dialog box appears. You can either save the hierarchy as a draft or discard your changes. If you close the dialog box without making a selection, your changes are discarded.</P>



## See also

[Working with organizations and organizational hierarchies (Retail essentials)](working-with-organizations-and-organizational-hierarchies-retail-essentials.md)

  


