---
title: (IND) Withholding tax for advance payments and prepayments
TOCTitle: (IND) Withholding tax for advance payments and prepayments
ms:assetid: 3659c0dd-43c0-43ea-a190-da4a4c9751db
ms:mtpsurl: https://technet.microsoft.com/library/JJ664610(v=AX.60)
ms:contentKeyID: 49385688
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Withholding tax for advance payments and prepayments 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can calculate Tax Collected at Source (TCS) and Tax Deducted at Source (TDS) withholding taxes on advance payments and prepayments received from customers or vendors. When the prepayment or advance payment is attached to a sales order or purchase order, the withholding tax is calculated only on the amount that exceeds the advance payment or prepayment amount.

## Example

You create an advance payment transaction for INR 10,000 for Customer 1. TCS is calculated for the transaction. Then you create a sales invoice for Customer 1 for INR 15,000 and link the advance payment transaction to the invoice. In this case, TCS is calculated only for INR 5,000.

## Automatic settlement

If the **Automatic settlement** check box is selected in the **Accounts receivable parameters** form, and an advance payment has already been received from the customer, the advance payment is adjusted toward the TCS amount first, and then toward the invoice amount.

For example, you have received an advance payment of INR 12,000 from Customer A. You create an invoice for Customer A for INR 22,000, of which INR 20,000 is the invoice amount and INR 2,000 is the TCS amount. First, INR 2,000 from the advance payment is adjusted toward the TCS amount, and then the balance is adjusted toward the invoice amount.

## Automatic posting

If you create a purchase invoice by using a method of payment that has automatic posting enabled, an automatic payment voucher is created for the net amount after TDS is deducted.

For example, if the invoice amount is INR 100,000, and the total TDS amount is INR 11,330, the automatic payment voucher is posted for INR 88,670, which is the net amount after the TDS amount is deducted.

## See also

[(IND) Accounts payable parameters (modified form)](https://technet.microsoft.com/library/jj664793\(v=ax.60\))

  


