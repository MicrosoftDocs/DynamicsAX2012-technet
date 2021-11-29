---
title: (RUS) About the electronic exchange format for client bank payments
TOCTitle: (RUS) About the electronic exchange format for client bank payments
ms:assetid: 53d82898-fe3b-488f-8462-3aa7895b904b
ms:mtpsurl: https://technet.microsoft.com/library/JJ665392(v=AX.60)
ms:contentKeyID: 49387480
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) About the electronic exchange format for client bank payments 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use the electronic exchange format to make client bank payments in Microsoft Dynamics AX. The electronic exchange format lets you interface with multiple bank templates to transfer electronic payments.

You must customize the electronic exchange formats to export or import data for exchange. When you configure the import or export settings for each bank account, you can specify the list of fields, the field order number, the field separator character, the naming format and extension of output files, and the structure of the data in the file. You can also set the default folders that are used to exchange files. This includes the export folder, the import folder, and the folder where payment files are archived after the transfer is completed.

Use the electronic exchange formats for client bank payments to complete the following transactions:

  - Export outgoing payments – Make payments to vendors, return money to customers, create purchase, sales, or currency transfers, and complete bank account or cash account operations. You can export outgoing payments that are made to the bank that is created in the payment journals to the archive file, which can be used as an interface between Microsoft Dynamics AX and the client bank program. The payment lines that are created are exported sequentially for each bank account, according to the details that you specify in the electronic exchange interface setup. A separate export file is created for each bank account, and you can view all of the payment documents electronically, or in hard copy in the payment order registry.

  - Import bank account statements (incoming and outgoing documents, and account balances) – The bank account statements are imported when a payment is made that increases the amount in the company bank account. During import, you can use the electronic exchange file formats, and the data is imported to Microsoft Dynamics AX from the client bank. Data about incoming payments, acknowledgment of payments, and a statement of bank accounts are imported from the client bank, and then exported to an archive file in Microsoft Dynamics AX. You can import incoming and outgoing payments periodically, and update the bank account statement for a company. The imported payments are adjusted, and the payments are posted.

Before you create a client bank payment transaction, complete the following tasks:

  - Set up a bank account for your company. For more information, see [Bank accounts (form)](https://technet.microsoft.com/library/aa587660\(v=ax.60\)).

  - Set up currency and exchange rates. For more information, see [Currency exchange rates (form)](https://technet.microsoft.com/library/hh209477\(v=ax.60\)).

  - Set up the terms of payment for a payment transaction. For more information, see [Terms of payment (form)](https://technet.microsoft.com/library/aa588427\(v=ax.60\)).

  - Set up journal names for payment journals and journal names for a general journal. For more information, see [Set up journal names](set-up-journal-names.md) and [Journal names setup (form)](https://technet.microsoft.com/library/aa552517\(v=ax.60\)).

## See also

[(RUS) Set up a customizable file format for a method of payment](rus-set-up-a-customizable-file-format-for-a-method-of-payment.md)

[(RUS) Set up an electronic exchange format for a client bank](rus-set-up-an-electronic-exchange-format-for-a-client-bank.md)

  


