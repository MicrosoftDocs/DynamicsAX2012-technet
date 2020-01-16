---
title: Set up the Internal controls site
TOCTitle: Set up the Internal controls site
ms:assetid: 37391592-8984-4a22-b21f-429d64f8cf69
ms:mtpsurl: https://technet.microsoft.com/library/Hh271496(v=AX.60)
ms:contentKeyID: 36384128
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- ConfigureControlEnvironment
audience: Application User
ms.search.region: Global
---

# Set up the Internal controls site 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Effective internal controls are important for compliance with regulations such as Section 404 of the U.S. Sarbanes-Oxley Act of 2002. Examples of internal controls relate to the preparation of financial statements, maintaining visibility of purchase orders and sales orders, and managing vendor accounts, customer accounts, and product master records. The **Internal controls** site contains the compliance-related data that helps your organization manage and evaluate the effectiveness of its controls.

Use the **Set up control environment** page to define the structure of the **Internal controls** site. For example, you might define the following structure:

  - **Corporate Headquarters**

  - **Operations - Domestic**
    
      - **Purchasing - Domestic**
    
      - **Sales - Domestic**

  - **Operations - Global**
    
      - **Purchasing - Global**
    
      - **Manufacturing - Global**
    
      - **Sales - Global**

After the folders have been created, you can add compliance documents to the **Internal controls** site. A compliance document represents a compliance project task, significant account, process, risk, control, test plan, issue, or remediation on the **Internal controls** site. Document templates define the properties and compliance workflow steps for documents, the level of the hierarchy in which each document can be nested or grouped, and how the documents are grouped. You can use the **Edit document templates** page to change the document templates. For more information, see [Examples: Internal controls](examples-internal-controls.md), [Manage internal controls](manage-internal-controls.md), and [Edit document templates](edit-document-templates.md).


> [!NOTE]
> <P>The <STRONG>Enable compliance process</STRONG> duty controls access to the <STRONG>Set up control environment</STRONG> page.</P>



## Set up the Internal controls site structure

1.  Click **Compliance** on the top link bar, and then click **Set up control environment** on the Quick Launch.

2.  On the **Set up control environment** page, in the left pane, select a node. You can add a child node by clicking **Add child** under the left pane.

3.  Enter a name for the document folder.

4.  Enter an owner of the node, in the following format: domain\\username
    

    > [!NOTE]
    > <P>The owner must be set up as a user on the Enterprise Portal for Microsoft Dynamics AX SharePoint site.</P>



5.  Click **Add user** and enter a user for the node by using the following format: domain\\username
    
    For example, you might enter users who will document the internal controls that are contained in the node, and give these users **Add/Copy** permissions. You might also enter users who will audit the internal controls, and you might give these users **Read** permissions.
    

    > [!NOTE]
    > <P>Each user must be set up as a user on the Enterprise Portal SharePoint site.</P>



6.  Select permissions for the user and then click the **Update line** icon.

7.  Repeat steps 5 and 6 for the remaining users for the node.

8.  Click **Save**.

## See also

[Manage internal controls](manage-internal-controls.md)

[Import internal controls to the Compliance site](import-internal-controls-to-the-compliance-site.md)

  


