---
title: (RUS) Set up dynamic table requisites for XML format
TOCTitle: (RUS) Set up dynamic table requisites for XML format
ms:assetid: 29359e1d-33a0-496e-8d39-cf910556806c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677492(v=AX.60)
ms:contentKeyID: 49384795
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- XML
- requisite
- requisites
- dynamic requisite
- table requisite
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up dynamic table requisites for XML format 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Dynamic table requisites are uniform requisites that can be consolidated into a table if you do not know the number of table lines when you set up the template. For reports that are exported in the XML format, the dynamic requisites code is determined by the XML schema definition (XSD) schema.

1.  Click **General ledger** \> **Setup** \> **Financial reports generator** \> **Document templates**.

2.  Select a template, and then click **Setup**. Click **Open**. The Microsoft Excel worksheet opens in the lower pane of the form.
    

    > [!NOTE]
    > <P>If the worksheet opens in a new window, you must update the system register to open the worksheet in the lower pane of the form. For more information, see <A href="rus-update-the-system-register-for-electronic-reporting.md">(RUS) Update the system register for electronic reporting</A>.</P>



3.  On the **Tables** tab, in the **Section** field, select the section that the requisite is added to.

4.  In the left section of the form, click **New** to create a line.

5.  Select the **Dynamic table** check box.

6.  Press CTRL+S to save the form. The right section of the form displays requisites for all table columns.

7.  In the Excel worksheet in the lower pane of the form, select the data area of the table.

8.  In the left section of the form, click **Select**, and then click **Yes**. The list and table cell area are displayed in the **Area** field.

9.  In the **Data type** and **Extended data type** fields, select the data type of the column and the extended data type to verify the value of the requisite that is imported. For more information, see [(RUS) Requisites setup (form)](https://technet.microsoft.com/en-us/library/jj710719\(v=ax.60\))

10. In the Excel worksheet in the lower pane of the form, select the first cell of the appropriate data column. In the right section of the form, click **Select**, and then click **Yes**.

11. In the left and right sections of the form, click **Go to**, and then verify that the cell ranges are selected correctly.

## See also

[(RUS) Document templates (form)](https://technet.microsoft.com/en-us/library/jj923585\(v=ax.60\))

[(RUS) Set up templates for electronic reporting](rus-set-up-templates-for-electronic-reporting.md)

[(RUS) Requisites setup (form)](https://technet.microsoft.com/en-us/library/jj710719\(v=ax.60\))

[(RUS) Format of requisites (form)](https://technet.microsoft.com/en-us/library/jj710737\(v=ax.60\))

[(RUS) Set up dynamic table requisites for text formats](rus-set-up-dynamic-table-requisites-for-text-formats.md)

  


