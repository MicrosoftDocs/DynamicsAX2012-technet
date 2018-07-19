---
title: (NOR) Set up the types of payment mode change for eInvoices
TOCTitle: (NOR) Set up the types of payment mode change for eInvoices
ms:assetid: e7f31ffc-d255-41e0-96c9-f26d2f5ee75c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg243234(v=AX.60)
ms:contentKeyID: 36059825
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Norway
---

# (NOR) Set up the types of payment mode change for eInvoices 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

1.  Click **Accounts receivable** \> **Setup** \> **e-Invoice** \> **Payment mode change**.

2.  Press CTRL+N to create a new payment mode.

3.  In the **Type** and **Name** fields, enter an identification code and a descriptive name for the type of payment mode change.

4.  Click the **Methods of payment** FastTab. In the **Status** field, select the payment mode status for the customer from the following options:
    
      - **Blank** – No change is required for the payment method.
    
      - **Pending** – The enrollment file for eInvoice service is received from the customer and imported, but the customer validation has not been made.
    
      - **Active** – The confirmation file is imported from the Bankenes Betalingssentral (BBS) after the eInvoice service is approved for the customer. You can change the payment method for eInvoice when the status is active.
    
      - **Deleted** – The notification message has been received and imported to cancel the eInvoice service for the customer.
    
      - **Rejected** – The eInvoice service is rejected for the customer.

5.  In the **From payment mode** field, select the current payment method for the customer.

6.  In the **From payment specification** field, select the current payment specification for the customer.

7.  In the **To payment mode** field, select the customer payment method that is specified in the enrollment file or the modification message.

8.  In the **To payment specification** field, select the payment specification that is specified in the enrollment file or the modification message.

9.  Close the form to save your changes.

## See also

[(NOR) Payment mode change (form)](https://technet.microsoft.com/en-us/library/hh209700\(v=ax.60\))

  


