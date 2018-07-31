---
title: (CHE) Create an LSV+ payment file
TOCTitle: (CHE) Create an LSV+ payment file
ms:assetid: f1be7bdc-6124-4964-b0e4-35c8c220db9f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg243278(v=AX.60)
ms:contentKeyID: 36059956
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Switzerland
---

# (CHE) Create an LSV+ payment file 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Swiss electronic payment system allows companies to deduct customer payments directly from a customer’s bank, also known as direct debit or Lastschriftenverfahren (LSV). Use this procedure to create a direct debit payment file that you can send to the bank or to a payment clearing service.

1.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Press CTRL+N to create a new journal and click **Lines**.

3.  Click **Functions** \> **Generate payments** to open the **Generate payments** form.

4.  Select the **Export format** option, and in the **Export format** field, select the **LSV (CH)** export file format.

5.  Click **Dialog** to open the **LSV (CH)** form.

6.  In the **Currency** field, select either Swiss franc (CHF) or Euro (EUR). Each LSV+ file can contain transactions for only one currency.

7.  In the **Processing date** field, enter the requested processing date for the bank or payment clearing service provider. This date is included in the export file.
    

    > [!NOTE]
    > <P>The requested processing date should be at least three days after the date that you will send the file to the bank or to the payment clearing service.</P>



8.  Select the **Record per line** check box to create a new line for each record.

9.  In the **File name** field, enter the location and file name for the payment file.

10. To print a control report, select the **Control report** check box. To set up printing options, click **Control report**.

11. To print a payment order report to send to the bank, also known as a bank payment order, select the **Payment order** check box. To set up printing options, click **Payment order**.

12. To print a payment advice report to send to customers, select the **Print payment advice** check box. To set up printing options, click **Payment advice**.

13. Click **OK** to close the form.

14. In the **Generate payments** form, click **OK** to create the payment file and print the payment advice report.

15. Close the forms to save your changes.

## See also

[(CHE) Swiss LSV+ electronic payment format](che-swiss-lsv-electronic-payment-format.md)

[(CHE) Set up a method of payment for LSV+ payment export files](che-set-up-a-method-of-payment-for-lsv-payment-export-files.md)

[(CHE) Set up an LSV+ method of payment for a customer](che-set-up-an-lsv-method-of-payment-for-a-customer.md)

  


