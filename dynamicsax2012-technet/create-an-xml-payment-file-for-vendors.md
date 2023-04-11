---
title: Create an XML payment file for vendors
TOCTitle: Create an XML payment file for vendors
ms:assetid: bbc9d04f-ea68-4b75-980a-4ed40f3f6a7b
ms:mtpsurl: https://technet.microsoft.com/library/Hh452632(v=AX.60)
ms:contentKeyID: 36971931
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create an XML payment file for vendors 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The electronic payment files that you can create for vendors can have many XML-based formats. Starting in Microsoft Dynamics AX 2012, electronic payments can be made by using Application Integration Framework (AIF) services. Several default payment formats are available, such as Single Euro Payments Area (SEPA) Credit Transfer. A developer can easily create new payment formats if new formats are required.

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Select a journal, and then click **Lines**.

3.  Click **Functions** \> **Generate payments**. The **Generate payments** form is displayed.

4.  Select the **Export payment using service** option, and then, in the **Payment format** field, select a payment format.
    

    > [!NOTE]
    > <P>For example, for SEPA vendor payments, select the <STRONG>SEPACreditTransfer</STRONG> payment format.</P>



5.  Click **Dialog**.

6.  In the **Payment processing data** form, enter the information that is required for the payment format.
    

    > [!NOTE]
    > <P>The fields that are displayed in the <STRONG>Payment processing data</STRONG> form depend on the payment format that you selected.</P>



7.  Click **OK**.

8.  In the **Generate payments** form, click **OK**.

## See also

[Create an electronic payment file for vendors](create-an-electronic-payment-file-for-vendors.md)

[Set up an outbound payment format](set-up-an-outbound-payment-format.md)

  


