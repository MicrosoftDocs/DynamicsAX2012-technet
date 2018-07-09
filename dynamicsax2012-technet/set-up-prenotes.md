---
title: Set up prenotes
TOCTitle: Set up prenotes
ms:assetid: b9aed6b5-7360-4750-89f7-4141327775ed
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242764(v=AX.60)
ms:contentKeyID: 36059120
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- vendor
- customer
- payment
- bank
- prenote
- account number
- automated clearing hourse
- electronic
---

# Set up prenotes [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A prenote is a zero-dollar transaction that is sent to a bank through the Automated Clearing House (ACH) network. Banks use prenotes to verify the accuracy of account data, such as routing numbers and account numbers.

## Before you create prenotes

Before you can create prenotes for your organization’s bank, you must follow these steps:

  - Define the prenote number sequence. For more information, see [Cash and bank management parameters (form)](https://technet.microsoft.com/en-us/library/aa591289\(v=ax.60\)).

  - Set up an organizational bank to require prenotes. For more information, see the following procedure.

## Set up an organizational bank to require prenotes

1.  Click **Cash and bank management** \> **Common** \> **Bank accounts**.

2.  Select the organizational bank account to require prenotes for, and then click the **Edit** button on the **Action Pane**.

3.  On the **General** FastTab, select the **Prenote required** check box.

4.  In the **Prenote response days** field, enter the number of days before prenotes are approved, as specified by your organization’s bank.


> [!NOTE]
> <P>If you update this value, the new value affects only new prenotes. Prenotes that have been approved by your organization’s bank do not have to be approved again.</P>



## Create prenotes for customer or vendor accounts

Follow these steps to create a customer or vendor account prenote for your organization’s bank.

1.  Click **Cash and bank management** \> **Periodic** \> **Create prenotes**.

2.  In the **Bank name** field, select the name of your organization’s bank.

3.  In the **File name** field, select where the new prenote file will be saved, and then type a file name. For example, if you select to save the prenote in C:\\Prenotes, and you enter a file name of BankA, this field would display C:\\Prenotes\\BankA.

4.  Select the file export type: **CCD**, **CTX**, or **PPD**. Check with your organization’s bank if you do not know which file type to select; some banks prefer a specific file type.

5.  Select the **Run on AOS** check box to run the prenote creation process on the Application Object Server (AOS) instead of on your computer. This option typically improves performance.

6.  In the **Account type** field, select the type of account to create a prenote for. You can create a prenote for a specific customer or vendor, or you can create prenotes for all customers, all vendors, or all customers and vendors.

7.  To create a prenote for a specific customer or vendor, select the customer or vendor account in the **Account** field.

## View the approval status of a customer bank prenote

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  Select a customer account, and then click the **Bank accounts** button on the **Action Pane**.

3.  On the **Setup** tab, you can view the status of the prenote in the **Prenotes** section. A prenote has a **Pending** status until your organization’s bank approves it.


> [!NOTE]
> <P>If the customer bank account is changed after a prenote was created for it, the prenote status will no longer appear in the <STRONG>Prenotes</STRONG> section. You must create a new prenote for the new customer bank account.</P>



## View the approval status of a vendor prenote

1.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.

2.  Select a vendor account, and then click the **Bank accounts** button on the **Action Pane**.

3.  On the **Setup** tab, you can view the status of the prenote in the **Prenotes** section. A prenote has a **Pending** status until your organization’s bank approves it.


> [!NOTE]
> <P>If the vendor bank account is changed after a prenote was created for it, the prenote status will no longer appear in the <STRONG>Prenotes</STRONG> section. You must create a new prenote for the new vendor bank account.</P>



## See also

[Set up customer prenotes](set-up-customer-prenotes.md)

[Set up vendor prenotes](set-up-vendor-prenotes.md)

[Create prenotes (form)](https://technet.microsoft.com/en-us/library/hh209352\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

