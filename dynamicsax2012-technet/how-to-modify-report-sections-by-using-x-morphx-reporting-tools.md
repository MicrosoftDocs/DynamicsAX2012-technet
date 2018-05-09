---
title: 'How to: Modify Report Sections by Using X++ (MorphX Reporting Tools)'
TOCTitle: 'How to: Modify Report Sections by Using X++'
ms:assetid: 9d1a6caf-5151-4176-b8ff-8cbca35f8535
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa847072(v=AX.60)
ms:contentKeyID: 35290314
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Modify Report Sections by Using X++ (MorphX Reporting Tools) 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can override the executeSection method for a report section to modify the layout of the section and to modify how the section is printed. You can use the ReportSection class, the ReportControl class, and additional classes that extend the ReportControl class to modify a section and the controls in the section.

To override the executeSection method, expand a report section, right-click **Methods**, and then click **Override Method**.

For more information about adding and modifying sections to reports, see [Walkthrough: Creating Reports in the AOT (MorphX Reporting Tools)](walkthrough-creating-reports-in-the-aot-morphx-reporting-tools.md) and view the **tutorial\_Positioning** report that is located under the **Reports** node in the Application Object Tree (AOT).

The following are examples of how to override the executeSection method:

  - Specify whether a section is included when a report is printed by making the super() call conditional in the executeSection method.

  - Hide and show controls in a report when it is printed by using the hide and show methods in the classes that extend ReportControl, such as the ReportRealControl.hide method and the ReportRealControl.show method. You can use the ReportDesign.controlName method and the ReportDesign.control method to specify the controls.

  - Insert a page break between sections by calling the newPage method.

## Example

To reference a section in X++, call the design.sectionName method as shown in the following code example.

    public boolean fetch()
    {
        CustTable   custTable;
        ;
    
        while select custTable
            where custTable.AccountNum
        {
            reportSection = this.design().sectionName('PageFooter');
            this.send(custTable);
    
            this.enablePageFooter();
            this.disableSection(PageFooter);
            this.enableSection(reportSection);
    
            this.newPage();
        }
    
        return true;
    }

## See also

[Report Sections (MorphX Reporting Tools)](report-sections-morphx-reporting-tools.md)

