---
title: (BEL) Generate customer payment files and upload them using CIS
TOCTitle: (BEL) Generate customer payment files and upload them using CIS
ms:assetid: 2e496e17-5299-48cc-82b9-4329d7c7ab49
ms:mtpsurl: https://technet.microsoft.com/library/Hh208526(v=AX.60)
ms:contentKeyID: 36056275
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Belgium
- IBS
- CIS
- customer payment file
audience: Application User
ms.search.region: Belgium
---

# (BEL) Generate customer payment files and upload them using CIS 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can upload payment files using Client Isabel Synchronizer (CIS) to transfer generated payment files from Microsoft Dynamics AX 2012 directly into Isabel 6. Before you can upload payment files to the Isabel Business Suite (IBS) server, you must generate the payment files. To generate the files, create the payment or domiciliation proposal in the payment journal. You can modify the payment details until they are uploaded to the IBS server.

## Generate customer payment files

1.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Create a new journal and click **Lines** to open the **Journal voucher** form.

3.  Enter the required details for the journal line.

4.  In the **Method of payment** field, select the required method of payment.

5.  Click **Functions** \> **Generate payments** to open the **Generate payments** form.

6.  In the **Method of payment** field, select the required method of payment.

7.  Select the **Show format dialog** check box to display the payment format dialog.

8.  Click **OK** to open the **Isabel (be)** form. By default, the upload path specified in the **IBS parameters** form is displayed in the **File name** field. You cannot modify the path.

9.  Enter the file name of the payment file, in the **File name** field. By default, the **Processing date** field displays the current date. You can modify the processing date if required.

10. Click **OK** to generate the payment file.

If the value for the **Upload mode** field in the **IBS parameters** form is **Attended mode**, the following actions take place when the payment files are generated:

  - The payment files are saved in the path specified in the **Upload folder** field of the **IBS parameters** form.

  - For every generated payment file, a record is added to the IBS logs in the **IBS transactions** form with the status **New**.

## Upload payment files using CIS

When you use CIS, you transfer generated payment files from Microsoft Dynamics AX 2012 directly to Isabel 6 portal. The first step is to select the payment files.

1.  Click **Cash and bank management** \> **Common** \> **IBS transactions**.

2.  Select the check box for each payment file to be uploaded.
    

    > [!NOTE]
    > <P>The payment files must be of the same type and cannot be larger than 50 MB. Each upload can contain up to 20 files.</P>



3.  Insert the Isabel smart card into the card reader.

4.  Click **Upload** to open the **Upload** form.

5.  Enter an email address for feedback on the upload process. This email address is automatically displayed for every subsequent upload.

6.  Click **OK** and then enter your Isabel password.
    
    If multiple Isabel certificates are present, Isabel 6 will open the **Choose a digital certificate** form. Select the correct certificate for your smart card, and click **OK**. After entering your PIN, click the button with the green flag to begin the upload process.

Once the connection is established with the Isabel 6 server, multiple .xml request and response documents are exchanged. If any error occurs during this process, the corresponding error code and message are displayed.

After a payment file is successfully uploaded, the Isabel 6 transactions are updated based on the information in the .xml documents. For each processed file, the selection box is cleared in the **IBS transactions** form and the status of the file is set as **Processed**. The following parameters are also updated:

  - Processed date

  - Processed user ID

  - Request ID

## See also

[(BEL) About CIS](bel-about-cis.md)

[(BEL) IBS parameters (form)](https://technet.microsoft.com/library/hh209077\(v=ax.60\))

[(BEL) Generate vendor payment files and upload them using CIS](bel-generate-vendor-payment-files-and-upload-them-using-cis.md)

  


