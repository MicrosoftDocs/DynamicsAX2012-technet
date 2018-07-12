---
title: (IND) View the VAT deferment schedule installment for a purchase order
TOCTitle: (IND) View the VAT deferment schedule installment for a purchase order
ms:assetid: f28bcc76-ede0-467f-8a7d-ec05665d4934
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ710926(v=AX.60)
ms:contentKeyID: 49386339
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- India
- Forms.VATDefermentDetails_IN
- VAT deferment transactions
- MsDynAx060.Forms.VATDefermentDetails_IN
audience: Application User
ms.search.region: India
---

# (IND) View the VAT deferment schedule installment for a purchase order 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

VAT deferment installments are calculated based on the deferment schedule for the specified Tax Identification Number (TIN). The deferment schedule installments are calculated and updated only for the purchase or return of capital goods.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**. Double click a purchase order that contains **Capital items** in the **VAT items type** field. The purchase order must have a status of **Invoiced**. In the **Purchase order** form, on the **Action Pane**, on the **Invoice** tab, in the **Journals** group, click **Invoice**. In the **Invoice journal** form, on the **Overview** tab, click **VAT deferment**.
    
    You can view transaction details such as purchase order number, invoice date, invoice number, voucher number, currency used, invoice amount, and calculated VAT amount for the transaction.

2.  Click the **Lines** FastTab to view the details of the purchase order lines and VAT-related details such as the calculated VAT amount, VAT deferred amount and VAT expense amount for the transaction.
    

    > [!NOTE]
    > <P>VAT expenses = VAT amount – VAT deferred.</P>



3.  Click **Deferment schedule** to view the deferment schedule installments attached to the line based on the TIN.

## See also

[(IND) Purchase orders (modified form)](https://technet.microsoft.com/en-us/library/jj664798\(v=ax.60\))

[(IND) VAT deferment transactions (form)](https://technet.microsoft.com/en-us/library/jj710922\(v=ax.60\))

[(IND) Deferment schedule (form)](https://technet.microsoft.com/en-us/library/jj664609\(v=ax.60\))

[(IND) VAT deferment balance (form)](https://technet.microsoft.com/en-us/library/jj664626\(v=ax.60\))

[(IND) View VAT deferment transactions](ind-view-vat-deferment-transactions.md)

  


