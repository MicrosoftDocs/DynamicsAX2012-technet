---
title: (BRA) Export RPS files
TOCTitle: (BRA) Export RPS files
ms:assetid: 7e0c8f94-564a-43e1-9478-3a5c78880036
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ710544(v=AX.60)
ms:contentKeyID: 49384435
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Export
- Brazil
- (BRA)
- RPS file
- export file
audience: Application User
ms.search.region: Brazil
---

# (BRA) Export RPS files 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Export RPS file** form to export the Recibo provisório de Serviço (RPS) files that can be submitted to São Paulo City Hall.

1.  Click **Accounts receivable** \> **Periodic** \> **Electronic fiscal document for services** \> **Export RPS file**.

2.  In the **From date** field, select the starting date of the period for which the RPS files are exported.

3.  In the **To date** field, select the ending date of the period for which the RPS files are exported.

4.  In the **From customer** field, select the first customer account number in the range of customer accounts to include in the RPS files.

5.  In the **To customer** field, select the last customer account number in the range of customer accounts to include in the RPS files.

6.  In the **From RPS** field, enter the first invoice number in the range of invoices to include in the RPS files.

7.  In the **To RPS** field, enter the last invoice number in the range of invoices to include in the RPS files.

8.  In the **Fiscal establishment ID** field, select the identifier of the fiscal establishment to include in the RPS files.

9.  In the **Fiscal document type** field, select the type of fiscal document to include in the RPS files.
    

    > [!NOTE]
    > <P>You can select only the fiscal document types that are defined for the fiscal establishment that you selected in the <STRONG>Fiscal establishment ID</STRONG> field.</P>



10. In the **File name** field, select or enter the path and file name of the RPS file.

11. Select the **Include previously exported RPS** check box to include an RPS file that was already processed.

12. Click **OK** to export the RPS files.

When you export an RPS file, a text file is generated based on the export file layout group that is specified in the **Export file layout group** field in the **Fiscal document types** form for the selected fiscal document type.

## See also

[(BRA) Export RPS file (form)](https://technet.microsoft.com/en-us/library/jj710498\(v=ax.60\))

[(BRA) About electronic fiscal document for services reporting for Sao Paulo](bra-about-electronic-fiscal-document-for-services-reporting-for-sao-paulo.md)

  


