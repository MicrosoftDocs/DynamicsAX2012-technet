---
title: Add a Customer administrator to a service in RapidStart Services
TOCTitle: Add a Customer administrator to a service in RapidStart Services
ms:assetid: 35b5581b-5557-4836-8439-635c4cf80af6
ms:mtpsurl: https://technet.microsoft.com/library/Dn193993(v=AX.60)
ms:contentKeyID: 52348250
author: Khairunj
ms.author: daxcpft
ms.date: 09/18/2015
mtps_version: v=AX.60
f1_keywords:
- add RapidStart customer
- Customer administrator for RapidStart Services
- enroll RapidStart customer
- invite RapidStart customer
- RapidStart administrator
- RapidStart customer enrollment
- RapidStart customer registration
---

# Add a Customer administrator to a service in RapidStart Services 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Beginning October 1, 2015, RapidStart services will no longer be supported. For more information, see the announcement on CustomerSourcehttps://mbs.microsoft.com/partnersource/northamerica/news-events/news/RapidStartServicesDiscontinued or PartnerSourcehttps://mbs.microsoft.com/customersource/northamerica/news-events/news-events/news/RapidStartServicesDiscontinued.

This topic explains how a Partner implementation expert can make RapidStart Services available to customers and prospects by using online services for Microsoft Dynamics ERP.


> [!IMPORTANT]
> <P>In the March 2014 release of Microsoft Dynamics Lifecycle Services, support for creating and opening RapidStart Services projects for Microsoft Dynamics AX was added to the Lifecycle Services project page. You can use the online services for Microsoft Dynamics ERP website as described in the rest of this topic, or you can use Lifecycle Services instead.</P>
> <P>To use Lifecycle Services, visit <A href="https://go.microsoft.com/fwlink/?linkid=306503">Microsoft Dynamics Lifecycle Services</A>.</P>



## Prerequisites

Before you start this process, you must do the following:

  - Complete the steps in the [Activate your Partner Portal account for Microsoft Dynamics ERP RapidStart Services](activate-your-partner-portal-account-for-microsoft-dynamics-erp-rapidstart-services.md) topic.

  - Identify the person who will act as the Customer administrator for RapidStart Services. This person might be someone from the customer organization. Alternatively, someone from a partner organization can work on behalf of the customer, provided that they use a different Microsoft account from the one that they use for their partner login.
    
    The Customer administrator must provide you with the ID for the Microsoft account that is used to sign in to CustomerSource. This is the ID that you must enter during the registration process. Make sure that the Customer administrator gives you only the ID for the Microsoft account and **not the password**.

After you add the customer in online services for Microsoft Dynamics ERP, the Customer administrator receives an email message from dynamicsonline@microsoft.com. This message contains an activation link that is used to complete the process. The link opens a web page, where the customer must sign in by using the Microsoft account that you entered when you registered the customer.

After the Customer administrator signs in, he or she reviews and agrees to the online services agreement and privacy statement, and then signs in to Customer Portal. In Customer Portal, other users in the customer organization can be added and assigned to roles.

## Make RapidStart Services available to customers and prospects

1.  In your browser, open online services at [http://www.dynamicsonline.com](https://go.microsoft.com/fwlink/p/?linkid=141031), and sign in to Partner Portal. If the **Getting Started – Partner Portal for Microsoft Dynamics® ERP** page is displayed, click **Create a new customer**.

2.  On the **Customers** page, on the **Action Pane**, click **New Customer**. Then, depending on whether you are enrolling an existing customer or a prospective customer, follow the instructions in this table.
    
    To use RapidStart Services in your own partner organization, you must add yourself as a new customer and use the procedure for enrolling a prospect.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Customer status</p></th>
    <th><p>Action</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Existing customer</p></td>
    <td><p>To enroll a customer who has an account in the VOICE system, follow these steps:</p>
    <ol>
    <li><p>On the <strong>Create a new customer</strong> page, in the <strong>Customer account number</strong> field, enter the customer’s account number in VOICE.</p></li>
    <li><p>Click <strong>Search my customers</strong>.</p>
    <p>The customer appears only if you have entered a correct account number and you are the customer’s partner of record in VOICE. If you don’t see your customer on the <strong>Select customer</strong> page, enter the customer name, and then click <strong>Search</strong>. The search page displays the customer accounts that resemble your search term and that are associated with your partner account in VOICE. Select the customer in the list, and then click <strong>Select customer</strong>. The <strong>Select customer</strong> page closes.</p></li>
    <li><p>On the <strong>Create a new customer</strong> page, the <strong>Customer account number</strong> field displays the account number. To copy the organization information and address from the customer record in VOICE, click <strong>Fill other fields using the customer account number</strong>. You can also enter the customer information manually.</p></li>
    </ol>
    <div class="alert">

    > [!NOTE]
    > <P>When you create a customer account here without adding a VOICE account number, the RapidStart Services service remains active for only 90 days. To continue to use RapidStart Services after 90 days, you must add the customer’s account number from the VOICE system to the customer record in Partner Portal. If you don’t add the VOICE number within 90 days, the account is inactivated. Microsoft retains the data for the account for an additional 30 days. If you contact Support and provide the customer’s VOICE account number during that time, you can reactivate the account and continue to work with the data.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p>Prospective customer</p></td>
    <td><p>To enroll a prospect, follow these steps:</p>
    <ol>
    <li><p>On the <strong>Create a new customer</strong> page, enter the Customer administrator’s information.</p></li>
    <li><p>Click <strong>Create Customer</strong>. For a prospect, you don’t need to enter anything in the <strong>Customer account number</strong> field.</p></li>
    <li><p>In the <strong>Contact email address</strong> field, enter the email address that is used to contact the customer. Notifications are sent to this address.</p>
    <p>This email address can be different from the Microsoft account email address.</p></li>
    </ol></td>
    </tr>
    </tbody>
    </table>


3.  After you provide the required information, click **Create customer**. The **Create a new customer** page closes.

4.  In the **Customer** list, select the customer, and then, on the **Action Pane**, click **Add Service**.

5.  On the **Choose the service you want to sign up for** page, click **RapidStart Services**.

6.  On the **Sign up for RapidStart Services** page, click **Add Service**.
    

    > [!IMPORTANT]
    > <P>Make sure that the <STRONG>Country/region of use</STRONG> field is set correctly, because you can’t change the value later. We have multiple data centers, and RapidStart Services pages load faster if you select the data center that is closest to your physical location. You can view the list of countries and regions where RapidStart Services is currently supported in the <STRONG>RapidStart Services</STRONG> section at the bottom of the online services home page at <A href="https://go.microsoft.com/fwlink/p/?linkid=141031">http://www.dynamicsonline.com</A>. If you don’t see the country or region for your customer, contact Support before you continue.</P>



7.  On the **Next steps** page, click **Close**. You have finished activating the subscription and can now activate RapidStart Services.

8.  On the **Service List** page, select the customer, and then, on the **Action Pane**, click **Send Activation**.

9.  On the **Send Activation** page, complete the information for the Customer administrator. The contact email address can differ from the email address that the Customer administrator uses for the Microsoft account.

10. Click **Activate** to send an activation email message to the Customer administrator.

11. On the **Service List** page, verify that the service status for the customer is **Invitation sent**.

## See also

[Add users and assign roles in RapidStart Services](add-users-and-assign-roles-in-rapidstart-services.md)

  


