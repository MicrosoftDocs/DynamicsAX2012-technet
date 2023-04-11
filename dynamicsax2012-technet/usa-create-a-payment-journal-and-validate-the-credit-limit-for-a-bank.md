---
title: (USA) Create a payment journal and validate the credit limit for a bank
TOCTitle: (USA) Create a payment journal and validate the credit limit for a bank
ms:assetid: 40f77da9-f173-40c1-a9b5-76da05d71541
ms:mtpsurl: https://technet.microsoft.com/library/Hh242260(v=AX.60)
ms:contentKeyID: 36056726
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- USA
- credit limit
- payment journal
audience: Application User
ms.search.region: USA
---

# (USA) Create a payment journal and validate the credit limit for a bank 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you can make a payment to a vendor or customer, you must enter all necessary company, vendor, or customer bank account details. When you set up company, vendor, or customer bank accounts, you must enter a valid bank account number and routing number.

The bank account number must contain 7 to 14 digits. The length of the routing number is based on the routing type selected, as shown below:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Routing type</p></th>
<th><p>Length</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>FW</strong> (Fed Wire transfers)</p></td>
<td><p>Nine digits</p></td>
</tr>
<tr class="even">
<td><p><strong>CP</strong> (Chip Participant code)</p></td>
<td><p>Six digits</p></td>
</tr>
<tr class="odd">
<td><p><strong>CH</strong> (Chip Universal identifier)</p></td>
<td><p>Four digits</p></td>
</tr>
</tbody>
</table>


Based on the cash credit or overdraft limit that the company has with the bank, you can set the credit limit in the **Bank accounts** form. You can also select the notifications to be displayed when you make a payment that exceeds the credit limit in the **Bank parameters** form.

## Set up bank parameters

You can select the notification to be displayed when the payment transaction exceeds the cash credit or overdraft limit.

1.  Click **Cash and bank management** \> **Setup** \> **Cash and bank management parameters**.

2.  In the **Bank credit limit tolerance** field, select form the following options the notification to be displayed when the credit limit is reached:
    
      - **None** – If you have exceeded the credit limit, a notification is not displayed.
    
      - **Warning** – If you have exceeded the credit limit, a warning message is displayed when you post the payment journal.
    
      - **Error** – If you have exceeded the credit limit, an error message is displayed and you cannot post the journal.

3.  Close the form to save your changes.

## Set up a bank account credit limit

Use the **Bank accounts** form to enter a valid bank account number, routing type, and routing number, and enter your cash credit or overdraft limit for payment transactions.

1.  Click **Cash and bank management** \> **Common** \> **Bank accounts**.

2.  Click **Bank account** to open the **Bank accounts** form.

3.  In the **Bank account** field, enter the unique bank account number. Enter the name of the bank in the **Name** field.

4.  In the **Routing number type** field, select the routing number type as **FW**, **CP**, or **CH**.

5.  In the **Routing number** field, enter the routing number for the bank. The routing number is validated based on the routing type selected.

6.  In the **Bank account number** field, enter a bank account number that contains 7 to 14 digits.

7.  In the **Credit limit** field, enter the credit limit. This is a negative number.

8.  Close the form to save your changes.

## Set up a bank account for a vendor or customer

Enter a valid bank account number, routing type, routing number, and other bank details for a vendor or customer account.

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.
    
    –or–
    
    Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.

2.  Select a vendor or customer account, on the Action Pane, in the **Setup** group, click **Bank accounts**.

3.  In the **Bank account** and **Name** fields, enter the unique ID that you use to identify the vendor or customer bank account and name of the bank.

4.  In the **Routing number type** field, select the routing number type as **FW**, **CP**, or **CH**.

5.  In the **Routing number** field, enter the routing number for the bank. The routing number is validated based on the routing type selected.

6.  In the **Bank account number** enter a vendor or customer bank account number that contains 7 to 14 digits.

7.  Close the form to save your changes.

## Post a payment journal for a bank account

You can create a payment journal to record a fixed asset purchase, service purchase, expense transaction, vendor payment, or customer payment. The payment journal is posted only after the payment transaction is validated against the credit limit specified by the bank.

1.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.
    
    –or–
    
    Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Press CTRL+N to create a new journal.

3.  In the **Name** field, select the journal name and click **Lines** to open the **Journal voucher** form.

4.  In the **Date** field, select the transaction date.

5.  In the **Account** field, select the general ledger, vendor, or customer account number.

6.  In the **Debit** field, enter the amount to be paid.

7.  In the **Offset account type** field, select **Bank**.

8.  In the **Offset account** field, select the bank account number.

9.  Click **Post** \> **Post** to post the journal. If you have exceeded your credit limit, a message is displayed. If you specified the **Bank credit limit tolerance** field as **Warning** in the **Bank parameters** form, the journal is posted. If the **Bank credit limit tolerance** type field is specified as **Error**, the journal is not posted.

10. Close the form to save your changes.

## See also

[Legal entities (form)](https://technet.microsoft.com/library/hh242860\(v=ax.60\))

[Customer bank accounts (form)](https://technet.microsoft.com/library/aa575695\(v=ax.60\))

[Vendor bank accounts (form)](https://technet.microsoft.com/library/aa589805\(v=ax.60\))

  


