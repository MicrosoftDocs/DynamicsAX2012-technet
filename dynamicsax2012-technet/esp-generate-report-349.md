---
title: (ESP) Generate Report 349
TOCTitle: (ESP) Generate Report 349
ms:assetid: 4d19eacd-0ff1-4389-96f3-cbb37dc6550b
ms:mtpsurl: https://technet.microsoft.com/library/Dn353635(v=AX.60)
ms:contentKeyID: 55129178
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.EUSalesListSelection
- Forms.EUSalesList
- ES - 00001
- MsDynAx060.Forms.EUSalesList
- MsDynAx060.Forms.EUSalesListSelection
audience: Application User
ms.search.region: Spain
---

# (ESP) Generate Report 349 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012_

Use the **Transfer transactions for EU sales list** form to transfer customer transactions and vendor transactions to the **EU sales list** form before you generate Report 349 as an ASCII file. You can also use delivery codes to include vendor transactions and customer transactions on Report 349. You can modify the delivery code for customer transactions that have item lines and service lines. For vendor transactions and customer transactions that have only service lines, the default delivery code is **E - Normal delivery**. The delivery code for each transaction is also included on the report.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 3 for AX 2012.</P>



Complete the following tasks before you generate Report 349:

  - Set up the country code or region code. For more information, see [About Intrastat](about-intrastat.md).

  - Set up Intrastat parameters for Report 349. For more information, see [About Intrastat](about-intrastat.md) and [Set up Intrastat from a free text invoice](set-up-intrastat-from-a-free-text-invoice.md).

  - Create commodity codes. For more information, see [Commodity codes (form)](https://technet.microsoft.com/library/aa617816\(v=ax.60\)).

  - Set up exchange rates. For more information, see [Exchange rate types (form)](https://technet.microsoft.com/library/hh242857\(v=ax.60\)).

  - Set up sales tax codes and sales tax groups. For more information, see [Set up and use sales tax codes](set-up-and-use-sales-tax-codes.md), [Sales tax codes (form)](https://technet.microsoft.com/library/aa553257\(v=ax.60\)), [Set up and use a sales tax group](set-up-and-use-a-sales-tax-group.md), and [Sales tax groups (form)](https://technet.microsoft.com/library/aa498345\(v=ax.60\)).

  - Select the **Transfer purchases** check box in the **EU sales list** area in the **Foreign trade parameters** form. For more information, see [Foreign trade parameters (form)](https://technet.microsoft.com/library/aa620385\(v=ax.60\)).

Use this procedure to transfer customer transactions and vendor transactions to the **EU sales list** form before you generate Report 349 as an ASCII file.

1.  Click **Organization administration** \> **Periodic** \> **Foreign trade** \> **EU sales list**.

2.  In the **EU sales list** form, click **Transfer** to open the **Transfer transactions for EU sales list** form to specify the reporting type for transferring the customer invoices, vendor invoices, or project invoices. For more information, see [Generate the EU sales list](generate-the-eu-sales-list.md) and [Transfer transactions for EU sales list (form)](https://technet.microsoft.com/library/aa499405\(v=ax.60\)).

3.  Click **Transfer** to transfer the transactions.

4.  In the **EU sales list** form, on the **Correction** tab, in the **Delivery code** field, select one of the following delivery codes:
    
      - **E - Normal delivery** – To report transactions for the delivery of items between EU member countries/regions.
    
      - **M - Delivery of goods from a tax-exempt importation** – To report transactions for the delivery of tax-exempt imported items to EU member countries/regions.
    
      - **H - Delivery of goods from a tax-exempt importation by an official tax representative** – To report transactions that were verified by an official tax representative for the delivery of tax-exempt imported items to EU member countries/regions.

5.  Click **Validate** to validate the transactions.

6.  Click **Reporting** to open the **EU reporting** form.

7.  In the **Reporting period** field, specify the reporting period.

8.  In the **From date** and **To date** fields, enter the starting date and ending date of the period that Report 349 is generated for.

9.  In the **File name** field, specify a name and path for the ASCII file.

10. Click **OK** to generate Report 349.

  


