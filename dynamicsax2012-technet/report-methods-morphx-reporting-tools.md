---
title: Report Methods (MorphX Reporting Tools)
TOCTitle: Report Methods
ms:assetid: ae286ec1-a332-4f1c-86bc-25368207a9e9
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa854897(v=AX.60)
ms:contentKeyID: 35290319
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Report Methods (MorphX Reporting Tools) 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can override a report method in the Application Object Tree (AOT). To override a report method in the AOT, click the report to expand its node, right-click the **Methods** node, and then click **Override Method**. To add a report method in the AOT, click the report to expand its node, right-click the **Methods** node, and then click **New Method**.


> [!NOTE]
> <P>Whenever possible, write your code in the underlying table instead of in the report. Methods written in a table are available to any report that uses that table as a data source.</P>



## Methods That Can Be Overridden

Each report in the AOT has child nodes named **Data Sources** and **Designs**. These nodes have references to the member objects of the report. They can be manipulated in overridden methods.

The following table describes the report methods that you can override.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Method</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>callMenuFunction</p></td>
<td><p>A Web method.</p></td>
</tr>
<tr class="even">
<td><p>caption</p></td>
<td><p>Creates a caption when previewing a report, or a document name when printing a report.</p></td>
</tr>
<tr class="odd">
<td><p>createProgressForm</p></td>
<td><p>Called when the fetch method is being executed. This presents a progress indicator to the user, which is visible until all the data has been fetched and can be displayed. For reports that are only one page long, the progress indicator does not appear.</p>
<p>This method opens the SysPrintProgress form. You can override this method to use a different form.</p></td>
</tr>
<tr class="even">
<td><p>dialog</p></td>
<td><p>Does nothing. This method can be overridden to add fields to the <strong>Reports</strong> dialog box.</p></td>
</tr>
<tr class="odd">
<td><p>fetch</p></td>
<td><p>Fetches records from the database. The fetch method instantiates a query, opens the query prompt, and then fetches the records.</p>
<p>During the execution of the fetch method, the next and get methods are executed in pairs on the query of the report. The send, the header and/or footer methods, and the progressInfo method are then executed. The cycle continues with calls to next, get, and so on, until all the data has been fetched.</p>
<p>The following are reasons for overriding the fetch method:</p>
<ul>
<li><p>The report is not based on a query.</p></li>
<li><p>Some of the fetched data must be processed (this can also be done on the send method).</p></li>
<li><p>The report is based on a temporary table.</p></li>
</ul>
<p>For more information, see <a href="how-to-override-the-fetch-method-to-filter-data-for-reports-morphx-reporting-tools.md">How to: Override the fetch Method to Filter Data for Reports (MorphX Reporting Tools)</a>.</p></td>
</tr>
<tr class="even">
<td><p>footer</p></td>
<td><p>If overridden, you can execute code before, after, or instead of printing the footer of the report.</p></td>
</tr>
<tr class="odd">
<td><p>getDeclineOverwrite</p></td>
<td><p>Determines whether to overwrite the existing output file when a user tries to save the report. This method is called by the form.</p></td>
</tr>
<tr class="even">
<td><p>getReportViewer</p></td>
<td><p>Gets a ReportViewer instance.</p></td>
</tr>
<tr class="odd">
<td><p>getTarget</p></td>
<td><p>Called by the SysPrintForm form when a user changes the print medium. Use the return value to detect the selected print medium.</p></td>
</tr>
<tr class="even">
<td><p>header</p></td>
<td><p>If overridden, you can execute code before, after, or instead of printing the header of the report.</p></td>
</tr>
<tr class="odd">
<td><p>init</p></td>
<td><p>Initializes the report and its objects. This is the earliest method that can be overridden among those executed when a report is constructed and run.</p>
<p>Override this method to add initialization tasks, such as the following:</p>
<ul>
<li><p>Validation of the argument objects received</p></li>
<li><p>Initialization of supporting classes</p></li>
<li><p>Dynamic changes to the design</p></li>
</ul>
<p>If your changes require access to the objects of the report, add your code after the super() call.</p>
<div class="alert">

> [!WARNING]
> <P>Do not delete the super() call from this method. The super() call initializes all the objects of the report.</P>


</div></td>
</tr>
<tr class="even">
<td><p>new</p></td>
<td><p>Used to instantiate an instance of the ReportRun class. The new method is a constructor.</p></td>
</tr>
<tr class="odd">
<td><p>pack</p></td>
<td><p>Packs the report into a container. The pack method returns the container. This method can be overridden to reduce the amount of the report that is packed.</p>
<p>The packed report can then be sent between the client and server platforms, unpacked, and executed. The ReportRun class has several methods that are marked final. They are named in the patterns of pack* and unpack*.</p></td>
</tr>
<tr class="even">
<td><p>pageFormatting</p></td>
<td><p>Displays the printer properties of the actual printer. However, the pageFormatting method is obsolete and is no longer used. Calls are made instead to this method on the PrintJobSettings class.</p></td>
</tr>
<tr class="odd">
<td><p>print</p></td>
<td><p>Prints the report to the selected print medium, such as a printer, file, or screen.</p></td>
</tr>
<tr class="even">
<td><p>printerSettings</p></td>
<td><p>Enables the user to select printer settings.</p>
<p>Executes when <strong>Printer Settings</strong> is selected in the shortcut menu or in the SysPrintForm form.</p></td>
</tr>
<tr class="odd">
<td><p>progressInfo</p></td>
<td><p>Updates the progress form with page and line numbers.</p>
<p>Override this method to add another progress indicator of the report evaluation progress.</p></td>
</tr>
<tr class="even">
<td><p>prompt</p></td>
<td><p>Prompts the user to select a print medium and other information.</p>
<p>Available mediums include paper, the screen, a print archive, .rtf, HTML, ASCII, .pdf, and text (UTF-8).</p>
<p>To disable the print medium selection, override the method, and then remove the call to super().</p>
<div class="alert">

> [!WARNING]
> <P>Do not mistake this method for the method of the same name on a query.</P>


</div></td>
</tr>
<tr class="odd">
<td><p>run</p></td>
<td><p>Runs the report. This method is executed when the user clicks <strong>OK</strong> on the preliminary specification dialog box of the report (which enables the user to select where to send the report, and so on).</p>
<p>The default version of this method does the following in the sequence shown:</p>
<ol>
<li><p>Calls prompt.</p></li>
<li><p>Creates a basic design if it does not already exist.</p></li>
<li><p>Arranges the fields.</p></li>
<li><p>Calls fetch.</p></li>
<li><p>Calls print.</p></li>
</ol></td>
</tr>
<tr class="even">
<td><p>send</p></td>
<td><p>Sends one fetched record to the body sections in the report.</p>
<p>Override this method if you want to change each record, but you do not want to override the fetch method.</p>
<p>The send method calls the progressInfo method.</p></td>
</tr>
<tr class="odd">
<td><p>setTarget</p></td>
<td><p>Executed by the SysPrintForm form when the print medium is changed.</p>
<p>Use this method to select the print medium or the return value to detect the selected medium.</p></td>
</tr>
<tr class="even">
<td><p>showMenuFunction</p></td>
<td><p>A Web method.</p></td>
</tr>
<tr class="odd">
<td><p>showMenuReference</p></td>
<td><p>A Web method.</p></td>
</tr>
<tr class="even">
<td><p>title</p></td>
<td><p>Gets or sets the title of the report.</p></td>
</tr>
</tbody>
</table>

