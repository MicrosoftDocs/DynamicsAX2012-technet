---
title: Print or email a report during off-peak hours
TOCTitle: Print or email a report during off-peak hours
ms:assetid: 2b3f8c73-b99c-47db-b615-6859dd13a998
ms:mtpsurl: https://technet.microsoft.com/library/Gg731911(v=AX.60)
ms:contentKeyID: 35132834
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Print or email a report during off-peak hours 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Occasionally, you may have to print an especially long report, such as a report that contains hundreds of rows of data. In this case, it may be best to print the report during off-peak hours, when few users are logged on to Microsoft Dynamics AX. The following procedure explains how to schedule a report to be printed during off-peak hours.

1.  Open the module that contains the data to print.

2.  On the module’s area page, in the **Reports** section, click the report to print.

3.  A form is displayed, where you can enter parameters to filter the data that is displayed on the report. Enter the parameters that you require. For more information about how to enter parameters to filter the data, see [Filter the data on a report](filter-the-data-on-a-report.md).

4.  Click **Destinations ...**. The **Print destination settings** form is displayed.

5.  Select the destination to print the report to. The following table lists the options and the additional steps that you must follow for each option.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Print destination</p></th>
    <th><p>Additional steps</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Print archive</strong></p></td>
    <td><ol>
    <li><p>In the <strong>Page range</strong> area, specify which pages of the report to print.</p></li>
    <li><p>Click <strong>OK</strong> to close the <strong>Print destination settings</strong> form.</p></li>
    </ol>
    <p>For information about how to print a report from the archive, see <a href="print-a-report-from-the-archive.md">Print a report from the archive</a>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Screen</strong></p></td>
    <td><p>Do not select this option. Because this report is printed as part of a batch, do not print the report to the screen.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Printer</strong></p></td>
    <td><ol>
    <li><p>If you want to save a copy of the report in the print archive, select the <strong>Save in print archive?</strong> check box.</p></li>
    <li><p>In the <strong>Name</strong> field, select the printer to print to.</p></li>
    <li><p>Click <strong>Properties</strong> to configure options for the printer. Note the following points:</p>
    <ul>
    <li><p><strong>For those using Microsoft Dynamics AX 2012 or Microsoft Dynamics AX 2012 Feature Pack:</strong> If you change the page layout orientation or the paper size, your change will not be honored when the report is printed.</p></li>
    <li><p><strong>For those using Microsoft Dynamics AX 2012 R2:</strong> If you change the page layout orientation or the paper size, you must select the <strong>Override default settings</strong> check box for your changes to take effect.</p></li>
    </ul></li>
    <li><p>In the <strong>Page range</strong> area, specify the pages of the report to print.</p></li>
    <li><p>In the <strong>Copies</strong> area, enter the number of copies to print.</p></li>
    <li><p>Click <strong>OK</strong> to close the <strong>Print destination settings</strong> form.</p></li>
    </ol></td>
    </tr>
    <tr class="even">
    <td><p><strong>File</strong></p></td>
    <td><ol>
    <li><p>Create the destination file.</p>
    <p>For example, assume that you want to save the <strong>Customers</strong> report as a PDF file. In this case, you would create a file that is named Customers.pdf.</p>
    <p>You can save a report as a CSV, Microsoft Excel, HTML, image, MTHML, PDF, or XML file.</p></li>
    <li><p>If you want to save a copy of the report in the print archive, select the <strong>Save in print archive?</strong> check box.</p></li>
    <li><p>In the <strong>File name</strong> field, enter the path of the destination file. The path must be entered in the following format: <em>\\Server\Volume\Directory\File</em>.</p>
    <div class="alert">

    > [!NOTE]
    > <P>The AOS service account for the Microsoft Dynamics AX batch server must have access to the destination file.</P>


    </div></li>
    <li><p>In the <strong>File format</strong> field, select the format of the destination file.</p></li>
    <li><p>In the <strong>Page range</strong> area, specify the pages of the report to print.</p></li>
    <li><p>Click <strong>OK</strong> to close the <strong>Print destination settings</strong> form.</p></li>
    </ol></td>
    </tr>
    <tr class="odd">
    <td><p><strong>E-mail</strong></p></td>
    <td><ol>
    <li><p>If you want to save a copy of the report in the print archive, select the <strong>Save in print archive?</strong> check box.</p></li>
    <li><p>In the <strong>To</strong> and <strong>Cc</strong> fields, specify who receives the email message by entering email addresses or tokens (if supported by the version of Microsoft Dynamics AX that you’re using).</p>
    <p>If you’re using cumulative update 7 for Microsoft Dynamics AX 2012 R2 or later, you can email reports to specific people by using tokens. When you use this feature, you don’t have to enter the email addresses of all recipients. Instead, you just enter a token. The token instructs Microsoft Dynamics AX to retrieve the appropriate email addresses from worker, customer, or vendor records.</p>
    <p>To enter tokens, complete the following steps:</p>
    <ol>
    <li><p>Click the <strong>Edit</strong> button that is next to the <strong>To</strong> or <strong>Cc</strong> field. The <strong>Assign email addresses</strong> form is displayed.</p></li>
    <li><p>To email the report to workers in your organization who have a specific job title, select the job title from the <strong>Worker title</strong> list.</p>
    <p>For example, suppose that you want to email this report to all workers who have the job title of Marketing Manager. In this case, you would select Marketing Manager from the <strong>Worker title</strong> list. Or, you would enter the following token in the <strong>To</strong> and <strong>Cc</strong> fields: <strong>@Marketing Manager@</strong></p></li>
    <li><p>Click <strong>OK</strong>.</p></li>
    </ol></li>
    <li><p>In the <strong>Subject</strong> field, enter the subject of the email message.</p></li>
    <li><p>In the <strong>File format</strong> field, select the format of the file that the report is saved to. This file is attached to the email message that is sent.</p></li>
    <li><p>In the <strong>Page range</strong> area, specify the pages of the report to print.</p></li>
    <li><p>Click <strong>OK</strong> to close the <strong>Print destination settings</strong> form.</p></li>
    </ol></td>
    </tr>
    </tbody>
    </table>


6.  Click the **Batch** tab.
    
    On this tab, you configure a *batch job*. A batch job is a task that is submitted to the instance of the Microsoft Dynamics AX server for automatic processing.

7.  Select the **Batch processing** check box.

8.  In the **Task description** field, accept the default description of this batch job or enter a new description.

9.  From the **Batch group** list, select the batch group that this batch job will be a part of.

10. Click **Recurrence**. The **Recurrence** form is displayed.

11. Schedule the date and time that the report is printed by following these steps:
    
    1.  From the **Time zone** list, select your time zone.
    
    2.  In the **Starting time** field, enter the time to print the report. For example, to print the report during off-peak hours, you may want to enter 2:00 A.M.
    
    3.  In the **Starting date** field, select the day to print the report.
    
    4.  If you want to print this report on a recurring basis, specify a recurrence pattern by entering a count or a date range. Then select the days on which the report is printed.
    
    5.  Click **OK** to close the **Recurrence** form.

12. Click **Alerts**. The **Set up alerts for batch jobs** form is displayed.

13. Specify how and when you want to receive alerts for the batch job. Then click **OK** to close the **Set up alerts for batch jobs** form.

14. Click **OK** to print the report to the selected destination on a recurring basis.

  


