---
title: (RUS) Set up composite cell type requisites
TOCTitle: (RUS) Set up composite cell type requisites
ms:assetid: 12330976-f99e-4933-b7d3-1c1dfb300cf4
ms:mtpsurl: https://technet.microsoft.com/library/JJ677460(v=AX.60)
ms:contentKeyID: 49384763
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- requisite
- composite cell
- requisites
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up composite cell type requisites 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

A composite requisite is a value that is generated from several cell groups that are not sequential. Use the **Requisites setup** form to set up composite **Cell** requisite types that are used in document templates.

1.  Click **General ledger** \> **Setup** \> **Financial reports generator** \> **Document templates**.

2.  Select a template, and then click **Setup**. Click **Open**. The Microsoft Excel worksheet opens in the lower pane of the form.
    

    > [!NOTE]
    > <P>If the worksheet opens in a new window, you must update the system register to open the worksheet in the lower pane of the form. For more information, see <A href="rus-update-the-system-register-for-electronic-reporting.md">(RUS) Update the system register for electronic reporting</A>.</P>



3.  In the **Section** field, select a section for the requisite.

4.  Click **New** to create a line, and then in the **Requisite type** field, select **Cell**.

5.  In the **Requisite** and **Description** fields, enter a requisite code and a description for the requisite. The **Attribute** field is updated with the XML attribute name. You can change the name if a different name is required.

6.  In the **Data type** and **Output type** fields, select the data type and output type of the requisite. For more information, see [(RUS) Requisites setup (form)](https://technet.microsoft.com/library/jj710719\(v=ax.60\)).

7.  In the **Extended data type** field, select the extended data type to verify the value of the requisite that is imported.

8.  In the Excel worksheet in the lower pane of the form, select the source cell for the requisite value.

9.  In the right section of the form, click **Add**, and then click **Yes**. A new line is created in the right section of the form.
    

    > [!NOTE]
    > <P>Click <STRONG>Go to</STRONG>, and verify that the selected cells in the worksheet contain the correct values that are used to create the requisite.</P>



10. In the **Prefix** field, enter the value that is added before the requisite, and in the **Postfix** field, enter the value that is added after the requisite.

After you create the lines, you can arrange them in the correct order. Select a line, and then click **Up** to move the line one position up, or click **Down** to move the line one position down.

## See also

[(RUS) Document templates (form)](https://technet.microsoft.com/library/jj923585\(v=ax.60\))

[(RUS) Requisites setup (form)](https://technet.microsoft.com/library/jj710719\(v=ax.60\))

[(RUS) Set up templates for electronic reporting](rus-set-up-templates-for-electronic-reporting.md)

  


