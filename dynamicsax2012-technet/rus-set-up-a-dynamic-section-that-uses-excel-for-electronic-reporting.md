---
title: (RUS) Set up a dynamic section that uses Excel for electronic reporting
TOCTitle: (RUS) Set up a dynamic section that uses Excel for electronic reporting
ms:assetid: 20b80b34-8a39-4061-9cd9-f40eb1528430
ms:mtpsurl: https://technet.microsoft.com/library/JJ677478(v=AX.60)
ms:contentKeyID: 49384786
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- section
- dynamic section
- excel sheet
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up a dynamic section that uses Excel for electronic reporting 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You must configure a document template for every report that is submitted electronically to the tax authority. Based on the electronic report format, a document template can contain several sections. If one section of a report format contains several similar blocks of information, you can create a dynamic Microsoft Excel worksheet for this section. Generally, this section is the first section of the template and displays totals for the objects.

## Set up a dynamic section that uses one Excel worksheet

1.  Click **General ledger** \> **Setup** \> **Financial reports generator** \> **Document templates**.

2.  Select a template, and then click **Setup**.

3.  Click **Open**. The Excel worksheet opens in the lower pane of the form.
    

    > [!NOTE]
    > <P>If the worksheet opens in a new window, you must update the system register to open the worksheet in the lower pane of the form. For more information, see <A href="rus-update-the-system-register-for-electronic-reporting.md">(RUS) Update the system register for electronic reporting</A>.</P>



4.  In the **Section** field, select the section code that the dynamic requisite refers to.
    

    > [!NOTE]
    > <P>You can select the section code on either the <STRONG>Overview</STRONG> tab or the <STRONG>Tree</STRONG> tab.</P>



5.  On the **Requisites** tab, click **New** to create a dynamic section. For more information, see [(RUS) Set up templates for electronic reporting](rus-set-up-templates-for-electronic-reporting.md).

6.  On the **Tables** tab, click **New** to set up a dynamic table that includes all requisites for the section. For more information, see [(RUS) Set up dynamic table requisites for text formats](rus-set-up-dynamic-table-requisites-for-text-formats.md) and [(RUS) Set up dynamic table requisites for XML format](rus-set-up-dynamic-table-requisites-for-xml-format.md).
    
    For information about how to add child sections, see [(RUS) Set up dynamic sections for electronic reporting](rus-set-up-dynamic-sections-for-electronic-reporting.md).

## Set up a dynamic section that uses two or more Excel worksheets

1.  Click **General ledger** \> **Setup** \> **Financial reports generator** \> **Document templates**.

2.  Select a template, and then click **Setup**.

3.  Click **Open**. The Excel worksheet opens in the lower pane of the form.
    

    > [!NOTE]
    > <P>If the worksheet opens in a new window, you must update the system register to open the worksheet in the lower pane of the form.</P>



4.  In the **Section** field, select the section code that the dynamic requisite refers to.
    

    > [!NOTE]
    > <P>You can select the section code on either the <STRONG>Overview</STRONG> tab or the <STRONG>Tree</STRONG> tab.</P>



5.  On the **Requisites** tab, click **New** to create a dynamic section.

6.  On the **Tables** tab, click **New** to set up a dynamic table that includes all requisites for the section.

7.  Close the form.

8.  In the **File name** field, select the name and path of the second Excel worksheet to set up dynamic sections, and then click **Setup**.

9.  Repeat steps 3 through 7.

10. To use a third Excel worksheet, in the **Document templates** form, in the **File name** field, select the name and path of the third Excel worksheet, and then click **Setup**.

11. Repeat steps 3 through 7.

## See also

[(RUS) Requisites setup (form)](https://technet.microsoft.com/library/jj710719\(v=ax.60\))

[(RUS) Document templates (form)](https://technet.microsoft.com/library/jj923585\(v=ax.60\))

  


