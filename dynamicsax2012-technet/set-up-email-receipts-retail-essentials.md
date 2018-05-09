---
title: Set up email receipts (Retail essentials)
TOCTitle: Set up email receipts (Retail essentials)
ms:assetid: 413b1b34-187b-4dd7-859e-d07466a0d578
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn859560(v=AX.60)
ms:contentKeyID: 63820134
ms.date: 01/07/2015
mtps_version: v=AX.60
---

# Set up email receipts (Retail essentials) 


Email receipts are an environmentally friendly option for processing retail sales. The customer can decide whether to receive a printed receipt, an email receipt, or both. This topic explains how to set up email receipts.

For customers who are set up in Retail essentials, you can set the customer receipt option in the **Customers** form. For customers who are not set up in Retail essentials, set the default receipt option in the **Retail parameters** form.

You can set up the message body of the email receipt as form notes. You can then send email messages in different languages, depending on the language of each customer. If no customer is selected, the email message uses the language settings for your company. The form note must be set up as a **Retail Headquarters Receipt** form type.

**Prerequisites**

Before you can generate email receipts for your customers, you must configure email functionality in Retail essentials. This step includes the following tasks:

  - Set up and configure the Simple Mail Transfer Protocol (SMTP) server, and then connect Retail essentials to the SMTP server. For more information, see [Configure email functionality in Microsoft Dynamics AX](configure-email-functionality-in-microsoft-dynamics-ax.md).

  - Set up an email notification profile, and assign it to your company and stores. Email notification profiles enable email messages to be sent to an individual or a group of recipients, based on user-configured parameters.

After you complete these steps, use the procedures in this topic to set up email receipt options for your company and customers.

## Set up email receipt options

Set up default customer receipt options for customers who are not set up in Retail essentials. Also set up email receipt options for customers who are set up in Retail essentials.

## Set default options for email receipts

1.  Click **Retail essentials** \> **Channels** \> **Setup** \> **Retail parameters**.

2.  On the **Posting** tab, under **Email receipt**, in the **Receipt option** field, select a default option:
    
      - **POS** – Print receipts from the point of sale (POS) register.
    
      - **E-mail** – Send receipts to customers in email messages.
    
      - **Both** – Print receipts from the POS register and send receipts to customers in email messages.

3.  In the **Subject** field, enter the default text that appears in the subject line of a receipt that is sent as an email message.

4.  In the **File name** field, enter the file name of the recipient’s email attachment. Do not include the file name extension.

## Set email receipt options for a customer

1.  Click **Retail essentials** \> **Customers** \> **All customers**.

2.  On the **All customers** list page, select a customer, and then, on the **Customer** tab, in the **Maintain** group, click **Edit**.

3.  In the **Customers** form, on the **Retail** FastTab, in the **Receipt option** field, select an option:
    
      - **POS** – The customer will receive only printed receipts. The printed receipt is generated from the POS register.
    
      - **E-mail** – The customer will receive only email receipts.
    
      - **Both** – The customer will receive both printed receipts and email receipts.

4.  In the **Receipt email** field, enter the customer’s email address if you selected either **E-mail** or **Both** in the **Receipt option** field.

## Create body text for the email message

1.  Click **Accounts receivable** \> **Setup** \> **Forms** \> **Form notes**.

2.  Click **New** to create a new form note. In the **Form** field, select **Retail Headquarters Receipt**, and then specify a language.

3.  On the **Form note** FastTab, enter the text for the body of the email message.

## See also

[Retail parameters (form)](https://technet.microsoft.com/en-us/library/hh597194\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

