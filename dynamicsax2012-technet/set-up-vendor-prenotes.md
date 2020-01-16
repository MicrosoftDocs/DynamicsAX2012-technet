---
title: Set up vendor prenotes
TOCTitle: Set up vendor prenotes
ms:assetid: 9c44938c-4b6c-4e2c-b782-70fdd26c2728
ms:mtpsurl: https://technet.microsoft.com/library/Hh209432(v=AX.60)
ms:contentKeyID: 36058726
author: Khairunj
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
- electronic payment
audience: Application User
ms.search.region: Global
---

# Set up vendor prenotes 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A prenote is a zero-dollar transaction that is sent to a bank through the Automated Clearing House (ACH) network. Banks use prenotes to verify the accuracy of account data, such as routing numbers and account numbers.

## Before you create prenotes

Before you can create prenotes for your organization’s bank, you must follow these steps:

  - Define the prenote number sequence. For more information, see [Cash and bank management parameters (form)](https://technet.microsoft.com/library/aa591289\(v=ax.60\)).

  - Set up an organizational bank to require prenotes. For more information, see the following procedure.

## Set up an organizational bank to require prenotes

1.  Click **Cash and bank management** \> **Common** \> **Bank accounts**.

2.  Select the organizational bank account to require prenotes for, and then click the **Edit** button on the **Action Pane**.

3.  On the **General** FastTab, select the **Prenote required** check box.

4.  In the **Prenote response days** field, enter the number of days before prenotes are approved, as specified by your organization’s bank.


> [!NOTE]
> <P>If you update this value, the new value affects only new prenotes. Prenotes that have been approved by your organization’s bank do not have to be approved again.</P>



## Create prenotes for vendor accounts

Follow these steps to create a vendor account prenote for your organization’s bank.

1.  Click **Accounts payable** \> **Periodic** \> **Create prenotes**.

2.  In the **Bank name** field, select the name of your organization’s bank.

3.  In the **File name** field, select where the new prenote file will be saved, and then type a file name. For example, if you select to save the prenote in C:\\Prenotes, and you enter a file name of BankA, this field would display C:\\Prenotes\\BankA.

4.  Select the file export type: **CCD**, **CTX**, or **PPD**. Check with your organization’s bank if you do not know which file type to select; some banks prefer a specific file type.

5.  Select the **Run on AOS** check box to run the prenote creation process on the Application Object Server (AOS) instead of on your computer. This option typically improves performance.

6.  In the **Account type** field, select the type of account to create a prenote for. You can create prenotes for all vendors or for a specific vendor.

7.  To create a prenote for a specific vendor, select the vendor account in the **Account** field.

## View the approval status of a vendor prenote

1.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.

2.  Double-click a vendor account, and then click the **Bank accounts** button on the **Action Pane**.

3.  On the **Setup** tab, you can view the status of the prenote in the **Prenotes** section. A prenote has a **Pending** status until your organization’s bank approves it.


> [!NOTE]
> <P>If the vendor bank account is changed after a prenote was created for it, the prenote status will no longer appear in the <STRONG>Prenotes</STRONG> section. You must create a new prenote for the new vendor bank account.</P>



## See also

[Set up prenotes](set-up-prenotes.md)

[Set up customer prenotes](set-up-customer-prenotes.md)

[Create prenotes (form)](https://technet.microsoft.com/library/hh209352\(v=ax.60\))

  


