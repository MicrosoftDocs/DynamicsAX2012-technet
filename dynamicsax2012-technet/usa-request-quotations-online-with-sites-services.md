---
title: (USA) Request quotations online with Sites Services
TOCTitle: (USA) Request quotations online with Sites Services
ms:assetid: 1974d4ef-9709-46d1-bb0e-0043a51df7e9
ms:mtpsurl: https://technet.microsoft.com/library/Hh208450(v=AX.60)
ms:contentKeyID: 36056112
author: Khairunj
ms.date: 07/24/2015
mtps_version: v=AX.60
f1_keywords:
- vendor
- Azure
- ACS
- authentication
- email
- authenticate
- RFQ
- procurement
- request for quotation
- requests for quotations
- vendor portal
- request for quotations
- requests for quotation
- RFQs
- Site Services
- access control
- email template
- portal
- user account
audience: Application User
ms.search.region: USA
---

# (USA) Request quotations online with Sites Services 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft Dynamics AX includes a solution for Sites Services for Microsoft Dynamics ERP that is named **Request for quotation**. After a Sites Services Web page is set up, a purchasing agent can use this solution to post purchasing requirements online in the form of a request for quotation (RFQ). Vendors can then review the RFQ and respond with quotations.

Your system administrator must sign up for a Sites Services account before you can request quotations online. For more information, see [(USA) About Sites Services](usa-about-sites-services.md).

## Activate the Request for quotation solution

Typically, the system administrator or purchasing manager activates the Request for quotation solution.

1.  Click **Procurement and sourcing** \> **Setup** \> **Sites Services** \> **Available solutions**.

2.  In the list of solutions on the left, select the **Request for quotation** solution, and then click **Activate**.

3.  Click **Synchronize** to synchronize Microsoft Dynamics AX with Sites Services.

## Create a Sites Services Web page for the RFQ

1.  Click **Procurement and sourcing** \> **Setup** \> **Sites Services** \> **Available solutions**.

2.  Click **Available pages**.

3.  In the **Available pages** form, click **Manage pages online** to open the Sites Services Web site.

4.  On the navigation pane, click **Purchasing**, and then under **Pages**, click **Request for quotation**.

5.  In the **Pages** group, click **New page**, select the **Request for quotation** page template, and then click **Next step**.

6.  Enter a name and URL for the Web page, and then click **Create page**.
    
    The Web page displays the RFQ online.

7.  Add text and customize the Web page.
    
    For each part of the Web page, click **Edit**, and then enter the text that you want to appear on the page, or select the fields from Microsoft Dynamics AX that you want to appear. You can change the labels of the fields, specify whether the fields are read-only or editable, and change the order of the fields.
    
    For more information, click the help button in Sites Services.

8.  When you have finished customizing the Web page, click **Save and close**, and then click **Close**.

9.  Click **Sign out**.

10. (Optional) To synchronize the Web page, click **Synchronize** in the **Available solutions** form. Alternatively, you can wait until the next synchronization job that is scheduled runs. After the page is synchronized, you can create a new RFQ in Microsoft Dynamics AX and send it to this page. For more information, see "Create and send an RFQ in Microsoft Dynamics AX," later in this topic.

## Create an e-mail template

Next, create an e-mail template for the e-mail message that is sent to the vendors that you want to submit quotations.

1.  Click **Organization administration** \> **Setup** \> **E-mail templates**.

2.  On the **File** menu, click **New** to create a new e-mail template.

3.  Enter values in the **E-mail ID**, **Sender name**, **Sender e-mail**, and **Default language code** fields.

4.  Click **E-mail message**, and then enter the text that you want to send to vendors.

5.  Add the following tokens to the message. The tokens are replaced automatically with Web addresses, or URLs, when you send the message.
    
      - **%AUTHURL%** – This token is replaced with the URL of the Windows Live ID Web page.
        
        Vendors must sign in with a Windows Live ID before they can access the Web page for the RFQ.
    
      - **%URL%** – This token is replaced with the URL of the Web page for the RFQ.
    
    For example, the message may say, "Click %AUTHURL% to sign in with your Windows Live ID, and then click %URL% to view the RFQ."

6.  When you have finished creating the message, click **File**, and then click **Close**.

When you create and send the RFQ from Microsoft Dynamics AX, the e-mail message is sent to the vendors that you specify. For more information, see the next section in this topic. The RFQ is also sent to the Web page for the RFQ. It may take several minutes for the RFQ to be sent to the Web page, depending on your synchronization schedule. Therefore, we recommend that you suggest in the message that vendors wait at least 30 minutes before they visit the Web page for the RFQ.

## Create and send an RFQ in Microsoft Dynamics AX

After you create the Web page and e-mail template, you can create the RFQ in Microsoft Dynamics AX and send it to the web Web page. Microsoft Dynamics AX then sends your e-mail message to the vendors that you specified.

1.  Click **Procurement and sourcing** \> **Common** \> **Requests for quotations** \> **All requests for quotations**.

2.  On the **Action Pane**, in the **New** group, click **Request for quotation**.

3.  Under **Sites Services**, in the **Page** field, select the Web page that you created in Sites Services.

4.  In the **E-mail template** field, select the e-mail template that you created for the RFQ.

5.  Complete the other information in the RFQ.

6.  In the **Process** group, click **Send**.

## Download and review the quotations

After the due date for the quotations, you can view and evaluate the vendors' quotations in Microsoft Dynamics AX. Quotations are automatically downloaded to Microsoft Dynamics AX when Microsoft Dynamics AX is synchronized with Sites Services.

1.  Click **Procurement and sourcing** \> **Common** \> **Requests for quotations** \> **Request for quotation replies**.

2.  In the **Request for quotation replies** list, double-click the reply that you want to view and evaluate.

## See also

[(USA) About Sites Services](usa-about-sites-services.md)

[(USA) Set up and maintain a Sites Services account](usa-set-up-and-maintain-a-sites-services-account.md)

  


