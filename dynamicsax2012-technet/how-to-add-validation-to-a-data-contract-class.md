---
title: 'How to: Add Validation to a Data Contract Class'
TOCTitle: 'How to: Add Validation to a Data Contract Class'
ms:assetid: 754849b3-e4fb-4934-b549-67eb77e79469
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg731942(v=AX.60)
ms:contentKeyID: 35132876
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Add Validation to a Data Contract Class 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If you want to provide additional validation, you can implement the [SysOperationValidatable](https://technet.microsoft.com/en-us/library/gg963711\(v=ax.60\)) interface that provides a validate method for a data contract. This topic describes how to validate a data contract class for the following scenarios:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Type of Data Contract</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Report Definition Language (RDL) Data Contract</p></td>
<td><p>A report is bound to a query, data method, or OLAP data source and validation logic must be added for the parameters.</p></td>
</tr>
<tr class="even">
<td><p>Report data provider (RDP) Data Contract</p></td>
<td><p>A report is bound to an RDP class and validation logic must be added for the parameters.</p></td>
</tr>
</tbody>
</table>


## Adding Validation to RDL Data Contracts

For RDL data contracts, the [SrsReportRdlDataContract](https://technet.microsoft.com/en-us/library/gg939600\(v=ax.60\)) class implements default validation that will do basic parameter validation. It will also validate the company and culture parameters. When you override this class, first call the super() method to allow the base class to validate, and then implement your validation logic. It is required to specify the SrsReportNameAttribute attribute using the following syntax SrsReportNameAttribute(ssrsreportstr(\<report\>, \<design\>)). The SysOperationContractProcessingAttribute attribute is optional. Supply the SysOperationContractProcessingAttribute attribute to use a custom UI builder with the contract class. Otherwise, the framework UI builder will be used to render the UI for dealing with the parameters when the report is run.

### To add validation to an RDL data contract

1.  In the Microsoft Dynamics AX Development Workspace, open the AOT. Right-click the **Classes** node and then click **New Class**.

2.  Double-click the new class to open the **classDeclaration** in Code Editor.

3.  An RDL data contract must extend the [SrsReportRdlDataContract](https://technet.microsoft.com/en-us/library/gg939600\(v=ax.60\)) class and implement the [SysOperationValidatable](https://technet.microsoft.com/en-us/library/gg963711\(v=ax.60\)) interface. The naming convention is \[ReportName\]RDLContract. The following code example illustrates the classDeclaration of the Hcmi9DocumentExpireListRdlContract data contract class that is used for the HCM i9 document expire list report. The FromDate and ToDate are examples using date effectivity.
    
        /// <summary>
        /// The <c>Hcmi9DocumentExpireListRdlContract</c> class is the <c>RdlContract</c> class for the
        /// <c>Hcmi9DocumentExpireList</c> report.
        /// </summary>
        [
            SrsReportNameAttribute('Hcmi9DocumentExpireList.Report'),
            SysOperationContractProcessingAttribute(classStr(Hcmi9DocumentExpireListUIBuilder))
        ]
        class Hcmi9DocumentExpireListRdlContract extends SrsReportRdlDataContract implements SysOperationValidatable
        {
            #define.parameterFromDate('FromDate')
            #define.parameterToDate('ToDate')
        } 

4.  In the AOT, right-click the new class you created, point to **New**, and then click **Method**.

5.  In the Code Editor, provide validation logic for the parameters. The following example illustrates the validation logic for the Hcmi9DocumentExpireListRdlContract data contract class parameters.
    
        /// <summary>
        /// Validates the parameters.
        /// </summary>
        /// <returns>
        /// true if successful; otherwise, false.
        /// </returns>
        public boolean validate()
        {
            boolean isValid = super();
            // Check whether FromDate and ToDate parameters are getting values or not
            if(this.getValue(#parameterFromDate) && this.getValue(#parameterToDate) )
            {
                // Check whether FromDate is greater than ToDate or not
                if (this.getValue(#parameterFromDate) > this.getValue(#parameterToDate))
                {
                    error("@SYS91020");
                    isValid = false;
                }
            }
            return isValid;
        }

## Adding Validation to RDP Data Contracts

For RDP data contracts, implement the validate method and return True or False to indicate whether the parameter is valid. It is required to attach the DataContractAttribute attribute. The SysOperationContractProcessingAttribute attribute is optional. Attach the SysOperationContractProcessingAttribute attribute to use a custom UI builder with the contract class. Otherwise, the framework UI builder will be used to render the UI for dealing with the parameters when the report is run. To report a validation error, use the error method and write to the infolog. The error messages in the infolog will be marshaled from the service to the client and then rendered. Do not throw an error.

### To add validation to an RDP data contract

1.  In the Microsoft Dynamics AX Development Workspace, open the AOT. Right-click the **Classes** node and then click **New Class**.

2.  Double-click the new class to open the **classDeclaration** in Code Editor.

3.  An RDP data contract must implement the [SysOperationValidatable](https://technet.microsoft.com/en-us/library/gg963711\(v=ax.60\)) interface. The naming convention is \[ReportName\]Contract. The following code example illustrates the classDeclaration of the AssetDueReplacementContract data contract class that is used for the asset due replacement report.
    
        /// <summary>
        /// The <c>AssetDueReplacementContract</c> class is used as the data contract for the <c>AssetDueReplacement</c> SSRS report.
        /// </summary>
        [
            DataContractAttribute,
            SysOperationContractProcessingAttribute(classStr(AssetDueReplacementUIBuilder))
        ]
        public class AssetDueReplacementContract implements SysOperationValidatable
        {
            CurrentOperationsTax postingLayer;
            AssetReplacementDate dateFrom;
            AssetReplacementDate dateTo;
            Name dimension;
            NoYes includeSubTotal;
        }

4.  In the AOT, right-click the new class you created, point to **New**, and then click **Method**.

5.  In the Code Editor, provide validation logic for the parameters. The following example illustrates the validation logic for the AssetDueReplacementContract data contract class parameters.
    
        /// Determines whether the parameters are valid.
        /// </summary>
        /// <returns>
        /// true when the parameters are valid; otherwise, false.
        /// </returns>
        public boolean validate()
        {
            boolean isValid = true;
            if (!dateFrom)
            {
                isValid = checkFailed(strFmt("@SYS84753", "@SYS180311"));
            }
            if (!dateTo)
            {
                isValid = checkFailed(strFmt("@SYS84753", "@SYS180217"));
            }
            if (dateFrom > dateTo)
            {
                isValid = checkFailed(strFmt("@SYS300457", date2StrUsr(dateFrom, DateFlags::FormatAll), date2StrUsr(dateTo, DateFlags::FormatAll)));
            }
            return isValid;
        }

For more information and examples, see the [Report Programming Guide](http://go.microsoft.com/fwlink/?linkid=230569).

