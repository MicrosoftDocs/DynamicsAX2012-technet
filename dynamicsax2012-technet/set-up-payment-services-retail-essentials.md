---
title: Set up payment services (Retail essentials)
TOCTitle: Set up payment services (Retail essentials)
ms:assetid: 29da1ae7-fb72-4dc9-894a-2ebb0b271fcb
ms:mtpsurl: https://technet.microsoft.com/library/Dn716062(v=AX.60)
ms:contentKeyID: 62200328
author: Khairunj
ms.date: 11/13/2014
mtps_version: v=AX.60
---

# Set up payment services (Retail essentials) 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

You can configure Retail essentials to process credit card transactions at retail point-of-sale (POS) registers. Payment data is captured once and then flows securely from the POS registers through your business processes in Retail essentials. This topic explains how to set up a payment service for Retail essentials to accept a variety of payment types.

The process for setting up a payment service in Retail essentials includes the following steps, which must be completed in this order:

1.  Partner: In Partner Portal, create a payment service account for the retailer.

2.  Retailer: In Customer Portal, set up a merchant account with a payment provider.

3.  Retailer: Set up Retail essentials for a payment service.

4.  Retailer: Set up retail stores for a payment service.

## Partner: In Partner Portal, create a payment service account for the retailer

1.  Sign in to [Partner Portal](https://go.microsoft.com/fwlink/?linkid=265493) by using the email address and password for your Microsoft account.

2.  Click **Customer List**, and then click **New Customer** to add the retailer.

3.  Select the retailer in the list, click **Add Service**, and then create a Payment Services for Microsoft Dynamics ERP account for the retailer.

4.  In the **Add Service** form, in the **Purpose of account** field, select **Production**.

5.  Click **Service List**, select the payment service that you created in step 3, click **Send Activation**, and then enter the customer’s contact information. This information includes the email address for the customer’s Microsoft account.

6.  Click **Activate** to send an invitation to the retailer.
    
    The retailer receives this invitation by email.

## Retailer: In Customer Portal, set up a merchant account with a payment provider

1.  In the invitation email message from your Retail essentials partner, click the invitation link to Payment Services. Sign in by using the email address and password for your Microsoft account.

2.  If you are asked to review and accept the Terms of Service Agreement, review the agreement and the Privacy Statement, select the **I accept the Terms of Service Agreement** check box, and then click **Activate**.

3.  Click **Open** for the payment service.

4.  Under **Payment settings**, click **Payment providers**.

5.  Compare the payment providers, read the terms for each provider, and then click **Sign up now** for the provider that you want.
    
      - If you select **First Data (EMPS)**, your contact information is automatically sent to First Data Merchant Services (FDMS). FDMS will contact you to process the application.
    
      - If you select **CyberSource**, your contact information is automatically sent to CyberSource. CyberSource will contact you to process the application.
    
      - If you select another provider, follow the provider’s instructions to submit an application.

6.  Sign in to [Customer Portal](https://go.microsoft.com/fwlink/?linkid=265494) by using the email address and password for your Microsoft account.

7.  Click **Service list**, select the check box for the payment service, and then click **Change Partner**.

8.  In the **Change support partner** form, select the partner in the list, select the **Grant service access to the selected partner** check box, and then click **Change Partner**.
    

    > [!NOTE]
    > <P>If you do not find your partner in the list, tell your partner to register as a partner for online services for Microsoft Dynamics ERP. For more information, see the <A href="https://mbs.microsoft.com/downloads/partner/softwareplusservices/partner_portal_provisioning_guide.pdf">Partner Portal Provisioning Guide</A>.</P>



9.  Sign out of Customer Portal.

The payment provider will contact you to process your application and set up a merchant account for you.

The process of setting up a merchant account typically includes a credit check. Typically, you must also discuss terms of service and sign a contract with the payment provider. This process might require several days. The process does not require any action in Retail essentials.

After your merchant account is set up with the payment provider, the payment provider provides the settings for your merchant account.

## Retailer: Set up Retail essentials for a payment service

1.  Click **Retail essentials** \> **Financials** \> **Setup** \> **Payment services**.

2.  In the **Payment services** form, click **New**, and then, in the **Payment service** field, enter a unique name for the payment service.

3.  In the **Payment connector** field, select **Dynamics Payment Connector**.

4.  In the **Test mode** field, select **true** if you are testing the payment service. If the payment service is active in the store, select **false**.

5.  Under **Payment service account**, enter the following information:
    
    1.  In the **Merchant account ID** field, enter the merchant account ID that you received from the payment provider.
    
    2.  In the **Service account ID** field, enter the service account ID that you received from the payment provider.
    
    3.  In the **Microsoft account** field, enter the email address for your Microsoft account. This account must be the same Microsoft account that was used to set up the merchant account in Customer Portal.
    
    4.  In the **Microsoft account password** field, enter the password for the Microsoft account.
    
    5.  In the **Supported currencies** field, enter currency codes for the currencies that are supported by the payment service. Separate the currency codes by semicolons, without using spaces. For example, enter **USD;CAD**.
    
    6.  In the **Supported payment methods** field, enter the payment methods that are accepted by the payment service. Separate the payment methods by semicolons, without using spaces. For example, enter **Visa;AmericanExpress;Debit**.
    

    > [!NOTE]
    > <P>Information is entered automatically in the <STRONG>Assembly name</STRONG>, <STRONG>Environment</STRONG>, <STRONG>Portal URL</STRONG>, and <STRONG>Public key</STRONG> fields. Microsoft Dynamics AX automatically generates the public key that is used to encrypt data that is sent to the payment service.</P>



6.  Copy the contents of the **Public key** field.

7.  Sign in to [Customer Portal](https://mocp.microsoftonline.com/site/default.aspx) by using the account email address and password for your Microsoft account.

8.  Under **Organization settings**, click **User management**, and then, in the **New** group, click **System User**.

9.  In the **Public key** field, paste the public key that you copied in step 6, and then click **Save**.

10. In the **User management** list, click the first name or last name of the system user that you created in step 8, and then click **Edit**.

11. Under **Services and Roles**, in the **Available Roles** list, select **Payment Administrators**. Use the right arrow button to add the role to the **Selected Roles** list, and then click **Save**.

12. Sign out of Customer Portal.

13. In Microsoft Dynamics AX, in the **Payment services** form, click **Validate**.
    
    The validation is confirmed as successful.

14. Click **Credit card types**, and then add all the credit card types that you accept.

## Retailer: Set up stores for a payment service

1.  Click **Retail essentials** \> **Channels** \> **Setup** \> **POS** \> **Profiles** \> **Hardware profiles**.

2.  In the **POS hardware profile** form, in the left pane, select the hardware profile for the store.

3.  On the **EFT service** FastTab, in the **EFT service** field, select **Payment Connector**.

4.  In the **Merchant account ID** field, enter the merchant account ID that you received from the payment provider.

5.  In the **Service account ID** field, enter the service account ID that you received from the payment provider.

6.  In the **Microsoft account** field, enter the email address for your Microsoft account. This account must be the same Microsoft account that was used to set up the merchant account in Customer Portal.

7.  In the **Microsoft account password** field, enter the password for the Microsoft account.

8.  In the **Supported currencies** field, enter currency codes for the currencies that are supported by the payment service. Separate the currency codes by semicolons, without using spaces. For example, enter **USD;CAD**.

9.  In the **Supported payment methods** field, enter the payment methods that are accepted by the payment service. Separate the payment methods by semicolons, without using spaces. For example, enter **Visa;AmericanExpress;Debit**.

10. Copy the contents of the **Public key** field.

11. Sign in to [Customer Portal](https://mocp.microsoftonline.com/site/default.aspx) by using the email address and password for your Microsoft account.

12. Under **Organization settings**, click **User management**, and then, in the **New** group, click **System User**.

13. In the **Public key** field, paste the public key that you copied in step 10, and then click **Save**.

14. In the **User management** list, click the first name or last name of the system user that you created in step 12, and then click **Edit**.

15. Under **Services and Roles**, in the **Available Roles** list, select **Payment Administrators**. Use the right arrow button to add the role to the **Selected Roles** list, and then click **Save**.

16. Sign out of Customer Portal.

## See also

[Setting up payment methods (Retail essentials)](setting-up-payment-methods-retail-essentials.md)

  


