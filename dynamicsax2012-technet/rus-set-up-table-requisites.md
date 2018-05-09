---
title: (RUS) Set up table requisites
TOCTitle: (RUS) Set up table requisites
ms:assetid: 9cca460d-82e7-4fa2-ba11-baa866b1ddb8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677625(v=AX.60)
ms:contentKeyID: 49384928
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- requisite
- table requisites
---

# (RUS) Set up table requisites 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Every report template contains several tables that have requisites in the table cells. Use the **Requisites setup** form to set up table requisites.

1.  Click **General ledger** \> **Setup** \> **Financial reports generator** \> **Document templates**.

2.  Select a template, and then click **Setup**. Click **Open**. The Microsoft Excel worksheet opens in the lower pane of the form.
    

    > [!NOTE]
    > <P>If the worksheet opens in a new window, you must update the system register to open the worksheet in the lower pane of the form. For more information, see <A href="rus-update-the-system-register-for-electronic-reporting.md">(RUS) Update the system register for electronic reporting</A>.</P>



3.  On the **Tables** tab, in the **Section** field, select the section that the requisite is added to.

4.  Click **New** to create a line, and then press CTRL+S to save the form. The **Format** field is updated with the format code that is set up in the **Document templates** form. You can update this format code for a specific table. In the right section of the form, three lines are created. One line has a column type of **Line code**, one has a column type of **Description**, and one has a column type of **Value**.

5.  In the Excel worksheet in the lower pane of the form, select a group of cells that is the data source for the table. In the left section of the form, click **Select**, and then click **Yes**. The list and table cell area are displayed in the **Area** field.

6.  In the **Description format** field, enter the description format for the requisite code.

7.  In the right section of the form, select the line that has a column type of **Line code**.

8.  In the Excel worksheet in the lower pane of the form, select the first cell of the column that contains the line code. In the right section of the form, click **Select**, and then click **Yes**.

9.  In the **Column number** field, enter the number that is used to create requisite code.

10. Select the lines that have column types of **Description** and **Value**, and then repeat steps 8 and 9 for each line.

11. In the **Data type** and **Extended data type** fields, select the data type of the column and the extended data type to verify the value of the requisite that is imported. For more information, see [(RUS) Requisites setup (form)](https://technet.microsoft.com/en-us/library/jj710719\(v=ax.60\)).

12. Create as many lines of the **Value** column type as there are value columns in the table. To arrange the lines in the correct order, select a line, and then click **Up** to move the line one position up, or click **Down** to move the line one position down.
    

    > [!NOTE]
    > <P>Click <STRONG>Go to</STRONG>, and verify that the cell ranges are selected correctly.</P>



13. In the left section of the form, click **Requisites** to create requisites in the selected section.
    

    > [!NOTE]
    > <P>On the <STRONG>Requisites</STRONG> tab, verify the requisites that you created.</P>



## See also

[(RUS) Document templates (form)](https://technet.microsoft.com/en-us/library/jj923585\(v=ax.60\))

[(RUS) Set up conditional cell type requisites](rus-set-up-conditional-cell-type-requisites.md)

[(RUS) Set up conditional requisites for XML formats](rus-set-up-conditional-requisites-for-xml-formats.md)

[(RUS) Set up composite cell type requisites](rus-set-up-composite-cell-type-requisites.md)

[(RUS) Set up dynamic table requisites for text formats](rus-set-up-dynamic-table-requisites-for-text-formats.md)

[(RUS) Set up dynamic table requisites for XML format](rus-set-up-dynamic-table-requisites-for-xml-format.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

