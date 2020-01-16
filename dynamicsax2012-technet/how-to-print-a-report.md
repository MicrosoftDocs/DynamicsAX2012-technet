---
title: 'How to: Print a Report'
TOCTitle: 'How to: Print a Report'
ms:assetid: 3ac14ad7-6427-4553-af97-13f961689fad
ms:mtpsurl: https://technet.microsoft.com/library/Ee873254(v=AX.60)
ms:contentKeyID: 28119346
author: Khairunj
ms.date: 10/24/2013
mtps_version: v=AX.60
---

# How to: Print a Report 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX, you can print reports that were created using Visual Studio tools for Microsoft Dynamics AX. This topic provides the pre-requisite steps for printing a report and to print from a menu item, including steps for programmatically specifying advanced printer properties like orientation and paper tray. For more information on how to programmatically print a report, see the [Report Programming Model](https://go.microsoft.com/fwlink/?linkid=230569).

### Pre-requisites to Print a Report

  - The report must be [deployed to the report server](how-to-deploy-reports-to-a-report-server.md).

  - The report must be [added to the AOT](how-to-add-reports-to-microsoft-dynamics-ax.md). This step is unique to Visual Studio tools for Microsoft Dynamics AX reports.

  - You must also have a way to access the report. You can access a report [programmatically](https://go.microsoft.com/fwlink/?linkid=230569) or from a [menu item](how-to-create-a-menu-item-for-a-report.md).

### To Print a Report from a Menu Item

1.  Open a menu item that corresponds to the report that you want to print.

2.  Set the parameters that exist.
    
    If you have queries, click the **Select** button and set the range.
    
    Click the **Print Destination** button to set the print destination fields. You can print to a screen, printer, file, or email recipient.

3.  Click **OK** to print the report.

### To Print a Report and specify printer properties in X++

  - Use the methods of SRSPrintDestinationSettings to set properties such as landscape/portrait orientation, number of copies, paper tray, and whether to collate the printed report.
    
        public static void main(Args _args)
        {
            SrsReportRunController controller = new SrsReportRunController();
            SRSPrintDestinationSettings printSettings;
        
            // set report name
            controller.parmReportName(ssrsReportStr(LedgerBalanceControl, Report));
        
            // get print settings from contract
            printSettings = controller.parmReportContract().parmPrintSettings();
        
            // set printer as the destination
            printSettings.printMediumType(SRSPrintMediumType::Printer);
            printSettings.printerName = "My Printer"; // specify your printer name 
            printSettings.printLandscape(true); // print in landscape orientation
            printSettings.numberOfCopies(2);    // print 2 copies
            printSettings.setPaperTray(1); // print to paper tray with index = 1 
                  
            printSettings.collate(true);          // collate printed copies
        
            // suppress the parameter dialog to send directly to printer
            controller.parmShowDialog(false);
        
            // start operation
            controller.startOperation();
        }

## See also

[Report Integration and Customization Overview](report-integration-and-customization-overview.md)

[How to: Add Reports to Microsoft Dynamics AX](how-to-add-reports-to-microsoft-dynamics-ax.md)

[How to: Deploy Reports to a Report Server](how-to-deploy-reports-to-a-report-server.md)

[How to: Create a Menu Item for a Report](how-to-create-a-menu-item-for-a-report.md)

