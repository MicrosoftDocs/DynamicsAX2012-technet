---
title: Filter the data on a report
TOCTitle: Filter the data on a report
ms:assetid: bac81e73-3299-495c-981f-fe159323b91b
ms:mtpsurl: https://technet.microsoft.com/library/Gg724098(v=AX.60)
ms:contentKeyID: 35133457
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Filter the data on a report 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

By filtering the data that is displayed on a report, you can view only the data that is important to you. The following procedure shows how to filter the data on the **Customers** report. You can modify this procedure to filter the data on the report that you are working with.

1.  Open the module that contains the data that you want to print. For example, to print the **Customers** report, open the **Accounts receivable** module.

2.  On the module’s area page, in the **Reports** section, click the report that you want to print. For example, to print the **Customers** report, click **Customer** \> **Customers**.
    
    A form is displayed that lists the fields that the data on the report is filtered by. The form also displays the destination that the report is printed to.

3.  Click **Select**. An inquiry form is displayed. This form is used to filter the data on the report.

4.  Click the **Range** tab. The **Range** tab displays the fields that you can filter the data on the report by.

5.  To add a field, click **Add**. Then follow these steps:
    
    1.  In the **Table** field, select the table that contains the field that you want to filter data by.
    
    2.  In the **Field** field, select the field that you want to filter data by.
    
    3.  In the **Criteria** field, select the data that you want to display on the report.
    
    For example, suppose you want to filter the **Customers** report so that it displays only those customers who receive a discount of 5 percent when they pay their bill in 30 days. In this scenario, you would follow these steps:
    
    1.  In the **Table** field, select **Customers**.
    
    2.  In the **Field** field, select **Customers**.
    
    3.  In the **Criteria** field, select **0.5%D30**.

6.  To remove a field, select the row that contain the field and then click **Remove**.

7.  Click **OK** to close the inquiry form.

8.  Click **Destinations ...** to specify how you want to print the report.

9.  Click **OK** to print the report.

## See also

[Print or email a report](print-or-email-a-report.md)

  


