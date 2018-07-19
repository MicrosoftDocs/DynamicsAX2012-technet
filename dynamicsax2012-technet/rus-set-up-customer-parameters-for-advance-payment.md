---
title: (RUS) Set up customer parameters for advance payment
TOCTitle: (RUS) Set up customer parameters for advance payment
ms:assetid: 0ebb0ca0-9160-4b2e-ac9d-65bf439c34e8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711389(v=AX.60)
ms:contentKeyID: 49387207
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up customer parameters for advance payment 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  Click the **Ledger and Sales tax** tab.

3.  Select the **Sales tax on prepayment journal voucher** check box to specify that sales tax must be deducted from payments with advance payments.

4.  In the **Posting profile with prepayment journal voucher** field, specify the posting profile for the advance payment.

5.  In the **VAT transaction type** field, select the type used for VAT on prepayment transaction during settlement cancelation.

6.  In the **Tax group of prepayment** field, select the sales tax group for the advance payment.

7.  In the **Item sales tax group** field, select the item sales tax group for the advance payment.

8.  In the **Prepayment handling** field, select the prepayment handling form layout from the following options:
    
      - **Simple** – Change the prepayment creation date during conversion of payment to a prepayment.
    
      - **Advanced** – Change the prepayment date along with the taxes during conversion of a payment to a prepayment.

9.  Select the **Automatically facture creation** check box to automatically create a facture when posting prepayments.
    

    > [!NOTE]
    > <P>If you do not select this check box, the factures on prepayments are created in postponed mode.</P>



10. Press CTRL+S or close the form.

## See also

[(RUS) Accounts receivable parameters (modified form)](https://technet.microsoft.com/en-us/library/jj733289\(v=ax.60\))

  


