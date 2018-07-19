---
title: (RUS) Set up dynamic table requisites for text formats
TOCTitle: (RUS) Set up dynamic table requisites for text formats
ms:assetid: 80d1f4ab-8a96-4c9e-92fb-1485b58b17d5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677587(v=AX.60)
ms:contentKeyID: 49384890
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- requisite
- requisites
- dynamic requisites
- table requisites
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up dynamic table requisites for text formats 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Dynamic table requisites are uniform requisites that can be consolidated into a table if you do not know the number of table lines when you set up the template. In text formats, the code for dynamic table requisites is generated like the code for table requisites. The code is based on the rule in the **Format** field, and on the line and column number in the table. Because the number of lines in a dynamic table is not known when you set up the template, you can assign the same line number to all requisites.

Use the **Requisites setup** form to set up dynamic table requisites.

1.  Click **General ledger** \> **Setup** \> **Financial reports generator** \> **Document templates**.

2.  Select a template, and then click **Setup**. Click **Open**. The Microsoft Excel worksheet opens in the lower pane of the form.
    

    > [!NOTE]
    > <P>If the worksheet opens in a new window, you must update the system register to open the worksheet in the lower pane of the form. For more information, see <A href="rus-update-the-system-register-for-electronic-reporting.md">(RUS) Update the system register for electronic reporting</A>.</P>



3.  On the **Tables** tab, in the **Section** field, select the section that the requisite is added to.

4.  Click **New** to create a line, and then press CTRL+S to save the form. The **Format** field is updated with the format code that is set up in the **Document templates** form. You can update this format code if a different format code is required. In the right section of the form, three lines are created. One line has a column type of **Line code**, one has a column type of **Description**, and one has a column type of **Value**.
    

    > [!NOTE]
    > <P>The <STRONG>Description</STRONG> column type is not required when you set up dynamic table requisites.</P>



5.  Select the **Dynamic table** check box.

6.  In the Excel worksheet in the lower pane of the form, select the data area of the table.

7.  In the left section of the form, click **Select**, and then click **Yes**. The list and table cell area are displayed in the **Area** field.

8.  In the right section of the form, select the line that has a column type of **Line code**, and then in the **Column number** field, enter the column number of the table in the Excel worksheet.

9.  Select the line that has a column type of **Value**, and then in the **Column number** field, enter the column number of the table in the Excel worksheet. Create as many lines of the **Value** column type as there are value columns in the table.

10. In the Excel worksheet in the lower pane of the form, select the first cell of the appropriate data column. In the right section of the form, click **Select**, and then click **Yes**.

11. In the **Data type** field, select the data type of the column. For more information, see [(RUS) Requisites setup (form)](https://technet.microsoft.com/en-us/library/jj710719\(v=ax.60\)).

12. In the **Extended data type** field, select the extended data type to verify the value of the requisite that is imported.

13. In the left and right sections of the form, click **Go to**, and verify that the cell ranges are selected correctly.

## See also

[(RUS) Document templates (form)](https://technet.microsoft.com/en-us/library/jj923585\(v=ax.60\))

[(RUS) Requisites setup (form)](https://technet.microsoft.com/en-us/library/jj710719\(v=ax.60\))

[(RUS) Format of requisites (form)](https://technet.microsoft.com/en-us/library/jj710737\(v=ax.60\))

  


