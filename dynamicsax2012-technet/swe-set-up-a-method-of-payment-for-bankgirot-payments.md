---
title: (SWE) Set up a method of payment for Bankgirot payments
TOCTitle: (SWE) Set up a method of payment for Bankgirot payments
ms:assetid: 7e1c7d7e-0577-444f-a1b9-11dbbed20471
ms:mtpsurl: https://technet.microsoft.com/library/Gg213144(v=AX.60)
ms:contentKeyID: 36058315
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Sweden
---

# (SWE) Set up a method of payment for Bankgirot payments 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Sweden, vendor payment files are sent to Bankgirot, which is a payment clearing service. You must set up a method of payment for the Bankgirot payments that is used in the payment journal.

1.  Click **Accounts payable** \> **Setup** \> **Payment** \> **Methods of payment**.

2.  Press CTRL+N to create a new method of payment, and then in the **Method of payment** field, enter an appropriate identifier for the method of payment, such as Bankgirot.

3.  Enter other information for the method of payment, as required.

4.  Click the **File formats** FastTab, and then in the **Export format** field, select **Bankgirot (SE)**.
    

    > [!NOTE]
    > <P>If the <STRONG>Export format</STRONG> field list is empty, click <STRONG>Setup</STRONG>, and then select one of the available formats.</P>



5.  Close the form.

## See also

[Methods of payment - vendors (form)](https://technet.microsoft.com/library/aa618565\(v=ax.60\))

[(SWE) Create a Bankgirot payment file that includes Postgirot payments](swe-create-a-bankgirot-payment-file-that-includes-postgirot-payments.md)

[Bankgirot (SE) (form)](https://technet.microsoft.com/library/hh209643\(v=ax.60\))

  


