---
title: 'Example: Create a Report with a Group Check Box'
TOCTitle: 'Example: Create a Report with a Group Check Box'
ms:assetid: 3acb567c-4933-4584-a6db-bcd092bb556a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn720903(v=AX.60)
ms:contentKeyID: 62235870
ms.date: 05/01/2014
mtps_version: v=AX.60
---

# Example: Create a Report with a Group Check Box 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

The following example provides information about how the **BOMPartOf** report was converted to use the current report programming model. This report provides an example of a report that requires a group check box in the UI.

## Example: BOMPartOf

  - The BOMPartOf report was migrated to the current report programming model.

  - An RDP contract was created.

  - The UI builder was used together with overrides so that the UI includes a group check box.

Before the conversion, the helper class did the following:

  - Add the fields to the dialog box.

  - Get the fields from the dialog box.

  - Set the report parameters.

  - Provide the grouping.

## Implementation

To see the full implementation, in the development workspace, click **AOT \> Classes \> BOMPartOfUIBuilder**. The following code illustrates how to create a form group control, and how to use the control in the build method, the [getFromDialog](https://technet.microsoft.com/en-us/library/gg745384\(v=ax.60\)) method, and the [getSearchIntervalFromDialog](https://technet.microsoft.com/en-us/library/gg745385\(v=ax.60\)) method.

    public void build() 
    { 
        FormBuildGroupControl formBuildGroupControl; 
        super(); 
        formBuildGroupControl = this.dialog().curFormGroup(); 
        formBuildGroupControl.columns(2); 
    } 
    public void getFromDialog() 
    { 
        super(); 
        this.getSearchIntervalFromDialog(this.dialog()); 
    } 
    protected void getSearchIntervalFromDialog(Dialog _dialog) 
    { 
        BOMPartOfContract contract = this.dataContractObject(); 
        FormGroupControl dialogSearchIntervalGroup = _dialog.formRun().control(_dialog.formRun().controlId('Date')); 
        contract.parmSearchInterval(dialogSearchIntervalGroup.optionValue()); 
    }

The following code illustrates the contract for the BOMPartOf report.

    [ 
        DataContractAttribute, 
        SysOperationContractProcessingAttribute(classstr(BOMPartOfUIBuilder),     
    SysOperationDataContractProcessingMode::CreateUIBuilderForRootContractOnly), 
        SysOperationGroupAttribute('Date', "@SYS25853", '4'), 
        SysOperationGroupAttribute('ViewGroup', "@SYS5252", '5') 
    ] 
    public class BomPartOfContract 
    { 
    ...

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

