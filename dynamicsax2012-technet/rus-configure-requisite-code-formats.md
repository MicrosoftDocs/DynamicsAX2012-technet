---
title: (RUS) Configure requisite code formats
TOCTitle: (RUS) Configure requisite code formats
ms:assetid: e43bcf9b-d8c0-4280-8f5e-57dbad4434ac
ms:mtpsurl: https://technet.microsoft.com/library/JJ913265(v=AX.60)
ms:contentKeyID: 52075450
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- format
- requisite
- requisite code format
- text format
audience: Application User
ms.search.region: Russia
---

# (RUS) Configure requisite code formats 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use requisite code formats to create requisites in the information section of a report. For reports that are exported in text formats, you can create requisites based on table descriptions and requisite code formats. Requisite names in reports that are exported in the XML format are defined by the XML schema definition (XSD), and are created automatically when the XSD schema is applied to the template.

The table information section of the requisites is predefined. In accordance with the format description, which is the rule that is used to create requisite codes that are stated in each format, the table section requisite code includes the following information:

  - The constant value; the prefix before items in the table section.

  - The five-digit code of the declaration section.

  - The five-digit code of the declaration line.

  - The two-digit number of the column in the declaration.

If a different rule for creating requisite codes exists in the format, you must create an appropriate record in the **Format of requisites** form. There can be any number of established rules, but only the one that is used for the selected template is listed.

Use the following procedure to configure requisite code formats.

1.  Click **General ledger** \> **Setup** \> **Financial reports generator** \> **Format of requisites**.

2.  Click **New** to create a line.

3.  In the **Format** field, enter a format code.

4.  In the **Name** field, enter a format name.

5.  Click **Add** to create a line. You must create the same number of lines as there are components in the requisite format.

6.  In the **Type** field, select the requisite format type from the following options:
    
      - **Section number** – The requisite format corresponds with a document section. The section code that is specified in the **Section** field in the **Requisites setup** form is used to create the requisite format.
    
      - **Table number** – The requisite format corresponds with a table. The table number that is specified in the **Table number** field in the **Requisites setup** form is used to create the requisite format.
    
      - **Row number** – The requisite format corresponds with a table line. The number of the table line that is specified in the **Line number** field in the **Requisites setup** form is used to create the requisite format.
    
      - **Column number** – The requisite format corresponds with a table column. The number of the table column that is specified in the **Column number** field in the **Requisites setup** form is used to create the requisite format.

7.  In the **Prefix** field, enter the value that always precedes requisite numbers that are generated automatically.

8.  In the **Postfix** field, enter the value that always follows requisite numbers that are generated automatically.

9.  In the **Length** field, enter the total length for the requisite format.

10. In the **Empty symbol** field, enter the character that is inserted between the prefix and postfix values to complete the total length of the requisite format.

11. Verify that the requisite format value is created correctly in the **Value** field.

## See also

[(RUS) Format of requisites (form)](https://technet.microsoft.com/library/jj710737\(v=ax.60\))

[(RUS) Requisites setup (form)](https://technet.microsoft.com/library/jj710719\(v=ax.60\))

[(RUS) Document templates (form)](https://technet.microsoft.com/library/jj923585\(v=ax.60\))

  


