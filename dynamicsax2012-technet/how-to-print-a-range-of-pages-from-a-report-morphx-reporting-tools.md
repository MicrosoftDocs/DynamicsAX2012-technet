---
title: 'How to: Print a Range of Pages from a Report (MorphX Reporting Tools)'
TOCTitle: 'How to: Print a Range of Pages from a Report'
ms:assetid: 66caf3fa-436e-462f-a935-3b9ab0c5bab8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa609374(v=AX.60)
ms:contentKeyID: 35290300
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Print a Range of Pages from a Report (MorphX Reporting Tools) 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Print a specified range of pages from a report by using the PrintJobSettings.allPages, PrintJobSettings.from, and PrintJobSettings.to methods.

## Example

In the following example, pages 2–4 from a report are printed to a .pdf file. The ReportRun.setTarget method specifies a file as the print medium. The printJobSettings.format and printJobSettings.fileName methods specify the file format and the file name.

    static void printToPDF(Args _args)
    {
        Args                args;
        ReportRun           rr;
        str reportName = 'Cust';
        ;
    
        args = new Args(reportName);
    
        rr = new ReportRun(args,'');
        
        rr.setTarget(Printmedium::File);
        rr.printJobSettings().format(PrintFormat::PDF);
    
        rr.printJobSettings().fileName("C:\\Cust_ReportRange.pdf");
        
        rr.printJobSettings().allPages(false);
        rr.printJobSettings().from(2);
        rr.printJobSettings().to(4);
    
        // Disables forms that enable users to modify
        // the report query and print settings.
        rr.query().interactive(false);
        rr.report().interactive(false);
    
        rr.run();
    
    }

## See also

[How to: Specify Printers for Reports (MorphX Reporting Tools)](how-to-specify-printers-for-reports-morphx-reporting-tools.md)

