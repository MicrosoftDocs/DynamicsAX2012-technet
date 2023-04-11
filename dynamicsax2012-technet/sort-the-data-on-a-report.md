---
title: Sort the data on a report
TOCTitle: Sort the data on a report
ms:assetid: fe8de4c1-14fa-4588-a9f9-1e850159d948
ms:mtpsurl: https://technet.microsoft.com/library/Gg751571(v=AX.60)
ms:contentKeyID: 35133699
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Sort the data on a report 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can sort the data that is displayed on a report. The following procedure shows how to sort the data on the **Customers** report. You can modify this procedure to sort the data on the report that you are working with.

1.  Open the module that contains the data to print. For example, to print the **Customers** report, open the **Accounts receivable** module.

2.  On the module’s area page, in the **Reports** section, click the report to print. For example, to print the **Customers** report, click **Customer** \> **Customers**.
    
    A form is displayed that lists the fields that the data on the report is filtered by. The form also displays the destination that the report is printed to.

3.  Click **Select**. An inquiry form is displayed. This form is used to sort the data on the report.

4.  Click the **Sorting** tab. The **Sorting** tab displays the fields that you can sort the data on the report by.

5.  To add a field, click **Add**. Then follow these steps:
    
    1.  In the **Table** field, select the table that contains the field that you want to sort the data by.
    
    2.  In the **Field** field, select the field that you want to sort the data by.
    
    3.  In the **Search direction** field, select whether you want to sort the data in ascending or descending order.
    
    For example, suppose you want to sort the **Customers** report by the customer’s credit limit. In this scenario, you would follow these steps:
    
    1.  In the **Table** field, select **Customers**.
    
    2.  In the **Field** field, select **Customers**.
    
    3.  In the **Criteria** field, select **Credit limit**.
    
    4.  In the **Search direction**, select **Ascending** or **Descending**.

6.  To remove a field, select the row that contain the field and then click **Remove**.

7.  Click **OK** to close the inquiry form.

8.  Click **Destinations ...** to specify how you want to print the report.

9.  Click **OK** to print the report.

## See also

[Print or email a report](print-or-email-a-report.md)

  


