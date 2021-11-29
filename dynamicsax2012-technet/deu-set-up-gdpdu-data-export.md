---
title: (DEU) Set up GDPdU data export
TOCTitle: (DEU) Set up GDPdU data export
ms:assetid: 8e40fa72-5700-45cb-9ee1-f49dc07795d7
ms:mtpsurl: https://technet.microsoft.com/library/Aa616006(v=AX.60)
ms:contentKeyID: 36058513
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Germany
---

# (DEU) Set up GDPdU data export 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Germany, tax auditors are allowed by law to access and verify data digitally from the electronic bookkeeping process during the statutory archiving period. There are three different ways to access the data for the tax authorities:

  - Direct access

  - Indirect access

  - Surrender of data media

The principles for data access and testing of digital documents are also referred to as Grundsätze zum Datenzugriff und zur Prüfbarkeit digitaler Unterlagen (GDPdU). In Microsoft Dynamics AX, the surrender of data media can be performed by using the GDPdU data export methods.

Use the **Data export definition groups** form to create definition groups for tables from which to export data. The resulting data file can be sent to a tax auditor.

## Create GDPdU definition groups

1.  Click **General ledger** \> **Periodic** \> **Data export** \> **Data export definition groups**.

2.  Press CTRL+N to create a new line.

3.  In the **Definition group** and **Name** fields, enter the name and description for the GDPdU table.

4.  Press CTRL+S to save the record.

## Create data export tables

1.  Click **General ledger** \> **Periodic** \> **Data export** \> **Data export definition groups**. Select the required definition groups, and then click **Data export tables** to open the **Data export tables** form.

2.  In the **Data export table** and **File name** fields, enter a data export table name and a file name, respectively.

3.  Press CTRL+S to save the record and make the **Data export fields** available.

## Create data export fields

1.  Click **General ledger** \> **Periodic** \> **Data export** \> **Data export definition groups**. Select the required definition groups, and then click **Data export tables** to open the **Data export tables** form.

2.  Click **Data export fields** to open the **Data export fields** form, and select the tables and fields that contain the necessary GDPdU data.

3.  Double-click the table to use, and then click **Next \>** to define the data export fields.

4.  Press CTRL+N to create a new line.

5.  In the **Data export field** and **Description** field, enter a name and description for the data to export.

6.  In the **Table** and **Field** fields, select the table and a field, respectively.

7.  Select the **Primary key** check box, if it is required.

8.  Repeat steps 3 through 6 to add more fields.

9.  Click **Finish**.

10. In the **Data export tables** form, select a date in the **Data export field for period** field. The value in this field is evaluated when determining the transactions that are included in the range of dates to export.

11. Close the forms to save your changes.

## See also

[GDPdU setup example](gdpdu-setup-example.md)

[(DEU) Export GDPdU data](deu-export-gdpdu-data.md)

[(DEU) Data export definition groups (form)](https://technet.microsoft.com/library/aa615425\(v=ax.60\))

[(DEU, FRA) Data export tables (form)](https://technet.microsoft.com/library/aa571461\(v=ax.60\))

[(DEU) Data export fields (form)](https://technet.microsoft.com/library/aa596357\(v=ax.60\))

[(DEU) Data export relations (form)](https://technet.microsoft.com/library/aa620743\(v=ax.60\))

  


