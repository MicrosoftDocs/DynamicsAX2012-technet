---
title: Prevent collection letters for invoices that are sent to a collection agency
TOCTitle: Prevent collection letters for invoices that are sent to a collection agency
ms:assetid: 1f00234d-bc33-469a-a744-f4c4eb089d00
ms:mtpsurl: https://technet.microsoft.com/library/Hh292595(v=AX.60)
ms:contentKeyID: 36655925
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Prevent collection letters for invoices that are sent to a collection agency 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To avoid sending more collection letters to a customer whose invoice has been sent to a collection agency, you can manually change the next collection letter in the sequence for a specific invoice. Reasons for changing the next collection letter in the sequence might include the following:

  - Change from **Collection letter 1** to **Collection letter 4**. You might do this if you decide to send this invoice to a collection agency sooner than the regular processing routine. For example, if communication with a customer has proven ineffective, you might decide to send the invoice to a collection agency right away.
    
    The invoice will then be included on the list of invoices that should be sent to a collection agency the next time that you use the **Creation of collection letter** form to create collection letters. That process will change the value in the **Valid collection letter code** field in the **Customer transactions** form from **Collection letter 4** to **Collection**.

  - Change from **Collection letter 1** to **Collection**. You might do this if you have already sent this invoice to the collection agency.

  - Change from **Collection letter 3** to **Collection letter 1**. You might do this if this customer said they will send payment this week.

The **Collection letter** field in the **Customer transactions** form displays the number of the most recent collection letter. The **Collection letter code** value is automatically set on the invoice after you process collection letters by using the **Creation of collection letter** form. (Click **Accounts receivable** \> **Periodic** \> **Collections** \> **New collection letters**.) The **Date** field indicates the date that the last collection letter was run.

## Change the status of a collection letter

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**. Select the customer account to update.
    
    –or–
    
    Click **Accounts receivable** \> **Common** \> **Collections** \> **Collections**. Double-click the customer account to update.

2.  On the **Action Pane**, on the **Customer** tab, click **Transactions** to open the **Customer transactions** form.
    
    –or–
    
    On the **Action Pane**, on the **Collect** tab, click **Settle open transactions** to open the **Settle open transactions** form.

3.  Select the invoice to change, and then click the **Collections** tab.
    
    The **Collection letter** field displays the number of the most recent collection letter that has been sent to the customer for the selected invoice. The **Collection letter code** field displays the last code that was used. The **Date** field indicates the date that the last collection letter was generated.

4.  Select the valid collection letter code for the collection letter that you want to use the next time that a collection letter is generated for the selected invoice, and then close the form.

You can use the **Collection letter journal** form to view or print a list of all of the collection letters for all customers or for a particular customer. (Click **Accounts receivable** \> **Inquiries** \> **Collections** \> **Collection letter journal**.)

The **Collection letter journal** form shows a list of customer accounts that have received any of the collection letters that are designated in the **Collection letter** form, including **Collection**. You can sort by collection letter code to see which letters are at the end of the collection letter sequence and which accounts are planned to be turned over to a collection agency.

## See also

[Control posting and printing of collection letters](control-posting-and-printing-of-collection-letters.md)

[Create collection letters](create-collection-letters.md)

[Set up a collection letter sequence](set-up-a-collection-letter-sequence.md)

[Valid collection letter code](https://technet.microsoft.com/library/aa598830\(v=ax.60\))

  


