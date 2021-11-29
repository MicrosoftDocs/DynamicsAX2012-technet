---
title: (RUS) Set up an expression requisite type
TOCTitle: (RUS) Set up an expression requisite type
ms:assetid: c642f32e-7d8e-487c-be91-fa82094b62a1
ms:mtpsurl: https://technet.microsoft.com/library/JJ677695(v=AX.60)
ms:contentKeyID: 49384994
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- requisite
- expression
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up an expression requisite type 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Queries** and **Fixed requisites** forms to set up a requisite for the name of an employee.

1.  Click **General ledger** \> **Setup** \> **Financial reports generator** \> **Queries**.

2.  Create a query for the **Electronic documents list** table and a related employee table. For more information, see [(RUS) Create a query for electronic reporting](rus-create-a-query-for-electronic-reporting.md).

3.  Close the form.

4.  Click **General ledger** \> **Setup** \> **Financial reports generator** \> **Fixed requisites**.

5.  Click **New** to create a line.

6.  In the **Requisite** field, enter an identification number for the requisite.

7.  In the **Name** field, enter Sender's last, first, and middle names.

8.  In the **Type** field, select **Expression**.

9.  On the **Expression** tab, click **New** to create a line.

10. In the **Query** field, select the query that is created for an employee table.

11. In the **Field name** field, select the field that is related to the last name of the employee.

12. In the **Prefix** and **Postfix** fields, enter the values that precede and follow the value of the selected field.

13. Repeat the last two steps for the fields that are related to the first and middle names of the employee.

## See also

[(RUS) Queries (form)](https://technet.microsoft.com/library/jj710734\(v=ax.60\))

[(RUS) Fixed requisites (form)](https://technet.microsoft.com/library/jj710680\(v=ax.60\))

[(RUS) Set up a fixed requisite](rus-set-up-a-fixed-requisite.md)

  


