---
title: (FRA) Generate the DES report
TOCTitle: (FRA) Generate the DES report
ms:assetid: 3a03da63-3947-4425-b7bf-f1638340de3e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242210(v=AX.60)
ms:contentKeyID: 36056635
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- France
- DES report
---

# (FRA) Generate the DES report [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A VAT-registered entity in the European Union (EU) can generate a periodic list that includes the details of all of the sales transactions with other VAT-registered entities in the EU. This list is referred to as the European Sales List (ESL). For VAT-registered entities in France, you can generate the Déclaration Européenne de Services, or European Declaration of Services (DES), which is similar to the EU sales list. However, the DES report contains only the details about the service item transactions.


> [!NOTE]
> <P>You must set up sales tax codes and sales tax groups correctly because they contain information that is included in the DES report.</P>



You can print the DES report or save it as an XML file.

## Set up the export file format and the report layout

You must set up the export file format and the report layout before you can generate the DES report.

1.  Click **Organization administration** \> **Setup** \> **Foreign trade** \> **Foreign trade parameters**.

2.  Click **EU sales list**, and then in the **EU sales list** area, select the **Report cash discount** check box to report cash discounts by using the EU sales list.

3.  Select the **Transfer purchases** check box to transfer the purchase transactions to the EU sales list.

4.  In the **Report layout** field, select **Display amounts by rows** to display the amounts for each customer or vendor by row in the EU sales list report.

5.  In the **XSLT ID** field, select the XML style sheet identification code that is used to generate the EU sales list. The XSLT ID parameter contains metadata for a country-specific file format.

## Export the DES report as an XML file

Before you can export the DES report, you must generate the EU sales list. For more information, see [Generate the EU sales list](generate-the-eu-sales-list.md).

After you generate the EU sales list, you can use the **EU reporting** form to export the DES report as an XML file.

1.  Click **Organization administration** \> **Periodic** \> **Foreign trade** \> **EU sales list**.

2.  Click **Transfer** to open the **Transfer transactions for EU sales list** form.

3.  Select the **Service** check box to include service transactions in the EU sales list.

4.  Click **Transfer** to transfer all of the service transactions to the EU sales list.

5.  Click **Reporting**, and then in the **EU reporting** form, in the **Reporting period** field, select **Not selected**, **Monthly**, or **Quarterly** as the declaration type.

6.  In the **From date** field, select the starting date of the reporting period.

7.  If you selected **Not selected** in the **Reporting period** field, then in the **To date** field, select the ending date of the reporting period.

8.  Select the **Generate file** check box to generate the DES report in a specific file format.

9.  In the **File name** field, enter the path and the file name for the DES report export file.

10. Click **OK** to generate the DES report as an XML file.

## See also

[EU Reporting (report)](https://technet.microsoft.com/en-us/library/aa585352\(v=ax.60\))

[EU sales list (form)](https://technet.microsoft.com/en-us/library/aa596355\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

