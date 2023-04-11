---
title: Set up Payment Services
TOCTitle: Set up Payment Services
ms:assetid: 475d8c44-a961-445b-939b-5b36380b9043
ms:mtpsurl: https://technet.microsoft.com/library/JJ680904(v=AX.60)
ms:contentKeyID: 49624325
author: tonyafehr
ms.date: 04/25/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up Payment Services 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can configure Microsoft Dynamics AX with Payment Services for Microsoft Dynamics ERP to process credit card transactions at retail point-of-sale (POS) registers, in online stores, and in the **Accounts receivable** module in Microsoft Dynamics AX. Payment data is captured once and flows securely from POS registers, online stores, and **Accounts receivable** through your business processes in Microsoft Dynamics AX.

Payment Services accepts a variety of payment types, and you can choose from several payment providers.

The process for setting up Payment Services includes the following steps, some performed by the retailer and others by the Microsoft Dynamics AX partner. The steps are performed in this order:

1.  Partner: In Partner Portal, create a Payment Services account for the retailer.

2.  Retailer: In Customer Portal, set up a merchant account with a payment provider.

3.  Partner: In Partner Portal, activate the payment provider.

4.  Retailer: In Customer Portal, test payment processing.

5.  Retailer: In Microsoft Dynamics AX, set up **Accounts receivable** for Payment Services.

6.  Retailer: In Microsoft Dynamics AX, set up retail stores for Payment Services.

7.  Retailer: In Microsoft Dynamics AX, set up online stores for Payment Services.

## Partner: In Partner Portal, create a Payment Services account for the retailer

1.  Sign in to [Partner Portal](https://go.microsoft.com/fwlink/?linkid=265493) by using your Microsoft account email address and password.

2.  Click **Customer List**, and then click **New Customer** to add the retailer.

3.  Select the retailer in the list, click **Add Service**, and then create a Payment Services account for the retailer.

4.  In the **Add Service** form, in the **Purpose of account** field, select **Production**.

5.  Click **Service List**, select the payment service that you created in step 3, and then click **Send Activation** to send an invitation to the retailer.
    
    The retailer receives this invitation by email.

## Retailer: In Customer Portal, set up a merchant account with a payment provider

1.  In the invitation email message from your Microsoft Dynamics AX partner, click the invitation link to Payment Services, and then sign in with your Microsoft account email address and password.

2.  Under **Payment settings**, click **Payment providers**.

3.  Compare the payment providers, read their terms, and then click **Sign up now** for the provider that you want.
    
      - If you select **First Data (EMPS)**, your contact information is automatically sent to First Data Merchant Services (FDMS). FDMS will contact you to process the application.
    
      - If you select **CyberSource**, your contact information is automatically sent to CyberSource. CyberSource will contact you to process the application.
    
      - If you select another provider, follow the provider’s instructions to submit an application.

4.  Sign in to [Customer Portal](https://go.microsoft.com/fwlink/?linkid=265494) by using your Microsoft account email address and password.

5.  Click **Service list**, select the check box for the payment service, and then click **Change Partner**.

6.  In the **Change support partner** form, select the partner in the list, select the **Grant service access to the selected partner** check box, and then click **Change Partner**.
    

    > [!NOTE]
    > <P>If you do not find your partner in the list, tell your partner to register as a partner for online services for Microsoft Dynamics ERP. For more information, see the <A href="https://mbs.microsoft.com/downloads/partner/softwareplusservices/partner_portal_provisioning_guide.pdf">Partner Portal Provisioning Guide</A>.</P>



7.  Sign out of Customer Portal.

The payment provider will contact you to process your application and set up a merchant account for you.

The process of setting up a merchant account typically includes performing a credit check, discussing terms of service, and signing a contract with the payment provider. This might take several days. This process does not involve any action in Microsoft Dynamics AX.

After your merchant account is set up with the payment provider, the payment provider provides the settings for the merchant account to you.

Provide the settings for the merchant account to your Microsoft Dynamics AX partner.

## Partner: In Partner Portal, activate the payment provider

1.  Sign in to [Partner Portal](https://go.microsoft.com/fwlink/?linkid=265493) by using your Microsoft account email address and password.

2.  In the **Customer list**, select the customer, and then click the link in the **Services** column.

3.  Select the service, and then click **Open Service**.

4.  Under **Payment Settings**, click **Payment Methods**.

5.  Under **Payment Provider Accounts**, select an account, and then under **Actions**, click **Activate**.
    
    The Payment Services website displays the **Payment Provider Account Activation** form.

6.  Depending on the payment provider, do one of the following:
    
      - **First Data** – use the following guidelines to enter the merchant account information that you received from the retailer and the payment provider, and then click **Activate**.
        
          - **AcquirerBin** – Enter the Acquirer BIN (Bank Identification Number).
        
          - **AgentBankNumber** – Enter the Agent Number.
        
          - **AgentChainNumber** – Enter the Chain Number.
        
          - **ApplicationCode** – If a value is not provided by the payment provider, leave the field blank.
        
          - **City** – Enter the city of the merchant.
        
          - **Comment** – If a value is not provided by the payment provider, leave the field blank.
        
          - **ConfirmationCode** – If a value is not provided by the payment provider, leave the field blank.
        
          - **Country / Region Code** – Enter the three-letter country code, such as **USA** or **CAN**.
        
          - **Email** – Enter the email address that was provided to the payment provider.
        
          - **IndustryCode** – If a value is not provided by the payment provider, leave the field blank.
        
          - **LanguageCode** – Enter the 2 letter language code, such as **EN** for US English.
        
          - **LocationNumber** – Enter the Location Number.
        
          - **MerchantAbaNumber** – If a value is not provided by the payment provider, leave this field blank.
        
          - **MerchantCategoryCode** – Enter the Merchant Category, also known as the SIC (Standard Industry Code).
        
          - **MerchantId** – Enter the Merchant Number.
        
          - **MerchantName** – Enter the name of the merchant.
        
          - **MerchantState** – Enter the state or province of the merchant.
        
          - **Postal Code** – Enter the postal code of the merchant.
        
          - **RawProvisionData** – Enter any value, such as **123abc**.
        
          - **Reimbursement** – If a value is not provided by the payment provider, leave the field blank.
        
          - **ServicePhoneNumber** – Enter **8884777877**.
        
          - **SettlementAgentNumber** – If a value is not provided by the payment provider, leave the field blank.
        
          - **SharingGroup** – If a value is not provided by the payment provider, leave the field blank.
        
          - **State / Province** – Enter the state or province of the merchant.
        
          - **StoreNumber** – Enter the Store Number.
        
          - **Street Address** – Enter the street address of the merchant.
        
          - **TerminalId** – Enter the Terminal Number of the merchant.
        
          - **VNumber** – Enter the V Number.
    
      - **First Data/Express Merchant Processing Solutions (EMPS)** – Use the following guidelines to enter the merchant account information that you received from the retailer and the payment provider, and then click **Activate**.
        
          - **DOPSIdentifier** – Enter **DOPSIdentifier**.
        
          - **DOPSPassword** – Enter **DOPSPassword**.
        
          - **MerchantCategoryCode** – Enter the merchant category code, which is also called the MCC code.
        
          - **MerchantCity** – Enter the city of the merchant.
        
          - **MerchantCountryCode** – Enter the two-letter country code, such as **US** or **CA**.
        
          - **MerchantId** – Enter the merchant ID. If there are two merchant IDs, **do not** enter **Nashville MID**.
        
          - **MerchantName** – Enter the name of the merchant.
        
          - **MerchantPostalCode** – Enter the postal code of the merchant.
        
          - **MerchantStateOrProvince** – Enter the state or province of the merchant.
        
          - **MerchantStatus** – Enter **1**.
        
          - **MerchantStreetAddress** – Enter the street address of the merchant.
        
          - **ServicePhoneNumber** – Enter **8884777877**.
        
          - **StoreNumber** – If a value is not provided by the payment provider, leave this field blank.
        
          - **TerminalId** – Enter the terminal ID of the merchant.
    
      - **CyberSource** – Use the following guidelines to enter the merchant account information that you received from the retailer and the payment provider, and then click **Activate**.
        
          - **MerchantId** – If a value is not provided by the payment provider, enter any value, such as **123abc**.
        
          - **RawProvisionData** – Enter any value.
    
      - **PayPal** – No action is needed. A merchant account is activated automatically after it is created by the payment provider.

7.  Under **Accepted Payment Methods**, select the payment provider to use for each payment method.

8.  Click **Save and Close**.

## Retailer: In Customer Portal, test the payment service

1.  Sign in to [Customer Portal](https://go.microsoft.com/fwlink/?linkid=265494) by using your Microsoft account email address and password.

2.  Click **Dashboard**, and then click the Payment Services account.

3.  Under **Places**, click **Manage payments**, and then click **New Payment**.

4.  Under **Card Information**, enter the required information, including a minimum payment amount, such as $1.00.

5.  Under **Billing Address**, enter the required information, and then click **Process Payment**.

6.  Repeat steps 3 through 5 for each type of credit card that you accept in your stores.

7.  Sign out of Customer Portal.

8.  Contact the payment provider for each test transaction and make sure that the transactions are processed with best possible interchange rate. Also check that the correct transactions fees are assessed, as specified in your payment provider agreement.

9.  Sign in to Customer Portal, click **Dashboard**, and then click the same Payment Services account as in step 2.

10. Under **Places**, click **Manage payments**, and then select and refund each of the test transactions.

## Retailer: In Microsoft Dynamics AX, set up Accounts receivable for Payment Services

1.  Click **Accounts receivable** \> **Setup** \> **Payment** \> **Payment services**.

2.  In the **Payment services** form, click **New**, and then in the **Payment service** field, enter a name for the payment service.

3.  In the **Payment connector** field, select **Dynamics Payment Connector**.

4.  Under **Test mode**, enter the following information:
    
      - In the **Merchant account ID** field, enter the merchant account ID that you received from the payment provider.
    
      - In the **Service account ID** field, enter the service account ID that you received from the payment provider.
    
      - In the **Microsoft account** field, enter the Microsoft account email address. This must be the same Microsoft account that was used to set up the merchant account on Customer Portal.
    
      - In the **Microsoft account password** field, enter the password for the Microsoft account.
    
      - In the **Supported currencies** field, enter currency codes for the currencies that are supported by the payment service. Separate the currency codes by semicolons, without using spaces. For example, enter **USD;CAD**.
    
      - In the **Supported payment methods** field, enter the payment methods that are accepted by the payment service. Separate the payment methods by semicolons without spaces. For example, enter **Visa;AmericanExpress;Debit**.
    

    > [!NOTE]
    > <P>Information is entered automatically in the <STRONG>Assembly name</STRONG>, <STRONG>Environment</STRONG>, <STRONG>Portal URL</STRONG>, and <STRONG>Public key</STRONG> fields. The public key is automatically generated by Microsoft Dynamics AX to encrypt the data that is sent to the payment service.</P>

    
    For instructions about how to set up **Accounts receivable** for Payment Services, see [Set up credit card authorizations](set-up-credit-card-authorizations.md).

5.  Copy the contents of the **Public key** field.

6.  Sign in to [Customer Portal](https://mocp.microsoftonline.com/site/default.aspx) by using your Microsoft account email address and password.

7.  Under **Organization settings**, click **User management**, and then in the **New** group, click **System User**.

8.  In the **Public key** field, enter the public key that you copied in step 6, and then click **Save**.

9.  In the **User management** list, click the first name or the last name of the system user that you created in step 8, and then click **Edit**.

10. Under **Services and Roles**, select **Payment Administrators** in the **Available Roles** list, use the right arrow button to add the role to the **Selected Roles** list, and then click **Save**.

11. Sign out of Customer Portal.

12. In Microsoft Dynamics AX, in the **Payment services** form, click **Validate**.
    
    The validation is confirmed as successful.

13. Click **Credit card types**, and then add all the credit cards that you accept.

## Retailer: In Microsoft Dynamics AX, set up retail stores for Payment Services


> [!NOTE]
> <P>You must complete the previous procedure, "Set up Accounts receivable for Payment Services" before you can set up retail stores for Payment Services.</P>



1.  Click **Accounts receivable** \> **Setup** \> **Payment** \> **Payment services**.

2.  In the **Payment services** form, click **Credit card types**, and then add all the credit cards that each retail store accepts.

3.  Click **Retail** \> **Setup** \> **POS** \> **Profiles** \> **Hardware profiles**. In the left pane, select the hardware profile for the store.

4.  On the **EFT service** FastTab, in the **EFT service** field, select **Payment Connector**.

5.  In the **Merchant account ID** field, enter the merchant account ID that you received from the payment provider.

6.  In the **Service account ID** field, enter the service account ID that you received from the payment provider.

7.  In the **Microsoft account** field, enter the Microsoft account email address. This must be the same Microsoft account that was used to set up the merchant account on Customer Portal.

8.  In the **Microsoft account password** field, enter the password for the Microsoft account.

9.  In the **Supported currencies** field, enter currency codes for the currencies that are supported by the payment service. Separate the currency codes by semicolons without spaces. For example, enter **USD;CAD**.

10. In the **Supported payment methods** field, enter the payment methods that are accepted by the payment service. Separate the payment methods by semicolons without spaces. For example, enter **Visa;AmericanExpress;Debit**.

11. Copy the contents of the **Public key** field.

12. Sign in to [Customer Portal](https://mocp.microsoftonline.com/site/default.aspx) by using your Microsoft account email address and password.

13. Under **Organization settings**, click **User management**, and then in the **New** group, click **System User**.

14. In the **Public key** field, enter the public key that you copied in step 9, and then click **Save**.

15. In the **User management** list, click the first name or the last name of the system user that you created in step 11, and then click **Edit**.

16. Under **Services and Roles**, select **Payment Administrators** in the **Available Roles** list, use the right arrow button to add the role to the **Selected Roles** list, and then click **Save**.


> [!NOTE]
> <P>Information is entered automatically in the <STRONG>Assembly name</STRONG>, <STRONG>Environment</STRONG>, <STRONG>Portal URL</STRONG>, and <STRONG>Public key</STRONG> fields. The public key is automatically generated by Microsoft Dynamics AX to encrypt the data that is sent to the payment service.</P>



## Retailer: In Microsoft Dynamics AX, set up online stores for Payment Services


> [!NOTE]
> <P>You must complete the procedure, "Set up Accounts receivable for Payment Services," earlier in this topic, before you can set up online stores for Payment Services.</P>



1.  Click **Retail** \> **Common** \> **Retail channels** \> **Online stores**. Select an online store, and then on the **Action Pane**, click **Edit**.

2.  On the **Payment accounts** FastTab, in the **Connectors** field, select **Dynamics Payment Connector**.

3.  Click **Add**, and then under **Details**, enter the following information:
    
      - In the **Merchant account ID** field, enter the merchant account ID that you received from the payment provider.
    
      - In the **Service account ID** field, enter the service account ID that you received from the payment provider.
    
      - In the **Microsoft account** field, enter the Microsoft account email address. This must be the same Microsoft account that was used to set up the merchant account on Customer Portal.
    
      - In the **Microsoft account password** field, enter the password for the Microsoft account.
    
      - In the **Supported currencies** field, enter currency codes for the currencies that are supported by the payment service. Separate the currency codes by semicolons. For example, enter **USD;CAD**.
    
      - In the **Supported payment methods** field, enter the payment methods that are accepted by the payment service. Separate the payment methods by semicolons without spaces. For example, enter **Visa;AmericanExpress;Debit**.
    

    > [!NOTE]
    > <P>Information is entered automatically in the <STRONG>Assembly name</STRONG>, <STRONG>Environment</STRONG>, <STRONG>Portal URL</STRONG>, and <STRONG>Public key</STRONG> fields. The public key is automatically generated by Microsoft Dynamics AX to encrypt the data that is sent to the payment service.</P>



4.  Copy the contents of the **Public key** field.

5.  Sign in to [Customer Portal](https://mocp.microsoftonline.com/site/default.aspx) with your Microsoft account email address and password.

6.  Under **Organization settings**, click **User management**, and then in the **New** group, click **System User**.

7.  In the **Public key** field, enter the public key that you copied in step 4, and then click **Save**.

8.  In the **User management** list, click the first name or the last name of the system user that you created in step 6, and then click **Edit**.

9.  Under **Services and Roles**, select **Payment Administrators** in the **Available Roles** list, use the right arrow button to add the role to the **Selected Roles** list, and then click **Save**.

## See also

[About credit card authorizations](about-credit-card-authorizations.md)

[Set up credit card authorizations](set-up-credit-card-authorizations.md)

  


