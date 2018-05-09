---
title: Troubleshoot Issues with Printing and Emailing Reports
TOCTitle: Troubleshoot Issues with Printing and Emailing Reports
ms:assetid: 58f3022d-37cf-4995-8443-573f7b8025d9
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn275971(v=AX.60)
ms:contentKeyID: 54628731
ms.date: 09/18/2013
mtps_version: v=AX.60
---

# Troubleshoot Issues with Printing and Emailing Reports 


This topic provides guidance and workarounds for problems using the **Print ranges**, **Group totals**, and **Print grand totals** print options, formatting dates and numbers, and emailing archived reports. The way to implement these options is different in Microsoft Dynamics AX 2012 than in Microsoft Dynamics AX 2009.

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>In this topic</strong></p>
<p>Printing ranges and totals</p>
<ul>
<li><p>Print Ranges</p></li>
<li><p>Group totals</p></li>
<li><p>Print Grand totals</p></li>
</ul>
<p>Formatting dates and numbers</p>
<ul>
<li><p>Date format correct in header but incorrect in report body</p></li>
<li><p>Currency or number format incorrect in report body</p></li>
</ul>
<p>Emailing reports</p>
<ul>
<li><p>Emailing archived reports</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Print Ranges

Microsoft Dynamics AX 2009 provided UI for defining **Print ranges** and **Print grand totals options** in the **Print option** tab of a query form.

In Microsoft Dynamics AX 2012 reports are designed using SSRS. Here the design of the reports is static. Changes to the report body cannot be applied dynamically as seen in Microsoft Dynamics AX 2009. The above features are removed from the options for displaying reports. Instead, you can define print ranges programmatically.

The following steps walk you through an example of how to implement print ranges for a report in Microsoft Dynamics AX 2012.

### Print Range Implementation in Microsoft Dynamics AX 2012

1.  Open the AOT and expand the node for the report under **\\Visual Studio Projects\\Dynamics AX Model Projects\\**. The following image shows the report object for the report AssetListing.
    
    ![Initial report body](images/Dn275971.InitialReportBody(AX.60).png "Initial report body")

2.  Right-click on the report object and click Edit to open the SSRS report design. The following image shows columns that can be used to form ranges.
    
    ![initial report design](images/Dn275971.InitialReportDesign(AX.60).png "initial report design")

3.  In this example, we will specify three ranges for the report:
    
    1.  AssetGroup
    
    2.  AssetId
    
    3.  BookId
    
    The values for these ranges are to be captured and passed on to the report. For this purpose we create three dummy parameters in the parameter section of the report. These parameters should not be shown on the parameter dialog. The **Visible** property for the parameters is set to false. They are only used to receive the range values from the **sysQuery** form.
    
    ![Parameters used to implement ranges](images/Dn275971.ImplementationOfPrintRanges(AX.60).png "Parameters used to implement ranges")

4.  Use a controller class to get range values from the **SysQuery** form. In this example it is named AssetListingController.
    
    ![AssetListingController](images/Dn275971.AssetListingController(AX.60).png "AssetListingController")
    
    In the method PreRunModifyContract we define code for getting range values from the query and assign these values to the range parameters created in the report. The properties of the menu item **AssetListing** used for this report should be modified as shown in the following.
    
      - \\Classes\\AssetListingController\\classDeclaration
        
            public class AssetListingController extends SrsReportRunController
            {
                SrsReportRdlDataContract rdlContract;
            }
    
      - \\Classes\\AssetListingController\\main
        
            public static void main(Args _args)
            {
                SrsReportRunController controller = new AssetListingController();
                controller.parmArgs(_args);
                controller.parmReportName(ssrsReportStr(AssetListing, Report));
                controller.startOperation();
            }
    
      - \\Classes\\AssetListingController\\preRunModifyContract
        
            protected void preRunModifyContract()
            {
                #define.AssetGroupParm   (‘AssetGroup’)
                #define.AssetIdParm    (‘AssetId’)
                #define.BookIdParm     (‘BookId’)
                #define.Blank          (‘’)
            
                Query   query;
                QueryBuildRange   queryBuildRange;
                QueryBuildDataSource    queryBuildDataSource;
            
                // Initializizing the SrsReportRdlDataContract object.
                // This is used for getting parameters in the report definition.
                rdlContract = this.parmReportContract().parmRdlContract() as SrsReportRdlDataContract;
            
                // Clearing off the older values from the report parameters.
                rdlContract.setValue(#AssetGroupParm, #Blank);
                rdlContract.setValue(#AssetIDParm, #Blank);
                rdlContract.setValue(#BookIDParm, #Blank);
            
                // Getting the query used for the report.
                query = this.getFirstQuery();
            
                // Getting range values for the Fixed Asset group.
                queryBuildDataSource     = query.dataSourceTable(tableNum(AssetTable));
                queryBuildRange          = queryBuildDataSource.findRange(fieldNum(AssetTable, AssetGroup));
            
                // Setting the range values to the AssetGroup parameter in the report.
                if (queryBuildRange.value())
                {
                    rdlContract.setValue(#AssetGroupParm, queryBuildRange.value());
                }
            
                // Getting range values for the Fixed Asset number.
                queryBuildRange = queryBuildDataSource.findRange(fieldNum(AssetTable, AssetId));
            
                // Setting the range values to the AssetId parameter in the report.
                if (queryBuildRange.value())  
                {
                    rdlContract.setValue(#AssetIdParm, queryBuildRange.value());   
                }
                // Getting range values for the Book range.
                queryBuildDataSource   = query.dataSourceTable(tableNum(AssetBookMerge));
                queryBuildRange        = queryBuildDataSource.findRange(fieldNum(AssetBookMerge, BookId));
            
                // Setting the range values to the BookId parameter in the report.
                if (queryBuildRange.value())
                {
                    rdlContract.setValue(#BookIdParm, queryBuildRange.value());
                }
            }
        
        ![AssetListing menu item](images/Dn275971.MenuItemAssetListing(AX.60).png "AssetListing menu item")

5.  In the report body design, use textboxes to display the Range parameter values.
    
    ![AssetListing report body design](images/Dn275971.AssetListingReport(AX.60).png "AssetListing report body design")

6.  To control the display of the ranges on the report, we create a Boolean parameter named PrintRanges on the report. The visibility of the textboxes is toggled by setting this parameter to true or false.
    
    ![PrintRanges parameter for AssetListing report](images/Dn275971.AssetListingPrintRanges(AX.60).png "PrintRanges parameter for AssetListing report")


> [!NOTE]
> <P>We cannot add ranges dynamically to the sysQuery form. Whatever ranges are present initially will be considered and accordingly parameters are added to the report. Dynamic addition of parameters to SSRS report is not supported.</P>



## Group Totals

If no grouping is automatically provided for a report, introduce groupings into the report design according to your requirements. The options for grouping the report can be specified by grouping on fields like the following:

1.  Fixed asset group

2.  Fixed asset number

3.  Book

We have taken these values as these are the ranges for the report. Usually the fields used for ranges are used for sorting and grouping. We have to create three Boolean parameters corresponding to the above three grouping fields.

![Asset listing report with group totals](images/Dn275971.AssetListingGroupTotals(AX.60).png "Asset listing report with group totals")

In the report design, create three groupings on the existing table.

The grouping hierarchy should follow the parameter hierarchy, which is the order in which the above parameters are displayed.

![Asset listing report design grouping hierarchy](images/Dn275971.AssetListingReportGroupingHierarchy(AX.60).png "Asset listing report design grouping hierarchy")

1.  As per the above screenshot, set Row Visibility expression for 1
    
        =iif(Parameters!FixedAssetGroup.Value = false and Parameters!FixedAssetNumber.Value = false and Parameters!Book.Value = false, false, true)

2.  As per the above screenshot, set Row Visibility expression for 2
    
        =iif(Parameters!FixedAssetGroup.Value = true and Parameters!FixedAssetNumber.Value = false and Parameters!Book.Value = false, false, true)

3.  As per the above screenshot, set Row Visibility expression for 3
    
        =iif(Parameters!FixedAssetNumber.Value = true and Parameters!Book.Value = false, false, true)

4.  As per the above screenshot, set Row Visibility expression for 4
    
        =iif(Parameters!Book.Value = true, false, true)

The grouping should be based on the chosen parameter. A sample expression for grouping is given as:

    =iif(Parameters!FixedAssetGroup.Value = true, Fields!AssetGroup.Value,1)

If the corresponding checkbox is checked, the grouping should be done on the corresponding value. Otherwise no grouping should be done. In the expression the value “1” is used for no grouping since it is a constant value.

The group headers are used to display the information as the value on which the data is grouped.

The group footers are used to display the value and the total values for the amount columns. In this way, grouping totals can be implemented.


> [!NOTE]
> <P>We cannot specify grouping fields dynamically to the sysQuery form. Whatever fields present initially will be considered and accordingly parameters are added to the report. Dynamic addition of parameters to SSRS report is not supported. This feature can be implemented only for reports which do not have any grouping defined in the design. Simple reports without groupings can make use of this option. This behavior is seen in Microsoft Dynamics AX 2009 reports. This is limitation for both Microsoft Dynamics AX 2009 and Microsoft Dynamics AX 2012 reports.</P>



## Print Grand Totals

In the report design, create a Boolean parameter named GrandTotal.

![Asset listing group total parameters](images/Dn275971.AssetListingGrandTotal1(AX.60).png "Asset listing group total parameters")

Edit the report design and create a static row at the bottom of the tablix. This serves as table footer. Use the summation expression for amounts to get the Grand total.

The summation expression for calculating grand totals is as follows:

    =sum(Fields!assetNetBookValue.Value)

Manage the visibility of the row by using the GrandTotal parameter. If it is checked, this parameter makes the row visible. Otherwise, the row is hidden.

![Asset listing group total design](images/Dn275971.AssetListingGrandTotal2(AX.60).png "Asset listing group total design")

The parameter dialog for the AssetListing report, without adding options for print ranges, grand totals, or group totals, is shown here:

![Asset listing group total design](images/Dn275971.AssetListingGrandTotal3(AX.60).png "Asset listing group total design")

The parameter dialog for the AssetListing report, including additional options for print ranges, grand totals and group totals, is show here:

![Asset listing group total design](images/Dn275971.AssetListingGrandTotal4(AX.60).png "Asset listing group total design")

Display the report on the screen by providing values for the above options on the Query form.For example, for Range, select fixed asset group as COMP and Fixed asset number as “COMP-001..COMP-002” and mark check box “Print ranges” under the “Print Options” group. Mark “Print grand total” checkbox under the “Print Options” group for printing the grand total in the report. Also, for Group totals check the checkbox for fixed asset number under the “Group totals” group. The following image calls out the values to provide.

![Asset listing group total design](images/Dn275971.AssetListingGrandTotal5(AX.60).png "Asset listing group total design")

The following image calls out the values as displayed in the report output.

![Asset listing group total design](images/Dn275971.AssetListingGrandTotal6(AX.60).png "Asset listing group total design")

## Date and Number Format Issues

The date and number format in an application are controlled by system local settings (Control Panel \> Region and language) and the date and number format in SSRS reports is controlled by the AX\_RenderingCulture parameter, which takes its value from the user’s AX language (specified in File \>Tools \> Options \> General \> Options \> Language). In parallel, the user’s language will also be controlled by system local settings.

This section contains workarounds for known issues affecting date and number formatting in reports in Microsoft Dynamics AX 2012.

## Date Format correct in header but incorrect in report body

The solution to this issue is as follows:

### Steps using VendInvoiceReport as an example

1.  Open AOT and expand node **\\Visual Studio Projects\\Dynamics AX Model Projects\\VendInvoiceReport**. Right click on this object and click **Edit** to open the Vend Invoice SSRS report design.

2.  Select the field design and set expression. Use the following expression for Date fields, using ToDisplayStringDate.
    
        =Microsoft.Dynamics.Framework.Reports.BuiltInMethods.ToDisplayStringDate(Parameters!AX_RenderingCulture.Value, Date Field value, "d")

![Expression for Date fields](images/Dn275971.ReportTroubleshootDateSolution(AX.60).png "Expression for Date fields")

## Currency or Number Format correct in total but incorrect in report body

The solution to this issue is as follows:

### Steps using VendInvoiceReport as an example

1.  Open AOT and expand node **\\Visual Studio Projects\\Dynamics AX Model Projects\\VendInvoiceReport**. Right click on this object and click **Edit** to open the Vend Invoice SSRS report design.

2.  Select the field design and set expression. Use the following expression for fields using symbols like the dot (.) and the comma (,), using ToDisplayStringAmount.
    
        =Microsoft.Dynamics.Framework.Reports.BuiltInMethods.ToDisplayStringAmount(Parameters!AX_RenderingCulture.Value,                            Amount Field value, true)

## Emailing Archived Reports

An example of a known issue with emailing archived reports can be seen with the Invoiced Sales Order report. If the user opens an Invoiced Sales Order and then opens the SO Invoiced report, there is no option available to send the report through email or to save it locally.

To work around this issue, export the SSRS report in PDF format (or any format) then attach it to an email. The user can send the file as an attachment.This can also be achieved through functionality in Microsoft Dynamics AX 2012 using the following steps:

### Steps

1.  **Open CEU \> Accounts receivable \> Setup \> Forms \> Form** setup

2.  Click on the **Print management** button to open the Print management setup form.

3.  Click on **Destinations \> Printer setup** – Here user has all the options to email the report, save the report locally, or send the report to the screen or printer.

4.  Open Invoiced Sales order. Click on Invoice journal for that Sales order. Here you can see there are 3 options are available (**Copy Preview**, **Original preview** and **Use print management**). Click on **Use print management** to get the expected report according to your current setting that specifies whether to email the report, save the report locally, or send the report to the screen or printer.

