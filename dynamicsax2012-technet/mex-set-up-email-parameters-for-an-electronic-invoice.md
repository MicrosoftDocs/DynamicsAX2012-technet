---
title: (MEX) Set up email parameters for an electronic invoice
TOCTitle: (MEX) Set up email parameters for an electronic invoice
ms:assetid: fcb13b86-7c2f-4657-a151-5017dddf2dcc
ms:mtpsurl: https://technet.microsoft.com/library/Hh227579(v=AX.60)
ms:contentKeyID: 36060097
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (MEX)
- electronic invoice
- Set up
- email parameters
audience: Application User
ms.search.region: Mexico
---

# (MEX) Set up email parameters for an electronic invoice 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **E-mail parameters** form and the **Set up batch processing** class form to set up email parameters for an electronic invoice. In the **Print destination settings** form, in the **File format** field, select **PDF** so that you can generate the electronic invoice as a .pdf file and send the file as an email attachment to a customer.

Set up the following email parameters to send an electronic invoice:

  - Set up Simple Mail Transfer Protocol (SMTP) to send email messages. Use the **E-mail parameters** form to set up an SMTP server and port, local computer name, user name, and password to send email messages to customers. For more information, see [E-mail parameters (form)](https://technet.microsoft.com/library/aa591302\(v=ax.60\)).

  - Create a batch group to print an electronic invoice. Use the **Batch group** form to create a batch group to send email messages by using a batch process. You must assign the batch group to the batch server that is set up to print electronic invoices. For more information, see [Create a batch group](create-a-batch-group.md).

  - Set up a batch process to send email messages for electronic invoices. Use the **Set up batch processing** form to process the email tasks that were ordered earlier and added to the batch group. For more information, see [Create a batch group](create-a-batch-group.md).

  - Create an email template for an electronic invoice. Use the **E-mail templates** form to create a predefined email message for a customer. You can set up a priority and assign a batch group for the email message. You can also enter a predefined subject for your email message in the **Subject** field. When you post an electronic invoice, the subject of the email message is updated by using the predefined text from the **Subject** field and the posted invoice number. For example, if you entered Electronic invoice submitted in the **Subject** field and you posted invoice A-11122222, the subject of the email message is displayed as Electronic invoice submitted - A-11122222. For more information, see [E-mail templates (form)](https://technet.microsoft.com/library/aa577102\(v=ax.60\)).

  - Send email messages by using a batch process. Use the **E-mail distributor batch** form to send email to customers by using the batch process. For more information, see [E-mail distributor batch (form)](https://technet.microsoft.com/library/bb147537\(v=ax.60\)).

  


