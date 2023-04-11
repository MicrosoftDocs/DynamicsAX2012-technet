---
title: (RUS) Accounting transaction translation
TOCTitle: (RUS) Accounting transaction translation
ms:assetid: e2ad2e4b-b773-4016-bd4a-223f8432159a
ms:mtpsurl: https://technet.microsoft.com/library/JJ856118(v=AX.60)
ms:contentKeyID: 50406416
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Accounting transaction translation 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Translation is used to transfer accounting transactions from one company to another to transform transactions for business or international reporting standards. Usually, during translation, ledger accounts are consolidated according to a set rule. It is also sometimes necessary to recalculate data from one currency or to change financial dimensions. For example, an accounting calculation might be performed in rubles, while a business calculation is performed in dollars.

Translation can be performed between one company and multiple others. For example, the company that performs the accounting calculation might translate data to one company for international reporting, and another company for business reporting.


> [!NOTE]
> <P>Microsoft Dynamics AX only performs translations for ledger transactions.</P>



The following types of voucher translations are available:

  - **One to one**– One to one translation is used to translate transactions from a source company to a target company when the same currency is used, if the national currency and the reporting currency are the same.

  - **Historical** – The voucher translation is performed according to the exchange rate on the date when the voucher is executed.

  - **Weighted** – A weighted average is used for the exchange rate for the period.

  - **Current** – The translation is performed for the exchange rate on the date when it is performed.

  - **Special** – The translation is performed for the exchange rate that is specified in the transaction, and is not linked to the exchange rate on the voucher date or the exchange rate on the translation date.

  - **User specified** – The translation is performed according to the exchange rate that is specified by the user.

The company develops translation rules based on their accounting policies, as follows:

  - The created translation rules describe from which accounting calculation in the Russian chart of accounts to which accounting calculation in the internal financial reporting standards (IFRS) chart of accounts the translation rules are created.

  - The from and to exchange rate that is used in the transfer of accounting transactions.

  - The created translation rules describe which dimension vouchers must be transferred from the company that holds the Russian account to the company that holds the international business accounts.

You must create target companies that perform the translation. Before you create target companies, follow these prerequisite steps:

  - Set up a chart of accounts, where translation is performed for a main account.

  - Set the currencies and exchange rates.

  - Create fiscal periods.

  - Create financial dimensions.

If **Translation difference** is selected as the posting type, the correspondence is saved when the transactions are translated. The translation procedure is created periodically, and you can transfer transactions from the source company, which is the database for Russian accounting, to an IFRS company or business account.

## See also

[(RUS) Set up a translation group](rus-set-up-a-translation-group.md)

[(RUS) Perform a single translation](rus-perform-a-single-translation.md)

  


