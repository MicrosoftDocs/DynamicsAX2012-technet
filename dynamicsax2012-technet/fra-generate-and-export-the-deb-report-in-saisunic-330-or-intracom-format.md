---
title: (FRA) Generate and export the DEB report in SAISUNIC 330 or INTRACOM format
TOCTitle: (FRA) Generate and export the DEB report in SAISUNIC 330 or INTRACOM format
ms:assetid: 9eeb4812-fabb-4137-a6b3-6a2d0b4378eb
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh209442(v=AX.60)
ms:contentKeyID: 36058754
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (FRA) Generate and export the DEB report in SAISUNIC 330 or INTRACOM format [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can generate the trade of goods and services (DEB) report in the SAISUNIC 330 or INTRACOM electronic file format. The updated formats include the single-digit Nomenclature Générale des Produits (NGP), or national item codes. Use the following procedures to transfer Intrastat transactions and export Intrastat information to generate the DEB report.

## Transfer Intrastat transactions from packing slips and invoices to the Intrastat form

You must transfer transactions from packing slips and invoices to the **Intrastat** form before you export the DEB report in the SAISUNIC 330 or INTRACOM format.

You can transfer the following invoices to the **Intrastat** form:

  - Vendor invoices that have a status of **Invoiced**

  - Customer invoices that have a status of **Invoiced**

  - Project invoices that have a status of **Invoiced**

  - Free text invoices that have a status of **Invoiced**

You can specify an NGP code when you manually enter or modify transactions in the **Intrastat** form, if required. For more information, see [About Intrastat](about-intrastat.md).

Use the following procedure to transfer Intrastat transactions to the **Intrastat** form.

1.  Click **Organization administration** \> **Periodic** \> **Foreign trade** \> **Intrastat**.

2.  Click **Transfer FR**.

3.  Select one or more of the following check boxes:
    
      - **Free text invoice** – Transfer the free text invoice transactions.
    
      - **Customer invoice** – Transfer the customer invoice transactions.
    
      - **Customer packing slips** – Transfer the customer packing slip transactions.
    
      - **Vendor invoice** – Transfer the vendor invoice transactions.
    
      - **Vendor product receipts** – Transfer the vendor packing slip transactions.
    
      - **Project invoice** – Transfer the project invoice transactions.

4.  Click **OK** to transfer the selected transactions to the **Intrastat** form.

5.  Select a transaction, and then on the **General** tab, in the **NGP** field, select or modify the NGP code, if required.

6.  Click **Validate** to specify the validation criteria, such as date and shipment batch to validate the Intrastat transactions.

7.  Click **OK** to validate the Intrastat transactions.

## Export Intrastat information to generate the DEB report

Use the **Create Intrastat diskette in French layout** form to generate and export the DEB report in the SAISUNIC 330 or INTRACOM format.

1.  Click **Organization administration** \> **Periodic** \> **Foreign trade** \> **Intrastat**.

2.  Select a validated transaction, and then click **Output** \> **Diskette FR** to open the **Create Intrastat diskette in French layout** form.

3.  In the **File name** field, select the path and file name for the DEB report.

4.  Select the **Only corrections** check box to include only the corrections in the DEB report.

5.  In the **Month** field, select the month for which the DEB report is generated.

6.  Select the **Export** check box to include export transactions.

7.  Select the **Import** check box to include import transactions.

8.  In the **File format** field, select **SAISUNIC** or **INTRACOM** as the file format.

9.  Click **OK** to generate the report in the specified file path.

## See also

[(FRA) Set up a French national item (NGP) code](fra-set-up-a-french-national-item-ngp-code.md)

[(FRA) Create and post a free text invoice with an NGP code](fra-create-and-post-a-free-text-invoice-with-an-ngp-code.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

