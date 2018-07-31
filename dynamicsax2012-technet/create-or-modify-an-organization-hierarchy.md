---
title: Create or modify an organization hierarchy
TOCTitle: Create or modify an organization hierarchy
ms:assetid: e791dec5-9dc6-46cb-acdf-f15805179d1e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh227463(v=AX.60)
ms:contentKeyID: 36059818
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create or modify an organization hierarchy 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use organizational hierarchies to view and report on your business from various perspectives. For example, you can set up one hierarchy for tax, legal, or statutory reporting. You can then set up another hierarchy to report financial information that is not legally required, but that is used for internal reporting.

This topic describes how to create and modify an organizational hierarchy.

## Create organizations

Before you create an organizational hierarchy, you must create organizations. For more information, see [Create or modify a legal entity](create-or-modify-a-legal-entity.md) or [Create or modify an operating unit](create-or-modify-an-operating-unit.md). For information about how to create departments and teams, see [Key tasks: New worker positions](key-tasks-new-worker-positions.md) and [Manage teams](manage-teams.md).

## Create a hierarchy

1.  Click **Organization administration** \> **Setup** \> **Organization** \> **Organization hierarchies**.

2.  Click **New**.

3.  Enter a name for the organizational hierarchy.

4.  Press **CTRL+S** to save the new hierarchy.

## Assign a purpose to the hierarchy

Before you add organizations to a hierarchy, you must select a purpose for the hierarchy. The purpose that you select determines the types of organizations that can be included in the hierarchy. For more information about individual hierarchy purposes, see [How to use organization hierarchy purposes](organization-hierarchies.md).

Complete the following steps to assign a purpose to a hierarchy.

1.  Click **Organization administration** \> **Setup** \> **Organization** \> **Organization hierarchy purposes**.

2.  Select a purpose, and then click **Add**. The **Organizations** form is displayed.

3.  Select the organizational hierarchy that you want to assign the purpose to, and then click **OK**.

## Add organizations to the hierarchy

You add organizations to the hierarchy to represent the structure of your business.

You can include legal entities and operating units in the same hierarchy, if both organization types can be used for the purpose that you selected for the hierarchy.

1.  Click **Organization administration** \> **Setup** \> **Organization** \> **Organization hierarchies**. Select a hierarchy, and then click **View**.

2.  Click **Edit**.

3.  Click **Insert**, and then select an organization type. In the form that is displayed, select an organization, and then click **OK**.
    
    To add levels underneath an organization, select the organization that you want to add the levels to, and then click **Insert**.

4.  When you have finished making changes, save the hierarchy.
    
    To save a draft, click **Save as draft**. Your changes are saved, but the hierarchy does not become active. If you have finished making changes to the hierarchy, click **Publish and close**. When you publish a hierarchy, you must specify an effective date. The effective date indicates when the hierarchy becomes active.
    

    > [!WARNING]
    > <P>If you close the <STRONG>Hierarchy designer -</STRONG> form without saving changes, a dialog appears, with options to save the hierarchy as a draft or discard your changes. If you close the dialog without making a selection, your changes will be discarded.</P>



## Modify a hierarchy

If a reorganization, merger, or acquisition occurs, you must modify existing organizational hierarchies.

You can view or change a hierarchy as of any future date or as of an effective date that has been published. However, you cannot publish updates to the hierarchy between existing effective dates. Changes must take effect after the last effective date that was published for the hierarchy.

If you must make a correction, you can delete the last future published version of a hierarchy. In the **Future changes** FactBox, click **More** to open the **Future change dates** form. Click **Delete latest date**.


> [!NOTE]
> <P>To view or modify a draft hierarchy, you must first view the published hierarchy that the draft is based on, and then click <STRONG>Edit</STRONG>. Draft hierarchies cannot be accessed directly.</P>



1.  Click **Organization administration** \> **Setup** \> **Organization** \> **Organization hierarchies**. Select a hierarchy, and then click **View**.

2.  Click **Edit**.
    
    If a draft already exists for the hierarchy, a message appears when you click **Edit**. You can either continue to work on the draft, or delete the draft and start a new one. You can save a draft for each effective date that is published.

3.  Add or remove organizations, or change the position of organizations in the hierarchy.

4.  When you have finished making changes, save the hierarchy.
    
    To save a draft, click **Save as draft**. Your changes are saved, but the modified hierarchy does not become active. If you have finished making changes to the hierarchy, click **Publish and close**. When you publish a hierarchy, you must specify an effective date. If versions of the hierarchy already exist that have future effective dates, your changes must take effect after the last effective date that was published for the hierarchy.
    

    > [!WARNING]
    > <P>If you close the <STRONG>Hierarchy designer -</STRONG> form without saving changes, a dialog appears, with options to save the hierarchy as a draft or discard your changes. If you close the dialog without making a selection, your changes will be discarded.</P>



## See also

[About organizations and organizational hierarchies](about-organizations-and-organizational-hierarchies.md)

  


