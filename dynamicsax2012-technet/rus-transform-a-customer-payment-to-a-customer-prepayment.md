---
title: (RUS) Transform a customer payment to a customer prepayment
TOCTitle: (RUS) Transform a customer payment to a customer prepayment
ms:assetid: a0ab41d3-02f4-4a6f-b6e1-03977762cfb2
ms:mtpsurl: https://technet.microsoft.com/library/JJ678542(v=AX.60)
ms:contentKeyID: 49387772
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.SalesBooksTable
- MsDynAx060.Forms.SalesBooksTable
audience: Application User
ms.search.region: Russia
---

# (RUS) Transform a customer payment to a customer prepayment 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

If unsettled payment documents remain at the end of reporting period, the payment documents must be converted to prepayments and included in the sales book. You can also convert a payment into a prepayment by using the **Customer transactions** form.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts receivable** \> **Periodic** \> **Sales book** \> **Sales books journal**. Click **Functions** \> **Transform to prepayment** to open the **Unsettled payments** form.

2.  Select the **Mark** check box for the payment line you want to convert to a prepayment, and then click **Prepayment handling** to open the **Convert to prepayment** form.

3.  In the **Date** field, select the transaction date.

4.  Select the **Automatically facture creation** check box to create a facture automatically on prepayment.
    

    > [!NOTE]
    > <P>If you do not select this check box, the factures on prepayments are created in postponed mode.</P>



5.  Click **OK** to transform the customer payment to a customer prepayment.
    

    > [!NOTE]
    > <P>This step reverses the previously created transaction and its attendant credit liability. Prepayment transactions are dated as specified in the <STRONG>Convert to prepayment</STRONG> form. Prepayment factures are created and included in the sales book after it is updated.</P>



## See also

[(RUS) Unsettled payments (form)](https://technet.microsoft.com/library/jj853162\(v=ax.60\))

  


