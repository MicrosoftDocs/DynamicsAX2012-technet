---
title: (CHE) Set up a method of payment for LSV+ payment export files
TOCTitle: (CHE) Set up a method of payment for LSV+ payment export files
ms:assetid: f99ae6ab-36ec-4cd2-b727-9194d18c4e2a
ms:mtpsurl: https://technet.microsoft.com/library/Gg243300(v=AX.60)
ms:contentKeyID: 36060060
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Switzerland
---

# (CHE) Set up a method of payment for LSV+ payment export files 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Methods of payment** form to set up a method of payment for Lastschriftenverfahren (LSV+) payment export files.

1.  Click **Accounts receivable** \> **Setup** \> **Payment** \> **Methods of payment**.

2.  Press CTRL+N to create a new line, and enter an identifier, such as **LSV**, in the **Method of payment** field.

3.  In the **Period** field, select **Invoice**. Each invoice is settled with only one payment.

4.  Click the **General** FastTab. In the **Account type** field, select **Bank**.

5.  In the **Payment account** field, select a bank account that is set up with the LSV+ information in the **Bank accounts** form.

6.  Click the **File formats** FastTab. In the **Export format** field, select **LSV (CH)**.
    

    > [!NOTE]
    > <P>If the field list is empty, click <STRONG>Setup</STRONG> and select from the available formats.</P>



7.  Enter other information as required for the method of payment.

8.  Close the form to save your changes.

## See also

[(CHE) Swiss LSV+ electronic payment format](che-swiss-lsv-electronic-payment-format.md)

  


