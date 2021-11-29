---
title: (LVA) Print a statement of foreign payments received in domestic banks
TOCTitle: (LVA) Print a statement of foreign payments received in domestic banks
ms:assetid: fc22a7dc-bc8b-4420-96b3-9f8e6775da88
ms:mtpsurl: https://technet.microsoft.com/library/JJ911244(v=AX.60)
ms:contentKeyID: 52075327
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Latvia
---

# (LVA) Print a statement of foreign payments received in domestic banks 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



If your company receives payments from a foreign bank and deposits the payments into a domestic bank, the company must prepare a monthly report on those incoming payments that exceeded the limit established by the Central Latvian Bank. You can use the **Foreign payments received by domestic banks** report to print a report for this purpose.


> [!NOTE]
> <P>To print this monthly statement, you must create and post all bank transactions in the <STRONG>Payment journal</STRONG> form in Accounts payable, the <STRONG>Payment journal</STRONG> form in Accounts receivable, and the <STRONG>General journal</STRONG> form. For more information, see <A href="lva-create-and-post-a-journal-for-foreign-receipts-and-payments.md">(LVA) Create and post a journal for foreign receipts and payments</A>.</P>



1.  Click **Cash and bank management** \> **Common** \> **Bank accounts**. Select a bank account, and then, on the **Action Pane**, on the **Bank account** tab, in the **Transactions** group, click **Transactions**.

2.  In the **Bank transactions** form, select a transaction, and then, on the **Notification to the central bank** tab, view or modify the information in the following fields:
    
      - **Purpose text** – The purpose for which this code is used in the report.
    
      - **Central bank purpose code** – The code used when reporting to the central bank.
    
      - **Correspondent country/region** – The country code used when reporting to the central bank.
    
      - **Payment registration number** – The payment registration number assigned by the bank.

3.  Click **Cash and bank management** \> **Inquiries** \> **Bank transactions**.

4.  In the **Inquiry** form, select the correspondent country and add or modify the amount criterion for bank transactions specified by Latvian Central Bank.

5.  Click **OK** to open the **Bank transactions** form to view the details on notification to the central bank, and modify them if needed.

6.  Click **Cash and bank management** \> **Reports** \> **Transactions** \> **Foreign payments received by domestic banks**.

7.  In the **Person responsible for payments** field, select or modify the code of the employee who is responsible for submitting the report.

8.  In the **Month** field, select or modify the month to submit the report.

9.  In the **Year** field, select or modify the year of submission of the report.
    

    > [!NOTE]
    > <P>Click <STRONG>Select</STRONG> to open the <STRONG>Inquiry</STRONG> form and modify the values in the <STRONG>Bank transactions</STRONG> and <STRONG>Addresses</STRONG> field groups. You can also reset the amount criterion.</P>



10. Click **OK** to print the statement.

## See also

[(LVA) Create and post a journal for foreign receipts and payments](lva-create-and-post-a-journal-for-foreign-receipts-and-payments.md)

[(LVA) Journal voucher - General journal (modified form)](https://technet.microsoft.com/library/jj853411\(v=ax.60\))

[(LVA) Journal voucher - Customer payment journal (modified form)](https://technet.microsoft.com/library/jj720370\(v=ax.60\))

[(LVA) Vendor payment journal lines (modified form)](https://technet.microsoft.com/library/jj721419\(v=ax.60\))

[(LVA) Bank transactions (modified form)](https://technet.microsoft.com/library/jj839644\(v=ax.60\))

  


