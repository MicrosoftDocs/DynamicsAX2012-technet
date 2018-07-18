---
title: (LTU) Set up the export format for a foreign customer payment transfer
TOCTitle: (LTU) Set up the export format for a foreign customer payment transfer
ms:assetid: 504e3887-8581-42fb-ab93-9243c4f764bb
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ665079(v=AX.60)
ms:contentKeyID: 49386661
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Lithuania
---

# (LTU) Set up the export format for a foreign customer payment transfer 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Users in Lithuania can use the LITAS system to export foreign customer payments from their accounting systems to the Bank of Lithuania.

1.  Click **Accounts receivable** \> **Setup** \> **Payment** \> **Methods of payment**.

2.  Click **New** to create a method of payment, and then enter the required information.

3.  In the **Account type** field, select the account type for the selected account.

4.  In the **Payment account** field, select the number of the payment account for the account type.

5.  In the **Sequence number** field, select the code for the number sequence that is used for the method of payment.
    

    > [!NOTE]
    > <P>You set up number sequences in the <STRONG>Number sequences</STRONG> form. (Click <STRONG>Organization administration</STRONG> &gt; <STRONG>Common</STRONG> &gt; <STRONG>Number sequences</STRONG> &gt; <STRONG>Number sequences</STRONG>. Click <STRONG>Number sequence</STRONG>.)</P>



6.  On the **File formats** FastTab, click **Setup** to open the **File formats for methods of payment** form.

7.  On the **Export** tab, in the **Available** list, select **Foreign payment transfer (LT)**, and then move it to the **Selected** field.

8.  Close the form to return to the **Methods of payment - customers** form.

9.  On the **File formats** tab, in the **Export format** field, select the **Foreign payment transfer (LT)** format for the export of foreign customer payments.

## See also

[(LTU) Customer methods of payment (modified form)](https://technet.microsoft.com/en-us/library/jj665101\(v=ax.60\))

  


