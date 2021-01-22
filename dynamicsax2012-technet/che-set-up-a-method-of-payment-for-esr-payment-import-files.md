---
title: (CHE) Set up a method of payment for ESR payment import files
TOCTitle: (CHE) Set up a method of payment for ESR payment import files
ms:assetid: 3f5db37c-6d60-4b17-ae27-10db89a4f8ce
ms:mtpsurl: https://technet.microsoft.com/library/Gg231173(v=AX.60)
ms:contentKeyID: 36056705
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Switzerland
---

# (CHE) Set up a method of payment for ESR payment import files 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Methods of payment** form to set up a method of payment for Enzahlungsschein mit Referenznummer (ESR) payment import files.

1.  Click **Accounts receivable** \> **Setup** \> **Payment** \> **Methods of payment**.

2.  Press CTRL+N to create a new line.

3.  In the **Method of payment** field, enter an identifier, such as **ESR**.

4.  In the **Period** field, select **Invoice**. Each invoice is settled with only one payment.

5.  On the **General** FastTab, in the **Account type** field, select **Bank**.

6.  In the **Payment account** field, select a bank account that is set up with the ESR information.

7.  Click the **File formats** FastTab, and then in the **Import format** field, select **ESR (CH)**.
    

    > [!NOTE]
    > <P>If the field list is empty, click <STRONG>Setup</STRONG> and select from the available formats.</P>



8.  Click the **Payment attributes** FastTab.

9.  Select the **Payment ID** check box.

10. Enter other information as required for the method of payment.

11. Close the form to save your changes.

## See also

[(CHE) Swiss LSV+ electronic payment format](che-swiss-lsv-electronic-payment-format.md)

  


