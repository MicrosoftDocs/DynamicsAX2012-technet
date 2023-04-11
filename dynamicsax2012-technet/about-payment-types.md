---
title: About payment types
TOCTitle: About payment types
ms:assetid: 601ca7c0-813f-4d3c-ae8d-28db307081e4
ms:mtpsurl: https://technet.microsoft.com/library/Gg242528(v=AX.60)
ms:contentKeyID: 36966726
author: tonyafehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- type
- types
- payment
audience: Application User
ms.search.region: Global
---

# About payment types 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can assign a system-defined payment type, such as **Check**, **Electronic payment**, or **Promissory note**, to any user-defined method of payment. Payment types are optional, but they are useful when you validate electronic payments. Payment types are also useful when you must quickly determine which payment type a payment uses, and when you must print reports that do not contain misspelled payment types. You assign payment types to payment methods in the **Methods of payment - vendors** form.


> [!TIP]
> <P>When you select a default payment method for a vendor in the <STRONG>Vendors</STRONG> form, a payment type is displayed in the <STRONG>Payment type</STRONG> field if a payment type is associated with a payment method. However, when you enter transactions, you specify a user-defined method of payment, not a payment type.</P>



## Validation of electronic payments

When a payment type of **Electronic payment** is associated with a payment method, additional validation is performed when you try to post the payment. This is especially important when you are setting up electronic payments, because vendors or banks might ask you to wait until a specific date before you process transactions for that bank account.

You can specify the active date and expiration date for a vendor bank account to indicate when the bank account is active. You can then assign a payment type of **Electronic payment** to a payment method. The additional validation then will be performed when payments that use the specified payment method are generated. During validation, the active date of the vendor's bank account is verified against the transaction date. For example, a payment is generated for a payment in a payment journal. The **Active date** field in the **Vendor bank accounts** form is blank, or the date that is specified is earlier than or the same as the payment transaction date. In this case, the payment is generated. However, if the active date is after the transaction date, you must wait until the active date to generate the payment.

This validation does not occur if no payment type is assigned to the payment method that is being used. In this case, the payment is always generated, regardless of the active date. If you post multiple payments, validation occurs for all payments for which payment types are assigned to the payment methods. You can post the payments that do not have errors.

For the **Electronic payment** payment type, validation occurs when you generate payments, remittances, or settlements in the **Journal voucher** form when the form is opened from one of the following forms:

  - **Payment journal** form – Generate a payment to activate validation.
    

    > [!TIP]
    > <P>The bank account that is used in the validation is specified in the <STRONG>Account identification</STRONG> field on the <STRONG>Bank</STRONG> tab for the lines of the <STRONG>Journal voucher</STRONG> form.</P>



  - **Draw promissory note journal** form or **Redraw promissory note journal** form – Generate a payment to activate validation.

  - **Remittance journal** form – Generate a remittance to activate validation.

  - **Settle promissory note journal** form – Generate a settlement to activate validation.


> [!NOTE]
> <P>If you select <STRONG>Check</STRONG>, <STRONG>Promissory note</STRONG>, or <STRONG>Other</STRONG> as the payment type, no validation is performed to determine whether a bank account is active. These payment types are provided to help you clarify the user-defined methods of payment.</P>



## See also

[Set up payment types for vendor methods of payment](set-up-payment-types-for-vendor-methods-of-payment.md)

[Specify when a vendor bank account is active](specify-when-a-vendor-bank-account-is-active.md)

[Vendor bank accounts (form)](https://technet.microsoft.com/library/aa589805\(v=ax.60\))

  


