---
title: Set up credit card authorizations
TOCTitle: Set up credit card authorizations
ms:assetid: fc467642-c6b1-47eb-8c4f-3db106e58046
ms:mtpsurl: https://technet.microsoft.com/library/Gg243306(v=AX.60)
ms:contentKeyID: 36060090
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Discover
- verification
- address
- capture
- authorization
- credit card
- authorizations
- authorize
- credit cards
- American Express
- AmEx
- MasterCard
- captures
- card value
- security code
- security codes
- Visa
- payment services
- payment service
audience: Application User
ms.search.region: Global
---

# Set up credit card authorizations 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to prepare to authorize credit cards that are submitted for the payment of sales orders. When a credit card payment is authorized, the credit card holder's name, billing address, credit card number, and available credit are verified. The customer's available credit is also reduced by the amount of the sales order. When the order is ready for invoicing and payment, the credit card charge is processed and the customer's credit card is billed.

You can set up credit card authorizations to be completed by the Payment Services for Microsoft Dynamics ERP payment service or by other payment services for which integrations are available.


> [!NOTE]
> <P>You can use only one payment service at a time in each legal entity.</P>



## Set up Payment Services as the payment service

1.  Click **Accounts receivable** \> **Setup** \> **Payment** \> **Payment services**.

2.  Click **Sign up now** to open the Payment Services for Microsoft Dynamics ERP website.

3.  Enter your email address and Microsoft Windows Live® ID account password. Enter additional information, as needed, to set up an account for Payment Services for Microsoft Dynamics ERP. When you have finished, close the browser.

4.  In the **Payment services** form, verify that your organization’s name is displayed in the **Name** field.

5.  Click the **…** button next to the **Service account ID** field, select a payment account, and then click **OK**.

6.  Select the **Test mode** check box to test the authorization process. Transactions that are sent to the payment service will be treated as test transactions, instead of business transactions.

7.  Optional: To validate billing address information when credit cards are authorized, select the **Address verification** check box and then select the amount of detail to verify.

8.  Optional: For added security, you can select the **Prompt for card verification value** check box. A three- or four-digit card verification value, also named a security code, is required for authorization. This card verification value is not stored in Microsoft Dynamics AX.

9.  Click **Credit card types** and set up information for each type of credit card that you accept. For more information, see [Credit card types (form)](https://technet.microsoft.com/library/hh209565\(v=ax.60\)).

10. Close the **Credit card types** form.

11. In the **Payment services** form, select the **Default processor for new credit cards** check box, and then close the form.

12. Test the credit card authorization process. For more information, see [Process an authorization for a sales order](process-an-authorization-for-a-sales-order.md).

13. When you are satisfied that the authorization process works correctly, open the **Payment services** form and clear the **Test mode** check box.

## Change a Payment Services account

You can change the Payment Services for Microsoft Dynamics ERP account online, if you have to.

1.  Click **Accounts receivable** \> **Setup** \> **Payment** \> **Payment services**.

2.  Click the **Manage account** button to open the Payment Services website.

3.  Make changes, as needed, and then close the browser.

4.  Close the **Payment services** form.

## See also

[About credit card authorizations](about-credit-card-authorizations.md)

[Credit card types (form)](https://technet.microsoft.com/library/hh209565\(v=ax.60\))

[Payment services (form)](https://technet.microsoft.com/library/hh227622\(v=ax.60\))

[Process an authorization for a sales order](process-an-authorization-for-a-sales-order.md)

  


