---
title: Define validation connections
TOCTitle: Define validation connections
ms:assetid: e3ec8fe1-e6cc-44a3-bb83-e019f620efb2
ms:mtpsurl: https://technet.microsoft.com/library/Aa551388(v=AX.60)
ms:contentKeyID: 36059727
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- project
- worker
- validation connection
audience: Application User
ms.search.region: Global
---

# Define validation connections 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

**This is preliminary documentation and is subject to change.**

You can associate a worker and a project from either the **Worker** form or the **Projects** form. However, the result of adding validation groups from the **Worker** form or the **Projects** form differs depending on the form that you use to add the group. Either a project is made available for a group of workers or a group of projects is made available for one worker.

## For a project

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**.

2.  Select a project.

3.  On the **Action Pane**, on the **Plan** tab, in the **Validation** group, click either **Assign workers** or **Assign categories**.

4.  In the **Project validation worker assignments** form or **Project validation category assignments** form, select the **Worker** tab or **Categories** tab, depending on the form that you opened.

5.  If you selected **Assign workers** in step 3, select the legal entity from which you want to assign workers.
    

    > [!NOTE]
    > <P>The <STRONG>Legal entity</STRONG> field is available only if intercompany timesheet support has been enabled for your legal entity.</P>

    
     
    

    > [!NOTE]
    > <P>This control is available only if Microsoft Dynamics AX 2012 Feature Pack is installed.</P>



6.  Click the **Add** and **Remove** buttons to select the appropriate workers or categories from the **Remaining workers** or **Remaining categories** list.

## For a worker

1.  Click **Human resources** \> **Common** \> **Workers** \> **Workers**.

2.  Select a worker.

3.  On the **Action Pane**, on the **Project management** tab, in the **Setup** group, click either **Assign categories** or **Assign projects**.

4.  In the **Worker validation project assignments** form or the **Worker validation category assignments** form, select the **Projects** tab or **Categories** tab, depending on the form that you opened.

5.  Click the **Add** and **Remove** buttons to select the appropriate projects or categories from the **Remaining projects** or **Remaining categories** list.

## For a category

1.  Click **Project management and accounting** \> **Setup** \> **Categories** \> **Project categories**.

2.  Select a category.

3.  In the menu bar, click **Validation**, and then select either **Assign workers** or **Assign projects** to associate a worker or project with the selected category.

4.  In the **Category validation worker assignments** form or the **Category validation project assignments** form, select the **Worker** tab or **Projects** tab, depending on the form that you opened.

5.  Click the **Add** and **Remove** buttons to select the appropriate workers or projects from the **Remaining workers** or **Remaining projects** list.

## See also

[About validation in projects](about-validation-in-projects.md)

[About intercompany timesheets](about-intercompany-timesheets.md)

[Project validation worker assignments (form)](https://technet.microsoft.com/library/aa583039\(v=ax.60\))

[Project validation category assignments (form)](https://technet.microsoft.com/library/hh209635\(v=ax.60\))

[Worker validation project assignments (form)](https://technet.microsoft.com/library/aa615780\(v=ax.60\))

[Worker validation category assignments (form)](https://technet.microsoft.com/library/hh242736\(v=ax.60\))

[Projects (form)](https://technet.microsoft.com/library/aa585245\(v=ax.60\))

[Workers (form)](https://technet.microsoft.com/library/aa583961\(v=ax.60\))

[Project categories (form)](https://technet.microsoft.com/library/aa582118\(v=ax.60\))

[Category validation project assignments (form)](https://technet.microsoft.com/library/aa620168\(v=ax.60\))

[Category validation worker assignments (form)](https://technet.microsoft.com/library/aa619209\(v=ax.60\))

  


