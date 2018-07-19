---
title: Import internal controls to the Compliance site
TOCTitle: Import internal controls to the Compliance site
ms:assetid: dd7f9677-3285-49bd-a8b3-6313b169b231
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh271671(v=AX.60)
ms:contentKeyID: 36384302
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- EPComplianceImportInternalControls
audience: Application User
ms.search.region: Global
---

# Import internal controls to the Compliance site 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

An internal controls matrix is a worksheet that is used to manage a list of compliance controls for an organization. You can save time by importing controls from an internal controls matrix in a Microsoft Excel workbook to the **Compliance** site. You can map the fields from the internal controls matrix file to the corresponding fields in document templates that are set up on the **Compliance** site. The import process automatically creates controls in the structure of the **Internal controls** site, based on your internal controls matrix. After you have imported internal controls, you can manage them on the **Internal controls** site.

## Prerequisites

Before you import the control matrix, you must follow these steps.

1.  Set up the structure of the **Internal controls** site. You must set up at least one control environment node under the **Root** node. For more information, see [Set up the Internal controls site](set-up-the-internal-controls-site.md).
    

    > [!NOTE]
    > <P>You must have <STRONG>Add/Copy</STRONG> permissions to the control environment nodes that you import data into.</P>



2.  Make sure that a document template exists for each type of control that will be imported. For more information, see [About compliance document templates](about-compliance-document-templates.md).

3.  Prepare the control matrix and upload it to the **Compliance resources** shared document library. For more information, see “Prepare the control matrix for import” later in this topic.

## Optional: Use the default controls library

A default controls library in Excel format is automatically installed in the **Compliance resources** shared documents folder. You can use the default controls library as the basis for your controls matrix file. You can either modify the file in the **Compliance resources** shared documents folder, or you can copy it, change the copy, and upload the copy to the **Compliance resources** shared documents folder.

If you use the default controls library, you must:

  - Fill in the **Environment Node** column for each row of controls that you will import.

  - Optional: Fill in the properties for the blank cells.

  - If you do not want to import all the controls, delete the controls that you do not want to import from the worksheet.

## Prepare the control matrix for import

Follow these guidelines for creating the control matrix worksheet:

  - Create the control matrix as a single worksheet in an Excel workbook, if it is possible. If necessary, you can use multiple worksheets. However, you must import each worksheet separately. Limit the file size to 4 megabytes (MB) or less.

  - Format the worksheet with each set of related controls in a separate row. The row must represent the control that is at the lowest level of the hierarchy and also all the parent-child relationships above it. For example, if you have a risk named **Credit**, a child control named **Credit term limits**, and a grandchild test plan named **Invoice review**, enter all these controls in the same row.

  - For each worksheet, include only the rows that you want to import. You cannot select a subset of the worksheet data to import.

  - Enter column headings in the first row of the worksheet.

  - Use a single column to represent control environment data. If your control environment contains two or more hierarchical nodes, such as **Region**, **Territory**, and **State**, concatenate the values into a single cell. For example, cell A2 contains **Region**, B2 contains **Territory**, and C2 contains **State**. In cell D2, enter **=\&A2\&B2\&C2** to concatenate the values to **RegionTerritoryState**. In the import wizard, select column D for the control environment data.

  - Use columns to represent document properties for controls.

  - Enter a name for each control. The name is the only required field. All other document property fields are optional. However, you might want to import as much data as you can. Importing the data is faster than manually updating the properties later.

  - Include merged cells only if they are contained in a single column or a single row. The import wizard uses the data from the merged cells for all the fields that are included in the merged cells.

  - For document property fields that are names, you can use a blank cell to indicate that the parent node will be taken from the next “name” cell up in the control environment hierarchy. For example, in the following illustration, for the row that contains the **Write off transactions** control, the cell in the **Test Plan Name** column is blank. Therefore, the **Write off transactions** control is the direct parent of the **Missing approval** issue. Similarly, the **Credit** risk under the **Accounts receivable** process name is the parent of the following controls: **Credit term limits**, **Write off transactions**, and **Approve write-off transactions**.
    
    ![ImportControlsBlankNames](images/Hh271671.ImportControlsBlankNames(AX.60).gif "ImportControlsBlankNames")

  - For document property fields that are not names, use a blank cell if you do not want to import data for the field.
    

    > [!NOTE]
    > <P>Values for the <STRONG>Owner</STRONG>, <STRONG>Status</STRONG>, and <STRONG>Evidence</STRONG> fields cannot be imported.</P>



  - Make a note of the input type for each document property field, and make sure that the information in the corresponding column in the worksheet uses the correct format. You can view the input types on the **Edit document templates** page. For detailed information about each input type, see the following table.
    
    <table>
    <colgroup>
    <col style="width: 33%" />
    <col style="width: 33%" />
    <col style="width: 33%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Input type</p></th>
    <th><p>Guideline</p></th>
    <th><p>Notes</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Text box</p></td>
    <td><p>In Excel, enter text. The text is imported as it is in the worksheet.</p></td>
    <td><p></p></td>
    </tr>
    <tr class="even">
    <td><p>Value list box</p></td>
    <td><p>In Excel, enter text. The text must be identical to one of the values in the list on the <strong>Internal controls</strong> site.</p></td>
    <td><p>If the text does not match a value in the corresponding list, the field is ignored during the import process. All other data for the row is imported. The text that is ignored is listed on the error report.</p>
    <p>The text is not case sensitive. Therefore, <strong>Effective</strong> and <strong>effective</strong> are interpreted as the same value.</p></td>
    </tr>
    <tr class="odd">
    <td><p>Multi-select</p></td>
    <td><p>In Excel, enter text. Separate list items with semicolons (;). The text must be identical to one or more of the values in the list on the <strong>Internal controls</strong> site.</p></td>
    <td><p>If the text does not match a value in the corresponding list, the text is ignored during the import process. All other data for the row is imported. The text that is ignored is listed on the error report.</p>
    <p>The text is not case sensitive. Therefore, <strong>Low</strong> and <strong>low</strong> are interpreted as the same value.</p></td>
    </tr>
    <tr class="even">
    <td><p>Number</p></td>
    <td><p>In Excel, enter the number. The text is imported as it is in the worksheet. Currency fields are formatted according to the format that is specified for the regional settings of the Windows server. Negative numbers are preceded by a minus (-) sign.</p></td>
    <td><p>On the <strong>Compliance</strong> site, numbers are stored by using the Text box data type.</p></td>
    </tr>
    <tr class="odd">
    <td><p>Calendar</p></td>
    <td><p>In Excel, enter the date. The date is formatted according to the format that is specified for the regional settings of the server.</p></td>
    <td><p>On the <strong>Compliance</strong> site, dates are stored by using the Text box data type.</p></td>
    </tr>
    <tr class="even">
    <td><p>Check box</p></td>
    <td><p>In Excel, enter <strong>Yes</strong> to select the check box. Enter <strong>No</strong> or leave the cell blank to clear the check box.</p></td>
    <td><p>If there is an error when the check box is imported, the check box is cleared during the import process. All other data for the row is imported. The check box that is cleared is listed on the error report.</p>
    <p>The text is not case sensitive. Therefore, <strong>Yes</strong> and <strong>yes</strong> are interpreted as the same value.</p></td>
    </tr>
    </tbody>
    </table>


## Import controls to the Compliance site

When you import controls, they are considered new controls. You cannot use the import wizard to update controls that are already on the **Compliance** site.

After the control matrix worksheet and **Compliance** site data have been mapped, the mapping is not automatically refreshed for changes that are made by another user during the mapping process.


> [!NOTE]
> <P>You must have <STRONG>Add/Copy</STRONG> permissions to the control environment nodes that you import data into.</P>



1.  Click **Compliance** on the top link bar, and then click **Import controls** on the Quick Launch.

2.  On the **Controls Import and Mapping wizard** welcome page, click **Next**.

3.  On the **Select file** page, select the control matrix workbook file. The list displays Excel workbooks that are in the **Compliance resources** document library. Click **Next**.

4.  On the **Select data** page, select the worksheet that contains the data to import.
    
    Up to 50 rows in the worksheet are displayed. Blank rows are ignored by the import process.

5.  When you are satisfied that you selected the correct worksheet, click **Next**.

6.  On the **Select environment field** page, select the column in the control matrix that contains control environment data. Click **Next**.

7.  On the **Map environment fields** page, there are two columns of data. The first column represents the environment nodes that are selected from the control matrix worksheet. The second column represents the environment nodes that you have **Add/Copy** permissions for on the **Compliance** site. For each entry in the left column, select the corresponding environment node from the list in the right column. Repeat this step for each unique worksheet node.

8.  Click **Next**.

9.  On the **Map control matrix properties** page, select a document template and a property. Click the **Map** button above the column that corresponds to the template and property that you selected. Repeat this step for each template and property that you want to import.
    

    > [!NOTE]
    > <P>For each document template that you import, you must map a column to the <STRONG>Name</STRONG> property. The other properties are optional.</P>



10. Click **Next**.

11. On the **Import status** page, click **Import** to process the import file.
    
    Depending on the amount of data that is imported, this process might take some time to finish. After you click **Import**, any actions you take will not affect the import process.
    

    > [!NOTE]
    > <P>We recommend that you do not navigate away from the <STRONG>Import status</STRONG> page until the process is finished. If you navigate away, the <STRONG>Import summary</STRONG> page is not displayed when the import process is finished.</P>



12. When the **Import summary** page is displayed, click **Finish**.
    
    When the process is complete, an error report is generated and is saved in the **Import Wizard Reports** folder in the **Compliance resources** document library. The report includes information about fields, text, and check boxes that are ignored during the import process. The file name contains the name of the import file, plus the date and time that the file was processed. For example, the file might be named **SampleControlMatrix2011-03-21T221950.htm**.

## Example

Fabrikam, a global organization, is required to document its controls. Phyllis, the accounting manager, has created a control matrix in Excel. She plans to import controls to the **Compliance** site. This example illustrates the process that Phyllis uses to prepare the control matrix and import controls. She works with Chris, the Enterprise Portal for Microsoft Dynamics AX site administrator.

### Set up the control environment

1.  Chris clicks **Compliance** on the top link bar, and then clicks **Set up control environment** on the Quick Launch.

2.  On the **Set up control environment** page, Chris sets up the control environment structure, based on information that Phyllis provided. He gives Phyllis **Add/Copy** permissions to each node. The resulting structure resembles this:
    
      - **Global**
        
          - **Operations**
        
          - **Sales**
        
          - **Purchasing**
    
      - **Domestic**
        
          - **Operations**
        
          - **Sales**
        
          - **Purchasing**

### Review document templates and identify properties to import data for

1.  Phyllis clicks **Compliance** on the top link bar, and then clicks **Document templates** on the Quick Launch.

2.  On the **Edit document templates** page, Phyllis decides to use the default document templates. She makes a list of the document templates and properties to import data for.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Document template</p></th>
    <th><p>Properties to import data for</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Project Task</p></td>
    <td><p>Name, Description, Comments</p></td>
    </tr>
    <tr class="even">
    <td><p>Significant Account</p></td>
    <td><p>Name, Description, Comments</p></td>
    </tr>
    <tr class="odd">
    <td><p>Process</p></td>
    <td><p>Name, Description, Comments, Process Owner, Transaction Type</p></td>
    </tr>
    <tr class="even">
    <td><p>Risk</p></td>
    <td><p>Name, Description, Comments, Assertions, Control Objective (COSO), Impact, Likelihood</p></td>
    </tr>
    <tr class="odd">
    <td><p>Control</p></td>
    <td><p>Name, Description, Comments, Priority, Control Type, Performed by, Control Tested, Control Effectiveness</p></td>
    </tr>
    <tr class="even">
    <td><p>Test Plan</p></td>
    <td><p>Name, Description, Owner, Status, Evidence, Comments, Objective, Performed by, Frequency, Design Assessment (COSO), Operating Effectiveness Testing (COSO)</p></td>
    </tr>
    <tr class="odd">
    <td><p>Issue</p></td>
    <td><p>Name, Description, Owner, Status, Evidence, Comments</p></td>
    </tr>
    <tr class="even">
    <td><p>Remediation</p></td>
    <td><p>Name, Description, Owner, Status, Evidence, Comments, Objective, Performed by</p></td>
    </tr>
    </tbody>
    </table>


### Prepare the control matrix import file

1.  Phyllis opens the control matrix workbook and selects the worksheet that contains the controls that she will import.

2.  Phyllis adds a column to represent the control environment data. Because the worksheet contains this information in multiple columns, she concatenates the information into one column (Column A + Column B = Column C), as shown in the following illustration.
    
    ![ImportControlsConcatenatedExample](images/Hh271671.ImportControlsConcatenatedExample(AX.60).gif "ImportControlsConcatenatedExample")

3.  Phyllis hides all the columns except for the names of controls. She verifies that all control name columns have an entry in them. A few names are blank. She examines these to make sure that the hierarchy is correct. She determines that the blank cells will result in the correct hierarchy when controls are implemented, as shown in the following illustration.
    
    ![ImportControlsBlankNames](images/Hh271671.ImportControlsBlankNames(AX.60).gif "ImportControlsBlankNames")

4.  Phyllis shows all columns and compares the remaining columns in the control matrix with the list of document types and properties that she previously created. She notices that the **Control Priority** column is blank for some controls.

5.  Phyllis works with her coworkers to identify a control priority for each control. She enters **Low**, **Medium**, or **High** in the **Control Priority** column for each row in the worksheet. Phyllis and her coworkers also identify the people who will perform some, but not all, controls. She enters the names of the people in the **Control Performed by** column for the appropriate rows. For the controls that do not have performers, she leaves the cells blank, as shown in the following illustration.
    
    ![ImportControlsBlankCells](images/Hh271671.ImportControlsBlankCells(AX.60).gif "ImportControlsBlankCells")

6.  Phyllis saves the workbook and uploads it to the **Compliance resources** shared documents library on the **Compliance** site.

### Import the controls

1.  Phyllis clicks **Compliance** on the top link bar, and then clicks **Import controls** on the Quick Launch. On the **Import controls** page, she clicks **Next**.

2.  Phyllis selects the control matrix workbook file that she previously uploaded to the **Compliance resources** shared documents library. Then she selects the worksheet that contains the controls to import.

3.  Phyllis selects the column that represents the control environment, and then maps each unique control node in the worksheet to a control environment node on the **Compliance** site.

4.  Phyllis maps each remaining column that she wants to import to a document template and document property.

5.  Phyllis clicks **Import** to process the import file.

6.  When the import process is finished, Phyllis reviews the error report in the **Import Wizard Reports** folder in the **Compliance resources** shared documents library.

7.  Phyllis clicks **Internal controls** on the Quick Launch.

8.  On the **Internal controls** page, Phyllis reviews the controls that she imported, as shown in the following illustration.
    
    ![ImportControlsInternalControlsResult](images/Hh271671.ImportControlsInternalControlsResult(AX.60).gif "ImportControlsInternalControlsResult")

## See also

[Set up the Internal controls site](set-up-the-internal-controls-site.md)

  


