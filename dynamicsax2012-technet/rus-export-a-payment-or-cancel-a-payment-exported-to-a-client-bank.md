---
title: (RUS) Export a payment or cancel a payment exported to a client bank
TOCTitle: (RUS) Export a payment or cancel a payment exported to a client bank
ms:assetid: 874c531d-3ee4-414e-951f-836677f3bc63
ms:mtpsurl: https://technet.microsoft.com/library/JJ678442(v=AX.60)
ms:contentKeyID: 49387672
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Export a payment or cancel a payment exported to a client bank 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use electronic exchange formats to export payments to a client bank, and to import payments and bank account statements from a client bank. Payments include outgoing and incoming payments between Microsoft Dynamics AX and a client bank. For more information about the client bank process, see [(RUS) About the electronic exchange format for client bank payments](rus-about-the-electronic-exchange-format-for-client-bank-payments.md). Use the **Export of payments to client-bank** form to export a payment to a client bank. You can export transactions that are created in the payment journals to the client bank. You can also cancel a payment that is exported to a client bank by using the **Exported payments** form.

## Export a payment to a client bank

1.  Click **Cash and bank management** \> **Periodic** \> **Client-bank** \> **Export of payments to client-bank**.

2.  Select a journal line. Click **Journal line** to open the **Journal voucher** form, and then modify the journal line, if required.

3.  Close the form.
    

    > [!NOTE]
    > <P>You can view the modified journal line in the <STRONG>Export of payments to client-bank</STRONG> form only if you open the form again.</P>



4.  In the **Export of payments to client-bank** form, select the **Marked** check box to select the journal line for the payment that must be exported.
    

    > [!NOTE]
    > <P>You can click <STRONG>Mark</STRONG> &gt; <STRONG>Mark all</STRONG> to select all of the journal lines for export.</P>



5.  Click **Payment export to bank**. The journal line is exported and saved in the path that is specified in the **Folder for export** field in the **Exchange formats for settlement account** form. A separate export file is created for each bank account.

6.  You can view the exported payments, the exported file name, and the date and time of export on the **Other** tab in the **Exported payments** form.

## Cancel a payment exported to a client bank

1.  Click **Cash and bank management** \> **Periodic** \> **Client-bank** \> **Exported payments**.

2.  Select the exported payment line to cancel, and then click **Void payment order**. The **Payment order status** field on the **General** tab is updated to **Rejected**, and the payment status is updated to **None**.
    

    > [!NOTE]
    > <P>You can select a transaction and then click <STRONG>Journal line</STRONG> to view the original payment journal line.</P>



## See also

[(RUS) Export of payments to client-bank (form)](https://technet.microsoft.com/library/jj678349\(v=ax.60\))

[(RUS) Exported payments (form)](https://technet.microsoft.com/library/jj678336\(v=ax.60\))

  


