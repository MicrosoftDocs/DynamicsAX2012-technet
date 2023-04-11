---
title: Print copies of payments as non-negotiable checks
TOCTitle: Print copies of payments as non-negotiable checks
ms:assetid: ccbbe602-5859-421d-98b4-0552cd6ec26d
ms:mtpsurl: https://technet.microsoft.com/library/Hh242904(v=AX.60)
ms:contentKeyID: 36059454
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- public sector
- payment
- payment journal
- check layout
- non-negotiable check
audience: Application User
ms.search.region: Global
---

# Print copies of payments as non-negotiable checks 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

After a payment has been generated and posted to the payment journal, you can print a copy of the payment as a non-negotiable check. A non-negotiable check is a document that cannot be bought, sold, exchanged, or transferred.

Before you can print copies of payments, you must follow these steps:

  - Set up a bank to print copies of payments. For more information, see [Cash and bank management parameters (form)](https://technet.microsoft.com/library/aa591289\(v=ax.60\)).

  - Set up a vendor method of payment to print copies of payments. For more information, see [Methods of payment - vendors (form)](https://technet.microsoft.com/library/aa618565\(v=ax.60\)).

### Set up the non-negotiable check layout for a bank account

1.  Click **Cash and bank management** \> **Common** \> **Bank accounts**.

2.  Select the bank account to set up the check layout for. In the **Action Pane**, select the **Setup** tab, and then click the **Check** button. The **Check layout** form opens.

3.  On the **Copies** tab, select an option for a signature and a watermark.

4.  Click **Print test**. The **Check layout - print test** form opens.

5.  Select **Non-negotiable check format** as the check type to print, and then click **OK**. The check layout is displayed.

### Print a copy of a payment from the Check form

1.  Click **Cash and bank management** \> **Common** \> **Checks**.

2.  Select a check or checks that have a status of **Paid**.

3.  Click **Print check copy**.

### Print a copy of a payment from the Payment history form

1.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**. On the **Action Pane**, select the **Invoice** tab, and then click the **Payment history** button.
    
    –or–
    
    Click **Procurement and sourcing** \> **Common** \> **Vendors** \> **All vendors**. On the **Action Pane**, select the **Invoice** tab, and then click the **Payment history** button.

2.  Select a payment or payments, and then click **Print payment copy**.
    

    > [!NOTE]
    > <P>You can print a copy of a payment only if its method of payment allows for payment copies and the offset account type is <STRONG>Bank</STRONG>. For more information, see <A href="https://technet.microsoft.com/library/aa618565(v=ax.60)">Methods of payment - vendors (form)</A> and <A href="https://technet.microsoft.com/library/aa599011(v=ax.60)">Journal voucher - Vendor payment journal (form)</A>.</P>



### Print a copy of a payment from a promissory note journal

1.  Click **Accounts payable** \> **Journals** \> **Promissory notes** \> **Draw promissory note journal**.
    
    –or–
    
    Click **Accounts payable** \> **Journals** \> **Promissory notes** \> **Redraw promissory note journal**.

2.  Select a journal or press CTRL+N to create a new line, and then click **Lines**. The **Journal voucher** form opens.

3.  Select a payment or payments, and then click **Print** \> **Payment copy**.
    

    > [!NOTE]
    > <P>You can print a copy of a payment only if its method of payment allows for payment copies and the offset account type is <STRONG>Bank</STRONG>. For more information, see <A href="https://technet.microsoft.com/library/aa618565(v=ax.60)">Methods of payment - vendors (form)</A> and <A href="https://technet.microsoft.com/library/aa599011(v=ax.60)">Journal voucher - Vendor payment journal (form)</A>.</P>



## See also

[Set up the check layout for a bank account](set-up-the-check-layout-for-a-bank-account.md)

  


