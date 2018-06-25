---
title: (RUS) Set up conditional requisites for XML formats
TOCTitle: (RUS) Set up conditional requisites for XML formats
ms:assetid: f03bb80f-4df4-41a3-b85c-74f071aae9c6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ710645(v=AX.60)
ms:contentKeyID: 49385043
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- XML
- requisites
- conditional requisites
---

# (RUS) Set up conditional requisites for XML formats [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

A conditional requisite is a requisite for which the value is selected from the cell area where the value is initially set up. An example of this type of requisite is the requisite for the tax amount that is due in the property tax declaration form. You can set up the value of a conditional requisite by using the Microsoft Excel template.

Use the following procedure to set up two conditional requisites that have the same attribute names. The requisite value is taken from the specified cells. If the value is not specified in the cell, the value is taken from the **Default** field in the **Requisites setup** form.

1.  Click **General ledger** \> **Setup** \> **Financial reports generator** \> **Document templates**.

2.  Select a template, and then click **Setup**. Click **Open**. The Microsoft Excel worksheet opens in the lower pane of the form.
    

    > [!NOTE]
    > <P>If the worksheet opens in a new window, you must update the system register to open the worksheet in the lower pane of the form. For more information, see <A href="rus-update-the-system-register-for-electronic-reporting.md">(RUS) Update the system register for electronic reporting</A>.</P>



3.  In the **Section** field, select the section code that the conditional requisite refers to.

4.  Click **New** to create a line, and then in the **Requisite type** field, select **Cell**.

5.  In the **Requisite** field, enter a requisite code. The **Attribute** field is updated with the XML attribute name. You can change the name if a different name is required.

6.  In the Excel worksheet in the lower pane of the form, select the cells that contain the values for the first line. In the left section of the form, click **Select**, and then click **Yes** to change the area of the requisite.

7.  In the **Data type** field, select **Conditional**, and in the **Output type** field, select **Optional**.

8.  Click **New** to create a line, and then in the **Requisite** field, enter a name for the requisite.

9.  In the **Attribute** field, specify the attribute name that matches the name in the **Attribute** field of the original requisite.

10. In the **Requisite type**, **Data type**, and **Output type** fields, select **Cell**, **Conditional**, and **Optional**.

11. In the Excel worksheet in the lower pane of the form, select the cells that contain the values for the first line. In the right section of the form, click **Select**, and then click **Yes** to change the area of the requisite.

12. In the **Prefix** field, enter the value that is added before the requisite, and in the **Postfix** field, enter the value that is added after the requisite.

13. In the **Default** field, specify the default value that is used for both requisites that appear in the Excel worksheet if the cells are empty.

## See also

[(RUS) Set up templates for electronic reporting](rus-set-up-templates-for-electronic-reporting.md)

[(RUS) Document templates (form)](https://technet.microsoft.com/en-us/library/jj923585\(v=ax.60\))

[(RUS) Requisites setup (form)](https://technet.microsoft.com/en-us/library/jj710719\(v=ax.60\))

[(RUS) Format of requisites (form)](https://technet.microsoft.com/en-us/library/jj710737\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

