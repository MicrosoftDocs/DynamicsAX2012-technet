---
title: Set up integration with Microsoft Office Add-ins
TOCTitle: Set up integration with Microsoft Office Add-ins
ms:assetid: c78ade1c-a85e-4519-893a-e56fab51c3b2
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh781102(v=AX.60)
ms:contentKeyID: 43894517
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- add in
- add ins
- add-ins
- integration
- microsoft office
- add-in
---

# Set up integration with Microsoft Office Add-ins [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft Dynamics AX can be integrated with Microsoft Word and Microsoft Excel. If your organization uses the Office Add-ins for Microsoft Dynamics AX, users can create Word documents and Excel workbooks that are linked dynamically to the tables in Microsoft Dynamics AX. Integration for the Office Add-ins must be set up before users can use the Office Add-ins to create files.

Use the following procedure to configure data sources for the Office Add-ins.

1.  Click **Organization administration** \> **Setup** \> **Document management** \> **Document data sources**.

2.  In the **Document data sources** form, click **New**.

3.  In the **Module** field, select the Microsoft Dynamics AX module from which a user can open and create files. For example, select **Sales and marketing** to enter the settings for a sales quotation.

4.  In the **Data source type** field, select one of the following options:
    
      - If the user wants to create files that other users can modify, select **Service**.
    
      - If the user wants to create files that only the user can modify, select **Query**.

5.  In the **Data source name** field, select the applicable data source.

6.  Select the **Activated** check box.


> [!NOTE]
> <P>The Office Add-ins are not supported by versions of Microsoft Office earlier than Microsoft Office 2007.</P>



## See also

[Integrating Microsoft Dynamics AX with Microsoft Office](integrating-microsoft-dynamics-ax-with-microsoft-office.md)

[Using the Microsoft Dynamics AX Add-in for Excel](using-the-microsoft-dynamics-ax-add-in-for-excel.md)

[Using the Microsoft Dynamics AX Add-in for Word](using-the-microsoft-dynamics-ax-add-in-for-word.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

