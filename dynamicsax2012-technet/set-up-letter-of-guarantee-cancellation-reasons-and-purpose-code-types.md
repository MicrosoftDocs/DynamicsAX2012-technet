---
title: Set up letter of guarantee cancellation reasons and purpose code types
TOCTitle: Set up letter of guarantee cancellation reasons and purpose code types
ms:assetid: 9ce4ecf5-be59-4615-8c21-d4e17144ee41
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh209439(v=AX.60)
ms:contentKeyID: 36058740
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Lletter of guarantee cancellation reasons and purpose code types
- Set up letter of guarantee cancellation reasons and purpose code types
audience: Application User
ms.search.region: Global
---

# Set up letter of guarantee cancellation reasons and purpose code types 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can set up a payment purpose or reason code to specify the objective of a letter of guarantee transaction or agreement.

## Set up a payment purpose code for a letter of guarantee transaction

1.  Click **Cash and bank management** \> **Setup** \> **Payment purpose codes**.

2.  Press CTRL+N to create a new payment purpose code.

3.  On the right pane, in the **Central bank purpose code** field, enter the code used to report to the central bank.

4.  In the **Name** field, enter the name of the payment purpose code.

5.  Click the **General** FastTab and in the **Purpose text** field, enter a justification or reason for the specified purpose code. This reason text appears in the report to the central bank.

6.  In the **Text** field, enter any additional information needed.

7.  Close the form to save your changes.

## Activate the cancellation reason and purpose type for a letter of guarantee transaction

1.  Click **Cash and bank management** \> **Setup** \> **Bank reasons**.

2.  Press CTRL+N to create a new bank reason.
    

    > [!NOTE]
    > <P>Reason codes help to explain why some types of transactions or field values were entered or changed. For example, you can create reason codes to use when you create or cancel a letter of guarantee.</P>



3.  In the **Reason code** field, enter the code to indicate a reason for the letter of guarantee transaction.

4.  In the **Default comment** field, enter a description for the reason code.

5.  Select the **Bank** check box to indicate that the reason code can be used for transactions that have a bank transaction type.

6.  Select the **Purpose code** check box to indicate that the reason code can be used as the letter of guarantee purpose code if required.

7.  Select the **Cancellation reason** check box to indicate that the reason code can be used to indicate the reason for cancelation of the letter of guarantee.

8.  Close the form to save your changes.

## See also

[Reasons (form)](https://technet.microsoft.com/en-us/library/hh209362\(v=ax.60\))

[Payment purpose codes (form)](https://technet.microsoft.com/en-us/library/aa587506\(v=ax.60\))

[Letter of guarantee (form)](https://technet.microsoft.com/en-us/library/hh227662\(v=ax.60\))

[Set up posting profiles for the letter of guarantee](set-up-posting-profiles-for-the-letter-of-guarantee.md)

[Request and issue the letter of guarantee](request-and-issue-the-letter-of-guarantee.md)

  


