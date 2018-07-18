---
title: Set up store payment methods (Retail Essentials)
TOCTitle: Set up store payment methods (Retail Essentials)
ms:assetid: 7af0c7c8-0e4f-482b-a53f-a3e7ca6d9b82
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn736903(v=AX.60)
ms:contentKeyID: 62200381
ms.date: 11/13/2014
mtps_version: v=AX.60
---

# Set up store payment methods (Retail Essentials) 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to assign methods of payment to stores. After you create a payment method in Retail essentials, you can assign it to stores. Multiple store payment methods can be based on a single organization-wide payment method. Each store payment method can have different settings.

For each payment method, you can specify the following information:

  - The general ledger account or bank account in which the payment method is posted

  - The minimum change amount that can be given

  - The conditions under which change can be given

You can also assign reason codes to each payment method. A reason code prompts a cashier to take one of the following actions:

  - Create entries that have unique entry codes.

  - Verify that entries have unique entry codes.

  - Collect information from the customer.


> [!NOTE]
> <P>If you copy a payment method from one store to another store, any currencies that are set up for the original store are copied to the new store.</P>



**Example**

  - The payment method is named **Voucher**.

  - The **Above minimum change tender** field is set to **Voucher**.

  - The **Change tender** field is set to **Cash**.

  - The **Minimum change** field is set to **20.00**.

**Case 1:** A customer buys products that are worth 475.00 and pays by using a voucher that is worth 500.00. The customer is owed 25.00 in change. The cashier issues a new voucher for 25.00 to the customer, because the amount that is owed to the customer is more than the value in the **Minimum change** field.

**Case 2:** A customer buys products that are worth 485.00 and pays by using a voucher that is worth 500.00. The customer is owed 15.00 in change. The cashier gives the customer 15.00 in cash, because the amount that is owed to the customer is less than the value in the **Minimum change** field.

You can also specify the currencies that are accepted in the store. For example, the currency codes that you enter are used to determine the currencies that are available during the Pay currency operation in Retail essentials. Retail essentials uses only currencies for which an exchange rate conversion is configured for the company that the store is assigned to.

For information about the fields in the **Payment method** form, see [Payment method (form)](https://technet.microsoft.com/en-us/library/hh580626\(v=ax.60\)).


> [!NOTE]
> <P>In Retail essentials, the form that you use to complete this task includes a subset of the controls that are available for other configurations of Retail. If a topic about this form describes controls that you don't see, it may be because you’re using Retail essentials.</P>



## Set up store payment methods

1.  Click **Retail essentials** \> **Channels** \> **Retail stores**.

2.  On the **Retail stores** list page, select the store to set up payment methods for.

3.  On the **Action Pane**, on the **Set up** tab, in the **Set up** group, click **Payment methods**.

4.  In the **Payment methods** form, click **New** to add a payment method.

5.  On the **General** FastTab, follow these steps:
    
    1.  In the **Payment method** field, select the organization-wide payment method that the store payment method is based on. Settings for the payment method are automatically entered, based on default setting that you set up in Retail essentials.
    
    2.  In the **Terms of payment** field, select the terms of payment for the payment method.
    
    3.  In the **Operation name** field, select the operation that cashiers use to accept payments of this type.
    
    4.  If you want to open the cash drawer every time that the payment method is used at the point of sale, select the **Open drawer** check box.
    
    5.  If you want to track the number of payment entries that are made by using the payment method, select the **POS count entries** check box.

6.  On the **Amount** FastTab, specify the settings that affect how transaction amounts are rounded and received.

7.  On the **Posting** FastTab, specify the settings and account information that are used to post payments for the payment method.

8.  On the **Change** FastTab, specify how change is given for the payment method.

9.  On the **Financial dimensions** FastTab, specify any financial dimensions that apply to the payment method.

10. For payment methods that are set to **Currency**, click **Currencies**. Then, in the **Accepted currencies** form, enter the currency codes for the currencies that are accepted by the store.

## See also

[Set up card payment methods for stores (Retail essentials)](set-up-card-payment-methods-for-stores-retail-essentials.md)

[Set up payment card types and card numbers (Retail essentials)](set-up-payment-card-types-and-card-numbers-retail-essentials.md)

[Setting up payment methods (Retail essentials)](setting-up-payment-methods-retail-essentials.md)

  


