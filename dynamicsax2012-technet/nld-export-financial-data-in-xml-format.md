---
title: (NLD) Export financial data in XML format
TOCTitle: (NLD) Export financial data in XML format
ms:assetid: d897dca4-a9b4-46a5-8eb6-944c094a8037
ms:mtpsurl: https://technet.microsoft.com/library/Hh227396(v=AX.60)
ms:contentKeyID: 36059644
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Netherlands
- XML
- export
audience: Application User
ms.search.region: Netherlands
---

# (NLD) Export financial data in XML format 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can export company financial and tax data in XML format. The XML file is created using the file name and path that you specify in the **Path and file name for XBRL** form. The exported XML file can be transformed to XBRL using third-party software and then submitted to the tax authorities. You can also specify budget models for the current and comparative reporting periods to generate budget figures in the XML file.

An XBRL instance document is generated in the path specified in the **Path and file name for XBRL** form. You can choose which instance documents (financial reports) that you want to create in XBRL Reporter. The software checks to ensure that all of the account numbers imported from Microsoft Dynamics AX are correctly mapped to XBRL elements, and that all XBRL elements needed for a report are mapped to account numbers. XBRL Reporter displays a list of errors for unmapped elements or accounts, which you can correct or ignore.

You can view the contents of the XBRL instance documents to ensure that they contain the same information as the financial statements printed in Microsoft Dynamics AX. You can encrypt the XBRL instance documents when you save them to the hard drive.

When you process the XBRL instance documents and check the base financial data in the files, you can add additional information, such as clarifications, if required. After processing, the instance documents can be submitted to the government portal. You can also send the XBRL instance documents to your bank to provide financial information for a loan application.

Manage folder and file permissions so that only users qualified to view the reports or use the eXtensible Business Reporting Language (XBRL) Reporter have access.

1.  Click **General ledger** \> **Setup** \> **Path and file name for XBRL**.

2.  In the **File name** field, enter the path and file name for the XML export file. Select only the XML file extension.

3.  Click **OK** to save the path and file name specified in the **File name** field.

4.  Click **General ledger** \> **Periodic** \> **Export financial data to XBRL**.

5.  Under the **Current period** field group, in the **From date** and **To date** fields, select the starting and ending dates of the reporting period. The starting and ending dates must be within the same fiscal year.

6.  In the **Budget model** field, select the current year budget model to generate the budget figures in the XML file.

7.  Under the **Comparative period** field group, in the **From date** and **To date** fields, enter or select the starting and ending dates for the comparative period, which provides the historic data for comparison. The starting and ending dates must be within the same fiscal year.

8.  In the **Budget model** field, select the comparative year budget model to generate the budget figures in the XML file.

9.  Select the **Include beginning balances**, **Include ending balances**, **Include net changes**, and **Include closing transactions** check boxes to include this data in the XML file for both the current period and the comparative period.

10. Click **OK** to export the XML file to the path specified in the **File name** field in the **Path and file name for XBRL** form.

## See also

[(NLD) Export financial data for XBRL reporter (form)](https://technet.microsoft.com/library/hh242795\(v=ax.60\))

[(NLD) Path and file name for XBRL (form)](https://technet.microsoft.com/library/hh227568\(v=ax.60\))

  


