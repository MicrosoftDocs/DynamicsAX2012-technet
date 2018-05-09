---
title: (DNK) Create and post a customer invoice for a public sector customer
TOCTitle: (DNK) Create and post a customer invoice for a public sector customer
ms:assetid: 84e6ff83-10e8-483e-a974-d5a1bb7ca36b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg213173(v=AX.60)
ms:contentKeyID: 36058400
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (DNK) Create and post a customer invoice for a public sector customer 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Sales order** and **Posting invoice** forms to create and post a sales order invoice and to generate the invoice as an .xml file. The .xml file is then converted to the Offentlig Information Online Universal Business Language (OIOUBL) format. You can generate electronic invoices for customers for whom you have specified a European Article Numbering (EAN) number in the **EAN** field and selected the **eInvoice** check box in the **Customers** form.

1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Double-click a sales order or click **Sales order** to create a sales order

3.  On the **Action Pane**, click **Header view**.

4.  Click the **General** FastTab, and then in the **Contact** field, select a contact person.

5.  In the **Customer requisition** and **Customer reference** fields, enter the customer requisition number and customer reference number.

6.  Click the **Setup** FastTab, and then in the **Dimension account** field, enter a dimension account number for the sales order header.
    
    –or–
    
    Click the **Setup** FastTab, select the **Line-specific** check box to specify dimension accounts for each sales order line. On the **Action Pane**, click **Line view**, and then click the **Line details** FastTab. Click the **Setup** tab, and then in the **Dimension account** field, enter a dimension account number.

7.  On the **Action Pane**, click the **Invoice** tab, and then click **Invoice**.

8.  In the **Posting invoice** form, select the **Posting** and **Print invoice** check boxes.

9.  Click **Printer setup** \> **Invoice**.

10. In the **Print destination settings** form, select the required print options for the invoice, and then click **OK**.

11. In the **Posting invoice** form, click **OK** to post the sales order invoice and generate the .xml file. The .xml file is converted to the OIOUBL format.

12. Close the forms.

When the batch job for electronic sales invoices is processed, invoices for customers who have an EAN number assigned are generated as .xml files, and then converted to the OIOUBL format. The resulting OIOUBL files are created in the shared folder that is specified for the **EInvoiceFileTransform\_OIOUBL** batch job task for the sales order batch job.

## See also

[(DNK) Set up batch processing for OIOUBL electronic invoicing](dnk-set-up-batch-processing-for-oioubl-electronic-invoicing.md)

[Sales posting (form)](https://technet.microsoft.com/en-us/library/aa550287\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

