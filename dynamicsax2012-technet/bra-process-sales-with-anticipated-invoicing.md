---
title: (BRA) Process sales with anticipated invoicing
TOCTitle: (BRA) Process sales with anticipated invoicing
ms:assetid: fa9ec2ac-fbf0-4e72-95d1-87497793bb43
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ863744(v=AX.60)
ms:contentKeyID: 50396427
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- process sales
- anticipated invoicing
audience: Application User
ms.search.region: Brazil
---

# (BRA) Process sales with anticipated invoicing 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In a sale that uses anticipated invoicing, you accept a prepayment, or advance payment, from a customer and issue a customer fiscal document later, when the items are actually delivered. In accordance with the price negotiation agreements with a customer, you can receive prepayments without delivering the items. However, you can issue the customer fiscal document only when the items are delivered to the customer. There is no physical or financial movement of inventory at the prepayment stage, and no taxes apply.

1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**. Set up sales tax on prepayments. For more information, see [Set up sales tax on prepayments](set-up-sales-tax-on-prepayments.md).

2.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**. Create a payment journal that has the following setup:
    
    1.  Click the **Setup** tab, and then select the **Amounts include sales tax** check box to post the prepayment journal voucher together with the sales tax amounts.
    
    2.  Click **Lines**, and then create a payment journal line.
    
    3.  Click the **Payment** tab, and then select the **Prepayment journal voucher** check box to post the prepayment through the journal.
    
    4.  Post the payment journal.

3.  Click **Organization administration** \> **Setup** \> **Brazil** \> **Operation type**. Create an operation type that has the following setup:
    
    1.  Select the **Create inventory movements** check box to specify that the operation type generates inventory movement, and to record the physical and financial movement of inventory.
        

        > [!NOTE]
        > <P>To create inventory-related ledger transactions, you must select the <STRONG>Post physical inventory</STRONG> and <STRONG>Post financial inventory</STRONG> check boxes on the <STRONG>Setup</STRONG> FastTab in the <STRONG>Item model groups</STRONG> form.</P>

    
    2.  Select the **Create customer/vendor transactions** check box to specify that the operation type creates customer or vendor transactions.
    
    3.  In the **Item account** field, select the default posting account that is used for the operation type in the ledger.
    
    For more information, see [(BRA) Set up operation types](bra-set-up-operation-types.md).

4.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.
    
    –or–
    
    Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

5.  To record this operation, create a sales order that has the operation type that you created. For more information, see [(BRA) Create and post a sales order](bra-create-and-post-a-sales-order.md).

6.  In the **Sales order** form, on the **Action Pane**, click the **Invoice** tab, and then click **Open transactions** to open the **Settle open transactions** form.

7.  Select the **Mark** check box to link the prepayment journal that you created to the sales order, and then close the form.

8.  Post the sales order.

## See also

[(BRA) Operation type (form)](https://technet.microsoft.com/en-us/library/jj822922\(v=ax.60\))

[Journal header (form)](https://technet.microsoft.com/en-us/library/aa557917\(v=ax.60\))

[Journal voucher - Customer payment journal (form)](https://technet.microsoft.com/en-us/library/aa556141\(v=ax.60\))

[(BRA) Sales orders (modified form)](https://technet.microsoft.com/en-us/library/jj911252\(v=ax.60\))

[Settle open transactions - customer (form)](https://technet.microsoft.com/en-us/library/aa558602\(v=ax.60\))

[(BRA) Sales posting (modified form)](https://technet.microsoft.com/en-us/library/jj853383\(v=ax.60\))

  


