---
title: (BEL) Generate vendor payment files and upload them using CIS
TOCTitle: (BEL) Generate vendor payment files and upload them using CIS
ms:assetid: d885f830-a83b-4770-8be7-81897051e681
ms:mtpsurl: https://technet.microsoft.com/library/Hh227395(v=AX.60)
ms:contentKeyID: 36059642
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Belgium
---

# (BEL) Generate vendor payment files and upload them using CIS 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can upload payment files by using Client Isabel Synchronizer (CIS) to transfer generated payment files from Microsoft Dynamics AX 2012 directly into Isabel 6. Before you can upload payment files to the Isabel Business Suite (IBS) server, you must generate the payment files. To generate the files, create the payment or domiciliation proposal in the payment journal. You can modify the payment details until they are uploaded to the IBS server.

For information on uploading payment files, see [(BEL) Generate customer payment files and upload them using CIS](bel-generate-customer-payment-files-and-upload-them-using-cis.md).

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Create a new journal and click **Lines** to open the **Journal voucher** form.

3.  Enter the required details for the journal line.

4.  In the **Method of payment** field, select the required method of payment.

5.  Click **Functions** \> **Generate payments** to open the **Generate payments** form.

6.  In the **Method of payment** field, select the required method of payment.

7.  Select the **Show format dialog** check box to display the payment format dialog.

8.  Click **OK** to open the **Isabel (be)** form. By default, the upload path specified in the **IBS parameters** form is displayed in the **File name** field. You cannot modify the path.

9.  Enter the file name of the payment file in the **File name** field. By default, the **Processing date** field displays the current date. You can modify the processing date if required.

10. Click **OK** to generate the payment file.

## See also

[(BEL) About CIS](bel-about-cis.md)

[(BEL) Generate customer payment files and upload them using CIS](bel-generate-customer-payment-files-and-upload-them-using-cis.md)

  


