---
title: Create a report by using the Microsoft Dynamics AX auto-report wizard
TOCTitle: Create a report by using the Microsoft Dynamics AX auto-report wizard
ms:assetid: 8528cc70-8624-4eba-94ce-cd01c2dd6267
ms:mtpsurl: https://technet.microsoft.com/library/Gg213177(v=AX.60)
ms:contentKeyID: 35133419
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create a report by using the Microsoft Dynamics AX auto-report wizard 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Auto-reports are preconfigured reports that you can generate by clicking **File** \> **Print** \> **Print** in a Microsoft Dynamics AX form. You can quickly generate an auto-report for use once, or you can create and save a custom auto-report that can be reused later. This topic describes both of these scenarios.

## Scenario: Quickly print a report for one-time use

You can use the auto-report functionality to quickly generate a report that displays the data that you are currently viewing in a Microsoft Dynamics AX form. The following procedure explains how to do so.

1.  Open the Microsoft Dynamics AX form that contains the data to print.

2.  Click **File** \> **Print** \> **Print**.
    
    The **Autoreport** form is displayed.

3.  To filter or sort the data on the report, click **Select**.
    
    An inquiry form is displayed. In this form, you can complete the following tasks:
    
      - **Filter the data** – To filter the data that is displayed on the report, click the **Range** tab. For information about how to filter the data, see [Filter the data on a report](filter-the-data-on-a-report.md).
    
      - **Sort the data** – To sort the data that is displayed on the report, click the **Sorting** tab. For information about how to sort the data, see [Sort the data on a report](sort-the-data-on-a-report.md).
    
      - **Specify date options** – To filter the data that is displayed on the report based on date information, click the **Date options** tab. Specify whether you want the report to display all active records, records that are active as of a specific date, or records that are active in a specific date range.

4.  Click **OK** to return to the **Autoreport** form.

5.  Click **OK** to print the report to the screen.

## Scenario: Create a custom report for reuse

You can use the auto-report functionality to create a custom report that is saved so that it can be reused later. The following procedure explains how to do so.

1.  Open the Microsoft Dynamics AX form that contains the data to print.

2.  Click **File** \> **Print** \> **Print**.
    
    The **Autoreport** form is displayed.

3.  Click **Modify...** \> **New**.
    
    The **Autoreport Wizard** is displayed.

4.  The wizard displays the names of tables and fields. If you are more familiar with the system names of tables and fields (for example, **CustTable**), than the names that appear in the user interface (for example, **Customer**), select the **Show system names of tables and fields** check box.
    
    Click **Next**.

5.  The **Report name** page is displayed. Enter a name for the report. Click **Next**.

6.  The **Select fields** page is displayed. Use the arrows to specify which fields should be included on the report. Use the **Up** and **Down** buttons to indicate the order in which they should appear. Click **Next**.
    

    > [!NOTE]
    > <P>If a field does not contain any data, it will not be included in the report.</P>



7.  If the report includes a field that contains real numbers or integers, the **Summation on fields** page is displayed. Specify which fields should contain sum values. Click **Next**.

8.  The **Report layout** page is displayed. Select a template to specify the layout of the report, and a template to specify the layout of tables. Click **Next**.

9.  Click **Finish** to complete the wizard. The **Autoreport** form is redisplayed.

10. To filter or sort the data on the report, click **Select**.
    
    An inquiry form is displayed. In this form, you can complete the following tasks:
    
      - **Filter the data** – To filter the data that is displayed on the report, click the **Range** tab. For information about how to filter the data, see [Filter the data on a report](filter-the-data-on-a-report.md).
    
      - **Sort the data** – To sort the data that is displayed on the report, click the **Sorting** tab. For information about how to sort the data, see [Sort the data on a report](sort-the-data-on-a-report.md).
    
      - **Specify date options** – To filter the data that is displayed on the report based on date information, click the **Date options** tab. Specify whether you want the report to display all active records, records that are active as of a specific date, or records that are active in a specific date range.

11. Click **OK** to return to the **Autoreport** form.

12. Click **OK** to print the report to the screen.
    
    The report settings are automatically saved. The next time that you open the form that you opened in step 1, you can generate and print this report by clicking **File** \> **Print** \> **Print**.

  


