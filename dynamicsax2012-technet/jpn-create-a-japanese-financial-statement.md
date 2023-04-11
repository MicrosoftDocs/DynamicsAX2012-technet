---
title: (JPN) Create a Japanese financial statement
TOCTitle: (JPN) Create a Japanese financial statement
ms:assetid: db18e463-a44a-49da-a617-c77d81fdbd90
ms:mtpsurl: https://technet.microsoft.com/library/JJ664977(v=AX.60)
ms:contentKeyID: 49386561
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- financial statement
- Japanese
- JP - 00003
audience: Application User
ms.search.region: Japan
---

# (JPN) Create a Japanese financial statement 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can design a financial statement, and then produce financial statements for each of your financial periods, and for the entire year, in the Japanese format. You can export financial statements to Microsoft Excel.

1.  Click **General ledger** \> **Setup** \> **Financial statement (traditional)** \> **Financial statement (traditional)**.

2.  Click **New** to create a new line.

3.  Enter a short name and description in the **Financial statement** and **Description** fields.

4.  Select the category for the current financial report in the **Category** field. To generate reports in the Japanese format, select **Cash flow reports (JP)**.

5.  Enter the identification for the report in the **Report ID** field.

6.  In the lower pane, click **Add** to create columns for the financial report.

7.  Enter a name for each column, and select a type for each column in the **Name** and **Column type** fields.

8.  Select the **By row definition** check box to use the amount type that has been set up for the row definition in the **Structure designer** form.
    

    > [!NOTE]
    > <P>The <STRONG>By row definition</STRONG> check box is available only for amount columns.</P>



9.  Select the **Print** check box to print the selected column from the report form, and specify the number of rows to be used for the selected column.

10. In the lower pane, click the **Setup** tab, and then in the **Date interval code** field, select the date interval for which to generate the financial report.
    

    > [!NOTE]
    > <P>You can set up date interval codes in the <STRONG>Date intervals</STRONG> form. Click <STRONG>General ledger</STRONG> &gt; <STRONG>Setup</STRONG> &gt; <STRONG>Periods</STRONG> &gt; <STRONG>Date intervals</STRONG>.</P>



11. Close the form.

## See also

[(JPN) Print a Japanese financial statement](jpn-print-a-japanese-financial-statement.md)

  


