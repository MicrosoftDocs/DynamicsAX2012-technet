---
title: (RUS) Set up dynamic sections for electronic reporting
TOCTitle: (RUS) Set up dynamic sections for electronic reporting
ms:assetid: 03dd6e59-4f02-4fc6-b8bb-84d80f8ea369
ms:mtpsurl: https://technet.microsoft.com/library/JJ664159(v=AX.60)
ms:contentKeyID: 49384741
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- electronic reporting
- dynamic section
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up dynamic sections for electronic reporting 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

A dynamic section is a Microsoft Excel template that has only one section that displays data for specific objects. In a template, this type of section can appear one or more times, or it might not appear. A dynamic section can contain requisites of any type.

## Set up a simple dynamic section

1.  Click **General ledger** \> **Setup** \> **Financial reports generator** \> **Document templates**.

2.  Select a template, and then click **Setup**.

3.  Click **Open**. The Excel worksheet opens in the lower pane of the form.
    

    > [!NOTE]
    > <P>If the worksheet opens in a new window, you must update the system register to open the worksheet in the lower pane of the form. For more information, see <A href="rus-update-the-system-register-for-electronic-reporting.md">(RUS) Update the system register for electronic reporting</A>.</P>



4.  In the **Section** field, select the section code that the dynamic requisite refers to.
    

    > [!NOTE]
    > <P>You can select the section code on either the <STRONG>Overview</STRONG> tab or the <STRONG>Tree</STRONG> tab.</P>



5.  On the **Requisites** tab, click **New** create a new line.

6.  In the **Requisite type** field, select **Cell**.

7.  In the **Requisite** field, enter the requisite code.

8.  In the **Description** field, enter a description for the requisite.

9.  Select the **Dynamic section** check box to indicate that the requisite is excluded from the report file.

10. In the **Data type** field, select **General**.

11. In the **Output type** field, select **Optional**.

12. In the lower section of the form, select the cells that define the value for this requisite. For example, you could select cell E158, which has the value Section00005 in the template for the assessed tax declaration.

13. Click **Select**, and then click **Yes** to change the area for the requisite. The **Value** field is updated with the value from the template.

## Set up a child dynamic section

A child section or subsection is related to a parent section in terms of the value of a field. These section types are used in XML reporting formats. Child sections can also be dynamic. For example, the first section in the transportation tax declaration contains final data, and the second section contains the decoding of the final data. Both sections contain a field for the Russian National Classifier of Administrative and Territorial Subdivisions (OKATO). However, the two sections are related only if their **OKATO** field values are the same.

You must set up a parent section before you can set up a child dynamic section for electronic reporting.

1.  Click **General ledger** \> **Setup** \> **Financial reports generator** \> **Document templates**.

2.  Select a template, and then click **Setup**.

3.  Click **Open**. The Excel worksheet opens in the lower pane of the form.

4.  In the **Section** field, select the parent section to add the child requisite to. Then set up a dynamic table that has an area that includes all section lines. For more information, see [(RUS) Set up dynamic table requisites for XML format](rus-set-up-dynamic-table-requisites-for-xml-format.md) and [(RUS) Set up dynamic table requisites for text formats](rus-set-up-dynamic-table-requisites-for-text-formats.md).

5.  In the **Reference to value** field of the dynamic requisite of the child section, select the requisite of the parent section that links the parent and child sections.
    

    > [!NOTE]
    > <P>This field is available only for report formats of version 4 or a later version that are set up in the <STRONG>Periods of formats application</STRONG> form.</P>



## See also

[(RUS) Requisites setup (form)](https://technet.microsoft.com/library/jj710719\(v=ax.60\))

[(RUS) Document templates (form)](https://technet.microsoft.com/library/jj923585\(v=ax.60\))

[(RUS) Set up templates for electronic reporting](rus-set-up-templates-for-electronic-reporting.md)

[(RUS) Set up simple cell type requisites](rus-set-up-simple-cell-type-requisites.md)

[(RUS) Set up composite cell type requisites](rus-set-up-composite-cell-type-requisites.md)

  


