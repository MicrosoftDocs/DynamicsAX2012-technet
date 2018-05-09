---
title: (RUS) Create an outgoing or incoming payment
TOCTitle: (RUS) Create an outgoing or incoming payment
ms:assetid: 63c340e6-60f9-4a63-bc27-0771c275cc35
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ665451(v=AX.60)
ms:contentKeyID: 49387537
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- incoming
- outgoing
---

# (RUS) Create an outgoing or incoming payment 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use electronic exchange file formats to export payments to a client bank, and to import payments and bank account statements from a client bank. Payments include outgoing and incoming payments between Microsoft Dynamics AX and a client bank. When the data exchange files are received from a client bank, you can export outgoing payments to the client bank or import incoming payments to Microsoft Dynamics AX. Use the **Journal voucher** form to create an outgoing or incoming payment. For more information, see [Journal voucher - Vendor payment journal (form)](https://technet.microsoft.com/en-us/library/aa599011\(v=ax.60\)) and [Journal voucher - Customer payment journal (form)](https://technet.microsoft.com/en-us/library/aa556141\(v=ax.60\)).

1.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.
    
    –or–
    
     Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Create a new journal, and then click **Lines**. For more information, see, [(RUS) Generate a payment order in rubles](rus-generate-a-payment-order-in-rubles.md)

3.  In the **Method of payment** field, select a method of payment.
    

    > [!NOTE]
    > <P>You must select a method of payment for which the <STRONG>Customizable format</STRONG> check box is selected on the <STRONG>File formats</STRONG> tab. The <STRONG>Payment specification</STRONG>, <STRONG>Offset account type</STRONG>, <STRONG>Offset account</STRONG>, <STRONG>Bank transaction type</STRONG>, <STRONG>The code of document kind</STRONG>, and <STRONG>Document type</STRONG> fields are updated in the payment journal.</P>



4.  Click the **Payment** tab, and then, in the **Currency conversion** field group, select one of the following options:
    
      - **Transit account** – The bank account for the purchase or sale of currency.
    
      - **Commission from account** – The account that is used to write off the commission.
    
      - **Currency** – The purchase currency code of the bank.
    
      - **Representative** – The employee number of the person who created the currency purchase order.
    
      - **Bank exchange rate** – The exchange rate for the purchase or sale of currency.

## See also

[(RUS) Journal voucher - Vendor payment journal (modified form)](https://technet.microsoft.com/en-us/library/jj733511\(v=ax.60\))

[(RUS) Export a payment or cancel a payment exported to a client bank](rus-export-a-payment-or-cancel-a-payment-exported-to-a-client-bank.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

