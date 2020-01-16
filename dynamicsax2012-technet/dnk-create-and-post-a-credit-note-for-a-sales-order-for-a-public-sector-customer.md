---
title: (DNK) Create and post a credit note for a sales order for a public sector customer
TOCTitle: (DNK) Create and post a credit note for a sales order for a public sector customer
ms:assetid: cf47b4af-449b-4c00-bdf6-40f0406af962
ms:mtpsurl: https://technet.microsoft.com/library/Hh242913(v=AX.60)
ms:contentKeyID: 36059476
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- credit notes
- sales order
- public sector customer
- create credit notes
- post a credit note
audience: Application User
ms.search.region: Denmark
---

# (DNK) Create and post a credit note for a sales order for a public sector customer 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Create credit note** and **Posting invoice** forms to create and post a credit note for a sales order and to generate the credit note as an .xml file. The .xml file is then converted to the Offentlig Information Online Universal Business Language (OIOUBL) format. You can generate electronic credit notes for customers for whom you have specified a European Article Numbering (EAN) number in the **EAN** field and selected the **eInvoice** check box in the **Customers** form.

1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Select a sales order line that has been created and invoiced for the customer who the EAN number is specified for.

3.  On the **Action Pane**, click the **Sell** tab, and then click **Credit note**.

4.  In the **Create credit note** form, select the **Select all** check box to select all the transactions in the sales order to create credit notes for, or in the lower pane, select the **Mark** check box to select a specific transaction in the sales order.

5.  Click **OK**. The details of the selected transaction are updated with the negative amount in the **Sales order** form.

6.  On the **Action Pane**, click the **Invoice** tab, and then click **Invoice**.

7.  In the **Posting invoice** form, select the **Posting** and **Print invoice** check boxes.

8.  Click **Printer setup** \> **Invoice**.

9.  In the **Print destination settings** form, select the required print options for the invoice, and then click **OK**.

10. In the **Posting invoice** form, click **OK** to post the sales order invoice and generate the .xml file. The .xml file is converted to the OIOUBL format.

11. Close the forms.

When the batch job for the electronic sales invoices is processed, invoices for customers who have an EAN number assigned are generated as .xml files, and are then converted to the OIOUBL format. The resulting OIOUBL files are created in the shared folder that is specified for the **EInvoiceFileTransform\_OIOUBL** batch job task for the sales order batch job.

## See also

[(DNK) Set up batch processing for OIOUBL electronic invoicing](dnk-set-up-batch-processing-for-oioubl-electronic-invoicing.md)

[Sales posting (form)](https://technet.microsoft.com/library/aa550287\(v=ax.60\))

[Sales posting (form)](https://technet.microsoft.com/library/aa550287\(v=ax.60\))

  


