---
title: (EEUR) Set up a payment method for cash payments in a retail store
TOCTitle: (EEUR) Set up a payment method for cash payments in a retail store
ms:assetid: 7aeee7c6-f5ae-4593-b7d2-8a8fe627a80f
ms:mtpsurl: https://technet.microsoft.com/library/Dn268479(v=AX.60)
ms:contentKeyID: 54917018
author: Khairunj
ms.date: 04/28/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.RetailTenderTypeTable
- RU - 00005
- RU - 00037
audience: Application User
ms.search.region: Czech Republic, Estonia, Hungary, Latvia, Lithuania, Poland, Russia
---

# (EEUR) Set up a payment method for cash payments in a retail store 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the following procedure to set up a payment method for cash payments in a retail store.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 1 for AX 2012 R2.</P>



1.  Click **Retail** \> **Common** \> **Retail channels** \> **Retail stores**.

2.  On the **Retail stores** list page, select the store to set up a payment method for.

3.  On the **Action Pane**, on the **Set up** tab, in the **Set up** group, click **Payment methods**.

4.  In the **Payment method** form, create a payment method. For more information about creating a payment method for a retail store, see [Set up store payment methods](set-up-store-payment-methods.md).

5.  On the **Posting** FastTab, in the **Account** field group, in the **Account type** field, select **Cash account**.
    

    > [!NOTE]
    > <P>You can select <STRONG>Cash account</STRONG> in the <STRONG>Account type</STRONG> field only if you select <STRONG>Normal</STRONG> or <STRONG>Tender remove/float</STRONG> in the <STRONG>Function</STRONG> field.</P>



6.  In the **Account number** field, select a cash account number for the payment method.

7.  In the **Tender remove/float** field group, in the **Offset account** field, select the offset account to post remove tender or float entry transactions for the payment method.
    

    > [!NOTE]
    > <P>You must set up offset accounts for both the cash tender payment method and the remove tender or float entry payment method for a store to create balanced general ledger entries for remove tender or float entry transactions.</P>


  


