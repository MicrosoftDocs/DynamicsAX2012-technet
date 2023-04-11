---
title: 'How to: Position Sections and Controls on Reports by Using X++ (MorphX Reporting Tools)'
TOCTitle: 'How to: Position Sections and Controls on Reports by Using X++'
ms:assetid: cde72335-bf04-4030-9bf0-add613dd686d
ms:mtpsurl: https://technet.microsoft.com/library/Bb278223(v=AX.60)
ms:contentKeyID: 35290372
author: tonyafehr
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Position Sections and Controls on Reports by Using X++ (MorphX Reporting Tools) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The sections in a report can be positioned by using code. The controls in a section can also be positioned by using code. Add this code to methods that you override.

## Relevant System Classes

### To access system class documentation

  - In the AOT, expand the **System Documentation** node, expand the **Classes** node, and then expand a class node to view its methods.
    
    or
    
    From the **Help** menu, click Developer Help. Expand the **Microsoft Dynamics AX SDK** node, expand the **Reference** node, expand the **Classes** node, expand the **Microsoft Dynamics AX System Classes** node, and then expand a class node to view its methods.
    
    or
    
    Navigate to the system class documentation on MSDN.

The following classes and their listed methods are used in the procedures in this topic:

  - ReportRun
    
      - currentYmm100
    
      - fetch
    
      - gotoYmm100
    
      - newPage
    
      - page
    
      - rulerCM

  - ReportSection
    
      - executeSection
    
      - leftMarginsEtc
    
      - topMarginAndFrame

  - ReportControl
    
      - left100mm
    
      - top100mm

## Positioning Items in a Report

The following steps describe how sections and controls are positioned in a report. The first part of the scenario creates a report with one section and two controls.

### To create a report with one section and two controls

1.  In the AOT, right-click the **Reports** node, and then click **New Report**. Expand the report node that you just created.

2.  Right-click the **Designs** node, and then click **New Report Design**. Expand the report design node that you just created.

3.  Right-click **AutoDesignSpecs**, click **New**, and then click **ProgrammableSection**.

4.  Right-click the **ProgrammableSection** that was just created, click **New Control**, and then click **String**.

5.  Right-click the string control node that you just created, and then click **Properties**. Use the **Properties** window to set **Name** to **ReturnHelloPSC**.

6.  Right-click **ProgrammableSection**, click **New Control**, and then click **Integer**. Use the **Properties** window to rename the integer control to **DemoRulerPSC**.

### To add the returnHelloM method that contains example code

1.  Right-click the **ProgrammableSection** node, click **Methods**, and then click **New Method**.

2.  Use the **Properties** window to rename the method to returnHelloM.

3.  Right-click the **returnHelloM** node, and then click **Edit**.

4.  Copy the following code and then paste it into the editor window.
    
        display str returnHelloM()
        {
            return "Hello";
        }
    

    > [!NOTE]
    > <P>The returnHelloM method is invoked by the ReturnHelloPSC string control. The DataMethod property of that control is set to this method.</P>



### To create a new demoRulerM method that contains example code

1.  Right-click the **ProgrammableSection** node, and then click **New Method**.

2.  Use the **Properties** window to rename the method to demoRulerM.

3.  Right-click the **demoRulerM** node, and then click **Edit**.

4.  Copy the following code and then paste it into the editor window.
    
        display int demoRulerM()
        {
            // The rulerCM method draws a ruler onto the report borders.
            // This helps the developer ascertain exactly
            // where the controls are positioned.
            // The rulerCM method is ineffective if called inside the
            // fetch method or inside executeSection.
            // The rulerINCH method is also available.
        
            return element.rulerCM();
        }
    

    > [!NOTE]
    > <P>The demoRulerM method is invoked by the DemoRulerPSC integer control. The DataMethod property of that control is set to this method. The demoRulerM method calls the rulerCM method. The rulerCM method is useful during development and testing, but it should be removed from your final production code.</P>



### To override the executeSection method

1.  Expand the **ProgrammableSection** node. Right-click the **Methods** node, and then click **executeSection**.

2.  Right-click the **executeSection** node, and then click **Edit**.

3.  Copy the following code and then paste it into the editor window.
    
        // This is an override of a method that exists under the
        // ProgrammableSection node in the AOT.
        public void executeSection()
            
            ReportControl repcon;
            ;
            if (element.page() >= 2)
            {
                repcon = this.controlName("ReturnHelloPSC");
            
                // 70 mm from left edge of the section.
                repcon.left100mm(7001 - this.leftMarginsEtc());
            
                // 20 mm from the top edge of the section.
                repcon.top100mm(2001 - this.topMarginAndFrame());
            
            super();

### To override the fetch method

1.  Expand the **ProgrammableSection** node. Right-click the **Methods** node, and then click **fetch**.

2.  Right-click the **fetch** node, and then click **Edit**.

3.  Copy the following code and then paste it into the editor window.
    
        // Override of the report's fetch method.
        public boolean fetch()
        {
            if (element.prompt())
            {
                // The print command is only for demonstration.
                print element.currentYmm100(), " == currentYnn100 , page 1.1";
                
                // By default, positioning starts at 0 mm from the top
                // of the paper (after adjusting for the margin).
                // Produce the report by invoking programmable section 1.
                element.execute(1);
                
                // Move positioning to 20 mm from the top of the paper.
                // Invoke programmable section 1 again.
                element.gotoYmm100(2001);
                print element.currentYmm100(), " == currentYnn100 , page 1.2";
                element.execute(1);
                
                element.gotoYmm100(6001);
                print element.currentYmm100(), " == currentYnn100 , page 1.3";
                element.execute(1);
                
                element.newPage(); // Creates page 2 of the report.
                print element.currentYmm100(), " == currentYnn100 , page 2.1";
                
                // The code in executeSection() positions the controls
                // differently after page 1.
                element.execute(1);
                return true;
               }
           return false;
        }

### To link each control to a method that was added

1.  Under the **ProgrammableSection**, right-click the **ReturnHelloPSC** node, and then click **Properties**.

2.  In the **Properties** window, set the **DataMethod** property to **returnHelloM**.

3.  Right-click the **DemoRulerPSC** node, and then click **Properties**.

4.  In the **Properties** window, set the **DataMethod** property to **demoRulerM**.

### To test the scenario

1.  To view the report, right click the node of the report, and then click **Open**.

2.  Click OK to accept the report specifications. The report appears on the screen.

"Hello" appears three times, all rightmost on the first page. The first occurrence is in the upper-left corner, by default. The vertical distances between the other two "Hello" occurrences are caused by the calls to gotoYmm100 in the fetch method.

Go to the last page of the report, and then press PageDown. One "Hello" is no longer positioned in the upper-left corner. This "Hello" was repositioned by the calls to left100mm and top100mm in executeSection.

## Tutorial Available

A working example that demonstrates the positioning of items in a report ships as part of Microsoft Dynamics AX. This tutorial demonstrates how a control can be fixed to a given position and made to stay there when margins and border thickness changes.

### To access the tutorial

  - In the AOT, expand **Reports**, and then expand **tutorial\_Positioning**.

## See also

[Report Design Section Properties](https://technet.microsoft.com/library/aa643974\(v=ax.60\))

