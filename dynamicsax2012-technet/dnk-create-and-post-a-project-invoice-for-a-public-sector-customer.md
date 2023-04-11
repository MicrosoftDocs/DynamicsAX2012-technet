---
title: (DNK) Create and post a project invoice for a public sector customer
TOCTitle: (DNK) Create and post a project invoice for a public sector customer
ms:assetid: 7cc09542-a13f-4607-87b7-306fb3c377f5
ms:mtpsurl: https://technet.microsoft.com/library/Gg213134(v=AX.60)
ms:contentKeyID: 36058268
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- electronic invoices
- EAN
- public sector customer
audience: Application User
ms.search.region: Denmark
---

# (DNK) Create and post a project invoice for a public sector customer 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can generate electronic invoices for customers for whom you have specified the European Article Numbering (EAN) number in the **EAN** field and selected the **eInvoice** check box in the **Customers** form. Verify that a contact person is assigned for the customer in the **Customers** form.

## Set up a funding source associated with eInvoice parameters for a project contract

You must assign a funding source for a project contract. You must also set up eInvoice parameters for the funding source before you can generate a project invoice as an .xml file. Use the **Funding source details** form to set up a funding source for a project contract.

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **Project contracts**.

2.  Double-click a project contract or click **Project contract** to create a project contract. For more information, see [Create a project contract](create-a-project-contract.md).

3.  In the **Project contracts** form, click the **Funding sources** FastTab, and then click **Add** to create a funding source for the project contract. For more information, see [Assign funding sources to a project contract](assign-funding-sources-to-a-project-contract.md).

4.  In the **Customer** field, select the customer account for which the EAN number is specified and the **eInvoice** check box is selected.

5.  Click **Details**, and then in the **Funding source details** form, click the **Other** FastTab.

6.  In the **Customer requisition** and **Customer reference** fields, enter a customer requisition number and a customer reference number.

7.  Select the **Line-specific** check box to specify dimension accounts for each project invoice line, and then in the **Dimension account** field, enter a dimension account number.
    

    > [!NOTE]
    > <P>Clear the <STRONG>Line-specific</STRONG> check box to specify a dimension account for the project invoice.</P>



8.  Close the forms.

## Post a project invoice for a public sector customer

Use the **Invoice proposals** and **Post invoice** forms to create and post a project invoice and to generate the invoice as an .xml file. The .xml file is then converted to the Offentlig Information Online Universal Business Language (OIOUBL) format. You must select the project contract that the funding source is assigned to. Verify that the eInvoice parameters are set up for the funding source.

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**.

2.  Double-click a project or click **Project** to create a project. For more information, see [Create a project](create-a-project.md).

3.  In the **Projects** form, click the **Manage** tab, and then click **Invoice proposals**.

4.  In the **Invoice proposals** form, click **New** \> **Invoice proposals**.

5.  In the **Create invoice proposals** form, in the **Invoicing method** field, select **Invoices** to include the transactions that have been posted from journals and are ready to be invoiced.

6.  Select the required transaction types to include those transactions in the invoices.

7.  In the **From date** and **To date** fields, select the starting and ending dates to include project transactions posted to the project, and then in the **Invoice date** field, select the ledger posting date.

8.  Click **OK**. The project invoices are created in the **Invoice proposals** form.

9.  In the **Invoice proposals** form, click **Post**.

10. In the **Post invoice** form, select the **Posting** and **Print invoice** check boxes.

11. In the **Post invoice** form, click **OK** to post the project invoice and generate the .xml file. The .xml file is converted to the OIOUBL format.

12. Close the forms.

When the batch job is processed, invoices for customers who have an EAN number assigned are generated as .xml files, and then converted to the OIOUBL format. The resulting OIOUBL files are created in the shared folder that is specified for the **EInvoiceFileTransform\_OIOUBL** batch job task for the project batch job.

## See also

[(DNK) Set up batch processing for OIOUBL electronic invoicing](dnk-set-up-batch-processing-for-oioubl-electronic-invoicing.md)

[Funding source details (form)](https://technet.microsoft.com/library/hh209607\(v=ax.60\))

[Project contracts (form)](https://technet.microsoft.com/library/aa586038\(v=ax.60\))

[Invoice proposals (form)](https://technet.microsoft.com/library/aa615408\(v=ax.60\))

  


