---
title: (EEUR) Set up query parameters for cell operations
TOCTitle: (EEUR) Set up query parameters for cell operations
ms:assetid: ebaa42bf-63ae-4bca-ae6a-4369b8b29594
ms:mtpsurl: https://technet.microsoft.com/library/JJ911241(v=AX.60)
ms:contentKeyID: 52075309
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Czech Republic, Estonia, Hungary, Latvia, Lithuania, Poland, Russia
---

# (EEUR) Set up query parameters for cell operations 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Query wizard** form that is provided by the Russian financial reports generator (FRG) to set up query parameters to calculate values for report cells.

1.  Click **General ledger** \> **Setup** \> **Financial reports generator** \> **Financial reports generator**.

2.  Select a line, and then click **Setup**.

3.  In the lower pane, click **Add**, and then in the **Line type** field, select **Function query**.

4.  Click **Setup** \> **Edit the query**.

5.  Select the **Show system names of tables, fields, and methods** check box to view the names for tables and fields in the query wizard.

6.  Click **Next \>**, and then in the **All tables** list, select the table that the calculation is performed on, and then click **\>** to move it to the **Selected tables** field.

7.  Click **\>** to move the selected table to the **Selected tables** list.

8.  In the **Tables that are related to the %1** list, select additional tables, and then click **\>** to move them to the **Selected tables** field.
    

    > [!NOTE]
    > <P>Only tables that are linked to the selected main table are available.</P>



9.  Click **Next \>**, and then in the **Available fields:** list, select the field to use as the data field for the report cell.
    

    > [!NOTE]
    > <P>Only the numerical fields from the selected main table are available.</P>



10. Click **\>**. The selected field name is displayed in the **Field name** field.

11. Select **Average**, **Sum**, **Minimum**, **Maximum**, or **Quantity** as the calculation for the selected field.

12. Click **Next \>**, and then in the **Available fields:** list, select the field that has the base date from which you want to generate a report.

13. Click **\>**. The selected field name is displayed in the **Field name** field.

14. In the **Period** field, enter a value if it is different from the default value that is determined for the cell or report.

15. Click **Next \>**, and then in the **Available fields:** list, select the fields that are used to filter data.

16. Click **\>** to move the selected field to the **Selected fields** list.

17. Click **Next \>**, and then click **Finish** to create and save the query with the specified parameters.

18. Click **Setup** \> **Edit the query** to open the **Inquiry** form, where you can edit the query if required.

## See also

[(EEUR) Field setup (form)](https://technet.microsoft.com/library/jj910976\(v=ax.60\))

[(EEUR) Query wizard (form)](https://technet.microsoft.com/library/jj710772\(v=ax.60\))

  


