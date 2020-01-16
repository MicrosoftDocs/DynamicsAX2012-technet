---
title: Set up receipt options (Retail essentials)
TOCTitle: Set up receipt options (Retail essentials)
ms:assetid: 6f578f01-9b7d-45ad-918d-7041dcef25c1
ms:mtpsurl: https://technet.microsoft.com/library/Dn736891(v=AX.60)
ms:contentKeyID: 62200368
author: Khairunj
ms.date: 08/15/2014
mtps_version: v=AX.60
---

# Set up receipt options (Retail essentials) 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to set up receipt options. You can specify receipt options for all customers and for specific customers who have been added to the **Customers** form. Receipts can be printed, sent in email messages, or both printed and sent in email messages. Customers can also choose receipt options at the point of sale (POS).

If you select either email receipts or both printed receipts and email receipts, you must also specify the receipt profile that is used to send the email receipts.


> [!NOTE]
> <P>In Retail essentials, the forms that you use to complete these tasks might include a subset of the controls that are available for other configurations of Retail. If a topic about these forms describes controls that you don't see, it may be because you’re using Retail essentials.</P>



## Set up receipt options for all customers

1.  Click **Retail essentials** \> **Channels** \> **Setup** \> **Retail parameters**.

2.  On the **Posting** tab, on the **Email receipt** FastTab, in the **Receipt option** field, select the default receipt option:
    
      - **POS** – Print receipts from the POS register.
    
      - **E-mail** – Send receipts to customers in email messages.
    
      - **Both** – Print receipts from the POS register and send receipts to customers in email messages.

3.  In the **Subject** field, enter the default text that appears as the subject line of email message that are used to send receipts.

4.  In the **File name** field, enter the file name of the email attachment for the recipient. Do not include the file extension.

## Set up receipt options for specific customers

1.  Click **Retail essentials** \> **Customers** \> **All customers**.

2.  On the **All customers** list page, select a customer, and then, on the **Customer** tab, in the **Maintain** group, click **Edit**.

3.  In the **Customers** form, on the **Retail** FastTab, select an option in the **Receipt option** field:
    
      - **POS** – The customer receives only printed receipts. The printed receipt is generated from the POS register.
    
      - **E-mail** – The customer receives only email receipts.
    
      - **Both** – The customer receives both printed receipts and email receipts.

4.  If you selected either **E-mail** or **Both** in the **Receipt option** field, in the **Receipt email** field, enter the customer’s email address.

## Specify a receipt profile for email receipts

1.  Click **Retail essentials** \> **Channels** \> **Setup** \> **POS** \> **Profiles** \> **Functionality profiles**.

2.  In the **POS functionality profile** form, select a profile, and then, on the **General** tab, in the **Email receipts** group, in the **Receipt profile ID** field, select a receipt profile.

## See also

[Set up receipt formats (Retail essentials)](set-up-receipt-formats-retail-essentials.md)

  


