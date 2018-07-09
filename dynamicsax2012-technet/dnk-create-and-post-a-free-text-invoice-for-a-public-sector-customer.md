---
title: (DNK) Create and post a free text invoice for a public sector customer
TOCTitle: (DNK) Create and post a free text invoice for a public sector customer
ms:assetid: 2f9683a9-0e33-4e1b-b3d1-146a013ddff4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg231025(v=AX.60)
ms:contentKeyID: 36056300
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- free text invoices
- post free text invoices
---

# (DNK) Create and post a free text invoice for a public sector customer [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Free text invoice** and **Post free text invoice** forms to create and post a free text invoice and generate the invoice as an .xml file. The .xml file is then converted to the Offentlig Information Online Universal Business Language (OIOUBL) format. You can generate electronic invoices for customers for whom you have specified a European Article Numbering (EAN) number in the **EAN** field and selected the **eInvoice** check box in the **Customers** form.

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  Double-click a free text invoice or click **Free text invoice** to create a free text invoice. For more information, see [Key tasks: Free text invoices](key-tasks-free-text-invoices.md).

3.  On the **Action Pane**, click **Header view**, and then click the **General** FastTab.

4.  Select the **Line-specific** check box to specify dimension accounts for each free text invoice line. You can enter a dimension account number in the **Dimension account** field on the **Line details** FastTab in **Line view**.
    

    > [!NOTE]
    > <P>If you clear the <STRONG>Line-specific</STRONG> check box, you can specify the dimension account for the free text invoice in the <STRONG>Dimension account</STRONG> field on the <STRONG>General</STRONG> FastTab in <STRONG>Header view</STRONG>.</P>



5.  Click the **Customer** FastTab, and then in the **Customer requisition** and **Customer reference** fields, enter the customer requisition number and customer reference number.

6.  In the **Contact** field, select the name of the contact person.

7.  On the **Action Pane**, click **Post** \> **Post**.

8.  In the **Post free text invoice** form, select the **Posting** and **Print invoice** check boxes.

9.  Click **Printer setup** \> **Invoice**.

10. In the **Print destination settings** form, select the required print options, and then click **OK**.

11. In the **Post free text invoice** form, click **OK** to post the free text invoice and generate the .xml file. The .xml file is converted to the OIOUBL format.

12. Close the forms.

When the batch job for electronic sales invoices is processed, invoices for customers who have an EAN number assigned are generated as .xml files. The .xml files are then converted to the OIOUBL format. The resulting OIOUBL files are created in the shared folder that is specified for the **EInvoiceFileTransform\_OIOUBL** batch job task for the sales order batch job.

## See also

[(DNK) Set up batch processing for OIOUBL electronic invoicing](dnk-set-up-batch-processing-for-oioubl-electronic-invoicing.md)

[(DNK) Set up customer accounts for OIOUBL electronic invoicing](dnk-set-up-customer-accounts-for-oioubl-electronic-invoicing.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

