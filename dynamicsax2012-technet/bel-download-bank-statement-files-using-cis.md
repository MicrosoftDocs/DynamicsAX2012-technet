---
title: (BEL) Download bank statement files using CIS
TOCTitle: (BEL) Download bank statement files using CIS
ms:assetid: 6aba7bd5-3c4b-4d93-b4bc-f768bfc62d95
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242610(v=AX.60)
ms:contentKeyID: 36057983
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- download
- Belgium
- CIS
- payment file
audience: Application User
ms.search.region: Belgium
---

# (BEL) Download bank statement files using CIS 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

After you review the processed bank files that are ready for download from Isabel 6, you can download the files using the **IBS transactions** form. The value of the **Download mode** field in the **IBS parameters** form cannot be **None**.

1.  Click **Cash and bank management** \> **Common** \> **IBS transactions**.

2.  Click **Download** to open the **Download** form.

3.  In the **From date** field, select the starting date for the files to be downloaded.

4.  Click **OK** to begin the download.

The interactions that take place between Microsoft Dynamics AX and the Isabel 6 server consist of an exchange of XML documents similar to the interactions during the upload process. After each file is successfully downloaded, a report entry is made in the **IBS transactions** form. You can differentiate between the uploaded and downloaded files in this form with the direction (Upload or Download). After completing the download, you can process the downloaded bank statement files.

The processed bank statement file is now available in the **IBS transactions** form, and contains the following details:

  - Processed date

  - Processed user ID

  - Request ID

  - Process status

The downloaded bank statement files are in CODA format. You can use the **Bank statement** form to process them. For more information, see [Bank statement (form)](https://technet.microsoft.com/en-us/library/aa600290\(v=ax.60\)).

## See also

[(BEL) About CIS](bel-about-cis.md)

[(BEL) CODA (form)](https://technet.microsoft.com/en-us/library/aa600713\(v=ax.60\))

[(BEL) Generate vendor payment files and upload them using CIS](bel-generate-vendor-payment-files-and-upload-them-using-cis.md)

[(BEL) Generate customer payment files and upload them using CIS](bel-generate-customer-payment-files-and-upload-them-using-cis.md)

  


