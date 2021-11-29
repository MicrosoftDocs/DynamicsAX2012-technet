---
title: (JPN) Print a Japanese financial statement
TOCTitle: (JPN) Print a Japanese financial statement
ms:assetid: 10877d0c-a18d-4c58-95e5-a9e52b9785b4
ms:mtpsurl: https://technet.microsoft.com/library/JJ711005(v=AX.60)
ms:contentKeyID: 49386416
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Print
- financial statement
- Japanese
- (JPN)
- Japan
audience: Application User
ms.search.region: Japan
---

# (JPN) Print a Japanese financial statement 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can export and print Japanese financial statements, such as balance sheets, profit and loss statements, and cash flow statements, by using Microsoft Excel.

1.  Click **General ledger** \> **Reports** \> **Transactions** \> **Financial statement (traditional)**.

2.  In the **Financial statement** field, select the financial statement to export.

3.  In the **Output type** field, select **Microsoft Excel**.

4.  In the **Primary dimension set** and **Secondary dimension set** fields, select the default group of financial dimensions or combinations of financial dimensions. For more information, see [Create a financial dimension set](create-a-financial-dimension-set.md).

5.  In the **From** and **To** fields, enter the first and last rows to print.

6.  In the **End date** field, select an end date for the financial statement.
    

    > [!NOTE]
    > <P>A financial statement has a predefined end date. By selecting an end date here, you may change the end date.</P>



7.  In the **Row definition for primary dimension set** and **Row definition for secondary dimension set** fields, select the row definitions that are used for the primary and secondary dimension sets on the financial statement.
    

    > [!NOTE]
    > <P>To print one financial statement for the value of each primary dimension set, select the <STRONG>Page break per primary dimension set</STRONG> check box. A separate page is printed for each primary dimension set, and the lines are based on the secondary dimension set. To print the primary dimension set as lines on a single financial statement, and the secondary dimension set as detailed information, clear the <STRONG>Page break per primary dimension set</STRONG> check box.</P>



8.  Click the **Save to** tab.

9.  In the **File name** field, select the file path and the name of the financial statement that you are exporting.

10. Click **OK** to export the financial statement in the specified file format and print a report.

## See also

[(JPN) Create a Japanese financial statement](jpn-create-a-japanese-financial-statement.md)

[Financial statement setup (form)](https://technet.microsoft.com/library/aa600912\(v=ax.60\))

  


