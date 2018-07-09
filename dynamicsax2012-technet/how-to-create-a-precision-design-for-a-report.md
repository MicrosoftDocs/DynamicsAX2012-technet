---
title: 'How to: Create a Precision Design for a Report'
TOCTitle: 'How to: Create a Precision Design for a Report'
ms:assetid: 7749d609-65c9-4933-84c9-173e6cc37aca
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Cc593896(v=AX.60)
ms:contentKeyID: 28119381
ms.date: 11/07/2012
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Framework.Design.Model.Reports.PrecisionDesignDefinition
---

# How to: Create a Precision Design for a Report [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can create a precision design for a report that requires a very precise layout, such as an invoice or a bank check. SQL Report Designer is used to create and edit a precision design for a report. Before you use SQL Report Designer to create a report design, the report must be available in the model and datasets must be added to the report so that the data is available in SQL Report Designer. The following procedures explain how to create a precision design and how to edit an existing report design with SQL Report Designer.

### To create a precision design for a report

1.  In Model Editor, expand the node for the report that you want to work with.

2.  Add datasets to the report. A report must have one or more datasets. For more information, see [How to: Define a Report Dataset](how-to-define-a-report-dataset.md).

3.  Right-click the **Designs** node for the report, point to **Add**, and then click **Precision Design**.
    
    The report design opens in SQL Report Designer and is ready to be edited. You can drag and drop fields from the **Report Data** pane onto the report. In addition, you can drag and drop elements from **Toolbox** onto the report. Use the properties in the **Properties** window to modify the display of the elements in a report. For more information, see [Designing Reports in Report Designer](http://go.microsoft.com/fwlink/?linkid=229038).

### To edit an existing report design in SQL Report Designer

1.  In Model Editor, expand the node for the report that you want to work with.

2.  Expand the **Designs** node for the report.

3.  Right-click the design, and depending upon the type of design, do one of the following:
    
      - If it is an auto design, click **Create Precision Design**.
    
      - If it is a precision design, click **Edit Using Designer**.
    

    > [!NOTE]
    > <P>You can edit an auto design with SQL Report Designer. However, when you do this, a new precision design is created based on the existing auto design. The changes made in SQL Report Designer are stored in the new precision design.</P>



## See also

[How to: Create an Auto Design for a Report](how-to-create-an-auto-design-for-a-report.md)

[Designing Reports in Report Designer](http://go.microsoft.com/fwlink/?linkid=229038)

[Walkthrough: Referencing a Report Parameter from Multiple Datasets in a Precision Design Report](walkthrough-referencing-a-report-parameter-from-multiple-datasets-in-a-precision-design-report.md)

