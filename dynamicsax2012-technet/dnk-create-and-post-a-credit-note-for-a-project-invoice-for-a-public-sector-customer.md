---
title: (DNK) Create and post a credit note for a project invoice for a public sector customer
TOCTitle: (DNK) Create and post a credit note for a project invoice for a public sector customer
ms:assetid: e3c59ed3-565e-4980-a4c1-773ca3fbde59
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh227429(v=AX.60)
ms:contentKeyID: 36059726
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- electronic invoicing
- OIOUBL
- project invoice
- credit note
audience: Application User
ms.search.region: Denmark
---

# (DNK) Create and post a credit note for a project invoice for a public sector customer 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Invoice proposals** and **Post invoice** forms to create and post a credit note for a project invoice and to generate the credit note as an .xml file. The .xml file is then converted to the Offentlig Information Online Universal Business Language (OIOUBL) format. You can generate electronic credit notes for customers for whom you have specified the European Article Numbering (EAN) number in the **EAN** field and selected the **eInvoice** check box in the **Customers** form.

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**.

2.  Double-click a project invoice that has been created and invoiced for a customer who an EAN number is specified for.

3.  In the **Projects** form, click the **Manage** tab, and then click **Invoice journals**.

4.  In the **Invoice journals** form, select an invoice journal line, and then click **Functions** \> **Select for credit note**.

5.  In the **Select for credit note** form, select the **Select** check box to specify the project invoice for the credit note.

6.  Click **OK**.

7.  In the **Projects** form, click **Invoice proposals**.

8.  In the **Invoice proposals** form, click **New** \> **Invoice proposals**.

9.  In the **Create invoice proposals** form, in the **Invoicing method** field, select **Credit notes** to specify that the transactions are to be credited.

10. Select the required transaction types to include the transactions in the credit note.

11. In the **From date** and **To date** fields, select the starting and ending dates to include project transactions posted to the project, and then in the **Invoice date** field, select the ledger posting date.

12. Click **OK**. The credit notes are created in the **Invoice proposals** form.

13. In the **Invoice proposals** form, click **Post**.

14. In the **Post invoice** form, select the **Posting** and **Print invoice** check boxes.

15. In the **Post invoice** form, click **OK** to post the credit note and generate the .xml file. The .xml file is converted to the OIOUBL format.

16. Close the forms.

When the batch job is processed, invoices for customers who have an EAN number assigned are generated as .xml files, and then converted to the OIOUBL format. The resulting OIOUBL files are created in the shared folder that is specified for the **EInvoiceFileTransform\_OIOUBL** batch job task for the project batch job.

## See also

[(DNK) Set up batch processing for OIOUBL electronic invoicing](dnk-set-up-batch-processing-for-oioubl-electronic-invoicing.md)

[Invoice proposals (form)](https://technet.microsoft.com/en-us/library/aa615408\(v=ax.60\))

[Post invoice proposals (form)](https://technet.microsoft.com/en-us/library/aa620017\(v=ax.60\))

[Invoice journals (form) (Project)](https://technet.microsoft.com/en-us/library/aa618187\(v=ax.60\))

[Select for credit note (form)](https://technet.microsoft.com/en-us/library/aa550205\(v=ax.60\))

  


