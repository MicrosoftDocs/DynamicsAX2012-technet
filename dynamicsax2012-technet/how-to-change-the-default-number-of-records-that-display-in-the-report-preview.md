---
title: 'How to: Change the Default Number of Records that Display in the Report Preview'
TOCTitle: 'How to: Change the Default Number of Records that Display in the Report Preview'
ms:assetid: d0a62a8f-e8b5-4587-beb2-cd56c5d6cc43
ms:mtpsurl: https://technet.microsoft.com/library/Ee910032(v=AX.60)
ms:contentKeyID: 28119589
author: tonyafehr
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Change the Default Number of Records that Display in the Report Preview 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can preview a report design to be sure that the layout and data look the way that you intended. The preview will return 1000 records by default. This makes the processing of large amounts of data for the preview more efficient. If you want to see all the data in the preview of your report, in the **Preview** window, click the **Load data sets fully** link.

The following procedure describes how to change the default number of records that display in the report preview.

### To change the default number of records in the preview

1.  Start Registry Editor.

2.  Locate the following registry subkey:
    
    HKEY\_LOCAL\_MACHINE \\Software\\Microsoft\\Dynamics\\6.0\\

3.  Select the **Reporting** node. In the right pane, right-click **DefaultDataSetSizeInPreview** and click **Modify…**

4.  In the **Edit DWORD Value** window, click the **Decimal** radio button.

5.  In the **Value data** field, enter the default number of records that you want to display on the report preview.
    

    > [!NOTE]
    > <P>Enter 0 if you want all records to display in the report preview.</P>
    > <P>The value will be reset to 1000 if you repair Visual Studio tools.</P>



6.  Restart Visual Studio to update the default value of records that will display in the report preview.

## See also

[How to: Preview a Report Design](how-to-preview-a-report-design.md)

[Creating Reports Overview](creating-reports-overview.md)

