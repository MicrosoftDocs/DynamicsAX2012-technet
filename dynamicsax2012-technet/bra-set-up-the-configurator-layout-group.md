---
title: (BRA) Set up the configurator layout group
TOCTitle: (BRA) Set up the configurator layout group
ms:assetid: 4184d0b2-aa20-4b85-8be0-1c6b7158f8be
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ863723(v=AX.60)
ms:contentKeyID: 50396406
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Brazil
- (BRA)
- configurator layout group
- layout group
- Set up configurator
- Set up layout group
---

# (BRA) Set up the configurator layout group [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Configurator layout groups** form to set up a configurator layout group. A configurator layout group defines the file structure that is used to import or export data. When you create configurator layout groups, you must attach a configurator definition group to the layout group and define the layout. If you create a configurator layout group to import a return file, you must select the **Register type** check box in the **Edit layout** form to define a register type for the record layout that has a header, detail, and trailer.


> [!NOTE]
> <P>You cannot delete a configurator definition group if it is attached to a configurator layout group.</P>



1.  Click **Organization administration** \> **Periodic** \> **Configurator** \> **Configurator layout groups**.

2.  Create a configurator layout group.

3.  In the **Layout group** and **Name** fields, enter an identification code and name for the configurator layout group.

4.  In the **Layout type** field, select one of the following options to indicate the type of layout:
    
      - **Delimited** – The fields are separated by a delimiter.
    
      - **Fixed length** – The fields have a fixed length.

5.  In the **Definition group** field, select the identification code of the definition group to attach to the configurator layout group.

6.  In the **File structure** field, select one of the following options to indicate the file structure for the layout group:
    
      - **Simple** – You can define a single header, detail, and trailer for the layout. If this option is selected, the **Header**, **Detail**, and **Trailer** options are available in the **Record type** field in the **Edit layout** form.
    
      - **Complex** – You can define multiple headers, details, and trailers for the layout. If this option is selected, the **File header**, **Batch header**, **Details**, **Batch trailer**, and **File trailer** options are available in the **Record type** field in the **Edit layout** form.

7.  If you selected **Delimited** in the **Layout type** field, click the **Layout** tab, and then enter information in the following fields:
    
    1.  In the **Delimited** field, select one of the following options to indicate the delimiter for the delimited layout type:
        
          - **Tab** – The fields are separated by tabs.
        
          - **Semicolon** – The fields are separated by semicolons.
        
          - **Comma** – The fields are separated by commas.
        
          - **Space** – The fields are separated by spaces.
        
          - **Other** – You can specify any other delimiter in the **Other** field.
    
    2.  If you selected **Other** in the **Delimited** field, in the **Other** field, enter the delimiter to use.
        

        > [!NOTE]
        > <P>This field is available only if you select <STRONG>Other</STRONG> in the <STRONG>Delimited</STRONG> field.</P>

    
    3.  In the **Text qualifier** field, select the text qualifier.

8.  Select the **Export** check box to use the layout group as an export format. If you select this check box, in the **Methods of payment - customers** and **Methods of payment - vendors** forms, in the **Export layout group** field, you can select the layout group for a method of payment that has the **Configurable layout file** export format.

9.  Select the **Import** check box to use the layout group as an import format. If you select this check box, in the **Methods of payment - customers** and **Methods of payment - vendors** forms, in the **Return layout group** field, you can select the layout group for a method of payment that has the **Configurable layout file** return format.

10. Click **Layout** to open the **Edit layout** form. You can define a simple or a complex file layout, based on the file structure that is defined for the layout group.

11. In the **Edit layout** form, enter information in the following fields:
    
    1.  In the **Record name** field, enter a name for the record layout.
    
    2.  In the **Record size** field, enter the size of the record layout. The total size that you specify for all the record lines in the **Size** field on the **Configurator layout fields** FastTab cannot be more than the record size.
    
    3.  In the **Record type** field, select the type of record to define the layout for.
        
        If you select **Simple** in the **File structure** field in the **Configurator layout groups** form, the following options are available:
        
          - **Header**
        
          - **Detail**
        
          - **Trailer**
        
        If you select **Complex** in the **File structure** field in the **Configurator layout groups** form, the following options are available:
        
          - **File header**
        
          - **Batch header**
        
          - **Details**
        
          - **Batch trailer**
        
          - **File trailer**
    
    4.  Select the **Hide** check box to indicate that the record layout is not printed in the output file. This check box is available only if you select the **Complex** file structure for the layout group in the **Configurator layout groups** form.
    
    5.  Select the **Register type** check box to activate a register type for the record layout. If you select this check box, you must define a register type for record layouts that have **Header**, **Detail**, and **Trailer** record types. To define a register type, select **Command** in the **Table name** field and **Register type** in the **Field name** field, and then specify the register type value in the **Content** field.
        

        > [!NOTE]
        > <P>You must specify a register type for each layout line of the layout group. The register group is used to import a return file.</P>



12. On the **Configurator layout fields** FastTab, enter or view information in the following fields:
    
    1.  In the **Table name** field, select a table to define the layout for. The tables that are defined in the **Configurator definition groups** form for the configurator definition group that is assigned to the configurator layout group are available.
    
    2.  In the **Field name** field, select a field to define the layout for. The fields that are defined for the table that you select in the **Table name** field are available.
        

        > [!NOTE]
        > <P>For a record layout line, you can specify either a field in the <STRONG>Field name</STRONG> field or a method in the <STRONG>Method name</STRONG> field.</P>

    
    3.  In the **Array index** field, enter the array index for the array type field.
    
    4.  In the **Method name** field, select a method to define the layout for. You can select a method in the list of methods that are available for the table that you select in the **Table name** field.
        

        > [!NOTE]
        > <P>For a record line, you can specify either a field in the <STRONG>Field name</STRONG> field or a method in the <STRONG>Method name</STRONG> field.</P>

    
    5.  In the **End position** field, view the ending position of the record. You can update the end position for string, integer, and real data types. When you update the end position for a field, the **Size** field and the number of characters in the **Format** field are updated. Any increase or decrease in the end position of the real data type updates the number of characters that are before the decimal point in the format.
        

        > [!NOTE]
        > <P>For the date and time data types, the end position is updated based on the value that you specify in the <STRONG>Format</STRONG> field.</P>

    
    6.  In the **Size** field, view the total size of the record layout line. The size is equal to the character count from the starting position to the ending position for the field. For example, if the ending position is 20, and the starting position is 10, the size is 11. The record size is updated if you update the value in the **End position** field or the **Format** field.
        

        > [!NOTE]
        > <P>For the date and time data types, the size includes the separator that is used in the format.</P>

    
    7.  In the **Type** field, view the default data type for the selected field or method. This field is updated based on the field that you select in the **Field name** field.
    
    8.  In the **Format** field, update the format of the field, based on the data type. This field is updated based on the field that you select in the **Field name** field.
        
        <table>
        <colgroup>
        <col style="width: 50%" />
        <col style="width: 50%" />
        </colgroup>
        <thead>
        <tr class="header">
        <th><p>Type</p></th>
        <th><p>Format</p></th>
        </tr>
        </thead>
        <tbody>
        <tr class="odd">
        <td><p>String</p></td>
        <td><p>X(nnn)</p>
        <ul>
        <li><p>X indicates that the value consists of characters.</p></li>
        <li><p>nnn indicates the number of characters.</p></li>
        </ul>
        <p>You can only modify the number of characters (nnn). For example, X(30) is a string that contains 30 characters.</p></td>
        </tr>
        <tr class="even">
        <td><p>Integer</p></td>
        <td><p>9(nnn)</p>
        <ul>
        <li><p>9 indicates a numeric value.</p></li>
        <li><p>nnn indicates the number of digits.</p></li>
        </ul>
        <p>You can only modify the number of digits (nnn).</p></td>
        </tr>
        <tr class="odd">
        <td><p>Real</p></td>
        <td><p>9(nnn)V9(nnn)</p>
        <ul>
        <li><p>9 indicates a numeric value.</p></li>
        <li><p>nnn indicates the number of digits.</p></li>
        <li><p>V indicates the separator between the integer and decimal values, such as a comma or a period. The separator that is used depends on the system setup.</p></li>
        <li><p>The second 9 indicates that the separator is followed by decimal places.</p></li>
        <li><p>The second nnn indicates the number of decimal places after the separator.</p></li>
        </ul>
        <p>For example, 9(8)V9(5) is an eight-digit number that has five decimal places.</p>
        <div class="alert">

        > [!NOTE]
        > <P>You can also use the format 9(nnn)9(nnn) when there is no separator between the integer and decimal values of the number.</P>


        </div></td>
        </tr>
        <tr class="even">
        <td><p>Date</p></td>
        <td><p>Any combination of DD, MM, and YY or YYYY. These placeholders represent the date, month, two-digit year, and four-digit year. You can use different combinations of DD, MM, YY, and YYYY, and can include or exclude a separator. For example, the date format can be DD/MM/YY or MM/DD/YYYY, or DDMMYY or MMDDYYYY.</p></td>
        </tr>
        <tr class="odd">
        <td><p>Time</p></td>
        <td><p>Any combination of hh, mm, and ss, which represent hours, minutes, and seconds. A colon (:) is used as the separator. For example, the time format can be hh:mm:ss.</p></td>
        </tr>
        </tbody>
        </table>
        

        > [!NOTE]
        > <P>For the string, integer, and real data types, you can only modify the number of characters, which is indicated by nnn. If you modify the number of characters for a field, the values in the <STRONG>End position</STRONG> and <STRONG>Size</STRONG> fields are updated.</P>

    
    9.  In the **Content** field, enter a value for the selected field, if any value is required. You must specify a value if you select **Command** in the **Table name** field, and **Fixed** or **Register type** in the **Field name** field.
        

        > [!NOTE]
        > <P>You must enter the value for the register type in the format that is specified in the <STRONG>Format</STRONG> field.</P>

    
    10. In the **Fill** field, enter the character that is used to fill empty spaces in the field. For example, if the **Name** field uses left justification and **X** as the fill character for a 10-character string, the value is displayed as **NameXXXXXX**.
    
    11. In the **Justification** field, select the justification that is applied to the value of the field that you select in the **Field name** field. The options are **Left justify** and **Right justify**. For example, if the **Name** field uses right justification and **X** as the fill character for a 10-character string, the value is displayed as **XXXXXXName**.
    
    12. In the **Truncate** field, select one of the following options to indicate the method that is used to truncate the decimal values in the selected field:
        
          - **None** – The value is not truncated or rounded.
        
          - **Truncate** – The value is truncated.
        
          - **Round** – The value is rounded up or down to the nearest whole number, depending on whether the number is more than or less than 00.50.
        
          - **Rounding-up** – The value is rounded up to the nearest whole number.
        
          - **Rounding-down** – The value is rounded down to the nearest whole number.
    
    13. In the **Comments** field, enter any comments. The comments that you enter in this field are used for informational purposes only.
        

        > [!NOTE]
        > <P>The <STRONG>Start position</STRONG>, <STRONG>End position</STRONG>, <STRONG>Size</STRONG>, <STRONG>Fill</STRONG>, <STRONG>Justification</STRONG>, and <STRONG>Truncate</STRONG> fields on the <STRONG>Configurator layout fields</STRONG> FastTab are available only if you select <STRONG>Fixed length</STRONG> in the <STRONG>Layout type</STRONG> field in the <STRONG>Configurator layout groups</STRONG> form.</P>

    
    14. In the **Complex** file structure layout, an automatic sequence number for the batch ID is generated for the **Batch header**, **Details**, and **Batch trailer** record types. Select **Command** in the **Table name** field and **Batch ID** in the **Field name** field, and then specify the batch ID in the **Content** field. The batch ID can contain a maximum of five characters.
    
    15. If you select **Command** in the **Table name** field in the **Complex** file structure layout, in the **Field name** field, select one of the following options. The options that are available depend on the record type.
        
          - **File Batch Qtd (Record type - File trailer)** – Generate the total number of batches in the layout on the output file.
        
          - **Batch Register Number (Record type – Details)** – Generate a sequential number for the registers in a batch.
        
          - **Qtd Registers in a Batch (Record type – Batch trailer, File trailer)** – Generate the total number of registers in the batch.

13. Repeat step 12 to add other fields to the record layout.

## See also

[(BRA) Configurator layout groups (form)](https://technet.microsoft.com/en-us/library/jj863736\(v=ax.60\))

[(BRA) Configurator export utility (form)](https://technet.microsoft.com/en-us/library/jj863720\(v=ax.60\))

[(BRA) Edit layout (form)](https://technet.microsoft.com/en-us/library/jj853382\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

