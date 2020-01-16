---
title: Set up store payment methods
TOCTitle: Set up store payment methods
ms:assetid: ed81e31e-e222-4398-b741-321ca28f2b98
ms:mtpsurl: https://technet.microsoft.com/library/Hh597274(v=AX.60)
ms:contentKeyID: 39519357
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- stores
- payment methods
audience: Application User
ms.search.region: Global
---

# Set up store payment methods 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

After you create a payment method in Retail, you can assign the payment method to stores. Multiple payment methods for stores can be based on a single organization-wide payment method. Each store payment method can have different settings.

For each payment method, you can specify the following information:

  - The general ledger account or bank account in which each payment method is posted

  - The minimum change amount that can be given for various payment methods

  - The conditions under which change can be given

You can also assign reason codes to each payment method. These reason codes prompt a cashier to take any of the following actions:

  - Create entries that have unique entry codes

  - Verify that entries have unique entry codes

  - Collect information from the customer

**Example**

  - The payment method is named **Voucher**.

  - The **Above minimum change tender** field is set to **voucher**.

  - The **Change tender** field is set to **Cash**.

  - The **Minimum change** field is set to **20.00**.

**Case 1**: A customer buys products that are worth 475.00, and pays by using a voucher that is worth 500.00. The customer is owed 25.00 in change. The cashier issues a new voucher for 25.00 to the customer because the amount that is owed to the customer is above the value in the **Minimum change** field.

**Case 2**: A customer buys products that are worth 485.00, and pays by using a voucher that is worth 500.00. The customer is owed 15.00 in change. The cashier gives the customer 15.00 in cash because the amount that is owed to the customer is under the value in the **Minimum change** field.

If Microsoft Dynamics AX 2012 R2 is installed, you can also specify the currencies that are accepted in the store. For example, the currency codes that you enter are used to determine the currencies that are available during the Pay currency operation in Microsoft Dynamics AX for Retail POS.

Retail POS uses only currencies for which an exchange rate conversion is configured for the company that the store is assigned to.


> [!NOTE]
> <P>If you copy a payment method from one store into another store, any currencies that are set up for the original store are copied to the new store.</P>



For information about fields in the **Payment method** form, see [Payment method (form)](https://technet.microsoft.com/library/hh580626\(v=ax.60\)).


> [!NOTE]
> <P>The procedure for completing this task was changed for Microsoft Dynamics AX 2012 R2. The updated procedure also applies to AX 2012 R3. For more information, see the section later in this topic.</P>



## Set up store payment methods

1.  Click **Retail** \> **Common** \> **Retail channels** \> **Retail stores**.

2.  On the **Retail stores** list page, select the store to set up payment methods for.

3.  On the **Action Pane**, on the **Set up** tab, in the **Set up** group, click **Payment methods**.

4.  In the **Payment method** form, click **New** to add a payment method.

5.  On the **General** FastTab, follow these steps:
    
    1.  In the **Payment method** field, select the organization-wide payment method that the store payment method is based on. Settings for the payment method are automatically entered based on default setting that you set up in Retail.
    
    2.  In the **Terms of payment** field, select the terms of payment for the payment method.
    
    3.  In the **Operation ID** field, select the operation that cashiers use to accept payments of this type.
    
    4.  If you want to open the cash drawer every time that the payment method is used at the point of sale, select the **Open drawer** check box.
    
    5.  If you want to track the number of payment entries that are made by using the payment method, select the **POS count entries** check box.

6.  On the **Amount** FastTab, specify the settings that affect how transaction amounts are rounded and received.

7.  On the **Posting** FastTab, specify the settings and account information that are used to post payments for the payment method.

8.  On the **Change** FastTab, specify how change is given for the payment method.

9.  On the **Financial dimensions** FastTab, specify any financial dimensions that apply to the payment method.

10. In Microsoft Dynamics AX 2012 R2, for payment methods that are set to **Currency**, click **Currencies**. Then, in the **Accepted currencies** form, enter the currency codes for the currencies that are accepted by the store.

## Set up payment methods for online stores in Microsoft Dynamics AX 2012 R2

1.  Click **Retail** \> **Common** \> **Retail channels** \> **Online stores**.

2.  On the **Online stores** list page, select the store to set up payment methods for.

3.  On the **Action Pane**, on the **Set up** tab, in the **Set up** group, click **Payment methods**.

4.  In the **Payment method** form, click **New** to add a payment method.

5.  On the **General** FastTab, follow these steps:
    
    1.  In the **Payment method** field, select the organization-wide payment method that the store payment method is based on. Settings for the payment method are automatically entered based on default setting that you set up in Retail.
    
    2.  In the **Terms of payment** field, select the terms of payment for the payment method.

6.  On the **Financial dimensions** FastTab, specify any financial dimensions that apply to the payment method.

7.  Click **Card setup**. Then, in the **Card setup** form, click **New** to create a new card. Enter the card name, and then select other appropriate options for the card type.
    
    You must set up cards as payment methods to accept card payments for the online store.

8.  For payment methods that are set to **Currency**, click **Currencies**. Then, in the **Accepted currencies** form, enter the currency codes for the currencies that are accepted by the store.

## See also

[About payment methods](about-payment-methods.md)

[Set up payment methods for an organization](set-up-payment-methods-for-an-organization.md)

[Set up card payment methods for stores](set-up-card-payment-methods-for-stores.md)

[Payment method (form)](https://technet.microsoft.com/library/hh580626\(v=ax.60\))

[Set up an online store](set-up-an-online-store.md)

  


