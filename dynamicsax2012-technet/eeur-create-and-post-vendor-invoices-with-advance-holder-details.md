---
title: (EEUR) Create and post vendor invoices with advance holder details
TOCTitle: (EEUR) Create and post vendor invoices with advance holder details
ms:assetid: b5b747ab-6969-4361-8407-1a6838f2d9b8
ms:mtpsurl: https://technet.microsoft.com/library/JJ911009(v=AX.60)
ms:contentKeyID: 52075305
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- vendor invoices
- advance holder
- advance holder invoice
- invoices for advance holder
- post vendor invoices
audience: Application User
ms.search.region: Czech Republic, Estonia, Hungary, Latvia, Lithuania, Poland, Russia
---

# (EEUR) Create and post vendor invoices with advance holder details 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to create and post vendor invoices with advance holder details. The advance holder balances are posted to the employee balance account instead of the vendor balance account.

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Press CTRL+N or click **Purchase order** to create a purchase order. For more information, see [Create a purchase order](create-a-purchase-order.md) and [(EEUR) Purchase orders (modified form)](https://technet.microsoft.com/library/jj710700\(v=ax.60\)).

3.  In the **Purchase order** form, on the **Action Pane**, click **Header view**, and then click the **Price and discount** FastTab.

4.  In the **Terms of payment** field, select the payment term. For more information, see [(EEUR) Terms of payment (modified form)](https://technet.microsoft.com/library/jj911004\(v=ax.60\)).
    

    > [!NOTE]
    > <P>Select a payment term that has the <STRONG>From advance holder</STRONG> check box selected in the <STRONG>Terms of payment</STRONG> form.</P>



5.  In the **Advance holder** field, select the advance holder for the purchase order.

6.  Click **Purchase** \> **Confirm** to confirm the purchase order.

7.  Click **Invoice** \> **Invoice** to create a vendor invoice for the purchase order.

8.  In the **Vendor invoice** form, in the **Invoice identification** field group, in the **Number** field, enter the invoice number.

9.  Click **Post** \> **Post** to select the posting settings and generate the invoice.
    
    You can view two vendor transactions with opposite amounts in the **Vendor transactions** form. For more information, see [(EEUR) Vendor transactions (modified form)](https://technet.microsoft.com/library/jj730985\(v=ax.60\)).

10. Close the form.

11. Click **Accounts payable** \> **Inquiries** \> **Advance holders** \> **Transactions**. In the **Advance holder transactions** form, you can view one advance holder transaction. For more information, see [(EEUR) Advance holder transactions (form)](https://technet.microsoft.com/library/jj910968\(v=ax.60\)).

12. Click **Voucher** to open the **Voucher transactions** form. The vendor balance account is replaced by the employee balance account, and the **Posting type** field is updated to **Employee balance**. For more information, see [Voucher transactions (form)](https://technet.microsoft.com/library/aa583215\(v=ax.60\)).

## See also

[(EEUR) Settle advance holder balances](eeur-settle-advance-holder-balances.md)

[(EEUR) Vendor invoice (modified form)](https://technet.microsoft.com/library/jj862346\(v=ax.60\))

  


