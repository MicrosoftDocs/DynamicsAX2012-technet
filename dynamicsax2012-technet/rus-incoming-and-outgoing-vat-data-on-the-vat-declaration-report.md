---
title: (RUS) Incoming and outgoing VAT data on the VAT declaration report
TOCTitle: (RUS) Incoming and outgoing VAT data on the VAT declaration report
ms:assetid: 5cb94f05-7185-4907-bce7-1ab9acdce4c8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ665424(v=AX.60)
ms:contentKeyID: 49387512
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Incoming and outgoing VAT data on the VAT declaration report 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can include incoming and outgoing value-added tax (VAT) data on the VAT declaration report. The VAT data is displayed in sections on the report. You can set up report cells for each section of the VAT declaration by using predefined requisites for VAT declaration.


> [!NOTE]
> <P>The VAT declaration report can be generated in both .xls and .xml formats.</P>



Before you can generate the VAT declaration report with incoming and outgoing VAT data, you must complete the following tasks:

  - Create a query of the **VAT declaration** type. You must select **VAT declaration** as the electronic reporting query type in the **Query type** field in the **Create query** form

  - Set up report codes in the **Report** form. For more information, see [(RUS) Set up the functions directory for electronic reporting](rus-set-up-the-functions-directory-for-electronic-reporting.md)

  - Create report cells for electronic reporting. For more information, see [(RUS) Create report cells for electronic reporting](rus-create-report-cells-for-electronic-reporting.md).

You must use the **Financial reports generator** report to generate the incoming and outgoing VAT details on the VAT declaration report. On the VAT declaration report, you can view tax information in specific sections that are classified based on their purposes. The columns within each section display information about tax details, such as the tax types and tax amounts that are included on the report.

## See also

[(RUS) Create report cells (form)](https://technet.microsoft.com/en-us/library/jj678529\(v=ax.60\))

  


