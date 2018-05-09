---
title: (RUS) Set up conditional cell type requisites
TOCTitle: (RUS) Set up conditional cell type requisites
ms:assetid: 743e537a-be2b-44b7-83c7-56b1f2f7b2d9
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677574(v=AX.60)
ms:contentKeyID: 49384877
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- requisites
- conditional requisites
- requisite setup
- set up requisites
---

# (RUS) Set up conditional cell type requisites 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Requisites setup** form to set up **Cell** requisite types that use the **Conditional** data type. The requisite types are used in document templates.

1.  Click **General ledger** \> **Setup** \> **Financial reports generator** \> **Document templates**.

2.  Select a template, and then click **Setup**. Click **Open**. The Microsoft Excel sheet opens in the lower pane of the form.
    

    > [!NOTE]
    > <P>If the worksheet opens in a new window, you must update the system register to open the worksheet in the lower pane of the form. For more information, see <A href="rus-update-the-system-register-for-electronic-reporting.md">(RUS) Update the system register for electronic reporting</A>.</P>



3.  In the **Section** field, select a section for the requisite.

4.  Click **New** to create a line, and then in the **Requisite type** field, select **Cell**.

5.  In the **Requisite** and **Description** fields, enter a requisite code and a description for the requisite. The **Attribute** field is updated with the XML attribute name. You can change the name if a different name is required.

6.  In the **Data type** field, select **Conditional**.
    

    > [!NOTE]
    > <P>The requisite depends on the value that is displayed in the cell when the requisite is imported. If the cell is not blank, the requisite value is updated with the value in the <STRONG>Value</STRONG> field in the right pane of the <STRONG>Requisites setup</STRONG> form. Otherwise, the requisite value is updated with the value in the <STRONG>Default</STRONG> field.</P>



7.  In the **Output type** field, select an output type for the requisite, from the following options:
    
      - **Optional** – The requisite is excluded from the report file if the requisite value is blank.
    
      - **Required** – The requisite is required and is always included in the report file. The requisite value cannot be blank.
    
      - **Predefined** – A requisite code must be available. The requisite value can be blank.

8.  In the **Extended data type** field, select the extended data type to verify the value of the requisite that is imported.

9.  In the Excel sheet in the lower pane of the form, select the source and target cells for the requisite value.

10. In the right pane of the form, click **Add**, and then click **Yes**. A new line is created in the right pane of the form, and the **Cell** field is updated with the value of the extended data type.

11. In the **Prefix** field, enter the value that is added before the requisite, and in the **Postfix** field, enter the value that is added after the requisite..

12. In the **Value** field, enter a value for the conditional requisite.

13. Click **Go to**, and then verify the selected cells in the lower pane of the form contain the correct values that are used to create the requisite. If any of the selected cells are not empty when the data is imported, the values of the lines are concatenated, and this concatenated value becomes the requisite value. For example, line 1 has a value of 1, and line 2 has a value of 2. If the cells for lines 1 and 2 are not empty, the value of the requisite is 12.

## See also

[(RUS) Document templates (form)](https://technet.microsoft.com/en-us/library/jj923585\(v=ax.60\))

[(RUS) Set up templates for electronic reporting](rus-set-up-templates-for-electronic-reporting.md)

[(RUS) Requisites setup (form)](https://technet.microsoft.com/en-us/library/jj710719\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

