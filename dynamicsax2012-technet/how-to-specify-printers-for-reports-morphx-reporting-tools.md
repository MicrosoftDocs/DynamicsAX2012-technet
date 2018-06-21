---
title: 'How to: Specify Printers for Reports (MorphX Reporting Tools)'
TOCTitle: 'How to: Specify Printers for Reports'
ms:assetid: 54ca6a41-ba68-4425-8b7c-248e2fae0d6d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa606033(v=AX.60)
ms:contentKeyID: 35290298
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Specify Printers for Reports (MorphX Reporting Tools) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Specify which printer a report is sent to and specify the printer settings by using the PrintJobSettings::deviceName method and the PrintJobSettings::unpackPrintJobSettings method. For more information about modifying other print settings, see PrintJobSettings class.

Specify whether users can select a printer and modify the printer settings by setting the **Interactive** property of the report to **No**. For more information, see [Report Properties](https://technet.microsoft.com/en-us/library/aa856851\(v=ax.60\)).

Send a report to a printer, a file, an e-mail address, or a screen by using the ReportRun.setTarget method and the PrintMedium system enumeration.

Send a report to additional output targets by using the ReportOutputUser and WebReportHTML classes.

## Specifying a Printer and Printer Settings for a Report

### To specify a printer and printer settings for a report

1.  To override the init method, click the report in the Application Object Tree (AOT), right-click **Methods**, click **Override Method**, and then click **init**. The X++ editor will appear.

2.  Call the deviceName and unpackPrintJobSettings methods.

## Example

In the following example, the deviceName method specifies the b110-1102-b printer and the unpackPrintJobSettings method specifies the settings that are contained in the SalesFormLetter class that ships with Microsoft Dynamics AX.

When you open the report by right-clicking the report and then clicking **Open**, the specified printer will be displayed in the dialog box.

    public void init()
    {
        PrintJobSettings printJobSettings;
        super();
    
        element.deviceName("b110-1102-b");
           element.unpackPrintJobSettings(SalesFormLetter::getPrinterSettingsFormletter(DocumentStatus::Invoice,PrintSetupOriginalCopy::Original));
    
    }

## See also

[Walkthrough: Creating Reports in the AOT (MorphX Reporting Tools)](walkthrough-creating-reports-in-the-aot-morphx-reporting-tools.md)

[How to: Print a Range of Pages from a Report (MorphX Reporting Tools)](how-to-print-a-range-of-pages-from-a-report-morphx-reporting-tools.md)

