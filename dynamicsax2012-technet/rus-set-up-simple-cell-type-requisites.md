---
title: (RUS) Set up simple cell type requisites
TOCTitle: (RUS) Set up simple cell type requisites
ms:assetid: baff70cb-27ec-4a75-b1ea-ba4fa59f8c50
ms:mtpsurl: https://technet.microsoft.com/library/JJ677681(v=AX.60)
ms:contentKeyID: 49384983
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- templates
- requisites
- cell requisites
- cell type
- document templates
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up simple cell type requisites 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Requisites setup** form to set up **Cell** requisite types that are used in document templates.

1.  Click **General ledger** \> **Setup** \> **Financial reports generator** \> **Document templates**.

2.  Select a template, and then click **Setup**. Click **Open**. The Microsoft Excel worksheet opens in the lower pane of the form.
    

    > [!NOTE]
    > <P>If the worksheet opens in a new window, you must update the system register to open the worksheet in the lower pane of the form. For more information, see <A href="rus-update-the-system-register-for-electronic-reporting.md">(RUS) Update the system register for electronic reporting</A>.</P>



3.  In the **Section** field, select a section for the requisite.

4.  Click **New** to create a line.

5.  In the **Requisite type** field, select **Cell**.

6.  In the **Requisite** field, enter a requisite code. The **Attribute** field is updated with the XML attribute name. You can change the name if a different name is required.

7.  In the **Description** field, enter a description for the requisite.

8.  In the **Data type** field, select the data type of the requisite, from the following options:
    
      - **General** – The requisite can have any type of value.
    
      - **Numeric** – The requisite must be numeric. If a cell contains text, the imported value of the requisite is blank.
    
      - **Text** – The requisite can have any value.
    
      - **Date** – The requisite must be in date format. If a cell contains any other type of value, the value of the requisite is blank.
    
      - **Conditional** – The requisite depends on the value that is displayed in the cell when the requisite is imported. If the cell is not blank, the requisite value is updated with the value in the **Value** field in the right section of the **Requisites setup** form. Otherwise, the requisite value is updated with the value in the **Default** field.

9.  In the **Output type** field, select an output type for the requisite, from the following options:
    
      - **Optional** – The requisite is excluded from the report file if the requisite value is blank.
    
      - **Required** – The requisite is required and is always included in the report file. The requisite value cannot be blank.
    
      - **Predefined** – A requisite code must be available. The requisite value can be blank.

10. In the **Extended data type** field, select the extended data type to verify the value of the requisite that is imported.

11. In the Excel worksheet in the lower pane of the form, select the source and target cells for the requisite value.

12. In the left section of the form, click **Select**, and then click **Yes** to change the area for the requisite. A new line is created in the right section of the form, and the **Cell** field is updated with the selected cell number.
    

    > [!NOTE]
    > <P>The order of requisites that are in the same section is the same as the order in the output text file. You can change the location of the requisites in the right section of the form.</P>



## See also

[(RUS) Document templates (form)](https://technet.microsoft.com/library/jj923585\(v=ax.60\))

[(RUS) Requisites setup (form)](https://technet.microsoft.com/library/jj710719\(v=ax.60\))

  


