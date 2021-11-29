---
title: Export accounting information (Retail essentials)
TOCTitle: Export accounting information (Retail essentials)
ms:assetid: c188bfb1-9f0a-4621-b69d-3bff3228ae48
ms:mtpsurl: https://technet.microsoft.com/library/Dn736945(v=AX.60)
ms:contentKeyID: 62200422
author: Khairunj
ms.date: 08/15/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.RetailSmbAccountExportProfile
- Forms.RetailSmbAccountExportResults
- MsDynAx060.Forms.RetailSmbAccountExportProfile
- MsDynAx060.Forms.RetailSmbAccountExportResults
---

# Export accounting information (Retail essentials) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Some retailers use one software system for retail operations and another system for accounting. This topic explains how to set up accounting exports, and how to export accounting information from Retail essentials in a file that can be used in a third-party accounting system.

A basic chart of accounts is included in Retail essentials. You can use this chart of accounts to map accounting totals from statement posting to the account numbers in the third-party accounting software. Exports can be performed manually or set up to recur automatically at regular intervals.

You can view previously exported accounting totals by the date range of the totals that were exported. You can also delete previously exported totals or export these totals again.

## Set up accounting export

1.  Click **Retail essentials** \> **Financials** \> **Accounting export** \> **Export profiles**.

2.  In the **Account export profile** form, click **New** to create a new profile, and then enter a name and description.

3.  On the **Profile accounts** FastTab, click **New** to map a Retail essentials account to an account in the third-party accounting system.

4.  In the **Exported account name** field, enter the name of the account in the third-party accounting system. Then, in the **Main account** field, select the Retail essentials account.

5.  Repeat steps 3 and 4 for each account that you want to map.

6.  Click **Retail essentials** \> **Channels** \> **Setup** \> **Retail parameters**.

7.  Click **Accounting export**, and then, in the **Accounting export profile** field, select a profile.

8.  In the **Export file path** field, enter the name of the folder to export to.

9.  Optional: To use a prefix to identify the file that is exported, enter the prefix in the **Export filename prefix** field.

10. Optional: To use an XSLT transform file to convert the file that is exported, enter the location of the transform file in the **XSLT transform file** field.

## Export accounting totals

1.  Post any unposted retail statements that should be included in the exported totals.
    

    > [!NOTE]
    > <P>The current day's statements are not included in exported totals. This restriction helps guarantee that the daily totals that are included in the export are complete.</P>



2.  Click **Generate account activity**.
    
    This batch job adds up totals for each account since the last export.
    

    > [!TIP]
    > <P>In the batch job dialog box, click <STRONG>Recurrence</STRONG> to set up a schedule to automatically generate accounting totals.</P>



3.  Click **Export account activity**.
    
    This batch job exports the accounting totals.
    

    > [!TIP]
    > <P>In the batch job dialog box, click <STRONG>Recurrence</STRONG> to set up a schedule to automatically export the accounting totals.</P>



## View or export previously exported accounting totals

1.  Click **Retail essentials** \> **Financials** \> **Accounting export** \> **Previous exports**.

2.  In the **Accounting export results** form, in the **Date exported** column, select the date for which to view the accounting export.

3.  View the exported accounting totals on the **Account amounts** FastTab.

4.  To export the selected accounting export again, clear the **Exported to file** check box. The totals will be exported the next time that the **Export account activity** batch job is run.

  


