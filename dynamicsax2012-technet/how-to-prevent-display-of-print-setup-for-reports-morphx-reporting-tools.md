---
title: 'How to: Prevent Display of Print Setup for Reports (MorphX Reporting Tools)'
TOCTitle: 'How to: Prevent Display of Print Setup for Reports'
ms:assetid: 3d3b4807-dbde-496a-b8df-f63278aa06cb
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Bb314611(v=AX.60)
ms:contentKeyID: 35290296
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Prevent Display of Print Setup for Reports (MorphX Reporting Tools) 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A report can contain sensitive data that requires that it be printed to only a secure printer.

## Preventing Users from Changing the Destination Printer

If a report contains sensitive data, you can prevent users who run the report from changing the destination printer.

### To prevent users from changing the printer

  - Set the Interactive property for the report to **No**.
    
    –or–

  - Override the ReportRun.prompt method on the report and set the value of the \_enableDevice parameter to false.

## Example

    public boolean prompt(boolean _enableCopy = true,
                          boolean _enablePages = true,
                          boolean _enableDevice = true,
                          boolean _enableProperties = true,
                          boolean _enablePrintTo = true)
    {
        boolean ret;
        ;
        ret = super(_enableCopy,
                    _enablePages,
                    false,   // _enableDevice
                    _enableProperties,
                    _enablePrintTo);
        return ret;
    }

## See also

[How to: Specify Printers for Reports (MorphX Reporting Tools)](how-to-specify-printers-for-reports-morphx-reporting-tools.md)

[Report Properties](https://technet.microsoft.com/en-us/library/aa856851\(v=ax.60\))

[Report Methods (MorphX Reporting Tools)](report-methods-morphx-reporting-tools.md)

