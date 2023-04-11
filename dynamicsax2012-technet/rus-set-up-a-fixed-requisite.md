---
title: (RUS) Set up a fixed requisite
TOCTitle: (RUS) Set up a fixed requisite
ms:assetid: 1be66d33-9bf6-4501-a5b5-b388eef8f2e3
ms:mtpsurl: https://technet.microsoft.com/library/JJ677470(v=AX.60)
ms:contentKeyID: 49384774
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- fixed requisite
- requisite
- set up requisite
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up a fixed requisite 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Fixed requisites are used to define general requisites and other requisites in the service section of document templates, general data in the information section, and data in the taxpayer information section. These sections are used to customize document templates.

For reports that are generated in text formats, you must use the following file naming format: OMMMMMYY.nnn

  - O – A prefix that represents data from business taxpayer accounting and tax forms.

  - MMMMM – A five-digit to nine-digit number that is the tax identification number (INN) of a business.

  - YY – The last two digits of the tax year.

  - nnn – The serial number of the file. The tax authority provides the serial number for the file for a tax year.

For reports that are generated in XML format, you must use the following file naming format: R\_T\_P\_O\_ggggmmdd\_N

  - R\_T – The prefix.

  - P – The identification number of the recipient, who is the tax authority. The recipient number is assigned by the Sistema oboznacheniy nalogovih organov, system of tax authority classification (SONO).

  - O – The identification number of the sender. This number is a 19-digit number (INN and KPP) for a business, a 12-digit identification number (INN) for individuals, and a four-digit identification number (SONO code) for the tax authority.

  - gggg – The year when the file that is submitted is created.

  - mm – The month when the file that is submitted is created.

  - dd – The date when the file that is submitted is created.

  - N – The file name, which can be between 1 and 36 characters. To guarantee that the file name is unique, you should use a 36-character globally unique identifier (GUID).

  - Use xml as the file name extension.

Use the **Fixed requisites** form to set up a fixed requisite. The requisite value is updated in the **Value** field in the **Fixed requisites** form.

1.  Click **General ledger** \> **Setup** \> **Financial reports generator** \> **Fixed requisites**.

2.  Click **New** to create a line, and then in the **Requisite** field, enter an identification number for the requisite. The **Attribute** field is updated with the XML attribute name. You can change the name if a different name is required.

3.  In the **Name** field, enter a name for the requisite.

4.  In the **Type** field, select the type of requisite, from the following options:
    
      - **Value** – Set values by entering them manually in the **Value** field or by running macros. For XML format versions, use the **Value** requisite type, and compile the value by using macros.
    
      - **Expression** – The **Value** field on the **Expression** tab is updated by using the queries that are set up in the **Queries** form. This option is available if the requisite value has several fields stored in the database tables that are queried. This option is also available if the requisite value is calculated based on the data in the function that is supplemented with values that are manually entered.
    
      - **File ID** – The **Value** field is updated automatically when you upload the electronic documents to the tax authorities. Use the **File ID** requisite type for reports that are submitted in text formats.
    
      - **Requisites number** – The **Value** field is updated automatically when you import the data. If the **Content** check box in the **Document templates** form is selected for a section, all related child section requisites are included in this requisite. Use the **Requisites number** requisite type for reports that are submitted in a text format.
    
      - **File name** – This requisite is used to define the file naming rule. You can create multiple fixed file name requisites and then select the appropriate requisite in the **Periods of formats application** form for each format version. When the document is exported to an output file, the file name is created according to the name that is entered in the **Value** field, and appropriate values are used instead of macros. To use the value of the requisite to create the file name, select the **File name** requisite type.

5.  In the **Value** field, enter the value of the requisite and the appropriate macros.
    

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>Value</STRONG> or <STRONG>File name</STRONG> in the <STRONG>Type</STRONG> field.</P>



6.  In the **Data type** field, specify a data type for the requisite, from the following options:
    
      - **General** – The requisite can have any type of value.
    
      - **Numeric** – The requisite must be numeric. If a cell contains text, the imported value of the requisite is blank.
    
      - **Text** – The requisite can have any value.
    
      - **Date** – The requisite must be in date format. If a cell contains any other type of value, the value of the requisite is blank.
    
      - **Conditional** – The requisite depends on the value that is displayed in the cell when the requisite is imported. If a cell is not blank, the requisite value is updated with the value in the **Value** field in the right section of the **Requisites setup** form. Otherwise, the requisite value is updated with the value in the **Default** field.

7.  In the **Output type** field, select the output type of the requisite, from the following options:
    
      - **Optional** – The requisite is excluded from the report file if the requisite value is blank.
    
      - **Required** – The requisite is required and is always included in the report file. The requisite value cannot be blank.
    
      - **Predefined** – A requisite code must be available. The requisite value can be blank.

8.  In the **Extended data type** field, select an extended data type to verify the value of the requisite that is imported.

9.  On the **Expression** tab, click **New** to create a line.
    

    > [!NOTE]
    > <P>The fields on this tab are available only if you select <STRONG>Expression</STRONG> in the <STRONG>Type</STRONG> field on the <STRONG>Overview</STRONG> tab.</P>



10. In the **Query** and **Table** fields, select a query and the name of the main query table to use for the requisite.

11. In the **Field name** field, select the name of the field in the table.

12. In the **Prefix** and **Postfix** fields, enter the values that precede and follow the value of the selected field.

## See also

[(RUS) Fixed requisites (form)](https://technet.microsoft.com/library/jj710680\(v=ax.60\))

[(RUS) Create a query for electronic reporting](rus-create-a-query-for-electronic-reporting.md)

[(RUS) Queries (form)](https://technet.microsoft.com/library/jj710734\(v=ax.60\))

[(RUS) Document templates (form)](https://technet.microsoft.com/library/jj923585\(v=ax.60\))

[(RUS) Periods of formats application (form)](https://technet.microsoft.com/library/jj710684\(v=ax.60\))

  


