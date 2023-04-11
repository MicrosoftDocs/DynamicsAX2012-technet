---
title: (JPN) Create row definitions for a Japanese financial statement
TOCTitle: (JPN) Create row definitions for a Japanese financial statement
ms:assetid: eaef2ea8-fecf-4d4e-a700-4c66185a1f87
ms:mtpsurl: https://technet.microsoft.com/library/JJ664984(v=AX.60)
ms:contentKeyID: 49386568
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- financial statement
- row definitions
audience: Application User
ms.search.region: Japan
---

# (JPN) Create row definitions for a Japanese financial statement 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to create row definitions for a financial statement.

1.  Click **General ledger** \> **Reports** \> **Transactions** \> **Financial statement (traditional)**.

2.  On the **Overview** tab, press CTRL+N to create a new dimension set record for a particular financial statement.

3.  Click the **Setup** tab, and then select a dimension set for the dimension that is selected on the **Overview** tab.

4.  Click **General ledger** \> **Setup** \> **Financial statement (traditional)** \> **Row definition**. For more information about dimension sets, see [Create a financial dimension set](create-a-financial-dimension-set.md).

5.  Press CTRL+N to create a row definition that you can link to a financial statement, and to select the dimension set that applies to this row definition.

6.  Select the **Bi-column** check box to print two columns in the report.
    

    > [!NOTE]
    > <P>If you select the <STRONG>Bi-column</STRONG> check box, the <STRONG>Division</STRONG> field is activated in the <STRONG>Structure designer</STRONG> form. Use the <STRONG>Division</STRONG> field to set the alignment direction for the items in the <STRONG>Structure designer</STRONG> form.</P>



7.  Click **Structure designer** to open the **Structure designer** form to set up the row attributes.

8.  Click the **Create** icon, and enter a row name and a description in the **Row name** and **Row description** fields.

9.  Select the row type in the **Type** field.

10. Click the **Setup** tab on the right pane, and select the value.
    

    > [!NOTE]
    > <P>The <STRONG>Value</STRONG> field is available only when the row type is <STRONG>Dimension</STRONG>.</P>



11. Select the **Use amount type** check box to activate the **Amount type** field, and then select **Total period**, **Opening balance**, or **Ending balance** as an amount type.

12. Enter other details for the current row type, as needed.

13. Click the **Special report** tab to enter the required details, as needed.

14. In the **Line** field, specify the starting line number for the row.

15. In the **Division** field, select the alignment direction for the row on the financial report.
    

    > [!NOTE]
    > <P>This field is enabled only when the <STRONG>Bi-column</STRONG> check box is selected in the <STRONG>Row definition</STRONG> form or in the <STRONG>Financial statement</STRONG> form.</P>



16. Close the forms.

## See also

[(JPN) Create a Japanese financial statement](jpn-create-a-japanese-financial-statement.md)

  


