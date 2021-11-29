---
title: (IND) Update transit document details for posted sales tax transactions
TOCTitle: (IND) Update transit document details for posted sales tax transactions
ms:assetid: 5518333f-9ced-4894-9575-0c7bcbac3650
ms:mtpsurl: https://technet.microsoft.com/library/JJ677822(v=AX.60)
ms:contentKeyID: 49385783
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Update transit document details for posted sales tax transactions 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



Goods are often moved from one area to another during trade. The transit document consists of transaction details, such as the voucher number, the date, the transaction amount, the tax amount, form series, and the form number. You must update the transaction details of the goods in transit before you can settle taxes for a specific period.

1.  Click **General ledger** \> **Periodic** \> **India** \> **Transit document details**.

2.  Select one of the following account types to update the transit document details for in the **Account type** field:
    
      - **Customer** – Update transit document details for the customer.
    
      - **Vendor** – Update transit document details for the vendor.

3.  Select the account number of the customer or the vendor for the account type in the **Account** field.

4.  Select the transaction form that is used to post the sales tax transactions in the **Source** field from the following options:
    
      - **All** – The sales tax transactions that are posted in all transaction forms are displayed.
    
      - **Purchase order** – The sales tax transactions that are posted in a purchase order are displayed.
    
      - **Sales order** – The sales tax transactions that are posted in a sales order are displayed.
    
      - **Journal** – The sales tax transactions that are posted in all journals are displayed.

5.  Select the date of transaction in the **Date** field.

6.  Click **Show data** to display the sales tax transactions for the specified account type and the account number in the lower pane. View the information for the posted sales tax transactions in the following fields:
    
      - **Voucher** – The voucher number of the transaction.
    
      - **Date** – The date the transaction was posted on.
    
      - **Source** – The module the transaction is attached to.
    
      - **Form type** – The type of sales tax form the transaction is attached to.
    
      - **Transaction amount** – The net amount in the purchase or sales transaction, or journal.
    
      - **Tax amount** – The sales tax amount that is calculated for the transaction.

7.  Enter the company transit document series in the **Form series** field and the company transit document number in the **Form number** field under the **Company transit document** field group.

8.  Enter the vendor or customer transit document series in the **Form series** field, and the vendor or customer transit document number in the **Form number** field.

9.  Select the **Mark** check box for the transactions to update the transit document details for.

10. Click **Update** to update the selected transactions with transit document details.

11. View the transactions that the transit document details are updated for in the sales tax inquiry.

## See also

[(IND) Transit document details (form)](https://technet.microsoft.com/library/jj664773\(v=ax.60\))

  


