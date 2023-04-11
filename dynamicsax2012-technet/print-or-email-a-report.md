---
title: Print or email a report
TOCTitle: Print or email a report
ms:assetid: 614c67f4-a516-474d-adb8-2c50fd239547
ms:mtpsurl: https://technet.microsoft.com/library/Gg231521(v=AX.60)
ms:contentKeyID: 35132858
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- report
- reports
audience: Application User
ms.search.region: Global
---

# Print or email a report 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft Dynamics AX includes hundreds of preconfigured reports that you can use to view and analyze business data. The following procedure explains how to print a report.

1.  Open the module that contains the data to print.

2.  On the module’s area page, in the **Reports** section, click the report to print.

3.  A form is displayed, where you can enter parameters to filter the data that is displayed on the report. Enter any parameters that you require. For more information about how to enter parameters to filter the data, see [Filter the data on a report](filter-the-data-on-a-report.md).

4.  Click **Destinations ...**. The **Print destination settings** form is displayed.

5.  Select the destination to print the report to. The following table lists the options and describes the additional steps that you must follow for each option.
    
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
    <li><p>In the <strong>Page range</strong> area, specify the pages of the report to print.</p></li>
    <li><p>Click <strong>OK</strong> to close the <strong>Print destination settings</strong> form.</p></li>
    </ol>
    <p>For information about how to print a report from the archive, see <a href="print-a-report-from-the-archive.md">Print a report from the archive</a>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Screen</strong></p></td>
    <td><ol>
    <li><p>If you want to save a copy of the report in the print archive, select the <strong>Save in print archive?</strong> check box.</p></li>
    <li><p>In the <strong>Page range</strong> area, specify the pages of the report to print.</p></li>
    <li><p>Click <strong>OK</strong> to close the <strong>Print destination settings</strong> form.</p></li>
    </ol>
    <div class="alert">

    > [!NOTE]
    > <P>For the best viewing experience, we recommend that you set the text size on your computer to <STRONG>Smaller – 100% (default)</STRONG> in the Control Panel. If the text size is larger than 100%, you may not be able to view all the data on the report.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Printer</strong></p></td>
    <td><ol>
    <li><p>If you want to save a copy of the report in the print archive, select the <strong>Save in print archive?</strong> check box.</p></li>
    <li><p>In the <strong>Name</strong> field, select the printer to print to.</p></li>
    <li><p>Click <strong>Properties</strong> to configure options for the printer. Note the following points:</p>
    <ul>
    <li><p><strong>For those using Microsoft Dynamics AX 2012 or Microsoft Dynamics AX 2012 Feature Pack:</strong> If you change the page layout orientation or the paper size, your change will not be honored when the report is printed.</p></li>
    <li><p><strong>For those using Microsoft Dynamics AX 2012 R2 or later:</strong> If you change the page layout orientation or the paper size, you must select the <strong>Override default settings</strong> check box for your changes to take effect.</p></li>
    </ul></li>
    <li><p>In the <strong>Page range</strong> area, specify the pages of the report to print.</p></li>
    <li><p>In the <strong>Copies</strong> area, enter the number of copies to print.</p></li>
    <li><p>Click <strong>OK</strong> to close the <strong>Print destination settings</strong> form.</p></li>
    </ol></td>
    </tr>
    <tr class="even">
    <td><p><strong>File</strong></p></td>
    <td><ol>
    <li><p>If you want to save a copy of the report in the print archive, select the <strong>Save in print archive?</strong> check box.</p></li>
    <li><p>In the <strong>File name</strong> field, enter the name and location of the file to save the report to.</p></li>
    <li><p>In the <strong>File format</strong> field, select the format of the file that the report is saved to.</p></li>
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


6.  Click **OK** to print the report to the selected destination.

  


