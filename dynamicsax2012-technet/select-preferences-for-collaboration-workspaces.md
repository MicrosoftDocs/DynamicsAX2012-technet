---
title: Select preferences for collaboration workspaces
TOCTitle: Select preferences for collaboration workspaces
ms:assetid: eafe821e-d0fa-4cd3-bcdd-5f85ae846edb
ms:mtpsurl: https://technet.microsoft.com/library/Hh227484(v=AX.60)
ms:contentKeyID: 36059867
author: Khairunj
ms.date: 10/06/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Select preferences for collaboration workspaces 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to specify preferences for how you create, maintain, and manage membership for collaboration workspaces. If you are using cumulative update 7 for Microsoft Dynamics AX 2012 R2, you can also specify preferences for how projects in Microsoft Dynamics AX 2012 are integrated with Microsoft SharePoint products or services.

If workspace settings are not configured for a certain business area (project, campaign, or opportunity), you cannot create collaboration workspaces for that area. However, you can link collaboration workspaces to projects, campaigns, or opportunities and then remove the links if they are no longer needed.

### To select options for collaboration workspaces

1.  Click **System administration** \> **Setup** \> **Enterprise Portal** \> **Collaboration workspace settings**.

2.  In the **Collaboration workspace settings** form, click **New**.

3.  In the **Business area** field, specify whether this configuration applies to projects, campaigns, opportunities, or all business areas.

4.  In AX 2012 R3 and cumulative update 7 or later for AX 2012 R2: If you are integrating the management of projects with Microsoft Project, in the **SharePoint implementation type** field, specify whether you are storing Microsoft Project MPP files in Microsoft SharePoint Online or an on-premises implementation of Microsoft SharePoint Server.

5.  In the **Workspace home page** field, type or select the root URL for this collaboration workspace.
    

    > [!NOTE]
    > <P>Enterprise Portal for Microsoft Dynamics AX must be installed on the Microsoft SharePoint Server 2010 computer or Microsoft SharePoint Server 2013 computer where the collaboration workspace sites are created.</P>

    
    Enter your SharePoint logon credentials when prompted.

6.  In the **Template** field, select a collaboration workspace template for the selected business area.
    
    In AX 2012 R3 and cumulative update 7 or later for AX 2012 R2: If you want to store a Microsoft Project MPP file in a Microsoft SharePoint implementation, you must select either a project site template or team site template.
    

    > [!NOTE]
    > <P>The templates that are available in this list are created and maintained in the Microsoft SharePoint Foundation 2010 or Microsoft SharePoint Foundation 2013 team site and in Microsoft SharePoint Server 2010 or Microsoft SharePoint Server 2013. The list may include templates that are not designed for collaboration workspaces.</P>



7.  In AX 2012 R3 and cumulative update 7 or later for AX 2012 R2: If you want to keep the task list in SharePoint in sync with the work breakdown structure in projects, select the **Synchronize the SharePoint task list with the project WBS structure** check box. This option is available only if you selected **Project** in the **Business area** field in step 1.

8.  Specify how you want workspaces to be created:
    
      - Select the **Create workspace automatically** check box if you want collaboration workspaces to be created automatically for the selected business area.
        
        If you select this check box and you selected **Project** in the **Business area** field, select the check boxes for the project types that you want collaboration workspaces to be created for.
        

        > [!NOTE]
        > <P>Collaboration workspaces can be created automatically only for business areas that are created in the Microsoft Dynamics AX client. They cannot be created automatically for business areas that are created in Enterprise Portal for Microsoft Dynamics AX.</P>

    
      - Select the **Prompt to create workspace** check box if you want users to be prompted with the option to create a collaboration workspace when they create one of the specified business areas.
        

        > [!NOTE]
        > <P>If the <STRONG>Create workspace automatically</STRONG> check box is not selected, users can create a workspace by selecting <STRONG>Collaboration workspace</STRONG> &gt; <STRONG>Create collaboration workspace</STRONG> in the <STRONG>Setup</STRONG> group in the appropriate form.</P>

    
      - Select the **Prompt to delete workspace** check box if you want users to be prompted to delete the associated workspace when a project, campaign, or opportunity is deleted.

## See also

[Set up collaboration workspaces](set-up-collaboration-workspaces.md)

[Create or link to a collaboration workspace (Sales and marketing)](create-or-link-to-a-collaboration-workspace-sales-and-marketing.md)

[Create or link to a collaboration workspace (Project)](create-or-link-to-a-collaboration-workspace-project.md)

[Collaboration workspace settings (form)](https://technet.microsoft.com/library/hh242783\(v=ax.60\))

  


