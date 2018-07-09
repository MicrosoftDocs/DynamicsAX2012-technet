---
title: (JPN) Set up for bills of exchange
TOCTitle: (JPN) Set up for bills of exchange
ms:assetid: 6de3e247-e629-4043-8a70-d615b7558867
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711072(v=AX.60)
ms:contentKeyID: 49386485
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (JPN) Set up for bills of exchange [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use bills of exchange (BOEs) to make payments for items and services. A BOE is a specific draft or order that is received from a customer for payment. In Japan, the BOE order can be endorsed to vendors to make payments before the BOE goes to maturity. This process of endorsement is applicable for all the drafts in Accounts receivable, whether they are promissory notes or BOEs, because the only difference between a promissory note and a bill of exchange is that, for the former, manufacturers promise to pay the payees by themselves instead of requesting a third party to make the payment. For more information, see [Set up bills of exchange](set-up-bills-of-exchange.md).

You can perform the following tasks by using the endorsement process:

  - A BOE is endorsed to a vendor, and if the BOE amount is smaller than the target vendor invoice amount, you can make the partial payment through BOEs. Also, a BOE can be endorsed to multiple vendors.

  - The accounting journal is generated. The accounts payable is posted as debtor account, and the endorsed BOE is posted as creditor account.

  - The BOE is marked as **Endorsed** and posted as **Notes receivables** to a bridge account called endorsed BOE. An account is used as a bridge account when the BOE is endorsed but not matured.

  - You cannot settle the payment until the BOE goes to the maturity period, which is from the maturity date to the due date, according to generally accepted accounting principles (GAAP) in Japan. For more information, see [(JPN) Create and endorse a bill of exchange](jpn-create-and-endorse-a-bill-of-exchange.md).

  - Reverse the endorsement if the BOE is dishonored by non-acceptance, or when the endorsement date is entered incorrectly. For more information, see [(JPN) Reverse a bill of exchange](jpn-reverse-a-bill-of-exchange.md).

  - During settlement of endorsed BOEs, a bill of exchange can be settled by using the endorsement settled process. The accounting journal entry is posted as Endorsed BOE debtor account, and the BOE (Notes receivable) is posted as creditor account.

## Set up number sequence parameters for bills of exchange

1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  In the **Ledger and sales tax** area, in the **Bill of exchange** field, select BOE.

3.  In the **Endorse Bill of Exchange** field, select the posting profile for the BOEs that are endorsed and issued to a vendor.

4.  In the **Number sequences** area, select the number sequence code for the **Endorsed bill of exchange voucher** reference.

## Set up a customer posting profile

You can use the **Customer posting profiles** form to add a new posting profile, such as EBOE, and to maintain the summary account as Endorsed BOE. The selected summary account is used as a bridge account when the BOE is endorsed but not matured.

1.  Click **Accounts receivable** \> **Setup** \> **Customer posting profiles**.

2.  In the **Posting profile** field, enter EBOE. In the **Description** field, enter Endorse bill of exchange.

3.  On the **Setup** FastTab, click **Add** to create a new line.

4.  In the **Account code** field, select **All**.

5.  In the **Endorse account** field, select the BOE account.
    

    > [!NOTE]
    > <P>You must create a main account for Endorsed BOE in the <STRONG>Chart of accounts</STRONG> form.</P>



## See also

[(JPN) Accounts receivable parameters (modified form)](https://technet.microsoft.com/en-us/library/jj664964\(v=ax.60\))

[Customer posting profiles (form)](https://technet.microsoft.com/en-us/library/aa600572\(v=ax.60\))

[Draw a bill of exchange](draw-a-bill-of-exchange.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

