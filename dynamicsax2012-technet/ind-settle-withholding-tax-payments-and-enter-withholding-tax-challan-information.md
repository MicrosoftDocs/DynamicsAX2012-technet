---
title: (IND) Settle withholding tax payments and enter withholding tax challan information
TOCTitle: (IND) Settle withholding tax payments and enter withholding tax challan information
ms:assetid: b6e8a9dd-c69e-43ea-b1fb-890193a12acf
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664827(v=AX.60)
ms:contentKeyID: 49386158
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (IND)
- india
- settle payments
- Settle TDS payments
- TDS challan
- TDS payments
---

# (IND) Settle withholding tax payments and enter withholding tax challan information [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Periodically, you must settle withholding tax payments with tax authorities. Complete the following procedures to settle withholding tax payments for the Tax Deducted at Source (TDS) and Tax Collected at Source (TCS) tax types and enter withholding tax challan information.

## Settle withholding tax payments

Complete the following procedures to settle withholding tax payments for a specific withholding tax settlement period.

### Make withholding tax payments available to settle

1.  Click **General ledger** \> **Periodic** \> **India withholding tax** \> **Withholding tax payment**.

2.  Select the withholding tax type to settle payments for.

3.  Select the Tax Account Number (TAN) and withholding tax period to settle payments for.

4.  Enter the starting date of the settlement period.

5.  In the **Transaction date** field, enter the posting date of the withholding tax settlement payment.

6.  In the **Withholding tax payment version** field, select one of the following options:
    
      - **Original** – Settle withholding tax payments for the first time for the selected settlement period.
    
      - **Latest corrections** – Settle withholding tax payments that were included on journal lines and that were posted in the settlement period since you last settled withholding tax payments for the selected period.

7.  Select the **Update** check box to make the withholding tax payments available in the **Settle open transactions** form, where you can select the transactions for settlement.

### Settle available withholding tax payments

1.  Click **General ledger** \> **Journals** \> **General journal**.

2.  In the **General journal** form, create a new journal or select an existing journal.

3.  Click **Lines** to open the **Journal voucher** form, where you can create journal lines.

4.  Click **New** to create a new journal line.

5.  In the **Account** field, select the TDS or TCS authority vendor to settle withholding tax payments with.

6.  Click **Functions** \> **Settlement** to open the **Settle open transactions** form, where you can view the TDS or TCS transactions that are available to settle for the tax authority vendor that you selected in step 5.

7.  To select a transaction and all lines in the transaction for settlement to the TDS or TCS authority vendor, select the **Mark** check box.
    
    To select only some of the lines for a transaction for settlement follow these steps:
    
    1.  Select a transaction.
    
    2.  Click **Withholding tax transactions**.
    
    3.  Select the **Mark** check box for only the lines to be settled.
    
    4.  Close the **Withholding tax transactions** form.
    

    > [!NOTE]
    > <P>After you select the transactions or lines to settle, the total amount to be settled to the tax authority vendor for the settlement period is displayed in the <STRONG>Amount to settle</STRONG> field in the <STRONG>Settle open transactions</STRONG> form.</P>



8.  Close the **Settle open transactions** form.

9.  In the **Journal voucher** form, select the line that you created in step 4.

10. On the **Payment fee** tab, select the **Fee ID** and **Currency** to use when delayed payments are made to the tax authority vendor and select the account that the fee must be deducted from.

11. On the **Tax information** tab, verify that the company information and withholding tax information is correct for the settlement.

12. Click **Post** \> **Post** to post the journal line.

## Enter withholding tax challan information

Before you can generate quarterly statements for TDS and TCS, you must enter challan information for transactions that are posted for settlement with a tax authority. For more information, see [(IND) Generate 26Q or 27Q quarterly statements for TDS](ind-generate-26q-or-27q-quarterly-statements-for-tds.md) or [(IND) Generate 27EQ quarterly statement for TCS](ind-generate-27eq-quarterly-statement-for-tcs.md).

1.  Click **General ledger** \> **Journals** \> **General journal**.

2.  Select the journal that you used to settle and post withholding tax transactions.

3.  Click **Lines**.

4.  Click **Withholding tax** \> **Challan information** in the **Journal voucher** form to enter the challan details for the transaction. The voucher number of the transaction is displayed in the **Voucher** field.

5.  If the withholding tax amount is not deposited by book entry, go to step 7.

6.  If the withholding tax amount is deposited by book entry, complete the followings steps and then go to step 10:
    
    1.  Select the **Deposited by book entry** check box.
    
    2.  Enter the **Transfer voucher number**.
    
    3.  Enter the payment date and additional text to include on the challan.

7.  Enter the challan number that is used to make the payment to the TDS or TCS authority vendor and then enter the payment date.

8.  Select the bank name to deposit the TDS or TCS amount that is payable to the TDS or TCS authority vendor in the **Bank name** field.
    

    > [!NOTE]
    > <P>You can set up bank accounts for the TDS or TCS authority vendor in the <STRONG>Vendor bank accounts</STRONG> form. For more information, see <A href="https://technet.microsoft.com/en-us/library/aa589805(v=ax.60)">Vendor bank accounts (form)</A>.</P>



9.  Enter the Basic Statistical Return (BSR) code of the bank in the **BSR code** field.

10. Close the form.

## See also

[(IND) Tax components (form)](https://technet.microsoft.com/en-us/library/jj664734\(v=ax.60\))

[(IND) Challan information (form)](https://technet.microsoft.com/en-us/library/jj677847\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

