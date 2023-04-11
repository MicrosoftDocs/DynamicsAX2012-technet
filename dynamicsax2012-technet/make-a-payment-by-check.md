---
title: Make a payment by check
TOCTitle: Make a payment by check
ms:assetid: 31baab1e-a686-4627-8714-21be0cc2016c
ms:mtpsurl: https://technet.microsoft.com/library/Aa570052(v=AX.60)
ms:contentKeyID: 36056344
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Make a payment by check 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To make a payment by check, you must first set up the layout of checks in the **Check layout** form.

1.  Click **Cash and bank management** \> **Common** \> **Bank accounts**.

2.  To set up the layout of checks for the selected bank account (if this needs to be done), click the **Setup** tab \>**Check layout**. See [Check layout (form)](https://technet.microsoft.com/library/aa576973\(v=ax.60\)) for information about the fields in the **Check layout** form.

3.  If you select **Fixed** in the **Check number method** field, you must create a series of pre-printed checks that you can use to make payments:
    
    1.  Click **Cash and bank management** \> **Common** \> **Bank accounts**.
    
    2.  Click **Functions** \> **Create checks**.
    
    3.  Enter the first check number in the check series and the number of checks to create, and click **OK**.

4.  Set up a method of payment for paying by check. This method of payment must have an export format. In the following steps, this method of payment is called Check. For more information, see [Set up a method of payment for checks](set-up-a-method-of-payment-for-checks.md).

5.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

6.  In the payment journal, press CTRL + N to create a payment line, and enter information about the date, account, and amount. For more information about payments to vendors, see [Key tasks: Vendor payments and settlements](key-tasks-vendor-payments-and-settlements.md).
    
    Alternatively, you can click **Payment proposal** \> **Create payment proposal** to generate payment lines for invoices that are not settled.

7.  On the payment line, in the **Offset account type** field, select **Bank**, and then select the correct bank account in the **Offset account** field.

8.  On the **Payment** tab, in the **Method of payment** field, select **Check**.

9.  Click **Functions**, and select **Generate payments**.

10. In the **Method of payment** field, select the correct method of payment for checks from the bank account. In this case, the method of payment is **Check**.

11. Click **Dialog**. In the **Payment by check** form, enter the first check number and the number of blank checks that you want to print.

12. Click **OK** to print the check, and then close the **Payment by check** form. Click **OK** in the **Generate payments** form to post the payment.

## See also

[Print copies of payments as non-negotiable checks](print-copies-of-payments-as-non-negotiable-checks.md)

  


