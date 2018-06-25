---
title: Set up email receipts
TOCTitle: Set up email receipts
ms:assetid: 68aa9c96-368d-4c1c-b8d0-80063dd8f3fc
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh597117(v=AX.60)
ms:contentKeyID: 39519166
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Set up email receipts [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Email receipts are an environmentally friendly option for processing retail sales. The customer can decide whether to receive a printed receipt, an email receipt, or both. This topic explains how to set up email receipts.

You can set the customer receipt option for customers who are set up in Microsoft Dynamics AX in the **Customers** form. For customers who are not set up in Microsoft Dynamics AX, set the default receipt option in the **Retail parameters** form.

You can set up the message body of the email receipt as form notes so that you can send email messages in different languages, depending on the language of the particular customer. If no customer is selected, the email message uses the language settings for your company. The form note must be set up as a **Retail Headquarters Receipt** form type.

**Prerequisites**

Before you can generate email receipts for your customers, you must configure email functionality in Microsoft Dynamics AX. This includes the following tasks:

  - Set up and configure the SMTP server, and then connect Microsoft Dynamics AX to the SMTP server. For more information, see [Configure email functionality in Microsoft Dynamics AX](configure-email-functionality-in-microsoft-dynamics-ax.md)

  - Optional: Set up email templates. For more information, see [Create application email templates](create-application-email-templates.md).

  - Set up an email notification profile and assign it to your company and stores. Email notification profiles enable emails to be sent to an individual or group of recipients based on user configured parameters.

After you complete these steps, use the procedures in this topic to set up email receipt options for your company and customers.

## Set up email receipt options

Set up default customer receipt options that can be used for customers who are not set up in Microsoft Dynamics AX. Also set up email receipt options for customers who are set up in Microsoft Dynamics AX.

## Set default options for email receipts

1.  Click **Retail** \> **Setup** \> **Parameters** \> **Retail parameters**.

2.  Click the **Posting** tab, and then under **Email receipt**, in the **Receipt option** field, select an option as the default:
    
      - **POS** – Print receipts from the point-of-sale register.
    
      - **E-mail** – Send receipts to customers in email messages.
    
      - **Both** – Print receipts from the point-of-sale register and send receipts to customers in email messages.

3.  In the **Subject** field, enter the text that appears by default in the subject line of a receipt that is sent as an email message.

4.  In the **File name** field, enter the file name of the recipient’s email attachment. Do not include the file extension.

## Set email receipt options for a customer

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  On the **All customers** list page, select a customer, and then, on the **Customer** tab, in the **Maintain** group, click **Edit**.

3.  In the **Customers** form, on the **Retail** FastTab, select an option in the **Receipt option** field:
    
      - **POS** – The customer will receive only printed receipts. The printed receipt is generated from the point-of-sale register.
    
      - **E-mail** – The customer will receive only email receipts.
    
      - **Both** – The customer will receive both a printed receipt and an email receipt.

4.  In the **Receipt email** field, enter the customer’s email address if you selected either **E-mail** or **Both** in the **Receipt option** field.

## Create body text for the email message

1.  Click **Accounts receivable** \> **Setup** \> **Forms** \> **Form notes**.

2.  Click **New** to create a new form note, and then in the **Form** field, select **Retail Headquarters Receipt**, and specify a language.

3.  On the **Form note** FastTab, enter the text that you want for the body of the email message.

## See also

[Retail parameters (form)](https://technet.microsoft.com/en-us/library/hh597194\(v=ax.60\))

[Customers (form) (Retail)](https://technet.microsoft.com/en-us/library/hh597207\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

