---
title: Edit document templates
TOCTitle: Edit document templates
ms:assetid: 6c6248f7-a8e8-4b3e-b5dc-fbc181e2bbb4
ms:mtpsurl: https://technet.microsoft.com/library/Hh271553(v=AX.60)
ms:contentKeyID: 36384185
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- EditDocumentTemplates
audience: Application User
ms.search.region: Global
---

# Edit document templates 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A document template defines the properties and workflow steps for documents, the order in which each document on the **Internal controls** page can be nested or grouped, and how the documents are grouped. You can change the default document templates to more closely match the needs of your organization. For example, you have a control matrix in a Microsoft Excel worksheet and you want to import the controls from the worksheet. If the worksheet contains columns that are not part of the default document templates, you can modify the document templates to add the corresponding document properties. Then you can import controls.


> [!NOTE]
> <P>If you modify the default document templates and you plan to import controls by using the default controls library, you might have to make corresponding changes to the columns in the default controls library worksheet before you import controls. For example, if you add a document property to a document template, you might want to add a column to the default controls library worksheet and fill in values for the property. Then, when you import controls, the property is automatically filled in.</P>



1.  Click **Compliance** on the top link bar, and then click **Document templates** on the Quick Launch.

2.  On the **Edit document templates** page, select a document template. For more information about each template, see [About compliance document templates](about-compliance-document-templates.md).

3.  Enter a name for the template.

4.  In the **Icon** section, select an icon from the list. The icon that you select will be displayed next to documents of this template type on the **Internal controls** page.

5.  In the **Properties** section, add or change lines.
    
      - To add a line, click **Add property**.
    
      - To change a line, click the **Edit line** icon, make the changes, and then click the **Update line** icon.

6.  In the **Workflow** section, add or change lines for the compliance workflow.
    
      - To add a line, click **Add step**.
    
      - To change a line, click the **Edit line** icon, make the changes, and then click the **Update line** icon.
    
      - To temporarily inactivate a compliance workflow step, click the **Edit line** icon, clear the **In use** check box, and then click the **Update line** icon. You can select this check box again at any time to reactivate the step.

7.  Click **Save**.

## See also

[Set up the Internal controls site](set-up-the-internal-controls-site.md)

[Examples: Internal controls](examples-internal-controls.md)

[Manage internal controls](manage-internal-controls.md)

  


