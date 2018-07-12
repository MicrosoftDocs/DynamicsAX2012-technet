---
title: (EST) Set up a customer reference number
TOCTitle: (EST) Set up a customer reference number
ms:assetid: 776d0c0c-e6ea-4a24-bef8-d571bfbbe2c7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ713649(v=AX.60)
ms:contentKeyID: 49643143
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Estonia
---

# (EST) Set up a customer reference number 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Before you set up reference numbers to link imported telebank payments to customers, you must assign a number sequence to the payment reference in the **Accounts receivable parameters** form. The reference numbers can be generated automatically, based on the number sequence.

Then, you can enter a reference number for payments in the **Customers** form. You can also use the **Create payment reference numbers** form to assign reference numbers to customers who do not have reference numbers.

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  Select a customer account. Or, on the **Action Pane**, on the **Customer** tab, in the **New** group, click **Customer** to create a customer account.

3.  On the **Payment defaults** FastTab, in the **Payment reference** field, enter the reference number for payments.
    

    > [!TIP]
    > <P>You can also use the <STRONG>Create payment reference numbers</STRONG> form to assign reference numbers to customers who do not have reference numbers. Click <STRONG>Accounts receivable</STRONG> &gt; <STRONG>Periodic</STRONG> &gt; <STRONG>Create payment reference numbers</STRONG>.</P>



4.  Press CTRL+S or close the form.
    
    The reference numbers are generated automatically, based on the number sequence that is defined in the **Accounts receivable parameters** form.

## See also

[(EST) Set up the import of telebank payments from customers](est-set-up-the-import-of-telebank-payments-from-customers.md)

  


