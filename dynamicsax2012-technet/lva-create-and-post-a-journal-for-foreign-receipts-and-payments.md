---
title: (LVA) Create and post a journal for foreign receipts and payments
TOCTitle: (LVA) Create and post a journal for foreign receipts and payments
ms:assetid: 45a0ceef-7c43-4219-a1eb-859aa5f642e1
ms:mtpsurl: https://technet.microsoft.com/library/JJ853408(v=AX.60)
ms:contentKeyID: 50396779
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Latvia
- notification to the central bank
audience: Application User
ms.search.region: Latvia
---

# (LVA) Create and post a journal for foreign receipts and payments 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

If your company receives payments from a foreign bank and deposits them into a domestic bank, you must report any incoming payments that exceed a certain amount to the Latvian Central Bank. You must also declare all foreign payments that are issued or received by your foreign bank accounts, if the payments exceed a certain amount.

Use this procedure to record the foreign receipts and payments in journal entries in **Accounts receivable**, **Accounts payable**, and **General ledger**. The **Journal voucher** forms contain fields for recording the information that is required to generate the **Foreign payments received by domestic banks** and **Foreign payments made through foreign banks** reports.

1.  Click **General ledger** \> **Journals** \> **General journal**.
    
    –or–
    
    Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.
    
    –or–
    
    Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Click **New** to create a journal, and then enter the required details.

3.  Click **Lines**.

4.  In the **Journal voucher** form, on the **Overview** tab, in the **Offset account type** field, select **Bank**.

5.  Enter any additional information that is needed to complete the journal line.

6.  On the **Payment** tab, in the **Notification to the central bank** field group, enter values for the fields in the following list.
    

    > [!NOTE]
    > <P>This field group appears on the tab only if you select <STRONG>Bank</STRONG> in either the <STRONG>Account type</STRONG> field or the <STRONG>Offset account type</STRONG> field in the <STRONG>Journal voucher</STRONG> form in <STRONG>General ledger</STRONG>.</P>

    
      - **Central bank purpose code** – Select the purpose code for the foreign payment or receipt. The code is printed on the report to the central bank. By default, this value is the code that is assigned to the customer or vendor, but you can change it.
    
      - **Purpose text** – Enter a brief description of the purpose of the payment or receipt. The text is printed on the report to the central bank. By default, this field displays the text that was entered for the customer or vendor, but you can change it.
    
      - **Import date** – Select the date on which payments or receipts to be included on the report were imported from an external system into Microsoft Dynamics AX.
    
      - **Payment registration number** – Enter the payment registration number that the bank assigned to the transaction on the bank statement.

7.  Enter any additional information in the journal, and then click **Post** \> **Post** to post the journal.

When the journal is posted, the correspondent country is determined by how the bank account for the customer or vendor and your company bank account are configured.

  - If the customer or vendor record includes a payment bank account, the posting process uses the country/region code of the bank address.

  - If the customer or vendor record does not include a payment bank account, the posting process uses the country/region code of the primary address for the customer or vendor.

  - If the transaction is a bank transfer, the posting process uses the country/region code of the address for the other bank.

If the source information for the fields that you use in the preceding procedure is not available at the time of posting or was entered incorrectly, you can enter or correct the information on the **Notification to the central bank** tab in the **Bank transactions** form.

**Optional: Turn on database logging**

To capture information about the person who changed any values in posted transactions, and view the current and former values, you can turn on database logging.

1.  Click **System administration** \> **Setup** \> **Database** \> **Database log setup**.

2.  Click **New**, and then, in the **Logging database changes** wizard, click **Next \>**.

3.  Click **Show all tables**, and then expand **Bank** \> **Bank transactions**.

4.  Select the following check boxes:
    
      - **BankPaymentRegistrationNum\_LV**
    
      - **CentralBankPurposeCode\_LV**
    
      - **CentralBankPurposeText\_LV**
    
      - **CorrespondentCountry\_LV**

5.  Click **Next \>**, and then, in the **Types of change** form, select the **Update** check box for each line.

6.  Click **Next \>**, and then click **Finish**.

## See also

[(LVA) Print a statement of foreign payments received in domestic banks](lva-print-a-statement-of-foreign-payments-received-in-domestic-banks.md)

[(LVA) Print a statement of foreign receipts and payments via foreign banks](lva-print-a-statement-of-foreign-receipts-and-payments-via-foreign-banks.md)

[(LVA) Journal voucher - General journal (modified form)](https://technet.microsoft.com/library/jj853411\(v=ax.60\))

[(LVA) Journal voucher - Customer payment journal (modified form)](https://technet.microsoft.com/library/jj720370\(v=ax.60\))

[(LVA) Vendor payment journal lines (modified form)](https://technet.microsoft.com/library/jj721419\(v=ax.60\))

[(LVA) Bank transactions (modified form)](https://technet.microsoft.com/library/jj839644\(v=ax.60\))

[Payment purpose codes (form)](https://technet.microsoft.com/library/aa587506\(v=ax.60\))

  


