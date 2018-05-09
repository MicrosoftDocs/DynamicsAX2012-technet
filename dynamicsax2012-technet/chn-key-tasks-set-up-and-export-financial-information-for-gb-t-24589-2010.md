---
title: '(CHN) Key tasks: Set up and export financial information for GB/T 24589-2010'
TOCTitle: '(CHN) Key tasks: Set up and export financial information for GB/T 24589-2010'
ms:assetid: e9cea1b1-7aae-4944-865b-cfd3ba129843
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ670114(v=AX.60)
ms:contentKeyID: 49478306
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- CN - 00003
---

# (CHN) Key tasks: Set up and export financial information for GB/T 24589-2010 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use these procedures to create a GB/T 24589-2010 report. You set up parameters and reporting schemas to export the business information for a selected fiscal period to XML files. You can validate the structure and information in the XML files before you send the GB/T 24589-2010 report to the authorities.

You can use the XML files to export the following records to a GB/T 24589-2010 report:

  - Master records, such as a vendor list, customer list, and chart of accounts

  - Customer and vendor transactions, such as sales and purchases

  - Ledger account balances

  - Fixed asset transactions that include depreciation


> [!NOTE]
> <P>To use this feature, you must install an XML editor application.</P>



## What do you want to do?

Set up parameters to export information

Export information to a report

## Set up parameters to export information

1.  Click **General ledger** \> **Setup** \> **Organization** \> **GB/T 24589-2010**.

2.  In the **GB/T 24589-2010 parameters** form, click the **GB/T 24589-2010** link. On the **General** FastTab, enter information about your organization. This information includes the financial dimension that your organization uses to report cash flow. The organization information is displayed in the header of the GB/T 24589-2010 report.

3.  In the **Cashflow dimension** field, enter the financial dimension number that is used to report cash flow activity.

4.  In the **Format of cash flow dimension** field, enter the number format that is used for the cash flow dimension. For example, if your organization uses 1111-00-1 as the number for the cash flow dimension, the number format that you enter is 4-2-1.

5.  In the **Format of fixed asset group ID** field, enter the number format that is used for fixed asset groups. For example, if your organization uses 555-88-01 as the number format for fixed asset groups, the number format that you enter is 3-2-2.

6.  On the **Xml schema and export folder** FastTab, click **View schema** to open the **Standard data element type XML Schema** file.

7.  Review the information in the file. You cannot modify the structure in the file. Use this file to review the schema structure, and to validate the schema in your XML output files before you submit the report to the authorities.

8.  Repeat steps 3 and 4 for the remaining XML files.

9.  Select the **Export accounts receivable and payable data** check box if you want to export customer and vendor transactions.

10. Select the **Export fixed asset data** check box if you want to export fixed asset transactions, such as purchases, disposals, and depreciation.

11. In the **Export XML files to** field, select the location in which to store the current XML files. Save the current files in the selected location.

12. Click the **Financial statements** link. Select a financial statement for your organization to map to the financial statements on the GB/T 24589-2010 report.

13. Click the **Fixed assets** link. Select the ledger accounts that you use to record fixed asset transactions. The transactions in these accounts are displayed in the fixed assets section of the GB/T 24589-2010 report.

Back to top

## Export information to a report

1.  Click **General ledger** \> **Periodic** \> **China** \> **GB/T 24589 Export**.

2.  On the **General** FastTab, select the fiscal year and period for which to export financial information. By default, the current fiscal year and period are displayed. You can modify the fiscal year and period.

3.  The **Export to** field displays the location of the XML files that contain your organization’s financial information for the specified fiscal year and period. The location is selected in the **GB/T 24589-2010 parameters** form.

4.  Click the **GBT preview** button to review the financial information in the report before you send the report to the authorities.

5.  On the **Batch** tab, you can set up a recurring job to create the GB/T 24589-2010 report. For example, you can set up a batch job to create the report after you close a fiscal period. For more information about how to set up a batch job, see [Submit a batch processing job from a form](submit-a-batch-processing-job-from-a-form.md).

Back to top

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

